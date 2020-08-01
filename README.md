# cd khanhvn666-setup-vpn  
# 0)Cach cai : sudo sh vpnsetup.sh
# 1.1) gcloud config set project PROJECT-id
# 1.2) gcloud projects list
# 1.3) gcloud config list --format 'value(core.project)' 2>/dev/null
# 1.4) open port udp 500: gcloud compute firewall-rules create ipsec-vpn --allow udp:500
# 1.5) open port udp 4500: gcloud compute firewall-rules create ipsec-vpn2 --allow udp:4500
# 1.6) open port tcp 500: gcloud compute firewall-rules create ipsec-vpn3 --allow tcp:500
# Ref:  https://tinhte.vn/threads/cach-tao-vpn-tu-xai-1-minh-1-server-gia-chi-5-thang-free-2-thang-dau-dung-web-game-netflix.2601032/
