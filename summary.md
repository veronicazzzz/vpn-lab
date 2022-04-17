--------------------

# Отчёт drive/MyDrive/ipsec.pcap

## Проверка наличия vpn трафика:
Protocol and data for drive/MyDrive/ipsec.pcap:
|    | application_name   | application_category_name   |   bidirectional_bytes |
|---:|:-------------------|:----------------------------|----------------------:|
|  0 | DNS                | Network                     |                  3287 |
|  1 | DNS.Google         | Advertisement               |                 21613 |
|  2 | DNS.Google         | Cloud                       |                   890 |
|  3 | DNS.Google         | Web                         |                 55094 |
|  4 | DNS.GoogleServices | Web                         |                 11897 |
|  5 | DNS.YouTube        | Media                       |                 84112 |
|  6 | ICMP               | Network                     |                  1962 |
|  7 | IPsec              | VPN                         |              51865351 |
|  8 | LLMNR              | Network                     |                   888 |
|  9 | MDNS               | Network                     |                  1920 |
| 10 | NetBIOS            | System                      |                  4742 |

## Информация по src_ip, dst_ip и application_name:

|                                                          |   bidirectional_packets |   bidirectional_bytes | application_category_name   |
|:---------------------------------------------------------|------------------------:|----------------------:|:----------------------------|
| ('192.168.75.1', '192.168.75.2', 'NetBIOS')              |                       4 |                   440 | System                      |
| ('192.168.75.1', '224.0.0.251', 'MDNS')                  |                      12 |                   840 | Network                     |
| ('192.168.75.1', '224.0.0.252', 'LLMNR')                 |                       2 |                   128 | Network                     |
| ('192.168.75.128', '159.203.14.174', 'IPsec')            |                   46355 |              51865351 | VPN                         |
| ('192.168.75.128', '192.168.75.2', 'DNS')                |                       2 |                   606 | Network                     |
| ('192.168.75.128', '192.168.75.2', 'DNS.Google')         |                       2 |                   434 | Web                         |
| ('192.168.75.128', '192.168.75.2', 'DNS.GoogleServices') |                       2 |                   431 | Web                         |
| ('192.168.75.128', '192.168.75.2', 'DNS.YouTube')        |                       2 |                   475 | Media                       |
| ('192.168.75.128', '192.168.75.2', 'NetBIOS')            |                      15 |                  1542 | System                      |
| ('192.168.75.128', '192.168.75.255', 'NetBIOS')          |                      30 |                  2760 | System                      |
| ('192.168.75.2', '192.168.75.128', 'ICMP')               |                      15 |                  1962 | Network                     |
| ('fe80::c43b:78f0:882b:ca43', 'ff02::1:3', 'LLMNR')      |                       2 |                   168 | Network                     |
| ('fe80::c43b:78f0:882b:ca43', 'ff02::fb', 'MDNS')        |                      12 |                  1080 | Network                     |

## Начало и конец захвата трафика:

Start date:2022-04-11 08:20:33
End date:2022-04-11 08:22:07

## Вывод полезной информации:

|                                          |   src2dst_duration_ms |
|:-----------------------------------------|----------------------:|
| ('192.168.75.1', 'LLMNR')                |                 418   |
| ('192.168.75.1', 'MDNS')                 |                4008   |
| ('192.168.75.1', 'NetBIOS')              |                7304   |
| ('192.168.75.128', 'DNS')                |                   0   |
| ('192.168.75.128', 'DNS.Google')         |                   0   |
| ('192.168.75.128', 'DNS.GoogleServices') |                   0   |
| ('192.168.75.128', 'DNS.YouTube')        |                   0   |
| ('192.168.75.128', 'IPsec')              |               87402   |
| ('192.168.75.128', 'NetBIOS')            |               55142.5 |
| ('192.168.75.2', 'ICMP')                 |               77087   |
| ('fe80::c43b:78f0:882b:ca43', 'LLMNR')   |                 418   |
| ('fe80::c43b:78f0:882b:ca43', 'MDNS')    |                4008   |

--------------------

# Отчёт drive/MyDrive/ipsec2.pcap

## Проверка наличия vpn трафика:
Protocol and data for drive/MyDrive/ipsec2.pcap:
|    | application_name   | application_category_name   |   bidirectional_bytes |
|---:|:-------------------|:----------------------------|----------------------:|
|  0 | DHCP               | Network                     |                   700 |
|  1 | DNS                | Advertisement               |                  9947 |
|  2 | DNS                | Media                       |                 10152 |
|  3 | DNS                | Network                     |                160121 |
|  4 | DNS.Amazon         | Web                         |                  3108 |
|  5 | DNS.AmazonAWS      | Cloud                       |                  4946 |
|  6 | DNS.AmazonVideo    | Video                       |                  3061 |
|  7 | DNS.AppleiTunes    | Streaming                   |                   627 |
|  8 | DNS.Facebook       | SocialNetwork               |                  3500 |
|  9 | DNS.Github         | Collaborative               |                 46298 |
| 10 | DNS.Google         | Advertisement               |                 64811 |
| 11 | DNS.Google         | Web                         |                 92381 |
| 12 | DNS.GoogleServices | Web                         |                 16484 |
| 13 | DNS.LinkedIn       | SocialNetwork               |                 26228 |
| 14 | DNS.Microsoft      | Cloud                       |                 10718 |
| 15 | DNS.Wikipedia      | Web                         |                 12211 |
| 16 | DNS.WindowsUpdate  | SoftwareUpdate              |                  3260 |
| 17 | DNS.YouTube        | Media                       |                 72259 |
| 18 | DNS.eBay           | Media                       |                  5420 |
| 19 | DNS.eBay           | Shopping                    |                 48531 |
| 20 | HTTP               | Web                         |                   108 |
| 21 | ICMP               | Network                     |                  3726 |
| 22 | ICMPV6             | Network                     |                   450 |
| 23 | IGMP               | Network                     |                   270 |
| 24 | IPsec              | VPN                         |             124681422 |
| 25 | MDNS               | Network                     |                   880 |
| 26 | NetBIOS            | System                      |                  4070 |
| 27 | SSDP               | System                      |                  1074 |
| 28 | TLS                | Web                         |                    54 |
| 29 | WSD                | Network                     |                  9912 |

## Информация по src_ip, dst_ip и application_name:

|                                                          |   bidirectional_packets |   bidirectional_bytes | application_category_name   |
|:---------------------------------------------------------|------------------------:|----------------------:|:----------------------------|
| ('178.18.232.225', '192.168.75.128', 'HTTP')             |                       1 |                    54 | Web                         |
| ('192.168.75.1', '192.168.75.2', 'NetBIOS')              |                      10 |                  1100 | System                      |
| ('192.168.75.1', '192.168.75.254', 'DHCP')               |                       2 |                   700 | Network                     |
| ('192.168.75.1', '224.0.0.22', 'IGMP')                   |                       5 |                   270 | Network                     |
| ('192.168.75.1', '224.0.0.251', 'MDNS')                  |                       4 |                   400 | Network                     |
| ('192.168.75.1', '239.255.255.250', 'SSDP')              |                       6 |                  1074 | System                      |
| ('192.168.75.1', '239.255.255.250', 'WSD')               |                       7 |                  4886 | Network                     |
| ('192.168.75.128', '159.203.14.174', 'IPsec')            |                  132631 |             124681422 | VPN                         |
| ('192.168.75.128', '192.168.75.2', 'DNS')                |                       4 |                  1212 | Network                     |
| ('192.168.75.128', '192.168.75.2', 'DNS.Amazon')         |                       4 |                   762 | Web                         |
| ('192.168.75.128', '192.168.75.2', 'DNS.AmazonAWS')      |                       2 |                   575 | Cloud                       |
| ('192.168.75.128', '192.168.75.2', 'DNS.AmazonVideo')    |                       4 |                   898 | Video                       |
| ('192.168.75.128', '192.168.75.2', 'DNS.AppleiTunes')    |                       2 |                   627 | Streaming                   |
| ('192.168.75.128', '192.168.75.2', 'DNS.Facebook')       |                       5 |                   380 | SocialNetwork               |
| ('192.168.75.128', '192.168.75.2', 'DNS.Github')         |                       4 |                  1198 | Collaborative               |
| ('192.168.75.128', '192.168.75.2', 'DNS.Google')         |                       2 |                   545 | Advertisement               |
| ('192.168.75.128', '192.168.75.2', 'DNS.GoogleServices') |                       2 |                   431 | Web                         |
| ('192.168.75.128', '192.168.75.2', 'DNS.LinkedIn')       |                       2 |                   300 | SocialNetwork               |
| ('192.168.75.128', '192.168.75.2', 'DNS.Microsoft')      |                       2 |                   242 | Cloud                       |
| ('192.168.75.128', '192.168.75.2', 'DNS.Wikipedia')      |                       2 |                   299 | Web                         |
| ('192.168.75.128', '192.168.75.2', 'DNS.WindowsUpdate')  |                       2 |                   420 | SoftwareUpdate              |
| ('192.168.75.128', '192.168.75.2', 'DNS.YouTube')        |                       2 |                   475 | Media                       |
| ('192.168.75.128', '192.168.75.2', 'DNS.eBay')           |                       4 |                  1128 | Shopping                    |
| ('192.168.75.128', '192.168.75.2', 'NetBIOS')            |                      27 |                  2970 | System                      |
| ('192.168.75.2', '192.168.75.128', 'ICMP')               |                      27 |                  3726 | Network                     |
| ('23.218.9.177', '192.168.75.128', 'TLS')                |                       1 |                    54 | Web                         |
| ('23.218.9.249', '192.168.75.128', 'HTTP')               |                       1 |                    54 | Web                         |
| ('fe80::c43b:78f0:882b:ca43', 'ff02::16', 'ICMPV6')      |                       5 |                   450 | Network                     |
| ('fe80::c43b:78f0:882b:ca43', 'ff02::c', 'WSD')          |                       7 |                  5026 | Network                     |
| ('fe80::c43b:78f0:882b:ca43', 'ff02::fb', 'MDNS')        |                       4 |                   480 | Network                     |

## Начало и конец захвата трафика:

Start date:2022-04-11 08:54:13
End date:2022-04-11 09:00:34

## Вывод полезной информации:

