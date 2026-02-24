#Create three docker images, representing frontend, backend, mongo db.
#Connect the images using docker compose.
#push it to your dockerhub.
#Create Jenkins Job, where performing the following actions,
  Build updated Docker images when changes are pushed to GitHub.
  Push those images to Docker Hub.
  Automatically pull the latest images and restart containers on the VM.
#Reverse Proxy: The entire application should be accessible via port 80
