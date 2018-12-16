# Lesson 7: Starting Small
- Resources:
	- [xxx](https://xxx)

### *1. Defining the Viewport*
- Resources:
	- [xxx](https://xxx)

- Set Viewport Size: 
	- Defines area browser can render content to.
	- xxx
	- xxx

### *2. Pixels*
- Resources:
	- [xxx](https://xxx)

- DIP (Device Independent Pixels): 
	- Different from Hardware pixels.
	- Font boosting: When DIP incorrectly set for viewport.
	- xxx

### *4. Pixels*
- Resources:
	- [xxx](https://xxx)

- DPR (Device Pixel Ratio): 
	- xxx
	- xxx
	- xxx


### *6. Calculate CSS Pixels for Viewport*
- Resources:
	- [xxx](https://xxx)

- CSS Pixels: 
	- Hardware Pixels / Device Pixel Ratio or 
	- Hardware Pixels * (1 CSS Pixel / Device Pixel Ratio)
	- e.g. 1920 Hardware Pixels / 2 Device Pixel Ratio = 960 CSS Pixels Max. for Viewport
	- xxx

### *7. Calculate CSS Pixels for Viewport Width*
- Resources:
	- [xxx](https://xxx)

- CSS Pixels: 
	- Hardware Pixels / Device Pixel Ratio or 
	- Hardware Pixels * (1 CSS Pixel / Device Pixel Ratio)
	- e.g. 640px Width / 2 DPR = 320 CSS Pixels Max. Width for Viewport
	- e.g. 768px Width / 2.5 DPR = 307 CSS Pixels Max. Width for Viewport
	- e.g. 1024px Width / 1 DPR = 1024 CSS Pixels Max. Width for Viewport
	- e.g. 800px Width / 1 DPR = 800 CSS Pixels Max. Width for Viewport

### *8. Setting the Viewport*
- Resources:
	- [Using the viewport meta tag to control layout on mobile browsers](https://developer.mozilla.org/en-US/docs/Mozilla/Mobile/Viewport_meta_tag)

- Set Viewport: 
	- <meta name="viewport" content="width=device-width, initial-scale=1">

### *9. Max-width on Elements*
- Resources:
	- [xxx](https://xxx)

- Set Width w/ Relative Units: 
	- img, embed, 
	  object, video {
	  	max-width: 100%;

	  }

### *12-13. Tap Target Sizes*
- Resources:
	- [big list of CSS properties.](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#Keyword_index)

- Set Width and Height to 48px: 
	- nav a, button {
			min-width: 48px;
			min-height: 48px;
		}

### *14. Tap Target Sizes*
- Resources:
	- [xxx](https://xxx)

- Start with smallest device (This prioritizes performance).
	- Phone
	- Tablet
	- Desktop

### *16. Project Solution*
- Resources:
	- [relative unit](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Values_and_units#Numeric_values)
	- [inherit KEYWORD](https://developer.mozilla.org/en-US/docs/Web/CSS/inherit)
	- [Flexbox example](https://storage.googleapis.com/supplemental_media/udacityu/3520169345/pattern-mostly-fluid-quiz-blankcss.html)


- Solutions:
	- <meta name="viewport" content="width=device-width, initial-scale=1">
	- width: 100%;
	- padding: 1.5em inherit; (Tap targets for <a> elements)
	- padding: 1.5em; (Tap targets for <a> elements)