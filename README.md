# Vincent's Portfolio 💼

A responsive and dynamic portfolio site built with HTML, CSS and JavaScript — designed to reflect both my technical and creative sides.

---

## 🌍 Live Demo

🔗 [View Portfolio](https://vinneys.github.io/portfolio)

---


## 🚀 Features

### ✅ Base Features
- **Fully responsive layout** – adapts to all screen sizes
- **Profile image positioning** – circular avatar floats above content using absolute positioning
- **Modal popups** – clean modal windows with project code previews and click-outside-to-close support
- **Formspree contact form** – real form submissions without backend



#### 🟢 `Blurred modal background`
> When clicking "Visa kod", the rest of the page is blurred to focus attention on the modal popup.

- Implemented using `filter: blur(5px)` + JavaScript class toggle
- Adds a modern, professional touch

#### 🟢 `Responsive modal gallery (slider)`
> Instead of static images, the popup modal includes a JavaScript-powered **image carousel** to preview multiple code screenshots.

- Controlled with Next/Prev buttons
- Built using vanilla JS array + image swap

#### 🟢 `Dynamic form success message`
> Custom JavaScript handles the Formspree response and shows a thank-you message inline (no redirect).

```js
fetch(form.action, {
  method: "POST",
  body: formData,
  headers: { 'Accept': 'application/json' }
})
