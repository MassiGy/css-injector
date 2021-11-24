# CSS-INJECTOR BASH SCRIPT USAGE GUID

## Description
		CSS Injector - Bash Based CSS to Html Injector.

This script is designed to take the linked css files declared inside an html file, read them and then inject the code into the html inside a <style> tag. The goal behind this command is to load the css inside your html, in order to minimize the http requests on the template rendering (gain more performance and space). The most optemized way to use this tool, is to add it into your build tasks.



## Setup
	
	git clone <this repo url>
	--
	cd css-injector
	--
	cp ./css-injector /usr/bin/css-injector
	--
	// OPTIONAL
	which css-injector

The expected output of the last command is "/usr/bin/css-injector"

##### Note 
Now you can run the css-injector command anywhere in your machine.



## Benefits of css-inejector
1. Easy to use.	
2. Less http requests.
3. Less files to store, more space to gain.	
4. Very Modular.


## Usage
 
	css-injector  <file.html>

##### Note
The file.html should be in the pwd directory alongside the css file that it is linking to. 
 
Exemples
	css-inejector index.html 

## License
MIT.




