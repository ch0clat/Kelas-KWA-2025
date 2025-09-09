# Login Bender
Log in with Bender's user account.
# Source
https://juice-shop.herokuapp.com/#/score-board?categories=Injection&showDisabledChallenges=false 

# Step by step
The website has insuficient protections with their users information, we can gather email informartion again with checking the about page.
![alt text](<Screenshot 2025-09-09 162508.png>)
With the email obtained, we can use the same SQLi query exploit from the previous challenge. 
![alt text](<Screenshot 2025-09-09 162318.png>)
we bypass the password checking and sucesfully login.
![alt text](<Screenshot 2025-09-09 162346.png>)