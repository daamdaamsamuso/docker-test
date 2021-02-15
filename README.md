#Docker Test
###Installation
<pre>
cd /home
git clone https://github.com/daamdaamsamuso/docker-test.git
cd docker-test
</pre>
###Run
<pre>
#Login for private Docker Repository
docker login
docker pull daamdaamdev/docker-test
docker run -p 80:80 -v /home/Docker-test/Project:/var/www/html daamdaamdev/docker-test
</pre>
