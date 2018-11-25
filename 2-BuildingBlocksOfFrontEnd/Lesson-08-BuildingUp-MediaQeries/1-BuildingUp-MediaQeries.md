# Lesson 8: Building Up-Media Queries
- Resources:
	- [Media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)

### *1-2. Responsive design*
- Resources:
	- [xxx](https://xxx)

- Changes according to device (use Media queries): 
	- Phone
	- Tablet
	- Desktop
	- etc.

### *3. Media queries*
- Resources:
	- [xxx](https://xxx)

- Media query as Linked separate stylesheet: 
	- e.g. Media query Stylesheet for over 500px width: 
	- <link rel="stylesheet" media="screen and (min-width:500px)" href="over500.css">
	- body {
		background-color: blue;
	  }
	- *Performance: Many small http requests.*

### *4. Media queries*
- Resources:
	- [xxx](https://xxx)

- Embed as property: 
	- e.g. @media screen and (min-width: 500px) {
				body {background-color: green;}
           } 
    - *Performance: Few big http requests.*

### *5. Media queries*
- Resources:
	- [Media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)

- Most common: 
	- min-width
	- e.g. @media screen and (min-width: 400px) {}
		- 400px or more
	- max-width
	- e.g. @media screen and (max-width: 500px) {}
		- 500px or less
	- min-width and max-width
	- e.g. @media screen and (min-width: 401px) and (max-width: 599px) {
        body {background-color: green;}
      }


### *7-11. Breakpoints Media queries*
- Resources:
	- [xxx](https://xxx)

- Breakpoints: 
	- Changes entire Layout at these points.
	- Pick breakpoints based on website's content.

- Pick Breakpoints based on content: 
	- e.g. min-width: 550px; min-width: 700px;
	- <meta name="viewport" content="width=device-width, initial-scale=1.0">
	- <link rel="stylesheet" href="weather.css"><!--For any width.-->
	- <link rel="stylesheet" media="screen and (min-width: 550px)" href="weather-medium.css">
	- <link rel="stylesheet" media="screen and (min-width: 700px)" href="weather-large.css">

### *14. Media queries*
- Resources:
	- [Media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)

- Media queries: 
	- @media screen and (max-width: 400px)
	- @media screen and (min-width: 301px) and (max-width: 600px)
	- @media screen and (min-width: 601px)
	- @media screen and (min-width: 961px)

### *15. Grid*
- Resources:
	- [Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout)
