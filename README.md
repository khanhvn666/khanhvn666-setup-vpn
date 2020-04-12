# cd khanhvn666-setup-vpn  
# 0)Cach cai : sudo sh vpnsetup.sh
# 1) open port udp 500: gcloud compute firewall-rules create ipsec-vpn --allow udp:500
# 2) open port udp 4500: gcloud compute firewall-rules create ipsec-vpn2 --allow udp:4500
# 3) open port tcp 500: gcloud compute firewall-rules create ipsec-vpn3 --allow tcp:500
# Ref:  https://tinhte.vn/threads/cach-tao-vpn-tu-xai-1-minh-1-server-gia-chi-5-thang-free-2-thang-dau-dung-web-game-netflix.2601032/
