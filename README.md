it is docker compose to set up the env 

to run it

```
docker compose up
```

you can add flag as you needs.

to cleanly shut it down and rm images and free all the ports 
```
docker rm $(docke stop $(docker ps -q))
docker system purne -a
```
