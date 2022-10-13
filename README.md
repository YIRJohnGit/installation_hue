# installation_hue

sudo su -
yum install -y hue-plugins
yum install -y hue

Setting Up UI
vi /etc/hue/conf/hue.ini
# Search <webhdfs>

in vi dw used for delete a word
Setting up the URL 
webhdfs_url=http://localhost:50070/webhdfs/v1/


vi sudo
========
#huw users
hue ALL=(ALL) ALL
hue ALL=(ALL) NOPASSWD: /sbin/chkconfig
hue ALL=(ALL) NOPASSWD: /sbin/service
hue ALL=(ALL) NOPASSWD: /bin/kill



service hue start
