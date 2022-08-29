# Extenstions

![image](https://user-images.githubusercontent.com/101969911/187269544-ab0a5dd8-1724-4bea-af1b-418fd90ab1fe.png)

## Challenge file
[flag.zip](https://github.com/CyberSecurityHat/CTF-Writeup/files/9446978/flag.1.zip)

## Solve

#file flag.zip <- Zip archive data <br>
#upzip flag.zip

#file flag.jpg <- 7-zip archive data <br>
#7zr x flag.jpg

#file flag.png <- POSIX tar archive<br>
#tar -xvf flag.png

#file flag.docx <- gzip compressed data <br>
#mv flag.docx flag.gz <br>
#gunzip flag.gz

#file flag <- bzip2 compressed data <br>
#mv flag flag.bz2 <br>
#bunzip2 flag.bz2

#file flag <- JPEG image data<br>
#display flag

![image](https://user-images.githubusercontent.com/101969911/187271170-a210ae0c-4a7b-496e-b851-074e412ac7e8.png)

## Comments

This is a matter of finding the extension through the file command and then unpacking it or changing the extension.<br>
This is a good challenge to learn the basics of extensions.

## flag
flag{1a1b0846961ddb23dad57bb5da727599}
