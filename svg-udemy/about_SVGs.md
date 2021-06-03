# What it is? 
- Stands for Scaleable Vector Graphics
- A kind of image format
	- Other image formats include jpg, gif, png. These are raster based
	- SVG is vector based, which means it is made with math. It can scale
	infinitely, which makes it great for things like logos, simple designs,
	snappy elements
- It's just XML, so if you're used to HTML tags, it should make sense

# Why use SVG?
- Can scale infinitely because it's just math. That means it's resolution independent
	- Contrast to loading different logo images for different resolutions (e.g. retina screens)
- Can be created with code. This can be pretty complex, but it's just XML. 
- Good support among all modern browsers (canIuse)
- Open standard (W3C) and can be used anywhere
- Smaller file size compared to a bitmapped file
- Can style shapes in CSS and make them interactive with JavaScript
	-Can programmatically manipulate shapes, sizes, positions with CSS and JS
	- E.g. applying a filter or adding interactivity
- Optional: Let the computer do the hard work instead of doing multiple HTTP requests by 
using inline SVG 


# How to use SVG?
- There are several ways to use, but the most commons ones are:

- Embed directly inside <svg> tags
	- E.g. :
		<svg>
    	<rect width="500" height="250"/>
		</svg>
	- Advantages of this method is that you can access it via the DOM and modify
	using JS and CSS
	- Disadvantages is that asset is not cacheable like img or background-image 

- Using the <img> tag
	- E.g: 
		<img src="mylogo.svg" alt="My Logo">
		- Advantages : easy, can be cached for good performance
		- Disadvantages : cannot be manipulated with JS or CSS
	- Good for logos or icons that don't need to be altered

- SVG as background image
	- E.g.: 
		.main {
			background: url(mybackground.svg);
		}

	- Advantages : can be cached, resolution independent
	- Disadvantages : like with <img>, cannot be manipulated with JS or CSS


# Creating SVGs 
- Can be created with code but this can get pretty complex. 
- (Show demo)
- Lots of people get put off by the concept of the 'vector' aspect of SVGs, but
you can generally create your designs in something like Illustrator, Inkscape, or 
other online tools like svg-edit (https://svg-edit.github.io/svgedit/releases/svg-edit-2.8.1/svg-editor.htm;).