|                                          |   src2dst_duration_ms |
|:-----------------------------------------|----------------------:|
| ('178.18.232.225', 'HTTP')               |                     0 |
| ('192.168.75.1', 'DHCP')                 |                     0 |
| ('192.168.75.1', 'IGMP')                 |                   281 |
| ('192.168.75.1', 'MDNS')                 |                     2 |
| ('192.168.75.1', 'NetBIOS')              |                 61466 |
| ('192.168.75.1', 'SSDP')                 |                 15053 |
| ('192.168.75.1', 'WSD')                  |                  7007 |
| ('192.168.75.128', 'DNS')                |                     0 |
| ('192.168.75.128', 'DNS.Amazon')         |                    95 |
| ('192.168.75.128', 'DNS.AmazonAWS')      |                     0 |
| ('192.168.75.128', 'DNS.AmazonVideo')    |                   102 |
| ('192.168.75.128', 'DNS.AppleiTunes')    |                     0 |
| ('192.168.75.128', 'DNS.Facebook')       |                  7119 |
| ('192.168.75.128', 'DNS.Github')         |                     0 |
| ('192.168.75.128', 'DNS.Google')         |                     0 |
| ('192.168.75.128', 'DNS.GoogleServices') |                     0 |
| ('192.168.75.128', 'DNS.LinkedIn')       |                     0 |
| ('192.168.75.128', 'DNS.Microsoft')      |                     0 |
| ('192.168.75.128', 'DNS.Wikipedia')      |                     0 |
| ('192.168.75.128', 'DNS.WindowsUpdate')  |                     0 |
| ('192.168.75.128', 'DNS.YouTube')        |                     0 |
| ('192.168.75.128', 'DNS.eBay')           |                     0 |
| ('192.168.75.128', 'IPsec')              |                380643 |
| ('192.168.75.128', 'NetBIOS')            |                252015 |
| ('192.168.75.2', 'ICMP')                 |                252015 |
| ('23.218.9.177', 'TLS')                  |                     0 |
| ('23.218.9.249', 'HTTP')                 |                     0 |
| ('fe80::c43b:78f0:882b:ca43', 'ICMPV6')  |                   282 |
| ('fe80::c43b:78f0:882b:ca43', 'MDNS')    |                     1 |
| ('fe80::c43b:78f0:882b:ca43', 'WSD')     |                  6048 |

--------------------

# Отчёт drive/MyDrive/wireguard.pcap

## Проверка наличия vpn трафика:
Protocol and data for drive/MyDrive/wireguard.pcap:
|    | application_name   | application_category_name   |   bidirectional_bytes |
|---:|:-------------------|:----------------------------|----------------------:|
|  0 | NetBIOS            | System                      |                   110 |
|  1 | TLS.AmazonAWS      | Cloud                       |                  2412 |
|  2 | TLS.Azure          | Cloud                       |                  2334 |
|  3 | WireGuard          | VPN                         |              46971392 |

## Информация по src_ip, dst_ip и application_name:

|                                                     |   bidirectional_packets |   bidirectional_bytes | application_category_name   |
|:----------------------------------------------------|------------------------:|----------------------:|:----------------------------|
| ('192.168.75.1', '192.168.75.2', 'NetBIOS')         |                       1 |                   110 | System                      |
| ('192.168.75.128', '174.138.27.251', 'WireGuard')   |                   40360 |              46971392 | VPN                         |
| ('20.82.250.189', '192.168.75.128', 'TLS.Azure')    |                       3 |                  2334 | Cloud                       |
| ('54.192.99.45', '192.168.75.128', 'TLS.AmazonAWS') |                       3 |                  2412 | Cloud                       |

## Начало и конец захвата трафика:

Start date:2022-04-11 08:28:08
End date:2022-04-11 08:29:21

## Вывод полезной информации:

|                                   |   src2dst_duration_ms |
|:----------------------------------|----------------------:|
| ('192.168.75.1', 'NetBIOS')       |                     0 |
| ('192.168.75.128', 'WireGuard')   |                 72645 |
| ('20.82.250.189', 'TLS.Azure')    |                 48011 |
| ('54.192.99.45', 'TLS.AmazonAWS') |                 48011 |

--------------------

# Отчёт drive/MyDrive/wireguard2.pcap

## Проверка наличия vpn трафика:
Protocol and data for drive/MyDrive/wireguard2.pcap:
|    | application_name   | application_category_name   |   bidirectional_bytes |
|---:|:-------------------|:----------------------------|----------------------:|
|  0 | NetBIOS            | System                      |                   770 |
|  1 | TLS                | Web                         |                    54 |
|  2 | TLS.Telegram       | Chat                        |                   648 |
|  3 | WSD                | Network                     |                  9912 |
|  4 | WireGuard          | VPN                         |              89326158 |

## Информация по src_ip, dst_ip и application_name:

|                                                      |   bidirectional_packets |   bidirectional_bytes | application_category_name   |
|:-----------------------------------------------------|------------------------:|----------------------:|:----------------------------|
| ('149.154.167.41', '192.168.75.128', 'TLS.Telegram') |                      11 |                   594 | Chat                        |
| ('192.168.75.1', '192.168.75.2', 'NetBIOS')          |                       3 |                   330 | System                      |
| ('192.168.75.1', '239.255.255.250', 'WSD')           |                       7 |                  4886 | Network                     |
| ('192.168.75.128', '174.138.27.251', 'WireGuard')    |                   90419 |              89326158 | VPN                         |
| ('93.158.134.119', '192.168.75.128', 'TLS')          |                       1 |                    54 | Web                         |
| ('fe80::c43b:78f0:882b:ca43', 'ff02::c', 'WSD')      |                       7 |                  5026 | Network                     |

## Начало и конец захвата трафика:

Start date:2022-04-11 09:02:49
End date:2022-04-11 09:08:17

## Вывод полезной информации:

|                                      |   src2dst_duration_ms |
|:-------------------------------------|----------------------:|
| ('149.154.167.41', 'TLS.Telegram')   |               63675.5 |
| ('192.168.75.1', 'NetBIOS')          |                7121.5 |
| ('192.168.75.1', 'WSD')              |                7171   |
| ('192.168.75.128', 'WireGuard')      |              327480   |
| ('93.158.134.119', 'TLS')            |                   0   |
| ('fe80::c43b:78f0:882b:ca43', 'WSD') |                6574   |

--------------------

# Отчёт drive/MyDrive/openvpn.pcap

## Проверка наличия vpn трафика:
Protocol and data for drive/MyDrive/openvpn.pcap:
|    | application_name   | application_category_name   |   bidirectional_bytes |
|---:|:-------------------|:----------------------------|----------------------:|
|  0 | HTTP.Google        | Web                         |                   870 |
|  1 | HTTP.GoogleCloud   | Cloud                       |                  1904 |
|  2 | ICMP               | Network                     |                  1854 |
|  3 | NetBIOS            | System                      |                 10412 |
|  4 | OpenVPN            | VPN                         |              94199721 |
|  5 | TLS                | Web                         |                  2004 |
|  6 | TLS.AmazonAWS      | Cloud                       |                  5930 |
|  7 | TLS.Azure          | Cloud                       |                   778 |
|  8 | TLS.Cloudflare     | Web                         |                  5874 |
|  9 | TLS.Google         | Web                         |                582947 |
| 10 | TLS.Microsoft      | Cloud                       |                  8087 |

## Информация по src_ip, dst_ip и application_name:

|                                                         |   bidirectional_packets |   bidirectional_bytes | application_category_name   |
|:--------------------------------------------------------|------------------------:|----------------------:|:----------------------------|
| ('157.245.51.246', '192.168.75.128', 'OpenVPN')         |                   89393 |              94199721 | VPN                         |
| ('173.194.73.119', '192.168.75.128', 'TLS.Google')      |                      15 |                  2207 | Web                         |
| ('188.114.99.128', '192.168.75.128', 'TLS.Cloudflare')  |                      10 |                  1170 | Web                         |
| ('192.168.75.128', '188.114.99.128', 'TLS.Cloudflare')  |                      64 |                  4704 | Web                         |
| ('192.168.75.128', '192.168.75.2', 'NetBIOS')           |                      19 |                  1856 | System                      |
| ('192.168.75.128', '192.168.75.255', 'NetBIOS')         |                      93 |                  8556 | System                      |
| ('192.168.75.128', '20.198.162.78', 'TLS.Microsoft')    |                      25 |                  8087 | Cloud                       |
| ('192.168.75.128', '212.188.15.15', 'TLS')              |                      18 |                  1002 | Web                         |
| ('192.168.75.128', '212.188.37.143', 'TLS')             |                      18 |                  1002 | Web                         |
| ('192.168.75.128', '34.107.221.82', 'HTTP.GoogleCloud') |                      18 |                   979 | Cloud                       |
| ('192.168.75.128', '64.233.161.94', 'HTTP.Google')      |                      16 |                   870 | Web                         |
| ('192.168.75.128', '64.233.165.198', 'TLS.Google')      |                    1003 |                573539 | Web                         |
| ('192.168.75.128', '74.125.10.26', 'TLS.Google')        |                      13 |                  4994 | Web                         |
| ('192.168.75.2', '192.168.75.128', 'ICMP')              |                      15 |                  1854 | Network                     |
| ('20.82.250.189', '192.168.75.128', 'TLS.Azure')        |                       1 |                   778 | Cloud                       |
| ('54.192.99.45', '192.168.75.128', 'TLS.AmazonAWS')     |                       8 |                  5930 | Cloud                       |

## Начало и конец захвата трафика:

Start date:2022-04-11 08:30:49
End date:2022-04-11 08:32:21

## Вывод полезной информации:

|                                        |   src2dst_duration_ms |
|:---------------------------------------|----------------------:|
| ('157.245.51.246', 'OpenVPN')          |               91821   |
| ('173.194.73.119', 'TLS.Google')       |               20333   |
| ('188.114.99.128', 'TLS.Cloudflare')   |               63340   |
| ('192.168.75.128', 'HTTP.Google')      |               54435   |
| ('192.168.75.128', 'HTTP.GoogleCloud') |               64155.5 |
| ('192.168.75.128', 'NetBIOS')          |               86015.5 |
| ('192.168.75.128', 'TLS')              |               54365   |
| ('192.168.75.128', 'TLS.Cloudflare')   |               86811   |
| ('192.168.75.128', 'TLS.Google')       |               44534   |
| ('192.168.75.128', 'TLS.Microsoft')    |                 764   |
| ('192.168.75.2', 'ICMP')               |               69424   |
| ('20.82.250.189', 'TLS.Azure')         |                   0   |
| ('54.192.99.45', 'TLS.AmazonAWS')      |               15319   |

--------------------

# Отчёт drive/MyDrive/openvpn2.pcap

