# magento2-auto-pull-and-deploy
Mangento 2 project auto pull on test server and deploy static code


Version 1.0.1 Todo's
--------------------------

* Move settings to one place (probably head of deploy_auto.sh)
* Move all code to one file (probably deplay_ayto.sh)
* Add autopull to the deplay_auto.sh (that it would pull latest changes from branch before deploying)


Version 1.0.0
------------------
Initial commit.

There is auto deploy file that checks the cnanges, and compares to last git changes,
if it differs then calls either deploy_master.sh  or deploy_develop.sh

deploy_master.sh
swithecs magento 2 to production mode, and does compilation of static content, clears cache, makes upgrade

deploy_develop.sh
switches magento 2 to develop mode, and does compilation of static content, clears cache, makes upgrade.