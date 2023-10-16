# IoV_paper_reading

本项目用于记录相关文献的阅读

## 使用指南
1. 安装[Git](https://git-scm.com/)
   
2. 克隆本项目
   ```
   git clone https://github.com/Internet-of-Vehicles-Code/IoV_paper_reading.git
   ```
3. 新建自己的文件夹及对应的markdown文件
   
   ![Alt text](./images/image.png)
4. 更新自己的论文阅读部分
5. 创建一个本地分支并推送到创建的新分支xz
   ```
   git checkout -b xz
   ```
   ![Alt text](./images/image-1.png)
   ![Alt text](./images/image-2.png)
   ![Alt text](./images/image-3.png)
6. 切换到主分支合并代码
   ```
   git checkout master
   ```
   ```
   git merge xz
   ```
   ![Alt text](./images/image-4.png)
   ![Alt text](./images/image-5.png)
7. 推送到主分支
   ```
   git push origin master
   ```
   ![Alt text](./images/image-6.png)