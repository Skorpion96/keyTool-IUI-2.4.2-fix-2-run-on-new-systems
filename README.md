# keyTool-IUI-2.4.2-fix-2-run-on-new-systems
Tried to fix this old tool to run it on new systems, it was failing to run, so i did my best and now it works, the original tool:https://code.google.com/archive/p/keytool-iui/

Download the original tool from:https://code.google.com/archive/p/keytool-iui/downloads (there are two, shouldn't matter which one), extract the jar with an archive manager, rename the folder "ktl241sta" as "keyTool IUI-2.4.2"

Rename rc15ktl.jar to main.jar, delete run_ktl.bat and run_ktl.sh and copy at their place the ones on this repo "keyTool IUI-2.4.2-run.bat" and "keyTool IUI-2.4.2-run.bat", on Windows you can then run the "keyTool IUI-2.4.2-run.bat" to run the tool, on Linux you may want to copy the program folder "keyTool IUI-2.4.2" to /opt using a root file manager or 'sudo cp -R "keyTool IUI-2.4.2" /opt', then copy the "keyTool IUI-2.4.2.desktop" from the app folder to /home/$USER/.local/share/applications where $USER is your username.

This is a 2011 tool, so don't expect much from it, there are better alternatives like:https://keystore-explorer.org/ but since i had started fixing it i finished, and in the end it was fun. The PNG for the icon is a random one from google
