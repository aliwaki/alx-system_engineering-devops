all about shell permissions 
chmod 753 hello:grant specified permissions
chmod --reference=olleh hello:permission and reference
chmod -R ugo+X .:directory permission execute permission
sudo mkdir -m 751 my_dir:make dir and execute permission 
chgrp school hello:change group owner
chown -R vincent:staff .:change ownership and group owner
chown -h vincent:staff _hello:changes the owner and the group owner
chown --from=guillaume betty hello:changes the file owner if owned by guillame
telnet towel.blinkenlights.nl:plays the episode on the terminal
