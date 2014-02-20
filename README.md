A Blog Exercise On Learning NodeJS
====================
Environment:Ubuntu/LinuxMint  NodeJS v0.10.25
---------------------

###Inital & Start MongoDB:
>1,Download:http://www.mongodb.org/downloads
>
>2,Unzip the file to your filesystem,and rename the unzip folder by name "mongodb".
>
>3,open the dir ~/mongodb/ by terminal,
>
	and exec 
		$ mkdir blog-db
		$ cd bin
		$ mongod -dbpath ~\mongodb\blog-db   
		#the code above can connect db to project and let project save data into blog-db
###Get Blog Project:
>open the your Projects direction,
>
    and exec
        $ git clone https://github.com/Channely/PracticeNodeBlog.git
        $ cd blog
        $ npm install
        $ node app
        #then open localhost:3000 in Chrome.


