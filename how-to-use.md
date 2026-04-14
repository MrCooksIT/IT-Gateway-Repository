---
layout: page
title: How to Use This Resource
permalink: /how-to-use/
nav_order: 2
---

# How to Use This Resource

IT Gateway is organised by **IT concept**, not by grade. Each topic page shows how the concept builds from Grade 10 through to Grade 12 in one place.

## Navigation

- **Side menu** — shows all six CAPS topics plus Exam Preparation and Grade 8–9 resources
- **Search bar** — type any keyword to find content quickly
- **Links within pages** — concepts link to related topics

## For learners

- Use the side menu to find the topic you are studying
- Each topic page explains what is covered at Grade 10, 11, and 12
- Look for the **Practice Questions** section at the bottom of each page
- Use the **Exam Preparation** section before tests and exams

## For Grade 8 and 9 learners

Go to [Grade 8 and 9 Resources](/grade-8-9/) for revision pages and practice questions aligned to your tests.

Your full curriculum content is on [CodeHS](https://codehs.com).

## Using with Google Classroom

This resource works alongside Google Classroom:
- Your teacher will link specific pages to assignments
- Submit your work through Google Classroom as usual

---

## Markdown quick reference

This is for adding or editing content. You don't need this as a learner.

### Basic formatting

```
**Bold text**
_Italic text_
~~Strikethrough~~
```

### Headings

```
# Heading 1 (page title)
## Heading 2 (main section)
### Heading 3 (sub-section)
```

### Lists

```
- Bullet item
- Another item

1. Numbered item
2. Another item
```

### Tables

```
| Column 1 | Column 2 |
|---|---|
| Row 1 data | More data |
| Row 2 data | More data |
```

### Code blocks

Use triple backticks with the language name:

````
```sql
SELECT * FROM Students WHERE Grade = 12;
```
````

````
```pascal
writeln('Hello World');
```
````

### Note and highlight callouts

```
{: .note }
This appears as a blue note box.

{: .highlight }
This appears as a yellow highlight box.
```

### Links

```
[Link text](./relative-page)
[Link text](/absolute-path/page)
```

### Adding a new page

1. Copy `_templates/concept-page.md` or `_templates/exam-prep-page.md`
2. Rename the file (use lowercase, hyphens instead of spaces: `my-new-topic.md`)
3. Put it in the correct topic folder
4. Update the `title:` and `parent:` in the frontmatter at the top
5. Write your content below the `---` line
