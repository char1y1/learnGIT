Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes.


　　在服务器添加完公钥后报错

1
sign_and_send_pubkey: signing failed: agent refused operation
　　这个时候我们只要执行下

1
2
eval "$(ssh-agent -s)"
ssh-add
　　就可以了
