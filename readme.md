## TTP Capstone Project - Backend (Servers + Databases)

Players' Cards Database endpoint on Heroku: https://ttp-capstone-project-backend.herokuapp.com/players_cards
<br>
Routes:
<li>/players_cards: GET request to get all of the players' cards (info)</li>
<li>/players_cards/id: GET request to get one player's card (info)</li>
<br><br>
Login and Sign Up routes on Heroku:
<li>/signup: POST request to insert a new user's username, email, password, and currency/balance</li>
<li>/login: POST request to insert the user's email and password. NOTE: The user must be registered first by signing up!! Otherwise, it will result in getting an error saying that "Email is not registered". </li>
<li>/users: GET request to get all of the users' information. </li>
<li>/users/id: GET request to get one user's information. </li>