## Проверка наличия vpn трафика:
Protocol and data for drive/MyDrive/openvpn2.pcap:
|    | application_name   | application_category_name   |   bidirectional_bytes |
|---:|:-------------------|:----------------------------|----------------------:|
|  0 | HTTP               | Web                         |                  1197 |
|  1 | HTTP.Google        | Web                         |                  1197 |
|  2 | HTTP.GoogleCloud   | Cloud                       |                  2612 |
|  3 | ICMP               | Network                     |                  3312 |
|  4 | NetBIOS            | System                      |                  3136 |
|  5 | OpenVPN            | VPN                         |             126757408 |
|  6 | SSDP               | System                      |                  3360 |
|  7 | TLS.AmazonAWS      | Cloud                       |                  9405 |
|  8 | TLS.Microsoft      | Cloud                       |                  8195 |
|  9 | TLS.Telegram       | Chat                        |                 87020 |
| 10 | WireGuard          | VPN                         |                  3538 |

## Информация по src_ip, dst_ip и application_name:

|                                                         |   bidirectional_packets |   bidirectional_bytes | application_category_name   |
|:--------------------------------------------------------|------------------------:|----------------------:|:----------------------------|
| ('157.245.51.246', '192.168.75.128', 'OpenVPN')         |                  136749 |             126757408 | VPN                         |
| ('174.138.27.251', '192.168.75.128', 'WireGuard')       |                       9 |                  3538 | VPN                         |
| ('192.168.0.1', '192.168.75.128', 'SSDP')               |                       1 |                   375 | System                      |
| ('192.168.75.1', '192.168.75.2', 'NetBIOS')             |                       1 |                   110 | System                      |
| ('192.168.75.128', '117.18.237.29', 'HTTP')             |                      22 |                  1197 | Web                         |
| ('192.168.75.128', '149.154.167.41', 'TLS.Telegram')    |                     283 |                 87020 | Chat                        |
| ('192.168.75.128', '192.168.75.2', 'NetBIOS')           |                      21 |                  2310 | System                      |
| ('192.168.75.128', '192.168.75.255', 'NetBIOS')         |                       3 |                   276 | System                      |
| ('192.168.75.128', '20.198.162.78', 'TLS.Microsoft')    |                      27 |                  8195 | Cloud                       |
| ('192.168.75.128', '239.255.255.250', 'SSDP')           |                       1 |                   179 | System                      |
| ('192.168.75.128', '34.107.221.82', 'HTTP.GoogleCloud') |                      24 |                  1306 | Cloud                       |
| ('192.168.75.128', '54.230.130.62', 'TLS.AmazonAWS')    |                     113 |                  8617 | Cloud                       |
| ('192.168.75.128', '74.125.24.94', 'HTTP.Google')       |                      22 |                  1197 | Web                         |
| ('192.168.75.2', '192.168.75.128', 'ICMP')              |                      24 |                  3312 | Network                     |
| ('35.162.162.226', '192.168.75.128', 'TLS.AmazonAWS')   |                      11 |                   788 | Cloud                       |

## Начало и конец захвата трафика:

Start date:2022-04-11 09:17:27
End date:2022-04-11 09:23:17

## Вывод полезной информации:

|                                        |   src2dst_duration_ms |
|:---------------------------------------|----------------------:|
| ('157.245.51.246', 'OpenVPN')          |              347914   |
| ('174.138.27.251', 'WireGuard')        |                8077   |
| ('192.168.0.1', 'SSDP')                |                  14   |
| ('192.168.75.1', 'NetBIOS')            |                3659.5 |
| ('192.168.75.128', 'HTTP')             |               84822   |
| ('192.168.75.128', 'HTTP.Google')      |               84579   |
| ('192.168.75.128', 'HTTP.GoogleCloud') |               94463.5 |
| ('192.168.75.128', 'NetBIOS')          |              125208   |
| ('192.168.75.128', 'SSDP')             |                   0   |
| ('192.168.75.128', 'TLS.AmazonAWS')    |              153444   |
| ('192.168.75.128', 'TLS.Microsoft')    |                 783   |
| ('192.168.75.128', 'TLS.Telegram')     |              341885   |
| ('192.168.75.2', 'ICMP')               |              257911   |
| ('35.162.162.226', 'TLS.AmazonAWS')    |                 664   |

--------------------

# Отчёт drive/MyDrive/novpn.pcap

## Проверка наличия vpn трафика:
No VPN traffic detected in drive/MyDrive/novpn.pcap, only ,TLS.AmazonAWS,HTTP,TLS.Google,TLS.Cloudflare,TLS,QUIC.Google,TLS.YouTube,QUIC.YouTube,ICMP,TLS.GoogleServices,NetBIOS,MDNS,LLMNR,QUIC.GoogleServices,HTTP.OCSP,HTTP.Google,HTTP.GoogleCloud,HTTP.Cloudflare,SSDP,DNS.DoH_DoT,WSD,DHCPV6,TLS.Azure,DNS.Microsoft,TLS.Microsoft,NetBIOS.SMBv1,DNS,TLS.GoogleCloud,HTTP.Azure,TLS.Wikipedia,TLS.LinkedIn,TLS.eBay,QUIC.GoogleCloud,TLS.Facebook,TLS.Github,TLS.Telegram,HTTP.Telegram

## Информация по src_ip, dst_ip и application_name:

