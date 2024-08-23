Here are 40 practice questions that align with the RHCSA exam objectives:

### **Essential Tools and Basic System Management**
1. **Basic Commands:**  
   How do you view the last 10 lines of a file named `/var/log/messages`?
   
2. **File Redirection:**  
   Redirect the output of `ls -l` to a file called `output.txt` without overwriting the existing content.

3. **File Compression:**  
   Compress the directory `/data` using `tar` and gzip into a file called `data.tar.gz`.

4. **Text Processing:**  
   Search for the string "error" in the file `/var/log/messages` and display the line numbers where it occurs.

5. **File Management:**  
   Create a hard link and a soft link for the file `/etc/fstab` in the `/tmp` directory.

6. **Permissions:**  
   Set the permissions of the file `file.txt` to `rwxr-xr--` using both symbolic and numeric notation.

7. **User Management:**  
   Create a new user named `johndoe` with a home directory `/home/johndoe`.

8. **Group Management:**  
   Add the user `johndoe` to the group `admin`.

### **Networking and Remote Access**
9. **SSH Configuration:**  
   Configure SSH key-based authentication for a user `johndoe` on a remote server.

10. **Hostname Configuration:**  
    Change the hostname of your system to `rhel9server`.

11. **Network Services:**  
    Start and enable the `httpd` service to run at boot.

12. **Firewall:**  
    Allow HTTP traffic through the firewall using `firewall-cmd`.

13. **IPv6 Configuration:**  
    Assign an IPv6 address to the network interface `eth0`.

14. **Remote File Transfer:**  
    Copy the file `/tmp/data.txt` from your local machine to a remote server using `scp`.

### **Storage Management**
15. **Partitioning Disks:**  
    Create a new primary partition of size 1 GB on `/dev/sdb` using `fdisk`.

16. **Logical Volumes:**  
    Create a new logical volume named `data_lv` of size 500 MB in the volume group `vg01`.

17. **File System Creation:**  
    Format the logical volume `data_lv` with the `xfs` file system.

18. **File System Mounting:**  
    Configure the system to automatically mount the `xfs` file system on `/data` at boot.

19. **Swap Management:**  
    Add a 1 GB swap partition to your system.

20. **Network File Systems:**  
    Mount an NFS share `192.168.1.100:/share` to `/mnt/nfs`.

### **System Management**
21. **System Logs:**  
    Display the last 50 entries in the system journal.

22. **Service Management:**  
    Restart the `cron` service and verify its status.

23. **Scheduled Tasks:**  
    Schedule a cron job to run a backup script `/usr/local/bin/backup.sh` daily at 2 AM.

24. **Kernel Management:**  
    List all installed kernels on your system.

25. **Bootloader Configuration:**  
    Set the default boot kernel to an older version using `grub2-set-default`.

26. **Troubleshooting:**  
    Boot the system into rescue mode and reset the root password.

### **Security Management**
27. **SELinux:**  
    Set SELinux to enforcing mode and list the current SELinux contexts for `/var/www/html`.

28. **File Permissions:**  
    Set the `setgid` bit on a directory `/shared` to ensure that new files created within inherit the group ID.

29. **Firewall Management:**  
    Block all incoming traffic except for SSH and HTTP using `firewall-cmd`.

30. **SELinux Troubleshooting:**  
    Use `ausearch` and `sealert` to diagnose and fix a SELinux-related access denial.

31. **SSH Configuration:**  
    Restrict SSH access to only users in the `admin` group.

### **Container Management**
32. **Container Image Management:**  
    Pull the `nginx` image from a remote registry.

33. **Running Containers:**  
    Start a container using the `nginx` image and expose port 80.

34. **Container Inspection:**  
    Inspect the configuration of a running container to view its IP address.

35. **Persistent Storage:**  
    Attach a persistent volume to a running container and mount it at `/data`.

36. **Container Networking:**  
    Configure a container to communicate with another container on the same host using a custom network.

37. **Containerfile:**  
    Write a `Containerfile` to build a custom image that installs `httpd` and serves a static website.

38. **Container Automation:**  
    Configure a container to start automatically as a systemd service.

### **Final Preparation**
39. **Mock Exam:**  
    Describe the steps to configure a new RHEL 9 system from scratch, including user setup, networking, storage, and security.

40. **Review:**  
    What are the key differences between `systemd` and traditional `init` systems in RHEL 9?

These questions are designed to help you practice key tasks and concepts that you might encounter on the RHCSA exam. They cover a broad range of topics to ensure you have a well-rounded understanding of system administration tasks in a RHEL 9 environment.
