## Table of contents

- [Overview](#this-is-only-a-QR-component)
  - [Screenshot](./design/desktop-design.jpg)
  - [Links](github-https://github.com/vishwajeet-8)
- [Author](#vishwajeet)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### code

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- displays site properly based on user's device -->

    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./images/favicon-32x32.png"
    />

    <title>Frontend Mentor | QR code component</title>

    <link rel="stylesheet" href="style.css" />

    <style>
      @import url("https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap");
    </style>
  </head>
  <body>
    <div class="main">
      <div class="first">
        <img src="./images/image-qr-code.png" alt="qr code" />
      </div>

      <div class="second">
        <h1>Improve your front-end skills by building projects</h1>
        <p>
          Scan th QR code to visit Frontend Mentor and take your coding skills
          to the next level
        </p>
      </div>
    </div>
  </body>
</html>
```

```css
* {
  margin: 0px;
}

@media only screen and (max-width: 376px) {
  body {
    background-color: hsl(212, 45%, 89%);
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .main {
    width: 250px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    background-color: hsl(0, 0%, 100%);
    padding: 10px;
    border-radius: 15px;
  }
  .first {
    margin-top: 5px;
  }

  img {
    width: 240px;
    background-size: contain;
    border-radius: 15px;
  }
  .second {
    text-align: center;
    font-family: "Outfit", sans-serif;
  }

  .second h1 {
    font-size: 1.3rem;
    font-weight: 700;
    margin-top: 15px;
    margin-bottom: 15px;
  }
  .second p {
    font-weight: 400;
    font-size: 0.938rem;
    margin-bottom: 15px;
  }
}

body {
  background-color: hsl(212, 45%, 89%);
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}

.main {
  width: 250px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background-color: hsl(0, 0%, 100%);
  padding: 10px;
  border-radius: 15px;
}
.first {
  margin-top: 5px;
}

img {
  width: 240px;
  background-size: contain;
  border-radius: 15px;
}
.second {
  text-align: center;
  font-family: "Outfit", sans-serif;
}

.second h1 {
  font-size: 1.3rem;
  font-weight: 700;
  margin-top: 15px;
  margin-bottom: 15px;
}
.second p {
  font-weight: 400;
  font-size: 0.938rem;
  margin-bottom: 15px;
}
```
