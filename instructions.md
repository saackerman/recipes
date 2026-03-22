# Recipe Markdown Format Guide

This guide explains the formatting conventions used in recipe files in this repository.

---

## File Structure

Each recipe file follows this structure:

1. **Title** – An H1 heading with the recipe name
2. **Yield** – Italicized line (e.g., *Makes approximately 25 balls*)
3. **Horizontal Rule** – `---` used as a section divider
4. **Ingredients Table** – An H2 section with a markdown table
5. **Instructions List** – An H2 section with a numbered list
6. **Original Video Link** – A footer credit link

---

## Ingredients Table

Use a markdown table with two columns: `Ingredient` and `Amount`.
Optional notes can be italicized inside the cell using `*(note)*`.

```markdown
| Ingredient | Amount |
|---|---|
| Protein Powder (Reese's flavor recommended) | 120g |
| Semi-Sweet Chocolate Chips *(for topping)* | 60g |
```

---

## Instructions List

Each step uses a **bold label** followed by a description.
Each step also includes a ⏱ timestamp hyperlink to the corresponding moment in the original video.

The timestamp icon is rendered using the HTML entity `&#x23F1;` (⏱), linked to a YouTube URL with a `&t=` parameter (time in seconds).

```markdown
1. **Step Name:** Description of the step. [&#x23F1;](https://www.youtube.com/watch?v=VIDEO_ID&t=SECONDS)
```

**Example:**
```markdown
1. **Mix the Base:** Combine all dry and wet ingredients in a large bowl. [&#x23F1;](https://www.youtube.com/watch?v=YmYYrEsNLMg&t=15)
```

---

## Footer Credit

At the bottom of the file, include an italicized link crediting the original video source:

```markdown
*[Original Video: Your video title here](https://www.youtube.com/watch?v=VIDEO_ID)*
```

---

## Full Example

See [HighProteinReeseSnackBalls.md](HighProteinReeseSnackBalls.md) as a reference.
