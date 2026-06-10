mixed-port: 7890
allow-lan: true
mode: rule
log-level: info
ipv6: true
external-controller: 127.0.0.1:9090
dns:
  enable: true
  listen: 0.0.0.0:1053
  ipv6: true
  enhanced-mode: fake-ip
  fake-ip-range: 198.18.0.1/16
  default-nameserver:
    - 223.5.5.5
    - 119.29.29.29
  nameserver:
    - https://dns.alidns.com/dns-query
    - https://doh.pub/dns-query
proxies:
  - name: 🇭🇰 香港｜Hong Kong 01
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 29945
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇭🇰 香港｜Hong Kong 02
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 29946
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇭🇰 香港｜Hong Kong 03
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 29951
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇭🇰 香港｜Hong Kong 04
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 29947
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇭🇰 香港｜Hong Kong 05
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 29948
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇭🇰 香港｜Hong Kong 06
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 52094
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇭🇰 香港｜Hong Kong 07
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 51977
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇭🇰 香港｜Hong Kong 08
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 10159
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇭🇰 香港｜Hong Kong 09
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 22846
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇭🇰 香港｜Hong Kong 10
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 24316
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇯🇵 日本｜Japan 01
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 47398
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇯🇵 日本｜Japan 02
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 27367
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇯🇵 日本｜Japan 03
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 52414
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇯🇵 日本｜Japan 04
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 16636
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇯🇵 日本｜Japan Res 01
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 51961
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇯🇵 日本｜Japan Res 02
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 55305
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇯🇵 日本｜Japan Res 03
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 58736
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇯🇵 日本｜Japan Res 04
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 38635
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇯🇵 日本｜Japan Dir 01
    type: vless
    server: jpsoftbank.sytes.net
    port: 7779
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇯🇵 日本｜Japan Dir 02
    type: vless
    server: nyh20.xzcloudnode.sbs
    port: 7789
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇯🇵 日本｜Japan Dir 03
    type: vless
    server: jpsoftbank.sytes.net
    port: 7799
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇯🇵 日本｜Japan Dir 04
    type: vless
    server: nyh20.xzcloudnode.sbs
    port: 7800
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇨🇳 台湾｜Taiwan 01
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 10038
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇨🇳 台湾｜Taiwan 02
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 10039
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇨🇳 台湾｜Taiwan 03
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 10040
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇨🇳 台湾｜Taiwan 04
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 10041
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇨🇳 台湾｜Taiwan ISP 05
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 18048
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇨🇳 台湾｜Taiwan ISP 06
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 39763
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇨🇳 台湾｜Taiwan ISP 07
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 41205
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇨🇳 台湾｜Taiwan ISP 08
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 43420
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇺🇸 美国｜USA Prime 01
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 32375
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇺🇸 美国｜USA Prime 02
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 32376
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇺🇸 美国｜USA Prime 03
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 32377
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇺🇸 美国｜USA Prime 04
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 32378
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇺🇸 美国｜USA Prime 05
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 27899
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇺🇸 美国｜USA Prime 06
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 45381
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇺🇸 美国｜USA Prime 07 x 0.2
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 37538
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇺🇸 美国｜USA Prime 08 x 0.2
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 21839
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇸🇬 新加坡｜Singapore 01
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 27851
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇸🇬 新加坡｜Singapore 02
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 27852
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇸🇬 新加坡｜Singapore 03
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 27853
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇸🇬 新加坡｜Singapore 04
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 27854
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇸🇬 新加坡｜Singapore 05
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 50455
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇸🇬 新加坡｜Singapore 06
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 44830
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇸🇬 新加坡｜Singapore 07
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 37824
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇸🇬 新加坡｜Singapore 08
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 31286
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇰🇷 韩国｜Korea 01
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 20289
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇰🇷 韩国｜Korea 02
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 33815
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇰🇷 韩国｜Korea 03
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 27734
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇰🇷 韩国｜Korea 04
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 22227
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇲🇾 马来西亚｜Malaysia 01
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 16430
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇲🇾 马来西亚｜Malaysia 02
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 55983
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇲🇾 马来西亚｜Malaysia 03
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 58895
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇲🇾 马来西亚｜Malaysia 04
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 32820
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇹🇭 泰国｜Thailand 01
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 40856
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇹🇭 泰国｜Thailand 02
    type: vless
    server: 6sttaqn48k8io46motir.beupisp.com
    port: 41479
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇹🇭 泰国｜Thailand 03
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 32790
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇹🇭 泰国｜Thailand 04
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 35624
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇻🇳 越南｜Vietnam 01
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 22268
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇻🇳 越南｜Vietnam 02
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 51542
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇻🇳 越南｜Vietnam 03
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 32388
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇻🇳 越南｜Vietnam 04
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 44560
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇲🇴 澳门｜Macau 01
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 50281
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇲🇴 澳门｜Macau 02
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 10447
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇲🇴 澳门｜Macau 03
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 14461
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇲🇴 澳门｜Macau 04
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 23248
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇵🇭 菲律宾｜Philippines 01
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 20038
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇵🇭 菲律宾｜Philippines 02
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 51048
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇵🇭 菲律宾｜Philippines 03
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 57598
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇵🇭 菲律宾｜Philippines 04
    type: vless
    server: 6sttaqn50k8io46motir.beupisp.com
    port: 34436
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇦🇺 悉尼｜Sydney
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 28242
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇦🇺 墨尔本｜Melbourne
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 10759
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇮🇳 印度｜India 01
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 27389
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇮🇳 印度｜India 02
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 10545
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇦🇪 迪拜｜Dubai
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 11749
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇮🇩 印尼｜Indonesia
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 18752
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇧🇷 巴西｜Brazil 01
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 39834
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇧🇷 巴西｜Brazil 02
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 48707
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇬🇧 英国｜United Kingdom
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 18483
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇫🇷 法国｜France
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 42630
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇩🇪 德国｜Germany
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 10031
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇷🇺 俄罗斯｜Russia
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 40066
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇦🇷 阿根廷｜Argentina
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 41314
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇲🇽 墨西哥｜Mexico 01
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 34860
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇲🇽 墨西哥｜Mexico 02
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 44051
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇨🇦 加拿大｜Canada
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 49308
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇨🇦 多伦多｜Canada
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 11531
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇮🇱 以色列｜Israel
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 42154
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇪🇸 西班牙｜Spain
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 11854
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇧🇪 比利时｜Belgium
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 55192
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇮🇹 意大利｜Italy
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 12238
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇦🇹 奥地利｜Austria
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 23831
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇭🇺 匈牙利｜Hungary
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 15019
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇲🇰 马其顿｜Macedonia
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 51007
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇱🇹 立陶宛｜Lithuania
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 44073
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇹🇷 土耳其｜Turkey
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 51064
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇨🇭 瑞士｜Switzerland
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 41826
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇸🇦 沙特｜Saudi Arabia
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 22925
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇳🇱 荷兰｜Netherlands
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 44116
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇨🇱 智利｜Chile 01
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 16615
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇨🇱 智利｜Chile 02
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 17979
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇨🇿 捷克｜Czech
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 17371
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇸🇪 瑞典｜Sweden
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 52438
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇿🇦 南非｜South Africa
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 12949
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇩🇰 丹麦｜Denmark
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 57791
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇹🇬 多哥｜Togo
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 10304
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇪🇬 埃及｜Egypt
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 64361
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇮🇸 冰岛｜Iceland
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 59289
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇳🇴 挪威｜Norway
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 17374
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇲🇦 卡萨布兰卡｜Morocco
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 15116
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇦🇿 阿塞拜疆｜Azerbaijan
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 16513
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇷🇴 罗马尼亚｜Romania
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 31120
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.microsoft.com
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇳🇬 尼日利亚｜Nigeria
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 25488
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇨🇴 哥伦比亚｜Colombia
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 10990
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇰🇿 哈萨克斯坦｜Kazakhstan
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 35752
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
  - name: 🇰🇬 吉尔吉斯斯坦｜Kyrgyzstan
    type: vless
    server: 6sttaqn47k8io46motir.beupisp.com
    port: 10056
    uuid: bf4aa4ec-902b-4338-b4d6-978b6ddc664c
    servername: www.python.org
    tls: true
    flow: xtls-rprx-vision
    client-fingerprint: chrome
    reality-opts:
      public-key: OgbAhQpciw6lM7etNl0Z6gPfJ7l0p_Oq8FGv2nDamh4
      short-id: 8d26d7af
    skip-cert-verify: true
    udp: true
