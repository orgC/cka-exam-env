

# 初始化环境
## MacOS 初始化
```
# 安装ansible
brew install ansible

# 安装sshpass
wget https://sourceforge.net/projects/sshpass/files/sshpass/1.08/sshpass-1.08.tar.gz
tar zxvf sshpass-1.08.tar.gz
cd sshpass-1.08
./configure
make
make install
```


# 测试ansible hosts
```
ansible -i hosts -m ping all 
```
