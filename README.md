<!-- Running -->

First, I created a React app as per the assignment requirements by running .
Next, I opened the Ubuntu terminal and navigated to the folder containing the Dockerfile for my React app which is "pawanpreetakursite-".
 Using the script provided for dockerizing my React app, I built the Docker image and tagged it with the name 'kaur_pawanpreet_coding_assignment11' by using cmd "sudo docker build -t kaur_pawanpreet_coding_assignment11. here i used "-t" flag to tag the image .
 After creating the Docker image, I ran the Docker container with the command `sudo docker run -p 7775:3000 kaur_pawanpreet_coding_assignment11`. This mapped port 7775 on my computer to port 3000 inside the container.
To access the web application, I opened a web browser and entered "localhost:7775" in the address bar. This allowed me to view the web application I created using React.