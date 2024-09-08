# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### Links

- Solution URL: [Github](https://github.com/EAguayodev/frontendmentor-four-card-feature-2/tree/main/four-card-feature-section-master)
- Live Site URL: [Vercel](https://frontendmentor-four-card-feature-2.vercel.app/)

## My process
Used flexbox to create the layout.

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
- Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
 <div class="container">
                <div class="card_box box-supervisor box_push">
                    <h3 class="c-heading">Supervisor</h3>
                    <p>Monitors activity to identify project roadblocks</p>

                    <img class="icons" src="images/icon-supervisor.svg" alt="">
                </div>

                <div class="card_box box-builder">
                    <h3 class="c-heading">Team Builder</h3>
                    <p>Scans our talent network to create the optimal team for your project</p>

                    <img class="icons" src="images/icon-team-builder.svg" alt="builder">
                </div>

                <div class="card_box box-calculator box_push">
                        <h3 class="c-heading">Calculator</h3>
                        <p>Uses data from past projects to provide better delivery estimates</p>

                        <img class="icons" src="images/icon-calculator.svg" alt="calculator">
                </div>

                <div class="card_box box-karma">
                    <h3 class="c-heading" id="karma">Karma</h3>
                    <p>Regularly evaluates our talent to ensure quality</p>

                    <img class="icons" src="images/icon-karma.svg" alt="karma-icon">
                </div>
            </div>
```
```css
.container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin: 0 auto;
    max-width: 1140px;
}
```

### Continued development

Currently working on the javascript part of the learning path.


## Author

- Website - [Eric Aguayo](https://www.ericaguayo.com)
- Frontend Mentor - [@ericaguayo](https://www.frontendmentor.io/profile/ericaguayo)
- Twitter - [@ericaguayo](https://www.twitter.com/ericaguayo)

## Acknowledgments

Give credit to anyone who helped you Franci Melink on this project. Helped me identify the issue with the h1 violation rule.