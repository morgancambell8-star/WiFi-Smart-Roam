# WiFi-Smart-Roam
magisk模块，双频WiFi6网络优化工具，支持三大功能：①双条件漫游（当前AP RSSI&lt;-65dBm且扫描到更好AP RSSI>-50dBm时触发重连）；②始终保持5GHz频段（仅在连接2.4GHz时触发检测，检测到同SSID下5GHz信号>-70dBm立即漫游切换）；③激进蜂窝切换策略（蜂窝RSRP>-85dBm即作为候选网络）。配合Magisk永久ROOT运行，开机自启。
