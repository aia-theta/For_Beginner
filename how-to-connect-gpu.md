## About how to connect to the server

### What you need are as follow
1. Connecting tools
  * For windows: [Putty](http://www.putty.org/)
  * For linux: Command-line
2. IP
  * For instance, 140.109.1.1
3. Account
  * Please contact to Catding or Sean
  
### Steps
1. Open Putty
* For Windows
![Step1_for_Win](/Source_files/connect_to_server_step1_win.png)
* For Liniux
![Step1_for_Linux](/Source_files/connect_to_server_step1_linux.png)

2. Key in Server IP and type your account and password
![Step2](/Source_files/connect_to_server_step2.png)
3. Open jupyter notebook from server
* step3-1
note that your **port number should be unique** (suggest > 8001)
![Step3_1](/Source_files/connect_to_server_step3_1.png)
* step3-2
![Step3_2](/Source_files/connect_to_server_step3_2.png)

4. Connect to jupyter notebook with your local environment
* step4-1
copy and paste strings shown in step3-2
![Step4_1](/Source_files/connect_to_server_step4_1.png)
* step4-2
modify the "localhost" to "server ip" (for instance, 140.109.17.41 in this example)
![Step4_2](/Source_files/connect_to_server_step4_2.png)

5. Open a python environment
![Step5](/Source_files/connect_to_server_step5.png)

## Important
[How to setup GPU usage](https://github.com/vashineyu/slides_and_others/blob/master/tutorial/gpu_usage.pdf) <br>
** Your must set your GPU ID before run the model ** <br>
Type **nvidia-smi** can help you know which GPU has been already taken. <br>
![nvidia-smi](/Source_files/connect_to_server_step6.png)
