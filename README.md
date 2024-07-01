# OSProject Running Containers for Application Development

Group Name: OS Innovators. 

Section: 1. 

Team Mates:
1. Nur Fatnin Izzati binti Sidik and 2110294
2. Aina Najwa Maisarah Binti Mohamad Zulkarnain and 2212708
3. Diniy Binti Johan and 2224132

## Rules
1. You are allowed to have **3 group** members. *Exception* is allowed **IFF (if and only if)** you are allowed to have 4 group members if you are a **multinational** or a **multigender** group. 
2. When you complete the project, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository. 
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see __Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/

## Forking this OS project repository
1. First thing you need in doing this project is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the OS project repository in your own github account. 

    1. Go to https://github.com/joeynor/OSProject and click fork to copy the project into your own repository
    2. Make sure that the new fork is now in your own repository

***Questions:***

1. What is the link of the fork OSProject in your repository. ***(1 mark)(https://github.com/fatninizz/OSProject.git)
2. How many files and folders are in this repository. ***(1 mark) 6 images file with 2 folders file (images and Readme.md)


## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own OSProject repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name, section and team members along with their matric IDs. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** 
The default OS used to run the virtual environment for Codespaces is Ubuntu.

2. What are the two options of ram, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** 
The two options of RAM, disk, and vCPU configuration for running Codespaces are:

2 cores, 4 GB RAM, 32 GB SSD
4 cores, 8 GB RAM, 64 GB SSD

3. Why must we commit and sync our current work on source control? ***(1 mark)*** 
We must commit and sync our current work on source control to ensure that our changes are saved and shared with others. This allows for collaboration, version tracking, and the ability to revert to previous states if needed.

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** 
/workspaces/OSProject

2. Run the command **cat /etc/passwd** . ***(1 mark)*** 
cat: /ect/passwd: No such file or directory


3. Run the command **df** . ***(1 mark)*** 
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 10381036  20772544  34% /
tmpfs              65536        0     65536   0% /dev
shm                65536        8     65528   1% /dev/shm
/dev/root       30298176 22626628   7655164  75% /vscode
/dev/sda1       46127956      100  43752280   1% /tmp
/dev/loop3      32847680 10381036  20772544  34% /workspaces

4. Run the command **du** . ***(1 mark)*** 
4       ./.git/lfs/tmp
8       ./.git/lfs
8       ./.git/objects/f2
8       ./.git/objects/12
8       ./.git/objects/eb
12      ./.git/objects/0e
8       ./.git/objects/83
8       ./.git/objects/0d
8       ./.git/objects/95
12      ./.git/objects/b5
12      ./.git/objects/72
8       ./.git/objects/47
8       ./.git/objects/7b
16      ./.git/objects/74
12      ./.git/objects/29
8       ./.git/objects/20
8       ./.git/objects/f6
8       ./.git/objects/81
8       ./.git/objects/fc
8       ./.git/objects/4b
12      ./.git/objects/14
8       ./.git/objects/a6
8       ./.git/objects/2b
8       ./.git/objects/52
8       ./.git/objects/93
12      ./.git/objects/ff
8       ./.git/objects/41
12      ./.git/objects/2e
8       ./.git/objects/3f
12      ./.git/objects/e5
12      ./.git/objects/62
8       ./.git/objects/b2
8       ./.git/objects/b6
8       ./.git/objects/cb
8       ./.git/objects/71
8       ./.git/objects/86
8       ./.git/objects/d8
12      ./.git/objects/73
8       ./.git/objects/c3
16      ./.git/objects/91
8       ./.git/objects/4f
12      ./.git/objects/17
8       ./.git/objects/a4
8       ./.git/objects/58
8       ./.git/objects/e7
12      ./.git/objects/fd
1828    ./.git/objects/pack
8       ./.git/objects/4a
8       ./.git/objects/b9
8       ./.git/objects/fa
12      ./.git/objects/af
8       ./.git/objects/35
8       ./.git/objects/fe
16      ./.git/objects/fb
8       ./.git/objects/f7
8       ./.git/objects/3a
12      ./.git/objects/70
12      ./.git/objects/3d
12      ./.git/objects/bf
8       ./.git/objects/49
8       ./.git/objects/96
8       ./.git/objects/60
12      ./.git/objects/1c
8       ./.git/objects/0b
8       ./.git/objects/04
8       ./.git/objects/cd
8       ./.git/objects/c6
8       ./.git/objects/24
8       ./.git/objects/ab
8       ./.git/objects/01
12      ./.git/objects/6e
12      ./.git/objects/44
12      ./.git/objects/64
8       ./.git/objects/c0
12      ./.git/objects/d2
8       ./.git/objects/c4
8       ./.git/objects/a3
4       ./.git/objects/info
8       ./.git/objects/1b
8       ./.git/objects/e9
2552    ./.git/objects
12      ./.git/refs/remotes/origin
16      ./.git/refs/remotes
8       ./.git/refs/heads
4       ./.git/refs/tags
32      ./.git/refs
12      ./.git/logs/refs/remotes/origin
16      ./.git/logs/refs/remotes
8       ./.git/logs/refs/heads
28      ./.git/logs/refs
36      ./.git/logs
68      ./.git/hooks
4       ./.git/branches
8       ./.git/info
2744    ./.git
1972    ./images
4740    .

5. Run the command **ls** . ***(1 mark)*** 
README.md  images

6. Run the command **ls -asl** . ***(1 mark)*** 
total 40
 4 drwxrwxrwx+ 4 codespace root  4096 Jun 26 15:01 .
 4 drwxr-xrwx+ 5 codespace root  4096 Jun 26 15:01 ..
 4 drwxrwxrwx+ 9 codespace root  4096 Jun 26 15:04 .git
24 -rw-rw-rw-  1 codespace root 20740 Jun 26 15:14 README.md
 4 drwxrwxrwx+ 2 codespace root  4096 Jun 26 15:01 images

7. Run the command **free -h** . ***(1 mark)*** 
              total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.4Gi       273Mi        66Mi       6.1Gi       6.0Gi
Swap:            0B          0B          0B

8. Run the command **cat /proc/cpuinfo** . ***(1 mark)*** 
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 2540.265
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 0
initial apicid  : 0
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.86
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:

processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 2543.812
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 1
initial apicid  : 1
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.86
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual

9. Run the command **top** and type **q** to quit. ***(1 mark)***
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 2540.265
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 0
initial apicid  : 0
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.86
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:

processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 2543.812
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 1
initial apicid  : 1
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.86
TLB size        : 2560 4K pages
clflush size    : 64
top - 15:16:46 up 21 min,  0 users,  load average: 0.17, 0.20, 0.35
Tasks:  18 total,   1 running,  17 sleeping,   0 stopped,   0 zombie
%Cpu(s):  1.8 us,  2.7 sy,  0.0 ni, 95.5 id,  0.0 wa,  0.0 hi,  0.0 si,  0.0 st
MiB Mem :   7929.6 total,    287.3 free,   1437.9 used,   6204.3 buff/cache
MiB Swap:      0.0 total,      0.0 free,      0.0 used.   6110.1 avail Mem 

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND    

10. Run the command **uname -a**. ***(1 mark)*** 
Linux codespaces-245ea4 6.5.0-1021-azure #22~22.04.1-Ubuntu SMP Tue Apr 30 16:08:18 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux

11. What is the available free memory in the system. ***(1 mark)*** 273Mi

12. What is the available disk space mounted on /workspace. ***(1 mark)*** 
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 10381304  20772276  34% /
tmpfs              65536        0     65536   0% /dev
shm                65536        8     65528   1% /dev/shm
/dev/root       30298176 22629904   7651888  75% /vscode
/dev/sda1       46127956      104  43752276   1% /tmp
/dev/loop3      32847680 10381304  20772276  34% /workspaces

13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** 
Linux codespaces-245ea4 6.5.0-1021-azure #22~22.04.1-Ubuntu SMP 
x86_64 x86_64 x86_64 GNU/Linux

14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** 
ls lists files and directories in the current directory, while ls -asl provides a detailed list including sizes, permissions, and hidden files.

15. What is the TLB size of the Virtual CPU. ***(1 mark)*** 
TLB size        : 2560 4K pages

16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** 
cpu family      : 25
cpu MHz         : 2914.402
cpu family      : 25
cpu MHz         : 2923.446

17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** 
top - 15:24:59 up 29 min,  0 users,  load average: 0.12, 0.25, 0.32
Tasks:  18 total,   1 running,  17 sleeping,   0 stopped,   0 zombie
top - 15:25:41 up 29 min,  0 users,  load average: 0.11, 0.23, 0.31
Tasks:  18 total,   1 running,  17 sleeping,   0 stopped,   0 zombie
%Cpu(s):  3.0 us,  2.4 sy,  0.0 ni, 94.6 id,  0.0 wa,  0.0 hi,  0.0 si,  0.0 st
MiB Mem :   7929.6 total,    355.3 free,   1454.8 used,   6119.5 buff/cache
MiB Swap:      0.0 total,      0.0 free,      0.0 used.   6092.8 avail Mem 

## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```
2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```

4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```

5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available? Yes
```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```

7. Stop the container and delete the container. What happened to your helloworld.txt? 

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** 

No, files in the container are not persistent because containers are designed to be ephemeral. Any data stored inside the container will be lost when the container is stopped or deleted. To persist data, you need to use volumes or bind mounts, which allow data to be stored outside the container's lifecycle.

2. Can we run two, or three instances of debian linux? . ***(1 mark)*** 

Yes, we can run two or three instances of Debian Linux. Containers are lightweight and isolated, so you can run multiple instances on the same host. Each instance runs independently with its own filesystem, processes, and network interfaces.

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** 

@ainamaisarah ➜ /workspaces/OSProject/myroot (main) $ docker exec -it angry_maxwell bash
root@dc15c8e40dd4:/# touch /root/testfile
root@dc15c8e40dd4:/# ls -l /root
total 0
-rw-r--r-- 1 root root 0 Jun 27 03:55 testfile

2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```
[Yes, we can change the files permission using chown command]

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** 

@ainamaisarah ➜ /workspaces/OSProject (main) $ ls -ld
drwxrwxrwx+ 6 codespace root 4096 Jun 27 04:05 .

2. What port is the apache web server running. ***(1 mark)*** 
Port 80

3. What port is open for http protocol on the host machine? ***(1 mark)*** 
Port 8080

## Create SUB Networks

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below
```bash
## STEP 1:
## Create Networks ##
docker network create bluenet
docker network create rednet`

## STEP 2: (automatically running)
## Create (1) Container in background called "c1" running busybox image ##
docker run -itd --net bluenet --name c1 busybox sh
docker run -itd --net rednet --name c2 busybox sh
```
***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)*** 

