Project scanario:
Install the necessary software on the machines using configuration management tool
Git workflow has to implemented
CodeBuild should automatically be triggered once a commit is made to master branch or develop branch
a. if a commit is made to master bracnch,testand push to prod
b. If a commit is made to develop branch,just test the product, do not push to prod
4.  The code should be containerized with the help of Dockerfile. The Dockerfile should be built every time there is a push to Github. Use the following pre-built container for ur application:hshar/webapp
The code should reside in '/var/www/html'
The above tasks should be defined in a jenkins Pilpline with the following jobs
job1 build
job2 test
job3 prod
