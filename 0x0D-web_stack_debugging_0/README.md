0x0D. Web stack debugging #0


Resource
Concepts
Network basics
Docker

Readme
What is Docker and why is it popular
Let's first pull a Docker image and run a container:

image
Note that docker command will pull the Ubuntu docker container image from the Internet and run it. I let you look at the meaning of the flags using the command docker run --help, the main idea is that it keeps the container up and running.

To execute a command on the Docker container, use *docker exec*:

image
If you want to connect to your Docker container and use Bash, you need to use *docker exec -ti*:

image
If you want to stop a container, use *docker stop*:

image
Web stack debugging

Intro
Debugging usually takes a big chunk of a software engineer’s time. The art of debugging is tough and it takes years, even decades to master, and that is why seasoned software engineers are the best at it… experience. They have seen lots of broken code, buggy systems, weird edge cases and race conditions.


Test and verify your assumptions
Debugging is fun
Debugging can be frustrating, but it will definitely be part of your job, it requires experience and methodology to become good at it. The good news is that bugs are never going away, and the more experienced you become, trickier bugs will be assigned to you! Good luck 😃


Tasks
0. Give me a page!

image
Advice; install docker on your local machine then pull the docker image debug the issue then proceed.
AVOID installing docker in ubuntu 14.04
