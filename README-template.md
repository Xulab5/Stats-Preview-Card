# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [Links](#links)
- [Built with](#built-with)
- [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size


### Screenshot

![](./nft-preview-card-screenshot.jpg)

### Links

- Live Site URL: [Stats Preview Card](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Bootstrap v5.0

To see how you can add code snippets, see below:

```html
<div class="container my-5">
<div class="card mb-3">
  <div class="row g-0">
    <div class="col-md-6 img-container d-block d-md-none">
      <img src="images/image-header-mobile.jpg" class="img-fluid" alt="student image">
    </div>
    <div class="col-md-6 content-con p-lg-4 p-xl-5 d-xl-flex align-items-xl-center">
      <div class="card-body text-center text-lg-start p-4 pt-xl-4 pe-xl-5">
        <h1 class="card-title fw-bolder">Get <span>insights</span> that help your business grow.</h1>
        <p class="card-text mt-4 mb-5 pe-xl-5">Discover the benefits of data analytics and make better decisions regarding revenue, customer experience, and overall efficiency.</p>
        <div class="summary-stat text-uppercase d-lg-flex justify-content-lg-between pe-xl-5 me-xl-5">
          <div class="my-4"><h4 class="fw-bold m-0">10k+</h4> <span class="fs-6">companies</span></div>
          <div class="my-4"><h4 class="fw-bold m-0">314</h4> <span class="fs-6">templates</span></div>
          <div class="my-lg-4"><h4 class="fw-bold m-0">12m+</h4> <span class="fs-6">queries</span></div>
        </div>
      </div>
    </div>
    <div class="col-md-6 img-container d-none d-md-block">
      <img src="images/image-header-desktop.jpg" class="img-fluid w-100 h-100" alt="student image">
    </div>
  </div>
</div>
</div>
  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a href="#">Xulab</a>.
  </div>
```
```css
    .attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
    body{background-color: hsl(233, 47%, 7%);color:hsl(0, 0%, 100%); display: grid; place-items: center; height: 100vh; margin:0px; padding:0px;}
    .card{background-color: hsl(244, 38%, 16%); border-radius: 10px;}
    .img-container img { border-top-left-radius: 10px;border-top-right-radius: 10px;}
    .card-title span{color: hsl(277, 64%, 61%);}
    .card-text{color: hsla(0, 0%, 100%, 0.75);}
    .summary-stat span{color:hsla(0, 0%, 100%, 0.6) ;}
    .fs-6{font-size: .8rem!important;}
    .img-container{position:relative}
    .img-container::before{
      content: "";
      position: absolute;
      background-color: hsl(277deg 64% 61% / 50%);
      width: 100%;
      height: 100%;
      border-top-left-radius: 10px;
      border-top-right-radius: 10px;
    }
    @media (min-width:768px) {
      .img-container img,.img-container::before { border-top-left-radius: 0px; border-bottom-right-radius: 10px; }
      .attribution{position: absolute; bottom:0;}
      
    }
```

### Continued development

Bootstrap is one of the framework I am wanting to become well verse in. It helps development pages really quickly. I totally recommend it if you have a deadline with your project.

## Author

- Website - [Xulab](https://substeven.netlify.app/)
- Frontend Mentor - [@Xulab05](https://www.frontendmentor.io/profile/Xulab5)
- Twitter - [@Xulab05](https://www.instagram.com/xulab05/)

## Acknowledgments
I'd like to give thanks to Front-end for this awesome short project.
