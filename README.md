# Frontend Mentor - Product preview card component

![Design preview for the QR code component coding challenge](./design/Screenshot%202023-07-07%20095854.png)

## Welcome! 👋

- Thanks for checking out this project made for a front-end coding challenge.

- [Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.

## The challenge

- My challenge was build out this Product preview card component and get it looking as close to the design provided by Frontend Mentor as possible.

## My solution

```html
<div class="container">
  <div class="card">
    <img src="images/image-product-desktop.jpg" alt="" class="product-shot" />
    <div class="content">
      <h2>PERFUME</h2>
      <h1>Gabrielle Essence Eau De Parfum</h1>
      <p>
        A floral, solar and voluptuous interpretation composed by Olivier Polge,
        Perfumer-Creator for the House of CHANEL.
      </p>
      <p id="current-price">$149.99</p>
      <p id="old-price">$169.99</p>
      <button id="add-cart-button">
        <img src="images/icon-cart.svg" alt="" /> Add to Cart
      </button>
    </div>
  </div>
</div>

<div class="attribution">
  Challenge by
  <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
    >Frontend Mentor</a
  >. Coded by <a href="https://github.com/lucas-brisolla">Lucas Brisolla</a>.
</div>
```

```css
@charset "UTF-8";

@import url("https://fonts.googleapis.com/css2?family=Fraunces:wght@700&family=Montserrat:wght@500;700&display=swap");

* {
  margin: 0;
  padding: 0;
}

body {
  background-color: #f2ebe3;
}

.container {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
}

.card {
  display: flex;
  align-items: center;
  background-color: #ffffff;
  font-family: "Montserrat", sans-serif;
  padding: 0px;
  border-radius: 15px;
  width: 900px;
}

.content {
  justify-content: center;
  align-items: center;
  margin-left: 55px;
  height: 100%;
  width: 35%;
}

.product-shot {
  justify-content: center;
  align-items: center;
  width: 50%;
  border-top-left-radius: 15px;
  border-bottom-left-radius: 15px;
}

p {
  color: #6c7289;
  line-height: 1.8em;
  font-size: 15px;
}

h2 {
  font-size: 15px;
  font-family: "Montserrat", sans-serif;
  letter-spacing: 10px;
  margin-bottom: 30px;
  color: #6c7289;
  font-weight: lighter;
}

h1 {
  font-family: "Fraunces", serif;
  font-size: 45px;
}

#current-price {
  display: inline-block;
  font-family: "Fraunces", serif;
  font-size: 55px;
  color: #3c8067;
}

#old-price {
  display: inline-block;
  font-family: "Montserrat", sans-serif;
  font-size: 15px;
  text-decoration: line-through;
  color: #6c7289;
}

#add-cart-button {
  display: block;
  background-color: #3c8067;
  color: white;
  border: none;
  text-align: center;
  font-family: "Montserrat", sans-serif;
  font-size: 25px;
  padding: 25px 60px 25px 60px;
  width: 100%;
  border-radius: 15px;
}

#add-cart-button > img {
  width: 25px;
  height: 25px;
}

#add-cart-button:hover {
  cursor: pointer;
  background-color: #224c3d;
  transition: 0.5s;
}

.attribution {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0;
  text-align: center;
  font-family: "Montserrat", "sans-serif";
}
```

## Links

- Live Site URL: https://lucas-brisolla.github.io/product-preview-card-component/

## Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
