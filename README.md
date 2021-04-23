# SSBONDpyinstaller
Usage
1.download the source from github by running:
'''
git clone https://github.com/LiuLab-CSRC/SSBONDPredict.git
'''
2.Enter the directory where where predict is located ,then run predict by:

'''
predict pdbfile the position of SSBONDPredict the path of outpath
'''

for example,you download the SSBONDPredict in your Desktop,you can run predict like this:
'''
predict /root/Desktop/3irq.pdb /root/Desktop ./
'''

## VERSION CHOOSE
There are three versions, include MACOS,LIUNX，Windows，please choose the one that suits you.  
if you want choose liunx version,you need to install docker first,the you can do like this:
'''
docker pull ubuntu
'''
Using the ubuntu image to start a container,and enter the container in command line mode:  
'''
docker run -it ubuntu /bin/bash  
'''
then run predict in the container as Usage.
