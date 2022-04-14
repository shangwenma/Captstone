# Captstone
## Configure the local GIT client
$ git config --global user.name "your_github_username"

$ git config --global user.email "your_github_email"

$ git config -l

$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY 

$ git config --global credential.helper cache # remembers the token

$ git pull -v # verify

ref:https://stackoverflow.com/questions/68775869/support-for-password-authentication-was-removed-please-use-a-personal-access-to

## Upload a file
#cp file to github respitory

$ git add <$filename$> # must in the github directory
  
$ git commit - m "<$comments$>" # shown the file that motified
  
$ git push <$local name$> # put user name and token(PAT)

## Remove a file
$git rm <$filename$> 
  
$ git commit - m "<$comments$>" # shown the file that motified
  
$ git push <$local name$> # put user name and token(PAT)
