# Secure Login in Python

## Step 1 - Running the script

- To run this script, click the 'Work in Repl.it' button above to open the Repl.it IDE. _**Note**: Make sure you sign into Repl first, as there can sometimes be bugs if you access it the other way around._

- Once you are in the Repl.it IDE, press 'Run' at the top of the screen to run the program. 
 
In its current state, this program takes allows a user to 'register' using a username and password, then stores those credentials in a database. **No attempt** is made to obscure or hide the login details, and as such the code is completely insecure.

## Step 2 - Improving security (I)

## Step 3 - Improving security (II)

The next step in securing our login procedure is to hide the password details when stored in the server. Passwords should _**never**_ be stored in plaintext and any attempt to do so is likely to end in disaster. Any unauthorised access to your server would mean that user passwords would be exposed! We can circumvent this via a process known as _hashing_ and _salting_. You can read more about this process [here](https://auth0.com/blog/adding-salt-to-hashing-a-better-way-to-store-passwords/).

This process is highly mathematical and can get quite confusing. Luckily Python has a few functions that will be able to help us out 

## Step 4 - Over to you

Please feel free to continue to edit the code and improve its usability and security. 

There are plenty of additional things you could try to implement, including wrapping the script in a Flask server, checking for multiple login attempts and a facility to reset a password. What else can you make this code do?

## Contact

Any questions or issues can be raised via the [Github issues](https://github.com/den01-hnc-2020/python-login/issues) pages.

## License 

Copyright Scott Morgan (2021). Released under the [MIT License](https://opensource.org/licenses/MIT)