BusyBox is a lightweight, single executable that provides several stripped-down Unix tools in a single binary. It's often used in embedded systems and environments where storage and resources are limited because it combines tiny versions of many common UNIX utilities into a single small executable.

2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)*** 

@ainamaisarah ➜ /workspaces/OSProject (main) $ docker network ls
NETWORK ID     NAME      DRIVER    SCOPE
a812a9b5d335   bluenet   bridge    local
4ce8f0dd779d   bridge    bridge    local
1f532b81ced0   host      host      local
c86620e95a38   none      null      local
e0725fabd965   rednet    bridge    local

3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)*** 

@ainamaisarah ➜ /workspaces/OSProject (main) $ docker inspect c1
[
    {
        "Id": "e718524c640e01086783745a541eabae3b85975a6dd221198b999ac07d8ce22b",
        "Created": "2024-06-27T04:13:18.451339979Z",
        "Path": "sh",
        "Args": [],
        "State": {
            "Status": "running",
            "Running": true,
            "Paused": false,
            "Restarting": false,
            "OOMKilled": false,
            "Dead": false,
            "Pid": 36779,
            "ExitCode": 0,
            "Error": "",
            "StartedAt": "2024-06-27T04:13:19.015390712Z",
            "FinishedAt": "0001-01-01T00:00:00Z"
        },
        "Image": "sha256:65ad0d468eb1c558bf7f4e64e790f586e9eda649ee9f130cd0e835b292bbc5ac",
        "ResolvConfPath": "/var/lib/docker/containers/e718524c640e01086783745a541eabae3b85975a6dd221198b999ac07d8ce22b/resolv.conf",
        "HostnamePath": "/var/lib/docker/containers/e718524c640e01086783745a541eabae3b85975a6dd221198b999ac07d8ce22b/hostname",
        "HostsPath": "/var/lib/docker/containers/e718524c640e01086783745a541eabae3b85975a6dd221198b999ac07d8ce22b/hosts",
        "LogPath": "/var/lib/docker/containers/e718524c640e01086783745a541eabae3b85975a6dd221198b999ac07d8ce22b/e718524c640e01086783745a541eabae3b85975a6dd221198b999ac07d8ce22b-json.log",
        "Name": "/c1",
        "RestartCount": 0,
        "Driver": "overlay2",
        "Platform": "linux",
        "MountLabel": "",
        "ProcessLabel": "",
        "AppArmorProfile": "docker-default",
        "ExecIDs": null,
        "HostConfig": {
            "Binds": null,
            "ContainerIDFile": "",
            "LogConfig": {
                "Type": "json-file",
                "Config": {}
            },
            "NetworkMode": "bluenet",
            "PortBindings": {},
            "RestartPolicy": {
                "Name": "no",
                "MaximumRetryCount": 0
            },
            "AutoRemove": false,
            "VolumeDriver": "",
            "VolumesFrom": null,
            "ConsoleSize": [
                9,
                123
            ],
            "CapAdd": null,
            "CapDrop": null,
            "CgroupnsMode": "private",
            "Dns": [],
            "DnsOptions": [],
            "DnsSearch": [],
            "ExtraHosts": null,
            "GroupAdd": null,
            "IpcMode": "private",
            "Cgroup": "",
            "Links": null,
            "OomScoreAdj": 0,
            "PidMode": "",
            "Privileged": false,
            "PublishAllPorts": false,
            "ReadonlyRootfs": false,
            "SecurityOpt": null,
            "UTSMode": "",
            "UsernsMode": "",
            "ShmSize": 67108864,
            "Runtime": "runc",
            "Isolation": "",
            "CpuShares": 0,
            "Memory": 0,
            "NanoCpus": 0,
            "CgroupParent": "",
            "BlkioWeight": 0,
            "BlkioWeightDevice": [],
            "BlkioDeviceReadBps": [],
            "BlkioDeviceWriteBps": [],
            "BlkioDeviceReadIOps": [],
            "BlkioDeviceWriteIOps": [],
            "CpuPeriod": 0,
            "CpuQuota": 0,
            "CpuRealtimePeriod": 0,
            "CpuRealtimeRuntime": 0,
            "CpusetCpus": "",
            "CpusetMems": "",
            "Devices": [],
            "DeviceCgroupRules": null,
            "DeviceRequests": null,
            "MemoryReservation": 0,
            "MemorySwap": 0,
            "MemorySwappiness": null,
            "OomKillDisable": null,
            "PidsLimit": null,
            "Ulimits": [],
            "CpuCount": 0,
            "CpuPercent": 0,
            "IOMaximumIOps": 0,
            "IOMaximumBandwidth": 0,
            "MaskedPaths": [
                "/proc/asound",
                "/proc/acpi",
                "/proc/kcore",
                "/proc/keys",
                "/proc/latency_stats",
                "/proc/timer_list",
                "/proc/timer_stats",
                "/proc/sched_debug",
                "/proc/scsi",
                "/sys/firmware",
                "/sys/devices/virtual/powercap"
            ],
            "ReadonlyPaths": [
                "/proc/bus",
                "/proc/fs",
                "/proc/irq",
                "/proc/sys",
                "/proc/sysrq-trigger"
            ]
        },
        "GraphDriver": {
            "Data": {
                "LowerDir": "/var/lib/docker/overlay2/28427ae6f3ef0a63e89d9d74882e64b7f881d94893484a181c223b51cc690282-init/diff:/var/lib/docker/overlay2/199f72f28e6a6b79e486612b6f5777c429387509d64b5aec143573f0e513bdc9/diff",
                "MergedDir": "/var/lib/docker/overlay2/28427ae6f3ef0a63e89d9d74882e64b7f881d94893484a181c223b51cc690282/merged",
                "UpperDir": "/var/lib/docker/overlay2/28427ae6f3ef0a63e89d9d74882e64b7f881d94893484a181c223b51cc690282/diff",
                "WorkDir": "/var/lib/docker/overlay2/28427ae6f3ef0a63e89d9d74882e64b7f881d94893484a181c223b51cc690282/work"
            },
            "Name": "overlay2"
        },
        "Mounts": [],
        "Config": {
            "Hostname": "e718524c640e",
            "Domainname": "",
            "User": "",
            "AttachStdin": false,
            "AttachStdout": false,
            "AttachStderr": false,
            "Tty": true,
            "OpenStdin": true,
            "StdinOnce": false,
            "Env": null,
            "Cmd": [
                "sh"
            ],
            "Image": "busybox",
            "Volumes": null,
            "WorkingDir": "",
            "Entrypoint": null,
            "OnBuild": null,
            "Labels": {}
        },
        "NetworkSettings": {
            "Bridge": "",
            "SandboxID": "fe7595e036e2fe60cb286e13a44e57ac1641aa8b06ba66e4c07bff745eeffe86",
            "SandboxKey": "/var/run/docker/netns/fe7595e036e2",
            "Ports": {},
            "HairpinMode": false,
            "LinkLocalIPv6Address": "",
            "LinkLocalIPv6PrefixLen": 0,
            "SecondaryIPAddresses": null,
            "SecondaryIPv6Addresses": null,
            "EndpointID": "",
            "Gateway": "",
            "GlobalIPv6Address": "",
            "GlobalIPv6PrefixLen": 0,
            "IPAddress": "",
            "IPPrefixLen": 0,
            "IPv6Gateway": "",
            "MacAddress": "",
            "Networks": {
                "bluenet": {
                    "IPAMConfig": null,
                    "Links": null,
                    "Aliases": null,
                    "MacAddress": "02:42:ac:12:00:02",
                    "NetworkID": "a812a9b5d335cf733761527d233a1cd7e6ab1bcb8e5a06ea7310c98778b0fb7f",
                    "EndpointID": "501215c9f928200b7f8f4a17cfca3bbc1e7e8b250200a90540ebba93b31560dd",
                    "Gateway": "172.18.0.1",
                    "IPAddress": "172.18.0.2",
                    "IPPrefixLen": 16,
                    "IPv6Gateway": "",
                    "GlobalIPv6Address": "",
                    "GlobalIPv6PrefixLen": 0,
                    "DriverOpts": null,
                    "DNSNames": [
                        "c1",
                        "e718524c640e"
                    ]
                }
            }
        }
    }
]
@ainamaisarah ➜ /workspaces/OSProject (main) $ docker inspect c2
[
    {
        "Id": "dbfb13e7150e2b9306277f85eb2c0d439c27b15b60839c0dbdc8a9abf2151107",
        "Created": "2024-06-27T04:13:19.104948237Z",
        "Path": "sh",
        "Args": [],
        "State": {
            "Status": "running",
            "Running": true,
            "Paused": false,
            "Restarting": false,
            "OOMKilled": false,
            "Dead": false,
            "Pid": 36889,
            "ExitCode": 0,
            "Error": "",
            "StartedAt": "2024-06-27T04:13:19.628805837Z",
            "FinishedAt": "0001-01-01T00:00:00Z"
        },
        "Image": "sha256:65ad0d468eb1c558bf7f4e64e790f586e9eda649ee9f130cd0e835b292bbc5ac",
        "ResolvConfPath": "/var/lib/docker/containers/dbfb13e7150e2b9306277f85eb2c0d439c27b15b60839c0dbdc8a9abf2151107/resolv.conf",
        "HostnamePath": "/var/lib/docker/containers/dbfb13e7150e2b9306277f85eb2c0d439c27b15b60839c0dbdc8a9abf2151107/hostname",
        "HostsPath": "/var/lib/docker/containers/dbfb13e7150e2b9306277f85eb2c0d439c27b15b60839c0dbdc8a9abf2151107/hosts",
        "LogPath": "/var/lib/docker/containers/dbfb13e7150e2b9306277f85eb2c0d439c27b15b60839c0dbdc8a9abf2151107/dbfb13e7150e2b9306277f85eb2c0d439c27b15b60839c0dbdc8a9abf2151107-json.log",
        "Name": "/c2",
        "RestartCount": 0,
        "Driver": "overlay2",
        "Platform": "linux",
        "MountLabel": "",
        "ProcessLabel": "",
        "AppArmorProfile": "docker-default",
        "ExecIDs": null,
        "HostConfig": {
            "Binds": null,
            "ContainerIDFile": "",
            "LogConfig": {
                "Type": "json-file",
                "Config": {}
            },
            "NetworkMode": "rednet",
            "PortBindings": {},
            "RestartPolicy": {
                "Name": "no",
                "MaximumRetryCount": 0
            },
            "AutoRemove": false,
            "VolumeDriver": "",
            "VolumesFrom": null,
            "ConsoleSize": [
                9,
                123
            ],
            "CapAdd": null,
            "CapDrop": null,
            "CgroupnsMode": "private",
            "Dns": [],
            "DnsOptions": [],
            "DnsSearch": [],
            "ExtraHosts": null,
            "GroupAdd": null,
            "IpcMode": "private",
            "Cgroup": "",
            "Links": null,
            "OomScoreAdj": 0,
            "PidMode": "",
            "Privileged": false,
            "PublishAllPorts": false,
            "ReadonlyRootfs": false,
            "SecurityOpt": null,
            "UTSMode": "",
            "UsernsMode": "",
            "ShmSize": 67108864,
            "Runtime": "runc",
            "Isolation": "",
            "CpuShares": 0,
            "Memory": 0,
            "NanoCpus": 0,
            "CgroupParent": "",
            "BlkioWeight": 0,
            "BlkioWeightDevice": [],
            "BlkioDeviceReadBps": [],
            "BlkioDeviceWriteBps": [],
            "BlkioDeviceReadIOps": [],
            "BlkioDeviceWriteIOps": [],
            "CpuPeriod": 0,
            "CpuQuota": 0,
            "CpuRealtimePeriod": 0,
            "CpuRealtimeRuntime": 0,
            "CpusetCpus": "",
            "CpusetMems": "",
            "Devices": [],
            "DeviceCgroupRules": null,
            "DeviceRequests": null,
            "MemoryReservation": 0,
            "MemorySwap": 0,
            "MemorySwappiness": null,
            "OomKillDisable": null,
            "PidsLimit": null,
            "Ulimits": [],
            "CpuCount": 0,
            "CpuPercent": 0,
            "IOMaximumIOps": 0,
            "IOMaximumBandwidth": 0,
            "MaskedPaths": [
                "/proc/asound",
                "/proc/acpi",
                "/proc/kcore",
                "/proc/keys",
                "/proc/latency_stats",
                "/proc/timer_list",
                "/proc/timer_stats",
                "/proc/sched_debug",
                "/proc/scsi",
                "/sys/firmware",
                "/sys/devices/virtual/powercap"
            ],
            "ReadonlyPaths": [
                "/proc/bus",
                "/proc/fs",
                "/proc/irq",
                "/proc/sys",
                "/proc/sysrq-trigger"
            ]
        },
        "GraphDriver": {
            "Data": {
                "LowerDir": "/var/lib/docker/overlay2/007b7731d15c18f33d6b68ce3cfccd58cd99f497dcc9e7c4d0c483837ebc5254-init/diff:/var/lib/docker/overlay2/199f72f28e6a6b79e486612b6f5777c429387509d64b5aec143573f0e513bdc9/diff",
                "MergedDir": "/var/lib/docker/overlay2/007b7731d15c18f33d6b68ce3cfccd58cd99f497dcc9e7c4d0c483837ebc5254/merged",
                "UpperDir": "/var/lib/docker/overlay2/007b7731d15c18f33d6b68ce3cfccd58cd99f497dcc9e7c4d0c483837ebc5254/diff",
                "WorkDir": "/var/lib/docker/overlay2/007b7731d15c18f33d6b68ce3cfccd58cd99f497dcc9e7c4d0c483837ebc5254/work"
            },
            "Name": "overlay2"
        },
        "Mounts": [],
        "Config": {
            "Hostname": "dbfb13e7150e",
            "Domainname": "",
            "User": "",
            "AttachStdin": false,
            "AttachStdout": false,
            "AttachStderr": false,
            "Tty": true,
            "OpenStdin": true,
            "StdinOnce": false,
            "Env": null,
            "Cmd": [
                "sh"
            ],
            "Image": "busybox",
            "Volumes": null,
            "WorkingDir": "",
            "Entrypoint": null,
            "OnBuild": null,
            "Labels": {}
        },
        "NetworkSettings": {
            "Bridge": "",
            "SandboxID": "a3eab6e480506ae9ab542ecf7f8657bd70ca1b96226126e4fcc8e88e3420e6c5",
            "SandboxKey": "/var/run/docker/netns/a3eab6e48050",
            "Ports": {},
            "HairpinMode": false,
            "LinkLocalIPv6Address": "",
            "LinkLocalIPv6PrefixLen": 0,
            "SecondaryIPAddresses": null,
            "SecondaryIPv6Addresses": null,
            "EndpointID": "",
            "Gateway": "",
            "GlobalIPv6Address": "",
            "GlobalIPv6PrefixLen": 0,
            "IPAddress": "",
            "IPPrefixLen": 0,
            "IPv6Gateway": "",
            "MacAddress": "",
            "Networks": {
                "rednet": {
                    "IPAMConfig": null,
                    "Links": null,
                    "Aliases": null,
                    "MacAddress": "02:42:ac:13:00:02",
                    "NetworkID": "e0725fabd965fca52112f51aae0e6e81b1307b9c783bd4a292e0d26817c2cfc1",
                    "EndpointID": "78cafbda5737b0ea4f56c2f0bbfee3757714fc3d5299bd5952dc109ca920b5bb",
                    "Gateway": "172.19.0.1",
                    "IPAddress": "172.19.0.2",
                    "IPPrefixLen": 16,
                    "IPv6Gateway": "",
                    "GlobalIPv6Address": "",
                    "GlobalIPv6PrefixLen": 0,
                    "DriverOpts": null,
                    "DNSNames": [
                        "c2",
                        "dbfb13e7150e"
                    ]
                }
            }
        }
    }
]

