Demo address: http://www.zovoland.com/sudoku/Sudoku.html

Techonology used: HTML, CSS, JavaScript and jQuery. 

Structure: 

	In JS folder, game.js contain the game data as well as all the JavaScript code runs this application.

	In CSS folder, game.css control the style of the application, including table for the game and the number select panel. ie.css handle the cross browser issues with IE.

	Sudoku.html contain the HTML structure of the application. But most of the elements are generated by JavaScript.

	BG.jpg is the background picture. 	

Technical choices: 

	The JavaScript code is write in a module style, so either the game data(question and answer) or game rules can be changed on requirements without the need to change other part of the code. 

	Store the game data in the elements id in a Block_x_y format, so the id can target both the value in the matrix array and the elements in the DOM.

	Use CSS3 transition in the select panel to make the game interface more interactive and attractive.

Things can be done if I have more time:

	A game data generater. Can generate game anwsers under Sudoku rule and push data in the matrix array. So the game can be adjust difficulty levels and play number of times.	

	Mobile evaluation, I whote code about reponsive design and web app meta tags, so it can be play on mobile device. I also tested it on both Android/iOS device. It can be played, but the user experience is not exactly I want. I'm considering add some more code to improve the speed for tap.
