# jupyter
Utility scripts to add new kernels into JupyterLab docker extension. Before start, install the extension as it described [here](https://www.docker.com/blog/getting-started-with-jupyterlab-as-a-docker-extension/).

## How to Use

To add the desired kernel, launch a terminal and execute the following: 

### Java
```
 ~ % docker exec -ti --user root jupyter_embedded_dd_vm /bin/sh -c "curl -s https://raw.githubusercontent.com/CaptainApollo/jupyter/main/addJava.sh | bash"
```

### Go

```
 ~ % docker exec -ti --user root jupyter_embedded_dd_vm /bin/sh -c "curl -s https://raw.githubusercontent.com/CaptainApollo/jupyter/main/addGo.sh | bash"
```



Finally, restart the extension (close, then reopen) to complete installation.
