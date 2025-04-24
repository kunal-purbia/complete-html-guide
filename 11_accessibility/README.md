# ♿ Chapter 11: Accessibility (A11y)

Accessibility in HTML ensures that websites are usable by **everyone**, including people with disabilities. It’s not just about compliance — it’s about **creating better experiences** for all users.

In this chapter, we’ll explore semantic HTML, ARIA attributes, keyboard navigation, and accessibility best practices.

---

## 🎯 What You’ll Learn

- Why accessibility matters
- Using semantic HTML correctly
- Common ARIA roles and labels
- Keyboard navigation and focus
- Screen reader considerations

---

## 🧩 Key Concepts

| Concept               | Description                                                      |
|-----------------------|------------------------------------------------------------------|
| Semantic HTML         | Tags that carry meaning (e.g., `<header>`, `<nav>`, `<main>`)     |
| ARIA (Accessible Rich Internet Applications) | Attributes like `aria-label`, `role` for screen readers |
| Focus Management      | Ensuring tab order and keyboard access to interactive elements   |
| Alt Text              | Describing images for screen readers                             |

---

## 📄 Example Files

| File Name                 | Description                                       |
|---------------------------|---------------------------------------------------|
| `01_semantic-tags.html`   | Layout using only semantic HTML5 tags            |
| `02_keyboard-access.html` | Navigable page using only the keyboard           |
| `03_aria-labels.html`     | Form elements with proper `aria-*` attributes    |
| `04_alt-text.html`        | Examples of effective and poor image descriptions|
| `05_accessible-form.html` | Fully accessible form with labels and ARIA roles |

---

## ✅ Practice Task

Rebuild a **contact form** that includes:
- Semantic structure
- Labeled inputs and textareas
- Keyboard navigability
- Descriptive `aria-label`s and meaningful alt text

---

## 💡 Best Practices

- Always use `alt` on images unless purely decorative (`alt=""`)
- Use `<label>` with form elements for screen readers
- Avoid using only color to convey information
- Test with keyboard-only navigation (`Tab`, `Shift+Tab`, `Enter`)
- Use [WAVE](https://wave.webaim.org/) or browser extensions for accessibility audits

---

## 🔜 Next Up: [Project Examples →](../12_project-examples/README.md)
