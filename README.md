client
dev tun
proto udp
remote edge-eu-starting-point-1-dhcp.hackthebox.eu 1337
resolv-retry infinite
nobind
persist-key
persist-tun
remote-cert-tls server
comp-lzo
verb 3
data-ciphers-fallback AES-128-CBC
data-ciphers AES-256-CBC:AES-256-CFB:AES-256-CFB1:AES-256-CFB8:AES-256-OFB:AES-256-GCM
tls-cipher "DEFAULT:@SECLEVEL=0"
auth SHA256
key-direction 1
<ca>
-----BEGIN CERTIFICATE-----
MIIDSDCCAjCgAwIBAgIUQShMroYO95avGUV+HFvOEghuMv8wDQYJKoZIhvcNAQEL
BQAwFTETMBEGA1UEAwwKSGFja1RoZUJveDAeFw0yMTEwMjExMTA1NDdaFw0zMTEw
MTkxMTA1NDdaMBUxEzARBgNVBAMMCkhhY2tUaGVCb3gwggEiMA0GCSqGSIb3DQEB
AQUAA4IBDwAwggEKAoIBAQCedIbjiIrL7EgTpvrMCfdYr7lDs5+x3bg4E5m/ucTw
MCztOmf+VKj+zocWviyR6N5jR5L2nUoLi3vz2+/Ic6zZHmvHl9kVsAg+qFQ3DHtL
rKrKc8k6G9DMhNaeJLfADEUZCMBpKpjB1EvdK7uTpx7u2q0sT9uzDYCTxHZvAna0
Ek0YCNo3mh7UoWCiSIxF7/h8xcgUmL4bXNLoEka6xHtYPnIYxakzwDzlhB9Ldgyt
u2z34QJ3uWtT/2E/JY4X964cnXmhtdCpppZ5us6CrslzUJyihNI7YefgW6VKAoQ6
cJ+vgoqwyu132p1DyTqMii6eBG82P7Rp2+yj1gYZeA4RAgMBAAGjgY8wgYwwHQYD
VR0OBBYEFBqDv0nbZS6Iru4cukfsXB8yF3h8MFAGA1UdIwRJMEeAFBqDv0nbZS6I
ru4cukfsXB8yF3h8oRmkFzAVMRMwEQYDVQQDDApIYWNrVGhlQm94ghRBKEyuhg73
lq8ZRX4cW84SCG4y/zAMBgNVHRMEBTADAQH/MAsGA1UdDwQEAwIBBjANBgkqhkiG
9w0BAQsFAAOCAQEAB1LXupSk4WctIuudC4yCwEgvjNTmwH6j129XUT3miWNwvqg4
I9Hq5hjlbVkeAV0kN37BJu9ORc9eInviFvVPq80WTxWYj6lmfsqHsfgeabEwtlzL
lviuXjPdB02hsGHk7CaUcfZ+GkkDGM0YwAJnY66atlDfQNIevz2DZzetQr/cdGmK
wFIHlXJl3lzAJL5gVKraLhXulO4ZnEGHH1l999a/G1qFU2x8tvpJ1uS+mIrEJE8v
QIyy8gGSt3+L9bcIKguiGUQEaE88w5p9kFkzNuig5rpGeA0C8sAC8+QAlLTykd3Q
q5QVkoKu0HRdwQcmPlVcD1+512IvwJDDtl9FDA==
-----END CERTIFICATE-----
</ca>
<cert>
Certificate:
    Data:
        Version: 3 (0x2)
        Serial Number:
            65:ad:62:08:44:ff:2e:6f:d4:cf:b7:31:74:2c:e5:0d
        Signature Algorithm: sha256WithRSAEncryption
        Issuer: CN=HackTheBox
        Validity
            Not Before: Jul 19 02:08:57 2022 GMT
            Not After : Jul  3 02:08:57 2025 GMT
        Subject: CN=itzkiddjay
        Subject Public Key Info:
            Public Key Algorithm: rsaEncryption
                RSA Public-Key: (2048 bit)
                Modulus:
                    00:eb:9c:5a:23:0d:35:ef:2f:0e:18:66:7f:2d:e7:
                    b5:65:30:ca:37:21:50:8a:43:f4:ec:7c:25:44:b1:
                    02:d1:65:9c:23:9f:80:03:26:4a:58:2b:b4:da:09:
                    69:18:0d:9f:71:50:66:0e:18:d1:88:7a:5e:ec:68:
                    f0:3b:4f:d9:77:ca:59:28:dc:4e:76:cb:80:8f:dd:
                    a6:c5:2c:af:f5:a1:a3:01:4e:01:d6:f5:f6:08:56:
                    aa:1e:95:80:59:d5:34:8e:ad:2d:ca:2c:6c:34:c5:
                    c7:0f:72:97:13:5b:d7:5c:81:83:6f:a8:9d:e4:06:
                    fb:e7:04:90:2e:2e:93:4e:6b:87:32:80:90:ce:42:
                    34:d0:4c:57:ac:0c:f3:bd:59:50:82:4b:e1:2e:23:
                    69:f1:f8:56:62:8c:e7:27:0c:14:e3:3c:4b:52:56:
                    a3:6d:4c:36:92:3f:44:0e:bb:05:b0:cc:11:89:57:
                    3a:0f:8d:7e:c7:ad:44:4f:a7:23:a7:cf:88:49:bb:
                    4b:a4:8c:42:28:b2:3e:0c:a4:b7:ac:7b:23:e1:fd:
                    55:54:e0:3d:3d:73:47:19:97:28:01:f9:ec:58:8f:
                    74:b8:d2:28:b3:72:98:8e:b6:27:0b:90:ed:b7:57:
                    bb:08:4f:cb:b2:e8:fe:94:53:69:92:53:6b:e6:e8:
                    1e:dd
                Exponent: 65537 (0x10001)
        X509v3 extensions:
            X509v3 Basic Constraints: 
                CA:FALSE
            X509v3 Subject Key Identifier: 
                B2:53:61:2E:53:8A:F5:B9:9C:12:3D:C6:F8:D7:BD:2D:F8:39:24:11
            X509v3 Authority Key Identifier: 
                keyid:1A:83:BF:49:DB:65:2E:88:AE:EE:1C:BA:47:EC:5C:1F:32:17:78:7C
                DirName:/CN=HackTheBox
                serial:41:28:4C:AE:86:0E:F7:96:AF:19:45:7E:1C:5B:CE:12:08:6E:32:FF

            X509v3 Extended Key Usage: 
                TLS Web Client Authentication
            X509v3 Key Usage: 
                Digital Signature
    Signature Algorithm: sha256WithRSAEncryption
         06:81:ff:dd:0c:09:b0:1a:a1:78:ed:ee:f1:f7:53:17:4a:e0:
         91:14:e2:8a:09:91:cd:72:85:2d:84:75:14:be:da:3c:01:e8:
         4d:66:8c:9c:21:a2:6d:b6:bc:1d:41:62:cf:38:b2:bc:b0:a8:
         a4:27:ba:9b:7c:c1:3e:20:38:99:9b:0b:48:90:8e:56:28:01:
         3d:8f:3c:38:9a:95:a5:9d:6c:49:46:7f:20:ec:7c:a8:d4:52:
         a4:b6:23:a9:8e:53:cd:41:48:b0:67:83:25:e2:77:c7:8b:17:
         00:da:c7:f7:df:5e:41:ce:72:94:d0:d7:ce:b8:f7:e2:97:29:
         b1:80:e4:b4:4c:1e:d7:03:27:bc:56:20:9b:dc:e0:26:5b:4f:
         f5:d3:60:09:f1:be:5f:66:b8:01:98:fa:9a:6b:4d:9c:08:dc:
         d9:23:60:6b:66:0c:b9:07:b7:0d:7b:99:b3:d4:63:5c:c9:f2:
         fc:23:53:58:e5:4a:29:7d:0d:e2:f7:78:1b:70:08:00:fc:8e:
         d7:5c:0c:63:d5:54:d9:68:99:71:0a:d5:33:f1:ab:f1:9b:9b:
         80:02:bd:4a:4a:81:22:13:58:4d:bd:8c:a6:a5:7b:42:1a:c7:
         85:f1:7f:a1:2c:f6:7a:5f:3c:29:92:79:3e:55:03:9b:af:18:
         be:76:98:6f
