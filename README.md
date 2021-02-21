# Code Refactor Starter Code
-To maintain sequential order of heads, the H2 header in <footer> was changed to H4
-Search Engine Optimization nav-bar id was fixed to properly navigate to the SEO in content section
-<head> container was moved above the <body> container to follow logical HTML structure
-Some meta tag information appeared to be missing.  Meta data was fixed so the browser would be properly, information could be sent to accessibility devices and instruction would then be available for the browser to load the content
-The <title> tag was changed to be the name of the company and shows in full when the mouse hovers over the tab
-Indenting of parent / children elements and spacing were cleaned up throughout both index.html and style.css for the next developer who works on this project.
-Commented descriptions were placed throughout index.html and style.css documents for easier code reading
-Detailed descriptions were placed in image alt attributes for screen readers
-I felt that the .float-left and .float-right classes were somewhat vague so I renamed them to 
.left-content-image and .right-content-image as they were only styling the content images
-The .hero class was changed to .hero-image to be more descriptive
-I deleted an unnecessary "Developer" folder to ensure proper loading and browser reading of index.html and style.css
-There were pproximately three containers were improperly contained as <div> tags with classes which where renamed with proper semantics (footer, nav, aside)

