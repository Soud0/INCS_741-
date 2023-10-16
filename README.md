# INCS_741-Assignment 2: RAIL FENCE CIPHER IMPLEMENTATION 
## Step 1: Docker Installation
Basic on your system, download the correct docker version from the website. Here is an example of Windows system.
## Step 2. Create a Dockerfile
Under the file folder, create a Dockerfile. Here is the Dockerfile
```bash
FROM python:3.12-slim
WORKDIR /usr/src/app
COPY assignment_2.py .
CMD ["python", "./assignment_2.py"]
```
## Step 3. Build Docker Images
Navigate to the directory containing your Dockerfile and assignment_2.py script in the Terminal, then run:
```bash
docker build -t assignment2 .
```
Here the docker image name is assignment2
## Step 4. Run a Docker Container
Once the image is built, run the container with:
```bash
docker run -it assignment2
```
## Example of Rail Fence Cipher
Here is an example of rail fence cipher when you're running docker container
![cipher] (https://github.com/Soud0/INCS_741-/blob/Assignment_2/cipher.JPG)
