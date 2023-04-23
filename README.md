## Overview

Exploring Grafana and Prometheus for application monitoring

## Execution

Tools:
<li> Java 11 </li>
<li> SpringBoot 2.7.8 </li>
<li> Docker </li>
<br>
Back-end: 
Import the project to an IDE of your choice, the IDE used in the development was the Netbeans IDE,
so just build the app to download the dependencies which are managed by Maven,
but first, Docker must be installed and the container images encoded in the <strong>docker-compose.yml</strong> file initialized,
with the command <code>docker-compose up -d</code>, and when the application is running, just access the link http://localhost:3000/ for Grafana with Prometheus and http://localhost:9090/ for only Prometheus metrics.
<br>


## Demo
![image](https://user-images.githubusercontent.com/56695817/233852189-6ee73540-64aa-4cc8-8f4d-1d55f4d1582a.png)

<br>

![image](https://user-images.githubusercontent.com/56695817/233850650-a53f570b-24bf-4a05-a0b6-7589cd3267a9.png)

<br>

![image](https://user-images.githubusercontent.com/56695817/233850738-25e336e9-168e-4b33-8197-730b669d9aca.png)

<br>

![image](https://user-images.githubusercontent.com/56695817/233850305-67b0a80e-8f14-4a07-882b-417781ff9d24.png)
