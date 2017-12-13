# d-apt
Debian APT repository for D tools

This is an experimental alternative to http://d-apt.sourceforge.net/.

The plan is:

1. Creating this repo

2. Upload script used to generate packages in http://d-apt.sourceforge.net/

3. Add the necessary automation to upload the packages to https://bintray.com/dlang-community/

4. First be able to trigger a build when a DMD version is released

5. Implement some sort of automatic trigger, so when a new DMD version is out the packages gets automatically generated and uploaded

6. Leave this repo in testing mode for some time (keeping the old d-apt repo updated)

7. pitch the project to Walter and co.

8. move it directly to the dlang organization and make it official

If we can't reach 8, we can just keep this one.
