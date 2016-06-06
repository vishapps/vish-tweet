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
