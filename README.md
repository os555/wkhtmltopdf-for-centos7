
# How to Setup wkhtmltopdf on CentOS 7
====================================

Install Dependencies
--------------------

  yum install fontconfig libXrender libXext xorg-x11-fonts-Type1 xorg-x11-fonts-75dpi freetype libpng zlib libjpeg-turbo
  
Install wkhtmltopdf
-------------------
  
  wget https://github.com/wkhtmltopdf/packaging/releases/download/0.12.6-1/wkhtmltox-0.12.6-1.centos7.x86_64.rpm
  
  rpm -Uvh wkhtmltox-0.12.2.1_linux-centos7-amd64.rpm
  
Test
----

  wkhtmltopdf http://www.google.com google.pdf
  
Related
-------
[Allow apache to exicute an external program through SELinux.](https://gist.github.com/calebbrewer/e2f29dfe571aa8d1161a#file-stop-selinux-from-blocking-apache-external-program-execution-md)
