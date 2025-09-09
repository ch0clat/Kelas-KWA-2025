# Login Jim
Log in with Jim's user account.
# Source
https://juice-shop.herokuapp.com/#/score-board?categories=Injection&showDisabledChallenges=false 

# Step by step
To login into Jim's account without knowing Jim's email and password, we had to do a little digging into the website. the website shows the email of the users in their reviews. we found jim's email through this review
![alt text](<Screenshot 2025-09-09 154343.png>)
With the email we are able to insert it into the login form.
![alt text](<Screenshot 2025-09-09 154412.png>)
without knowing the password. we bypass the password checking by adding ``' --`` at the end of the email.
![alt text](<Screenshot 2025-09-09 154705.png>)
with that query we are able to bypass the password check and sucesfully login into the account.