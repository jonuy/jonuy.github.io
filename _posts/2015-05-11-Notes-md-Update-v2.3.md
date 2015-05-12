---
layout: post
title: Notes.md Update v2.3
---

The [Notes.md](https://play.google.com/store/apps/details?id=com.jonuy.notesmd) updates are starting to come a little less frequently and the baby's become a lot more mobile. I wouldn't say the two are not related...

The updates in version 2.3 are styling related - one's a feature and one's a bug fix.

#### Notebook Colors
Previously, it was difficult to differentiate notes from one another in the main list view. Though now, if you use notebooks, you can set different colors to each while will help distinguish notes in one notebook from those in another.

<img src="/images/notes-md/v23-notebookcolor1.png" alt="v23-notebook-color-1" style="width:33%">
<img src="/images/notes-md/v23-notebookcolor2.png" alt="v23-notebook-color-2" style="width:33%">

#### Lollipop Shadows
Only until my phone got the Lollipop update did I notice that UI was broken for you Android 5.0 users. Sorry 😬. It basically stems from me using the CardView support widget and not setting `card_view:cardUseCompatPadding="true"`. It should be fixed now. I'm using a bunch of emulators on different versions with [Genymotion](https://www.genymotion.com) now which should ease the pain of personally testing across several versions of Android.