#### Setup:

1. $

#### Some commands

$ docker swarm init
$ docker swarm leave --force
$ docker stack deploy -c stack.yml MyStack

$ docker stack ls
$ docker stack services MyStack

- Configure you Matomo Analytics
  $ docker stack rm MyStack
  $ docker stack deploy -c stack.yml MyStack

in browser: localhost

(it flag = interactive mode)
$ docker exec -it <dockerId or name> /bin/sh
