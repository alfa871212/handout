# 實現本地latex編譯以及VSCode編輯

由於Windows有字體問題，故採用虛擬機安裝Ubuntu20.04LTS，也方便日後與GitHub協作。

* Platform: Ubuntu20.04LTS (w/ VMWare) / MacOS (M1 capable)
* TexLive with XeLatex compiler
* Chinese Font (Founder) enabled
* git 簡單教學


## 簡易步驟
1. 於官網 [https://www.vmware.com/tw/products/workstation-player/workstation-player-evaluation.html](https://) 下載VMware Workstation Player(個人使用免費)，並安裝。
2. 下載Ubuntu20.04 LTS iso檔 [https://ubuntu.com/download/desktop](https://)，並用VMWare安裝虛擬機
3. 在虛擬機的Linux系統下載並安裝VScode
4. 在桌面按右鍵，打開終端機(Terminal)，輸入以下指令`sudo apt-get install git`
5. 在終端機輸入`git --help`，確認安裝
6. 在桌面按右鍵，打開終端機(Terminal)，輸入以下指令`sudo apt-get install texlive-full`（檔案較大，需要下載較久）
7. 在終端機輸入`xelatex --help`，確認安裝
8. 在終端機輸入`cd ~/Desktop/`，切換資料夾至桌面
9. 在終端機輸入`git clone https://github.com/alfa871212/hanout.git`，下載資料夾
10. 在終端機輸入`cd handout`，切換資料夾至handout
11. 在終端機輸入`code .`，打開VScode
12. 在VScode安裝latex插件，並利用README資料夾中的setting配置latex快捷鍵


