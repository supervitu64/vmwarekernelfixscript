# vmware kernel fix script
basically a script that fixes a bug regarding newer kernels and vmware compiling while running on those kernels
mostly for 17.5, haven't tested on other versions

copy paste the following script to your console (you need wget and make installed):

```wget https://github.com/supervitu64/vmwarekernelfixscript/releases/download/tag/vmware.sh && chmod +x vmware.sh && ./vmware.sh && sudo rm -rf vmware-*```

this line of commands obtains the script, gives it execution permissions, runs it, then deletes any remnants of it to free up disk space.
if there are problems with the script kindly make an issue and i will fix it
