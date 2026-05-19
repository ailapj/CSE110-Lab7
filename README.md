## Check for Understanding 

# 1 
I would fit an automated test in the Recipe project development pipeline within a github action that runs whenever code is pushed because it'd help catch bugs early before the code gets merged or deployed. It allows for testing to be done in increments, and for new changes to not break exisiting functions. This is more reliable that running tests manually since there is no guarantee that the manual test will happen regularly, and waiting until all development is done is risky since bugs might pile up and it would be hard to detect them. 

# 2 
No. E2E is for entire applicaiton flow and correct output is a more suitable case for unit testing 

# 3 
The difference between navigation and snapshot mode is that navigation mode analyzes the website while the page is loading from the start. This way, it can measure and score loading speed and performance during startup. The Search engine optimization focuses on page metada and document strucutre, and best practices check for security. On the other hand, snapshot mode analyzes the page in the current state it's at without reloading the page. This way, it focuses more on the accessibility of the website, and that the current page follows best practices of input fields, images, and aspect ratio. 

# 4 
1) We can improve the SEO by including meta data to the document. 
2) We can improve the accessibility of the page by adding a [lang] attribute to the <html> element. This will allow the screen reader to know how to pronounce the words on the page, increasing accessibility. 
3) We can improve performance of the page by reducing/avoiding chaining critical requests. Right now, the css and JS files are connected to the HTML page and are loaded only after the HTML file. This delays rendering and creates latency. By reducing the JS file sizes, or combining files, we can increase speed and therefore performance. 


