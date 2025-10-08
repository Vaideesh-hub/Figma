# Ex09 Event Registration Web Application
## Date:08.10.2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
index1.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="global1.css" />
    <link rel="stylesheet" href="style1.css" />
  </head>
  <body>
    <div class="android-compact">
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="rectangle"></div>
      <div class="div"></div>
      <img class="i" src="i3.jpg" />
      <p class="camera-competition">
        <span class="text-wrapper">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;</span>
        <span class="span">&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span class="text-wrapper-2">Camera Competition<br />For Everyone</span>
      </p>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">Login</div>
      <div class="text-wrapper-4">Register</div>
      <img class="img" src="i4.jpg" />
    </div>
  </body>
</html>

global1.css
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

.android-compact {
  background-color: #000000;
  width: 100%;
  min-width: 412px;
  min-height: 917px;
  position: relative;
}

.android-compact .text-on-a-path {
  position: absolute;
  top: 394px;
  left: 113px;
  width: 178px;
  height: 50px;
}

.android-compact .rectangle {
  position: absolute;
  top: 603px;
  left: 113px;
  width: 178px;
  height: 48px;
  background-color: #ffffff;
}

.android-compact .div {
  position: absolute;
  top: 39px;
  left: 48px;
  width: 308px;
  height: 80px;
  background-color: #d9d9d9;
}

.android-compact .i {
  top: 193px;
  left: 63px;
  width: 286px;
  height: 190px;
  aspect-ratio: 1.5;
  position: absolute;
  object-fit: cover;
}

.android-compact .camera-competition {
  position: absolute;
  top: 27px;
  left: 37px;
  width: 319px;
  height: 92px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: transparent;
  font-size: 12px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper {
  color: #ffffff;
}

.android-compact .span {
  color: #ffffff;
  font-size: 24px;
}

.android-compact .text-wrapper-2 {
  color: #ff0000;
  font-size: 24px;
}

.android-compact .rectangle-2 {
  position: absolute;
  top: 497px;
  left: 113px;
  width: 178px;
  height: 53px;
  background-color: #d9d9d9;
}

.android-compact .text-wrapper-3 {
  position: absolute;
  top: 496px;
  left: 105px;
  width: 195px;
  height: 54px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ff0000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-4 {
  position: absolute;
  top: 606px;
  left: 103px;
  width: 197px;
  height: 45px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #e80808;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .img {
  top: 0;
  left: 0;
  width: 1px;
  height: 1px;
  position: absolute;
  object-fit: cover;
}

index2.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="global2.css" />
    <link rel="stylesheet" href="style.2css" />
  </head>
  <body>
    <div class="android-compact">
      <div class="rectangle"></div>
      <div class="text-wrapper">Camera Events</div>
      <img class="star" src="i1.jpg" />
      <div class="div">Nature Photography</div>
      <img class="img" src="i1.jpg" />
      <div class="sports-photography">Sports<br />Photography</div>
      <img class="star-2" src="i1.jpg" />
      <div class="text-wrapper-2">Marco Photography</div>
      <img class="star-3" src="i1.jpg" />
      <div class="text-wrapper-3">Fashion Photography</div>
      <img class="star-4" src="i1.jpg" />
      <div class="text-wrapper-4">Editorial Photography</div>
      <img class="star-5" src="i1.jpg" />
      <div class="text-wrapper-5">Conceptual Photography</div>
      <img class="star-6" src="i1.jpg" />
      <div class="text-wrapper-6">Aerial Photography</div>
    </div>
  </body>
</html>

global2.css

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

style2.css

.android-compact {
  background-color: #000000;
  width: 100%;
  min-width: 412px;
  min-height: 917px;
  position: relative;
}

.android-compact .rectangle {
  position: absolute;
  top: 57px;
  left: 63px;
  width: 280px;
  height: 54px;
  background-color: #000000;
}

.android-compact .text-wrapper {
  position: absolute;
  top: 54px;
  left: 38px;
  width: 328px;
  height: 66px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .star {
  position: absolute;
  top: 151px;
  left: 79px;
  width: 29px;
  height: 21px;
}

.android-compact .div {
  position: absolute;
  top: 140px;
  left: 108px;
  width: 226px;
  height: 46px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .img {
  position: absolute;
  top: 236px;
  left: 79px;
  width: 29px;
  height: 21px;
}

.android-compact .sports-photography {
  position: absolute;
  top: 223px;
  left: 126px;
  width: 208px;
  height: 50px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .star-2 {
  position: absolute;
  top: 321px;
  left: 79px;
  width: 32px;
  height: 26px;
}

.android-compact .text-wrapper-2 {
  position: absolute;
  top: 314px;
  left: 140px;
  width: 194px;
  height: 53px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .star-3 {
  position: absolute;
  top: 423px;
  left: 77px;
  width: 31px;
  height: 21px;
}

.android-compact .text-wrapper-3 {
  position: absolute;
  top: 413px;
  left: 144px;
  width: 182px;
  height: 56px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .star-4 {
  position: absolute;
  top: 527px;
  left: 78px;
  width: 29px;
  height: 24px;
}

.android-compact .text-wrapper-4 {
  position: absolute;
  top: 511px;
  left: 151px;
  width: 175px;
  height: 67px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .star-5 {
  position: absolute;
  top: 634px;
  left: 76px;
  width: 31px;
  height: 22px;
}

.android-compact .text-wrapper-5 {
  position: absolute;
  top: 628px;
  left: 149px;
  width: 177px;
  height: 48px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .star-6 {
  position: absolute;
  top: 749px;
  left: 79px;
  width: 29px;
  height: 24px;
}

.android-compact .text-wrapper-6 {
  position: absolute;
  top: 741px;
  left: 162px;
  width: 181px;
  height: 59px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

index3.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="global3.css" />
    <link rel="stylesheet" href="style3.css" />
  </head>
  <body>
    <div class="android-compact">
      <img class="polygon" src="i2.jpg" />
      <div class="THANK-YOU-ALL-THE">THANK&nbsp;&nbsp;<br /><br />YOU<br /><br />ALL THE BEST</div>
    </div>
  </body>
</html>

global3.css

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

style3.css

.android-compact {
  background-color: #000000;
  width: 100%;
  min-width: 412px;
  min-height: 917px;
  position: relative;
}

.android-compact .polygon {
  position: absolute;
  top: 242px;
  left: 28px;
  width: 365px;
  height: 349px;
}

.android-compact .THANK-YOU-ALL-THE {
  position: absolute;
  top: 270px;
  left: 25px;
  width: 373px;
  height: 370px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}
```


## OUTPUT:
![alt text](<Screenshot 2025-10-08 145156.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
