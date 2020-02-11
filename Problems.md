*Pro1: Run "test.go" in VSCode (WSL) : 
  	Failed to initialize build cache at /home/xulinux/.cache/go-build: mkdir /home/xulinux/.cache/go-build:permission denied
	
	Solution : sudo chmod -R 777 /home/xulinux/.cache
	
	
*Pro2: Failed to push the local file to github
![Image](https://github.com/DerrickXuLuo/Geo-index-Based-Social-Network/blob/master/Pictures/png1.png)
	
	Solution : 1. git pull origin master --allow-unrelated-history
		   2. git push origin master

![Image](https://github.com/DerrickXuLuo/Geo-index-Based-Social-Network/blob/master/Pictures/png2.png)

*Pro3: Failed to run the elasticservice in the instance on GCE
![Image](https://github.com/DerrickXuLuo/Geo-index-Based-Social-Network/blob/master/Pictures/png3.png)

	Solution : According to the "support matrix" of the elasticSearch official website, the version of the installed elasticservice, 	            version 3, only support java whose version is up to 8
		   
		   1. Install the java version 8
![Image](https://github.com/DerrickXuLuo/Geo-index-Based-Social-Network/blob/master/Pictures/png4.png)
		 
		   2. Test the elasticservice again, it works
![Image](https://github.com/DerrickXuLuo/Geo-index-Based-Social-Network/blob/master/Pictures/png5.png)

		   
