## OpenVpn User Limit Crack
openvpn access server install file and crack file.

#### Before starting with the project you need to install ``` net-tools ```
```
yum -y install net-tools
yum -y install wget
yum -y install nano
```

##### 1. Download the project:
```
git clone https://github.com/drunkleen/openvpn_as_crack.git
```
##### 2. Change Directory to downloaded Path:
```
cd openvpn_as_crack
```
##### 3. Install OpenVpn Server:
```
rpm -ivh openvpn-as-2.5-CentOS7.x86_64.rpm
```
Or
```
yum -y install openvpn-as
```
##### 4. Set the password:
```
passwd openvpn
```
##### 5. Go to your OpenVPN:
example

```https://your_server_address:943/admin```


### Time To crack
##### 1. Redirect to downloaded Reposetory:
```
cd openvpn_as_crack
```
##### 2. Copy the patch file into installed OpenVPN Directory:
```
cp pyovpn-2.0-py2.7.egg /usr/local/openvpn_as/lib/python2.7/site-packages/
```
##### 3.Redirect to downloaded App Reposetory:
```
cd /usr/local/openvpn_as/bin
```
##### 4. Run the ```ovpn-init``` to reconfigure OpenVPN:
```
./ovpn-init
```
Type ```DELETE``` and the ```yes```

If an error is reported and the relevant module cannot be found, edit _ovpn-init and annotate it.