|                                                            |   bidirectional_packets |   bidirectional_bytes | application_category_name   |
|:-----------------------------------------------------------|------------------------:|----------------------:|:----------------------------|
| ('108.177.14.198', '192.168.75.128', 'TLS.Google')         |                    1452 |                918779 | Web                         |
| ('131.253.33.200', '192.168.75.128', 'TLS.Azure')          |                       1 |                    54 | Cloud                       |
| ('142.250.74.162', '192.168.75.128', 'TLS.Google')         |                       5 |                   791 | Advertisement               |
| ('142.250.74.67', '192.168.75.128', 'TLS.Google')          |                      11 |                   634 | Web                         |
| ('188.114.99.128', '192.168.75.128', 'TLS.Cloudflare')     |                    7128 |               1373354 | Web                         |
| ('192.168.0.1', '192.168.75.128', 'SSDP')                  |                       2 |                   606 | System                      |
| ('192.168.75.1', '224.0.0.251', 'MDNS')                    |                      12 |                   840 | Network                     |
| ('192.168.75.1', '224.0.0.252', 'LLMNR')                   |                       2 |                   128 | Network                     |
| ('192.168.75.1', '239.255.255.250', 'SSDP')                |                       3 |                   537 | System                      |
| ('192.168.75.128', '104.119.240.68', 'TLS')                |                       5 |                   301 | Web                         |
| ('192.168.75.128', '104.16.85.20', 'TLS.Cloudflare')       |                      34 |                  9347 | Web                         |
| ('192.168.75.128', '108.156.13.26', 'HTTP.OCSP')           |                      26 |                  2888 | Network                     |
| ('192.168.75.128', '108.156.22.68', 'TLS.AmazonAWS')       |                      37 |                  9073 | Cloud                       |
| ('192.168.75.128', '108.177.14.198', 'QUIC.YouTube')       |                       6 |                  8394 | Media                       |
| ('192.168.75.128', '13.107.42.14', 'TLS.Azure')            |                       9 |                   530 | Cloud                       |
| ('192.168.75.128', '13.107.42.14', 'TLS.LinkedIn')         |                       6 |                   857 | SocialNetwork               |
| ('192.168.75.128', '140.82.112.22', 'TLS.Github')          |                     344 |                366770 | Collaborative               |
| ('192.168.75.128', '140.82.113.22', 'TLS.Github')          |                      23 |                  6601 | Collaborative               |
| ('192.168.75.128', '140.82.114.21', 'TLS.Github')          |                      90 |                 22537 | Collaborative               |
| ('192.168.75.128', '140.82.121.4', 'TLS.Github')           |                     274 |                274798 | Collaborative               |
| ('192.168.75.128', '140.82.121.5', 'TLS.Github')           |                     302 |                159074 | Collaborative               |
| ('192.168.75.128', '142.250.74.10', 'QUIC.GoogleServices') |                      13 |                 18187 | Web                         |
| ('192.168.75.128', '142.250.74.10', 'TLS.GoogleServices')  |                      36 |                  8282 | Web                         |
| ('192.168.75.128', '142.250.74.110', 'QUIC.Google')        |                       6 |                  8394 | Advertisement               |
| ('192.168.75.128', '142.250.74.110', 'TLS.Google')         |                      16 |                  1083 | Web                         |
| ('192.168.75.128', '142.250.74.130', 'QUIC.Google')        |                       2 |                  2798 | Web                         |
| ('192.168.75.128', '142.250.74.131', 'TLS.Google')         |                      35 |                 14563 | Web                         |
| ('192.168.75.128', '142.250.74.132', 'TLS.Google')         |                      60 |                 25105 | Web                         |
| ('192.168.75.128', '142.250.74.134', 'QUIC.Google')        |                      13 |                 18187 | Advertisement               |
| ('192.168.75.128', '142.250.74.134', 'TLS.Google')         |                       6 |                   857 | Advertisement               |
| ('192.168.75.128', '142.250.74.138', 'TLS.Google')         |                      16 |                  1083 | Web                         |
| ('192.168.75.128', '142.250.74.14', 'TLS.Google')          |                     150 |                 30369 | Advertisement               |
| ('192.168.75.128', '142.250.74.142', 'QUIC.Google')        |                      13 |                 18187 | Web                         |
| ('192.168.75.128', '142.250.74.142', 'TLS.Google')         |                      22 |                  6017 | Web                         |
| ('192.168.75.128', '142.250.74.162', 'QUIC.Google')        |                      13 |                 18187 | Web                         |
| ('192.168.75.128', '142.250.74.162', 'TLS.Google')         |                       6 |                   857 | Advertisement               |
| ('192.168.75.128', '142.250.74.163', 'HTTP.Google')        |                      27 |                  1470 | Web                         |
| ('192.168.75.128', '142.250.74.163', 'HTTP.OCSP')          |                      38 |                  5514 | Cloud                       |
| ('192.168.75.128', '142.250.74.163', 'TLS.Google')         |                      47 |                 16858 | Web                         |
| ('192.168.75.128', '142.250.74.2', 'QUIC.Google')          |                      13 |                 18187 | Advertisement               |
| ('192.168.75.128', '142.250.74.2', 'TLS.Google')           |                       6 |                   857 | Advertisement               |
| ('192.168.75.128', '142.250.74.2', 'TLS.GoogleServices')   |                       6 |                   857 | Web                         |
| ('192.168.75.128', '142.250.74.22', 'TLS.Google')          |                    4027 |               4787253 | Web                         |
| ('192.168.75.128', '142.250.74.22', 'TLS.YouTube')         |                     153 |                118417 | Media                       |
| ('192.168.75.128', '142.250.74.35', 'TLS.Google')          |                      31 |                  7590 | Web                         |
| ('192.168.75.128', '142.250.74.42', 'QUIC.GoogleServices') |                       4 |                  5596 | Web                         |
| ('192.168.75.128', '142.250.74.42', 'TLS.GoogleServices')  |                      28 |                  4841 | Web                         |
| ('192.168.75.128', '142.250.74.54', 'TLS.YouTube')         |                      84 |                 57418 | Media                       |
| ('192.168.75.128', '142.250.74.67', 'TLS.Google')          |                      16 |                  1083 | Web                         |
| ('192.168.75.128', '142.250.74.70', 'QUIC.Google')         |                      13 |                 18187 | Advertisement               |
| ('192.168.75.128', '142.250.74.70', 'TLS.Google')          |                       6 |                   857 | Advertisement               |
| ('192.168.75.128', '142.250.74.77', 'TLS.Google')          |                      16 |                  1083 | Web                         |
| ('192.168.75.128', '142.250.74.8', 'QUIC.GoogleServices')  |                       4 |                  5596 | Web                         |
| ('192.168.75.128', '142.250.74.8', 'TLS.Google')           |                      16 |                  1083 | Web                         |
| ('192.168.75.128', '142.251.1.156', 'TLS.Google')          |                       6 |                   857 | Advertisement               |
| ('192.168.75.128', '142.251.1.157', 'QUIC.Google')         |                      13 |                 18187 | Advertisement               |
| ('192.168.75.128', '142.251.1.157', 'TLS.Google')          |                       6 |                   857 | Advertisement               |
| ('192.168.75.128', '147.75.79.213', 'TLS')                 |                      27 |                  7703 | Web                         |
| ('192.168.75.128', '149.154.167.151', 'HTTP.Telegram')     |                       9 |                   730 | Chat                        |
| ('192.168.75.128', '149.154.167.151', 'TLS.Telegram')      |                    2572 |               2960602 | Chat                        |
| ('192.168.75.128', '149.154.167.41', 'HTTP.Telegram')      |                      10 |                  1003 | Chat                        |
| ('192.168.75.128', '149.154.167.41', 'TLS.Telegram')       |                     992 |                678388 | Chat                        |
| ('192.168.75.128', '149.154.167.92', 'HTTP.Telegram')      |                      10 |                  1007 | Chat                        |
| ('192.168.75.128', '149.154.167.92', 'TLS.Telegram')       |                     134 |                123146 | Chat                        |
| ('192.168.75.128', '151.101.129.35', 'TLS')                |                      10 |                  4917 | Web                         |
| ('192.168.75.128', '151.101.130.133', 'TLS')               |                      11 |                  4654 | Web                         |
| ('192.168.75.128', '151.101.2.133', 'TLS')                 |                    1272 |               1359259 | Web                         |
| ('192.168.75.128', '151.101.65.21', 'TLS')                 |                    2151 |               1569314 | Web                         |
| ('192.168.75.128', '178.154.131.216', 'TLS')               |                      16 |                  1083 | Web                         |
| ('192.168.75.128', '178.18.232.211', 'HTTP')               |                      24 |                  1306 | Web                         |
| ('192.168.75.128', '178.18.232.225', 'HTTP')               |                       7 |                   394 | Web                         |
| ('192.168.75.128', '178.18.232.225', 'HTTP.OCSP')          |                      27 |                  4145 | Network                     |
| ('192.168.75.128', '185.172.148.128', 'TLS')               |                      24 |                  7930 | Web                         |
| ('192.168.75.128', '185.199.109.133', 'TLS.Github')        |                    2018 |               2121740 | Collaborative               |
| ('192.168.75.128', '185.199.110.133', 'TLS.Github')        |                      20 |                  5718 | Collaborative               |
| ('192.168.75.128', '185.199.110.154', 'TLS')               |                      31 |                  7836 | Web                         |
| ('192.168.75.128', '185.199.111.133', 'TLS.Github')        |                      20 |                  5702 | Collaborative               |
| ('192.168.75.128', '185.199.111.154', 'TLS')               |                       9 |                   530 | Web                         |
| ('192.168.75.128', '188.114.98.128', 'HTTP.Cloudflare')    |                      13 |                   707 | Web                         |
| ('192.168.75.128', '188.114.98.128', 'HTTP.OCSP')          |                      28 |                  5681 | Network                     |
| ('192.168.75.128', '188.114.99.128', 'HTTP.Cloudflare')    |                      13 |                   707 | Web                         |
| ('192.168.75.128', '188.114.99.128', 'TLS.Cloudflare')     |                     164 |                 89623 | Web                         |
| ('192.168.75.128', '192.124.249.24', 'HTTP.OCSP')          |                      25 |                  4096 | Network                     |
| ('192.168.75.128', '192.168.75.2', 'DNS')                  |                       2 |                   573 | ConnCheck                   |
| ('192.168.75.128', '192.168.75.2', 'DNS.DoH_DoT')          |                       2 |                   374 | Network                     |
| ('192.168.75.128', '192.168.75.2', 'DNS.Microsoft')        |                       2 |                   317 | Cloud                       |
| ('192.168.75.128', '192.168.75.2', 'NetBIOS')              |                      22 |                  2420 | System                      |
| ('192.168.75.128', '192.168.75.255', 'NetBIOS')            |                       6 |                   552 | System                      |
| ('192.168.75.128', '192.168.75.255', 'NetBIOS.SMBv1')      |                       2 |                   486 | System                      |
| ('192.168.75.128', '195.201.201.32', 'TLS')                |                      19 |                  1095 | Web                         |
| ('192.168.75.128', '20.190.159.70', 'TLS.Azure')           |                       4 |                   216 | Cloud                       |
| ('192.168.75.128', '20.54.37.64', 'TLS.Azure')             |                      20 |                  2420 | Cloud                       |
| ('192.168.75.128', '20.54.37.64', 'TLS.Microsoft')         |                      31 |                  8750 | Cloud                       |
| ('192.168.75.128', '209.140.129.52', 'TLS.eBay')           |                      58 |                 33057 | Shopping                    |
| ('192.168.75.128', '209.140.129.66', 'TLS.eBay')           |                      47 |                 25507 | Shopping                    |
| ('192.168.75.128', '209.140.129.84', 'TLS.eBay')           |                      11 |                  5416 | Shopping                    |
| ('192.168.75.128', '209.140.129.85', 'TLS.eBay')           |                      23 |                 12036 | Shopping                    |
| ('192.168.75.128', '209.140.144.108', 'TLS.eBay')          |                      56 |                 16618 | Shopping                    |
| ('192.168.75.128', '209.140.151.235', 'TLS.eBay')          |                     136 |                 84371 | Shopping                    |
| ('192.168.75.128', '212.188.15.12', 'QUIC.YouTube')        |                      13 |                 18187 | Media                       |
| ('192.168.75.128', '212.188.15.12', 'TLS.YouTube')         |                      18 |                  6561 | Media                       |
| ('192.168.75.128', '212.188.15.13', 'QUIC.YouTube')        |                      13 |                 18187 | Media                       |
| ('192.168.75.128', '212.188.15.13', 'TLS.YouTube')         |                      35 |                 17734 | Media                       |
| ('192.168.75.128', '212.188.15.14', 'QUIC.YouTube')        |                      13 |                 18187 | Media                       |
| ('192.168.75.128', '212.188.15.14', 'TLS.YouTube')         |                    3663 |               4882595 | Media                       |
| ('192.168.75.128', '212.188.15.17', 'QUIC.YouTube')        |                       8 |                 11192 | Media                       |
| ('192.168.75.128', '212.188.15.17', 'TLS')                 |                      29 |                  1602 | Web                         |
| ('192.168.75.128', '212.188.15.18', 'TLS.YouTube')         |                      18 |                  6561 | Media                       |
| ('192.168.75.128', '212.188.15.19', 'TLS')                 |                       6 |                   348 | Web                         |
| ('192.168.75.128', '212.188.34.206', 'QUIC.YouTube')       |                      13 |                 18187 | Media                       |
| ('192.168.75.128', '212.188.34.206', 'TLS.YouTube')        |                    4871 |               6393136 | Media                       |
| ('192.168.75.128', '212.188.35.207', 'QUIC.YouTube')       |                      13 |                 18187 | Media                       |
| ('192.168.75.128', '212.188.35.207', 'TLS.YouTube')        |                     339 |                330395 | Media                       |
| ('192.168.75.128', '212.188.37.142', 'QUIC.YouTube')       |                      13 |                 18187 | Media                       |
| ('192.168.75.128', '212.188.37.142', 'TLS.YouTube')        |                      18 |                  6561 | Media                       |
| ('192.168.75.128', '216.58.207.195', 'TLS.Google')         |                     103 |                 22295 | Web                         |
| ('192.168.75.128', '216.58.207.202', 'TLS.GoogleServices') |                      22 |                  7317 | Web                         |
| ('192.168.75.128', '216.58.207.227', 'HTTP.Google')        |                       7 |                   394 | Web                         |
| ('192.168.75.128', '216.58.207.227', 'HTTP.OCSP')          |                      42 |                  5745 | Cloud                       |
| ('192.168.75.128', '216.58.207.227', 'TLS.Google')         |                      36 |                  7927 | Web                         |
| ('192.168.75.128', '224.0.0.251', 'MDNS')                  |                       2 |                   140 | Network                     |
| ('192.168.75.128', '224.0.0.252', 'LLMNR')                 |                       2 |                   128 | Network                     |
| ('192.168.75.128', '23.13.248.61', 'TLS.eBay')             |                      92 |                 44180 | Shopping                    |
| ('192.168.75.128', '23.13.250.159', 'TLS')                 |                      53 |                 15603 | Web                         |
| ('192.168.75.128', '23.59.143.163', 'HTTP')                |                       4 |                   216 | Web                         |
| ('192.168.75.128', '239.255.255.250', 'SSDP')              |                       3 |                   429 | System                      |
| ('192.168.75.128', '239.255.255.250', 'WSD')               |                       7 |                  4662 | Network                     |
| ('192.168.75.128', '3.123.205.102', 'TLS.AmazonAWS')       |                      27 |                  6224 | Cloud                       |
| ('192.168.75.128', '31.13.72.36', 'TLS.Facebook')          |                       6 |                   857 | SocialNetwork               |
| ('192.168.75.128', '34.107.221.82', 'HTTP.GoogleCloud')    |                      56 |                  6161 | Cloud                       |
| ('192.168.75.128', '34.117.237.239', 'TLS.GoogleCloud')    |                      16 |                  1083 | Cloud                       |
| ('192.168.75.128', '34.120.208.123', 'TLS.GoogleCloud')    |                      79 |                 23521 | Cloud                       |
| ('192.168.75.128', '35.174.150.168', 'TLS.AmazonAWS')      |                       9 |                   530 | Cloud                       |
| ('192.168.75.128', '35.241.15.240', 'QUIC.GoogleCloud')    |                       8 |                  9877 | Cloud                       |
| ('192.168.75.128', '35.241.15.240', 'TLS.GoogleCloud')     |                      21 |                  8154 | Cloud                       |
| ('192.168.75.128', '40.127.240.158', 'TLS.Microsoft')      |                      22 |                  9069 | Cloud                       |
| ('192.168.75.128', '52.202.69.186', 'TLS.AmazonAWS')       |                      21 |                  8442 | Cloud                       |
| ('192.168.75.128', '52.42.134.249', 'TLS.AmazonAWS')       |                       8 |                   560 | Cloud                       |
| ('192.168.75.128', '54.230.130.22', 'TLS.AmazonAWS')       |                      26 |                  1438 | Cloud                       |
| ('192.168.75.128', '54.230.130.7', 'TLS.AmazonAWS')        |                      16 |                  1125 | Cloud                       |
| ('192.168.75.128', '54.83.14.188', 'TLS.AmazonAWS')        |                      71 |                 40624 | Cloud                       |
| ('192.168.75.128', '64.233.162.196', 'TLS.Google')         |                      16 |                  1083 | Web                         |
| ('192.168.75.128', '64.233.162.94', 'TLS.Google')          |                      65 |                 36316 | Web                         |
| ('192.168.75.128', '64.4.250.36', 'TLS')                   |                      32 |                  7884 | Web                         |
| ('192.168.75.128', '64.71.144.211', 'TLS')                 |                      83 |                 54078 | Web                         |
| ('192.168.75.128', '66.135.201.118', 'TLS.eBay')           |                      22 |                  8674 | Shopping                    |
| ('192.168.75.128', '74.125.131.157', 'TLS.Google')         |                       6 |                   857 | Advertisement               |
| ('192.168.75.128', '74.125.131.198', 'TLS.YouTube')        |                     303 |                177524 | Media                       |
| ('192.168.75.128', '77.88.21.90', 'TLS')                   |                      19 |                  1420 | Web                         |
| ('192.168.75.128', '77.88.55.80', 'TLS')                   |                      19 |                  1420 | Web                         |
| ('192.168.75.128', '91.198.174.192', 'TLS.Wikipedia')      |                     608 |                566603 | Web                         |
| ('192.168.75.128', '91.198.174.208', 'TLS.Wikipedia')      |                      20 |                  6378 | Web                         |
| ('192.168.75.128', '93.184.220.29', 'HTTP')                |                      24 |                  1306 | Web                         |
| ('192.168.75.128', '93.184.220.29', 'HTTP.OCSP')           |                      71 |                 17350 | Network                     |
| ('192.168.75.128', '93.184.221.225', 'TLS.eBay')           |                     443 |                515050 | Shopping                    |
| ('192.168.75.128', '96.16.161.118', 'TLS.eBay')            |                      28 |                  8456 | Shopping                    |
| ('192.168.75.128', '96.16.161.25', 'TLS.eBay')             |                     974 |                920236 | Shopping                    |
| ('192.168.75.2', '192.168.75.128', 'ICMP')                 |                      22 |                  2964 | Network                     |
| ('212.188.15.19', '192.168.75.128', 'TLS')                 |                      32 |                  4481 | Web                         |
| ('213.180.193.90', '192.168.75.128', 'TLS')                |                       2 |                   116 | Web                         |
| ('34.216.199.145', '192.168.75.128', 'TLS.AmazonAWS')      |                      17 |                  2034 | Cloud                       |
| ('5.45.205.245', '192.168.75.128', 'HTTP')                 |                       4 |                   216 | Web                         |
| ('52.188.50.245', '192.168.75.128', 'HTTP.Azure')          |                       4 |                   216 | Cloud                       |
| ('54.230.130.15', '192.168.75.128', 'TLS.AmazonAWS')       |                       2 |                   170 | Cloud                       |
| ('54.230.130.27', '192.168.75.128', 'TLS.AmazonAWS')       |                      11 |                  1441 | Cloud                       |
| ('93.184.220.29', '192.168.75.128', 'HTTP')                |                       3 |                   162 | Web                         |
| ('fe80::5959:447f:b090:968', 'ff02::1:2', 'DHCPV6')        |                       1 |                   157 | Network                     |
| ('fe80::5959:447f:b090:968', 'ff02::1:3', 'LLMNR')         |                       2 |                   168 | Network                     |
| ('fe80::5959:447f:b090:968', 'ff02::c', 'SSDP')            |                       3 |                   471 | System                      |
| ('fe80::5959:447f:b090:968', 'ff02::c', 'WSD')             |                       7 |                  4802 | Network                     |
| ('fe80::5959:447f:b090:968', 'ff02::fb', 'MDNS')           |                       2 |                   180 | Network                     |
| ('fe80::c43b:78f0:882b:ca43', 'ff02::1:3', 'LLMNR')        |                       2 |                   168 | Network                     |
| ('fe80::c43b:78f0:882b:ca43', 'ff02::fb', 'MDNS')          |                      12 |                  1080 | Network                     |

