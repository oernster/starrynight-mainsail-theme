# starrynight-mainsail-theme
Theme for MainSail UI for use with klipper (3D printing) with starry backgrounds and nice colours

Screenshots of the theme can be found in Screenshots.

# Usage and setup
1) Download git.

2) Clone the repo by clicking on code to the right and selecting copy, then type:

git clone <paste in here without corner brackets>

3) Next, in klipper_config on your pi, create a directory called '.theme'

4a) You may need to install scp for your system.

4b) scp (secure copy) all the files (one by one) excluding 'LICENSE,' 'README.md' and the Screenshots directory into the .theme directory on your pi.

e.g. scp <filename without corner brackets> pi@10.0.0.1:<filename without corner brackets>

5) Refresh your browser!

# Comments
At some point I may ask the mainsail repo guys if they want to add this to their docs.
FYI, if you use Kiaou to install a theme (my starrynight theme isn't supported this way yet anyhow), a) in my experience it doesn't work and b) if you're mid print it stops the print unnecessarily because it probably reboots klipper totally unnecessarily or something; these are static files so I lost a print that way - you have been warned!
