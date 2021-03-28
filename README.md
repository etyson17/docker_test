Welcome to Eric Tyson's Docker application!

to run this file first build it in docker with this command in the terminal:

docker build . -t docker_test

next run this command:

docker run -d -p 8080:80 docker_test

if you get an error that looks like this:

docker: Error response from daemon: driver failed programming external connectivity on endpoint vigilant_turing (40f9628be8b1ea538a0980b9deb880d79f728d443a74ebdb94482057b9c202af): Bind for 0.0.0.0:8080 failed: port is already allocated.

change 8080 to another integer like 8081. When this runs succefully open a browser and enter localhost:8080. If you had to change the 8080 replace it with whatever you changed it to. 
