## Follow the below commands to make this as a containerize image

# 1. docker build -t node-app:1.0 .
  -t is a tag which is used to set a name for image
# 2. docker images 
# 3. docker run -d -p 3000:3000 node-app
   -d represents detch mode which helps to run a image as a background process 
   -p represents the port which is used for port binding {host port}:{running port} 
4. docker login
5. docker tag node-app:1.0 <username>/node-app:v1.0
6. docker push <username>/node-app:v1.0