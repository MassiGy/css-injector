# CSS-INJECTOR BASH SCRIPT USAGE GUID

## Description
		CSS Injector - Bash Based CSS to Html Injector.

This script is designed to take the passed css file, read the passed html file, and then inject the css file code into the html inside a <style> tag as a replace for the <link> tag . The goal behind this command is to load the css inside your html, in order to minimize the http requests on the template rendering (gain more performance and space). The most optemized way to use this tool, is to add it into your build tasks.



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
 
	css-injector  <inject_form.css> <inject_to.html>


 
Exemples
	css-inejector  style.css index.html 

## License
MIT.




