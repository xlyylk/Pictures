mixed-port: 7890
allow-lan: false
mode: rule
log-level: warning
external-controller: 127.0.0.1:9090
unified-delay: true
global-client-fingerprint: chrome
keep-alive-interval: 360
clash-for-android:
  append-system-dns: false
cfw-bypass:
  - localhost
  - 127.*
  - 10.*
  - 172.16.*
  - 192.168.*
  - <local>
hosts:
  mtalk.google.com: 108.177.125.188
  paoluz.link: 104.21.71.42
dns:
  enable: true
  listen: 127.0.0.1:5335
  respect-rules: true
  default-nameserver: [119.29.29.29, 223.5.5.5]
  proxy-server-nameserver: [https://223.5.5.5/dns-query, https://doh.pub/dns-query]
  use-hosts: true
  use-system-hosts: true
  enhanced-mode: redir-host
  fake-ip-filter: ["*.market.xiaomi.com","*.n.n.srv.nintendo.net", +.stun.playstation.net, xbox.*.*.microsoft.com, "*.msftncsi.com", "*.msftconnecttest.com", WORKGROUP, "*.lan", stun.*.*.*, stun.*.*, time.windows.com, time.nist.gov, time.apple.com, time.asia.apple.com, "*.ntp.org.cn", "*.openwrt.pool.ntp.org", time1.cloud.tencent.com, time.ustc.edu.cn, pool.ntp.org, ntp.ubuntu.com, "*.*.xboxlive.com", speedtest.cros.wr.pvp.net, stun.services.mozilla1.com, ntp.nasa.gov]
  nameserver: [https://doh.pub/dns-query, https://223.5.5.5/dns-query]
  nameserver-policy:
    "geosite:bytedance":
        - 180.184.1.1
        - 180.184.2.2
    "geosite:cn,apple,category-games@cn":
        - 119.29.29.29
        - 223.6.6.6
        - system
    "geosite:private":
        - system
  fallback:
    - https://8.8.8.8/dns-query
    - https://1.1.1.1/dns-query
  fallback-filter:
    geosite:
      - category-porn
      - category-forums
      - category-cryptocurrency
    ipcidr:
      - 240.0.0.0/4
      - 116.89.243.0/24
proxies:
  - { name: '🇭🇰 D00 香港宽频1', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41275, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇭🇰 D00 香港宽频2', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41091, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇭🇰 D00 香港宽频3', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41493, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇭🇰 D01 香港边缘1', type: ss, server: shark.douyucdn.cn.o8268e691.ksyungslb.com.douyinvod.click, port: 41518, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇭🇰 D01 香港边缘2', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41318, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇭🇰 D01 香港边缘3', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41155, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇭🇰 D01 香港边缘4', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41415, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇹🇼 D10 台湾', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41403, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇹🇼 D11 台湾', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41401, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇹🇼 D12 台湾', type: ss, server: shark.douyucdn.cn.o8268e601.ksyungslb.com.douyinvod.click, port: 41402, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇹🇼 D13 台湾', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41400, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇹🇼 D14 台湾', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41404, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇹🇼 D15 台湾', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41406, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇯🇵 D20 日本边缘1', type: ss, server: shark.douyucdn.cn.o8268e691.ksyungslb.com.douyinvod.click, port: 41230, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇯🇵 D20 日本边缘2', type: ss, server: shark.douyucdn.cn.o8268e691.ksyungslb.com.douyinvod.click, port: 41424, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇯🇵 D20 日本边缘3', type: ss, server: shark.douyucdn.cn.o8268e691.ksyungslb.com.douyinvod.click, port: 41411, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇯🇵 D21 日本宽频 [3]', type: ss, server: shark.douyucdn.cn.o8268e691.ksyungslb.com.douyinvod.click, port: 41114, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇯🇵 D21 日本星链 [6]', type: ss, server: shark.douyucdn.cn.o8268e691.ksyungslb.com.douyinvod.click, port: 41192, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇸🇬 D30 新加坡', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41429, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇸🇬 D31 新加坡', type: ss, server: shark.douyucdn.cn.o8268e691.ksyungslb.com.douyinvod.click, port: 41413, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇸🇬 D33 新加坡', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41442, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇸🇬 D34 新加坡', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41393, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇺🇸 D40 美国', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41346, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇺🇸 D41 美国', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41367, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇺🇸 D42 美国', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41325, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇺🇸 D43 美国', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41375, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇻🇳 D5 越南宽频', type: ss, server: shark.douyucdn.cn.o8268e691.ksyungslb.com.douyinvod.click, port: 41407, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇰🇷 D5 韩国宽频', type: ss, server: shark.douyucdn.cn.o8268e691.ksyungslb.com.douyinvod.click, port: 41808, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇲🇾 D5 马来西亚边缘1', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41342, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇲🇾 D5 马来西亚边缘2', type: ss, server: shark.douyucdn.cn.o8268e629.ksyungslb.com.douyinvod.click, port: 41378, cipher: 2022-blake3-aes-256-gcm, password: HF9NE3VusuRnuhzMONb3+JR/4v5T5qaUdv1/fX0oWO4=:YzlhODllZGQtOWJlMi0zNTYwLTg3ZTQtMGYzZGQyZjI=, udp: true }
  - { name: '🇮🇱 H6 以色列', server: shark.douyucdn.cn.o8268e602.ksyungslb.com.douyinvod.click, port: 39810, type: ssr, cipher: chacha20-ietf, password: GhQrDS, protocol: auth_aes128_sha1, obfs: plain, protocol-param: 164032:luq2q6k8gg, obfs-param: bilivideo.com, udp: true }
  - { name: '🇷🇺 H6 俄罗斯 [0.5]', server: shark.douyucdn.cn.o8268e602.ksyungslb.com.douyinvod.click, port: 39149, type: ssr, cipher: chacha20-ietf, password: GhQrDS, protocol: auth_aes128_sha1, obfs: plain, protocol-param: 164032:luq2q6k8gg, obfs-param: bilivideo.com, udp: true }
  - { name: '🇿🇦 H6 南非', server: shark.douyucdn.cn.o8268e602.ksyungslb.com.douyinvod.click, port: 39818, type: ssr, cipher: chacha20-ietf, password: GhQrDS, protocol: auth_aes128_sha1, obfs: plain, protocol-param: 164032:luq2q6k8gg, obfs-param: bilivideo.com, udp: true }
  - { name: '🇱🇺 H6 卢森堡', server: shark.douyucdn.cn.o8268e602.ksyungslb.com.douyinvod.click, port: 39479, type: ssr, cipher: chacha20-ietf, password: GhQrDS, protocol: auth_aes128_sha1, obfs: plain, protocol-param: 164032:luq2q6k8gg, obfs-param: bilivideo.com, udp: true }
  - { name: '🇮🇩 H6 印尼', server: shark.douyucdn.cn.o8268e602.ksyungslb.com.douyinvod.click, port: 39443, type: ssr, cipher: chacha20-ietf, password: GhQrDS, protocol: auth_aes128_sha1, obfs: plain, protocol-param: 164032:luq2q6k8gg, obfs-param: bilivideo.com, udp: true }
  - { name: '🇮🇳 H6 印度', server: shark.douyucdn.cn.o8268e602.ksyungslb.com.douyinvod.click, port: 39824, type: ssr, cipher: chacha20-ietf, password: GhQrDS, protocol: auth_aes128_sha1, obfs: plain, protocol-param: 164032:luq2q6k8gg, obfs-param: bilivideo.com, udp: true }
  - { name: '🇹🇷 H6 土耳其 [8]', server: shark.douyucdn.cn.o8268e602.ksyungslb.com.douyinvod.click, port: 39814, type: ssr, cipher: chacha20-ietf, password: GhQrDS, protocol: auth_aes128_sha1, obfs: plain, protocol-param: 164032:luq2q6k8gg, obfs-param: bilivideo.com, udp: true }
  - { name: '🇳🇬 H6 尼日利亚 [8]', server: shark.douyucdn.cn.o8268e602.ksyungslb.com.douyinvod.click, port: 39850, type: ssr, cipher: chacha20-ietf, password: GhQrDS, protocol: auth_aes128_sha1, obfs: plain, protocol-param: 164032:luq2q6k8gg, obfs-param: bilivideo.com, udp: true }
  - { name: '🇩🇪 H6 德国', server: shark.douyucdn.cn.o8268e602.ksyungslb.com.douyinvod.click, port: 39823, type: ssr, cipher: chacha20-ietf, password: GhQrDS, protocol: auth_aes128_sha1, obfs: plain, protocol-param: 164032:luq2q6k8gg, obfs-param: bilivideo.com, udp: true }
  - { name: '🇲🇩 H6 摩尔多瓦', server: shark.douyucdn.cn.o8268e602.ksyungslb.com.douyinvod.click, port: 39817, type: ssr, cipher: chacha20-ietf, password: GhQrDS, protocol: auth_aes128_sha1, obfs: plain, protocol-param: 164032:luq2q6k8gg, obfs-param: bilivideo.com, udp: true }
  - { name: '🇹🇭 H6 泰国', server: shark.douyucdn.cn.o8268e602.ksyungslb.com.douyinvod.click, port: 39803, type: ssr, cipher: chacha20-ietf, password: GhQrDS, protocol: auth_aes128_sha1, obfs: plain, protocol-param: 164032:luq2q6k8gg, obfs-param: bilivideo.com, udp: true }
  - { name: '🇦🇺 H6 澳大利亚', server: shark.douyucdn.cn.o8268e691.ksyungslb.com.douyinvod.click, port: 39412, type: ssr, cipher: chacha20-ietf, password: GhQrDS, protocol: auth_aes128_sha1, obfs: plain, protocol-param: 164032:luq2q6k8gg, obfs-param: bilivideo.com, udp: true }
  - { name: '🇮🇪 H6 爱尔兰', server: shark.douyucdn.cn.o8268e602.ksyungslb.com.douyinvod.click, port: 39472, type: ssr, cipher: chacha20-ietf, password: GhQrDS, protocol: auth_aes128_sha1, obfs: plain, protocol-param: 164032:luq2q6k8gg, obfs-param: bilivideo.com, udp: true }
  - { name: '🇫🇮 H6 芬兰', server: shark.douyucdn.cn.o8268e602.ksyungslb.com.douyinvod.click, port: 39828, type: ssr, cipher: chacha20-ietf, password: GhQrDS, protocol: auth_aes128_sha1, obfs: plain, protocol-param: 164032:luq2q6k8gg, obfs-param: bilivideo.com, udp: true }
  - { name: '🇬🇧 H6 英国 [3]', server: shark.douyucdn.cn.o8268e602.ksyungslb.com.douyinvod.click, port: 39322, type: ssr, cipher: chacha20-ietf, password: GhQrDS, protocol: auth_aes128_sha1, obfs: plain, protocol-param: 164032:luq2q6k8gg, obfs-param: bilivideo.com, udp: true }
  - { name: '🇳🇱 H6 荷兰', server: shark.douyucdn.cn.o8268e602.ksyungslb.com.douyinvod.click, port: 39802, type: ssr, cipher: chacha20-ietf, password: GhQrDS, protocol: auth_aes128_sha1, obfs: plain, protocol-param: 164032:luq2q6k8gg, obfs-param: bilivideo.com, udp: true }
  - { name: '🇵🇭 H6 菲律宾 [5]', server: shark.douyucdn.cn.o8268e602.ksyungslb.com.douyinvod.click, port: 39812, type: ssr, cipher: chacha20-ietf, password: GhQrDS, protocol: auth_aes128_sha1, obfs: plain, protocol-param: 164032:luq2q6k8gg, obfs-param: bilivideo.com, udp: true }
  - { name: '🇦🇷 H6 阿根廷 [2]', server: shark.douyucdn.cn.o8268e602.ksyungslb.com.douyinvod.click, port: 39813, type: ssr, cipher: chacha20-ietf, password: GhQrDS, protocol: auth_aes128_sha1, obfs: plain, protocol-param: 164032:luq2q6k8gg, obfs-param: bilivideo.com, udp: true }
  - { name: '🇹🇼 Y1 台湾 [0.2]', server: dy-tw-05.ksyungslb.lol, port: 486, udp: true, skip-cert-verify: true, sni: api3-eeft-gateway-hl.feishu.cn, type: hysteria2, password: luq2q6k8gg164032 }
  - { name: '🇹🇼 Y2 台湾 [0.2]', server: tw04-o1.oiiaicat.me, port: 486, udp: true, skip-cert-verify: true, sni: api3-eeft-gateway-hl.feishu.cn, type: hysteria2, password: luq2q6k8gg164032 }
  - { name: '🇹🇼 V5 台湾 [0.1]', type: vless, server: dy-tw-07.ksyungslb.lol, port: 1443, uuid: c9a89edd-9be2-3560-87e4-0f3dd2f24733, pbk: h6gA4e9TDf55_R3CEGAmyLbVGNqLfERt5wea2DFw7Wc, udp: true, tls: true, skip-cert-verify: false, sni: react.dev, flow: xtls-rprx-vision, client-fingerprint: ios, servername: react.dev, reality-opts: { public-key: h6gA4e9TDf55_R3CEGAmyLbVGNqLfERt5wea2DFw7Wc, short-id: bb44791d } }
  - { name: '🇹🇼 V8 台灣 [0.1]', type: vless, server: dy-tw-06.ksyungslb.lol, port: 8443, uuid: c9a89edd-9be2-3560-87e4-0f3dd2f24733, pbk: h6gA4e9TDf55_R3CEGAmyLbVGNqLfERt5wea2DFw7Wc, udp: true, tls: true, skip-cert-verify: false, sni: osxapps.itunes.apple.com, flow: xtls-rprx-vision, client-fingerprint: ios, servername: osxapps.itunes.apple.com, reality-opts: { public-key: h6gA4e9TDf55_R3CEGAmyLbVGNqLfERt5wea2DFw7Wc, short-id: bb44791d } }
  - { name: '🇹🇼 V7 台灣 [0.1]', type: vless, server: tw05-o1.oiiaicat.me, port: 7826, uuid: c9a89edd-9be2-3560-87e4-0f3dd2f24733, pbk: h6gA4e9TDf55_R3CEGAmyLbVGNqLfERt5wea2DFw7Wc, udp: true, tls: true, skip-cert-verify: false, sni: broadcast.chat.bilibili.com, flow: xtls-rprx-vision, client-fingerprint: edge, servername: broadcast.chat.bilibili.com, reality-opts: { public-key: h6gA4e9TDf55_R3CEGAmyLbVGNqLfERt5wea2DFw7Wc, short-id: bb44791d } }
  - { name: '🇹🇼 V1 台灣 [0.1]', type: vless, server: tw04-o1.oiiaicat.me, port: 1443, uuid: c9a89edd-9be2-3560-87e4-0f3dd2f24733, pbk: h6gA4e9TDf55_R3CEGAmyLbVGNqLfERt5wea2DFw7Wc, udp: true, tls: true, skip-cert-verify: false, sni: react.dev, flow: xtls-rprx-vision, client-fingerprint: ios, servername: react.dev, reality-opts: { public-key: h6gA4e9TDf55_R3CEGAmyLbVGNqLfERt5wea2DFw7Wc, short-id: bb44791d } }

proxy-groups:
  - name: 🚀 节点代理
    type: select
    proxies:
      - ♻️ 自动选择
      - 🇭🇰 D00 香港宽频1
      - 🇭🇰 D00 香港宽频2
      - 🇭🇰 D00 香港宽频3
      - 🇭🇰 D01 香港边缘1
      - 🇭🇰 D01 香港边缘2
      - 🇭🇰 D01 香港边缘3
      - 🇭🇰 D01 香港边缘4
      - 🇹🇼 D10 台湾
      - 🇹🇼 D11 台湾
      - 🇹🇼 D12 台湾
      - 🇹🇼 D13 台湾
      - 🇹🇼 D14 台湾
      - 🇹🇼 D15 台湾
      - 🇯🇵 D20 日本边缘1
      - 🇯🇵 D20 日本边缘2
      - 🇯🇵 D20 日本边缘3
      - 🇯🇵 D21 日本宽频 [3]
      - 🇯🇵 D21 日本星链 [6]
      - 🇸🇬 D30 新加坡
      - 🇸🇬 D31 新加坡
      - 🇸🇬 D33 新加坡
      - 🇸🇬 D34 新加坡
      - 🇺🇸 D40 美国
      - 🇺🇸 D41 美国
      - 🇺🇸 D42 美国
      - 🇺🇸 D43 美国
      - 🇻🇳 D5 越南宽频
      - 🇰🇷 D5 韩国宽频
      - 🇲🇾 D5 马来西亚边缘1
      - 🇲🇾 D5 马来西亚边缘2
      - 🇮🇱 H6 以色列
      - 🇷🇺 H6 俄罗斯 [0.5]
      - 🇿🇦 H6 南非
      - 🇱🇺 H6 卢森堡
      - 🇮🇩 H6 印尼
      - 🇮🇳 H6 印度
      - 🇹🇷 H6 土耳其 [8]
      - 🇳🇬 H6 尼日利亚 [8]
      - 🇩🇪 H6 德国
      - 🇲🇩 H6 摩尔多瓦
      - 🇹🇭 H6 泰国
      - 🇦🇺 H6 澳大利亚
      - 🇮🇪 H6 爱尔兰
      - 🇫🇮 H6 芬兰
      - 🇬🇧 H6 英国 [3]
      - 🇳🇱 H6 荷兰
      - 🇵🇭 H6 菲律宾 [5]
      - 🇦🇷 H6 阿根廷 [2]
      - 🇹🇼 Y1 台湾 [0.2]
      - 🇹🇼 Y2 台湾 [0.2]
      - 🇹🇼 V5 台湾 [0.1]
      - 🇹🇼 V8 台灣 [0.1]
      - 🇹🇼 V7 台灣 [0.1]
      - 🇹🇼 V1 台灣 [0.1]
      - DIRECT
  - name: 🌍 国外媒体
    type: select
    proxies:
      - 🚀 节点代理
      - 🎯 绕过代理
      - 🇭🇰 D00 香港宽频1
      - 🇭🇰 D00 香港宽频2
      - 🇭🇰 D00 香港宽频3
      - 🇭🇰 D01 香港边缘1
      - 🇭🇰 D01 香港边缘2
      - 🇭🇰 D01 香港边缘3
      - 🇭🇰 D01 香港边缘4
      - 🇹🇼 D10 台湾
      - 🇹🇼 D11 台湾
      - 🇹🇼 D12 台湾
      - 🇹🇼 D13 台湾
      - 🇹🇼 D14 台湾
      - 🇹🇼 D15 台湾
      - 🇯🇵 D20 日本边缘1
      - 🇯🇵 D20 日本边缘2
      - 🇯🇵 D20 日本边缘3
      - 🇯🇵 D21 日本宽频 [3]
      - 🇯🇵 D21 日本星链 [6]
      - 🇸🇬 D30 新加坡
      - 🇸🇬 D31 新加坡
      - 🇸🇬 D33 新加坡
      - 🇸🇬 D34 新加坡
      - 🇺🇸 D40 美国
      - 🇺🇸 D41 美国
      - 🇺🇸 D42 美国
      - 🇺🇸 D43 美国
      - 🇻🇳 D5 越南宽频
      - 🇰🇷 D5 韩国宽频
      - 🇲🇾 D5 马来西亚边缘1
      - 🇲🇾 D5 马来西亚边缘2
      - 🇮🇱 H6 以色列
      - 🇷🇺 H6 俄罗斯 [0.5]
      - 🇿🇦 H6 南非
      - 🇱🇺 H6 卢森堡
      - 🇮🇩 H6 印尼
      - 🇮🇳 H6 印度
      - 🇹🇷 H6 土耳其 [8]
      - 🇳🇬 H6 尼日利亚 [8]
      - 🇩🇪 H6 德国
      - 🇲🇩 H6 摩尔多瓦
      - 🇹🇭 H6 泰国
      - 🇦🇺 H6 澳大利亚
      - 🇮🇪 H6 爱尔兰
      - 🇫🇮 H6 芬兰
      - 🇬🇧 H6 英国 [3]
      - 🇳🇱 H6 荷兰
      - 🇵🇭 H6 菲律宾 [5]
      - 🇦🇷 H6 阿根廷 [2]
      - 🇹🇼 Y1 台湾 [0.2]
      - 🇹🇼 Y2 台湾 [0.2]
      - 🇹🇼 V5 台湾 [0.1]
      - 🇹🇼 V8 台灣 [0.1]
      - 🇹🇼 V7 台灣 [0.1]
      - 🇹🇼 V1 台灣 [0.1]
  - name: 📲 电报信息
    type: select
    proxies:
      - 🚀 节点代理
      - 🎯 绕过代理
      - 🇭🇰 D00 香港宽频1
      - 🇭🇰 D00 香港宽频2
      - 🇭🇰 D00 香港宽频3
      - 🇭🇰 D01 香港边缘1
      - 🇭🇰 D01 香港边缘2
      - 🇭🇰 D01 香港边缘3
      - 🇭🇰 D01 香港边缘4
      - 🇹🇼 D10 台湾
      - 🇹🇼 D11 台湾
      - 🇹🇼 D12 台湾
      - 🇹🇼 D13 台湾
      - 🇹🇼 D14 台湾
      - 🇹🇼 D15 台湾
      - 🇯🇵 D20 日本边缘1
      - 🇯🇵 D20 日本边缘2
      - 🇯🇵 D20 日本边缘3
      - 🇯🇵 D21 日本宽频 [3]
      - 🇯🇵 D21 日本星链 [6]
      - 🇸🇬 D30 新加坡
      - 🇸🇬 D31 新加坡
      - 🇸🇬 D33 新加坡
      - 🇸🇬 D34 新加坡
      - 🇺🇸 D40 美国
      - 🇺🇸 D41 美国
      - 🇺🇸 D42 美国
      - 🇺🇸 D43 美国
      - 🇻🇳 D5 越南宽频
      - 🇰🇷 D5 韩国宽频
      - 🇲🇾 D5 马来西亚边缘1
      - 🇲🇾 D5 马来西亚边缘2
      - 🇮🇱 H6 以色列
      - 🇷🇺 H6 俄罗斯