# How-To-Install-Python3-On-CentOS-7
How To Install Python3 On CentOS 7
1. yum update -y
2. yum install -y python3
3. python3
 (Ctrl+D to exit python shell)

4. yum install gcc openssl-devel bzip2-devel libffi-devel -y
5. curl -O https://www.python.org/ftp/python/3.8...
6. tar -xzf Python-3.8.1.tgz
7. cd Python-3.8.1/
8. ./configure --enable-optimizations
9. make altinstall
10. python3.8
