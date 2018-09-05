## install jupyter notebook
pip instal jupyter
## launch jupyter notebook
jupyter notebook
## create a kernel in a virtualenv
source bin/activate 
python -m ipykernel install --name kernel_name
source deactivate
## delete a kernel
jupyter kernelspec list (to show all the existing kernels)
sudo jupyter kernelspec uninstall kernel_name (to delete the kernel)
