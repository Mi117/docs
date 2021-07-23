---
Title: "invert"
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Images"
  - "Functions"
  - "Colors"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-css"
  - "https://www.codecademy.com/learn/paths/front-end-engineer-career-path"
  - "https://www.codecademy.com/learn/paths/full-stack-engineer-career-path"
---

## Definition

CSS filter function that inverts the colors of an element.

## Syntax

```css
filter: invert(<value>);
```

where a required `<value>` can be one of the following:

- Number value: `0`, `.4`
- Percentage value: `100%`, `50%`

**Note:** A value of `0` and `0%` will leave image unchanged. Values of `1` and `100%` will result in picture completely inverted. Value defaults to `1` and negatives values are not allowed.

## Example 1

Invert an image `25%`:

```css
.banner-image {
    filter: invert(25%);
}
```
