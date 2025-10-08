# Ex09 Event Registration Web Application
## Date: 08/10/2025
## Name: Tharun S
## Ref No: 25007797

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
PAGE 1

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
    <div class="android-compact">
      <img class="sports-bg" src="img/sports-bg-1.png" />
      <img class="intersect" src="img/intersect.png" />
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="text-wrapper">REGISTER NOW</div>
      <div class="div">SPORTS MEET</div>
      <div class="rectangle"></div>
    </div>
  </body>
</html>

globals.css

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
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 412px;
  min-height: 917px;
  position: relative;
}

.android-compact .sports-bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 412px;
  height: 917px;
  aspect-ratio: 1.65;
  object-fit: cover;
}

.android-compact .intersect {
  position: absolute;
  top: 311px;
  left: 59px;
  width: 322px;
  height: 67px;
  object-fit: cover;
}

.android-compact .text-on-a-path {
  position: absolute;
  top: 743px;
  left: -312px;
  width: 215px;
  height: 53px;
}

.android-compact .text-wrapper {
  position: absolute;
  top: 738px;
  left: 126px;
  width: 243px;
  -webkit-text-stroke: 1px #ff0d0d;
  font-family: "JejuHallasan-Regular", Helvetica;
  font-weight: 400;
  color: #ff0004;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .div {
  position: absolute;
  top: 489px;
  left: 99px;
  width: 290px;
  -webkit-text-stroke: 1px #ff0a0a;
  font-family: "Jolly Lodger-Regular", Helvetica;
  font-weight: 400;
  color: #111ed2;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .rectangle {
  position: absolute;
  top: 730px;
  left: 117px;
  width: 253px;
  height: 50px;
  background-color: #e5fd0e;
  border-radius: 100px;
  opacity: 0.75;
}

PAGE 2

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
    <div class="image"><img class="rectangle" src="img/rectangle.png" /></div>
  </body>
</html>

globals.css

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

.image {
  width: 436px;
  height: 549px;
}

.image .rectangle {
  position: fixed;
  top: 29px;
  left: 24px;
  width: 412px;
  height: 520px;
  aspect-ratio: 0.79;
  object-fit: cover;
}

PAGE 3

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
    <div class="image"><img class="sports" src="img/sports-2-1.png" /></div>
  </body>
</html>

globals.css

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

.image {
  width: 512px;
  height: 917px;
}

.image .sports {
  position: fixed;
  top: -208px;
  left: 209px;
  width: 412px;
  height: 916px;
  aspect-ratio: 1.82;
  object-fit: cover;
}

```


## OUTPUT:

<img width="1920" height="1080" alt="Screenshot (42)" src="https://github.com/user-attachments/assets/cf6b660c-f7c0-41af-934e-7a157c5f1b65" />


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
