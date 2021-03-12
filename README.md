# test-gitpush
##熟悉git操作

###报错1
![image](https://user-images.githubusercontent.com/67595678/110922911-40f51c00-835b-11eb-9374-142425109c01.png)  
原因：服务器的SSL证书没有经过第三方机构的签署  
处理：
https://www.jianshu.com/p/9d163c041c24   创建ssh密钥（本地git和远端github是通过ssh加密传输的）
