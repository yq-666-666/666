一个简易的电话簿

## 在 VMware 中安装 Ubuntu 22.04

1. 前往 Ubuntu 官网下载 `ubuntu-22.04-desktop-amd64.iso`。
2. 打开 VMware Workstation/Player，点击 **Create a New Virtual Machine**。
3. 选择 **Installer disc image file (iso)**，加载下载好的 Ubuntu 22.04 ISO。
4. 客户机系统选择 **Linux**，版本选择 **Ubuntu 64-bit**。
5. 按需分配资源（建议：2 核 CPU、4GB 内存、40GB 磁盘）。
6. 完成虚拟机创建后启动，安装类型选择 **Erase disk and install Ubuntu**（仅作用于虚拟磁盘）。
7. 按提示设置语言、时区、用户名和密码，等待安装完成后重启进入系统。
8. 系统启动后在 VMware 菜单安装 VMware Tools（或在 Ubuntu 中执行 `sudo apt install open-vm-tools open-vm-tools-desktop`）。
