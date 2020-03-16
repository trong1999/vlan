## Bài toán
- Muốn tạo ra nhiều vlans trên một interface
- <img src="https://i.imgur.com/XT0vUwQ.png">
## Giải quyết bài toán
- Configure card mạng cần chia vlan
  + **/etc/sysconfig/network-scripts/ifcfg-ens37**
  + <img src="https://i.imgur.com/HgfGfeT.png">
  + **/etc/sysconfig/network-scripts/ifcfg-ens37.100**
  + <img src="https://i.imgur.com/6k1gGSc.png">
  + **/etc/sysconfig/network-scripts/ifcfg-ens37.200**
  + <img src="https://i.imgur.com/cPFeab0.png">
- Kiểm tra **ip a**
  + <img src="https://i.imgur.com/UWDO5Uc.png">
