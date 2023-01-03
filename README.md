# Xiao Restore

This is a UNIX/MacOS (POSIX) adaption of the restore technique from: [Seeeduino Forum](https://forum.seeedstudio.com/t/how-to-unbrick-a-dead-xiao-using-a-xiao-daplink-and-openocd/261800). 

Clone the repo and flash Xiao-1 with the `simple_daplink_xiao.uf2` firmware. Then, attach the bricked Xiao (Xiao-2) debug pins to Xiao-1 like this: 

![Xiao Wiring](https://forum.seeedstudio.com/uploads/default/original/2X/2/2f54af875128a23df9fe86300d036e50a1b576be.jpeg)

Then run `./flash_unprotected.sh` from the cloned directory. You'll probably need to `brew install openocd` or something like that beforehand.