这是一个GitHub-Git常用语法介绍文档


使用 git 命令克隆模版： git clone git@github.com:xjmwx4/xjmwx4.github.io.git  (/之后 .gt之前为repo)

复制文件到另一文件： cp -r your_source_document/* your_destination_document/ （记得在github根目录下 从master返回github目录指令： cd .. ）






cd      进入用户主目录；

cd  ~  进入用户主目录；

cd  -  返回进入此目录之前所在的目录；

cd  ..  返回上级目录（若当前目录为“/“，则执行完后还在“/"；".."为上级目录的意思）；

cd ../..  返回上两级目录；

cd  !$  把上个命令的参数作为cd参数使用