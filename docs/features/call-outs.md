# Notes, tips, info, and warnings

TechDocs supports [Admonition extensions](https://squidfunk.github.io/mkdocs-material/reference/admonitions/). These extensions let you create separate notifications/call-outs in your documentation.

## Syntax

To create a notification, use !!!, add a notification title (Warning, Tip, Note, etc.), and indent the first line of the text with 4 spaces. Here's an example:

```
!!! Note
    This creates a notification/call-out block in your text.
    The result is not shown in your editor. Techdocs styles
    this during the build.
```

Note that if you use prettier or perform other code formatting on markdown at save-time or commit-time, indentation may be lost and your notifications will lose their formatting. If you encounter this, you may want to configure your code formatter to ignore markdown files or ignore the `/docs` folder. If you use prettier, you could wrap your call-outs like the following:

```
<!-- prettier-ignore-start -->
!!! Note
    The comments above and below ensure prettier ignores this.
<!-- prettier-ignore-end -->
```

## Usage and types

Use call-outs/notifications sparingly. The text should be concise and contain 1-3 sentences at most. If you use a lot of call-outs, or if a notification is very long,
put that information into its own section.

Technical writing supports 4 notification types. See below for descriptions and guidance on how to use each one.  

### Note

A note is a mild warning. It alerts the reader to something important, but not catastrophic.

!!! Note
    The information in a note is optional. It tells the reader to pay attention because something bad may or may not happen if they ignore a note.

### Tip

A tip provides the reader with some type of helpful workflow, steps, or process information. Nothing bad should happen if the reader ignores a tip.

!!! Tip
    The information in a tip is optional. Use it to help make the reader's life easier if they pay attention to it. But, they can keep doing things the hard way if they want to.

### Info

An info call-out provides general information, background, or context. It's similar to a tip but shouldn't include procedure or process help like that notification type.

!!! Info
    The information in an info call-out is optional. Ignoring it should not affect workflow or cause a problem. However, reading it may put someone on the path to enlightenment.

### Warning

A warning contains critical information. It conveys a sense of urgency and indicates that something awful will happen if the reader fails to pay attention to your message. This is the most dire, alarming notification you can put in your documentation.

!!! Warning
    The information in a warning is a hard requirement. Ignoring a warning collapses the time-space continuum and we cease to exist. Either that or someone on PagerDuty will have to deal with it.
