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



yum install python3-pip
mkdir pywinrm_offline
cd pywinrm_offline
python3.9 -m pip download pywinrm
python3.9 -m pip install pywinrm
ansible-galaxy collection install ansible.windows
ansible-galaxy collection install ansible.windows:==1.9.0
ansible-galaxy collection install /root/ansible-windows-1.9.0.tar.gz
ansible windows -i /root/playbook/machine -m win_ping -vvv

ansible-galaxy collection install /root/ansible-windows-1.9.0.tar.gz
ansible-galaxy collection install ansible-windows-1.9.0.tar.gz




python3.9 -m pip install --no-index --find-links=. pywinrm
python3.9 -m pip download pywinrm
python3.9 -m pip install pywinrm


python3.11 -c "import winrm; print(winrm.__version__)"
python3.9 -c "import winrm; print(winrm.__version__)"



~                
