Dcoker All command
* Image Build : docker build -t image_name .    [.  for directory]
* Show image :docker image ls
* Image delete: docker image rm image_id
* Show Container :docker ps ls
* delete containerc with volume : docker rm container_name -fv   [Delete with exestince volume}
* delete container : docker rm container-name -f   [-f for force ]
* Run Image : docker run -v ${pwd}:/app --env-file ./.env -p 3000:3000 -d --name container_name image_name  
              [ Here, -v for volume, 
                powersheel for ${pwd}, If we use cmd then %cd% --env-file if env file present
  