## Начало и конец захвата трафика:

Start date:2022-04-11 09:26:51
End date:2022-04-11 09:32:17

## Вывод полезной информации:

|                                           |   src2dst_duration_ms |
|:------------------------------------------|----------------------:|
| ('108.177.14.198', 'TLS.Google')          |              227501   |
| ('131.253.33.200', 'TLS.Azure')           |                   0   |
| ('142.250.74.162', 'TLS.Google')          |                  11   |
| ('142.250.74.67', 'TLS.Google')           |               63677.5 |
| ('188.114.99.128', 'TLS.Cloudflare')      |              271798   |
| ('192.168.0.1', 'SSDP')                   |                3020   |
| ('192.168.75.1', 'LLMNR')                 |                 417   |
| ('192.168.75.1', 'MDNS')                  |                4014   |
| ('192.168.75.1', 'SSDP')                  |                6026   |
| ('192.168.75.128', 'DNS')                 |                   0   |
| ('192.168.75.128', 'DNS.DoH_DoT')         |                   0   |
| ('192.168.75.128', 'DNS.Microsoft')       |                   0   |
| ('192.168.75.128', 'HTTP')                |               94989   |
| ('192.168.75.128', 'HTTP.Cloudflare')     |               37997   |
| ('192.168.75.128', 'HTTP.Google')         |                6246   |
| ('192.168.75.128', 'HTTP.GoogleCloud')    |              170014   |
| ('192.168.75.128', 'HTTP.OCSP')           |               65024   |
| ('192.168.75.128', 'HTTP.Telegram')       |                 323.5 |
| ('192.168.75.128', 'LLMNR')               |                 409.5 |
| ('192.168.75.128', 'MDNS')                |                   1   |
| ('192.168.75.128', 'NetBIOS')             |              123012   |
| ('192.168.75.128', 'NetBIOS.SMBv1')       |              117596   |
| ('192.168.75.128', 'QUIC.Google')         |               18941   |
| ('192.168.75.128', 'QUIC.GoogleCloud')    |                2298   |
| ('192.168.75.128', 'QUIC.GoogleServices') |                9610   |
| ('192.168.75.128', 'QUIC.YouTube')        |               18942.5 |
| ('192.168.75.128', 'SSDP')                |                6021   |
| ('192.168.75.128', 'TLS')                 |                 796.5 |
| ('192.168.75.128', 'TLS.AmazonAWS')       |                9441.5 |
| ('192.168.75.128', 'TLS.Azure')           |                   0   |
| ('192.168.75.128', 'TLS.Cloudflare')      |               91942   |
| ('192.168.75.128', 'TLS.Facebook')        |                 149   |
| ('192.168.75.128', 'TLS.Github')          |                 489   |
| ('192.168.75.128', 'TLS.Google')          |                 146   |
| ('192.168.75.128', 'TLS.GoogleCloud')     |              111955   |
| ('192.168.75.128', 'TLS.GoogleServices')  |                 444   |
| ('192.168.75.128', 'TLS.LinkedIn')        |                 169   |
| ('192.168.75.128', 'TLS.Microsoft')       |               65132.5 |
| ('192.168.75.128', 'TLS.Telegram')        |               18258   |
| ('192.168.75.128', 'TLS.Wikipedia')       |                 708   |
| ('192.168.75.128', 'TLS.YouTube')         |               39085.5 |
| ('192.168.75.128', 'TLS.eBay')            |                5962   |
| ('192.168.75.128', 'WSD')                 |                7670   |
| ('192.168.75.2', 'ICMP')                  |              221459   |
| ('212.188.15.19', 'TLS')                  |              115553   |
| ('213.180.193.90', 'TLS')                 |                8006   |
| ('34.216.199.145', 'TLS.AmazonAWS')       |               73348   |
| ('5.45.205.245', 'HTTP')                  |                   0   |
| ('52.188.50.245', 'HTTP.Azure')           |                   1   |
| ('54.230.130.15', 'TLS.AmazonAWS')        |               32006   |
| ('54.230.130.27', 'TLS.AmazonAWS')        |              127367   |
| ('93.184.220.29', 'HTTP')                 |               48006   |
| ('fe80::5959:447f:b090:968', 'DHCPV6')    |                   0   |
| ('fe80::5959:447f:b090:968', 'LLMNR')     |                 410   |
| ('fe80::5959:447f:b090:968', 'MDNS')      |                   1   |
| ('fe80::5959:447f:b090:968', 'SSDP')      |                6021   |
| ('fe80::5959:447f:b090:968', 'WSD')       |                6891   |
| ('fe80::c43b:78f0:882b:ca43', 'LLMNR')    |                 417   |
| ('fe80::c43b:78f0:882b:ca43', 'MDNS')     |                4013   |

--------------------

# Отчёт drive/MyDrive/wg&ovpn&novpn.pcap

