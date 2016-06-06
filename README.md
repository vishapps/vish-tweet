This is Twitter clone created for exercise and learning purposes. 
Ruby version is- <br>
ruby 2.2.1p85 (2015-02-26 revision 49769) <br>
I used C9, GitHub and BitBucket to create this tutorial <br>
- Create a account with GitHub & BitBucket .<br>
- Create a new repository (public or private) in GitHub & BitBucket <br>
- Create a C9 account <br>
-Create new project in C9- $ rails new vish-twitt <br>
-cd to new file <br>
$ git init <br>
 (to Initialized empty Git repository). <br>
$ git remote add origin git@github.com:vishapps/vish-twitt.git (to add repo to GitHub)<br>
$ git remote set-url origin --add git@bitbucket.org:Adhikariv/vish-twitt.git (to add extra repo to BitBucket)<br>
$ git add -A  (stages All fies)<br>
$ git commit -m "................."<br>

If you have test invironment,<br>
$ bundle exec rake test<br>

If you have more braches,<br>
$ git checkout master<br>
$ git merge ............(branch name)<br>

Then push up to the remote repositoris<br>
$ git push<br>

If you have Heroku, deploy to Heroku<br>
$ git push heroku<br>
$ heroku run rake db:migrate<br>

=> Create pages (blow command will create a folder & 4 pages in views/layout/pages folder and also crerates a rb file in controllers (pages_controller.rb))<br>
$ rails g controller pages index home profile explore<br>

=> Define root URL in routes.rb file-(This will indicate root page is index)   <br>
-  root 'pages#index'<br>
=> To show all the pages, difine all the URLs in routs.rb files like-   <br>
  get '/home' => 'pages#home'<br>
  get '/profile' => 'pages#profile'<br>
  get '/explore' => 'pages#explore'<br>

Covered topics are-<br>
Working with Bootstrap<br>
Building Navigation Bar<br>
working on profile page<br>
User Authantication with Devise<br>
Dynamic Navigation <br>
Adding User_Name function in users table of Devise (adding a column in database)<br>
Making form so people can put their user name when they sign in<br>
Implement routing so URL coresponds with username<br>
Bulding model and control to represent tweets, aka posts and adding some velidation so tweets are 140 	characters or less order by descending dates so the most recent ones are always top.<br>
Showing the tweets<br>
Making form for post or tweets<br>
Styling and Showing Logo<br>
Showing Logo<br>
Adding image in profile name (avatar)<br>
Working on Landing page & guest navigation<br>
Add style in Home Page & Tweet Form<br>
Styling and working on Left and Right Panels<br>
Styling user profile page, profile banner and left-right panel<br>
Implementing Follower and Following relationship<br>
Tuning up to show posts correctly in all pages and followers and posts to show right numbers<br>
Styling the forms (Devise- Login, sign up, Edit profile)<br>
