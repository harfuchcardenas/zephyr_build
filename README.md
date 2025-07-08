This repository is a Perl script created to be run on the linux command line. After been cloned follow the following steps to build a Zephyr project.

Installation (Ubuntu 20.04.1 LTS):

--Clone the repository--

git clone git@github.com:harfuchcardenas/humidity-control.git cd zephyr_build

--Access directory--

cd zephyr_build

--Give execution permission-- chmod +x ./build-file

--Run script-- ./build-file

Notes: If it is the first time the script is been run, then an Error will prompt out as there the Virtual Environment is created and the directories created are not updated in runtime, so re-run ./build-file. If the script is run consecutively for different source directory it is needed to remove manually the build/ directory before the script is run again.