proxy-groups:
  - name: 🚀 节点选择
    type: select
    proxies:
      - ♻️ 自动选择
      - DIRECT
      - 🇭🇰 香港｜Hong Kong 01
      - 🇭🇰 香港｜Hong Kong 02
      - 🇭🇰 香港｜Hong Kong 03
      - 🇭🇰 香港｜Hong Kong 04
      - 🇭🇰 香港｜Hong Kong 05
      - 🇭🇰 香港｜Hong Kong 06
      - 🇭🇰 香港｜Hong Kong 07
      - 🇭🇰 香港｜Hong Kong 08
      - 🇭🇰 香港｜Hong Kong 09
      - 🇭🇰 香港｜Hong Kong 10
      - 🇯🇵 日本｜Japan 01
      - 🇯🇵 日本｜Japan 02
      - 🇯🇵 日本｜Japan 03
      - 🇯🇵 日本｜Japan 04
      - 🇯🇵 日本｜Japan Res 01
      - 🇯🇵 日本｜Japan Res 02
      - 🇯🇵 日本｜Japan Res 03
      - 🇯🇵 日本｜Japan Res 04
      - 🇯🇵 日本｜Japan Dir 01
      - 🇯🇵 日本｜Japan Dir 02
      - 🇯🇵 日本｜Japan Dir 03
      - 🇯🇵 日本｜Japan Dir 04
      - 🇨🇳 台湾｜Taiwan 01
      - 🇨🇳 台湾｜Taiwan 02
      - 🇨🇳 台湾｜Taiwan 03
      - 🇨🇳 台湾｜Taiwan 04
      - 🇨🇳 台湾｜Taiwan ISP 05
      - 🇨🇳 台湾｜Taiwan ISP 06
      - 🇨🇳 台湾｜Taiwan ISP 07
      - 🇨🇳 台湾｜Taiwan ISP 08
      - 🇺🇸 美国｜USA Prime 01
      - 🇺🇸 美国｜USA Prime 02
      - 🇺🇸 美国｜USA Prime 03
      - 🇺🇸 美国｜USA Prime 04
      - 🇺🇸 美国｜USA Prime 05
      - 🇺🇸 美国｜USA Prime 06
      - 🇺🇸 美国｜USA Prime 07 x 0.2
      - 🇺🇸 美国｜USA Prime 08 x 0.2
      - 🇸🇬 新加坡｜Singapore 01
      - 🇸🇬 新加坡｜Singapore 02
      - 🇸🇬 新加坡｜Singapore 03
      - 🇸🇬 新加坡｜Singapore 04
      - 🇸🇬 新加坡｜Singapore 05
      - 🇸🇬 新加坡｜Singapore 06
      - 🇸🇬 新加坡｜Singapore 07
      - 🇸🇬 新加坡｜Singapore 08
      - 🇰🇷 韩国｜Korea 01
      - 🇰🇷 韩国｜Korea 02
      - 🇰🇷 韩国｜Korea 03
      - 🇰🇷 韩国｜Korea 04
      - 🇲🇾 马来西亚｜Malaysia 01
      - 🇲🇾 马来西亚｜Malaysia 02
      - 🇲🇾 马来西亚｜Malaysia 03
      - 🇲🇾 马来西亚｜Malaysia 04
      - 🇹🇭 泰国｜Thailand 01
      - 🇹🇭 泰国｜Thailand 02
      - 🇹🇭 泰国｜Thailand 03
      - 🇹🇭 泰国｜Thailand 04
      - 🇻🇳 越南｜Vietnam 01
      - 🇻🇳 越南｜Vietnam 02
      - 🇻🇳 越南｜Vietnam 03
      - 🇻🇳 越南｜Vietnam 04
      - 🇲🇴 澳门｜Macau 01
      - 🇲🇴 澳门｜Macau 02
      - 🇲🇴 澳门｜Macau 03
      - 🇲🇴 澳门｜Macau 04
      - 🇵🇭 菲律宾｜Philippines 01
      - 🇵🇭 菲律宾｜Philippines 02
      - 🇵🇭 菲律宾｜Philippines 03
      - 🇵🇭 菲律宾｜Philippines 04
      - 🇦🇺 悉尼｜Sydney
      - 🇦🇺 墨尔本｜Melbourne
      - 🇮🇳 印度｜India 01
      - 🇮🇳 印度｜India 02
      - 🇦🇪 迪拜｜Dubai
      - 🇮🇩 印尼｜Indonesia
      - 🇧🇷 巴西｜Brazil 01
      - 🇧🇷 巴西｜Brazil 02
      - 🇬🇧 英国｜United Kingdom
      - 🇫🇷 法国｜France
      - 🇩🇪 德国｜Germany
      - 🇷🇺 俄罗斯｜Russia
      - 🇦🇷 阿根廷｜Argentina
      - 🇲🇽 墨西哥｜Mexico 01
      - 🇲🇽 墨西哥｜Mexico 02
      - 🇨🇦 加拿大｜Canada
      - 🇨🇦 多伦多｜Canada
      - 🇮🇱 以色列｜Israel
      - 🇪🇸 西班牙｜Spain
      - 🇧🇪 比利时｜Belgium
      - 🇮🇹 意大利｜Italy
      - 🇦🇹 奥地利｜Austria
      - 🇭🇺 匈牙利｜Hungary
      - 🇲🇰 马其顿｜Macedonia
      - 🇱🇹 立陶宛｜Lithuania
      - 🇹🇷 土耳其｜Turkey
      - 🇨🇭 瑞士｜Switzerland
      - 🇸🇦 沙特｜Saudi Arabia
      - 🇳🇱 荷兰｜Netherlands
      - 🇨🇱 智利｜Chile 01
      - 🇨🇱 智利｜Chile 02
      - 🇨🇿 捷克｜Czech
      - 🇸🇪 瑞典｜Sweden
      - 🇿🇦 南非｜South Africa
      - 🇩🇰 丹麦｜Denmark
      - 🇹🇬 多哥｜Togo
      - 🇪🇬 埃及｜Egypt
      - 🇮🇸 冰岛｜Iceland
      - 🇳🇴 挪威｜Norway
      - 🇲🇦 卡萨布兰卡｜Morocco
      - 🇦🇿 阿塞拜疆｜Azerbaijan
      - 🇷🇴 罗马尼亚｜Romania
      - 🇳🇬 尼日利亚｜Nigeria
      - 🇨🇴 哥伦比亚｜Colombia
      - 🇰🇿 哈萨克斯坦｜Kazakhstan
      - 🇰🇬 吉尔吉斯斯坦｜Kyrgyzstan
  - name: ♻️ 自动选择
    type: url-test
    proxies:
      - 🇭🇰 香港｜Hong Kong 01
      - 🇭🇰 香港｜Hong Kong 02
      - 🇭🇰 香港｜Hong Kong 03
      - 🇭🇰 香港｜Hong Kong 04
      - 🇭🇰 香港｜Hong Kong 05
      - 🇭🇰 香港｜Hong Kong 06
      - 🇭🇰 香港｜Hong Kong 07
      - 🇭🇰 香港｜Hong Kong 08
      - 🇭🇰 香港｜Hong Kong 09
      - 🇭🇰 香港｜Hong Kong 10
      - 🇯🇵 日本｜Japan 01
      - 🇯🇵 日本｜Japan 02
      - 🇯🇵 日本｜Japan 03
      - 🇯🇵 日本｜Japan 04
      - 🇯🇵 日本｜Japan Res 01
      - 🇯🇵 日本｜Japan Res 02
      - 🇯🇵 日本｜Japan Res 03
      - 🇯🇵 日本｜Japan Res 04
      - 🇯🇵 日本｜Japan Dir 01
      - 🇯🇵 日本｜Japan Dir 02
      - 🇯🇵 日本｜Japan Dir 03
      - 🇯🇵 日本｜Japan Dir 04
      - 🇨🇳 台湾｜Taiwan 01
      - 🇨🇳 台湾｜Taiwan 02
      - 🇨🇳 台湾｜Taiwan 03
      - 🇨🇳 台湾｜Taiwan 04
      - 🇨🇳 台湾｜Taiwan ISP 05
      - 🇨🇳 台湾｜Taiwan ISP 06
      - 🇨🇳 台湾｜Taiwan ISP 07
      - 🇨🇳 台湾｜Taiwan ISP 08
      - 🇺🇸 美国｜USA Prime 01
      - 🇺🇸 美国｜USA Prime 02
      - 🇺🇸 美国｜USA Prime 03
      - 🇺🇸 美国｜USA Prime 04
      - 🇺🇸 美国｜USA Prime 05
      - 🇺🇸 美国｜USA Prime 06
      - 🇺🇸 美国｜USA Prime 07 x 0.2
      - 🇺🇸 美国｜USA Prime 08 x 0.2
      - 🇸🇬 新加坡｜Singapore 01
      - 🇸🇬 新加坡｜Singapore 02
      - 🇸🇬 新加坡｜Singapore 03
      - 🇸🇬 新加坡｜Singapore 04
      - 🇸🇬 新加坡｜Singapore 05
      - 🇸🇬 新加坡｜Singapore 06
      - 🇸🇬 新加坡｜Singapore 07
      - 🇸🇬 新加坡｜Singapore 08
      - 🇰🇷 韩国｜Korea 01
      - 🇰🇷 韩国｜Korea 02
      - 🇰🇷 韩国｜Korea 03
      - 🇰🇷 韩国｜Korea 04
      - 🇲🇾 马来西亚｜Malaysia 01
      - 🇲🇾 马来西亚｜Malaysia 02
      - 🇲🇾 马来西亚｜Malaysia 03
      - 🇲🇾 马来西亚｜Malaysia 04
      - 🇹🇭 泰国｜Thailand 01
      - 🇹🇭 泰国｜Thailand 02
      - 🇹🇭 泰国｜Thailand 03
      - 🇹🇭 泰国｜Thailand 04
      - 🇻🇳 越南｜Vietnam 01
      - 🇻🇳 越南｜Vietnam 02
      - 🇻🇳 越南｜Vietnam 03
      - 🇻🇳 越南｜Vietnam 04
      - 🇲🇴 澳门｜Macau 01
      - 🇲🇴 澳门｜Macau 02
      - 🇲🇴 澳门｜Macau 03
      - 🇲🇴 澳门｜Macau 04
      - 🇵🇭 菲律宾｜Philippines 01
      - 🇵🇭 菲律宾｜Philippines 02
      - 🇵🇭 菲律宾｜Philippines 03
      - 🇵🇭 菲律宾｜Philippines 04
      - 🇦🇺 悉尼｜Sydney
      - 🇦🇺 墨尔本｜Melbourne
      - 🇮🇳 印度｜India 01
      - 🇮🇳 印度｜India 02
      - 🇦🇪 迪拜｜Dubai
      - 🇮🇩 印尼｜Indonesia
      - 🇧🇷 巴西｜Brazil 01
      - 🇧🇷 巴西｜Brazil 02
      - 🇬🇧 英国｜United Kingdom
      - 🇫🇷 法国｜France
      - 🇩🇪 德国｜Germany
      - 🇷🇺 俄罗斯｜Russia
      - 🇦🇷 阿根廷｜Argentina
      - 🇲🇽 墨西哥｜Mexico 01
      - 🇲🇽 墨西哥｜Mexico 02
      - 🇨🇦 加拿大｜Canada
      - 🇨🇦 多伦多｜Canada
      - 🇮🇱 以色列｜Israel
      - 🇪🇸 西班牙｜Spain
      - 🇧🇪 比利时｜Belgium
      - 🇮🇹 意大利｜Italy
      - 🇦🇹 奥地利｜Austria
      - 🇭🇺 匈牙利｜Hungary
      - 🇲🇰 马其顿｜Macedonia
      - 🇱🇹 立陶宛｜Lithuania
      - 🇹🇷 土耳其｜Turkey
      - 🇨🇭 瑞士｜Switzerland
      - 🇸🇦 沙特｜Saudi Arabia
      - 🇳🇱 荷兰｜Netherlands
      - 🇨🇱 智利｜Chile 01
      - 🇨🇱 智利｜Chile 02
      - 🇨🇿 捷克｜Czech
      - 🇸🇪 瑞典｜Sweden
      - 🇿🇦 南非｜South Africa
      - 🇩🇰 丹麦｜Denmark
      - 🇹🇬 多哥｜Togo
      - 🇪🇬 埃及｜Egypt
      - 🇮🇸 冰岛｜Iceland
      - 🇳🇴 挪威｜Norway
      - 🇲🇦 卡萨布兰卡｜Morocco
      - 🇦🇿 阿塞拜疆｜Azerbaijan
      - 🇷🇴 罗马尼亚｜Romania
      - 🇳🇬 尼日利亚｜Nigeria
      - 🇨🇴 哥伦比亚｜Colombia
      - 🇰🇿 哈萨克斯坦｜Kazakhstan
      - 🇰🇬 吉尔吉斯斯坦｜Kyrgyzstan
    url: http://www.gstatic.com/generate_204
    interval: 300
    tolerance: 50
  - name: 🌍 国外媒体
    type: select
    proxies:
      - 🚀 节点选择
      - ♻️ 自动选择
      - 🎯 全球直连
      - 🇭🇰 香港｜Hong Kong 01
      - 🇭🇰 香港｜Hong Kong 02
      - 🇭🇰 香港｜Hong Kong 03
      - 🇭🇰 香港｜Hong Kong 04
      - 🇭🇰 香港｜Hong Kong 05
      - 🇭🇰 香港｜Hong Kong 06
      - 🇭🇰 香港｜Hong Kong 07
      - 🇭🇰 香港｜Hong Kong 08
      - 🇭🇰 香港｜Hong Kong 09
      - 🇭🇰 香港｜Hong Kong 10
      - 🇯🇵 日本｜Japan 01
      - 🇯🇵 日本｜Japan 02
      - 🇯🇵 日本｜Japan 03
      - 🇯🇵 日本｜Japan 04
      - 🇯🇵 日本｜Japan Res 01
      - 🇯🇵 日本｜Japan Res 02
      - 🇯🇵 日本｜Japan Res 03
      - 🇯🇵 日本｜Japan Res 04
      - 🇯🇵 日本｜Japan Dir 01
      - 🇯🇵 日本｜Japan Dir 02
      - 🇯🇵 日本｜Japan Dir 03
      - 🇯🇵 日本｜Japan Dir 04
      - 🇨🇳 台湾｜Taiwan 01
      - 🇨🇳 台湾｜Taiwan 02
      - 🇨🇳 台湾｜Taiwan 03
      - 🇨🇳 台湾｜Taiwan 04
      - 🇨🇳 台湾｜Taiwan ISP 05
      - 🇨🇳 台湾｜Taiwan ISP 06
      - 🇨🇳 台湾｜Taiwan ISP 07
      - 🇨🇳 台湾｜Taiwan ISP 08
      - 🇺🇸 美国｜USA Prime 01
      - 🇺🇸 美国｜USA Prime 02
      - 🇺🇸 美国｜USA Prime 03
      - 🇺🇸 美国｜USA Prime 04
      - 🇺🇸 美国｜USA Prime 05
      - 🇺🇸 美国｜USA Prime 06
      - 🇺🇸 美国｜USA Prime 07 x 0.2
      - 🇺🇸 美国｜USA Prime 08 x 0.2
      - 🇸🇬 新加坡｜Singapore 01
      - 🇸🇬 新加坡｜Singapore 02
      - 🇸🇬 新加坡｜Singapore 03
      - 🇸🇬 新加坡｜Singapore 04
      - 🇸🇬 新加坡｜Singapore 05
      - 🇸🇬 新加坡｜Singapore 06
      - 🇸🇬 新加坡｜Singapore 07
      - 🇸🇬 新加坡｜Singapore 08
      - 🇰🇷 韩国｜Korea 01
      - 🇰🇷 韩国｜Korea 02
      - 🇰🇷 韩国｜Korea 03
      - 🇰🇷 韩国｜Korea 04
      - 🇲🇾 马来西亚｜Malaysia 01
      - 🇲🇾 马来西亚｜Malaysia 02
      - 🇲🇾 马来西亚｜Malaysia 03
      - 🇲🇾 马来西亚｜Malaysia 04
      - 🇹🇭 泰国｜Thailand 01
      - 🇹🇭 泰国｜Thailand 02
      - 🇹🇭 泰国｜Thailand 03
      - 🇹🇭 泰国｜Thailand 04
      - 🇻🇳 越南｜Vietnam 01
      - 🇻🇳 越南｜Vietnam 02
      - 🇻🇳 越南｜Vietnam 03
      - 🇻🇳 越南｜Vietnam 04
      - 🇲🇴 澳门｜Macau 01
      - 🇲🇴 澳门｜Macau 02
      - 🇲🇴 澳门｜Macau 03
      - 🇲🇴 澳门｜Macau 04
      - 🇵🇭 菲律宾｜Philippines 01
      - 🇵🇭 菲律宾｜Philippines 02
      - 🇵🇭 菲律宾｜Philippines 03
      - 🇵🇭 菲律宾｜Philippines 04
      - 🇦🇺 悉尼｜Sydney
      - 🇦🇺 墨尔本｜Melbourne
      - 🇮🇳 印度｜India 01
      - 🇮🇳 印度｜India 02
      - 🇦🇪 迪拜｜Dubai
      - 🇮🇩 印尼｜Indonesia
      - 🇧🇷 巴西｜Brazil 01
      - 🇧🇷 巴西｜Brazil 02
      - 🇬🇧 英国｜United Kingdom
      - 🇫🇷 法国｜France
      - 🇩🇪 德国｜Germany
      - 🇷🇺 俄罗斯｜Russia
      - 🇦🇷 阿根廷｜Argentina
      - 🇲🇽 墨西哥｜Mexico 01
      - 🇲🇽 墨西哥｜Mexico 02
      - 🇨🇦 加拿大｜Canada
      - 🇨🇦 多伦多｜Canada
      - 🇮🇱 以色列｜Israel
      - 🇪🇸 西班牙｜Spain
      - 🇧🇪 比利时｜Belgium
      - 🇮🇹 意大利｜Italy
      - 🇦🇹 奥地利｜Austria
      - 🇭🇺 匈牙利｜Hungary
      - 🇲🇰 马其顿｜Macedonia
      - 🇱🇹 立陶宛｜Lithuania
      - 🇹🇷 土耳其｜Turkey
      - 🇨🇭 瑞士｜Switzerland
      - 🇸🇦 沙特｜Saudi Arabia
      - 🇳🇱 荷兰｜Netherlands
      - 🇨🇱 智利｜Chile 01
      - 🇨🇱 智利｜Chile 02
      - 🇨🇿 捷克｜Czech
      - 🇸🇪 瑞典｜Sweden
      - 🇿🇦 南非｜South Africa
      - 🇩🇰 丹麦｜Denmark
      - 🇹🇬 多哥｜Togo
      - 🇪🇬 埃及｜Egypt
      - 🇮🇸 冰岛｜Iceland
      - 🇳🇴 挪威｜Norway
      - 🇲🇦 卡萨布兰卡｜Morocco
      - 🇦🇿 阿塞拜疆｜Azerbaijan
      - 🇷🇴 罗马尼亚｜Romania
      - 🇳🇬 尼日利亚｜Nigeria
      - 🇨🇴 哥伦比亚｜Colombia
      - 🇰🇿 哈萨克斯坦｜Kazakhstan
      - 🇰🇬 吉尔吉斯斯坦｜Kyrgyzstan
  - name: 📲 电报信息
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - 🇭🇰 香港｜Hong Kong 01
      - 🇭🇰 香港｜Hong Kong 02
      - 🇭🇰 香港｜Hong Kong 03
      - 🇭🇰 香港｜Hong Kong 04
      - 🇭🇰 香港｜Hong Kong 05
      - 🇭🇰 香港｜Hong Kong 06
      - 🇭🇰 香港｜Hong Kong 07
      - 🇭🇰 香港｜Hong Kong 08
      - 🇭🇰 香港｜Hong Kong 09
      - 🇭🇰 香港｜Hong Kong 10
      - 🇯🇵 日本｜Japan 01
      - 🇯🇵 日本｜Japan 02
      - 🇯🇵 日本｜Japan 03
      - 🇯🇵 日本｜Japan 04
      - 🇯🇵 日本｜Japan Res 01
      - 🇯🇵 日本｜Japan Res 02
      - 🇯🇵 日本｜Japan Res 03
      - 🇯🇵 日本｜Japan Res 04
      - 🇯🇵 日本｜Japan Dir 01
      - 🇯🇵 日本｜Japan Dir 02
      - 🇯🇵 日本｜Japan Dir 03
      - 🇯🇵 日本｜Japan Dir 04
      - 🇨🇳 台湾｜Taiwan 01
      - 🇨🇳 台湾｜Taiwan 02
      - 🇨🇳 台湾｜Taiwan 03
      - 🇨🇳 台湾｜Taiwan 04
      - 🇨🇳 台湾｜Taiwan ISP 05
      - 🇨🇳 台湾｜Taiwan ISP 06
      - 🇨🇳 台湾｜Taiwan ISP 07
      - 🇨🇳 台湾｜Taiwan ISP 08
      - 🇺🇸 美国｜USA Prime 01
      - 🇺🇸 美国｜USA Prime 02
      - 🇺🇸 美国｜USA Prime 03
      - 🇺🇸 美国｜USA Prime 04
      - 🇺🇸 美国｜USA Prime 05
      - 🇺🇸 美国｜USA Prime 06
      - 🇺🇸 美国｜USA Prime 07 x 0.2
      - 🇺🇸 美国｜USA Prime 08 x 0.2
      - 🇸🇬 新加坡｜Singapore 01
      - 🇸🇬 新加坡｜Singapore 02
      - 🇸🇬 新加坡｜Singapore 03
      - 🇸🇬 新加坡｜Singapore 04
      - 🇸🇬 新加坡｜Singapore 05
      - 🇸🇬 新加坡｜Singapore 06
      - 🇸🇬 新加坡｜Singapore 07
      - 🇸🇬 新加坡｜Singapore 08
      - 🇰🇷 韩国｜Korea 01
      - 🇰🇷 韩国｜Korea 02
      - 🇰🇷 韩国｜Korea 03
      - 🇰🇷 韩国｜Korea 04
      - 🇲🇾 马来西亚｜Malaysia 01
      - 🇲🇾 马来西亚｜Malaysia 02
      - 🇲🇾 马来西亚｜Malaysia 03
      - 🇲🇾 马来西亚｜Malaysia 04
      - 🇹🇭 泰国｜Thailand 01
      - 🇹🇭 泰国｜Thailand 02
      - 🇹🇭 泰国｜Thailand 03
      - 🇹🇭 泰国｜Thailand 04
      - 🇻🇳 越南｜Vietnam 01
      - 🇻🇳 越南｜Vietnam 02
      - 🇻🇳 越南｜Vietnam 03
      - 🇻🇳 越南｜Vietnam 04
      - 🇲🇴 澳门｜Macau 01
      - 🇲🇴 澳门｜Macau 02
      - 🇲🇴 澳门｜Macau 03
      - 🇲🇴 澳门｜Macau 04
      - 🇵🇭 菲律宾｜Philippines 01
      - 🇵🇭 菲律宾｜Philippines 02
      - 🇵🇭 菲律宾｜Philippines 03
      - 🇵🇭 菲律宾｜Philippines 04
      - 🇦🇺 悉尼｜Sydney
      - 🇦🇺 墨尔本｜Melbourne
      - 🇮🇳 印度｜India 01
      - 🇮🇳 印度｜India 02
      - 🇦🇪 迪拜｜Dubai
      - 🇮🇩 印尼｜Indonesia
      - 🇧🇷 巴西｜Brazil 01
      - 🇧🇷 巴西｜Brazil 02
      - 🇬🇧 英国｜United Kingdom
      - 🇫🇷 法国｜France
      - 🇩🇪 德国｜Germany
      - 🇷🇺 俄罗斯｜Russia
      - 🇦🇷 阿根廷｜Argentina
      - 🇲🇽 墨西哥｜Mexico 01
      - 🇲🇽 墨西哥｜Mexico 02
      - 🇨🇦 加拿大｜Canada
      - 🇨🇦 多伦多｜Canada
      - 🇮🇱 以色列｜Israel
      - 🇪🇸 西班牙｜Spain
      - 🇧🇪 比利时｜Belgium
      - 🇮🇹 意大利｜Italy
      - 🇦🇹 奥地利｜Austria
      - 🇭🇺 匈牙利｜Hungary
      - 🇲🇰 马其顿｜Macedonia
      - 🇱🇹 立陶宛｜Lithuania
      - 🇹🇷 土耳其｜Turkey
      - 🇨🇭 瑞士｜Switzerland
      - 🇸🇦 沙特｜Saudi Arabia
      - 🇳🇱 荷兰｜Netherlands
      - 🇨🇱 智利｜Chile 01
      - 🇨🇱 智利｜Chile 02
      - 🇨🇿 捷克｜Czech
      - 🇸🇪 瑞典｜Sweden
      - 🇿🇦 南非｜South Africa
      - 🇩🇰 丹麦｜Denmark
      - 🇹🇬 多哥｜Togo
      - 🇪🇬 埃及｜Egypt
      - 🇮🇸 冰岛｜Iceland
      - 🇳🇴 挪威｜Norway
      - 🇲🇦 卡萨布兰卡｜Morocco
      - 🇦🇿 阿塞拜疆｜Azerbaijan
      - 🇷🇴 罗马尼亚｜Romania
      - 🇳🇬 尼日利亚｜Nigeria
      - 🇨🇴 哥伦比亚｜Colombia
      - 🇰🇿 哈萨克斯坦｜Kazakhstan
      - 🇰🇬 吉尔吉斯斯坦｜Kyrgyzstan
  - name: Ⓜ️ 微软服务
    type: select
    proxies:
      - 🎯 全球直连
      - 🚀 节点选择
      - 🇭🇰 香港｜Hong Kong 01
      - 🇭🇰 香港｜Hong Kong 02
      - 🇭🇰 香港｜Hong Kong 03
      - 🇭🇰 香港｜Hong Kong 04
      - 🇭🇰 香港｜Hong Kong 05
      - 🇭🇰 香港｜Hong Kong 06
      - 🇭🇰 香港｜Hong Kong 07
      - 🇭🇰 香港｜Hong Kong 08
      - 🇭🇰 香港｜Hong Kong 09
      - 🇭🇰 香港｜Hong Kong 10
      - 🇯🇵 日本｜Japan 01
      - 🇯🇵 日本｜Japan 02
      - 🇯🇵 日本｜Japan 03
      - 🇯🇵 日本｜Japan 04
      - 🇯🇵 日本｜Japan Res 01
      - 🇯🇵 日本｜Japan Res 02
      - 🇯🇵 日本｜Japan Res 03
      - 🇯🇵 日本｜Japan Res 04
      - 🇯🇵 日本｜Japan Dir 01
      - 🇯🇵 日本｜Japan Dir 02
      - 🇯🇵 日本｜Japan Dir 03
      - 🇯🇵 日本｜Japan Dir 04
      - 🇨🇳 台湾｜Taiwan 01
      - 🇨🇳 台湾｜Taiwan 02
      - 🇨🇳 台湾｜Taiwan 03
      - 🇨🇳 台湾｜Taiwan 04
      - 🇨🇳 台湾｜Taiwan ISP 05
      - 🇨🇳 台湾｜Taiwan ISP 06
      - 🇨🇳 台湾｜Taiwan ISP 07
      - 🇨🇳 台湾｜Taiwan ISP 08
      - 🇺🇸 美国｜USA Prime 01
      - 🇺🇸 美国｜USA Prime 02
      - 🇺🇸 美国｜USA Prime 03
      - 🇺🇸 美国｜USA Prime 04
      - 🇺🇸 美国｜USA Prime 05
      - 🇺🇸 美国｜USA Prime 06
      - 🇺🇸 美国｜USA Prime 07 x 0.2
      - 🇺🇸 美国｜USA Prime 08 x 0.2
      - 🇸🇬 新加坡｜Singapore 01
      - 🇸🇬 新加坡｜Singapore 02
      - 🇸🇬 新加坡｜Singapore 03
      - 🇸🇬 新加坡｜Singapore 04
      - 🇸🇬 新加坡｜Singapore 05
      - 🇸🇬 新加坡｜Singapore 06
      - 🇸🇬 新加坡｜Singapore 07
      - 🇸🇬 新加坡｜Singapore 08
      - 🇰🇷 韩国｜Korea 01
      - 🇰🇷 韩国｜Korea 02
      - 🇰🇷 韩国｜Korea 03
      - 🇰🇷 韩国｜Korea 04
      - 🇲🇾 马来西亚｜Malaysia 01
      - 🇲🇾 马来西亚｜Malaysia 02
      - 🇲🇾 马来西亚｜Malaysia 03
      - 🇲🇾 马来西亚｜Malaysia 04
      - 🇹🇭 泰国｜Thailand 01
      - 🇹🇭 泰国｜Thailand 02
      - 🇹🇭 泰国｜Thailand 03
      - 🇹🇭 泰国｜Thailand 04
      - 🇻🇳 越南｜Vietnam 01
      - 🇻🇳 越南｜Vietnam 02
      - 🇻🇳 越南｜Vietnam 03
      - 🇻🇳 越南｜Vietnam 04
      - 🇲🇴 澳门｜Macau 01
      - 🇲🇴 澳门｜Macau 02
      - 🇲🇴 澳门｜Macau 03
      - 🇲🇴 澳门｜Macau 04
      - 🇵🇭 菲律宾｜Philippines 01
      - 🇵🇭 菲律宾｜Philippines 02
      - 🇵🇭 菲律宾｜Philippines 03
      - 🇵🇭 菲律宾｜Philippines 04
      - 🇦🇺 悉尼｜Sydney
      - 🇦🇺 墨尔本｜Melbourne
      - 🇮🇳 印度｜India 01
      - 🇮🇳 印度｜India 02
      - 🇦🇪 迪拜｜Dubai
      - 🇮🇩 印尼｜Indonesia
      - 🇧🇷 巴西｜Brazil 01
      - 🇧🇷 巴西｜Brazil 02
      - 🇬🇧 英国｜United Kingdom
      - 🇫🇷 法国｜France
      - 🇩🇪 德国｜Germany
      - 🇷🇺 俄罗斯｜Russia
      - 🇦🇷 阿根廷｜Argentina
      - 🇲🇽 墨西哥｜Mexico 01
      - 🇲🇽 墨西哥｜Mexico 02
      - 🇨🇦 加拿大｜Canada
      - 🇨🇦 多伦多｜Canada
      - 🇮🇱 以色列｜Israel
      - 🇪🇸 西班牙｜Spain
      - 🇧🇪 比利时｜Belgium
      - 🇮🇹 意大利｜Italy
      - 🇦🇹 奥地利｜Austria
      - 🇭🇺 匈牙利｜Hungary
      - 🇲🇰 马其顿｜Macedonia
      - 🇱🇹 立陶宛｜Lithuania
      - 🇹🇷 土耳其｜Turkey
      - 🇨🇭 瑞士｜Switzerland
      - 🇸🇦 沙特｜Saudi Arabia
      - 🇳🇱 荷兰｜Netherlands
      - 🇨🇱 智利｜Chile 01
      - 🇨🇱 智利｜Chile 02
      - 🇨🇿 捷克｜Czech
      - 🇸🇪 瑞典｜Sweden
      - 🇿🇦 南非｜South Africa
      - 🇩🇰 丹麦｜Denmark
      - 🇹🇬 多哥｜Togo
      - 🇪🇬 埃及｜Egypt
      - 🇮🇸 冰岛｜Iceland
      - 🇳🇴 挪威｜Norway
      - 🇲🇦 卡萨布兰卡｜Morocco
      - 🇦🇿 阿塞拜疆｜Azerbaijan
      - 🇷🇴 罗马尼亚｜Romania
      - 🇳🇬 尼日利亚｜Nigeria
      - 🇨🇴 哥伦比亚｜Colombia
      - 🇰🇿 哈萨克斯坦｜Kazakhstan
      - 🇰🇬 吉尔吉斯斯坦｜Kyrgyzstan
  - name: 🍎 苹果服务
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - 🇭🇰 香港｜Hong Kong 01
      - 🇭🇰 香港｜Hong Kong 02
      - 🇭🇰 香港｜Hong Kong 03
      - 🇭🇰 香港｜Hong Kong 04
      - 🇭🇰 香港｜Hong Kong 05
      - 🇭🇰 香港｜Hong Kong 06
      - 🇭🇰 香港｜Hong Kong 07
      - 🇭🇰 香港｜Hong Kong 08
      - 🇭🇰 香港｜Hong Kong 09
      - 🇭🇰 香港｜Hong Kong 10
      - 🇯🇵 日本｜Japan 01
      - 🇯🇵 日本｜Japan 02
      - 🇯🇵 日本｜Japan 03
      - 🇯🇵 日本｜Japan 04
      - 🇯🇵 日本｜Japan Res 01
      - 🇯🇵 日本｜Japan Res 02
      - 🇯🇵 日本｜Japan Res 03
      - 🇯🇵 日本｜Japan Res 04
      - 🇯🇵 日本｜Japan Dir 01
      - 🇯🇵 日本｜Japan Dir 02
      - 🇯🇵 日本｜Japan Dir 03
      - 🇯🇵 日本｜Japan Dir 04
      - 🇨🇳 台湾｜Taiwan 01
      - 🇨🇳 台湾｜Taiwan 02
      - 🇨🇳 台湾｜Taiwan 03
      - 🇨🇳 台湾｜Taiwan 04
      - 🇨🇳 台湾｜Taiwan ISP 05
      - 🇨🇳 台湾｜Taiwan ISP 06
      - 🇨🇳 台湾｜Taiwan ISP 07
      - 🇨🇳 台湾｜Taiwan ISP 08
      - 🇺🇸 美国｜USA Prime 01
      - 🇺🇸 美国｜USA Prime 02
      - 🇺🇸 美国｜USA Prime 03
      - 🇺🇸 美国｜USA Prime 04
      - 🇺🇸 美国｜USA Prime 05
      - 🇺🇸 美国｜USA Prime 06
      - 🇺🇸 美国｜USA Prime 07 x 0.2
      - 🇺🇸 美国｜USA Prime 08 x 0.2
      - 🇸🇬 新加坡｜Singapore 01
      - 🇸🇬 新加坡｜Singapore 02
      - 🇸🇬 新加坡｜Singapore 03
      - 🇸🇬 新加坡｜Singapore 04
      - 🇸🇬 新加坡｜Singapore 05
      - 🇸🇬 新加坡｜Singapore 06
      - 🇸🇬 新加坡｜Singapore 07
      - 🇸🇬 新加坡｜Singapore 08
      - 🇰🇷 韩国｜Korea 01
      - 🇰🇷 韩国｜Korea 02
      - 🇰🇷 韩国｜Korea 03
      - 🇰🇷 韩国｜Korea 04
      - 🇲🇾 马来西亚｜Malaysia 01
      - 🇲🇾 马来西亚｜Malaysia 02
      - 🇲🇾 马来西亚｜Malaysia 03
      - 🇲🇾 马来西亚｜Malaysia 04
      - 🇹🇭 泰国｜Thailand 01
      - 🇹🇭 泰国｜Thailand 02
      - 🇹🇭 泰国｜Thailand 03
      - 🇹🇭 泰国｜Thailand 04
      - 🇻🇳 越南｜Vietnam 01
      - 🇻🇳 越南｜Vietnam 02
      - 🇻🇳 越南｜Vietnam 03
      - 🇻🇳 越南｜Vietnam 04
      - 🇲🇴 澳门｜Macau 01
      - 🇲🇴 澳门｜Macau 02
      - 🇲🇴 澳门｜Macau 03
      - 🇲🇴 澳门｜Macau 04
      - 🇵🇭 菲律宾｜Philippines 01
      - 🇵🇭 菲律宾｜Philippines 02
      - 🇵🇭 菲律宾｜Philippines 03
      - 🇵🇭 菲律宾｜Philippines 04
      - 🇦🇺 悉尼｜Sydney
      - 🇦🇺 墨尔本｜Melbourne
      - 🇮🇳 印度｜India 01
      - 🇮🇳 印度｜India 02
      - 🇦🇪 迪拜｜Dubai
      - 🇮🇩 印尼｜Indonesia
      - 🇧🇷 巴西｜Brazil 01
      - 🇧🇷 巴西｜Brazil 02
      - 🇬🇧 英国｜United Kingdom
      - 🇫🇷 法国｜France
      - 🇩🇪 德国｜Germany
      - 🇷🇺 俄罗斯｜Russia
      - 🇦🇷 阿根廷｜Argentina
      - 🇲🇽 墨西哥｜Mexico 01
      - 🇲🇽 墨西哥｜Mexico 02
      - 🇨🇦 加拿大｜Canada
      - 🇨🇦 多伦多｜Canada
      - 🇮🇱 以色列｜Israel
      - 🇪🇸 西班牙｜Spain
      - 🇧🇪 比利时｜Belgium
      - 🇮🇹 意大利｜Italy
      - 🇦🇹 奥地利｜Austria
      - 🇭🇺 匈牙利｜Hungary
      - 🇲🇰 马其顿｜Macedonia
      - 🇱🇹 立陶宛｜Lithuania
      - 🇹🇷 土耳其｜Turkey
      - 🇨🇭 瑞士｜Switzerland
      - 🇸🇦 沙特｜Saudi Arabia
      - 🇳🇱 荷兰｜Netherlands
      - 🇨🇱 智利｜Chile 01
      - 🇨🇱 智利｜Chile 02
      - 🇨🇿 捷克｜Czech
      - 🇸🇪 瑞典｜Sweden
      - 🇿🇦 南非｜South Africa
      - 🇩🇰 丹麦｜Denmark
      - 🇹🇬 多哥｜Togo
      - 🇪🇬 埃及｜Egypt
      - 🇮🇸 冰岛｜Iceland
      - 🇳🇴 挪威｜Norway
      - 🇲🇦 卡萨布兰卡｜Morocco
      - 🇦🇿 阿塞拜疆｜Azerbaijan
      - 🇷🇴 罗马尼亚｜Romania
      - 🇳🇬 尼日利亚｜Nigeria
      - 🇨🇴 哥伦比亚｜Colombia
      - 🇰🇿 哈萨克斯坦｜Kazakhstan
      - 🇰🇬 吉尔吉斯斯坦｜Kyrgyzstan
  - name: 🎯 全球直连
    type: select
    proxies:
      - DIRECT
      - 🚀 节点选择
      - ♻️ 自动选择
  - name: 🛑 全球拦截
    type: select
    proxies:
      - REJECT
      - DIRECT
  - name: 🍃 应用净化
    type: select
    proxies:
      - REJECT
      - DIRECT
  - name: 🐟 漏网之鱼
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - ♻️ 自动选择
      - 🇭🇰 香港｜Hong Kong 01
      - 🇭🇰 香港｜Hong Kong 02
      - 🇭🇰 香港｜Hong Kong 03
      - 🇭🇰 香港｜Hong Kong 04
      - 🇭🇰 香港｜Hong Kong 05
      - 🇭🇰 香港｜Hong Kong 06
      - 🇭🇰 香港｜Hong Kong 07
      - 🇭🇰 香港｜Hong Kong 08
      - 🇭🇰 香港｜Hong Kong 09
      - 🇭🇰 香港｜Hong Kong 10
      - 🇯🇵 日本｜Japan 01
      - 🇯🇵 日本｜Japan 02
      - 🇯🇵 日本｜Japan 03
      - 🇯🇵 日本｜Japan 04
      - 🇯🇵 日本｜Japan Res 01
      - 🇯🇵 日本｜Japan Res 02
      - 🇯🇵 日本｜Japan Res 03
      - 🇯🇵 日本｜Japan Res 04
      - 🇯🇵 日本｜Japan Dir 01
      - 🇯🇵 日本｜Japan Dir 02
      - 🇯🇵 日本｜Japan Dir 03
      - 🇯🇵 日本｜Japan Dir 04
      - 🇨🇳 台湾｜Taiwan 01
      - 🇨🇳 台湾｜Taiwan 02
      - 🇨🇳 台湾｜Taiwan 03
      - 🇨🇳 台湾｜Taiwan 04
      - 🇨🇳 台湾｜Taiwan ISP 05
      - 🇨🇳 台湾｜Taiwan ISP 06
      - 🇨🇳 台湾｜Taiwan ISP 07
      - 🇨🇳 台湾｜Taiwan ISP 08
      - 🇺🇸 美国｜USA Prime 01
      - 🇺🇸 美国｜USA Prime 02
      - 🇺🇸 美国｜USA Prime 03
      - 🇺🇸 美国｜USA Prime 04
      - 🇺🇸 美国｜USA Prime 05
      - 🇺🇸 美国｜USA Prime 06
      - 🇺🇸 美国｜USA Prime 07 x 0.2
      - 🇺🇸 美国｜USA Prime 08 x 0.2
      - 🇸🇬 新加坡｜Singapore 01
      - 🇸🇬 新加坡｜Singapore 02
      - 🇸🇬 新加坡｜Singapore 03
      - 🇸🇬 新加坡｜Singapore 04
      - 🇸🇬 新加坡｜Singapore 05
      - 🇸🇬 新加坡｜Singapore 06
      - 🇸🇬 新加坡｜Singapore 07
      - 🇸🇬 新加坡｜Singapore 08
      - 🇰🇷 韩国｜Korea 01
      - 🇰🇷 韩国｜Korea 02
      - 🇰🇷 韩国｜Korea 03
      - 🇰🇷 韩国｜Korea 04
      - 🇲🇾 马来西亚｜Malaysia 01
      - 🇲🇾 马来西亚｜Malaysia 02
      - 🇲🇾 马来西亚｜Malaysia 03
      - 🇲🇾 马来西亚｜Malaysia 04
      - 🇹🇭 泰国｜Thailand 01
      - 🇹🇭 泰国｜Thailand 02
      - 🇹🇭 泰国｜Thailand 03
      - 🇹🇭 泰国｜Thailand 04
      - 🇻🇳 越南｜Vietnam 01
      - 🇻🇳 越南｜Vietnam 02
      - 🇻🇳 越南｜Vietnam 03
      - 🇻🇳 越南｜Vietnam 04
      - 🇲🇴 澳门｜Macau 01
      - 🇲🇴 澳门｜Macau 02
      - 🇲🇴 澳门｜Macau 03
      - 🇲🇴 澳门｜Macau 04
      - 🇵🇭 菲律宾｜Philippines 01
      - 🇵🇭 菲律宾｜Philippines 02
      - 🇵🇭 菲律宾｜Philippines 03
      - 🇵🇭 菲律宾｜Philippines 04
      - 🇦🇺 悉尼｜Sydney
      - 🇦🇺 墨尔本｜Melbourne
      - 🇮🇳 印度｜India 01
      - 🇮🇳 印度｜India 02
      - 🇦🇪 迪拜｜Dubai
      - 🇮🇩 印尼｜Indonesia
      - 🇧🇷 巴西｜Brazil 01
      - 🇧🇷 巴西｜Brazil 02
      - 🇬🇧 英国｜United Kingdom
      - 🇫🇷 法国｜France
      - 🇩🇪 德国｜Germany
      - 🇷🇺 俄罗斯｜Russia
      - 🇦🇷 阿根廷｜Argentina
      - 🇲🇽 墨西哥｜Mexico 01
      - 🇲🇽 墨西哥｜Mexico 02
      - 🇨🇦 加拿大｜Canada
      - 🇨🇦 多伦多｜Canada
      - 🇮🇱 以色列｜Israel
      - 🇪🇸 西班牙｜Spain
      - 🇧🇪 比利时｜Belgium
      - 🇮🇹 意大利｜Italy
      - 🇦🇹 奥地利｜Austria
      - 🇭🇺 匈牙利｜Hungary
      - 🇲🇰 马其顿｜Macedonia
      - 🇱🇹 立陶宛｜Lithuania
      - 🇹🇷 土耳其｜Turkey
      - 🇨🇭 瑞士｜Switzerland
      - 🇸🇦 沙特｜Saudi Arabia
      - 🇳🇱 荷兰｜Netherlands
      - 🇨🇱 智利｜Chile 01
      - 🇨🇱 智利｜Chile 02
      - 🇨🇿 捷克｜Czech
      - 🇸🇪 瑞典｜Sweden
      - 🇿🇦 南非｜South Africa
      - 🇩🇰 丹麦｜Denmark
      - 🇹🇬 多哥｜Togo
      - 🇪🇬 埃及｜Egypt
      - 🇮🇸 冰岛｜Iceland
      - 🇳🇴 挪威｜Norway
      - 🇲🇦 卡萨布兰卡｜Morocco
      - 🇦🇿 阿塞拜疆｜Azerbaijan
      - 🇷🇴 罗马尼亚｜Romania
      - 🇳🇬 尼日利亚｜Nigeria
      - 🇨🇴 哥伦比亚｜Colombia
      - 🇰🇿 哈萨克斯坦｜Kazakhstan
      - 🇰🇬 吉尔吉斯斯坦｜Kyrgyzstan
