# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Author](#author)

### Screenshot

<link rel="screenshoot" href="screenshoot/desktop.png">
<link rel="screenshoot" href="screenshoot/mobile.png">


**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [C:\Users\HP\Desktop\Challenging Project\results-summary-component-main\challange2.html](https://your-solution-url.com)
- Live Site URL: [ https://raghda19.github.io/Results-summary-component/](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- [Styled Components](https://getbootstrap.com/docs/4.5/layout/overview/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

-I used bootstrap grid to divine the {div1 and div2} as columns in row. 
-I add this cod at the top
```css
 @media screen and (max-width:1440px) and (min-width:375px) {
    body {
        margin: 0;
    }

}
```
To adjust the width of the website to fit moblie {width=375px} i used [@media (max-width: 575.98px) { ... }] and inside it i change the width of both [body and #div1]  as will as auther element to match the requier project which is mean // Extra small devices (portrait phones, less than 576px)// i tried to use [@media (max-width: 375px) { ... }] but it didn't work.

-To adjust the width of the website to fit desktop {width=1440px} i used [@media (max-width:1440px) { ... }] and inside it i change the width of both [body and #div1] as will as auther element to match the requier project. 

```html
<div class="container">
  <div class="row">
    <div class="col-xl-6">col</div>
    <div class="co-xl-6">col</div> 
</div>
```
```css
@media (max-width: 1440px) {
}
@media (max-width: 575.98px) {
}

 ```      



### Continued development

I need to focus on those two areas:
-@media


## Author

- Website - [Raghda Mohamed](https://www.your-site.com)
- Frontend Mentor - [@Raghda19](https://www.frontendmentor.io/profile/Raghda19)