## Проверка наличия vpn трафика:
Protocol and data for drive/MyDrive/wg&ovpn&novpn.pcap:
|    | application_name    | application_category_name   |   bidirectional_bytes |
|---:|:--------------------|:----------------------------|----------------------:|
|  0 | DHCP                | Network                     |                  1400 |
|  1 | DNS                 | ConnCheck                   |                  1146 |
|  2 | DNS                 | Network                     |                 12996 |
|  3 | DNS.AmazonAWS       | Cloud                       |                  1006 |
|  4 | DNS.DoH_DoT         | Network                     |                 35540 |
|  5 | DNS.Google          | Web                         |                  3692 |
|  6 | DNS.GoogleServices  | Web                         |                   870 |
|  7 | DNS.Microsoft       | Cloud                       |                  1760 |
|  8 | DNS.Microsoft       | Web                         |                   291 |
|  9 | DNS.YouTube         | Media                       |                  5560 |
| 10 | DNS.eBay            | Shopping                    |                   657 |
| 11 | HTTP                | Web                         |                  4908 |
| 12 | HTTP.AmazonAWS      | Cloud                       |                   394 |
| 13 | HTTP.Google         | Web                         |                   394 |
| 14 | HTTP.GoogleCloud    | Cloud                       |                  1404 |
| 15 | HTTP.GoogleCloud    | ConnCheck                   |                  7260 |
| 16 | HTTP.OCSP           | Cloud                       |                 40390 |
| 17 | HTTP.OCSP           | Network                     |                103133 |
| 18 | HTTP.Telegram       | Chat                        |                 32415 |
| 19 | ICMP                | Network                     |                  9696 |
| 20 | ICMPV6              | Network                     |                  3610 |
| 21 | IGMP                | Network                     |                  2146 |
| 22 | IPsec               | VPN                         |                  2186 |
| 23 | LLMNR               | Network                     |                 10706 |
| 24 | MDNS                | Network                     |                 23662 |
| 25 | NetBIOS             | System                      |                 11954 |
| 26 | OpenVPN             | VPN                         |              61172291 |
| 27 | QUIC.Google         | Advertisement               |                 72748 |
| 28 | QUIC.Google         | Web                         |                 40655 |
| 29 | QUIC.GoogleCloud    | Cloud                       |                  7079 |
| 30 | QUIC.GoogleServices | Web                         |                 18187 |
| 31 | QUIC.YouTube        | Media                       |                218244 |
| 32 | SSDP                | System                      |                132457 |
| 33 | TLS                 | Web                         |               3357248 |
| 34 | TLS.AmazonAWS       | Cloud                       |                185327 |
| 35 | TLS.Azure           | Cloud                       |                  4585 |
| 36 | TLS.Cloudflare      | Web                         |                 58289 |
| 37 | TLS.DoH_DoT         | Network                     |               1310860 |
| 38 | TLS.Facebook        | SocialNetwork               |                 50563 |
| 39 | TLS.Github          | Collaborative               |               5437389 |
| 40 | TLS.Google          | Advertisement               |                135946 |
| 41 | TLS.Google          | Web                         |                372128 |
| 42 | TLS.GoogleCloud     | Cloud                       |                153907 |
| 43 | TLS.GoogleServices  | Web                         |                 94921 |
| 44 | TLS.LinkedIn        | SocialNetwork               |                 68560 |
| 45 | TLS.Microsoft       | Cloud                       |                 50540 |
| 46 | TLS.Telegram        | Chat                        |               5589112 |
| 47 | TLS.Wikipedia       | Web                         |                959924 |
| 48 | TLS.YouTube         | Media                       |              25075082 |
| 49 | TLS.eBay            | Shopping                    |               5117587 |
| 50 | WSD                 | Network                     |                 65248 |
| 51 | WireGuard           | VPN                         |             102575276 |

## Информация по src_ip, dst_ip и application_name:

