# ICND Internet Packet
IP

網路層定義了不同廣播區域間資料的傳送方式，需要的資訊包含：

(1) 發送端與接收端的邏輯位置（邏輯位置與LLC位址不同，前者為階層的國家/市區/巷弄/門號，後者為扁平的 MAC 特定位址），前者的邏輯位址獨立於後者的邏輯位址，利用邏輯定址，讓不同實體線材連結的設備可以相互連接。

(2) 途徑（從源頭到目的途經的任何區段）。

# IP 封包

              +-----------+--------------+-------------+------+
              | IP header | 發送端邏輯位址 | 接收端邏輯位址 | 資料 |
              +-----------+--------------+-------------+------+
                                               |
                                               |
                                               |
                                               V
                                               
                                               網段 與 節點
                                                 |     |
                                                 V     V
                                            192.168.100.21
                                            
                                            /* 網段即 Network Portion (網路中某區段)*/
                                            /* 節點即 Host Portion (該區段中某部主機或是網路設備)*/


# 階層形式的邏輯位址

* 網路段落

標明了整個網路架構中每一個區段，使 router 能自其中辨別路徑，並依此決定網何處傳送封包。

* 上述段落中的主機

指稱某一特定設備或是該設備上一連接埠 。


# 子網路遮罩



# 路由設備


# 網路層位址

此邏輯位址是利用階層的方式，逐一確認網路中的網段，進而確定其中的節點或是設備。
