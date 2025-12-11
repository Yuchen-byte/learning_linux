条件：
1. 仅在终端中完成
2. 不能使用 VScode
任务：
1. 创建如下目录结构
linux_explorer_学号/
├── documents/
│   ├── work/
│   │   └── projects/
│   └── personal/
├── backups/
└── system_info/
2. 在projects/目录下创建2个文本文件，分别命名为 project1.txt,project2.txt
3. 在personal/ 目录下创建my_project.doc文件
4. 收集系统信息到文件：
使用df -h查看磁盘使用情况，保存到system_info/disk_usage.txt
使用du -sh查看项目目录大小，保存到system_info/project_size.txt
使用cat合并这两个信息文件为system_info/summary.txt
5. 使用find命令查找项目中所有的文本文件(txt)
6. 将项目下所有带project字段的文本文件复制到backups/目录下

