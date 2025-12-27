# Ex08 Event Registration Web Application
## Date:26/12/2025

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-plus">
      <img class="logo" src="img/logo1-1.png" />
      <div class="text-wrapper">VIJAYAPRATHISHA J (25008497)</div>
      <div class="div">EVENT REGISTRATION FORM</div>
      <p class="NAME-GENDER-AGE">
        NAME <br /><br />GENDER<br /><br />AGE<br /><br />DEPARTMENT<br /><br />REGISTER NO<br /><br />EMAIL ID
        <br /><br />MOBILE NO
      </p>
      <img class="arrow" src="img/arrow-1.svg" />
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="rectangle"></div>
      <div class="text-wrapper-2">REGISTER</div>
    </div>
  </body>
</html>

globals.html

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.iphone-plus {
  overflow: hidden;
  background-image: url(./img/iphone-14-plus-3.png);
  background-size: cover;
  background-position: 50% 50%;
  width: 100%;
  min-width: 428px;
  min-height: 926px;
  position: relative;
}

.iphone-plus .logo {
  position: absolute;
  top: 8px;
  left: 0;
  width: 428px;
  height: 108px;
  aspect-ratio: 4.09;
  object-fit: cover;
}

.iphone-plus .text-wrapper {
  position: absolute;
  top: 887px;
  left: 34px;
  width: 456px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #16eb0f;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-plus .div {
  position: absolute;
  top: 131px;
  left: 9px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-plus .NAME-GENDER-AGE {
  position: absolute;
  top: 297px;
  left: 69px;
  width: 193px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-plus .arrow {
  position: absolute;
  top: 799px;
  left: 83px;
  width: 132px;
  height: 15px;
}

.iphone-plus .text-on-a-path {
  position: absolute;
  top: 772px;
  left: -390px;
  width: 170px;
  height: 54px;
}

.iphone-plus .rectangle {
  position: absolute;
  top: 779px;
  left: 245px;
  width: 173px;
  height: 68px;
  background-color: #d9d9d9;
}

.iphone-plus .text-wrapper-2 {
  position: absolute;
  top: 791px;
  left: 277px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}
```


## OUTPUT:
![alt text](<Screenshot (71).png>)


## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
