---
title: Guide for Shepherds
---

We use the term "shepherd" for the person ultimately keeping an eye on making forward progress on a particular text. They don't have to do all the work or even the majority of the work, they just need to be willing to help move things along.

While we will probably expand things to include translation alignment, postagging, treebanking, sembanking, and more at some point, the initial milestones for a text are:

1. get a clean version with a referencing scheme in our format
2. lemmatise the text and resolve any ambiguities in the lemmatisation

## Getting Started

* make sure you are in <https://greek-learner-texts.slack.com/>
* discuss the text you'd like to shepherd in the `#potential-projects` channel
* if you can't get anyone else interested, you can still proceed solo but better if you have a few people that can help
* make sure you are listed under "Who We Are" on <https://github.com/greek-learner-texts/greek-learner-texts.github.io/blob/master/index.md> (send a pull-request)
* start a new channel in Slack and invite anyone who expressed an interest (you can also advertise it in `#general`)
* start a github repo for it by going to <https://github.com/greek-learner-texts/text-repository-template> and clicking the green button "use this template"
* add a `greek-texts` topic tag to your repo
* add the repo in the appropriate YAML file in <https://github.com/greek-learner-texts/greek-learner-texts.github.io/tree/master/_data/texts> (send a pull-request)
* `/github subscribe` to the repo in the `#github` channel on Slack

## Putting Together the Initial Text

* check Scaife (<https://scaife.perseus.org/library/>) to see if the text you want to work on is already in Perseus/OGL
* if so, find the repo in GitHub and get the relevant TEI XML
* if not, you'll need to track down an openly-licensed version (either public domain / CC0, cc-by, or cc-by-sa)
* there may be quite a lot of correction to do (see [Preparing an Open Apostolic Fathers](https://jktauber.com/2018/11/01/preparing-open-apostolic-fathers/) for what we did for the Apostolic Fathers)
* there may be scans available on archive.org or elsewhere or you may even need to scan it yourself. If you need any help with OCR, just ask in the `#ocr` channel
* [James needs to expand this a lot but] get it in our standard "reference text-part" form, one line per referenceable text-part
* set up a `text-validator.toml` and validate the text with `text-validator` (preferably set up a GitHub Action to do this on all commits and PRs)

## Lemmatising the Text

* [James still to write]
