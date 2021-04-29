# 100 Days Of Code - Log

### Day 51: Wednesday April 28, 2021 

**Progress**: A lot of the ground work in place. Created job model. Got edit, delete, create views up and running. Mixins and authorizations. My Job Board where you can see list of all your jobs. This will become the main thing. 

**Key Learning**:  

**Thoughts:**  

**Minutes Worked:** 110


### Day 51: Tuesday April 27, 2021 

**Progress**: Started on new app. Got the groundwork laid for the django infrastructure and user accounts.

**Key Learning**:  

**Thoughts:**  

**Minutes Worked:** 65

### Day 50: Monday April 26, 2021 

**Progress**: None

**Key Learning**:  

**Thoughts:**  

**Minutes Worked:** 0


### Day 49: Sunday April 25, 2021 

**Progress**: Deployed Twitbook app!

**Key Learning**:  

**Thoughts:** So psyched to have deployed this. Feels great to finish another project. Always more that could be done. But took this so much further than I would have thought. Feels great to just conceputalize something, start, and make it a reality. Had to figure out a lot of challenging stuff along the way. But that's the price you pay and really, the fun of it. Always better to just go for it. If you knew how hard it would be, you might not want to start. Started thinking about next project already. Keep coming up with ideas and challenging yourself to figure out how to build them.

**Minutes Worked:** 60

**Link to resources:** 
1. [Deployed app](https://ma-twitbook.herokuapp.com/)


### Day 48: Thursday April 22, 2021 

**Progress**: Spent an hour trying to deploy and just ran into a bunch of issues and ended up having to call it quits. Everything still works locally and the code is all in github at least. Will try again Sunday. I think the app is good, ready to move on.

**Key Learning**:  

**Thoughts:** 

**Minutes Worked:** 80

### Day 47: Wednesday April 21, 2021 

**Progress**: Still working on Twitter-esk product. Got a shit ton of little things done. Found out how to submit form from within a list. Now can follow from user list. Submit comment from feed. Delete comment from feed. Delete comment from post detail. Reversed order of posts in profile. Edit bio. Added user passes test mixins. Can't go to update profile, post delete, or comment delete unless it's your profile or you are the author.

**Key Learning**: When you are in the zone, don't let it go. Use it all up till you don't have anymore. 

**Thoughts:** Feels good to get all this done. It's amazing the amount of complexity and little edge cases you need to consider when building even a simple web app like this. Just the little things that you need to remember. It's actually quite fun to juggle them all in your head. I think I'm just about done with this. Going to spend one more day wrapping up little things, then deploy.

**Minutes Worked:** 160


### Day 46: Tuesday April 20, 2021 

**Progress**: Did a bunch of little things around the UI. I added all of a user's posts to their profile. Made it so you don't see follow or unfollow button on own profile. Formatted follower / following lists. Made login required for all pages but landing. Will redirect to login. 

**Key Learning**: 

**Thoughts:** Don't want to spend too much time working on UI. My goal is to learn Django - want to keep doing more projects that will help with that. I think the last thing to do would be to see if I can figure out a workaround for forms in list view - not being able to use them is blocking me from allowing people to follow someone directly from user list and from adding comments in feed (which I'm not sure I care about). I'm going to dedicate one, max two days to this. Then after that I'll give myself one more day to work on UI. Then get ready for deployment and call it. Max 4 more days. 

**Minutes Worked:** 113

### Day 45: Monday April 19, 2021 

**Progress**: Bunch of work around followers. Put up guard rails so that you can't follow yourself or follow the same person twice. Put conditionals in UI so you see Follow vs Unfollow buttons depending on whether you follow that user or not.


### Days 38 - 31

**Progress**: Put in a bunch of hours Monday - Thursday and got a bunch done. Learned a bunch about Django. Things list conditional post requets, a lot about checking for existing entries in a model, what you can and can't do with models and querysets, how to create custom filter tags, etc. 


### Day 37: Sunday April 11, 2021

**Today's Progress**: Not a lot of progress today. Trying to implement follower / following system. I created a model which I think will work. In the admin I can add followers. I can display them on a user's profile. Next I need to figure out how I can allow a user to follow another by clicking a button on the other user's profile. I am not currently passing data to to the post method correctly. That, or, the post method is not creating a new database entry at all. I actually think it's the later. Will figure this out tomorrow. Once I get that done, will be getting close to core functionality. Then make sure users only see posts from people they follow. 

**Key Learning**: More time doesn't mean more productive. 30 minutes with a sharp brain is worth far more than 2 hours when you're out of it. 

**Thoughts:** 

**Minutes Worked:** 120

### Day 36: Saturday April 10, 2021

**Today's Progress**: No work

### Day 35: Friday April 9, 2021

**Today's Progress**: No work


### Day 34: Thursday April 8, 2021

