# 100 Days Of Code - Log

See [100DaysOfCode Tracking Google Sheet](https://docs.google.com/spreadsheets/d/1br3t1gGp6G0mQPgSHaLoZDLTmmth0QQRw8t4yEyHrUg/edit?usp=sharing) for additional tracking details.

### Day 1: Sat, 2018-05-05

* Setup [100DaysOfCode Repo](https://github.com/experimatt/100-days-of-code)
* Setup [Google Sheet](https://docs.google.com/spreadsheets/d/1br3t1gGp6G0mQPgSHaLoZDLTmmth0QQRw8t4yEyHrUg/edit?usp=sharing) for tracking
* Investigate OMG Transit [issues](https://gitlab.com/omgtransit/omgtransit/issues) for http => https redirect & better handling of geolocation/privacy errors ([Commit](https://gitlab.com/omgtransit/omgtransit/merge_requests/4/diffs?commit_id=fa2d9b2aa048d0e6632fbd23be392dd526a4cbb1))
    - Lighthouse audit shows
        1. slow load times
        2. geolocation should ask permission before requesting location
    - Branch: `mdecuir/fix-geolocation-errors`


### Day 2: Sun, 2018-05-06
* OMG Transit: Start adding tests to `list.spec.js` ([Commit](https://gitlab.com/omgtransit/omgtransit/merge_requests/4/diffs?commit_id=5300d3fd751ccad6642ddca9c9e8a95e0907727d))
* OMG Transit: Finished tests in `list.spec.js` ([Commit](https://gitlab.com/omgtransit/omgtransit/merge_requests/4/diffs?commit_id=07a2552bb339b669407840797764e81e8fcd0040))

### Day 3: Mon, 2018-05-07
* SICP: finished watching [SICP Lecture 1A](https://www.youtube.com/watch?v=2Op3QLzMgSY&index=1&list=PLB63C06FAF154F047&t=5s)
* OMG Transit: Refactored list component logic ([Commit](https://gitlab.com/omgtransit/omgtransit/merge_requests/4/diffs?commit_id=32d4c7cee20ab4a6c6e54d2cafb2afb7d0bac24b))

### Day 4: Tue, 2018-05-08
* SICP: started watching SICP Lecture 1B (10 minutes in)
* OMG Transit: Refactored map component logic & ripped out location updater ([Commit 1](https://gitlab.com/omgtransit/omgtransit/merge_requests/4/diffs?commit_id=6983cb8cfdd35197fe487f2d79247068b288d8ee), [Commit 2](https://gitlab.com/omgtransit/omgtransit/merge_requests/4/diffs?commit_id=f343a96baafda678f03e0c49764098eb9f4dcadf))
* Organized & facilitated Mpls Jr Devs #12 event

### Day 5: Wed, 2018-05-09
* SICP: continued Lecture 1B (37 minutes in)
* OMG Transit: Finished list spec, finished map component refactor, started adding map component spec ([Commit 1](https://gitlab.com/omgtransit/omgtransit/merge_requests/4/diffs?commit_id=f46063ac4a4e5c7aa7f3fd2abc01cfcd58376a9e), [Commit 2](https://gitlab.com/omgtransit/omgtransit/merge_requests/4/diffs?commit_id=461038cdf6ef9071a6f79db47e49b90d2d477563))

### Day 6: Thu, 2018-05-10
* OMG Transit: Handle ad blockers on the list view ([Commit](https://gitlab.com/omgtransit/omgtransit/merge_requests/4/diffs?commit_id=82efbee7625e175b996a67eea1369a28d97b4e37))

### Day 7: Fri, 2018-05-11
* OMG Transit: Add to map specs, fix error padding and merged MR in ([Commit 1](https://gitlab.com/omgtransit/omgtransit/merge_requests/4/diffs?commit_id=976d51791daeab55d5446c4a3cde1a67057e204d), [Commit 2](https://gitlab.com/omgtransit/omgtransit/commit/7e66045e42e5e898ac43d86e6e30aa238e694987), [MR](https://gitlab.com/omgtransit/omgtransit/merge_requests/4))

### Day 8: Sat, 2018-05-12
* OMG Transit: Add prettier ([Merge Request](https://gitlab.com/omgtransit/omgtransit/merge_requests/5/diffs))

### Day 9: Sun, 2018-05-13
* Mpls Jr Devs: Update navbar, setup folder structure, and initial structure/copy of the site ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/27))

### Day 10: Mon, 2018-05-14
* Mpls Jr Devs: Group hacking session. Style welcome section. ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/30))

### Day 11: Tue, 2018-05-15
* Mpls Jr Devs: Style contact section ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/31))

### Day 12: Wed, 2018-05-16
* Mpls Jr Devs: Make the menu functional ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/34))

### Day 13: Thu, 2018-05-17
* Mpls Jr Devs: Coordinated merging in other people's block ing PRs (no code written)

### Day 14: Fri, 2018-05-18
* Mpls Jr Devs: Update menu background color ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/37))

### Day 15: Sat, 2018-05-19
* Mpls Jr Devs: Style events section and add primary/secondary section styles ([WIP Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/39))

### Day 16: Sun, 2018-05-20
* Mpls Jr Devs: Finish styling and filling in events section ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/39))

### Day 17: Mon, 2018-05-21
* Mpls Jr Devs: Code of Conduct Modal/Collapse proof of concepts ([WIP Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/40))

### Day 18: Tue, 2018-05-22
* Mpls Jr Devs: Start styling & updating content of CoC ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/41))

### Day 19: Wed, 2018-05-23
* Mpls Jr Devs: Finish styling and updating content of CoC ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/41))

### Day 20: Thu, 2018-05-24
* Mpls Jr Devs: Move individual event data to json file ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/42))

### Day 21: Fri, 2018-05-25
* Mpls Jr Devs: Add individual Event component and start using it ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/42))

### Day 22: Sat, 2018-05-26
* Mpls Jr Devs: Use new Event component for past events ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/42))

