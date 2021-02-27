HW 01 HTML, CSS, and Git: Code Refactor

HTML file modifications:
Line 7: Changed title to Horiseon for browser tab.

Line 11: Changed div tag to header tag because this is at the head of the website page.

Line 13: Changed div tag to nav tag because these are navigational buttons.

Line 16: I noticed that when clicked, it did not scroll down to the Search Engine Optimization paragraph. Online Reputation Management and Social Media Marketing buttons did though. I found that by adding an id of "search-engine-optimization" to line 30, it fixed this.

Line 28: Changed tag from div to article to separate the image from the rest of the content on the webpage. Attempted to use img tag, but left a gap between the header and hero image.

** Line 29: Changed tag from div to main because this is the main part of the content on the webpage.

Line 30: Changed tag from div to section to organize each block of content. Added id="search-engine-optimization" to allow nav button to scroll down to this body of content.

Line 31: Added alt="image of notebook on desk with brainstorming ideas" to describe photo to improve accessibility of the website.

Line 38: Added alt="image of laptop screen displaying a graph of reputation growing." to describe photo to improve accessibility of the website.

Line 45: Added alt="image of desk covered with stickers referencing social media " to describe photo to improve accessibility of the website.

Line 52: Changed tag from div to aside to organize and identify fty information and images to the right.

Line 75: Changed tag from div to footer to identify footer of the page.



CSS file modifications:
Line 27, 35, 39: div tag in line 13 of HTML file was changed to nav, so div in CSS file was changed to nav.

Line 89: (.benefit-lead, .benefit-brand, .benefit-cost) all shared identical attributes and values, so they were combined into one line of code and separated with commas.

Line 94: (.benefit-lead h3, .benefit-brand h3, .benefit-cost h3) all shared identical attributes and values, so they were combined into one line of code and separated with commas.

Line 99: (.benefit-lead img, .benefit-brand img, .benefit-cost img) all shared identical attributes and values, so they were combined into one line of code and separated with commas.

Line 114: (.search-engine-optimization img, .online-reputation-management img, .social-media-marketing img) all shared identical attributes and values, so they were combined into one line of code and separated with commas.

Line 118: (.search-engine-optimization h2, .online-reputation-management h2, .social-media-marketing h2) all shared identical attributes and values, so they were combined into one line of code and separated with commas.

Github URL: https://github.com/wilks625
Github Repo URL: https://wilks625.github.io/hw-week-1/
