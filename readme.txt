#Launch with:
docker-compose up -d

#Shut down with:
docker-compose down --rmi 'all'

#This will shut down and clear all images, returning to fresh state on next compose up.

#Launch bash within the container
docker exec -it charlesserver_app_1 bash