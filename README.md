# MEAN-stack-with-Angular2-Tutorial

###### Configuration #########
1. Check Git
================================================================
	{ https://git-scm.com/ }
	{  https://try.github.io/levels/1/challenges/1 }
	git --version

2. Check NodeJs
=================================================================
	{ https://nodejs.org/en/ }
	{ https://github.com/login :bsmpnb:ha******_**}
	node -v
	Create directory "MEAN-stack-with-Angular2-Tutorial" on github yo will get below
	echo "# MEAN-stack-with-Angular2-Tutorial" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git remote add origin https://github.com/bsmpnb/MEAN-stack-with-Angular2-Tutorial.git
	git push -u origin master

	create your staging branch
	git checkout -b staging
	git branch
	npm init
	Create file "index.js"

3.Install Express Js
=============================================================	
	{ https://expressjs.com/ }
	npm install express --save
	in package.json
	"scripts": {
	    "start": "node index.js"
	  },
	npm start
	http://localhost:1337/


4. install https://nodemon.io/
=============================================================
	npm install -g nodemon
	nodemon index.js

5. install mongodb
==============================================================
	mongod -v
	{ https://robomongo.org/ }
	{ https://robomongo.org/download }
	cd ~/Downloads
	sudo cp /var/www/html/mean-ang2/robo3t-1.1.1-linux-x86_64-c93c6b0.tar.gz /opt/
	tar xvzf robo3t-1.1.1-linux-x86_64-c93c6b0.tar.gz
	sudo apt-get install robomongo
	/opt/robo3t-1.1.1-linux-x86_64-c93c6b0/bin/robomongo
	
6. mongoose
============================================================
	{ http://mongoosejs.com/ }
	{ https://nodejs.org/api/crypto.html }
	{ https://nodejs.org/api/crypto.html#crypto_crypto_randombytes_size_callback }
	npm install mongoose --save

7. install angular2/cli
==========================================================
	{ https://cli.angular.io/ }
	sudo npm install -g angular/cli
	ng new client && cd client && ng serve
	

8. ADD to Git server_setup branch
===========================================================
	git status
	git add.
	git status
	git branch
	git commit -m "Server Setup"
	git status
	git push --all origin
	git branch
	git checkout master
	git merge server-setup
	git status
	git push