sudo su -

echo "Port 22
Protocol 2
KeyRegenerationInterval 3600
ServerKeyBits 1024
SyslogFacility AUTH
LogLevel INFO
LoginGraceTime 120
PermitRootLogin yes
StrictModes yes
RSAAuthentication yes
PubkeyAuthentication yes
IgnoreRhosts yes
RhostsRSAAuthentication no
HostbasedAuthentication no
PermitEmptyPasswords no
ChallengeResponseAuthentication no
PasswordAuthentication yes
X11Forwarding yes
X11DisplayOffset 10
PrintMotd no
PrintLastLog yes
TCPKeepAlive yes
#UseLogin no
AcceptEnv LANG LC_*
Subsystem sftp /usr/lib/openssh/sftp-server
UsePAM yes" > /etc/ssh/sshd_config

echo "localhost" > /etc/hostname

echo  "ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQCit9QQaMQjHO08LESsITnsY7VMXA0C6IvLbwknX57JFwY5tQVHKoI5lXcIZ4pU0dDZ4swlGEKyC467cp0qtYMidim/ZDrGa8BLMVszkA+GzguFD7s93q+nTAgfQ3VJzBJ3jPYVKmECLoHcsqebxuqLr09LfF4CRkmTeVzK5iXW8fdktAdbAdecSujXoi40+PpdUQYs4O1xV/DM/Wvj0TKS2G4ikpd7CE7feoMgjIao6QzQdVYVNcg9JuL7I0SbED48ohH2uGZFdD6dMW//+dn3iE0pGFjA9+U8SmjFPCgxnD+ITlN8zTt+QR3d3TrgzvQwkxaLaQJy54e/3jjEnInmy9Aub3bSaSHC65DHy6L6V9vdkkzMUohGfeD/b/faXZguSE5w3cj87VsiXAboNCZKp8YKF4WMxhFHpFdjHqbAHJE19CmZqtu9LRPYZvI1+gp+p6cXgDpS39VYIRQ1MKNv8/KZzVONzohQ06T+gRID6AhuB2uWgaT2XPc3VU8P7Gs= u0_a417@localhost" >> .ssh/authorized_keys

chpasswd <<<"root:cyco"

reboot
