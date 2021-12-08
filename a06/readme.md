# Interface Design
Diana Alamari | Digital Humanities 110 | Fall 2021

## Introduction

The purpose of my project is to provide music and film enthusiasts visiting/residing in Hawaii the ability to use one app for all their creative needs within Hawaii. They will be able to search for various creative events or resource they want, such as concerts, workshops, and recording studios. This interface design's purpose is to digitalize the low-fidelity prototypes, and create a common theme after exploring design variations. For design consideration, I referred to Hawaii Creative Industry's website, Google Fonts, Yelp, and Meetup. I digitalized the wireframes on Figma with the iPhone 11-sized wireframes. Details of my design process as well as the digital file of my design variations are provided below.

*Design variations and wireframes: https://www.figma.com/file/60yDKMkVGN9UHxclMeyv6p/a6-prototype-(Copy)?node-id=0%3A1*


### UI Screen Designs

**Color, shape, and typography variations are displayed below.**

|UI Design Variations|
|-----|
|Color variations|
|![Color A6](https://github.com/diana-alamari/DH110-21/blob/main/a06/a6%20color%20variation.png?raw=true)|
|Shape Variations|
|![Shape A6](https://github.com/diana-alamari/DH110-21/blob/main/a06/a6%20shapes%20.png?raw=true)
|Typography Variations|
|![Typography A6](https://github.com/diana-alamari/DH110-21/blob/main/a06/a6%20typography.png?raw=true)

&nbsp;

**The layout test for object proportions and sizing is displayed below.**

|Layout test|
|-----------|
|![Layout test](https://github.com/diana-alamari/DH110-21/blob/main/a06/layout%20test.png?raw=true)|


### Accessibility Test
**Contrast within the light mode and the dark mode of the design are displayed below.

|Mode|Background vs text| Background, button, text|
:--------|:---------:|:----------:
Light|![Light mode, dark text](https://github.com/diana-alamari/DH110-21/blob/main/a06/light%20mode%20dark%20text.png?raw=true)|![Light mode, dark button](https://github.com/diana-alamari/DH110-21/blob/main/a06/light%20mode%20dark%20button.png?raw=true)
Dark|![Dark mode, light text](https://github.com/diana-alamari/DH110-21/blob/main/a06/dark%20mode%20light%20text.png?raw=true)|![Dark mode, light button](https://github.com/diana-alamari/DH110-21/blob/main/a06/dark%20mode%20light%20button.png?raw=true)


### Impression Test

https://youtu.be/5QTaqnH0chQ

- The user was asked to evaluate the design variations by color, typography, and shapes. He asked to switch between frames for deeper evaluation of each. The user expressed appeal in the combined shapes, the Amaranth text, and the dark mode. Ultimately, he seemed most confident in his opinion of the shapes and the color mode. 

### Design details

The *color* variations were created by standard variations of an app: a "dark mode" and a "light/standard mode". 
- Within each color frame, I made sure that all features contrasted with the background to some extent. 
- On the dark mode, the main contrasting features are white, off-white, and red. 
- On the standard mode, the main contrasting features are two types of grey and black. 

   * The content on both modes passed the color-contrast accessibility check.

The *typography* variations were tested through combinations and uniform text styles. 
  -  First image: combination of Playfair, Heebo, and Amaranth
  -  Second: Amaranth only
  -  Third: Playfair only
  -  Fourth: Heebo only

The *shapes* were tested through the following:
  - square features
  - semi-round features
  - round features
  - combination of the above

The grid was originally created with specified margins around the frame, in a 3x5 grid. Ultimately, I used the convenient 10x10 grid and features managed to fit well in the grid.

### Decision
Ultimately, I took some of the user's opinions combined with standard conventions to finalize a general design concept. I decided to select the standard color mode, combination of text types, and combination of shapes (round-edged + circle). I proceeded with the light mode through analyzing research of conventional standards. However, the user's appeal in the dark mode is mentally bookmarked for a future *customizable dark mode option* in the app. The Amaranth preference from the user was considered in my final decision; as a result, I made sure to keep that style in the app. However, I implemented the combination texts based on the features on which the text is placed. For example, the title is appropriate for one style of text, and the button selections are able to be slightly different in style; this is because they serve as completely different aesthetic functions within the same page. Lastly, I found that the user's shape combination preference lined up with standard/general user consensus for apps that are similar in conceptual features, so I used that shape combination.
