### Reset root password

the default admin user is `root`

use the following command to reset password,

`gitlab-rake "gitlab:password:reset"`


### config url

vim /etc/gitlab/gitlab.rb

add `external_url "http://192.168.1.98:8929"`

then gitlab-ctl reconfigure

