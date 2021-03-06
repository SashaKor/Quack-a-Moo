# Quack-a-Moo
#### Members: Mohammed S. Jamil, Isaac Jon, Ahnaf Kazi, Addison Huang
#### SoftDev1 pd6
#### P #00: Da Art of Storytellin'
#### 2018-10-01

## What is it
So you wanna be the next Shakespeare, and want to show your genius in one paragraph of a story? Then this is the place for you.
Our website facilitates the creation of a nonsensical story by collaborating with other people. We believe that collaboration will lead to elaboration. You can create your own low-effort story and wait as no one adds to it. The other option is to look at the last edit in a story and continue the story or ruin it for everyone by writing nonsense.

## What do you need to run

On your terminal run the following commands
Make sure you have __python3__ installed

```
    $ git clone https://github.com/Zer0-M/Quack-a-Moo.git # this clones our repo in order to run 
    $ python3 -m venv quack # this creates a virtual environment named quack. Replace the name as you see fit 
    $ . quack/bin/activate # this activates the virtual environment 
    $ pip3 install wheel 
    $ pip3 install flask # since our code was written using the flask framework
    $ pip3 install passlib #passlib is used for password encryption on the website
```
### Why Passlib

Link to the Passlib Documentation:https://passlib.readthedocs.io/en/stable/<br/>
Passlib encrypts a password by hashing it and can also decrypt it for later verification.
We decided to use this module as we thought any website that requires authentication, should not make passwords easily available to everyone who clones the repository.
Passlib is used to encrypt passwords submitted on our website. The passwords are decrypted for verification when a user logs in.

## How do you run

Run these commands in your terminal
```
   python3 app.py
```

Then go to preferred non-Chrome web browser and go to <br/>
http://127.0.0.1:5000/ <br/>
<br/>
After you're done remember to disable your virtuatl environment by using the following command in the terminal: 
```
    $ deactivate
```
