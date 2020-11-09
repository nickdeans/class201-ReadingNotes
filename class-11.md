# Readings: Audio, Video, Images

## Images 

Controlling Sizes of Images - You can control the size of an image using the width and height properties in CSS, just like you can for any other box. See below for example.
```
<img src="images/magnolia.jpg" class="large" alt="magnolia">

img.large {
    width: 500px;
    height: 500px;
}
```

Aligning images using CSS -  Web page authors are increasingly using the float property to align images. There are two ways to achieve this. 
1. The float property is added to the class that was created to represent the size of the image. 
2. New classes are created with names such as align-left or align-right to the images to the the left or right of the page. 
```
img.align-left {
    float: left;
    margin-right: 10px;
}
```

Centering Images using CSS - In order to center an image, it should be turned into a block-level element using the display property with a avlue of block. Once the containing element has been made into a block-level element, there are two common ways in which you can horizontally center an image.
1. On the containing element, you can use the text-align property with a value of center.
2. On the image itself, you can use the use the margin property and set the values of the left and right margins to auto.
```
img.align-center {
    display: blcok;
    margin: 0px auto;
}
```

Background Images - The background-image property allows you to place an image behind any HTML element. This could be the entire page or just part of the page.
```
body {
    background-image: url("./img/patterns.jpeg")
}
```

Background Position - When an image is not being repeated, you can use the background-position property to specify where in the browser window the background image should be placed.
```
body {
    background-position: center top;
}
```

## Practical Information 

**Search Engine Optimization(SEO)** - SEO is a huge topic and several books have been written on the subject. It is the practice of trying to help your site appear nearer the top of search engine results when people look for the topics that your website covers. There are two types of SEO.
1. On-Page techniques - The methods you can use on your web pages to improve their rating in search engines. In every page of your website there are seven key places where keywords can appear in order to improve findability. 
    - Page Title
    - URL/ Web Address
    - Headings
    - Text 
    - Link Text 
    - Image ALT Text
    - Page Descriptions
2. Off-Page techniques - Getting other sites to link to you is just as important as on-page techniques. Search engines help determine how to rank your site by looking at the numbers of other sites that link to yours. 