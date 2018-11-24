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

- Set Viewport: 
	- img, embed, 
	  object, video {
	  	max-width: 100%;

	  }

