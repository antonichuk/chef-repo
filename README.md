chef-solo-demo
==============

1) Copy the whole application to the node (system).

2) Install the chef-solo using :

curl -L https://www.opscode.com/chef/install.sh | sudo bash

3) Verify the installation using :

chef-solo -v

4) After that execute the chef-solo using

chef-solo -c solo.rb -j node.json


Enjoy Coding..!
