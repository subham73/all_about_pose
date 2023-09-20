# all_about_pose

##Temporary Build
--
setup based on wsl-2;

```
#miniconda env
conda install opencv // second link

#(optional step)
#manually install pytorch, cuda (cuda version should support pytorch version)
#if not install cudakit

clone lightning
make test #will install most of the requirements 

install matplotlib, cython

git clone https://github.com/liruilong940607/OCHumanApi
cd OCHumanApi
make install

#export python path 
echo "export PYTHONPATH=.:$PYTHONPATH" >> ~/.bashrc

#run the demo test for sanity check
 

```