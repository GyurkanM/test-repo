# SSH signing test
git config --global user.name "GyurkanM"  
git config --global user.email "email@gmail.com"  
git config --global gpg.format ssh  
git config --global user.signingkey C:\Users\username\\.ssh\mykey  
git commit -S -a -m 'some commit msg'
