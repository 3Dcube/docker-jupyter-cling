I think cling + jupyter is absolutely unusable. Now you can check it yourself:
```bash
docker run -it --rm -p 8888:8888 3dcube/jupyter-cling start-notebook.sh --NotebookApp.token=''
```
If you still want use it, let's check documentation
[docker-stacks/base-notebook/README.md](https://github.com/jupyter/docker-stacks/blob/master/base-notebook/README.md)
