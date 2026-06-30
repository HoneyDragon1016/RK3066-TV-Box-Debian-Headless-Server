# RK3066-TV-Box-Debian-Headless-Server
本專案紀錄如何將一台搭載 Rockchip RK3066 晶片的舊款 Android 電視盒，徹底閹割其表層 UI 系統，並透過 `chroot` 技術注入完整的 Debian 內核，將其打造成一台 24 小時不間斷運作、具備開機自啟動、遠端 SSH 穿隧與 PM2 行程守護的環境友善型微型伺服器。
