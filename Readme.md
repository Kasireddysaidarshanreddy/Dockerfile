DOCKERFILE
  CMD
    README.MD
    Dockerfile (write the code)
	     FROM almaliunx 
		 RUN yum install nginx -y
	     CMD ["nginx" , "-g" , "Daemon off;"]
		#CMD ["sleep" , "20] there should be only one CMD instruction if we give multiple the last one will be considered 
     
  FROM 
    README.MD
    Dockerkerfile (write code)
          FROM almalinux:tag 
  RUN
    README.MD  
    Dockerfile (write code)
	      FROM almaliunx 
		  RUN yum install nginx -y 
		  