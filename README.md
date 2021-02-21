# Code Refactor Starter Code
Greetings Horiseon Social Solution Services,

I am excited to present back to you, a completed request for accessibility optimization.
I have put in time and care to ensure your page meets all current accessibility stardards and to make sure
all requirements listed in your acceptence criteria were met.  Below you will find a summarized list of changes, a live URL displaying those changes and an URL to the repository containing your files.

Thank you for this opportunity,
-Aimee Jesso

-Search Engine Optimization nav-bar id was fixed to properly navigate to the SEO in content section
-<head> container was moved above the <body> container to follow logical HTML structure
-Some meta tag information appeared to be missing.  Meta data was fixed so the browser would be properly, information could be sent to accessibility devices and instruction would then be available for the browser to load the content
-The <title> tag was changed to be the name of the company and shows in full when the mouse hovers over the tab
-Indenting of parent / children elements and spacing were cleaned up throughout both index.html and style.css for the next developer who works on this project.
-Commented descriptions were placed throughout index.html and style.css documents for easier code reading
-Detailed descriptions were placed in image alt attributes for assistive devices
-I felt that the .float-left and .float-right classes were somewhat vague so I renamed them to 
.left-content-image and .right-content-image as they were only styling the content images
-The .hero class was changed to .hero-image to be more descriptive
-I deleted an unnecessary "Developer" folder to ensure proper loading and browser reading of index.html and style.css
-There were pproximately three containers were improperly contained as <div> tags with classes which where renamed with proper semantics (footer, nav, aside)
-To maintain sequential order of headers, the H2 header in <footer> was changed to H4
-Some CSS Styles were repeated throughout the Benefits and Content containers which are now consolidated and fewer CSS style lines now exist

Live URL:
https://missaimeejay.github.io/HoriseonSocialSolutionServices/
Github Repository URL: https://github.com/MissAimeeJay/HoriseonSocialSolutionServices
![Screenshot](./ProjectScreenshot.png)
