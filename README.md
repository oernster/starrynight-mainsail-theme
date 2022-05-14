# starrynight-mainsail-theme
Theme for MainSail UI for use with klipper (3D printing) with starry backgrounds and nice colours

Screenshots of the theme can be found in Screenshots.

# Usage and setup
1) Download git.

2) Clone the repo by clicking on the green code button to the right and selecting copy, then type:

git clone -paste_copied_text_here-

3) Next, in ~/klipper_config on your pi, create a directory called '.theme'

4a) You may need to install scp for your system (windows; mac/linux should already have it).

4b) scp (secure copy) all the files (one by one) on to your pi.

e.g. scp pi@10.0.0.1:custom.css custom.css

for each of 'custom.css' 'favicon-32x32.png' 'main-background.jpeg' 'sidebar-background.jpeg' 'sidebar-logo.png'
  
4c) ssh into your pi

4d) Copy each of the 5 files into the directory: /home/pi/klipper_config/.theme

e.g. cp custom.css ~/klipper_config/.theme
     cp *.jpeg ~/klipper_config/.theme
     cp *.png ~/klipper_config/.theme

4e) Delete the pre-copied files:

e.g. rm *.css
     rm *.jpeg
     rm *.png

5) Refresh your browser!

# Comments
FYI, if you use Kiaou to install a theme (my starrynight theme isn't supported this way yet anyhow), in my experience it doesn't work
