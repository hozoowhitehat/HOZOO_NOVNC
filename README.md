# HOZOO_NOVNC
😄 halo semua ini adalah sc install di shell clond atau codespaces dan selamat menikmati 😄👍


git clone https://github.com/hozoowhitehat/HOZOO_NOVNC

cd HOZOO_NOVNC


docker build -t alpine-xfce4 Alpine_xfce4_noVNC/


docker run -it -p 6080:6080 -p 56780:56780 --name alpine-novnc alpine-xfce4
