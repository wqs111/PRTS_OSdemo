# PRTS_OSdemo

CAUTION：  *SYSTEM ON HOLD* 

~~ 本项目参考《30天自制操作系统》，~~
~~试图构建一个较小的可使用操作系统，其名恰好（并非）为PRTS。 ~~

## Introduce


## Build
```cmd
cmd
make run
```
编译所需的工具链保存在tolset, z_tools中

目前的项目结构
```
PRTS_OSdemo
├─ .gitignore
├─  README.md
│  
├─src
│      ipl.nas
│      make.bat
│      Makefile
│      
├─tolset
│  ├─z_new_o
│  ├─z_new_w
│  └─z_osabin
└─z_tools
    ├─guigui00
    ├─haribote
    ├─osa_qemu
    ├─qemu
    ├─qemu_9x
    └─win32
```