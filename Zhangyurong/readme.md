# IoV_paper_reading

本项目用于记录相关文献的阅读。

Our mission is to promote the security of Internet of Vehicles and autonomous driving.

People working on the paper reading program:
- [Zheng Xue](./Xuezheng/paper_reading_xz.md)
- [Yurong Zhang](./Zhangyurong/paper_reading_zyr.md)
- [Hongmin Wei](./Weihongmin/paper_reading_whm.md)

## 使用指南
- 各分支修改后上传到自己所在分支并合并到主分支操作
1. 切换到自己所在分支
   ```
   git checkout zyr
   ```
2. 拉取最新主分支内容到zyr
    ```
    git pull origin master
    ```
    ![Alt text](./images/image_1.jpg)
3. 修改、更新内容
4. 添加到自己所在分支
    ```
    git add .
    ```
5. 添加评论
    ```
    git commit -m "update..."
    ```
    ![Alt text](./images/image_2.jpg)
6. 上传到自己所在分支
    ```
    git push origin zyr
    ```
    ![Alt text](./images/image_3.jpg)
7. 切换到主分支
    ```
    git checkout master
    ```
8. 在主分支中合并分支zyr
    ```
    git merge zyr
    ```
    ![Alt text](./images/image_4.jpg)
9. 更新推送到主分支
    ```
    git push origin master
    ```
    ![Alt text](./images/image_5.jpg)
