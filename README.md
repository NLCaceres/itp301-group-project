Team Members
	Nicholas Caceres and Duncan Gammie

API Used: 
	Google Books API (returns the JSON-P) with its Embedded Viewer API
	Overview: https://developers.google.com/books/docs/overview

Plugin Used:
	Turn JS 
	Website: turnjs.com

Description:
	Duncan and I used the Turn JS plugin in combination with the Google Books API order to create a magazine of magazines and books. By creating an endpoint to the Google Books API, we could insert an embedded viewer into a new div element we create dynamically. After making the new div element, the newly made div element is inserted into a "flipbook" div container element in a "page" wrapper as the next "page". By doing this, we can "flip" through div elements displayed and animated like a book or magazine. As we flip through and make divs, we load a book or magazine into the viewer/div element using book and magazine ISBNs received from the API JSON-P as a parameter for the Embedded Viewer API's load function. 
