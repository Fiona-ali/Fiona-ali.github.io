# Make It Do Something — Feature Explainer

## What I built
I added one live feature to my portfolio: a small task queue demo. A visitor can add a sample task, choose normal or high priority, mark it complete, or remove it. The list stays in that browser so the demo still has its tasks after a refresh.

## What a backend is
A backend is the part of an app that runs on a server. It can receive requests, apply rules, and save data to a shared database. This demo does not use a backend because it does not need to send a task anywhere.

## How the data flows
1. The visitor types a task and chooses a priority in the page.
2. JavaScript in the browser checks the input and adds the task to the list.
3. The browser saves that list in its own local storage.
4. When the page opens again in the same browser, the code reads the saved list and draws it.
5. Marking a task complete or removing it updates the same browser-local list.

No task is sent to me or to a server. Clearing this browser's site data removes the saved demo list.

## How I checked it
I tested the live page by adding a sample task, refreshing the page to check that it remained, marking it complete, and removing it. Those actions exercise the feature from input through browser storage and back to the rendered list.
