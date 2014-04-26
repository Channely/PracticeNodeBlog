A Blog Exercise On Learning NodeJS
====================
Environment:Ubuntu/LinuxMint  NodeJS v0.10.25
---------------------

###You can use the guide "Initial & Start MongoDB","Get Blog Project" for this project version before(not include) commit:'init heroku'.
###If you use the latest version of this project, you should only use guide 'Get Blog Project'.

###Initial & Start MongoDB:
>1,Download:http://www.mongodb.org/downloads
>
>2,Unzip the file to your filesystem,and rename the unzip folder by name "mongodb".
>
>3,open the dir ~/mongodb/ by terminal,
>
	and exec 
		$ mkdir blog-db
		$ cd bin
		#start mongodb
		$ mongod -dbpath ~\mongodb\blog-db   
		#the code above can connect db to project and let project save data into blog-db
		#stop mongodb
		#$ sudo service mongodb stop
		#If catch error while start/staop/restart mongodb, this is possible [solutions](http://my.oschina.net/coderman/blog/201555).
		#添加新功能后，都要清空数据库（即删除 ~\mongodb\blog-db 文件夹里所有文件）

###Get Blog Project:
>open the your Projects direction,
>
    and exec
        $ git clone https://github.com/Channely/PracticeNodeBlog.git
        $ cd PracticeNodeBlog
        $ npm install
        $ node app
        #then open localhost:3000 in Chrome.


