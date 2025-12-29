# Ex09 Event Registration Web Application
## Date:25/12/2025

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
home page

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="image">
      <img class="img" src="img/image-1.png" />
      <img class="rectangle" src="img/rectangle-1.svg" />
      <div class="div"></div>
      <div class="LOGIN">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;LOGIN</div>
      <div class="REGISTER">&nbsp;&nbsp;&nbsp;&nbsp; REGISTER</div>
      <div class="ART-COMPETITION"><br />ART COMPETITION</div>
    </div>
  </body>
</html>



.image {
  position: relative;
  width: 593px;
  height: 889px;
  background-color: #a01d1d;
  border: 1px solid;
  border-color: #000000;
  aspect-ratio: 0.67;
}

.image .img {
  position: absolute;
  width: 100.00%;
  height: 100%;
  top: 0;
  left: 4.22%;
  object-fit: cover;
}

.image .rectangle {
  position: absolute;
  width: 37.67%;
  height: 5.90%;
  top: 35.30%;
  left: 27.69%;
}

.image .div {
  position: absolute;
  width: 37.85%;
  height: 6.02%;
  top: 45.25%;
  left: 27.60%;
  background-color: #d47741;
}

.image .LOGIN {
  position: absolute;
  width: 32.99%;
  height: 4.63%;
  top: 36.57%;
  left: 30.38%;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.image .REGISTER {
  position: absolute;
  width: 30.56%;
  height: 3.36%;
  top: 46.64%;
  left: 31.08%;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.image .ART-COMPETITION {
  position: absolute;
  width: 36.09%;
  height: 11.59%;
  top: 17.32%;
  left: 25.46%;
  font-family: "JejuHallasan-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

event page

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="image" src="img/image-5.png" />
      <img class="rectangle" src="img/rectangle-3.svg" />
      <div class="EVENTS-WALL-PAINTING">EVENTS<br /><br /><br />WALL PAINTING</div>
      <div class="text-wrapper">WATER PAINTING</div>
      <div class="div">OIL PAINTING</div>
      <div class="text-wrapper-2">ACRYLIC PAINTING</div>
      <div class="text-wrapper-3">DIGITAL ART</div>
      <p class="theme-save-water">theme<br /><br />Save Water<br />Chennai Heritage &amp; Culture</p>
    </div>
  </body>
</html>

.iphone {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 427px;
  min-height: 874px;
  position: relative;
}

.iphone .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 427px;
  height: 874px;
  aspect-ratio: 0.67;
  object-fit: cover;
}

.iphone .rectangle {
  position: absolute;
  top: 284px;
  left: -591px;
  width: 293px;
  height: 224px;
}

.iphone .EVENTS-WALL-PAINTING {
  position: absolute;
  top: 204px;
  left: 33px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper {
  position: absolute;
  top: 426px;
  left: 29px;
  width: 243px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .div {
  position: absolute;
  top: 375px;
  left: 0;
  width: 263px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 464px;
  left: 13px;
  width: 291px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 502px;
  left: -52px;
  width: 356px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .theme-save-water {
  position: absolute;
  top: 585px;
  left: 47px;
  width: 385px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

registration page

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="image" src="img/image-3.png" />
      <img class="text-on-a-path" src="img/text-on-a-path-2.svg" />
      <div class="REGISTRATION-FORM">
        REGISTRATION FORM<br /><br />NAME:<br /><br /><br /><br />
        AGE:<br /><br /><br /><br />GENDER:<br /><br /><br /><br />DEPARTMENT:<br /><br /><br /><br />MOBILE.NO:<br /><br /><br /><br />EMAIL
        ID:
      </div>
      <img class="rectangle" src="img/rectangle-4.svg" />
      <div class="div"></div>
      <img class="img" src="img/rectangle-6.svg" />
      <div class="rectangle-2"></div>
      <img class="rectangle-3" src="img/rectangle-8.svg" />
      <div class="rectangle-4"></div>
      <img class="text-on-a-path-2" src="img/text-on-a-path.svg" />
      <img class="text-on-a-path-3" src="img/image.svg" />
      <div class="rectangle-5"></div>
      <div class="text-wrapper">Register</div>
    </div>
  </body>
</html>

.iphone {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 400px;
  min-height: 874px;
  position: relative;
}

.iphone .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 400px;
  height: 874px;
  aspect-ratio: 2.74;
  object-fit: cover;
}

.iphone .text-on-a-path {
  position: absolute;
  top: 103px;
  left: -1053px;
  width: 289px;
  height: 78px;
}

.iphone .REGISTRATION-FORM {
  position: absolute;
  top: 47px;
  left: 69px;
  width: 245px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle {
  position: absolute;
  top: 142px;
  left: 107px;
  width: 246px;
  height: 49px;
}

.iphone .div {
  position: absolute;
  top: 257px;
  left: 111px;
  width: 246px;
  height: 47px;
  background-color: #ff9b9b;
}

.iphone .img {
  position: absolute;
  top: 376px;
  left: 115px;
  width: 238px;
  height: 49px;
}

.iphone .rectangle-2 {
  position: absolute;
  top: 496px;
  left: 127px;
  width: 230px;
  height: 46px;
  background-color: #ff9b9b;
}

.iphone .rectangle-3 {
  position: absolute;
  top: 605px;
  left: 123px;
  width: 230px;
  height: 50px;
}

.iphone .rectangle-4 {
  position: absolute;
  top: 722px;
  left: 114px;
  width: 239px;
  height: 51px;
  background-color: #ff9b9b;
}

.iphone .text-on-a-path-2 {
  top: 816px;
  width: 174px;
  height: 63px;
  position: absolute;
  left: -921px;
}

.iphone .text-on-a-path-3 {
  top: 824px;
  width: 178px;
  height: 55px;
  position: absolute;
  left: -921px;
}

.iphone .rectangle-5 {
  position: absolute;
  top: 795px;
  left: 201px;
  width: 165px;
  height: 63px;
  background-color: #ff9b9b;
}

.iphone .text-wrapper {
  position: absolute;
  top: 819px;
  left: 233px;
  width: 120px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

end of the page

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="image" src="img/image-4.png" />
      <p class="WITHOUT-ART-JUST-THE">WITHOUT ART JUST THE <br />EARTH IS EH</p>
      <div class="THANK-YOU-for">
        THANK YOU<br />
        for registering
      </div>
      <div class="contact">contact:8889991112<br />email:artworld@gmail.com</div>
    </div>
  </body>
</html>

.iphone {
  background-color: #ffc9e7;
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  position: relative;
}

.iphone .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 393px;
  height: 852px;
  aspect-ratio: 0.59;
  object-fit: cover;
}

.iphone .WITHOUT-ART-JUST-THE {
  position: absolute;
  top: 268px;
  left: 53px;
  width: 311px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .THANK-YOU-for {
  position: absolute;
  top: 501px;
  left: 83px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .contact {
  position: absolute;
  top: 713px;
  left: 27px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}






## OUTPUT:

<img width="470" height="778" alt="530467415-cde643a4-ff1d-4623-9fb8-1ecbb66fadd9" src="https://github.com/user-attachments/assets/547cd336-9acc-42bd-8bfe-b36195474d8f" />
<img width="453" height="783" alt="530467428-3e0f95e4-0c67-41f6-881d-8d6f8f2994bc" src="https://github.com/user-attachments/assets/c4632065-d768-453c-b9a4-940a425525a1" />
<img width="422" height="788" alt="530467447-2618e59f-c162-42e4-bccd-d6f019086207" src="https://github.com/user-attachments/assets/f943eadc-e88b-4d77-a41b-79413ad23558" />




## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
