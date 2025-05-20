# Ex09 Event Registration Web Application
## Date:20/05/2025

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

HOME PAGE
```
<div class="i-phone-16-plus-1">
  <img
    class="screenshot-2025-05-20-200620-1"
    src="screenshot-2025-05-20-200620-10.png"
  />
  <div class="rectangle"></div>
  <div class="register">
    <span>
      <span class="register-span"></span>
      <span class="register-span2">REGISTER</span>
      <span class="register-span3"></span>
    </span>
  </div>
  <div class="rectangle-1"></div>
  <div class="login">LOGIN</div>
  <div class="sports-day">
    SPORTS
    <br />
    DAY
  </div>
</div>

.i-phone-16-plus-1,
.i-phone-16-plus-1 * {
  box-sizing: border-box;
}
.i-phone-16-plus-1 {
  background: #57d51d;
  height: 932px;
  position: relative;
  overflow: hidden;
}
.screenshot-2025-05-20-200620-1 {
  width: 405px;
  height: 64px;
  position: absolute;
  left: 12px;
  top: 95px;
  object-fit: cover;
  aspect-ratio: 405/64;
}
.rectangle {
  background: #d9d9d9;
  width: 265px;
  height: 67px;
  position: absolute;
  left: 82px;
  top: 466px;
}
.register {
  color: #000000;
  text-align: left;
  position: absolute;
  left: 82px;
  top: 474px;
  width: 288px;
  height: 67px;
}
.register-span {
  font-family: "Inter-Regular", sans-serif;
  font-size: 12px;
  font-weight: 400;
}
.register-span2 {
  font-family: "Inter-Regular", sans-serif;
  font-size: 48px;
  font-weight: 400;
}
.register-span3 {
  font-family: "Inter-Regular", sans-serif;
  font-size: 36px;
  font-weight: 400;
}
.rectangle-1 {
  background: #d9d9d9;
  width: 224px;
  height: 80px;
  position: absolute;
  left: 93px;
  top: 555px;
}
.login {
  color: #060606;
  text-align: left;
  font-family: "Inter-Regular", sans-serif;
  font-size: 48px;
  font-weight: 400;
  position: absolute;
  left: 122px;
  top: 567px;
  width: 266px;
  height: 97px;
}
.sports-day {
  color: #ffffff;
  text-align: left;
  font-family: "JacquesFrancoisShadow-Regular", sans-serif;
  font-size: 64px;
  font-weight: 400;
  position: absolute;
  left: 65px;
  top: 249px;
  width: 342px;
  height: 136px;
}
```

2ND PAGE
```
<div class="i-phone-16-plus-2">
  <div
    class="sports-cricket-kabaddi-volley-ball-basket-ball-food-ball-hand-ball-through-ball"
  >
    <span>
      <span
        class="sports-cricket-kabaddi-volley-ball-basket-ball-food-ball-hand-ball-through-ball-span"
      ></span>
      <span
        class="sports-cricket-kabaddi-volley-ball-basket-ball-food-ball-hand-ball-through-ball-span2"
      >
        SPORTS
        <br />
      </span>
      <span
        class="sports-cricket-kabaddi-volley-ball-basket-ball-food-ball-hand-ball-through-ball-span"
      >
        <br />
      </span>
      <ul
        class="sports-cricket-kabaddi-volley-ball-basket-ball-food-ball-hand-ball-through-ball-span3"
      >
        <li>CRICKET</li>
      </ul>
      <ul
        class="sports-cricket-kabaddi-volley-ball-basket-ball-food-ball-hand-ball-through-ball-span4"
      >
        <li>KABADDI</li>
        <li>VOLLEY BALL</li>
        <li>BASKET BALL</li>
        <li>FOOD BALL</li>
        <li>HAND BALL</li>
        <li>THROUGH BALL</li>
      </ul>
    </span>
  </div>
</div>

.i-phone-16-plus-2,
.i-phone-16-plus-2 * {
  box-sizing: border-box;
}
.i-phone-16-plus-2 {
  background: #f3ff0b;
  height: 932px;
  position: relative;
  overflow: hidden;
}
.sports-cricket-kabaddi-volley-ball-basket-ball-food-ball-hand-ball-through-ball {
  text-align: left;
  position: absolute;
  left: 40px;
  top: 69px;
  width: 361px;
  height: 635px;
}
.sports-cricket-kabaddi-volley-ball-basket-ball-food-ball-hand-ball-through-ball-span {
  color: #d41d1d;
  font-family: "Inter-Regular", sans-serif;
  font-size: 64px;
  font-weight: 400;
}
.sports-cricket-kabaddi-volley-ball-basket-ball-food-ball-hand-ball-through-ball-span2 {
  color: #0037ea;
  font-family: "JejuGothic-Regular", sans-serif;
  font-size: 96px;
  font-weight: 400;
}
.sports-cricket-kabaddi-volley-ball-basket-ball-food-ball-hand-ball-through-ball-span3 {
  color: #b50909;
  list-style-type: disc;
  padding-left: 1em;
  font-family: "InriaSerif-Regular", sans-serif;
  font-size: 40px;
  font-weight: 400;
}
.sports-cricket-kabaddi-volley-ball-basket-ball-food-ball-hand-ball-through-ball-span4 {
  color: #b50909;
  list-style-type: disc;
  padding-left: 1em;
  font-family: "InstrumentSans-Regular", sans-serif;
  font-size: 40px;
  font-weight: 400;
}
```
3RD PAGE
```
<div class="i-phone-16-plus-3">
  <div class="thank-you">THANK YOU</div>
  <div class="ph-7525855685-location-saveetha-engineering-college">
    <span>
      <span class="ph-7525855685-location-saveetha-engineering-college-span">
        PH
      </span>
      <span class="ph-7525855685-location-saveetha-engineering-college-span2">
        :
      </span>
      <span class="ph-7525855685-location-saveetha-engineering-college-span3">
        7525855685.
        <br />
      </span>
      <span class="ph-7525855685-location-saveetha-engineering-college-span4">
        LOCATION:
      </span>
      <span class="ph-7525855685-location-saveetha-engineering-college-span3">
        SAVEETHA ENGINEERING COLLEGE.
      </span>
    </span>
  </div>
</div>

.i-phone-16-plus-3,
.i-phone-16-plus-3 * {
  box-sizing: border-box;
}
.i-phone-16-plus-3 {
  background: #3806ff;
  height: 932px;
  position: relative;
  overflow: hidden;
}
.thank-you {
  color: #ffffff;
  text-align: left;
  font-family: "JacquesFrancois-Regular", sans-serif;
  font-size: 48px;
  font-weight: 400;
  position: absolute;
  left: 36px;
  top: 374px;
  width: 442px;
  height: 326px;
}
.ph-7525855685-location-saveetha-engineering-college {
  text-align: left;
  font-family: "JainiPurva-Regular", sans-serif;
  font-size: 36px;
  font-weight: 400;
  position: absolute;
  left: 129px;
  top: 714px;
  width: 340px;
  height: 153px;
}
.ph-7525855685-location-saveetha-engineering-college-span {
  color: #e11619;
}
.ph-7525855685-location-saveetha-engineering-college-span2 {
  color: #f60c0c;
}
.ph-7525855685-location-saveetha-engineering-college-span3 {
  color: #ffffff;
}
.ph-7525855685-location-saveetha-engineering-college-span4 {
  color: #f40909;
}

```
## OUTPUT:

![alt text](<Screenshot 2025-05-20 204648.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
