# check-links
* 文件类型：批处理文件
* 文件功能：批量检查文件里面的链接对象是否存在
* 支持检查的对象：md/html都支持；可遍历检查包含多级子文件夹目录的路径。
* 使用方法：
    1. 把check_links.sh放在对应目录下
    2. 在已部署了git服务器的系统中，一般情况下 找一个支持运行linux命令的控制器即可）在空白处，右键菜单选择git bash here 
    输入举例如下:
    ```bash
    $ ./check_links.sh .（遍历检查当前文件夹下的所有子文件和子文件夹）
    ```
    ![企业微信截图_17503176831570](https://github.com/user-attachments/assets/78e9c804-4570-4f6d-b951-2596818c0f7c)
