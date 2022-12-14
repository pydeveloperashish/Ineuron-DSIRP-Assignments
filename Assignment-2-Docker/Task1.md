### Demonstrate minimum 15 basic docker command with explanation and screenshot.

---------------------------------------------------------------------------------------------------------------------------------------------------------

### check docker images:
```bash
docker images
```
![docker-images](https://user-images.githubusercontent.com/59412013/195279858-859b709d-f148-4a1b-8ccd-6ee57de4b912.png)



### check docker version:
```bash
docker --version
```
![docker-version](https://user-images.githubusercontent.com/59412013/195280527-d48bb71e-0cfe-42a6-b26c-fc7828ea467d.png)



### pull docker image:
```bash
docker pull hello-world
```
![docker-pull](https://user-images.githubusercontent.com/59412013/195281931-252d4556-c8a5-476f-81c8-4675ded03afe.png)



### run docker image:
```bash
docker run hello-world
```
![docker-run](https://user-images.githubusercontent.com/59412013/195281962-83a7fdff-ffd8-4af4-aedd-a3a868e8cd37.png)



### run docker image in detach mode:
```bash
docker run -d hello-world
```
![docker-run-detach-mode](https://user-images.githubusercontent.com/59412013/195282211-acbedee9-ec4f-42c4-8bde-047d741e00fb.png)



### check running docker containers:
```bash
docker ps
```
![docker-ps](https://user-images.githubusercontent.com/59412013/195282010-670b8426-2ae8-4e08-a685-c234fbfede3f.png)




### check all docker containers:
```bash
docker ps -a
```
![docker-ps-all](https://user-images.githubusercontent.com/59412013/195282054-5dfcc976-7767-436e-a568-1bda59515dba.png)



### Start one or more stopped containers:
```bash
docker start
```
![docker-start](https://user-images.githubusercontent.com/59412013/195284145-de06c948-9179-4fce-896f-7b821044eb0c.png)




### Stop one or more running containers:
```bash
docker stop
```
![docker-stop](https://user-images.githubusercontent.com/59412013/195284168-cf883c74-abd5-441e-b692-d1b5e6a8702e.png)



### Remove one or more containers:
```bash
docker rm
```
![docker-rm](https://user-images.githubusercontent.com/59412013/195284219-3d644172-a5cb-49ce-bdb0-96e5a69edd06.png)



### Remove one or more images:
```bash
docker rmi
```
![docker-rmi](https://user-images.githubusercontent.com/59412013/195284281-2e1681c0-656b-4548-b96a-caf33d9b556a.png)





### Rename a container:
```bash
docker rename current_name name_you_want_to_give
```
![docker-rename](https://user-images.githubusercontent.com/59412013/195286388-5c6f19b9-986d-4eda-a37e-639acf4986e8.png)




### Display a live stream of container(s) resource usage statistics:
```bash
docker stats
```
![docker-stats](https://user-images.githubusercontent.com/59412013/195286451-5a467004-2250-4096-b675-2e0ad58cdf7d.png)





### Fetch the logs of a container:
```bash
docker logs container_id
```
![docker-logs](https://user-images.githubusercontent.com/59412013/195287486-676f067b-a1dd-4934-bbba-867fb37b544d.png)





### Kill one or more running containers:
```bash
docker kill container_id
```
![docker-kill](https://user-images.githubusercontent.com/59412013/195287545-c9030323-c9c9-43d5-bb6e-f3e02125a00b.png)

