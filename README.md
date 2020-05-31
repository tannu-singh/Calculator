### Calculator Exercise details:

Create a web app (using any programming languages) which logs calculations as they happen and shares those calculations with everyone connected to the website.

For example, user A and user B go to your site at the same time. User A calculates "5 + 5", which equals "10". This is logged below the calculator as "5 + 5 = 10". User B is updated about this calculation right after user A posts it. Now, user B calculates "3 x 4".This calculates to “12” and displays "3 x 4=12" right below the prior calculation. User A sees this update immediately after user B posts it. 

### Test Cases
The following test cases were covered during the development of calculator website app.
- This calculator website app does the mathemactical calculation [BODMAS.](https://en.wikipedia.org/wiki/Order_of_operations "BODMAS")
- A test case was developed to make sure that no two consecutive [operators](https://en.wikipedia.org/wiki/List_of_mathematical_symbols "operators") are added in an equation. I have added four major operators in this calculator (+, -, /, x)
- A test case was also developed to ensure that in a real number there is only one point and not multiple points to represent a decimal number.
- A test case was developed to make sure that an equation does not start from +, /, or x except -.
- 10 logs are shown.
- Results remain the same even when the link is refreshed.
### Software/ Programming languages used

- Javascript : socket.io, and express.io library are used.
- HTML
- CSS

### Implementation Steps

1. Download the repository from Github.
2. Unzip and open cmd.
3. Make a connection to localhost; in my case I had to connect to localhost://9000 using this command: python -m http.server 9000
4.  Open another terminal/cmd and install npm, nodemon.
5. Using npm dowload the dependent libraries: 
	a. npm i socket.io
	b. npm i express
6. Enter npm in init mode : npm init
7. Open server.js file using : nodemon server.js
8. Run localhost://9000 in the browser ([Chrome](https://www.google.com/chrome/ "Chrome")) and test the calculations.


