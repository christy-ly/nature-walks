<h3 align="center">Nature Walks – A Tourist Website 🗻🗻🗻</h3>

## 💬 Overview
This project is a clean, professional tourist website built with HTML, CSS, and SCSS. It features a modular SCSS architecture, responsive design, and engaging animations for an excellent user experience.

## 🛠 Technologies Stack
- HTML5 – Structure and semantic markup
- CSS3 / SCSS – Styling, responsive layout, and animations
- Sass – CSS preprocessor for modular and maintainable code

## ✨ Features  
- Built with semantic **HTML5**  
- Modular **SCSS** structure with `abstract`, `base*`, `components`, and `layout` folders  
- Responsive design using `vh`, `%`, and `rem` units  
- Engaging **CSS animations** and **transitions**  
- Fully optimized for desktop and mobile viewports using **CSS @media queries**
- Clear and maintainable CSS naming using **BEM methodology**:  
  - Elements named with `__` (double underscore), e.g., `.card__title` 
  - Modifiers named with `--` (double dash), e.g., `.card--featured` or `.card__button--disabled`  
- **SCSS nesting** for cleaner stylesheets:  
  - Example of nesting an element selector inside a parent:  
    ```scss
    .header {
      h1 {
        /* styles for h1 inside .header */
      }
    }
    ```  
  - Avoid using `&` directly with elements (like `&h1`), as it concatenates selectors (e.g., `.headerh1`), which is usually unintended.  
  - Use `&` to create modifier classes properly, e.g.:  
    ```scss
    .btn {
      &--white {
        /* styles for .btn-white */
      }
    }
    ```
    
## 📁 Folder Structure
```
project-root/
│
├── index.html
├── css/
│   └── style.css
├── sass/
│   ├── abstract/
│   │   ├── _functions.scss
│   │   ├── _mixins.scss
│   │   └── _variables.scss
│   ├── base/
│   │   ├── _animations.scss
│   │   ├── _base.scss
│   │   ├── _typography.scss
│   │   └── _untility.scss
│   ├── components/
│   │   ├── _bg-video.scss
│   │   ├── _button.scss
│   │   ├── _card.scss
│   │   ├── _review.scss
│   │   ├── _compistion.scss
│   │   └── _subscription.scss
│   ├── layout/
│   │   ├── _footer.scss
│   │   ├── _header.scss
│   │   ├── _navigation.scss
│   │   ├── _popup.scss
│   │   └── _row.scss
│   └── main.scss
├── img/
│   └── hero.jpg
└── README.md
```

## 📽️View Demo
Check out the live demo of this project here: [View Demo](https://steady-donut-83396d.netlify.app/)

## 📚References
- **HTML & CSS Docs** – [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web)
- **CSS Layout Guide** – [CSS-Tricks](https://css-tricks.com/snippets/css/)
- **Photo Source** – [Unsplash](https://unsplash.com/?utm_source=your_app_name&utm_medium=referral)
- **Video Source** – [Pexels](https://unsplash.com/?utm_source=your_app_name&utm_medium=referral)


