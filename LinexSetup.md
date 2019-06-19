
### List your instance ip and DNS name

<pre>
ifconfig
cat /etc/resolv.conf
</pre>
![ex_screenshot](./캡처_linux_ip_dns_cm.PNG)
![ex_screenshot](./캡처_linux_ip_dns_mn.PNG)
![ex_screenshot](./캡처_linux_ip_dns_dn1.PNG)
![ex_screenshot](./캡처_linux_ip_dns_dn2.PNG)
![ex_screenshot](./캡처_linux_ip_dns_dn3.PNG)

### List the Linux release
<pre>
 cat /etc/redhat-release
</pre>
![ex_screenshot](./캡처_linux_version.PNG)

### List file system capacity(master node)
<pre>
 df -h
</pre>
![ex_screenshot](./캡처_linux_filesystem_capa.PNG)

### List command & output for yum repolist enabled
<pre>
yum repolist
</pre>
![ex_screenshot](./캡처_linux_yum_repo.PNG)


### List the /etc/passwd for training
<pre>
cat /etc/passwd
</pre>
![ex_screenshot](./캡처_linux_passwd_entries.PNG)


### List the /etc/group for skcc
<pre>
cat /etc/group
</pre>
![ex_screenshot](./캡처_linux_group_entries.PNG)

### List output the flowing commands
<pre>
getent group skcc
getent passwd training
</pre>
![ex_screenshot](./캡처_getent.PNG)


