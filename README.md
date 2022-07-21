# Snake Game using HTML/CSS and JavaScript

Website link:- https://snake-game-html.herokuapp.com/

A simple Snake Game using HTML/CSS and JavaScript.



![ScreenRecorder_2022-07-21_4e4086d1-b2ed-4688-9b65-d444808e5f8d (2)](https://user-images.githubusercontent.com/61287615/180205441-1e136bc0-a4b1-4204-855d-feeada7df06f.gif)


## Rules of the game:- 
1. Move up using upward arrow.
2. Move down using downward arrow.
3. Its game over when you touch the walls.

## Deployment :- 

The source file index.html is deployed using Heroku.com.

We had to create two files in order to deploy to heroku namely "composter.json" and "index.php".

composter.json 
   
           {}
           
index.php

           <?php include_once("index.html"); ?>


Adding git directory to heroku
 
           heroku login
           heroku git:remote snake-game-html
           git push heroku master
           git add . 
           git commit -m "your commit message" 
           git push heroku master