|                                                             |   bidirectional_packets |   bidirectional_bytes | application_category_name   |
|:------------------------------------------------------------|------------------------:|----------------------:|:----------------------------|
| ('13.35.169.4', '192.168.75.128', 'TLS.AmazonAWS')          |                      11 |                  1441 | Cloud                       |
| ('142.250.74.162', '192.168.75.128', 'TLS.Google')          |                       1 |                    58 | Web                         |
| ('142.250.74.35', '192.168.75.128', 'TLS.Google')           |                       1 |                    54 | Web                         |
| ('142.250.74.67', '192.168.75.128', 'TLS.Google')           |                       1 |                    54 | Web                         |
| ('142.251.1.157', '192.168.75.128', 'TLS.Google')           |                       1 |                    54 | Web                         |
| ('149.154.167.41', '192.168.75.128', 'TLS.Telegram')        |                      11 |                   594 | Chat                        |
| ('178.18.232.211', '192.168.75.128', 'HTTP')                |                      11 |                   594 | Web                         |
| ('18.66.248.55', '192.168.75.128', 'TLS.AmazonAWS')         |                      11 |                   858 | Cloud                       |
| ('184.27.33.170', '192.168.75.128', 'HTTP')                 |                       1 |                    54 | Web                         |
| ('188.114.99.128', '192.168.75.128', 'TLS.Cloudflare')      |                       1 |                    58 | Web                         |
| ('192.168.0.1', '192.168.75.128', 'SSDP')                   |                      15 |                  5481 | System                      |
| ('192.168.75.1', '192.168.75.2', 'NetBIOS')                 |                       3 |                   330 | System                      |
| ('192.168.75.1', '192.168.75.254', 'DHCP')                  |                       2 |                   700 | Network                     |
| ('192.168.75.1', '224.0.0.22', 'IGMP')                      |                       5 |                   270 | Network                     |
| ('192.168.75.1', '224.0.0.251', 'MDNS')                     |                      40 |                  2920 | Network                     |
| ('192.168.75.1', '224.0.0.252', 'LLMNR')                    |                       2 |                   128 | Network                     |
| ('192.168.75.1', '239.255.255.250', 'SSDP')                 |                       6 |                  1074 | System                      |
| ('192.168.75.1', '239.255.255.250', 'WSD')                  |                       7 |                  4886 | Network                     |
| ('192.168.75.128', '104.16.85.20', 'TLS.Cloudflare')        |                      29 |                  5962 | Web                         |
| ('192.168.75.128', '108.138.24.78', 'HTTP.AmazonAWS')       |                       7 |                   394 | Cloud                       |
| ('192.168.75.128', '108.138.24.78', 'HTTP.OCSP')            |                      26 |                  2888 | Network                     |
| ('192.168.75.128', '108.156.22.44', 'TLS.AmazonAWS')        |                      36 |                  9616 | Cloud                       |
| ('192.168.75.128', '108.177.14.198', 'TLS.YouTube')         |                      37 |                 10323 | Media                       |
| ('192.168.75.128', '13.107.42.14', 'TLS.LinkedIn')          |                       6 |                   857 | SocialNetwork               |
| ('192.168.75.128', '140.82.112.22', 'TLS.Github')           |                      90 |                 23186 | Collaborative               |
| ('192.168.75.128', '140.82.121.4', 'TLS.Github')            |                     546 |                520919 | Collaborative               |
| ('192.168.75.128', '140.82.121.5', 'TLS.Github')            |                     359 |                188362 | Collaborative               |
| ('192.168.75.128', '142.250.74.130', 'QUIC.Google')         |                      13 |                 18187 | Advertisement               |
| ('192.168.75.128', '142.250.74.130', 'TLS.Google')          |                       6 |                   857 | Advertisement               |
| ('192.168.75.128', '142.250.74.138', 'QUIC.GoogleServices') |                      13 |                 18187 | Web                         |
| ('192.168.75.128', '142.250.74.138', 'TLS.GoogleServices')  |                      36 |                  8312 | Web                         |
| ('192.168.75.128', '142.250.74.14', 'TLS.Google')           |                      67 |                 14607 | Advertisement               |
| ('192.168.75.128', '142.250.74.142', 'QUIC.Google')         |                      13 |                 18187 | Web                         |
| ('192.168.75.128', '142.250.74.142', 'TLS.Google')          |                      24 |                  6126 | Web                         |
| ('192.168.75.128', '142.250.74.162', 'QUIC.Google')         |                      13 |                 18187 | Web                         |
| ('192.168.75.128', '142.250.74.162', 'TLS.Google')          |                       6 |                   857 | Web                         |
| ('192.168.75.128', '142.250.74.162', 'TLS.GoogleServices')  |                       6 |                   857 | Web                         |
| ('192.168.75.128', '142.250.74.163', 'HTTP.Google')         |                       7 |                   394 | Web                         |
| ('192.168.75.128', '142.250.74.163', 'HTTP.OCSP')           |                      87 |                 16483 | Cloud                       |
| ('192.168.75.128', '142.250.74.163', 'TLS.Google')          |                      21 |                  6920 | Web                         |
| ('192.168.75.128', '142.250.74.182', 'TLS.YouTube')         |                      35 |                  8295 | Media                       |
| ('192.168.75.128', '142.250.74.2', 'TLS.Google')            |                       6 |                   857 | Advertisement               |
| ('192.168.75.128', '142.250.74.3', 'TLS.Google')            |                      34 |                  7819 | Web                         |
| ('192.168.75.128', '142.250.74.35', 'TLS.Google')           |                     249 |                183384 | Web                         |
| ('192.168.75.128', '142.250.74.36', 'QUIC.Google')          |                       4 |                  4281 | Web                         |
| ('192.168.75.128', '142.250.74.36', 'TLS.Google')           |                      34 |                  7779 | Web                         |
| ('192.168.75.128', '142.250.74.42', 'TLS.GoogleServices')   |                      30 |                  4965 | Web                         |
| ('192.168.75.128', '142.250.74.67', 'TLS.Google')           |                      18 |                  1048 | Web                         |
| ('192.168.75.128', '142.250.74.70', 'QUIC.Google')          |                      13 |                 18187 | Advertisement               |
| ('192.168.75.128', '142.250.74.70', 'TLS.Google')           |                       6 |                   857 | Advertisement               |
| ('192.168.75.128', '149.154.165.120', 'HTTP.Telegram')      |                       9 |                   530 | Chat                        |
| ('192.168.75.128', '149.154.165.120', 'TLS.Telegram')       |                      15 |                  1516 | Chat                        |
| ('192.168.75.128', '149.154.167.151', 'HTTP.Telegram')      |                      10 |                   904 | Chat                        |
| ('192.168.75.128', '149.154.167.151', 'TLS.Telegram')       |                      20 |                  1947 | Chat                        |
| ('192.168.75.128', '149.154.167.41', 'HTTP.Telegram')       |                      10 |                   943 | Chat                        |
| ('192.168.75.128', '149.154.167.41', 'TLS.Telegram')        |                     129 |                 24671 | Chat                        |
| ('192.168.75.128', '149.154.175.54', 'HTTP.Telegram')       |                      10 |                   838 | Chat                        |
| ('192.168.75.128', '149.154.175.54', 'TLS.Telegram')        |                      14 |                  1444 | Chat                        |
| ('192.168.75.128', '151.101.1.21', 'TLS')                   |                    2681 |               1939322 | Web                         |
| ('192.168.75.128', '151.101.2.133', 'TLS')                  |                      15 |                  5996 | Web                         |
| ('192.168.75.128', '151.101.2.206', 'TLS.eBay')             |                      37 |                 14488 | Shopping                    |
| ('192.168.75.128', '151.101.65.35', 'TLS')                  |                      93 |                 31985 | Web                         |
| ('192.168.75.128', '157.245.51.246', 'OpenVPN')             |                   73901 |              61172291 | VPN                         |
| ('192.168.75.128', '159.203.14.174', 'IPsec')               |                       4 |                  2186 | VPN                         |
| ('192.168.75.128', '172.217.21.174', 'TLS.YouTube')         |                      37 |                 10355 | Media                       |
| ('192.168.75.128', '173.194.151.28', 'QUIC.YouTube')        |                      13 |                 18187 | Media                       |
| ('192.168.75.128', '173.194.151.28', 'TLS.YouTube')         |                      48 |                 12412 | Media                       |
| ('192.168.75.128', '173.194.176.149', 'QUIC.YouTube')       |                      13 |                 18187 | Media                       |
| ('192.168.75.128', '173.194.176.149', 'TLS.YouTube')        |                    4119 |               5203582 | Media                       |
| ('192.168.75.128', '173.194.222.198', 'TLS.YouTube')        |                     252 |                120944 | Media                       |
| ('192.168.75.128', '174.138.27.251', 'WireGuard')           |                  101348 |             102575276 | VPN                         |
| ('192.168.75.128', '178.18.232.211', 'HTTP.OCSP')           |                      34 |                  3196 | Network                     |
| ('192.168.75.128', '178.18.232.225', 'HTTP.OCSP')           |                      24 |                  2651 | Network                     |
| ('192.168.75.128', '18.232.28.189', 'TLS.AmazonAWS')        |                      11 |                  4571 | Cloud                       |
| ('192.168.75.128', '185.199.108.133', 'TLS.Github')         |                      20 |                  5702 | Collaborative               |
| ('192.168.75.128', '185.199.109.133', 'TLS.Github')         |                      20 |                  5702 | Collaborative               |
| ('192.168.75.128', '185.199.109.154', 'TLS')                |                      20 |                  5635 | Web                         |
| ('192.168.75.128', '185.199.110.133', 'TLS.Github')         |                      20 |                  5702 | Collaborative               |
| ('192.168.75.128', '185.199.110.154', 'TLS')                |                      31 |                 10867 | Web                         |
| ('192.168.75.128', '185.199.111.133', 'TLS.Github')         |                      20 |                  5718 | Collaborative               |
| ('192.168.75.128', '185.199.111.154', 'TLS')                |                       9 |                   530 | Web                         |
| ('192.168.75.128', '188.114.98.128', 'HTTP.OCSP')           |                      32 |                  7283 | Network                     |
| ('192.168.75.128', '188.114.99.128', 'TLS.Cloudflare')      |                      30 |                  6040 | Web                         |
| ('192.168.75.128', '188.114.99.128', 'TLS.DoH_DoT')         |                      20 |                  5658 | Network                     |
| ('192.168.75.128', '192.124.249.36', 'HTTP.OCSP')           |                      25 |                  4096 | Network                     |
| ('192.168.75.128', '192.168.75.2', 'DNS')                   |                       3 |                   228 | Network                     |
| ('192.168.75.128', '192.168.75.2', 'DNS.AmazonAWS')         |                       2 |                   423 | Cloud                       |
| ('192.168.75.128', '192.168.75.2', 'DNS.DoH_DoT')           |                       2 |                   374 | Network                     |
| ('192.168.75.128', '192.168.75.2', 'DNS.Google')            |                       2 |                   492 | Web                         |
| ('192.168.75.128', '192.168.75.2', 'DNS.GoogleServices')    |                       2 |                   435 | Web                         |
| ('192.168.75.128', '192.168.75.2', 'DNS.Microsoft')         |                       2 |                   317 | Cloud                       |
| ('192.168.75.128', '192.168.75.2', 'DNS.YouTube')           |                       2 |                   475 | Media                       |
| ('192.168.75.128', '192.168.75.2', 'DNS.eBay')              |                       4 |                   438 | Shopping                    |
| ('192.168.75.128', '192.168.75.2', 'NetBIOS')               |                      73 |                  7652 | System                      |
| ('192.168.75.128', '192.168.75.254', 'DHCP')                |                       2 |                   700 | Network                     |
| ('192.168.75.128', '192.168.75.255', 'NetBIOS')             |                      18 |                  1656 | System                      |
| ('192.168.75.128', '20.198.162.76', 'TLS.Microsoft')        |                      29 |                  8303 | Cloud                       |
| ('192.168.75.128', '20.54.37.73', 'TLS.Microsoft')          |                      38 |                 12830 | Cloud                       |
| ('192.168.75.128', '209.140.129.51', 'TLS.eBay')            |                     121 |                 58057 | Shopping                    |
| ('192.168.75.128', '209.140.129.52', 'TLS.eBay')            |                     103 |                 52748 | Shopping                    |
| ('192.168.75.128', '209.140.129.84', 'TLS.eBay')            |                      21 |                  8788 | Shopping                    |
| ('192.168.75.128', '209.140.129.85', 'TLS.eBay')            |                      61 |                 26699 | Shopping                    |
| ('192.168.75.128', '209.140.129.90', 'TLS.eBay')            |                      74 |                 33784 | Shopping                    |
| ('192.168.75.128', '209.140.148.141', 'TLS.eBay')           |                      41 |                 20362 | Shopping                    |
| ('192.168.75.128', '209.140.148.240', 'TLS.eBay')           |                      57 |                 16352 | Shopping                    |
| ('192.168.75.128', '212.188.15.14', 'QUIC.YouTube')         |                      13 |                 18187 | Media                       |
| ('192.168.75.128', '212.188.15.14', 'TLS.YouTube')          |                      53 |                 11239 | Media                       |
| ('192.168.75.128', '212.188.15.17', 'QUIC.YouTube')         |                      13 |                 18187 | Media                       |
| ('192.168.75.128', '212.188.15.17', 'TLS.YouTube')          |                      45 |                  9196 | Media                       |
| ('192.168.75.128', '212.188.15.19', 'QUIC.YouTube')         |                      13 |                 18187 | Media                       |
| ('192.168.75.128', '212.188.15.19', 'TLS.YouTube')          |                    2113 |               2715259 | Media                       |
| ('192.168.75.128', '212.188.35.16', 'QUIC.YouTube')         |                      13 |                 18187 | Media                       |
| ('192.168.75.128', '212.188.35.16', 'TLS.YouTube')          |                      48 |                 12391 | Media                       |
| ('192.168.75.128', '212.188.37.142', 'QUIC.YouTube')        |                      13 |                 18187 | Media                       |
| ('192.168.75.128', '212.188.37.142', 'TLS.YouTube')         |                      18 |                  6561 | Media                       |
| ('192.168.75.128', '212.188.49.141', 'QUIC.YouTube')        |                      13 |                 18187 | Media                       |
| ('192.168.75.128', '212.188.49.141', 'TLS.YouTube')         |                      48 |                 10175 | Media                       |
| ('192.168.75.128', '212.188.49.146', 'QUIC.YouTube')        |                      13 |                 18187 | Media                       |
| ('192.168.75.128', '212.188.49.146', 'TLS.YouTube')         |                      28 |                 13271 | Media                       |
| ('192.168.75.128', '212.188.7.143', 'QUIC.YouTube')         |                      13 |                 18187 | Media                       |
| ('192.168.75.128', '212.188.7.143', 'TLS.YouTube')          |                      50 |                 11022 | Media                       |
| ('192.168.75.128', '212.188.7.145', 'QUIC.YouTube')         |                      13 |                 18187 | Media                       |
| ('192.168.75.128', '212.188.7.145', 'TLS.YouTube')          |                      51 |                 13766 | Media                       |
| ('192.168.75.128', '216.58.207.198', 'QUIC.Google')         |                      13 |                 18187 | Advertisement               |
| ('192.168.75.128', '216.58.207.198', 'TLS.Google')          |                       6 |                   857 | Advertisement               |
| ('192.168.75.128', '216.58.207.226', 'TLS.Google')          |                       6 |                   857 | Advertisement               |
| ('192.168.75.128', '216.58.207.234', 'TLS.GoogleServices')  |                      35 |                  8227 | Web                         |
| ('192.168.75.128', '216.58.211.10', 'TLS.GoogleServices')   |                      31 |                  9260 | Web                         |
| ('192.168.75.128', '224.0.0.22', 'IGMP')                    |                      25 |                  1374 | Network                     |
| ('192.168.75.128', '224.0.0.251', 'MDNS')                   |                      32 |                  3031 | Network                     |
| ('192.168.75.128', '224.0.0.252', 'LLMNR')                  |                       1 |                    75 | Network                     |
| ('192.168.75.128', '23.13.248.61', 'TLS.eBay')              |                      54 |                 22546 | Shopping                    |
| ('192.168.75.128', '23.13.250.159', 'TLS')                  |                      57 |                 19583 | Web                         |
| ('192.168.75.128', '239.255.255.250', 'SSDP')               |                      15 |                  2613 | System                      |
| ('192.168.75.128', '239.255.255.250', 'WSD')                |                       8 |                  8952 | Network                     |
| ('192.168.75.128', '3.123.205.102', 'TLS.AmazonAWS')        |                      28 |                  6278 | Cloud                       |
| ('192.168.75.128', '31.13.72.36', 'TLS.Facebook')           |                       6 |                   857 | SocialNetwork               |
| ('192.168.75.128', '34.107.221.82', 'HTTP.GoogleCloud')     |                      45 |                  3710 | ConnCheck                   |
| ('192.168.75.128', '34.117.237.239', 'TLS.GoogleCloud')     |                      42 |                  8962 | Cloud                       |
| ('192.168.75.128', '34.120.208.123', 'TLS.GoogleCloud')     |                      95 |                 18429 | Cloud                       |
| ('192.168.75.128', '34.216.199.145', 'TLS.AmazonAWS')       |                      20 |                  6443 | Cloud                       |
| ('192.168.75.128', '34.67.180.164', 'TLS.GoogleCloud')      |                      13 |                  7313 | Cloud                       |
| ('192.168.75.128', '34.72.38.229', 'TLS.GoogleCloud')       |                      13 |                  7313 | Cloud                       |
| ('192.168.75.128', '35.174.151.106', 'TLS.AmazonAWS')       |                      34 |                 11358 | Cloud                       |
| ('192.168.75.128', '35.241.15.240', 'QUIC.GoogleCloud')     |                       6 |                  7079 | Cloud                       |
| ('192.168.75.128', '35.241.15.240', 'TLS.GoogleCloud')      |                      22 |                  8208 | Cloud                       |
| ('192.168.75.128', '54.230.130.15', 'TLS.AmazonAWS')        |                      19 |                  5467 | Cloud                       |
| ('192.168.75.128', '54.230.130.25', 'TLS.AmazonAWS')        |                      45 |                  9051 | Cloud                       |
| ('192.168.75.128', '54.230.130.56', 'TLS.AmazonAWS')        |                      36 |                  6922 | Cloud                       |
| ('192.168.75.128', '54.230.130.93', 'TLS.AmazonAWS')        |                       9 |                   530 | Cloud                       |
| ('192.168.75.128', '54.83.14.188', 'TLS.AmazonAWS')         |                      86 |                 55764 | Cloud                       |
| ('192.168.75.128', '64.233.162.154', 'TLS.Google')          |                       6 |                   857 | Advertisement               |
| ('192.168.75.128', '64.233.162.155', 'TLS.Google')          |                       6 |                   857 | Advertisement               |
| ('192.168.75.128', '64.4.250.36', 'TLS')                    |                      33 |                  7939 | Web                         |
| ('192.168.75.128', '67.207.67.2', 'DNS')                    |                       1 |                    76 | Network                     |
| ('192.168.75.128', '67.207.67.2', 'DNS.Microsoft')          |                       4 |                   328 | Cloud                       |
| ('192.168.75.128', '67.207.67.3', 'DNS')                    |                       1 |                    76 | Network                     |
| ('192.168.75.128', '67.207.67.3', 'DNS.Microsoft')          |                       2 |                   164 | Cloud                       |
| ('192.168.75.128', '74.125.153.202', 'QUIC.YouTube')        |                      13 |                 18187 | Media                       |
| ('192.168.75.128', '74.125.153.202', 'TLS.YouTube')         |                    1145 |               1264355 | Media                       |
| ('192.168.75.128', '91.198.174.192', 'TLS.Wikipedia')       |                     392 |                297431 | Web                         |
| ('192.168.75.128', '91.198.174.208', 'TLS.Wikipedia')       |                      22 |                  6485 | Web                         |
| ('192.168.75.128', '93.184.220.29', 'HTTP')                 |                       7 |                   394 | Web                         |
| ('192.168.75.128', '93.184.220.29', 'HTTP.OCSP')            |                     100 |                 22692 | Network                     |
| ('192.168.75.128', '93.184.221.225', 'TLS.eBay')            |                     557 |                629921 | Shopping                    |
| ('192.168.75.128', '95.101.172.125', 'TLS.eBay')            |                    1143 |               1054921 | Shopping                    |
| ('192.168.75.128', '95.101.172.14', 'TLS.eBay')             |                      29 |                  8581 | Shopping                    |
| ('192.168.75.2', '192.168.75.128', 'ICMP')                  |                      73 |                  9696 | Network                     |
| ('20.54.37.64', '192.168.75.128', 'TLS.Azure')              |                      13 |                  4175 | Cloud                       |
| ('23.218.9.177', '192.168.75.128', 'TLS')                   |                      11 |                   935 | Web                         |
| ('34.107.221.82', '192.168.75.128', 'HTTP.GoogleCloud')     |                      11 |                   594 | Cloud                       |
| ('34.117.237.239', '192.168.75.128', 'TLS.GoogleCloud')     |                      17 |                  2702 | Cloud                       |
| ('34.120.208.123', '192.168.75.128', 'TLS.GoogleCloud')     |                      17 |                  2891 | Cloud                       |
| ('34.216.199.145', '192.168.75.128', 'TLS.AmazonAWS')       |                       1 |                    54 | Cloud                       |
| ('35.160.51.228', '192.168.75.128', 'TLS.AmazonAWS')        |                      18 |                  2181 | Cloud                       |
| ('54.230.130.27', '192.168.75.128', 'TLS.AmazonAWS')        |                       1 |                    54 | Cloud                       |
| ('93.184.220.29', '192.168.75.128', 'HTTP')                 |                      11 |                   594 | Web                         |
| ('fe80::5959:447f:b090:968', 'ff02::16', 'ICMPV6')          |                      25 |                  2310 | Network                     |
| ('fe80::5959:447f:b090:968', 'ff02::1:3', 'LLMNR')          |                       1 |                    95 | Network                     |
| ('fe80::5959:447f:b090:968', 'ff02::c', 'SSDP')             |                       2 |                   314 | System                      |
| ('fe80::5959:447f:b090:968', 'ff02::c', 'WSD')              |                       8 |                  9208 | Network                     |
| ('fe80::5959:447f:b090:968', 'ff02::fb', 'MDNS')            |                      32 |                  3671 | Network                     |
| ('fe80::c43b:78f0:882b:ca43', 'ff02::16', 'ICMPV6')         |                       5 |                   450 | Network                     |
| ('fe80::c43b:78f0:882b:ca43', 'ff02::1:3', 'LLMNR')         |                       2 |                   168 | Network                     |
| ('fe80::c43b:78f0:882b:ca43', 'ff02::c', 'WSD')             |                       7 |                  5026 | Network                     |
| ('fe80::c43b:78f0:882b:ca43', 'ff02::fb', 'MDNS')           |                      40 |                  3720 | Network                     |

