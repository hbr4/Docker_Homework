# Docker_Homework
## For this homework, you need to complete the Docker Getting Started guide sections 1,2, and 3 found. Please also read sections 4,5, and 6 to complete your basic knowledge of Docker.

 

 - Firstly, a python script was developed for hello-world. The script used was:

    `print("Hello-World!")`

 - Then, a dockerfile was created using the follow script:

    `FROM python:3  `
      
    `ADD hello-world.py /  `
      
   ` RUN pip install pystrich ` 
      
    `CMD [ "python", "./hello-world.py" ]`

 - A Docker Hub account was created and the image was pushed to Docker Hub. Refer to the below: [https://hub.docker.com/r/hbr4njit/hello-world](https://hub.docker.com/r/hbr4njit/hello-world)

Finally, all commits were pushed to GitHub.