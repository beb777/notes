# notes
# installation 
* tar file tar.gz
` tar -ztvf filename.tar.gz`  
` tar -xf filname.tar.xz`
* Installing OpenJDK
`dnf search openjdk`  
`sudo dnf install <openjdk-package-name>`  
* install pycharm  
  - mkdir ~/Apps
  - download pycharm pycharm-community-2020.3.2.tar.gz
  - cd /apps ls
  - tar -xvzf pycharm-community-2020.3.2.tar.gz #extract 
  - rm pycharm-professional-2017.1.3.tar.gz # remove the packege 
  - cd pycharm-professional-2017.1.3/  # change the directry 
  -  ./bin/pycharm.sh  # run pycharm  
 *change defult editor either vim or nano something else  
which vim and add the path in export 
example    export EDITOR=/usr/bin/vim

  add the line of code in   ~/.bashrc
`export EDITOR=vim`
