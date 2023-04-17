# FBProphet-Time-Series-Forecasting
Steps to install FBProphet and its dependencies : https://medium.com/data-folks-indonesia/installing-fbprophet-prophet-for-time-series-forecasting-in-jupyter-notebook-7de6db09f93e

Note : FBProphet works properly only in python version < 3.9, so we used created a virtual env with python 3.8.

Anaconda command to install fbprophet : https://anaconda.org/conda-forge/fbprophet

To run the virtual enviroment in jupyter notebook: (Use this for help : https://www.youtube.com/watch?v=UeDJ9PY_aqg&ab_channel=DataForTraders)
  1. Open Anaconda prompt
  2. run command >> conda activate virtual_env_name
  3. run command >> pip install --user ipykernel
  4. python -m ipykernel install --user --name=time_series
  
Newly created kernels and envs of jupyter notebook are stored here
C:\Users\[User-Name]\AppData\Roaming\jupyter\kernels

After performing all the steps, type command JUPYTER NOTEBOOK in anaconda prompt.
Once it opens, select the env that you have created

--See this image for your reference
![image](https://user-images.githubusercontent.com/37772760/232401414-42c9be77-db8d-4457-80ab-1a4350873ffd.png)

Now you are good to go and start coding

