# Day-1

Most of the contents have been forked from other blogs and from the tensorflow tutorial of Parag K Mital

https://github.com/pkmital

git clone https://github.com/Clanatia/Day-1.git


Tensorflow 설치방법

1. Anaconda3 Tensorflow install  (install time : 20~40 min)

 1) Download and install Anaconda python3 (Windows OS is only use bit 64)  https://www.continuum.io/downloads
   
    if you install Anaconda , please check - All user -
    
    tenosrflow support python 3
 
 2) open cmd
 
 3) typing : 
 
             conda update conda
             
             pip install tensorflow 
             
             or
             
             pip install --upgrade https://storage.googleapis.com/tensorflow/windows/cpu/tensorflow-0.12.1-cp35-cp35m-win_amd64.whl
 
 
 4)Error
 
    if you have Cannot remove entries from nonexistent file \anaconda32\envs\tst\lib\site-packages\easy-install.pth
    
    -> typing:
    
               pip install --upgrade --ignore-installed setuptools
    
    not a supported wheel on this platform
    -> typing:
    
               pip install --upgrade pip
  5)Test
  code: enter python (typing python on cmd)
  
        import tensorflow as tf
        
        hello = tf.constant("Hello, Tensorflow!")
        
        sess = tf.Session()
        
        print(sess.run(hello))
        
        
