### When Command not found 
## 
### 
Switch the user
```bash
bash: sudo: command not found
```
Check if you’re root
```bash
whoami
```
If the output is:
```bash
root
```
You are already root, so you don’t need sudo.

You can directly run:
```bash
apt update -y
```

##### If You’re Not Root
If you’re not root and sudo isn’t installed, you can install it after switching to root:
```bash
su -
```

Now install sudo:
```bash
apt update
apt install sudo -y
```
Then add your user to the sudo group:
```bash
usermod -aG sudo <your_username>
```
Logout and log back in — now you can use sudo.

#### If You’re Inside a Docker Container

Docker images (like ubuntu:latest) often don’t have sudo by default.

You can install it manually (as root):

apt update
apt install sudo -y
