## Operating System (OS)
- what is Operating System?
- 常見的作業系統:
  - 伺服器常用作業系統
  - 手機作業系統
  - 雲端作業系統
- 作業系統的功能與服務 
- 作業系統的運作模式:Dual mode operation - 雙重模式
  - user mode vs Kernel Mode
  - [Kernel Mode 與 User Mode 的概念](https://medicineyeh.wordpress.com/2015/02/10/kernel-mode-%E8%88%87-user-mode-%E7%9A%84%E6%A6%82%E5%BF%B5/)
- [Privileged instruction（特權指令）](https://wangwilly.github.io/willywangkaa/2018/07/10/Operating-System-Basic-Concept-2/)
- kernal vs shell
  - [kernal](https://en.wikipedia.org/wiki/Kernel_(operating_system)#:~:text=The%20kernel%20is%20a%20computer,between%20hardware%20and%20software%20components.)
  - [核心（Kernel|內核）](https://zh.wikipedia.org/wiki/%E5%86%85%E6%A0%B8)
    - The kernel is a computer program at the core of a computer's operating system and generally has complete control over everything in the system
    - 核心在計算機科學中是一個用來管理軟體發出的資料I/O（輸入與輸出）要求的電腦程式，將這些要求轉譯為資料處理的指令並交由`中央處理器（CPU）`及電腦中其他電子元件進行處理，是現代作業系統中最基本的部分
    - 核心是為眾多`應用程式`提供對`電腦硬體`的安全存取的一部分軟體，這種存取是有限的，並由核心決定一個程式在什麼時候對某部分硬體操作多長時間。
    - 直接對硬體操作是非常複雜的。所以核心通常提供一種硬體抽象的方法，來完成這些操作。有了這個，通過行程間通訊機制及系統呼叫，應用行程可間接控制所需的硬體資源（特別是處理器及IO裝置）。

## Linux Operating System 
- linux kernal [英文版WIKI](https://en.wikipedia.org/wiki/Linux_kernel) [中文版WIKI](https://zh.wikipedia.org/wiki/Linux%E5%86%85%E6%A0%B8)
   - [The Linux Kernel Archives](https://www.kernel.org/)
   - [torvalds/linux: Linux kernel source tree](https://github.com/torvalds/linux)
   - [Linux Kernel Programming](https://www.tenlong.com.tw/products/9781789953435?list_name=srh)
- linux shell [英文版WIKI](https://en.wikipedia.org/wiki/Unix_shell) [中文版WIKI](https://zh.wikipedia.org/wiki/Unix_shell)
    - A Unix shell is a command-line interpreter or shell that provides a command line user interface for Unix-like operating systems. 
    - The shell is both an interactive command language and a scripting language, and is used by the operating system to control the execution of the system using shell scripts
    - 有許多shell: BASH(Bourne Again SHell) csh(The C shell)
    - 檢查你(使用者)登入時所用的shell
        - finger root 
    - [How to Change your Login Shell](https://gps.uml.edu/tutorials/unix-linux/unix/shell.htm#:~:text=To%20change%20your%20shell%20use,prompts%20for%20the%20new%20one.)
        - chsh
  - Linux commands
  - shell programming(Linux Shell Script)
    - 網站學習資源 [Shell 教程](https://www.runoob.com/linux/linux-shell.html)
    - 書[shell 腳本實戰](https://www.tenlong.com.tw/products/9787115506887?list_name=srh)
    - 教學影片[Shell Scripting Tutorial | Shell Scripting Crash Course | Linux Certification Training | Edureka](https://www.youtube.com/watch?v=GtovwKDemnI)
    - [簡明 Linux Shell Script 入門教學](https://blog.techbridge.cc/2019/11/15/linux-shell-script-tutorial/)
    - 簡單範例
```
gedit xxx.sh
chmod +755 xxx.sh
./xxx.sh 
```
```
# 宣告使用 /bin/bash
#!/bin/bash

echo "=== 將目前執行 process 的 PID 依照數字大小排序，取出前 10 名 === "

# ps 為列出 process 相關資訊，透過 | pipe 管線傳遞資料。
# awk 可以根據 pattern 進行資料處理（這邊印出第一欄 PID）
# sort 是進行排序，其排序時，預設都是把資料當作字串來排序
# 若想讓資料根據實際數值的大小來排序，可以加上 -n 參數。
# -r 則是由大到小排序，預設是由小到大
ps | awk '{print $1}' | sort -rn | head -10
```
## Windows Operating System
- Windows kernal
- Windows shell (Windows 有兩個命令行 shell：Command shell 和PowerShell)
  - cmd(Command shell)
  - [windows commands](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/windows-commands) 
  - 作業1: 20個 windows 指令(含網路指令 ping netstat ....)
  - 作業2: 開啟記事本(notepad.exe | calc.exe)  使用taskkill殺掉
     - [How To Kill A Process In Windows 11](https://www.c-sharpcorner.com/article/how-to-kill-a-process-in-windows-11/) 
  - 作業3: task manager 
      - netstat /?
      - netstat -ano
      - taskkill /PID 18354 /F 
   - powershell
     - powershel cmdlet 
       - 指令格式: 動詞-名詞 get-process 
     - powershell programming
       - 👍[PowerShell 使用者入門 powershell 101](https://learn.microsoft.com/zh-tw/powershell/scripting/learn/ps101/01-getting-started?view=powershell-7.2)
       - 👍[適用於系統管理的範例指令碼](https://learn.microsoft.com/zh-tw/powershell/scripting/samples/sample-scripts-for-administration?view=powershell-7.2)
       - [PowerShell Documentation](https://learn.microsoft.com/en-us/powershell/)
       - [PowerShell 流程自動化攻略](https://www.tenlong.com.tw/products/9789865026677?list_name=srh) 
 

### 經典教科書 [作業系統, 10/e (授權經銷版)(Silberschatz: Operating System Concepts, 10/e)](https://www.tenlong.com.tw/products/9789865522506?list_name=srh)
```
Part 1 總　論
CHAPTER 1　概　　說
CHAPTER 2　作業系統結構

Part 2 行程管理
CHAPTER 3　行程觀念
CHAPTER 4　執行緒與並行性
CHAPTER 5　CPU 排班

Part 3 行程同步
CHAPTER 6　同步工具
CHAPTER 7　同步範例
CHAPTER 8　死　結

Part 4 記憶體管理
CHAPTER 9　主記憶體
CHAPTER 10　虛擬記憶體

Part 5 儲存裝置
CHAPTER 11　大量儲存結構檔案系統
CHAPTER 12　輸入/輸出系統

Part 6 檔案系統
CHAPTER 13　案系統介面檔
CHAPTER 14　檔案系統的製作
CHAPTER 15　檔案系統內部

Part 7 安全與保護
CHAPTER 16　安　全
CHAPTER 17　保　護

Part ８ 進階主題
CHAPTER 18　虛擬機
CHAPTER 19　網路與分散式系統

Part 9 個案研究
CHAPTER 20　Linux 系統
CHAPTER 21　Windows 10
```
