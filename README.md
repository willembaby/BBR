# 安装（注意，过程中出现蓝屏选择时，按Tab键切换到No选项，再回车）
wget -N --no-check-certificate https://raw.githubusercontent.com/Ache1123/BBR/master/bbr.sh && chmod +x bbr.sh && bash bbr.sh
# 检查BBR运行状态
bash /root/bbr.sh status
# 控制，没有卸载选项。 (安装|启动|停止|检查状态)
bash /root/bbr.sh {install | start | stop | status }