-----BEGIN CERTIFICATE-----
MIIDVjCCAj6gAwIBAgIQZa1iCET/Lm/Uz7cxdCzlDTANBgkqhkiG9w0BAQsFADAV
MRMwEQYDVQQDDApIYWNrVGhlQm94MB4XDTIyMDcxOTAyMDg1N1oXDTI1MDcwMzAy
MDg1N1owFTETMBEGA1UEAwwKaXR6a2lkZGpheTCCASIwDQYJKoZIhvcNAQEBBQAD
ggEPADCCAQoCggEBAOucWiMNNe8vDhhmfy3ntWUwyjchUIpD9Ox8JUSxAtFlnCOf
gAMmSlgrtNoJaRgNn3FQZg4Y0Yh6Xuxo8DtP2XfKWSjcTnbLgI/dpsUsr/WhowFO
Adb19ghWqh6VgFnVNI6tLcosbDTFxw9ylxNb11yBg2+oneQG++cEkC4uk05rhzKA
kM5CNNBMV6wM871ZUIJL4S4jafH4VmKM5ycMFOM8S1JWo21MNpI/RA67BbDMEYlX
Og+NfsetRE+nI6fPiEm7S6SMQiiyPgykt6x7I+H9VVTgPT1zRxmXKAH57FiPdLjS
KLNymI62JwuQ7bdXuwhPy7Lo/pRTaZJTa+boHt0CAwEAAaOBoTCBnjAJBgNVHRME
AjAAMB0GA1UdDgQWBBSyU2EuU4r1uZwSPcb4170t+DkkETBQBgNVHSMESTBHgBQa
g79J22UuiK7uHLpH7FwfMhd4fKEZpBcwFTETMBEGA1UEAwwKSGFja1RoZUJveIIU
QShMroYO95avGUV+HFvOEghuMv8wEwYDVR0lBAwwCgYIKwYBBQUHAwIwCwYDVR0P
BAQDAgeAMA0GCSqGSIb3DQEBCwUAA4IBAQAGgf/dDAmwGqF47e7x91MXSuCRFOKK
CZHNcoUthHUUvto8AehNZoycIaJttrwdQWLPOLK8sKikJ7qbfME+IDiZmwtIkI5W
KAE9jzw4mpWlnWxJRn8g7Hyo1FKktiOpjlPNQUiwZ4Ml4nfHixcA2sf3315BznKU
0NfOuPfilymxgOS0TB7XAye8ViCb3OAmW0/102AJ8b5fZrgBmPqaa02cCNzZI2Br
Zgy5B7cNe5mz1GNcyfL8I1NY5UopfQ3i93gbcAgA/I7XXAxj1VTZaJlxCtUz8avx
m5uAAr1KSoEiE1hNvYympXtCGseF8X+hLPZ6Xzwpknk+VQObrxi+dphv
-----END CERTIFICATE-----
</cert>
<key>
-----BEGIN PRIVATE KEY-----
MIIEvQIBADANBgkqhkiG9w0BAQEFAASCBKcwggSjAgEAAoIBAQDrnFojDTXvLw4Y
Zn8t57VlMMo3IVCKQ/TsfCVEsQLRZZwjn4ADJkpYK7TaCWkYDZ9xUGYOGNGIel7s
aPA7T9l3ylko3E52y4CP3abFLK/1oaMBTgHW9fYIVqoelYBZ1TSOrS3KLGw0xccP
cpcTW9dcgYNvqJ3kBvvnBJAuLpNOa4cygJDOQjTQTFesDPO9WVCCS+EuI2nx+FZi
jOcnDBTjPEtSVqNtTDaSP0QOuwWwzBGJVzoPjX7HrURPpyOnz4hJu0ukjEIosj4M
pLeseyPh/VVU4D09c0cZlygB+exYj3S40iizcpiOticLkO23V7sIT8uy6P6UU2mS
U2vm6B7dAgMBAAECggEBANEfSJ3d5uYyFMexieZ7x/RV1tYR+sOOR8Dy+705g6/K
CUlRE7U38jrKKE5yldYkmUVhQAP5IVmKi+A30CpE2FfLwVFUIUytmaGX8aMG4/MY
EW9iBp3+V+7UxVA6D98sLucIbSEKRsycUu+yHMew97kCt1+PAP1Y+ZL16Ockrdim
Qhn2KMunFvajUPU0bykst76d1hYmfZsbFQvd0KtsBM/Hbnx8aOfQNagipLRwmKc2
XO8WUEERkg2gXXE2nePncuY6PmCQ/P9EV9tAK8SPArHW7+U129CSkmZ0Y8Zk11QX
HjPZqj+qjrgLsgPQXJAf3A9Q7UiWFNhZNGftHlZmusECgYEA+us90Ei5cE9N2LsO
lRxqHOPfMLmYko21V2YSSx0RdPZ/qEVfK6jC9sZsViukcd9Nz0d4HyzCC7B0vgyg
BVQQ74t2BlEkJIxwIkcJdvK3r+7YAI1rP/9YXdL1RRduJf1BzwQTZIoX8VGuYniB
Xk9ZxHdR1NTh5+0WycibChWbCg0CgYEA8GHA4WgPu9tv7aC8XwADckqlKNAh/mYz
EpoCAwVHtyiKYq6z6CZfos7EUZhWHkKugYlwYSiu0htVeCZXjxYjZJa6LO17qGuU
/uzijqjBNRLkQnUN57uwglUskZiVgtC13YhQRmuDxjSTAodwyOTZn5/bzAWHeL+9
vsvvnzV1RBECgYAErrUlmOXVAbXbMIpyH+ifB2WX3C7LtVdH/UCkJDO6Mgtp0XmY
L/sLbeKBrSjRczBZiOTl+Aja/P0Auu2Vi98RCVI3hfYdtH03NoonrRneb5+aSwlQ
VWyJu7EWC/zjOpmqylGuU6FkwHh3n/YSE3sCXpOpXBunH1aIh3TVOFf/VQKBgEBL
VSS1CahMbCaZ3Ghof4N9VamR6dW6jiSGjs0yB1mE/WahpbsNMH1CYp4UacxUN4qs
MSO7lu7ZosWtM7Qwzqyj6A4GQxHsHIEG6R4RIwRIFkd0OZDm0bI6h941ep/vpQUo
5ZfAQBGulDeT9GW3WEHqpwZt4Cs61cyHjYL+8GuRAoGAGTtQww3gQZlKgoHLerQN
2KeVQuLc4WiglXs2U2PHzEifenWZR8vGYHvEATyE/kLrAiR2ksRX9nVmLGmglYTs
czhq9T3KepJ8uTLtT6qVYi10vX1Ji7YgfHcWvizbug88+JrLr0AQU0a7rh9Yxa+R
+vP4tZ0Eyzu0/oM7zDrnaYw=
-----END PRIVATE KEY-----
</key>
<tls-auth>
#
# 2048 bit OpenVPN static key
#
-----BEGIN OpenVPN Static key V1-----
0c2366d5bc34cc2cfced9f8ed08b94e3
7e2be07c258c3de51eefa39e8cc4a2dc
b822000c24c3d5267dc35cc097e36c43
cb8f570d8a42fbfd41b9c3e2230bf1b1
4d0bb9af2722356ea49bd66e19fdfbc3
554fcc530d0ef5a2484f1d63a6da1a3a
d5bbbaa32f27a51e216711c4fb104f26
a0d7a3db0c1ad27a216c6e31637a2995
a59060bf9ee947b89fbfc34570f5bf3b
4af9818f8de979da6205cdcbefbce4a4
995a0b7726e67c095e0d567f6a2de413
8f07d8d32894767f709646913f9d674f
c89dee94440ec0f3bc13f0bbab5502a3
6b59db08892ae408283001a083f78c11
d5d23a051fe1e5ef1fd8dc9c387f85ff
584ffdd15ee63e6640c7782151498019
-----END OpenVPN Static key V1-----
</tls-auth>
