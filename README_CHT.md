# UC2鍵盤(Universal-Century 2)

![UC2](https://i.imgur.com/sl2A7q3.jpeg)

UC2鍵盤(Universal-Century 2) 是左右分離式鍵盤，有86顆鍵，有完整的F鍵區，為TKL尺寸的鍵盤，單面包含了3顆拇指鍵與編碼器。

UC2鍵盤的Layout配置，是由 Willow Layout (v 1.0) 發展而來，該Layout由 [Hanachi-ap](https://github.com/hanachi-ap) 開發，並使用CC BY-SA 4.0發布。

UC2 Layout也是依照CC BY-SA 4.0規範發布，並由 [AndyChiu](https://github.com/AndyChiu) 維護。

非常感謝 Hanachi 先生的自由發佈精神!

![FDM PCB Board](https://imgur.com/Obr9v1y.jpeg)

PCB的部分，採用FDM方式的3D印表機列印，線路採用CAT5或者CAT6的網路線內芯並且手動拉線，而非工廠製作的PCB。
Layout設計採用[Keyboard-layout-editor.com (KLE)](http://www.keyboard-layout-editor.com/) 網頁程式處理，列印的3D檔案(.STL)是由 [hotswap_pcb_generator](https://github.com/AndyChiu/hotswap_pcb_generator) OpenSCAD 腳本程式來處理。

* OpenSCAD 檔案 : [SCAD](https://github.com/AndyChiu/UC2/tree/main/SCAD)
* 3D 檔案 : [STLs](https://github.com/AndyChiu/UC2/tree/main/STLs)
* 製作指南: [中文](https://ie321mx.blogspot.com/2021/09/choc-v2.html)
* Layout 與 key matrix 說明文件 : [PDF](https://github.com/AndyChiu/UC2/tree/main/PDF)
* QMK Firmware : [UC2](https://github.com/AndyChiu/qmk_firmware/tree/uc2_kb/keyboards/handwired/uc2) 

強烈建議使用 [REMAP](https://remap-keys.app) 來設定鍵盤，可以透過 VIA 技術來設定個別按鍵功能，且支援網頁燒錄韌體至MCU，可由此開啟頁面 [UC2 firmware](https://remap-keys.app/catalog/bwCYjD27IZM8dbOddvCt/firmware) 進行燒錄!

![Left Hand](https://i.imgur.com/FnKEIS4.jpeg)
![Right Hand](https://i.imgur.com/pPTj6vC.jpeg)
