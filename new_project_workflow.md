|---> Install Anaconda3
|------- Download the installer file;
|------- Install using bash command i.e. $bash <downloaded installer file path>
|---> Create and activate a virtual environment
|------- python -m venv <venv_name> (Creates venv in current directory);
|------- source <venv_name>/bin/activate (Activates the venv).
|---> Install ipykernel in the venv
|------- pip install ipykernel
|---> Attach venv with Jupyter
|------- python -m ipykernel install --user --name=<venv_name>
|---> Check that the kernel is attached to Jupyter
|------- jupyter kernelspec list
|---> To remove a specific kernel/venv
|------- jupyter kernelspec uninstall <kernel_name>
