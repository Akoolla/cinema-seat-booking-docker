Build the image
sudo docker build -t elevenrox-web-nginx .

Run the container
sudo docker run -p 8080:80 elevenrox-web-nginx