rule-providers:
  LocalAreaNetwork:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/LocalAreaNetwork.list
    path: ./rules/LocalAreaNetwork.yaml
  BanAD:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/BanAD.list
    path: ./rules/BanAD.yaml
  BanProgramAD:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/BanProgramAD.list
    path: ./rules/BanProgramAD.yaml
  GoogleCN:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/GoogleCN.list
    path: ./rules/GoogleCN.yaml
  SteamCN:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/Ruleset/SteamCN.list
    path: ./rules/SteamCN.yaml
  Microsoft:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/Microsoft.list
    path: ./rules/Microsoft.yaml
  Apple:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/Apple.list
    path: ./rules/Apple.yaml
  ProxyMedia:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/ProxyMedia.list
    path: ./rules/ProxyMedia.yaml
  Telegram:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/Telegram.list
    path: ./rules/Telegram.yaml
  ProxyLite:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/ProxyLite.list
    path: ./rules/ProxyLite.yaml
  ChinaDomain:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/ChinaDomain.list
    path: ./rules/ChinaDomain.yaml
  ChinaCompanyIp:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/ChinaCompanyIp.list
    path: ./rules/ChinaCompanyIp.yaml
rules:
  - DOMAIN-SUFFIX,nodebuf.com,🚀 节点选择
  - RULE-SET,LocalAreaNetwork,🎯 全球直连
  - RULE-SET,BanAD,🛑 全球拦截
  - RULE-SET,BanProgramAD,🍃 应用净化
  - RULE-SET,GoogleCN,🎯 全球直连
  - RULE-SET,SteamCN,🎯 全球直连
  - RULE-SET,Microsoft,Ⓜ️ 微软服务
  - RULE-SET,Apple,🍎 苹果服务
  - RULE-SET,ProxyMedia,🌍 国外媒体
  - RULE-SET,Telegram,📲 电报信息
  - RULE-SET,ProxyLite,🚀 节点选择
  - RULE-SET,ChinaDomain,🎯 全球直连
  - RULE-SET,ChinaCompanyIp,🎯 全球直连
  - GEOIP,CN,🎯 全球直连
  - MATCH,🐟 漏网之鱼
