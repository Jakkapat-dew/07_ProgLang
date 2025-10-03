## 1. Install VS Code ##
- Request IT to install Visial Studio Code.
[VScode installer](https://code.visualstudio.com/ "https://code.visualstudio.com/")

## 2. Install Anaconda ##
- Requset IT to insatall Anaconda Environment.
[Anaconda installer](https://www.anaconda.com/download/success "https://www.anaconda.com/download/success")

## 3. Create an anaconda environment to run python ##
1. Open VSCode
![](./images/01_start.png "Start VS Code")

2. Install Python extensions
- Click "Extenesion"
- Search  "Python Extension Pack"
- Click "Install"
![](./images/02_extensions.png)

3. Create folder
- Click Explorer
- Click File > Open folder
![](../images/03_create_working_folder.png)
- Select folder  
![](./images/04_select_working_folder.png)

4. New python notebook file(.ipynb)
- Right click > New file  
![](./images/05_new_file.png)
- Type filename + extension(.ipynb)  
![](./images/06_basic_ipynb.png)
<!-- Comments
- Click "Select Kernel" > "Python Environments"
![alt text](./images/07_select_kernel_py_env.png)
- Click "Create Python Environment
![alt text](./images/08_select_create_py_env.png)
- Click "Conda"
![alt text](./images/09_select_create_conda.png)
- Select Python version (Python 3.11)
![alt text](./images/10_select_python.png)
- Log will show
![alt text](./images/11_creating.png)
- After installation finished, Conda will show.
![alt text](./images/12_conda_show.png)
-->
- At Python Extension
- Click Conda > Create Environment  
![alt text](./images/13_create_conda_env.png)
- Select Python version  
![alt text](./images/14_select_python_ver.png)
- Set Environment name > Press Enter  
![alt text](./images/15_env_name.png)
- Creating...  
![alt text](./images/16_creating.png)
- After the environment creation was finished. Click on python notebook file(.ipynb)
- Click Select Kernel  
![alt text](./images/17_select_kernel.png)
- Click Select Another Kernels > Python Environments > Your Environment\
![alt text](./images/18_select_your_env_name.png)
- Verify your environment with python code.
- Click Add Code Cell  
![alt text](./images/19_add_code_cell.png)
- Add python code 
    ``` py 
    print("Hello World")
    ```
![alt text](./images/20_add_code_print.png)
- Click Execute Cell or using short cut (Ctrl+Alt+Enter)  
![alt text](./images/21_Exe_Cell.png)
- Click Install to install ipykernel package
![alt text](./images/22_Install_ipykernel_package.png)
- It will recommend you to install by command.
![alt text](./images/23_Install_ipykernel_cmd.png)
- To install by command, Go to your conda environment then Click "Open in Terminal"  
![alt text](./images/24_open_in_terminal.png)
- Install ipykernel package by command to run in terminal  
- Copy this command to run in terminal.
```sh
conda install ipykernel
```
![alt text](./images/25_install_ipykernel_cmd.png)
- Type "y" then press Enter to proceed  
![alt text](./images/26_type_y_to_proceed.png)
- Wait until the installation was finished  
![alt text](./images/27_finish.png)
- Click Execute Cell or using short cut (Ctrl+Alt+Enter)  
![alt text](./images/21_Exe_Cell.png)
- Execution outputs will show.  
![alt text](./images/28_print_success.png)
