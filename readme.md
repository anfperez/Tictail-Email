# Tictail E-mail Example

## Link on CodePen: https://codepen.io/anfperez/pen/Pebwyr

## Technologies Used

* HTML5
* CSS3

## Tools Utilized
* Sublime Text Editor
* Adobe Illustrator
* Digital Color Meter
* Chrome Developer Tools (iPhone 6/6s/7/8 emulator)

## Assets
* [Hipster Ipsum](https://hipsum.co/) 
* [Social Media Icons by Daniel Oppel](https://dribbble.com/shots/1509889-Free-Social-Media-Icons) 
* [Instagram Stock Photos by Rekita Nicole](http://www.rekitanicole.com/blog/2015/8/free-stock-photos)
* [Google Fonts: Tajawal](https://fonts.google.com/specimen/Tajawal)

## Process

When I received this assignment, I was excited to use my CSS skills to be able to work from a spec and build a project from scratch. I did some research and figured that CSS Flexbox would be the best way to go about implementing the 3-column system.

First, I made a rough prototype of what I wanted the main site to look like on Webflow.io: http://angelas-first-project-5c907a.webflow.io/.

I took care of the basic assets first. I found the sample images online by doing an image search. For the social media icons, I downloaded a trial of Adobe Illustrator in order to export the individual icons out of a vector art file. I decided to use "Hipster Ipsum" instead of the usual Ipsum Lorem text. Next, I used a program called Digital Color Meter to figure out the exact rgb/hex codes for the colors I needed. I kept the same colors for the background and the font colors for the headers, paragraphs, and links. For the font, I selected a Google Font called Tajawal. I wanted to emulate the font in the e-mail, which is sans-serif. 

I decided to work with Flexbox since it offered me a simple toolset that I could use to implement the 3x3 grid. I was able to get it to work by using the "display: flex" property. I also placed the columns inside containers called "grids". Similar to Bootstrap, the grid can be divided up into 1-12 columns. For the 3x3 grid, I made to sure to place three similarly titled columns ("col-1-3") to divide up the grid. Almost all the columns used on the page are 1/3, except for one column which is 1/2.

This is the current column structure on the page:

container
H2
p
grid
	1/3 - 1/3 - 1/3
	1/3 - 1/3 - 1/3
	1/3 - 1/3 - 1/3
hr
grid
	1/3 - 1/3 - 1/3
	1/3 - 1/3 - 1/3
grid
	1/2 - 1/2 
grid
	1/3 - 1/3 - 1/3

All links open in a new tab. Most of the links are configured to lead to the main Tictail site (www.tictail.com), but the social media links lead directly to each of Tictail's social media pages.

## Mobile Version 

I knew that I wanted the e-mail to be responsive to mobile devices. In order to make this happen, I consulted a list of common breakpoints for different devices. I found [this](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/) list very useful. Ultimately, I picked out the breakpoint for the iPhone 6, 7, 8 to use in the e-mail project. If this was an actual e-mail, I would implement more screen sizes, device types, and browsers.

The e-mail is now responsive in that when a user views it on an iPhone 6, 6s, 7, or 8, the images will stack on top of each other instead of being presented in a 3x3 grid. I used the Emulator dev tool built into Chrome to view the e-mail on an iPhone-sized screen. 

In all, I tried to keep both the HTML and CSS files as short as possible while still having the range of functionality needed.

I added a short screen recording I made using QuickTime Player to demonstrate what the e-mail looks like on mobile.

## Future Improvements

* implement Trello Board for ease of done/future tasks
* for the mobile version of the website, the section at the bottom containing the first two links isn't spaced correctly. There is too much space between the first and second large links. 
* the series of links that read "Links to another category" and "Explore Tictail" should be centered. I tried using "justify-content: center" and "align-items: center", but neither seemed to work. With more time, I should be able to figure out why these links aren't being centered.

## Thoughts

I really enjoyed preparing this coding assignment. I was able to practice much of the front-end design work I have done in the past, both at jobs and in personal projects. I have also never worked with a vector graphics sheet before, but learning how to open it and export individual images using Adobe Illustrator turned out to be surprisingly easy. Thank you for giving me the opportunity to turn this sample e-mail into real HTML and CSS. 

![tictail](https://github.com/anfperez/Tictail-Email/blob/master/iPhone_example.gif "tictail")
