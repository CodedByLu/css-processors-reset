# Modern CSS Reset (Multi-Processor Version)

A modern, lightweight CSS reset designed to give your project a clean and consistent foundation across all browsers. All versions contain the same reset logic, written in the syntax of each processor. This reset draws inspiration from [Andy Bell’s Modern CSS Reset](https://piccalil.li/blog/a-modern-css-reset/) and extends it with several improvements such as:

- better focus visibility for accessibility
- smooth scrolling
- consistent media defaults
- normalized tables and `<hr>` styling
- improved text wrapping and layout safety
- pointer cursor normalization
- root stacking context for modern frameworks

This package includes versions for all major CSS processors:

- **reset.css**
- **reset.less**
- **reset.sass**
- **reset.scss**
- **reset.styl**

Use whichever matches your workflow.

---

## 💡 Why This Reset Exists

Browsers apply their own default styles (margins, line-heights, borders, spacing, etc.) which differ across engines.
This reset removes inconsistencies and sets predictable, modern defaults so you can:

- build layouts faster
- avoid browser differences
- gain full control over design
- improve accessibility and text rendering

It is intentionally minimal and does **not** overwrite elements with design decisions — only normalizes them.

---

## How to Use

Include it at the very top of your main stylesheet, before any other CSS:

```html
<link rel="stylesheet" href="./reset.css" />
```

Or, if you’re using a bundler or preprocessor:

```css
@import "./reset.css";
```

```less
@import "./reset.less";
```

```sass
@import ./reset.sass
```

```scss
@import "./reset.scss";
```

```styl
@import "./reset.styl"
```
