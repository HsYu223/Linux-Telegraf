# Linux-Telegraf
Linux Telegraf 監控VMWare虛擬叢集主機資源

# 下載rpm

https://dl.influxdata.com/telegraf/releases/telegraf-1.28.5-1.x86_64.rpm

# 在檔案的路徑下下指令選擇本地壓縮檔解壓縮安裝

sudo yum localinstall telegraf-1.28.5-1.x86_64.rpm

# 修改config

vim /etc/telegraf/telegraf.conf

# 啟動服務

systemctl start telegraf

# 設定自動啟動

systemctl enable telegraf

# 查看服務有沒有啟動

systemctl status telegraf

# 停止服務

systemctl stop telegraf

# 重新啟動

systemctl restart telegraf

