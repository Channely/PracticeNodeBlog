A Blog Exercise On Learning NodeJS

Environment:Ubuntu/LinuxMint  NodeJS v0.10.25


DB:
Inital
1,Download:http://www.mongodb.org/downloads
2,Unzip the file to your filesystem,and rename the unzip folder by name "mongodb".
3,open the dir ~/mongodb/ by terminal,
	and exec 
		$ mkdir blog-db
		$ cd bin
		$ mongod -dbpath ~\mongodb\blog-db   
			#connect db to project & save data into blog-db
Blog:
$ git clone https://github.com/Channely/PracticeNodeBlog.git
$ cd blog
$ npm install
$ node app
Then:
Open localhost:3000 in Chrome.