## Начало и конец захвата трафика:

Start date:2022-04-11 09:34:50
End date:2022-04-11 09:49:35

## Вывод полезной информации:

|                                           |   src2dst_duration_ms |
|:------------------------------------------|----------------------:|
| ('13.35.169.4', 'TLS.AmazonAWS')          |                   0   |
| ('142.250.74.162', 'TLS.Google')          |                   0   |
| ('142.250.74.35', 'TLS.Google')           |                   0   |
| ('142.250.74.67', 'TLS.Google')           |                   0   |
| ('142.251.1.157', 'TLS.Google')           |                   0   |
| ('149.154.167.41', 'TLS.Telegram')        |                   0   |
| ('178.18.232.211', 'HTTP')                |               63690   |
| ('18.66.248.55', 'TLS.AmazonAWS')         |                   0   |
| ('184.27.33.170', 'HTTP')                 |                   0   |
| ('188.114.99.128', 'TLS.Cloudflare')      |                   0   |
| ('192.168.0.1', 'SSDP')                   |                 555   |
| ('192.168.75.1', 'DHCP')                  |                   0   |
| ('192.168.75.1', 'IGMP')                  |                 166   |
| ('192.168.75.1', 'LLMNR')                 |                 418   |
| ('192.168.75.1', 'MDNS')                  |               96242   |
| ('192.168.75.1', 'NetBIOS')               |                2157   |
| ('192.168.75.1', 'SSDP')                  |               15052   |
| ('192.168.75.1', 'WSD')                   |                6329   |
| ('192.168.75.128', 'DHCP')                |                   0   |
| ('192.168.75.128', 'DNS')                 |                   0   |
| ('192.168.75.128', 'DNS.AmazonAWS')       |                   0   |
| ('192.168.75.128', 'DNS.DoH_DoT')         |                   0   |
| ('192.168.75.128', 'DNS.Google')          |                   0   |
| ('192.168.75.128', 'DNS.GoogleServices')  |                   0   |
| ('192.168.75.128', 'DNS.Microsoft')       |                   0   |
| ('192.168.75.128', 'DNS.YouTube')         |                   0   |
| ('192.168.75.128', 'DNS.eBay')            |                  25   |
| ('192.168.75.128', 'HTTP')                |                5477   |
| ('192.168.75.128', 'HTTP.AmazonAWS')      |                5648   |
| ('192.168.75.128', 'HTTP.Google')         |                5840   |
| ('192.168.75.128', 'HTTP.GoogleCloud')    |              155845   |
| ('192.168.75.128', 'HTTP.OCSP')           |               66540   |
| ('192.168.75.128', 'HTTP.Telegram')       |                 329   |
| ('192.168.75.128', 'IGMP')                |               34782   |
| ('192.168.75.128', 'IPsec')               |                7473   |
| ('192.168.75.128', 'LLMNR')               |                 410   |
| ('192.168.75.128', 'MDNS')                |               47117   |
| ('192.168.75.128', 'NetBIOS')             |               29780   |
| ('192.168.75.128', 'OpenVPN')             |              293379   |
| ('192.168.75.128', 'QUIC.Google')         |               18941   |
| ('192.168.75.128', 'QUIC.GoogleCloud')    |                1309   |
| ('192.168.75.128', 'QUIC.GoogleServices') |               18955   |
| ('192.168.75.128', 'QUIC.YouTube')        |               18928   |
| ('192.168.75.128', 'SSDP')                |                  25   |
| ('192.168.75.128', 'TLS')                 |                 900.5 |
| ('192.168.75.128', 'TLS.AmazonAWS')       |                6501   |
| ('192.168.75.128', 'TLS.Cloudflare')      |               84686   |
| ('192.168.75.128', 'TLS.DoH_DoT')         |                 892.5 |
| ('192.168.75.128', 'TLS.Facebook')        |                 148   |
| ('192.168.75.128', 'TLS.Github')          |                 650   |
| ('192.168.75.128', 'TLS.Google')          |                 148   |
| ('192.168.75.128', 'TLS.GoogleCloud')     |                1411   |
| ('192.168.75.128', 'TLS.GoogleServices')  |                 452   |
| ('192.168.75.128', 'TLS.LinkedIn')        |                 169   |
| ('192.168.75.128', 'TLS.Microsoft')       |               28532   |
| ('192.168.75.128', 'TLS.Telegram')        |                5755   |
| ('192.168.75.128', 'TLS.Wikipedia')       |                 721.5 |
| ('192.168.75.128', 'TLS.YouTube')         |              116412   |
| ('192.168.75.128', 'TLS.eBay')            |                6327   |
| ('192.168.75.128', 'WSD')                 |               18430.5 |
| ('192.168.75.128', 'WireGuard')           |              312805   |
| ('192.168.75.2', 'ICMP')                  |              552921   |
| ('20.54.37.64', 'TLS.Azure')              |                   0   |
| ('23.218.9.177', 'TLS')                   |               63685   |
| ('34.107.221.82', 'HTTP.GoogleCloud')     |                   0   |
| ('34.117.237.239', 'TLS.GoogleCloud')     |                   0   |
| ('34.120.208.123', 'TLS.GoogleCloud')     |                   0   |
| ('34.216.199.145', 'TLS.AmazonAWS')       |                   0   |
| ('35.160.51.228', 'TLS.AmazonAWS')        |                   0   |
| ('54.230.130.27', 'TLS.AmazonAWS')        |                   0   |
| ('93.184.220.29', 'HTTP')                 |                   0   |
| ('fe80::5959:447f:b090:968', 'ICMPV6')    |               34782.5 |
| ('fe80::5959:447f:b090:968', 'LLMNR')     |                 410   |
| ('fe80::5959:447f:b090:968', 'MDNS')      |               47117.5 |
| ('fe80::5959:447f:b090:968', 'SSDP')      |                3069   |
| ('fe80::5959:447f:b090:968', 'WSD')       |               18318.5 |
| ('fe80::c43b:78f0:882b:ca43', 'ICMPV6')   |                 167   |
| ('fe80::c43b:78f0:882b:ca43', 'LLMNR')    |                 418   |
| ('fe80::c43b:78f0:882b:ca43', 'MDNS')     |               96241.5 |
| ('fe80::c43b:78f0:882b:ca43', 'WSD')      |                6692.5 |