### Day 23: Sun, 2018-05-27
* Mpls Jr Devs: Deploy new site to github pages; Start updating readme. ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/44), [WIP Pull Request(https://github.com/mplsjrdevs/mplsjrdevs/pull/45))

### Day 24: Mon, 2018-05-28
* Mpls Jr Devs: Hide register button if > 2 weeks out ([Pull Requst](https://github.com/mplsjrdevs/mplsjrdevs/pull/49))

### Day 25: Tue, 2018-05-29
* Mpls Jr Devs: Design tweaks based on Adriana's feedback ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/50))

### Day 26: Wed, 2018-05-30
* Mpls Jr Devs: Add favicon & dynamically show different menus for mobile/desktop ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/50))

### Day 27: Thu, 2018-05-31
* Mpls Jr Devs: Make mobile menu pass the thumb test ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/50))

### Day 28: Fri, 2018-06-01
* Mpls Jr Devs: Add faces to community section ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/51))

### Day 29: Sat, 2018-06-02
* Mpls Jr Devs: Add carousel placeholder to ommunity section ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/51))

### Day 30: Sun, 2018-06-03
* Mpls Jr Devs: Add community members data structure, make clicking on faces work ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/51))

### Day 31: Mon, 2018-06-04
* Mpls Jr Devs: Add text overlay on image hover ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/51))

### Day 32: Tue, 2018-06-05
* Mpls Jr Devs: Add font awesome and start using it ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/51))

### Day 33: Wed, 2018-06-06
* Mpls Jr Devs: Make the carousel work! ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/51))

### Day 34: Thu, 2018-06-07
* Mpls Jr Devs: Fix carousel height, styling, and randomize order by default ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/51))

### Day 35: Fri, 2018-06-08
* Mpls Jr Devs: Tidy up & merge community section; review Chelsey's PR ([Pull Request](https://github.com/mplsjrdevs/mplsjrdevs/pull/51))

### Day 36: Sat, 2018-06-09
* Setup Microsoft Surface for development use & got Mpls Jr Devs running locally

### Day 37: Sun, 2018-06-10
* TC Pizza Bracket: Firebase & npm bracket package research

### Day 38: Mon, 2018-06-11
* TC Pizza Bracket: Setup new repo w/ create-react-app and firebase ([Repo](https://gitlab.com/experimatt/tc-pizza-bracket))

### Day 39: Tue, 2018-06-12
* Mpls Jr Devs: Update event schedule & fix day-of event display; Organize & facilitate Mpls Jr Devs #13

### Day 40: Wed, 2018-06-13
* TC Pizza Bracket: Setup firebase hosting & add placeholder content to site

### Day 41: Thu, 2018-06-14
* Mpls Jr Devs: Help Chelsey merge her contact PR in ([PR](https://github.com/mplsjrdevs/mplsjrdevs/pull/52))

### Day 42: Fri, 2018-06-15
* Mpls Jr Devs: Merge Chelsey's bio; Update icons in contact section ([PR](https://github.com/mplsjrdevs/mplsjrdevs/pull/55))

### Day 43: Sat, 2018-06-16
* Mpls Jr Devs: Contact section styling and wrapping ([PR](https://github.com/mplsjrdevs/mplsjrdevs/pull/55))

### Day 44: Sun, 2018-06-17
* TC Pizza Bracket: Add bracket & start building data structure ([WIP MR](https://gitlab.com/experimatt/tc-pizza-bracket/merge_requests/1)
    - [Minnesota Monthly pizza bracket](http://www.minnesotamonthly.com/Food-Drink/Pizza-Madness/) starts on 6/18; Halting working on TC Pizza Bracket

### Day 45: Mon, 2018-06-18
* OMG Transit: Update stops, packages, and rename actions for clarity ([WIP MR](https://gitlab.com/omgtransit/omgtransit/merge_requests/6))

### Day 46: Tue, 2018-06-19
* OMG Transit: Rename reducers for clarity, add bike station actions ([WIP MR](https://gitlab.com/omgtransit/omgtransit/merge_requests/6))

### Day 47: Wed, 2018-06-20
* OMG Transit: Load niceride station & availability ([WIP MR](https://gitlab.com/omgtransit/omgtransit/merge_requests/6))

### Day 48: Thu, 2018-06-21
* OMG Transit: Include nicerides when getting nearby stops ([WIP MR](https://gitlab.com/omgtransit/omgtransit/merge_requests/6))

### Day 49: Fri, 2018-06-22
* OMG Transit: Add nicerides to map ([WIP MR](https://gitlab.com/omgtransit/omgtransit/merge_requests/6))

### Day 50: Sat, 2018-06-23
