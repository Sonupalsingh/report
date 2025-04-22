## on window
Get-Service winrm
Start-Service winrm
winrm e winrm/config/listener
winrm quickconfig



## On linux
*sudo /usr/bin/python3.11 -m pip install pywinrm





sudo yum install python3-pip

pip install ansible pywinrm



[windows]
win_server1 ansible_host=172.16.5.104 ansible_user=Administrator ansible_password=aaaa ansible_connection=winrm ansible_winrm_transport=ntlm ansible_winrm_port=5985
~                                                                                                                                                             
~                
