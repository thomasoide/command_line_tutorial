# command_line_tutorial

This is everything you need to know to run the django-rmp-data project from the command line. 

## 1. cd into the correct directory

A quick explanation about what this means. From the Finder bar, click the 'Go' tab and select home. You should see something like this: 

(/home.png)

This is what's called your home directory. It houses your desktop, documents, music, photos, etc. If you use finder a lot, you'll see that they are directories you use on a daily basis. 

Now, open your terminal and type this command 

```bash
ls
```

So if you compare the two screens, you'll see that they are basically the same. This is where your terminal always starts. 

(/home_terminal.png)

So, what does the command 'cd' actually mean? 

Imagine that your computer's file hierarchy is like a tree. In order to climb that tree to get to a specific branch, you'll need to climb using the lower branches. 

When you 'cd' into a location, it's like you're clicking and opening a folder. For this project, you're going to have to 'cd' into the django-rmp-data folder, wherever it is on your computer. 

If the folder is on your desktop, the commands will look something like this:

```bash
cd Desktop ; cd django-rmp-data
```

If the folder is in your home directory, the command is as simple as:

```bash
cd django-rmp-data
```

## 2. Start the virtual environment

So now that you've 'cd'ed into the correct folder, you'll need to start the virtual environment. 

```bash
pipenv shell
```

The web server on your local machine will not run unless you run this command. 

## 3. Start the web server

It's as simple as this:

```bash
python manage.py runserver
``` 

## 4. Navigate to the page in your web browser. 

Instead of writing out the whole complicated IP Address, you can simply type 'localhost:8000' without quotes into your browser. 

## 5. The page should show up

Any changes you make to the page should appear in real-time, just like on Github Pages. 

Remember, the files you will be working with are in two locations: 

rmp/static/rmp/style.css -- This is where all of your css will go. 

rmp/templates/rmp/*.html -- This is where all of the html templates are. accident_list.html has all of the comments I wrote to guide you guys if you forgot what everything does. 



