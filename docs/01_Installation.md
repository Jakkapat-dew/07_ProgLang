## 1. Install VS Code ##
- Request IT to install Visial Studio Code.\
[VScode installer](https://code.visualstudio.com/ "https://code.visualstudio.com/")

## 2. Install Anaconda ##
- Requset IT to insatall Anaconda Environment.\
[Anaconda installer](https://www.anaconda.com/download/success "https://www.anaconda.com/download/success")

## 3. Create an anaconda environment to run python ##
1. Open VSCode\
![](/images/01_start.png "Start VS Code")

2. Install Python extensions
- Click "Extenesion"
- Search  "Python Extension Pack"
- Click "Install"\
![](/images/02_extensions.png)

3. Create folder
- Click Explorer
- Click File > Open folder\
![](/images/03_create%20working%20folder.png)
- Select folder\
![](/images/04_select%20working%20folder.png)

4. New python notebook file(.ipynb)
- Right click > New file\
![](/images/05_new%20file.png)
- Type filename + extension(.ipynb)\
![](/images/06_basic_ipynb.png)
<!-- Comments
- Click "Select Kernel" > "Python Environments"
![alt text](/images/07_select%20kernel%20py%20env.png)
- Click "Create Python Environment
![alt text](/images/08_select%20create%20py%20env.png)
- Click "Conda"
![alt text](/images/09_select%20create%20conda.png)
- Select Python version (Python 3.11)
![alt text](/images/10_select%20python.png)
- Log will show
![alt text](/images/11_creating.png)
- After installation finished, Conda will show.
![alt text](/images/12_conda_show.png)
-->
- At Python Extension
- Click Conda > Create Environment\
![alt text](/images/13_create_conda_env.png)
- Select Python version\
![alt text](/images/14_select%20python_ver.png)
- Set Environment name > Press Enter\
![alt text](/images/15_env_name.png)
- Creating...\
![alt text](/images/16_creating.png)
- After the environment creation was finished. Click on python notebook file(.ipynb)
- Click Select Kernel\
![alt text](/images/17_select%20kernel.png)
- Click Select Another Kernels > Python Environments > Your Environment\
![alt text](/images/18_select%20your%20env%20name.png)
- Verify your environment with python code.
- Click Add Code Cell\
![alt text](/images/19_add%20code%20cell.png)
- Add python code 
``` py 
print("Hello World")
```
![alt text](/images/20_add%20code%20print.png)
- Click Execute Cell or using short cut (Ctrl+Alt+Enter)\
![alt text](/images/21_Exe%20Cell.png)
- Click Install to install ipykernel package
![alt text](/images/22_Install%20ipykernel%20package.png)
- It will recommend you to install by command.
![alt text](/images/23_Install%20ipykernel%20cmd.png)
- To install by command, Go to your conda environment then Click "Open in Terminal"
![alt text](/images/24_open%20in%20terminal.png)
- Install ipykernel package by command to run in terminal\
- Copy this command to run in terminal.
```sh
conda install ipykernel
```
![alt text](/images/25_install%20ipykernel%20cmd.png)
- Type "y" then press Enter to proceed\
![alt text](/images/26_type%20y%20to%20proceed.png)
- Wait until the installation was finished\
![alt text](/images/27_finish.png)
- Click Execute Cell or using short cut (Ctrl+Alt+Enter)\
![alt text](/images/21_Exe%20Cell.png)
- Execution outputs will show.
![alt text](/images/28%20print%20success.png)
