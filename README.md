# SSBONDpyinstaller
## VERSION CHOOSE
There are three versions, include MACOS,LIUNX，Windows，please choose the one that suits you.
## Usage  
1.Download source code from github by running:
```
git clone https://github.com/LiuLab-CSRC/SSBONDPredict.git
```
2.Enter the directory where predict is located ,then run predict by:

```
predict 'pdbfile' 'the position of SSBONDPredict' 'the path of outpath'
```

For example,if you choose MACOS version and you download the SSBONDPredict in your Desktop, after enter the directory of macpredict you can run macpredict like this:
```
macpredict /root/Desktop/3irq.pdb /root/Desktop ./
```

## liunx version attention 
If you want choose liunx version,you need to install docker first,the you can do like this:
```
docker pull ubuntu
```
Using the ubuntu image to start a container,and enter the container in command line mode:  
```
docker run -it ubuntu /bin/bash  
```
then run predict in the container as above Usage.
For example:
```
liunxpredict /root/users/test/Desktop/3irq.pdb  /root/users/test/Desktop ./
```
