# dockernight
Exercises and material for a 3-hour workshop for BeCode students.

## Presentation
The link to the slides can be found [here](https://github.com/0ctavia/dockernight/blob/master/dockerpresentation.odp).

## Exercises



1. Clone the repository. Build the docker image.

Do not forget to add a tag (with the -t option) to avoid randomly generated image names.

2. Run the image you just build.

3. Enter into the running container and delete the targetfile. Look in the Dockerfile to see where it is.

4. Exit the running container and stop the container.

5. Delete the container.

6. Run the container again, and look for the targetfile.

    *hint: it should be back*

7. Exit the container, and try to write a command line that will delete your targetfile without getting into the container.

8. Stop and remove the container. Run it again and map your container to a port through the command line (your docker container when running on port 80).

    Surfing to localhost:[ _yourport_ ]/index.php should show you a Dockernight exercises webpage.

9. Stop and remove the container. Run it again but mount the website directory as a volume, over the target directory, and expose a port.

    Surfing to localhost:[ _yourport_ ]/index.php should show you a different webpage.



