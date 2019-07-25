---


---

<h1 id="useful-docker-information">USEFUL DOCKER INFORMATION</h1>
<h2 id="definition">Definition:</h2>
<p><em>Docker is a container management service. The keywords of Docker are develop, ship and run anywhere. The whole idea of Docker is for developers to easily develop applications, ship them into containers which can then be deployed anywhere.<br>
docker is client-server architecture.</em></p>
<h2 id="features">Features:</h2>
<ol>
<li>
<p>Docker has the ability to reduce the size of development by providing a smaller footprint of the operating system via containers.</p>
</li>
<li>
<p>With containers, it becomes easier for teams across different units, such as development, QA and Operations to work seamlessly across applications.</p>
</li>
<li>
<p>You can deploy Docker containers anywhere, on any physical and virtual machines and even on the cloud.</p>
</li>
<li>
<p>Since Docker containers are pretty lightweight, they are very easily scalable.</p>
</li>
</ol>
<h2 id="containers">Containers:</h2>
<ul>
<li>A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another.</li>
<li>A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings.</li>
</ul>
<h2 id="difference-between-vms-and-docker">Difference between VMs and Docker</h2>
<p><a href="https://www.freecodecamp.org/news/a-beginner-friendly-introduction-to-containers-vms-and-docker-79a9e3e119b/">Refer This…</a></p>
<blockquote>
<p>Advantage of using docker:<br>
<em>Containers take a different approach: by leveraging the low-level mechanics of the host operating system, containers provide most of the isolation of virtual machines at a fraction of the computing power.</em><br>
NOTE:<br>
<em>Docker Image is a file with many layers<br>
Docker Containers are runtime instances of docker image<br>
Containers are writable while Image is only readable</em><br>
<a href="https://pythonise.com/feed/flask/building-a-flask-app-with-docker-compose">Refer here to build Docker Compose file with Simple flask web application and nginx image to expose one port to list to another</a></p>
</blockquote>
<blockquote>
<p>Alternatives:<br>
Some alternatives to Docker are Solaris Zones, BSD jails, and LXC</p>
</blockquote>
<h2 id="docker-components">Docker Components:</h2>
<ol>
<li>Docker Engine/Server<br>
<em>The Docker daemon (dockerd) listens for Docker API requests and manages Docker objects such as images, containers, networks, and volumes. A daemon can also communicate with other daemons to manage Docker services.</em></li>
</ol>
<blockquote>
<p>Main Tasks of docker engine/server</p>
</blockquote>
<ul>
<li>Run as a Daemon</li>
<li>Building Images</li>
<li>Downloading Images</li>
<li>Stating Containers</li>
<li>Stopping Containers<br>
Six REST API for remote management</li>
</ul>
<ol start="2">
<li>Docker Client<br>
<em>Docker client is a key component which used by many Docker users to interact with Docker. When you run the docker commands, the client sends these commands to dockerd, which carries them out. The docker command uses the Docker API also Docker client can communicate with more than one daemon.</em></li>
</ol>
<blockquote>
<p>Main Tasks</p>
</blockquote>
<ul>
<li>communicates with the docker server using the REST API.</li>
</ul>
<blockquote>
<p>Example: Client machine</p>
</blockquote>
<blockquote>
<p>NOTE:</p>
</blockquote>
<ul>
<li>The machine running the docker server is called “docker host”.</li>
<li>ngnix web server similar to apache.</li>
<li>debian is a file structure</li>
</ul>

