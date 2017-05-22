# Magento 2 auto pull and deploy shell script

Shell script that  pulls lates changed from git automatically and if there is changes then runs deploy scirpts for magento 2 project.

## Getting Started

Download the project and copy project files to the root of the magento directory

### Prerequisites

Basic knowledge about shell scirpts, commandline scripts and the cron jobs.

```
Give examples
```

### Installing

1. Copy shell script(s)  to the base of the magento 2 project.
```
TODO
```
2. Go trough settings of the deploy script. The default should be goot to go, but some there is some settings that allows you to change some processes.
```
TODO
```
3. Make a test, check if the script does not fail.
```
TODO
```
4. Add script to cron tasks.
```
TODO
```
5. Test if the cron job works.
```
TODO
```


## Built With

## Versioning

## Authors

* **Aivars Lauzis** - *Initial work* - [PurpleBooth](https://github.com/lauzis)


## License

This project is licensed under the GPL3 - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration


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