# devops exercise - maya cohen
 
 In every push will start the github action workflow to run.

 the workflow include the following steps: 

1. clean all maven package if exist
2. build and package the java app with maven
3. create artifact of the app
4. create docker image from docker file that in this repo and push to my own dockerHub remote repo

you can pull the image from the repo and create container from this image.

# helm chart:

I create helm chart template with helm commands,
and than I change the image to my own image.