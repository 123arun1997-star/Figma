# Ex08 Event Registration Web Application
## Date:20.03.2026

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
homepage:1(html)
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="saveetha-engineering" src="img/saveetha-engineering-college-logo-400x400-1.png" />
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <img class="rectangle" src="img/rectangle-1.png" />
      <div class="ellipse"></div>
      <img class="img" src="img/rectangle-2.svg" />
      <div class="text-wrapper">TOURNAMENT</div>
      <div class="div"></div>
      <div class="text-wrapper-2">LOGIN</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">REGISTER</div>
      <div class="ellipse-2"></div>
      <img class="ellipse-3" src="img/ellipse-3.png" />
    </div>
  </body>
</html>
(css)
.iphone-pro-max {
  overflow: hidden;
  background-image: url(./img/iphone-16-17-pro-max-1.png);
  background-size: cover;
  background-position: 50% 50%;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .saveetha-engineering {
  position: absolute;
  top: 74px;
  left: 0;
  width: 440px;
  height: 121px;
}

.iphone-pro-max .text-on-a-path {
  position: absolute;
  top: 324px;
  left: 33px;
  width: 295px;
  height: 68px;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 208px;
  left: -349px;
  width: 179px;
  height: 184px;
}

.iphone-pro-max .ellipse {
  position: absolute;
  top: 306px;
  left: -370px;
  width: 162px;
  height: 100px;
  background-color: #d9d9d9;
  border-radius: 81px / 50px;
  transform: rotate(180deg);
}

.iphone-pro-max .img {
  position: absolute;
  top: 446px;
  left: 96px;
  width: 255px;
  height: 58px;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 458px;
  left: calc(50.00% - 101px);
  width: 215px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 551px;
  left: 113px;
  width: 221px;
  height: 59px;
  background-color: #09469c33;
  box-shadow:
    0px 4px 4px #00000040, inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 560px;
  left: 194px;
  width: 91px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 657px;
  left: 111px;
  width: 223px;
  height: 61px;
  background-color: #17309533;
  border: 1px solid;
  border-color: #000000;
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 666px;
  left: 172px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .ellipse-2 {
  position: absolute;
  top: 227px;
  left: 152px;
  width: 5px;
  height: 9px;
  background-color: #d9d9d9;
  border-radius: 2.5px / 4.5px;
}

.iphone-pro-max .ellipse-3 {
  position: absolute;
  top: 227px;
  left: 113px;
  width: 223px;
  height: 179px;
}
Homepage:2(HTML)
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="rectangle" src="img/rectangle-5.svg" />
      <div class="text-wrapper">TOURNAMENT</div>
      <div class="div"></div>
      <div class="text-wrapper-2">BATTLE ROYALE</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">CLASH SQUAD</div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-4">LONE WOLF</div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-5">HEAD SHOT 2V2</div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-6">HEAD SHOT 4V4</div>
    </div>
  </body>
</html>
(CSS)
.iphone-pro-max {
  background-image: url(./img/iphone-16-17-pro-max-2.png);
  background-size: cover;
  background-position: 50% 50%;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 104px;
  left: 36px;
  width: 369px;
  height: 82px;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 96px;
  left: 76px;
  width: 311px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #ed51e8;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 233px;
  left: 36px;
  width: 369px;
  height: 84px;
  background-color: #ed15ed33;
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 233px;
  left: 61px;
  width: 326px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #f37aef;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 356px;
  left: 36px;
  width: 377px;
  height: 82px;
  background-color: #cd12a433;
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 346px;
  left: 76px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #f561f0;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 500px;
  left: 45px;
  width: 368px;
  height: 77px;
  box-shadow:
    0px 4px 4px #00000040, 0px 4px 4px #00000040, 0px 4px 4px #00000040, 0px 4px 4px #00000040, 0px 4px 4px #00000040;
}

.iphone-pro-max .rectangle-4 {
  position: absolute;
  top: 487px;
  left: 36px;
  width: 377px;
  height: 82px;
  background-color: #cd2f9333;
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 485px;
  left: 103px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #eb5acc;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-5 {
  position: absolute;
  top: 638px;
  left: 36px;
  width: 377px;
  height: 82px;
  background-color: #e71ae733;
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
}

.iphone-pro-max .text-wrapper-5 {
  top: 636px;
  color: #db5fb6;
  position: absolute;
  left: 59px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-6 {
  position: absolute;
  top: 773px;
  left: 35px;
  width: 378px;
  height: 88px;
  background-color: #ef2ad833;
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
}

.iphone-pro-max .text-wrapper-6 {
  top: 773px;
  width: 325px;
  color: #d85ccf;
  position: absolute;
  left: 59px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}
HOME PAGE:3(HTML)
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <div class="text-wrapper">EVENT REGISTRATION FORM</div>
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <img class="img" src="img/rectangle-15.svg" />
      <div class="text-wrapper-2">Email ID :</div>
      <div class="text-wrapper-3">:</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-4">Phone No:</div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-5">District :</div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-6">Squad Name :</div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-7">Age:</div>
      <div class="text-wrapper-8">Full Name :</div>
    </div>
  </body>
</html>
(CSS)
.iphone-pro-max {
  position: relative;
  width: 440px;
  height: 956px;
  mix-blend-mode: exclusion;
  background-blend-mode: darken;
  background-image: url(./img/iphone-16-17-pro-max-3.png);
  background-size: cover;
  background-position: 50% 50%;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 56px;
  left: 56px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #edff00;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 42px;
  left: 34px;
  width: 371px;
  height: 75px;
  background-color: #d9d9d933;
  border: 1px solid;
  border-color: #ffffff;
  box-shadow:
    0px 4px 4px #00000040, inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
}

.iphone-pro-max .div {
  position: absolute;
  top: 158px;
  left: 34px;
  width: 371px;
  height: 78px;
  background-color: #d9d9d933;
  border: 1px solid;
  border-color: #f3f0f0;
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 282px;
  left: 34px;
  width: 371px;
  height: 81px;
  background-color: #f6f6f033;
  border: 1px solid;
  border-color: #ddff00;
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
  opacity: 0.1;
}

.iphone-pro-max .img {
  position: absolute;
  top: 397px;
  left: 42px;
  width: 368px;
  height: 83px;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 415px;
  left: 56px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 544px;
  left: 102px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 516px;
  left: 36px;
  width: 364px;
  height: 82px;
  background-color: #d9d9d933;
  border: 1px solid;
  border-color: #fff7f7;
  box-shadow:
    0px 4px 4px #00000040, inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 535px;
  left: 50px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-4 {
  position: absolute;
  top: 630px;
  left: 42px;
  width: 363px;
  height: 83px;
  background-color: #d9d9d933;
  border: 1px solid;
  border-color: #fff9f9;
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 642px;
  left: 61px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-5 {
  position: absolute;
  top: 768px;
  left: 42px;
  width: 374px;
  height: 83px;
  background-color: #d9d9d933;
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 782px;
  left: 53px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-6 {
  position: absolute;
  top: 282px;
  left: 36px;
  width: 374px;
  height: 81px;
  background-color: #d9d9d933;
  border: 1px solid;
  border-color: transparent;
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
}

.iphone-pro-max .text-wrapper-7 {
  position: absolute;
  top: 299px;
  left: 56px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-8 {
  position: absolute;
  top: 173px;
  left: 56px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}
HOMEPAGE:4(HTML)
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="rectangle" src="img/rectangle-20.png" />
      <div class="text-wrapper">THANK YOU</div>
      <div class="div"></div>
      <p class="we-are-all-eagerly">
        We are all eagerly waiting for your participte in the&nbsp;&nbsp;free fire tournament .
      </p>
      <div class="rectangle-2"></div>
      <img class="img" src="img/rectangle-23.svg" />
      <div class="phone-no">
        Phone No: 876543287<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        7656765435
      </div>
      <div class="text-wrapper-2">email no : freefiereindiaofficial@gmail.com</div>
      <div class="text-wrapper-3">Contact us :</div>
    </div>
  </body>
</html>
(CSS)
.iphone-pro-max {
  overflow: hidden;
  background-image: url(./img/iphone-16-17-pro-max-4.png);
  background-size: cover;
  background-position: 50% 50%;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 76px;
  left: 16px;
  width: 408px;
  height: 137px;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 294px;
  left: 38px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 316px;
  left: 16px;
  width: 408px;
  height: 104px;
  background-color: #d9d9d933;
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
}

.iphone-pro-max .we-are-all-eagerly {
  position: absolute;
  top: 530px;
  left: calc(50.00% - 182px);
  width: 386px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 478px;
  left: 503px;
  width: 166px;
  height: 180px;
  background-color: #fc1fbd33;
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
}

.iphone-pro-max .img {
  position: absolute;
  top: 726px;
  left: 3px;
  width: 436px;
  height: 230px;
}

.iphone-pro-max .phone-no {
  position: absolute;
  top: 854px;
  left: 103px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 809px;
  left: 38px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 726px;
  left: 91px;
  font-family: "Jaini Purva-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}



```



## OUTPUT:
![alt text](<Screenshot (18).png>)
![alt text](<Screenshot (19).png>)
![alt text](<Screenshot (20).png>)
![alt text](<Screenshot (21).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
