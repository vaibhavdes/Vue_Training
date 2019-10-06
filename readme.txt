Vue:
	It is a Javascript based Framework used to build UI and Front-End of Web Applications
Editor Recommeded:
	Visual Studio Code 
		https://code.visualstudio.com/download
	Plugins Recommeded:
			Prettier (By Esben)
			Vetur (By Pine)
How to get Started:
	1. Install NodeJS with NPM
		https://nodejs.org/en/download/
	2.	Open Node.js Command Prompt
		(Execute Following Commands in Sequence)
			npm install -g @vue/cli
			(Node Change Directory where you want to create your first Vue Project)
			vue create hello-world
			(Pick Default - Babel)
			cd hello-world
			(Yes Now we are ready to Deploy Project)
			npm run serve
	3.	Open Browser
			Enter URL: http://localhost:8080 

What's Next?
	Go through the Repo in Following Sequence
		1. package.json (All required libraries are mentioned into this)
		2. public/index.html (Vue is Single Page Applications (SPA) based, so all components we create are rendered in "Div" in this file by manipulating Virtual DOM)
		3. src/main.js (Vue Root Instance - Entrypoint : It does the work of rendering components in "Div")
		4. src/app.vue (Vue Root Component)
		5. src/assets	(All Media or Any other files here)
		6. src/components/HelloWorld.vue	(Our First Component)
	
	Read Comments in Each File according to numbering, make modification in your created project and You will understand the working and concepts.
	
Happy Learning!
		
		
	Some Basics:
		1) Structure of Every Component		
				1) <template></template> (Here comes all html tags)
				2) <script></script> (Props,Methods etc Functionality here)
				3) <style></styple>	(Add all styling css syntax here)