Rednet: "Gateway": "172.19.0.1"
Bluenet: "Gateway": "172.18.0.1",

4. What is the network address for the running container c1 and c2? ***(1 mark)*** 
Rednet: "Network": "172.19.0.1",
Bluenet: "Network": "172.18.0.1"

5. Using the command ```docker exec c1 ping c2```, which basically tries to do a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)*** __Fill answer here__.
@ainamaisarah ➜ /workspaces/OSProject (main) $ docker exec c1 ping -c 4 172.19.0.1
PING 172.19.0.1 (172.19.0.1): 56 data bytes
64 bytes from 172.19.0.1: seq=0 ttl=64 time=0.074 ms
64 bytes from 172.19.0.1: seq=1 ttl=64 time=0.076 ms
64 bytes from 172.19.0.1: seq=2 ttl=64 time=0.120 ms
64 bytes from 172.19.0.1: seq=3 ttl=64 time=0.081 ms

--- 172.19.0.1 ping statistics ---
4 packets transmitted, 4 packets received, 0% packet loss
round-trip min/avg/max = 0.074/0.087/0.120 ms

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2
```
***Questions:***

1. Are you able to ping? Show your output . ***(1 mark)*** 
@ainamaisarah ➜ /workspaces/OSProject (main) $ docker exec c1 ping -c 4 172.19.0.1
PING 172.19.0.1 (172.19.0.1): 56 data bytes
64 bytes from 172.19.0.1: seq=0 ttl=64 time=0.072 ms
64 bytes from 172.19.0.1: seq=1 ttl=64 time=0.071 ms
64 bytes from 172.19.0.1: seq=2 ttl=64 time=0.086 ms
64 bytes from 172.19.0.1: seq=3 ttl=64 time=0.099 ms

--- 172.19.0.1 ping statistics ---
4 packets transmitted, 4 packets received, 0% packet loss
round-trip min/avg/max = 0.071/0.082/0.099 ms

2. What is different from the previous ping in the section above? ***(1 mark)*** 
In the previous attempt, c1 and c2 were on separate networks (bluenet and rednet respectively) and could not communicate directly.
In this attempt, both c1 and c2 are connected to the bridgenet network, which acts as a bridge between the two subnetworks (bluenet and rednet).
As a result, c1 can now successfully ping c2 because they are both part of the same bridgenet network, allowing them to communicate.

## Intermediate Level (10 marks bonus)

### Node.js and MySQL in Docker Containers

This guide will help you set up a simple Node.js website that retrieves a random row from a MySQL database. Both the MySQL server and the Node.js server will run in separate Docker containers on two separate networks. Your job is to make it work by making the two containers in two separate network bridged together.

#### Step 1: Set Up the Docker Network

Create a Docker network to for the two containers.
For mysql, call it **mysqlnet** for nodejs call it **nodejsnet** .

#### Step 2: Set Up the MySQL Container

Run a MySQL container on the created network.

```sh
docker run --name mysql-container --network mysqlnet -e MYSQL_ROOT_PASSWORD=rootpassword -e MYSQL_DATABASE=mydatabase -e MYSQL_USER=myuser -e MYSQL_PASSWORD=mypassword -d mysql:latest
```

#### Step 3: Set Up the Node.js Container

1. **Create a directory for your Node.js application and initialize it.**

    ```sh
    mkdir nodejs-app
    cd nodejs-app
    npm init -y
    npm install express mysql
    ```

2. **Create a file named `index.js` with the following content:**

    ```js
    const express = require('express');
    const mysql = require('mysql');

    const app = express();
    const port = 3000;

    // Create a MySQL connection
    const connection = mysql.createConnection({
      host: 'mysql-container',
      user: 'myuser',
      password: 'mypassword',
      database: 'mydatabase'
    });

    // Connect to MySQL
    connection.connect((err) => {
      if (err) {
        console.error('Error connecting to MySQL:', err);
        return;
      }
      console.log('Connected to MySQL');
    });

    // Define a route to get a random row
    app.get('/random', (req, res) => {
      const query = 'SELECT * FROM mytable ORDER BY RAND() LIMIT 1';
      connection.query(query, (err, results) => {
        if (err) {
          console.error('Error executing query:', err);
          res.status(500).send('Server Error');
          return;
        }
        res.json(results[0]);
      });
    });

    // Start the server
    app.listen(port, () => {
      console.log(`Server running at http://localhost:${port}`);
    });
    ```

3. **Create a Dockerfile for the Node.js application:**

    ```Dockerfile
    # Use the official Node.js image
    FROM node:14

    # Create and change to the app directory
    WORKDIR /usr/src/app

    # Copy application dependency manifests to the container image
    COPY package*.json ./

    # Install production dependencies
    RUN npm install

    # Copy local code to the container image
    COPY . .

    # Run the web service on container startup
    CMD [ "node", "index.js" ]
    ```

#### Step 4: Build and Run the Node.js Container

1. **Build the Docker image for the Node.js application.**

    ```sh
    docker build -t nodejs-app .
    ```

2. **Run the Node.js container on the same network as the MySQL container.**

    ```sh
    docker run --name nodejs-container --network nodejsnet -p 3000:3000 -d nodejs-app
    ```

#### Step 5: Test the Setup

You can now test the setup by accessing the Node.js application in your browser or using a tool like `curl`:

```sh
curl http://localhost:3000/random
```

#### Step 6: Ensure `mytable` is Populated

Make sure you have created the `mytable` table and populated it with some data in your MySQL database for the above steps to work correctly.

You can use the following SQL commands to create and populate the table (run these commands in the MySQL container):

```sql
CREATE TABLE mytable (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(255) NOT NULL,
  value VARCHAR(255) NOT NULL
);

INSERT INTO mytable (name, value) VALUES ('example1', 'value1'), ('example2', 'value2'), ('example3', 'value3');
```

### Summary

You have now set up a Node.js application in a Docker container on nodejsnet netowrk and a MySQL database in another Docker container on mysqlnet network. Now bridge the two network together.

***Questions:***

1. What is the output of step 5 above, explain the error? ***(1 mark)*** <br />"Cannot GET /" is displayed.
2. Show the instruction needed to make this work. ***(1 mark)*** <br/>Step 6 consist of the instructions needed to solve the issue.<br/>First, we are required to create "mytable" in mysql container. Then, we enter the code provided in step six to input the sample data in the table created. Lastly, we enter "curl http://localhost:3000/random
" in the command prompt as stated in step 5 which will return a random row from the table we have created..



## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***AS STATED IN ITALEEM SYSTEM***
