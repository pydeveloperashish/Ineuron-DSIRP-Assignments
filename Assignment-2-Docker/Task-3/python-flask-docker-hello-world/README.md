Build the image using the following command

```bash
$ docker build -t simple-flask-app:latest .
```
![docker-build](https://user-images.githubusercontent.com/59412013/195299902-48af43aa-4f82-4980-afc0-9202184c71af.png)




Run the Docker container using the command shown below.

```bash
$ docker run -d -p 5000:5000 simple-flask-app
```
![docker-run](https://user-images.githubusercontent.com/59412013/195299956-27ddfadf-cf6f-4124-ab31-d798ca972a93.png)



The application will be accessible at http:127.0.0.1:5000 
![app-running](https://user-images.githubusercontent.com/59412013/195300009-d1728edd-3144-48c7-a62c-8d9e748da8ff.png)
