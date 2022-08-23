# lab08-heroku-dumpster-fire

So you're on Part 5 of Lab 8 and Heroku is exploding! You've come to the right place. This epic gamer guide was made by Daniel and Aidan.

First, follow the instructions of Lab 5 up to step 6. Once you're at step 6, do the following:

1) Create a file called `requirements.txt` and add the following code:

```
gunicorn==20.1.0
Flask==2.2.0
```

2) Create a file called `.gitignore` and add the following code:

```
venv/
```

---

Finish the rest of Step 6. Now for Step 7, where we will commit our code to Github:

1) Head over to your shell and type in `git add .`

After, you can run `git status` to confirm that everything's ok; it should look something like this:

![Git status](https://i.imgur.com/7UbsXM7.png)

2) Now, before we commit, we need to tell Github who we are. To do this, run the following commands in shell (replace your email and name with your actual email and name):

`git config --global user.email "you@example.com"`

`git config --global user.name "Your Name"`

3) Finally, we can commit! Type in the following command to shell:

`git commit -m "YOUR MESSAGE HERE"`

Replace the "YOUR MESSAGE HERE" with whatever message you want; this is the message that is attached to the commit, something like "initial commit" or "fixed bug A."

--- 

Last step! Finally, we can push to Heroku. Run the following command in the shell:

`git push heroku master`

If this doesn't work, try the following command:

`git push heroku main`

And you're done! Your code should now be on Heroku. Head to your Heroku dashboard, select the app you created, and click "Open App". You should now see your website!
