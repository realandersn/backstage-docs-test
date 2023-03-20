# Tabs

TechDocs supports the [PyMarkdown](https://facelessuser.github.io/pymdown-extensions/extensions/tabbed/) extensions that let you create tabs. Tabs group and organize content under clickable labels, horizontally across the page.

You may want to use tabs to help save vertical space on a page, to make side-by-side comparisons, or to organize text or code in a way that conveys a sense of cause and effect.

## Basic syntax and example

Start a tab with `===` followed by a quoted tab title and then the text or code associated with each tab. The syntax for a simple set of tabbed text looks like this:

```
=== "Tab 1"
    Lorem ipsum dolor sit amet.

=== "Tab 2"
    Consectetur adipiscing elit, sed do eiusmod tempor.

=== "Tab 3"
    Ut enim ad minim veniam.
```

When published, Backstage displays tabbed content like this:

=== "Tab 1"
    Tab 1, lorem ipsum dolor sit amet.

=== "Tab 2"
    Tab 2, consectetur adipiscing elit, sed do eiusmod tempor.

=== "Tab 3"
    Tab 3, ut enim ad minim veniam.


## Text and code example

This example groups some plain text and a code fragment under 2 tabs.

```markdown
=== "Tab 1"
    ```txt
    Plain text (.txt) formatted in a tab.
    Here's a second line of text.
    ```
=== "Tab 2"
    ```xml
    XML code in a tab.
    <parent>
      <groupId>com.spotify</groupId>
      <artifactId>root</artifactId>
      <version>106</version>
    </parent>
    ```
```

When published, Backstage displays tabbed content like this:

=== "Tab 1"
    ```txt
    Plain text (.txt) formatted in a tab.
    Here's a second line of text.
    ```
=== "Tab 2"
    ```xml
    XML code in a tab.
    <parent>
      <groupId>com.spotify</groupId>
      <artifactId>root</artifactId>
      <version>106</version>
    </parent>
    ```

For more information and examples, refer to the PyMarkdown documentation linked above in the page introduction.