**Today's Progress**: Made a bunch of progress. Fixed two issues with user profiles - links not working and info not displaying. Then added links to profiles from the feed and nav bar. Then made a user list page which shows a list of all users. You can go to their profiles from here and, soon, you will be able to follow one from here. 

**Key Learning**: 

**Thoughts:** Feels great to be productive. Feels like I'm getting faster and able to figure out more on my own. Did 35 minutes in the morning and 45 at night. Breaking it up is nice too. Next up is implementing follower / following relationship.

**Minutes Worked:** 80


### Day 33: Wednesday April 7, 2021

**Today's Progress**: Made some fixes on the feed. Set up base infrastructure for profiles - urls, view, template. Had a few issues with links to the profile and displaying info once there. 

**Key Learning**: 

**Thoughts:** 

**Minutes Worked:** 64


### Day 32: Tuesday April 6, 2021

**Today's Progress**: Got back into it. Reoriented myself on social media app. Had left off with issue on creating comments within ListView (the feed page). Realized this is pretty complex. Implemented a work around. To add comment, a user can see a detail view of a post, add a comment there, and then return to the feed. I'd like to fix this in the long run. Next up is creating profiles, creating a follower / following relationship. I want to get to where a user can: see list of all users, follow another user. They will only see posts in their feed from people they follow. Their profile will show their own info and will show follower/following count.

**Key Learning**: 

**Thoughts:** I could overwrite the class and create a get_object that would give me the specific post in the listview. Feeling excited to get back into it. I love programming.

**Minutes Worked:** 80

