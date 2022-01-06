<details>
    <summary>CSS-Basics</summary>


## CSS3 Basic Rules
1. Mobile First Mentaility
2. Modual Based Code
3. Web Font Support
4. Enables Faster Development & Load  Times
5. 2D & 3D Animations
6. New Colors & Image Effects
7. Box Sizing Fixes

## ID Selectors
- In CSS will always start with a #

## Class Selectors
- Is used for smaller and individual styles within the page
- It starts with a .
## Element selectors
- Applies to HTML Elements

## All Selectors
- starts with a *


# CSS3 Advanced
## Box Model
- width: 400px;
- border:solid 2px #000;
- padding:10px
- padding-left:10px;
- margin:100px;

## Adding Color
- Use #


## Borders
- border-left:dotted 5px blue;


## Background images
- div tags are containers
- background: url("URL") top center no-repeat;
- class=""

## Styling links
- <a href="#"></a>
- a { color:yellowgreen}

## Styling ID tags
- Create structures to a document
- #topArea { background-color:#000;}
- <div id="topArea"></div>

## Float & Clear
- column
  - float:left;
  - width:200px;
- clear 
  - clear:both;

## Block and Inline elements
- <span> in css will apply css to just that
- display:block;

## Positioning
- <img src="" class="positionMe/>
- positionMe { position: relative; 
  - top:100px;
  - position:fixed;
  - left:50%  }

## Building The Framework
<style>
    #headerArea{
        width:900px;
        height:75px;
        background:url("header.jpg") top center no-repeat
    }

    #sideArea{
        width:300px;
        float:left;
    }

    #textArea{
        width:600px;

    }

    #footerArea{
        width:900px;
        height:400px;
    }
</style>

## Adding the Elements
- Lots of elements from html...

</details>

<details>
<summary>BootStrap 4</summary>

## What is Bootstrap? 
- Framework for building websites. Keep responsive design in mind.
- Download getbootstrap.com
- Responsive meta tag
    <meta name="viewport">
- So read bootstrap documentation to get what you want. 
- Lists are done with <ul></ul>

## Creating Containers
    - <div class="container"> </div>
      - <div class="row">
      - <div class="col-lg-4 col-sm-6">
      - <div class="card"> # Cool images http://placehold.it/
        - <img class="card-img-top">
        - <div class="card-body"> 
          -<h4 class="card-title">
    - Container fluid
      - will go as wide as the browser goes

## Styling images
- class="rounded"
- rounded-circle 
- img-fluid
- img-thumbnail

## Creating the Footer
- footer class="py-5 bg-dark"
  - <div class="container"> 
  - <p>Footer Copy Here </p>
  - fixed-bottom

## Adding styled buttons
- <button type="button" class="btn">

</details>

## Adding Google Maps
- Check google api documentation

## Image Carousel
- class="carousel slide" data-ride="carousel"
  - carousel-indicators
  - data-target="id" data-slide-to="0"
  - Check bootstrap documentation for it...


## Adding a contact form
- <form> 
  - <label for="name">
  - <input type="text" class="form-control" id="name" placeholder="your name">
  - <input type="text" class="form-control" id="email" placeholder="your email">
  -<button type="submit" class="btn btn-primary">Send my message</button>
  
