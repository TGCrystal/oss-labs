## Checkpoint 1

![Screenshot](screenshots/1.png)

## Checkpoint 2

The tests run for each submission can be found by clicking the build name, scroll down to "View Tests Summary", and click on that.

![This test](https://open.cdash.org/test/371962067) failed. It does show the line of the test file that failed, along with why it failed. It also showed the command that failed. As far as I can tell though, it does say `ctresalloc.log` does not match but I do not see what it is does print or is supposed to print. 

I am on Ubuntu so ![this one](https://open.cdash.org/build/7123794) would be kind of close to my configuration. It looks like the only test that failed did so due to connecting to some website, so I don't think this would be an issue for me. 

Command line after running the tests:
![](screenshots/2.png)

## Checkpoint 3

Result from `ctest -I 1,50`
![](screenshots/3.png)

I ran `ctest -I 25,25 -VV` to see the verbose output for the failing test, and it showed the test failed because the copyright went until 2020 but the current year is 2021. Here is a screenshot of before and after fixing that:
![](screenshots/3-2.png)

## Checkpoint 4

![Repo](https://github.com/TGCrystal/Lab8-Testing)

Screenshots:
![](screenshots/4-1.png)
![](screenshots/4-2.png)