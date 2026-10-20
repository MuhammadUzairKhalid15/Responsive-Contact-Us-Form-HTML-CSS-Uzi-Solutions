# Responsive Contact Us Form (HTML & CSS)

A clean, responsive contact page built with **HTML & CSS only**. Contact details with icons sit on the left, a message form on the right, and on mobile the layout stacks automatically. **No framework, no JavaScript.**

🔗 **Live Demo:** https://muhammaduzairkhalid15.github.io/Responsive-Contact-Us-Form-HTML-CSS-Uzi-Solutions/
💻 **Repository:** https://github.com/MuhammadUzairKhalid15/Responsive-Contact-Us-Form-HTML-CSS-Uzi-Solutions

> ⭐ If this helped you, a star on the repo means a lot!

## ✨ Features

- 📱 Fully responsive with two breakpoints (950px and 820px)
- 🧭 Two-column card: contact details (address, phone, email) and a message form
- 🔀 On small screens the layout stacks and the form moves to the top
- ➖ Vertical divider line made with a CSS pseudo-element
- 🎨 Soft, borderless inputs with a purple accent
- ✨ Smooth hover transition on the send button
- 🚫 No JavaScript

> Note: this is a front-end UI only. The form does not send messages yet. Replace the demo contact details with your own.

## 🔧 Built With

- **HTML5**
- **CSS3**: flexbox, media queries, pseudo-elements, transitions
- **Font Awesome**: icons
- **Google Fonts**: Poppins

## 📂 Project Structure

```
Responsive-Contact-Us-Form-HTML-CSS-Uzi-Solutions/
├── index.html
└── style.css
```

## 🚀 Getting Started

1. Clone the repository
   ```
   git clone https://github.com/MuhammadUzairKhalid15/Responsive-Contact-Us-Form-HTML-CSS-Uzi-Solutions.git
   ```
2. Open `index.html` in your browser. Resize the window to see the layout adapt.

## 🧠 How the Mobile Layout Works

```css
@media (max-width: 820px) {
    .container .content {
        flex-direction: column-reverse;
    }
}
```

`column-reverse` stacks the two columns and puts the form first, with no extra HTML.

## 💡 What I Practiced

- Building a two-column layout with flexbox
- Writing media queries for multiple breakpoints
- Reordering content on mobile with `flex-direction: column-reverse`
- Drawing a divider with `::before` and `position: absolute`
- Styling borderless inputs and a hover transition

## 🔜 Next Steps

- Connect the form to a backend or a form service
- Add labels and email validation for better accessibility

## 📬 Feedback

Suggestions are welcome. Open an issue or reach out on LinkedIn!
