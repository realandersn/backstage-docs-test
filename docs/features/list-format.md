# List Formatting

Start here for some basic tips about creating lists in Markdown. Just one important thing first: keep in mind that all lists must be preceded by an empty line. 

## Numbered lists

A numbered list (or ordered list) automatically numbers each list item. To create a numbered list, start each list item with `1.` and let Markdown do the rest.

**Syntax:**

```markdown
1. Numbered item
1. Numbered item
1. Numbered item
```

**Example:**

1. Numbered item
1. Numbered item
1. Numbered item

## Bullet lists

A bullet list (or unordered list) puts round marks in front of each list item. To create a bullet list, start each list item with `-` and let Markdown do the rest.

**Syntax:**

```markdown
- Bullet item
- Bullet item
- Bullet item
```

**Example:**

- Bullet item
- Bullet item
- Bullet item

## Nested lists

A nested list contains numbered or bulleted sub-lists. To nest a list, indent 4-spaces wherever you want to start the new list.

**Syntax:**

```markdown
1. Numbered item
1. Numbered item
    - Nested bullet, 4-space indent
    - Nested bullet, 4-space indent
1. Numbered item
```

**Example:**

1. Numbered item
1. Numbered item
    - Nested bullet, 4-space indent
    - Nested bullet, 4-space indent
1. Numbered item

## Aligning content in a list

Sometimes, you may have to put a lot of information under a list item. When you need to add extra text, code, or images, indent 4-spaces to keep this content aligned with your list items.

### Text alignment

Here's an example of aligning text in a list.

**Syntax:**

The 4-space indented line isn't aligned with the second bullet, but they will be aligned in the generated docs.

```markdown
1. First item
1. Second item with aligned filler text.
    
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur lacinia iaculis tellus eu porttitor. Sed ultricies arcu sapien, eget pharetra metus convallis eget. Morbi scelerisque quis orci viverra volutpat. Etiam condimentum ex imperdiet accumsan lobortis. Aenean luctus erat vel laoreet efficitur.

1. Third item
```

**Example:**

1. First item
1. Second item with aligned filler text.
    
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur lacinia iaculis tellus eu porttitor. Sed ultricies arcu sapien, eget pharetra metus convallis eget.

1. Third item

### Images

Here's an example of aligning images in a list:

**Syntax:**

Put a line break between your list items and the image.

```markdown
- Bullet item
- Bullet item

    ![my_image](../img/image4.png)

- Bullet item
```

**Example:**

- Bullet item
- Bullet item

    ![test_image](../img/image4.png)

- Bullet item

This works with numbered lists too.

1. Numbered item
1. Numbered item

    ![my_image](../img/image4.png)

1. Numbered item

### Spacing

A long list can look crowded. Add a hard return to your list to open it up and make it easier to read.

**Syntax:**

```markdown
- Bullet item
<!--- Hard return adds padding between the bullets --->
- Bullet item
- Bullet item
```

**Example:**

- Bullet item

- Bullet item
- Bullet item

## Lists in documentation

See the Lists section in the _Spotify Technical Writing Handbook_. It provides advice on how to use lists in your written work.

## Other resources

An online search using the phrase "lists in Markdown" will return a lot of helpful sites and information. Here are a few you can try right now:

- GitHub Guide: [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- Markdown Guide: [Basic Syntax](https://www.markdownguide.org/basic-syntax/)
- Commonmark: [Interactive Markdown list tutorial](https://commonmark.org/help/tutorial/10-nestedLists.html)
