


```
docker build -t rjubuntu .
docker run -d --name rjucontainer rjubuntu
docker run -d -p 80:80 --name rjucontainer rjubuntu
```


(note: the container is not running. It is buggy)