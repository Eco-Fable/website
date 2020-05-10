---
title: React Lifecycle Hooks
path: react-lifecycle-hooks
date: 2020-05-08
tags: ['coding', 'react', 'frontend']
---

In class components, there are quite a few lifecycle hooks that can be used to update your components depending on data logic and conditions.

I'm going to describe the ones I've come to use so far with examples. I'll update this post as I use more in my projects.

## componentDidUpdate

Invoked after the component updates.

## componentWillUpdate

Whether the component updates.

## shouldComponentUpdate

`shouldComponentUpdate(nextProps, nextState)`


## componentDidMount

Invoked after the component mounts.

## componentWillMount

Whether the component will mount.

## componentWillUnmount

Whether the component will unmount.



> Any child component of the component depending on this lifecycle hook, won't update unless the parent component updates.

[Found a typo or problem? Edit this page.](https://github.com/Dana94/website/blob/master/blog/2020-05-15-react-lifecycle-hooks.md)
