docker-ubuntu-ijulia
========================

Minimal Docker Image running Julia in IPython notebook

Run it using
```
docker run -d -p 8888:8888 sbminimal/docker-ubuntu-ijulia
```

and access it via your webbrowser at [http://127.0.0.1:8888/](http://127.0.0.1:8888/).

If you want to persist your notebooks, you can link the /data/notebooks directory to some <local-directory> using

```    
docker run -d -p 8888:8888 -v <local-directory>:/data/notebooks sbminimal/docker-ubuntu-ijulia
```

