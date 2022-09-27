# Docker_exercise

This image will provide you with systhem information about processes that are currently running on your systhem.

You will be able to build this image by using command docker build and parameter that is a folder from which you're going to build (e.g. docker build [folder_name]). After that the first step is FROM alpine, that allowes a container to run on it's own OS and also it will download it if you don't have it installed. Next step is COPY. Once the image is built it will contain a file called script.sh at a location /script.sh inside alpine Linux box.

To push this image on your Docker hub repository first you need to have a Docker hub account. After that you need to create a repository where you will push your image. Then log into the Doker hub in command line. Find the image ID that you want to push and tag that image (e.g. docker tag [image_name]:[version] [username]/[image_name]:[version]). Then push your image to the repository you created (e.g. docker push [image_name]). 
