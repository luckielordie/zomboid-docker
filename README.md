# Zomboid Docker

`docker run --rm --name zomboid -it -p 16261:16261/udp -p 16262:16262/udp -v /zomboid_server/JTWZomboid:/root/Zomboid -v /home/ec2-user/workshop_content:/home/steam/project_zomboid/steamapps luckielordie/zomboid:latest`
