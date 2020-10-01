# Week-3 -- Day-3

## Competing with Other Bootcamp Students

Please remember you are competing with self-learners and other coding bootcamp students when job search time comes.

In case you are curious what other coding bootcamp students have accomplished search for their repos on GitHub. You can use keywords such as "General Assembly" or "Flat Iron".

One thing you will notice when you look at other coding bootcamps students repo is they almost alway have a good readme. This is especially true when it comes to portfolio items. So...don't forget to write good readme's.

## Getting started with Bootstrap!

 1. Load the Bootstrap CSS
 2. Load jQuery
 3. Load the Bootstrap Javascript

In that order. You can use either the CDN way to get started or download each file to your computer and then load it that way. Two good sources for getting started are:

https://getbootstrap.com/docs/3.3/getting-started/

https://www.w3schools.com/bootstrap4/bootstrap_get_started.asp

Notice the difference between the two. Just remember you need the Bootstrap CSS, jQuery and Bootstrap Javascript regardless of how you choose to load the Bootstrap library.

Once you think you have loaded bootstrap into your html page open up the page in chrome and check the console in the dev tools to make sure ther are no errors. You can also click on the "Network" tab and make sure all the right files were loaded.

Here is one example of how you could load bootstrap:

    <!DOCTYPE HTML>
    <html lang="en" dir="ltr">
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <!-- 1) Load Bootstrap CSS -->
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">

        <title></title>
      </head>
      <body>

       <!--  2) Load jQuery -->
       <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
       <!-- 3) Load Bootstrap JavaScript -->
       <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>

      </body>
    </html>


### Making sure Bootstrap was loaded!

Then make sure it was loaded correctly by checking the console in the dev tools of chrome.

![console in dev tools within chrome](https://raw.githubusercontent.com/Team-FCB/Assets/master/dev-tools-2.png)

Make sure there are no error messages!

You also check the network tab and to make sure the bootstrap was loaded. You might have to refresh the page with the tab already open to see the libraries!

![enter image description here](https://raw.githubusercontent.com/Team-FCB/Assets/master/network-tab.png)
