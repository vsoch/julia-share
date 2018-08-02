# Jupyter Share

This is a notebook modified from the [datascience-notebook](https://github.com/jupyter/docker-stacks/blob/master/datascience-notebook/README.md) stack. It includes many more packages for Julia+Jupyter.


## Usage

This is derived from [this guide](https://github.com/jupyter/docker-stacks/tree/master/datascience-notebook)

```bash
docker pull vanessa/julia-share
```

Run the container, bind your working directory (to save files to your host) to `/home/joyvan/work`

```bash
docker run -it --rm -p 8888:8888 -v $PWD:/home/jovyan/work vanessa/share-julia
```
