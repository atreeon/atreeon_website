---
title: Flutter's TextField and TextFormField Events
date: 2022-11-28
tags:
  - posts
  - flutter
layout: layouts/post.njk
---
# Flutter's TextField and TextFormField Events

## Intro
`TextField` and `TextFormField` have a number of events that fire when the user does interacts.  Here I'll explain each event and what they do.

## `TextField`
### `onChanged`
When the text inside the textbox is changed at all by the user.  The event fires after any small change without losing focus.

### `onSubmitted`
Is triggered when a user presses carriage return on a website or presses the 'done' box on a mobile (or find, search etc)

### `onEditingComplete`
Same as `onSubmitted` but the value isn't available to the user.

<https://dartpad.dev/?id=55b83253540890dad410349224e30736>

## `TextFormField`
### `onSaved`
The code inside the `onSaved` event is called when the form specified in the `TextFormField` is saved.  This happens by calling _`formKey.currentState!.save()` and usually happens on a button press at the bottom of a form.

### `onFieldSubmitted`
Same as `onSubmitted` in a TextField

### `onChanged`
Same as `onChanged` in a TextField

### `onEditingComplete`
Same as `onEditingComplete` in a TextField

[dartpad](https://dartpad.dev/?id=9bcb0ebec0c01142fc7e530c46f94e56")

More info:
<https://stackoverflow.com/questions/63690311/flutter-textfield-difference-between-onedittingcomplete-and-onsubmitted>