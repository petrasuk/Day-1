# Day-1
TTT 1일차 수업자료
Tensorflow 설치방법
1. Anaconda3 Tensorflow install
 1) Download and install Anaconda 3 (Windows OS is only use bit 64)
 2) open cmd
 3) typing : 
             conda update conda
             pip install tensorflow
 4)Error
    if you have Cannot remove entries from nonexistent file d:\anaconda32\envs\tst\lib\site-packages\easy-install.pth
    -> typing: pip install --upgrade --ignore-installed setuptools
    
    not a supported wheel on this platform -> typing: pip install --upgrade pip
