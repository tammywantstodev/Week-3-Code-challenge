#Week 3 code challenge-Flatdango

##index.html
This file contains the basic structure for the Flatdango page. 
It contains the elements, classes, and ids that serve as placeholders that
the DOM will access in order to connect data in the API to the front-end.

##index.css
The CSS contains all the code to style the web page and make sure that when the
data is retrieved, it is displayed in a pleasant manner on the page, for example
it is displayed in the right sections of the page and long pieces of text 
aren't cut off because they can't fit on the screen.


##Index.js
This file contains majority of the code. It ``connects to the API``, using ``fetch()``
makes sure data is parsed to an appropriate form, creates elements to store retrieved 
data and then appends said data to the HTML to be displayed on the front-end.
It also enables the front-end to interact with the API with methods such as 
``PATCH`` that enable actions in the front-end to have a direct impact on the 
data in the API.

##db.json
This file contains the data that make up the server for this program. All the
data about the movies are stored in here as ``JSON objects``.

##Prerequisites
Node.js installed on your machine
Clone this repository```git clone<SSH key>```
Run each file using node.js ```node fileName.js```

###Author:Tamara Kaka
