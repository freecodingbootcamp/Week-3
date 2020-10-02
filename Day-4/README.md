# Week-3 -- Day-4

## Git and Naming Good Practices

Always create and use just **one** repo per project! General speaking, you do not put multiple assignments in one repo. Pick descriptive names for your repos, folder and file names. Under no circumstances use spaces.

#### Bad Repo Name Example:

    someWebDevBootcamp

#### Good Repo Name Example:

    fcb_resume_assignment

If you are planning on **hosting** your HTML/CSS page use **index.html** for the name of the page.

While it's very easy to miss and it happens to me, **letter casing** (upper and lower case) matters. So

    <link rel="stylesheet" href="css/styles.css">

is not the same as

    <link rel="stylesheet" href="CSS/styles.css">

Did you catch the difference?

## Help I Don't See the Git Instructions

So you created a repo on GitHub because you want to push your code up to it. However ran into a problem. You have seen your instructor look at page that looks like this:

![git push instructions](https://raw.githubusercontent.com/Team-FCB/Assets/master/Git-Instructions.png)

But you don't see it! No worries. All you need is to get the link [GIT_REPO_URL] to the newly created repo. Here is a screenshot of how you can get it:

![Git clone copy url image](https://raw.githubusercontent.com/Team-FCB/Assets/master/Git-Clone-URL.png)

This will copy the [GIT_REPO_URL]

Now run the following instructions in the folder where you have your code. REPLACE [GIT_REPO_URL] with the actual repo URL. The one that you just copied.

    git init
    git add .
    git commit -m "first commit"
    git branch -M main
    git remote add origin [GIT_REPO_URL]
    git push -u origin master

You might have to enter your GitHub credentials. And that is it.

You did it!

![DJ Khaled Celebrating in pool with big ass bottle](https://media.giphy.com/media/RDbZGZ3O0UmL6/giphy.gif)


## Oh no I Received a Merge Conflict Message

You might have received something like:

	...
    CONFLICT (content): Merge conflict in  [YOUR_FILE]  
    Automatic merge failed; fix conflicts and  then commit the  result.

No worries!

Just find the file in question in your favorite code editor and select either the purple option or blue option depending on which one you would like to keep. And then re-push to github.

![merge conflict screenshot](https://raw.githubusercontent.com/Team-FCB/Assets/master/merge-conflict.png)


You might have to repeat the git combo commands (git add, commit, push) and maybe even a `git pull origin main` again.

Sorry about being short about this topic. Feel free to reach out to me directly if you are still struggling with this part.
