# password-generator

#Let's make password generator in Python 🔒

It’s important to protect your personal information and the most common way we do this is with a password. So in this project, you’ll create a program to generate passwords for you.

The passwords will be random, so no one will be able to guess them!

Let's create a python file in any text editor and start coding! (I am using `passwordgenerator.py` for this tutorial.

##Adding random characters
First, let's import `random`. This will help us in getting a random number!
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/p2pp9wxwtv8h1kvoygbm.png)

Next, we will create a list of characters, stored in a variable called `chars`.
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/4w5c7xy6cd9p64qoj72k.png)

Now you can choose a random character from the list, and store it in a variable called `password`.
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/200k9y9cfbs4apcdbpdn.png)

Finally, you can print your (very short!) password to the screen.
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/7mdlz7e6grxv5o11t09o.png)

Let's test our program by pressing "play" or right-clicking and selecting "run python file in terminal." You see 1 letter in your terminal. For example, I received an `x`.
`python-password-generator/passwordgenerator.py
x`

That works! But a password isn't very secure with just letters. Let's add some numbers to our `chars`. 
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/z7gsy8g4zekxrufhopn2.png)

Let's run this again a few times and now we should see letters and numbers. 

Now let's add some punctuation to our `chars` for some added security! 
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/qletp09sg0xgygq3aty6.png)

##Now a random password!
A single character isn’t very useful. Let’s improve your program to create a longer password.

To create a password, you will add random characters to it, one at a time.

To start with, your `password` variable should be empty. Add this line to your code:
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/e689frdaqpvugxgoz2de.png)

You want to choose a random character 10 times. To do this, add the following code: (remember to indent correctly)- the line to choose a random character, so that it happens 10 times.
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/muy9gcs3aekjrbe71ggk.png)

You need to use `+=` to add the new character to the password each time.
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/3bhuu1u0fjbiqqb38bz6.png)

Let's test your new code and you should see a password that’s 10 characters long. Here's what I got!
`lt31@#udet`

Is 10 characters enough? You can change the length of your password by editing the number in our `range`.
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/6wxkmm2qdwec6w3x7wkl.png)

##Choosing a password length 
We can edit the length of our password manually but there is a much better way to do this. Let’s allow the user to choose the length of their password.
First, ask the user to input a password length, and store it in a variable called `length`.
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/jw0dumukyiafvryyy177.png)

Use `int()` to turn the user’s input into a whole number.
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/2ann9vht6q06yr4u7q4v.png)

Use your `length` variable to repeat as many times as the user entered.
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/zsc367d4xp6vypf5xx8i.png)

Test this by running your code. You should see something similar to this:

`python-password-generator/passwordgenerator.py
password length?10`
`#y*lt2oq*!`
`python-password-generator/passwordgenerator.py
password length?20
l@8tngydl9tl1dvsj7n0`

Boom! We're done and you now have your own password generator. 
