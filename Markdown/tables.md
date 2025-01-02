# Create Tables

Creating tables doesn't require you to provide spacings so you can focus on the content not the dimensions of the table.

## Simple Table

```markdown
| Heading1 | Heading2 | ... | Heading n| # First line consided as Heading
| ------ | ---- | ---- | ---- | # Give 3 or greater than 3 '-' to seperate rows
| Row1-Col1 | Row1-Col2 | ... | Row1-Col n |
| Row2 -Col1 | Row2-Col2 | ... | Row2-Col n|
```

The above code renders as following table:

| Heading1 | Heading2 | ... | Heading n|
| ------ | ---- | ---- | ---- |
| Row1-Col1 | Row1-Col2 | ... | Row1-Col n |
| Row2 -Col1 | Row2-Col2 | ... | Row2-Col n|

## Table alignment

```markdown
| Left alignment | Center alignment | Right alignment |
| :--- | :---: | ---: | # ":" defines alignment
| Left | Center | Right |
```

The above code renders as following table:

| Left alignment | Center alignment | Right alignment |
| :--- | :---: | ---: |
| Left | Center | Right |

## Code in Table

```markdown
| Code in table |
| --- |
| `Code`| # Give "`" for code
```

The above code renders as following table:

| Code in table |
| --- |
| `Code`|

## Multi paragraph in Table

```markdown
| Single Paragraph | Multiple Paragraphs |
|---|---|
| First Line | First Line </br> Second Line | # </br> breaks the line
```

| Single Paragraph | Multiple Paragraphs |
|---|---|
| First Line | First Line </br> Second Line |
