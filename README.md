# Codium Docker training

## Requirements

You need Docker and Docker Compose. For that, you have several options:

1. Install Docker in your local machine (recommended)

   - https://docs.docker.com/get-docker/
   - On a Linux system, you need to manually install Docker Compose: https://docs.docker.com/compose/install/

2. Use an online Docker playground
   - Navigate to https://labs.play-with-docker.com/
   - You need to Login with a Docker Hub account. If you don't have one, you can create it easily from [here](https://hub.docker.com/signup)
   - Click on "Start"
   - Click on "Add new instance" (the instance will be alive for 4 hours)
   - There you can write any Docker or Docker Compose command as you would do it from you local machine.
   - We would recommend you to upload this repository to you playground instance:
     - From the playground instance terminal: `wget https://github.com/CodiumTeam/docker-training/archive/refs/heads/master.zip && unzip master.zip`
     - The previous command creates a folder named `docker-training-master` that contains all the resources of this repository.
   - In case you need it, you can upload any file or folder from your local machine to your playground instance:
     - To copy a file: `scp [your-filename] [your-instance-id]@direct.labs.play-with-docker.com:/root`
     - To copy a folder recursively: `scp -r [your-folder] [your-instance-id]@direct.labs.play-with-docker.com:/root`

## Exercises

- [Exercise 1: hello world](exercise-1)
- [Exercise 2: basic commands](exercise-2)
- [Exercise 3: ports, envs and volumes](exercise-3)
- [Exercise 4: Docker Compose](exercise-4)
- [Exercise 5: build your own image](exercise-5)
- [Exercise 6: building more efficient images](exercise-6)
- [Exercise 7: using Docker in your development environment](exercise-7)
- [Exercise 8: publish your own image](exercise-8)
- [Exercise 9: troubleshooting](exercise-9)
- [Exercise 10: clean up the system](exercise-10)
- [Exercise 11: security](exercise-11)
- [Exercise 12: pipelines](exercise-12)


## Interesting resources

### General

- https://github.com/GoogleContainerTools/distroless
- https://github.com/docker/awesome-compose

### Docker Compose

- https://github.com/docker/awesome-compose
- https://jvns.ca/blog/2021/01/04/docker-compose-is-nice/

### Tools for troubleshooting and monitoring

- https://github.com/bcicen/ctop
- https://github.com/jesseduffield/lazydocker

### Best practices

- https://docs.docker.com/develop/develop-images/dockerfile_best-practices/
- https://yodralopez.dev/docker-cheatsheet-v2.pdf
- https://cheatsheetseries.owasp.org/cheatsheets/Docker_Security_Cheat_Sheet.html

### Other interesting learning resources

- [KataCoda](https://www.katacoda.com/?q=docker&hPP=12&idx=scenarios&p=0&is_v=1)
- https://training.play-with-docker.com/
