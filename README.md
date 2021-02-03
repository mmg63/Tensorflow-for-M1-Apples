# Tensorflow-for-M1-Apples
How to be able to install Tensorflow on M1 Apple macbooks and mac mini

#Apple_M1_Tensorflow
I'd run in to problem when I bought apple M1 processor #macbookair for using neural engine chipset in my #machinelearning models. Eventually, I found out how should I get my issue sort out. Now I like to share my finding to others.
First, They should refer to the apple's GitHub page 
https://lnkd.in/dS5xvNH

In the following, I will describe some steps to install tensorflow in their apple computer equipped M1 processor as my experiences:
1- Download Mac-optimized TensorFlow in apple GitHub page,

2- Download X_code_command_line tools(if not installed in your macbook from Apple_developer_tools page),

3- uninstall python3 from macbook and reinstall it from command line tools

4- open terminal via spotlight and create a directory for your project(e.g., mkdir myproject)

5- Go to you project folder(e.g., cd myproject)

6- create a virtual enviroment(e.g., python3 -m venv .mytensorflow_env) in your project folder

7- unzip your files downloaded from apple GitHub page using tar command(e.g., tar -xvg tensorflow_macos-0.1alpha1.tar.gz)

8- run: sh sh tensorflow_macos/install_venv.sh -p, then activate your environment (. myproject/.mytensorflow_env/bin/activate)

9- Tensorflow will be installed and,

10- enjoy it.
