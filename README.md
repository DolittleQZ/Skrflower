# Skrflower

## 一、项目目录介绍   

Android-安卓工程文件   
Backend-后端工程文件   
Web    -网页工程文件   

## 二、分支介绍   

master     -主分支，用于发布    
dev        -工作分支，合并三端代码，再更新到master      
dev_android-安卓端工作分支，提mr到dev     
dev_backend-后端工作分支，提mr到dev     
dev_web    -网页端工作分支，提mr到dev     

## 三、开发说明

开发人员首先将dev或对应的dev_type分支代码fork到自己的github    
然后在个人的github分支上进行开发   
开发完后提交pull request到dev_type    
项目管理者最后将dev_type中的代码合并到dev    
确认无误后再将dev分支merge到master分支

