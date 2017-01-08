# D3- [Data Driven Documents] (https://d3js.org/)

## Initial set-up

You can get your local server running by fllowing the below steps (root access might be needed)

1. apt-get install nodejs
2. npm install -g http-server or apt-get install npm
3. npm install forever -g
4. sudo ln -s "$(which nodejs)" /usr/bin/node
5. http-server & 
This will start the server on http://localhost:8080 from the current working directory.

### Fundamentals

1. HTML
2. DOM
3. CSS
4. JavaScript
5. SVG
6. Developer Tools


HTML- It is used to structure content for web browsers-- how you decide what goes where on your page. 

DOM- Your HTML has a hierarchical structure just like your family., parents and children. Web browserrs parse this structure to make sense of the content of a page.

CSS- It is used to style your web page-- aesthetics: color, fonts, margins etc.

JavaScript- Dynamic scripting language so that you can instruct the browser to do cool things without reloading the entire page.

SVG- THis is a text based image format--- you can specify image using tags like the ones in HTML. This is what ou use when you want to have an image, which neer loses quality. 

Developer tools- I would suggest to use Chrome. OPen your HTML page in your browser, right click, and choose Inspct Element-- you will see many cool section including the current state of your DOM. Explore it-- console is going to be your buddy!

### D3 concepts

1. Selection- Pass a CSS selector is select() method to get a reference to that object. If there are many such elements then a rference to the first occurence of that object is given. Use selectAl() to get all of the objects.

2. Chaining- Chain syntax is used so that several ations can be performed in a single lie of code using the dot(.) operator. It is a fast and cleaner way to write code but debugging can be tough so be careful!

3. Binding Data- Attaching or associating data to specific elements so that you can refer to those values to apply mapping rules- make longer bars, change colors etc. THis is important because nobody wants to keep a bunch of data-less, unmappable DOM elements. What do we need to do binding:
	1. Data- this could be an array, csv or tsv files, JSON. Type conversion is a good idea to keep in mind since JavaScript may not automatically do it for you.
	2. Selection of DOM elements- Decide the element you want to associate our data to.

When D3 binds data to an elemnt, that data does not exits in the DOM, rather in the memory as a __data__ attribute of that element.