**Link to resources:** 
1. [Cool website that shows what functions a given view has available](https://ccbv.co.uk/projects/Django/3.0/django.views.generic.list/ListView/)



## Break

**Took a one month break to focus on Lenny Rachistsky's Product Management Fundementals Course. Awesome experience. Back to it.
** Goal is to spend minimum 7 hours a week for all of April.
** During the break I started building a little app that has the base functionality of a social media site - a feed, profiles, friends. I'm going to pick up by finishing that. 


### Day 31: Monday March 8, 2021

**Today's Progress**: Toyed around with social media app.

### Day 30: Sunday March 7, 2021

**Today's Progress**: Toyed around with social media app.


### Day 29: Monday March 1, 2021

**Today's Progress**: Got the newspaper app deployed! Had run into some issues. They mainly centered around heroku finding my staticfiles. Couldn't quite figure the issue out. But in the end I didn't need the static files, so decided to leave them out of the deployment. 

**Key Learning**: Critical to go through all pipenv installs before deployment because we're not using a requirements.txt file to explicity tell Heroku what they are. Need to do each before deployment.

**Thoughts:** Deployment is still messy but I imagine with practice it will come. There is also a django-heroku package that is worth trying. Supposed to simplify deplyoment. Also, I need to learn more git. Was confused about why I had a main and master branch and how to sync them.

**Minutes Worked:** 86

**Link to resources:** 
1. [Deployed News App](https://ambrogi-news.herokuapp.com/)


### Day 28: Sunday February 28, 2021

**Today's Progress**: Starting on deployment. Set up environment variables and then ran into some issues.

**Key Learning**: 

**Thoughts:** 

**Minutes Worked:** 60

**Link to resources:** 


### Day 27: Saturday February 27, 2021

**Today's Progress**: Figured out how to add comments from within detail view.

**Key Learning**: How to create a form for model B (comment) within a view that is driven by model A (article) 

**Thoughts:** 

**Minutes Worked:** 50

**Link to resources:** 
1. [How to add comments section](https://dev.to/radualexandrub/how-to-create-a-comment-section-for-your-django-blog-3egp)
2. [Adding Extra content to class based views: maybe a better approach to do within view](https://docs.djangoproject.com/en/3.1/topics/class-based-views/generic-display/#adding-extra-context)
3. [Basic Forms - django docs](https://docs.djangoproject.com/en/3.1/topics/class-based-views/generic-editing/)
4. [Good stack exchange post on this](https://stackoverflow.com/questions/45659986/django-implementing-a-form-within-a-generic-detailview)



### Day 26: Friday February 26, 2021

**Today's Progress**: No progress, didn't code.


### Day 25: Thursday February 25, 2021

**Today's Progress**: No progress, didn't code.


### Day 24: Wednesday February 24, 2021

**Today's Progress**: Added display of comments on list and detail view. End of Book-guided content. Made it so that you only see the option to edit in list and detail view if you are the correct user. Began to figure out how to write comments within detail view.

**Key Learning**: 

**Thoughts:** 

**Minutes Worked:** 84

**Link to resources:** 


### Day 23: Tuesday February 23, 2021

**Today's Progress**: Newspaper app. Adeed access restrictions so can only view all functionality if logged in and can only edit/delete articles if user is the author. Created comments model which has many-to-one relationship with articles. Added to admin and customized view. Next up is to display in article list UI. Should be able to finish that tomorrow. That's end of functionality in this book. Then there's a few things not covered here that I'd like to add: only see edit/delete option if logged in, link to article detail from article list, ability to add comment in article detail.

**Key Learning**: Began learning about how foreign keys work!

**Thoughts:** 

**Minutes Worked:** 60

**Link to resources:** 


### Day 22: Monday February 22, 2021

**Today's Progress**:  Added templates for detail, edit, create, delete. Restyled landing page. Changed create page to automatically store author as current user. Added first login required mixin for create page which has dependency on being logged in. Will continue with authorizations tomorrow.

**Key Learning**: First time with mixins - looking forward to exploring more.

**Thoughts:** Crazy how much stuff Django has built it. For login required mixin, just add a couple arguments to view and will redirect to login if user tries to view and not logged in.

**Minutes Worked:** 62

**Link to resources:** 


### Day 21: Sunday February 21, 2021

**Today's Progress**:  Added article list. For article edit, delete, and detail, I just added the urls and views. Need to do templates tomorrow.

**Key Learning**: Don't start too late if you're already tired! If you have one thing you want to get done in a day, do it as early as possible.

**Thoughts:** 

**Minutes Worked:** 30

**Link to resources:** 

### Day 20: Saturday February 20, 2021

**Today's Progress**:  Continued Newspaper app. Spend 30 minutes trying to figure out email, then decided to move on. Not core to app. Just need to create a different email account via my actual domain for it to work. Will do later. Back to outputting email to console. Began on core functionality by creating articles app and Article model. Tested in admin. 

**Key Learning**: Editing the email template is a good example of finding and over-writing Django source code.

**Thoughts:** Excited to get on with progress on the app itself.

**Minutes Worked:** 60

**Link to resources:** 


### Day 19: Friday February 19, 2021

**Today's Progress**: No progress, didn't code.


### Day 18: Thursday February 18, 2021

**Today's Progress**: Continued setup of Newspaper app. Added password change and password reset capabilities.  

**Key Learning**: How much Django offers out of the box.

**Thoughts:** Django is phenomenal here. Basically everything exists out of the box. Just a matter of customizing templates.

**Minutes Worked:** 62

**Link to resources:** 

### Day 17: Wednesday February 17, 2021

**Today's Progress**: Continued setup of Newspaper app. Added views and urls for pages. Created seperate pages app. Added tests. Added bootstrap and crispy forms. Next up: change password, then emai, then actual app. 

**Key Learning**: Solidying url/view/template process. Seeing how to further break up project with pages app. One useful thing: if there's bootstrap magic you want to change, easiest to go to source code in github and search in search bar. There you can get an understanding of what you need to do. 

**Thoughts:** Nice to see things looking decent with Bootstrap :). Took some time to understand tests. 

**Minutes Worked:** 75

**Link to resources:** 
1. [Django Source Code](https://github.com/django/django)
2. [Example of finding helper text in source code (150 characters)](https://github.com/django/django/blob/7af8f4127397279d19ef7c7899e93018274e2f9b/django/contrib/auth/models.py)


### Day 16: Tuesday February 16, 2021

**Today's Progress**: Began last project of Django for Beginners - Newspaper App. Built user model and created templates for base, home, login, signup

**Key Learning**: Solidying process for starting up a new project. Directories, installing django, creating project and first apps, setting up user model, creating inital templates, views, urls.

**Thoughts:** Very tired tonight. Feeling sloppy. Will come back ready to add in views and urls for first templates tomorrow.

**Minutes Worked:** 60

**Link to resources:** 




### Day 15: Monday February 15, 2021

**Today's Progress**: Added Heroku config and deployed blog app, concluding the first major project of Learn Django for Beginners.

**Key Learning**: Some notes on staticfiles and the steps required for deployment. 

**Thoughts:** I should read up more to understand static files. I should also put together a check list for each: 1. creating a project 2. creating each new view, template, url combo 3. deployment

**Minutes Worked:** 30

**Link to resources:** 
1. [Blog deployement](http://blog-ydg.herokuapp.com/)


### Day 14: Sunday February 14, 2021

**Today's Progress**: None. On vacation.


### Day 13: Saturday February 13, 2021

**Today's Progress**: None. On vacation.


### Day 10: Friday February 12, 2021

**Today's Progress**: Finished chapter 7 and blog app from Django for Beginners. Added ability to delete posts. Added user accounts, log in, log out, and sign up. 

**Key Learning**: The basics of user models.

**Thoughts:** Super exciting to finish this first project. So cool how easy it was to implement user accounts. If I was to work on this more, I would display the author next to each post, move the log in / log out for improved UI, and add controls so that users can only edit their own posts. For now, I'm just going to keep cranking on to the last project of this book because I think it will cover a lot of that. 

**Minutes Worked:** 60




### Day 11: Thursday February 11, 2021

**Today's Progress**: None. Preparing for weekend trip.


### Day 10: Wednesday February 10, 2021

**Today's Progress**: Contined on blog app in chapter 5 of Django for beginners. Added individual pages for blog posts, the ability to create a post via a from, the ability to edit a post via a form, some initial tests. Up next is ability to delete, user authentication, and more tests.

**Key Learning**: Learning about how models can both populate and be fed my forms. A little about absolute urls to direct users. How primary keys work in detail views. 

**Thoughts:** Fun to make a lot of progress. Excited to do more. I do feel like I should take more time to understand structure and theory. For example, could barely explain any of the above. But, for now I think it makes sense to focus on just building, as the patterns will begin to come together for me. May make sense to block of a day for concept review and reading (maybe Sundays.)

**Minutes Worked:** 97

**Link to resources:** 
1. 

### Day 9: Tuesday February 09, 2021

**Today's Progress**: No progress, mental health day.

### Day 8: Monday February 08, 2021

**Today's Progress**: Began Blog app, chapter 5 of Django for Beginners. Configured DB, set up urls, views, and templates for home page which displays posts from DB. Added in some html and css. 

**Key Learning**: Getting down the pattern of create a model, set up urls for view, which displays template. Starting to see how Django scripting can display DB info in template. Learned about foreign keys and many-to-one relationships (i.e. many blog posts to one author).

**Thoughts:** Felt good. Can see a lot of applications for the underlying pattern: allow user to create db entry. Then display those. Job board, stores, etc. 

**Minutes Worked:** 68

**Link to resources:** 
1. 



### Day 7: Sunday February 07, 2021

**Today's Progress**: Built, tested, and deployed my first database driven app. Chapter 4 of Django for Beginners. An extremely basic message board.

**Key Learning**: Creating a database model, updating it with the admin panel, and displaying contents from the database on a webpage. 

**Thoughts:** Very cool. Once I get the basics of creating databases and displaying their contents, that opens up a whole new world for me and a lot I can build. I understand how to use that and how to work with databases already. No-code, bubble experience actually very helpful here. Know what pulling db info to populate content is like.

**Minutes Worked:** 103

**Link to resources:** 
1. [Message board deployment](https://arcane-lake-95105.herokuapp.com/)
2. [Progress log](https://docs.google.com/spreadsheets/d/1GUllE5IPdZ3DudqF9BqqFuiJNOsrYVuaUskVZIXtf0o/edit#gid=0)



### Day 5: Saturday February 06, 2021

**Today's Progress**: No progress. No time for work.


### Day 5: Friday February 05, 2021

**Today's Progress**: No progress. No time for work.



### Day 4: Thursday February 04, 2021

**Today's Progress**: Chapter 3 of Django for Beginners. Created base template, extended by home and about. Created first tests. Deployed first project to Heroku.

**Key Learning**: Basics of class based views. How views call templates and urlconfigs are used to map url to a view. 

**Thoughts:** Felt good. Made a lot of progress and a lot of firsts. Tired by the end.

**Minutes Worked:** 94

**Link to resources:** 
1. [First deployment](http://ancient-tundra-32763.herokuapp.com/)
2. [Python classes](https://docs.python.org/3.8/tutorial/classes.html)
3. [Gunicorn server](https://gunicorn.org/)
4. [100 days of code tracker](https://docs.google.com/spreadsheets/d/1GUllE5IPdZ3DudqF9BqqFuiJNOsrYVuaUskVZIXtf0o/edit#gid=0)
5. [Django for Beginners Chapter 3](https://djangoforbeginners.com/pages-app/)


### Day 3: Wednesday February 03, 2021

**Today's Progress**: No progress. Had to go visit girlfriend after work. 

**Thoughts:** 

**Minutes Worked:** 

**Link to resources:** 


### Day 2: Tuesday, February 02, 2021

**Today's Progress**: Completed chapter 2 of Django for Beginners. Set up a Django website that displayed "Hello World"

**Thoughts:** 30 minutes into working, ran into a bug which would not allow me to start my server. After an hour, I realized that VS Code had automatically put a file into UTF-16, as opposed to UTF-8. Fixed that and everything worked.

**Minutes Worked:** 105

**Link to resources:** 



### Day 1: Monday, February 01, 2021

**Today's Progress**: Forked this repo, reinstalled Python, updated VS Code, installed pipenv and Django

**Thoughts:** Ran into an issue in which I had to add directory where pipenv was to PATH. Fixed it.

**Minutes Worked:** 60

**Link to resources:** 
1. [Install Python](https://installpython3.com/windows/)
2. [Add directory to PATH](https://www.architectryan.com/2018/03/17/add-to-the-path-on-windows-10/)






