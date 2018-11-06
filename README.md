# Reusable Storyboard
This project demos how to create and reuse a view via a Storyboard file:
1. Create view to be reused in main storyboard file. Use Xcode refactor tool to refactor this view into another storyboard file and name appropriately - see [Reusable.storyboard](./ReusableStoryboard/ReusableStoryboard/Base.lproj/Reusable.storyboard)
1. Create container views that point to a Storyboard reference in Interface Builder
1. Click on the Storyboard reference and add the name of the Storyboard file

## Pros
- Can reuse View defined in Storyboard files

## Cons
- Cannot view reused Storyboard in place
- Cannot customise the reused view in the place of reuse. For example see [Main.storyboard](./ReusableStoryboard/Base.lproj/Main.storyboard) and note that there is no way to add subviews.