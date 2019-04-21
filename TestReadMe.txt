Please tell me who you are .Run  
git config --global user.email "you@example.com"
git config --global user.name "Your Name" to set your account's default identity.

해당 에러 메세지는 
" 그래 이제 너가 설정해놓은 repository에 commit을 할껀데 
그전에, 너는 누구야 ? " 를 묻는건데요,

에러 메세지에서 말해주는대로 
$ git config --global user.name "user name"
$ git config --global user.email "user e-mail" 을 적어주시면 됩니다 :)


git init
git remote add origin repository address
git status
git add .
git commit -m "Hello Git hub"
git push origin master

<<<<<<< HEAD
git pull origin master
=======
added new sentences
>>>>>>> 29f62e4bce2492d5aa7787f91c0bb405944444f9
