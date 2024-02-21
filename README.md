# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot
![](./screenshots/desktop_view.png)
![](./screenshots/mobile_view.png)

### Links
- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)


### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned
In HTML i learn how to write a html for screen readers with css
 In CSS Flex,Grid and variables 


```html
<p class="product__price">
            <span class="visually-hidden">Current Price:</span> $149.99
          </p>
```

```css
/* css for screen readers */
.visually-hidden:not(:focus):not(:active) {
  clip: rect(0 0 0 0);
  clip-path: inset(50%);
  height: 1px;
  overflow: hidden;
  position: absolute;
  white-space: nowrap;
  width: 1px;
}
/* flex */
.flex-group {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
  align-items: center;
}
/* grid */
body{
    display: grid;
  place-content: center;
  margin: 1rem;
}
/* variables */
:root{
    --clr-primary-400: hsl(158, 36%, 37%);
  --clr-primary-500: hsl(158, 36%, 20%);
  --clr-secondary-200: hsl(30, 38%, 92%);

}
```
### Continued development
I want to continue focusing on in selectors,flex,grid,responsive layout by doing more projects.

### Useful resources
- [Example resource 1](https://www.fonts.google.com) - This helped me for Fonts. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.joshwcomeau.com/css/custom-css-reset) - This is an amazing article which helped me to reset predefined css for tags,position and layouts.

## Author
- Website - [Dinesh.P](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/Dinesh-36)

## Acknowledgments
I give a hat tip to Kevin Powell(youtube channel)

