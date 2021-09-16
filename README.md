# UX CSS Lib
Ux CSS Lib is build upon Bootstrap 5.0.  

It's meant to be used with ux projects so it is built to work with fast prototyping philosophy.  

# Top-level semantic classes (aka components)
When you are fast prototyping a project you don't want inside all details of your css, maybe you just need a top-level class that describe your component.

For example you want to do something like this:  

```
div
    .className sidebar
    ul
        li 'item 1
        li 'item ...
```

Instead of:

```
div
    .className sidebar
    ul
        .className sidebar-group
        li 'item 1
            .className sidebar-item
        li 'item ...
            .className sidebar-item
```

So you rely on the structure of your html.