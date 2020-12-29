# Acer-S50-51-hackintosh
## 电脑配置

|   规格   |                         详细信息                          |
| :------: | :-------------------------------------------------------: |
| 电脑型号 |                  宏碁 S50-51 笔记本电脑                   |
| 操作系统 |                  macOS Catalina 10.15.x                   |
|  处理器  |                   英特尔 Core i5-10210U                   |
|   内存   |                   8 GB ( DDR4 2400MHz )                   |
|   硬盘   | 西数 WDC PC SN520 SDAPNUW-512G-1014 ( 512 GB / 固态硬盘 ) |
|   显卡   |                    英特尔 UHD Graphics                    |
|  显示器  |                奇美 CMN15E7 ( 15.5 英寸  )                |
|   声卡   |                      Realtek ALC255                       |
|   网卡   |                       原装网卡AX201                       |

## 已知问题

- 目前触摸板、键盘这些问题需要解决，可以正常使用。

## 安装部分

- #### 安装教程

  - `F2`进入BIOS,
  - 先查看

- 安装之后操作

  - 安装好系统之后，先用制作好的EFI文件进入系统

  - `终端`执行以下代码

  - ```
    sudo spctl --master-disable
    ```

  - 再执行重建缓存：

  - ```
    sudo kextcache -i /
    ```

  - 完整替换EFI

  - 最后重启完成

## 电脑正常工作部分

- 显卡
- 电源
- 无限网卡
- 声卡
- 睡眠

## 参考教程

- [教程链接]: https://dortania.github.io/OpenCore-Install-Guide	"教程链接"

- 教程链接

