# SSH Hardening

Control Mapping:
AC-17
IA-2

Changes:
PermitRootLogin no
MaxAuthTries 3
LoginGraceTime 60
X11Forwarding no
PasswordAuthentication no

Validation:
sshd -T | grep permitrootlogin
Result: permitrootlogin no
