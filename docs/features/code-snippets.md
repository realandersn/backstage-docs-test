# Code snippets

To format code or text into its own distinct block, use triple backticks. This gives a nice grey box and puts the code in code format.

Syntax highlighting is provided through the use of the [Highlight](https://squidfunk.github.io/mkdocs-material/setup/extensions/python-markdown-extensions/#highlight) extension. To use it add the code language after the opening backticks. The [following languages](https://pygments.org/languages/) are supported.  Make sure the opening and closing backtick sequences are each at the start of a new line.

````markdown
```yaml
the::real::deal:
  some_key:
    address_cmd: 'hostname -I | cut -d" " -f1'
```
````

```yaml
the::real::deal:
  some_key:
    address_cmd: 'hostname -I | cut -d" " -f1'
```

For inline code and file names, fence with single backticks like `` `this` ``.

### Highlight lines in code snippet

To highlight specific lines of your code snippet you can add `hl_lines` to it. 

````markdown
```yaml hl_lines="1 3"
the::real::deal:
  some_key:
    address_cmd: 'hostname -I | cut -d" " -f1'
```
````

```yaml hl_lines="1 3"
the::real::deal:
  some_key:
    address_cmd: 'hostname -I | cut -d" " -f1'
```
