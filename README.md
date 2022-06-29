# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Future Updates](#future-updates)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](/images/screenshot.png)

### Links

- [Github Solution](https://github.com/iamtrazed/QR-Code-Component "Github Solution")
- [Github Pages Live Solution](https://iamtrazed.github.io/QR-Code-Component/ "Github Pages Live Solution")

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- BEM Methodology
- Flexbox
- Mobile-first workflow

### What I learned

The main thing that I learned from building this project was fixing all the messy
code that was all over the place, duplicate classes, nonsense attributes, so I was introduced to the BEM Methodology and to be honest I really loved it.

If there is room for improvement I'm always open to suggestions!

```html
<main>
  <section class="card">
    <a class="card__img">
      <img src="images/image-qr-code.png" alt="QR Code Frontendmentor" />
    </a>
    <div class="card__information">
      <h2>Improve your front-end skills by building projects</h2>
      <p>
        Scan the QR code to visit Frontend Mentor and take your coding skills to
        the next level
      </p>
    </div>
  </section>
  <footer>
    <div>
      Challenge by
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
        >Frontend Mentor</a
      >.
    </div>
    <div>&nbsp;Coded by <a href="#">Harun Jonuzi</a>.</div>
  </footer>
</main>
```

### Continued development

Still need to fully understand Semantic HTML5 and slowly move to learning the Sass concepts.

### Useful resources

- [Learn BEM](https://en.bem.info/methodology/) - The main source of learning how to use the BEM Methodology which I highly suggest it to everyone.
- [Writing Markdown Guide](https://www.markdownguide.org/getting-started/) - Writing this whole markdown guide was a new thing to me, which I think is very useful for learning how to structure your thoughts and project into a simple layout for everyone to understand it.

## Author

- Frontend Mentor - [@iamtrazed](https://www.frontendmentor.io/profile/iamtrazed)
- Twitter - [@iamtrazed](https://www.twitter.com/iamtrazed)

## Future Updates

#### Case Version 0.1

> I want to find a solution to use less code to center the image in the card, which in this case it takes 3 lines to center the image. `display: flex;`, `flex-direction: column;`, `align-items: center`.

```css
.card {
  background-color: var(--white-clr);
  border-radius: 1.2rem;
  width: 250px;
  height: 400px;
  display: flex;
  flex-direction: column;
  align-items: center;
  box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px;
}
```

---
