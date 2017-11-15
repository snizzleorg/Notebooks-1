# Jupyter Notebooks to work with different SymPhoTime files

At the moment this repository only contains one Notebook to illustrate how to work with the tiff files generated by SymPhoTime64 (http://www.picoquant.com/products/category/software/symphotime-64-fluorescence-lifetime-imaging-and-correlation-software)

## Installing / Running

### Docker2Repo
The easiest way of setting up Jupyter to run the notebooks of this repository is generating a Docker image specifically for the Notebooks.

 1. Install Docker
    * Windows: https://docs.docker.com/docker-for-windows/install/
    * OSX: https://docs.docker.com/docker-for-mac/install/
    * Ubuntu: https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/
 2. Install Docker2Repo (https://github.com/jupyter/repo2docker)
   
   ```pip install jupyter-repo2docker```

 3. Create and run Docker image directly from this repository
 
   ```jupyter-repo2docker git@github.com:PicoQuant/Notebooks.git```
 
### Conda
