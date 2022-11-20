# starrynight-mainsail-theme
Theme for a Voron MainSail UI for use with klipper (3D printing) with starry/moon backgrounds and nice colours

Screenshots of the theme can be found in Screenshots.

# Usage and setup
1) Download git.

2) Clone the repo by clicking on the green code button to the right and selecting copy, then type:

git clone paste_copied_text_here

3) Next, ssh into your pi and enter the command (On windows you may prefer the tool putty):

   mkdir ~/klipper_config/.theme

4a) You may need to install scp for your system (windows; mac/linux should already have it).

4b) scp (secure copy) all the files (one by one) on to your pi.  Or on windows use WinSCP, on mac CyberDuck is a nice UI tool for SFTP.

e.g. scp pi@10.0.0.1:custom.css custom.css

for the whole theme directory copy that into ~/klipper_config/.theme

5) Reboot your pi
