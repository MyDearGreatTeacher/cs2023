## Operating System (OS)
- user mode vs Kernel Mode
  - [Kernel Mode 與 User Mode 的概念](https://medicineyeh.wordpress.com/2015/02/10/kernel-mode-%E8%88%87-user-mode-%E7%9A%84%E6%A6%82%E5%BF%B5/)
- kernal vs shell
  - [kernal](https://en.wikipedia.org/wiki/Kernel_(operating_system)#:~:text=The%20kernel%20is%20a%20computer,between%20hardware%20and%20software%20components.)
  - [核心（Kernel|內核）](https://zh.wikipedia.org/wiki/%E5%86%85%E6%A0%B8)
    - 核心在計算機科學中是一個用來管理軟體發出的資料I/O（輸入與輸出）要求的電腦程式，將這些要求轉譯為資料處理的指令並交由`中央處理器（CPU）`及電腦中其他電子元件進行處理，是現代作業系統中最基本的部分
    - 核心是為眾多應用程式提供對電腦硬體的安全存取的一部分軟體，這種存取是有限的，並由核心決定一個程式在什麼時候對某部分硬體操作多長時間。
    - 直接對硬體操作是非常複雜的。所以核心通常提供一種硬體抽象的方法，來完成這些操作。有了這個，通過行程間通訊機制及系統呼叫，應用行程可間接控制所需的硬體資源（特別是處理器及IO裝置）。
  - linux 
    - linux kernal
      - [The Linux Kernel Archives](https://www.kernel.org/)
      - [torvalds/linux: Linux kernel source tree](https://github.com/torvalds/linux)
      - [Linux Kernel Programming](https://www.tenlong.com.tw/products/9781789953435?list_name=srh)
    - linux shell
    -  
  - Windows
    - Windows kernal
    - Windows shell (Windows 有兩個命令行 shell：Command shell 和PowerShell)
      - cmd(Command shell)
        - [windows commands](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/windows-commands) 
          - 作業1: 20個 windows 指令(含網路指令 ping netstat ....)
          - 作業2: 開啟記事本(notepad.exe | calc.exe)  使用taskkill殺掉
          - 作業3: task manager 
          - netstat /?
          - netstat -ano
          - taskkill /PID 18354 /F 
        - powershell
          - powershel cmdlet 
            - get-process  動詞-名詞
          - powershell programming
            - 👍[PowerShell 使用者入門 powershell 101](https://learn.microsoft.com/zh-tw/powershell/scripting/learn/ps101/01-getting-started?view=powershell-7.2)
            - 👍[適用於系統管理的範例指令碼](https://learn.microsoft.com/zh-tw/powershell/scripting/samples/sample-scripts-for-administration?view=powershell-7.2)
            - [PowerShell Documentation](https://learn.microsoft.com/en-us/powershell/)
            - [PowerShell 流程自動化攻略](https://www.tenlong.com.tw/products/9789865026677?list_name=srh) 
## Windows Operating System 
- Windows shell ==> 
  - cmd
  - powershell

## Linux Operating System 

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
