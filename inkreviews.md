# Project 04 Proposal:

## Requirements:

      1.  Full Stack
      2.  Interactive front-end
      3.  Full CRUD (be a complete product?)
      4.  Implement thoughtful user stories
      5.  Visually impressive design
      6.  Deployed online; publicly accessible.
      
## App Name: Ink Reviewer
- A app that reviews anything related to pens, pencils, paper, stationery, etc.  and maybe arts and crafts sites.  or not.  

## MVP: 
 - User can register from home page, view & edit profile info
 - User can view all the things in the database where things are pens, pencils, papers, etc
 - User can search for things in database-by thing id (see if you can do this for category id?)
 - User can create reviews of things in database, can also edit review of things in database
 - User can add things to the database, can edit things in database
 - User can create favorites, or remove from favorites
 
 
## Reach Goals:
 - Auth.  I hope I can make that work. 
 
## User Stories & Wire Frames:

  - when the user arrives on the homepage, user can register, login, or view
  - register-name, email, password (password_digest)
  - login-name, password
  - have nav bar-where does user want to go?  browse, search, add product or add review?
  - forms needed:
      - product form
      - review form 

## DB structure

![Ink App DB tables](https://i.imgur.com/HFhWfDB.png)


## Planned Technologies:
  - Rails, full stack
  - API to local database, not using an external api
  - will research Devise gem to see if this can streamline some of the auth stuff
<<<<<<< HEAD
  - Paperclip
  - ImageMagick
  - raty.js or ratyrate--did not use, couldn't get it to work.
  - used searchkick (but was also unable to get search results to display in the view-it's still showing a blank page.)
=======
            - Devise actually seems do-able...I'm going to try it. 
            - [Devise Documentation](http://devise.plataformatec.com.br/)
>>>>>>> 736086cf69ef1b2427290eb7501de069b8cf7a7b
  
## Timelines:
[Pls see my project page](https://github.com/alee092017/Project04_and_LastDayReq/projects/1)

## Foreseen challenges or obstacles:

 - the V of MVC.  creating views always trips me up more so than anything else.
 - All of Auth
 - Procrastination- don't jump down a rabbit hole of assembling stuff for the seedfile.  just pull from jetpens or mochithings or muji. 

## Link to project repo
[My project 04 repo-revised](https://github.com/alee092017/InkAppAgain)
- full commit history is here
- i reference a bunch of things online but followed closely a tutorial by Mackenzie Child on how to build a movie review app. Code was not copied.  I have 10 pages of notes I took in order to get mine functioning.

## Deployed on Heroku:
absolutely doesn't work
[Access Heroku Page here ](https://radiant-brook-89291.herokuapp.com/users/sign_in)
- issues with sqlite3 had to replace with postgres (duh)
- kept giving an error about yarn but I have yarn installed but not declared in the gemfile...??
- also looks like the fatal error is still due to database issue and still requires more troubleshooting.
- Procfile--was not included and didn't require puma in gemfile....
- [command line errors in terminal-and link to deploy repo](https://github.com/alee092017/InkAppDeploy/blob/master/TerrminalOutput-HerokuErrors)



