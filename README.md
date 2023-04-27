# check system specs in Linux OS Terminal

To check system specs in Linux OS Terminal, you can use various commands depending on the information you need. Here are some commonly used commands:

1. To check the CPU information, use the following command:

```@ruby
$ cat /proc/cpuinfo
```

2. To check the amount of RAM installed, use the following command:

```@ruby
$ free -m
```

3. To check the disk usage, use the following command:

```@ruby
$ df -h
```

4. To check the network interface configuration, use the following command:

```@ruby
$ ifconfig
```

5. To check the version and release of the Linux distribution, use the following command:

```@ruby
$ lsb_release -a
```

6. To check the kernel version, use the following command:

```@ruby
$  uname -a
```

7. To check the GPU information, use the following command:

```@ruby
$  lspci -vnn | grep VGA -A 12
```

These commands will give you information about your system's CPU, RAM, disk usage, network interface, Linux distribution, kernel version, and GPU.
