# Week 8 General AI Fluency Capstone — Send the Link

**Owner:** Shaik Fiona Ali  
**Next case study:** Google Search Ranking & Discoverability Capstone — refresh opportunity scoring  
**Portfolio:** https://fiona-ali.github.io/  
**Published paper:** https://fiona-ali.github.io/flyrank-capstone.html  
**Repository:** https://github.com/Fiona-ali/flyrank-ml-internship  
**Reminder:** 23 November 2026, 7:00 PM IST

## Keep the portfolio build context

Keep Fiona's existing portfolio Claude Project, including its voice, stack notes, and identity kit, as the drafting context for future case studies. The project supports the writing process; facts and metrics in the published case must still be checked against the source paper and repository.

## Where the next case will go

Add one new project card inside the existing Work / Selected Projects section (id: projects) of index.html, below the current featured subject-tracking project. The card will be titled Google Search Ranking & Discoverability Capstone and will link to the public research paper. The paper remains the detailed write-up; the card will give a short case summary and link to the reproducible notebook in Fiona's internship repository.

Keep the current SFA.EXE visual style. Do not imply the portfolio page is the deployed model: the deliverable is a research paper and offline analysis, not a production ranking service.

## Three-beat case outline

**Problem.** Editors need a practical way to decide which content items to inspect first. A ranking can help make a review queue, but a historical performance signal does not prove that an item will decline in the future or benefit from a refresh.

**What I did.** I used the anonymized 30,000-row starter extract and compared a metadata-based Logistic Regression ranking with the Week-4 freshness-and-volume rule. I kept whole client groups out of training, evaluated both rankings on the same held-out clients, and documented the proxy target, data limits, and comparator caveat in the paper.

**What came of it.** On the reported held-out split, the model's Precision@50 was 0.720, versus 0.380 for the rule and a 0.577 proxy base rate. This supports further testing of a human-review shortlist on this snapshot only. It does not show future decline, prove that refreshing a page works, or justify automatic edits.

## Steps to add the case

1. Reopen flyrank-capstone.html and the capstone notebook to confirm the title, method, results, and limitations against the submitted versions.
2. Add the project card to the existing projects section in index.html; link to the paper and the capstone notebook in Fiona's repository.
3. Use the three beats above, preserving the 30,000-row extract, client-held-out evaluation, and Precision@50 context. Keep the outcome explicitly directional.
4. Check every new link and preview the card on desktop and a phone-sized viewport. Confirm it fits the existing portfolio style.
5. Publish the portfolio update and compare the live card and links with the committed source.

## Reminder evidence

An enabled reminder titled Add FlyRank capstone case is scheduled for 23 November 2026 at 7:00 PM India time. Its instruction is to add the Search Intelligence capstone as a portfolio case, use the problem / what I did / what came of it structure, link the deployed paper and internship repository, and verify claims against the accepted final results. The reminder was checked as active on 19 November 2026.

## Source and claim limits

The case outline is based on Fiona's public paper at https://fiona-ali.github.io/flyrank-capstone.html and the corresponding capstone work in https://github.com/Fiona-ali/flyrank-ml-internship. Keep the paper's limitations with the case: the label is a trailing comparison proxy, results are from one fixed grouped split, the rule uses an overlapping 90-day impression total, and no causal refresh effect or future performance was tested. Do not state that a FlyRank graduate badge has been issued; its official verification link was not available in the portfolio notes checked on 16 November 2026.
