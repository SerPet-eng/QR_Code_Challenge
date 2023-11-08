# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

---

## Overview

### Screenshot

##### Mobile Version

![Mobile Version](./screenshots/Screen%20Shot%202023-11-07%20at%2020.28.27.png)

##### Desktop Version

![Desktop Version](./screenshots/FireShot%20Capture%20003%20-%20Frontend%20Mentor%20-%20QR%20code%20component%20-%20127.0.0.1.png)

### Links

- Solution URL: [GitHub](https://github.com/SerPet-eng/QR_Code_Challenge)
- Live Site URL: [Netlify](https://incomparable-horse-cdcba3.netlify.app/)

---

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Flex
- Mobile-first workflow

### What I learned

This part may change in the future because there are things that surely I haven't learn but what I've learn so far is to organize the **content** of a single HTML element

#### For example:

```html
<main class="app">
  <div class="app-box">
    <img src="./images/image-qr-code.png" alt="QR Code" class="app-image" />
    <h2 class="app-title">
      Improve your front-end skills by building projects
    </h2>
    <p class="app-paragraph">
      Scan the QR code to visit Frontend Mentor and take your coding skills to
      the next level
    </p>
  </div>
  <div class="attribution">
    <p>
      Challenge by
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
        >Frontend Mentor</a
      >.
    </p>
    <p>
      Coded by <a href="https://github.com/SerPet-eng">Christian De Guzman</a>.
    </p>
  </div>
</main>
```

> As you can see, the `<div class="app-box">` and `<div class="attribution">` had their own content.
> Seperating the content and put it inside of their respective HTML Element is really important,
> Especially if we use `display: flex`.

### Continued development

Other thing that need some polish but good enough to meet the requirements is in this CSS of mine:

```css
@media only screen and (min-width: 900px) {
  .app {
    margin: 37%;
  }
}
```

This **media** stuff is still needs some adjustment but the rest of the code:

```css
body {
  font-family: var(--ff-Outfit);
  background-color: var(--cc-lightGray);
}

.app {
  margin: 10%;
}

.app-box {
  padding: 1.5rem;
  border-radius: 20px;
  background-color: var(--cc-white);
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

.app-image {
  width: 100%;
  border-radius: 10px;
}

.app-title {
  margin-top: 20px;
  font-weight: var(--fw-700);
  color: var(--cc-darkBlue);
}

.app-paragraph {
  margin-top: 20px;
  margin-bottom: 30px;
  font-weight: var(--fw-400);
  color: var(--cc-grayBlue);
}
```

I'm pretty confident with the result of this code of mine but like I said, it need some **polish** but good enough to meet the requirements. Which in this case is the QR Code Component.

### Useful resources

- [freeCodeCamp](https://www.freecodecamp.org/news/how-to-center-anything-with-css-align-a-div-text-and-more/) - This site help me to remind me how to center an object using CSS and in this part of the site, it has different ways to center an object. Very informative.
- [W3Schools](https://www.w3schools.com/) - This site always help to remember things, for instance in CSS. Especially if I'm not coding for a while, If I want to remember something that I have known before, I'll just go to this site. Very useful!
- [Scrimba](https://scrimba.com/learn/htmlandcss/) - This part of Scrimba when it was my first time really get into web developing, this help me understand the basics and fundamentals of HTML and CSS. High recommended for beginners, it was easy to follow and very engaging.

---

## Author

- GitHub - [Christian De Guzman](https://github.com/SerPet-eng)
- Frontend Mentor - [@SerPet-eng](https://www.frontendmentor.io/profile/SerPet-eng)
- Twitter - [@dchristian796](https://twitter.com/dchristian796)
