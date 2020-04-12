# 1. Install Jupyter Notebook
* Download the latest version of Python 3 at this link: https://www.python.org/downloads/

* Make sure python has been added to System Path (should be added automatically on installation).

* Open cmd.exe and type in the following command to install jupyterlab:
``` 
> python -m pip install jupyterlab
```

# 2. Install IRKernel to enable working with R in Jupyter Notebook
* Assuming that you have already installed R, now open R console and type in the following command:
```
> install.packages('IRkernel')
```
* Wait for the installation to finish, then type in the following command to make IRKernel available to Jupyter:
```
> IRkernel::installspec(user = FALSE)
```

# 3. Run Jupyter Notebook server on localhost
* Open cmd.exe, switch to your desired path where you stored your notebooks (*.ipynb* files) using **cd** command, then type in the following command to start Jupyter notebook:
```
> jupyter notebook
```
* After the Jupyter server has started, it will automatically open a new tab on your browser to the localhost from where you can navigate and open your notebooks.