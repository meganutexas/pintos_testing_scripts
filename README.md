#Pintos Testing Scripts

Scripts for testing the PintOS projects with nice colorful PASS/FAIL output

###DON'T FORGET
You still need to know how to use the basic Pintos testing commands yourself
- test everything: **make check**
- determine what your grade is: **make grade**
- run a single test: **tests/[project]/[test].result**
  - use the -VERBOSE flag to see the output from the test as it is being run

###How to use the scripts
All scripts need to go in the [project]/build directory to be run properly. 

Can run with command: 

**source [test script name].**
- it might be helpful to run chmod 755 [test script name] on all the scripts

The create_custom_test_runner can be run with: 

**source create_custom_test_runner [name of script] [list of test categories separated by spaces]**
- need to make sure that create_helpers.zip has been unzipped within the [project]/build directory
- will create a custom test script that only runs the tests associated with the categories you gave it

clean, compile, and show_test can be run for any of the projects in Pintos
