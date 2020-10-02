                                                                   Griggorii@gmail.com

Example load profile icc color calibration

Open edit source color.jcnf rename /home/$user_name$ save and icc profile edit replace

Terminal run in folder location autostart color color.jcnf copy paste enter command: 

cp -r autostart color color.jcnf ~/.config && chmod -R a+rwx ~/.config/autostart/z-displaycal-apply-profiles.desktop
