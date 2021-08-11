# Basic commands for GitHub upload :

        c:/GitRepository/test> git init
        c:/GitRepository/test> git add .
        c:/GitRepository/test> git -m commit "first commit"
        c:/GitRepository/test> git remote add origin https://github.com/saifali2019github/spring-rest.git
        c:/GitRepository/test> git push -u origin master
  
 # IF Already done all above steps for PUSH we can only do
	
	      c:/GitRepository/test> git push -u origin master

# IF in case you want to reset/remove the remote origin i.e. "https://github.com/saifali2019github/spring-rest.git"
# you can use following commands :
  
        c:/GitRepository/test> git remote -v  		.............to view remote origin 
        c:/GitRepository/test> git remote rm origin	.......... to clear remote origin
  
# To pull changes : 
  ex: - c:/GitRepository/test> git init
	    	c:/GitRepository/test> git pull https://github.com/saifali2019github/spring-rest.git master
        
        
