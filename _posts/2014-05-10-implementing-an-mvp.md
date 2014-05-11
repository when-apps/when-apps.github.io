---
layout: post
title:  "Implementing an MVP"
date:   2014-05-10 22:00:00
---

Only 51 hours passed between the [first commit](https://github.com/when-apps/whendid-ios/commit/ff296a75b47c1f55bdf1ecc300ff262053eff474) and the [last commit](https://github.com/when-apps/whendid-ios/commit/26be51d9ac224816df4ab2573355a6d80d627218) for the *When did* MVP.

I started by writing down the idea in my notebook and then later on my [product repository](https://github.com/jonmagic/product/tree/master/when_did).

Armed with a list of three features (add timer, show timer counting, remove timer) I proceeded to break each feature down into small easily shippable pieces. Those turned into the following commits:


1. [Implement a table view (backed by fake data)](https://github.com/when-apps/whendid-ios/commit/5399e7f70960167b7fad1dcb1fa1783e0f8593e7).
1. [Implement a model for storing the timer in Core Data](https://github.com/when-apps/whendid-ios/commit/6fc785c5df00d3fd3a08e5ddd168a3694b473e95).
1. [Implement a form for adding a timer](https://github.com/when-apps/whendid-ios/commit/8930ba869157bfc16c40e7ada25f960ad9aae56d).
1. [Display saved and new timers in table](https://github.com/when-apps/whendid-ios/commit/b686866b4a5de15965880bce50eb63d3ce08238f).
1. [Show seconds since timer started and live update](https://github.com/when-apps/whendid-ios/commit/f694eaa97936811c8be5f50668d323d406d2271e).
1. [Align text & change font sizes to be more readable](https://github.com/when-apps/whendid-ios/commit/a50e5535859a447baee33bdd6579327b787e08a2).
1. [Add ability to set timer start time](https://github.com/when-apps/whendid-ios/commit/736167fb29612974a745bc9fb634859401a1a157).
1. [Refactor to be more maintainable](https://github.com/when-apps/whendid-ios/commit/6347bfc42a0e53bd301bdf9e9cf6bd19d73c5fc1).
1. [Sort timers most recent to oldest](https://github.com/when-apps/whendid-ios/commit/ddeea3e24f35e22e8778273912d6b4d15783f391).
1. [Add timer edit screen](https://github.com/when-apps/whendid-ios/commit/8f9ef8819777dbb39d1ed4687f994ba02af5c3f8).
1. [Add delete timer screen with confirmation step](https://github.com/when-apps/whendid-ios/commit/668c1530adb762cbcf375ba608b9529e904b23bf).
1. [Show easy to read distance in time](https://github.com/when-apps/whendid-ios/commit/ed7dff257f628a1ba3a2f47691506520dce65161).
1. [Add icons!](https://github.com/when-apps/whendid-ios/commit/062356138a9be9caed1e39b958753a755e10701d).

When building an MVP I try to concentrate on:

1. Saying no to almost every feature idea. No no no.
1. Clearly defining core features. For example: add timer, show timer counting, remove timer.
1. Breaking each feature down into many small easily shippable steps.
1. Implementing.
1. Repeating 3 & 4 until core features all work.

Once I had the MVP finished I submitted the app to the Appstore!
