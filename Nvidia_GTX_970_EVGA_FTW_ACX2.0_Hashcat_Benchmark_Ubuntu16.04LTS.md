## Nvidia GTX 970 (EVGA FTW ACX2.0) Hashcat Benchmark

**System** Dell Optiplex 330

**CPU** Intel Core 2 Duo E4500 Processor (2.2 GHz, 2 MB L2 cache, 800 MHz FSB)

**RAM** 2 GB DDR2 Non-ECC SDRAM, 800 MHz

**GPU** Nvidia GTX 970 (EVGA FTW ACX 2.0) (Base 1216 MHz, Boost 1367 MHz)

**OS** Ubuntu 16.04 LTS

**Software** Hashcat v3.5.0, nvidia-375 (nvidia 375.66)

### Benchmark

```
hashcat (v3.5.0) starting in benchmark mode...

* Device #1: GeForce GTX 970, 1009/4036 MB allocatable, 13MCU

Hashtype: MD4

Speed.Dev.#1.....: 21004.6 MH/s (83.43ms)

Hashtype: MD5

Speed.Dev.#1.....: 11661.9 MH/s (74.94ms)

Hashtype: Half MD5

Speed.Dev.#1.....:  7409.2 MH/s (58.92ms)

Hashtype: SHA1

Speed.Dev.#1.....:  3838.1 MH/s (56.83ms)

Hashtype: SHA-256

Speed.Dev.#1.....:  1459.6 MH/s (74.42ms)

Hashtype: SHA-384

Speed.Dev.#1.....:   478.7 MH/s (56.86ms)

Hashtype: SHA-512

Speed.Dev.#1.....:   497.2 MH/s (54.74ms)

Hashtype: SHA-3 (Keccak)

Speed.Dev.#1.....:   379.0 MH/s (71.84ms)

Hashtype: SipHash

Speed.Dev.#1.....: 13817.4 MH/s (63.11ms)

Hashtype: Skip32 (PT = $salt, key = $pass)

Speed.Dev.#1.....:  2544.7 MH/s (13.14ms)

Hashtype: RIPEMD-160

Speed.Dev.#1.....:  2269.0 MH/s (95.73ms)

Hashtype: Whirlpool

Speed.Dev.#1.....:   127.1 MH/s (107.27ms)

Hashtype: GOST R 34.11-94

Speed.Dev.#1.....:   120.0 MH/s (112.90ms)

Hashtype: GOST R 34.11-2012 (Streebog) 256-bit

Speed.Dev.#1.....: 24902.7 kH/s (270.14ms)

Hashtype: GOST R 34.11-2012 (Streebog) 512-bit

Speed.Dev.#1.....: 24809.0 kH/s (272.24ms)

Hashtype: DES (PT = $salt, key = $pass)

Speed.Dev.#1.....:  9695.7 MH/s (89.96ms)

Hashtype: 3DES (PT = $salt, key = $pass)

Speed.Dev.#1.....:   268.9 MH/s (50.66ms)

Hashtype: phpass, WordPress (MD5), phpBB3 (MD5), Joomla (MD5)

Speed.Dev.#1.....:  3357.9 kH/s (62.63ms)

Hashtype: scrypt

Speed.Dev.#1.....:   374.4 kH/s (17.44ms)

Hashtype: PBKDF2-HMAC-MD5

Speed.Dev.#1.....:  3726.1 kH/s (55.89ms)

Hashtype: PBKDF2-HMAC-SHA1

Speed.Dev.#1.....:  1551.2 kH/s (56.61ms)

Hashtype: PBKDF2-HMAC-SHA256

Speed.Dev.#1.....:   579.7 kH/s (83.54ms)

Hashtype: PBKDF2-HMAC-SHA512

Speed.Dev.#1.....:   209.4 kH/s (59.23ms)

Hashtype: Skype

Speed.Dev.#1.....:  6178.1 MH/s (70.47ms)

Hashtype: WPA/WPA2

Speed.Dev.#1.....:   190.7 kH/s (69.49ms)

Hashtype: IKE-PSK MD5

Speed.Dev.#1.....:   862.6 MH/s (63.14ms)

Hashtype: IKE-PSK SHA1

Speed.Dev.#1.....:   387.7 MH/s (70.19ms)

Hashtype: NetNTLMv1 / NetNTLMv1+ESS

Speed.Dev.#1.....: 10605.3 MH/s (82.21ms)

Hashtype: NetNTLMv2

Speed.Dev.#1.....:   800.8 MH/s (68.03ms)

Hashtype: IPMI2 RAKP HMAC-SHA1

Speed.Dev.#1.....:   773.4 MH/s (70.43ms)

Hashtype: Kerberos 5 AS-REQ Pre-Auth etype 23

Speed.Dev.#1.....:   145.0 MH/s (93.87ms)

Hashtype: Kerberos 5 TGS-REP etype 23

Speed.Dev.#1.....:   144.7 MH/s (94.04ms)

Hashtype: DNSSEC (NSEC3)

Speed.Dev.#1.....:  1569.5 MH/s (69.17ms)

Hashtype: PostgreSQL CRAM (MD5)

Speed.Dev.#1.....:  3210.1 MH/s (67.90ms)

Hashtype: MySQL CRAM (SHA1)

Speed.Dev.#1.....:  1092.3 MH/s (49.85ms)

Hashtype: SIP digest authentication (MD5)

Speed.Dev.#1.....:   989.3 MH/s (55.07ms)

Hashtype: SMF (Simple Machines Forum) > v1.1

Speed.Dev.#1.....:  3196.9 MH/s (68.17ms)

Hashtype: vBulletin < v3.8.5

Speed.Dev.#1.....:  3380.8 MH/s (64.47ms)

Hashtype: vBulletin >= v3.8.5

Speed.Dev.#1.....:  2309.4 MH/s (94.39ms)

Hashtype: IPB2+ (Invision Power Board), MyBB 1.2+

Speed.Dev.#1.....:  2436.6 MH/s (89.45ms)

Hashtype: WBB3 (Woltlab Burning Board)

Speed.Dev.#1.....:   618.5 MH/s (88.03ms)

Hashtype: OpenCart

Speed.Dev.#1.....:   975.2 MH/s (55.86ms)

Hashtype: Joomla < 2.5.18

Speed.Dev.#1.....: 11604.0 MH/s (75.14ms)

Hashtype: PHPS

Speed.Dev.#1.....:  3380.8 MH/s (64.47ms)

Hashtype: Drupal7

Speed.Dev.#1.....:    25793 H/s (64.36ms)

Hashtype: osCommerce, xt:Commerce

Speed.Dev.#1.....:  6162.3 MH/s (70.74ms)

Hashtype: PrestaShop

Speed.Dev.#1.....:  3981.3 MH/s (54.74ms)

Hashtype: Django (SHA-1)

Speed.Dev.#1.....:  3227.2 MH/s (67.54ms)

Hashtype: Django (PBKDF2-SHA256)

Speed.Dev.#1.....:    29071 H/s (93.44ms)

Hashtype: MediaWiki B type

Speed.Dev.#1.....:  3165.5 MH/s (68.85ms)

Hashtype: Redmine

Speed.Dev.#1.....:  1322.7 MH/s (82.07ms)

Hashtype: PunBB

Speed.Dev.#1.....:  1329.4 MH/s (81.64ms)

Hashtype: PostgreSQL

Speed.Dev.#1.....: 11436.6 MH/s (76.21ms)

Hashtype: MSSQL (2000)

Speed.Dev.#1.....:  3916.1 MH/s (55.65ms)

Hashtype: MSSQL (2005)

Speed.Dev.#1.....:  3875.5 MH/s (56.23ms)

Hashtype: MSSQL (2012, 2014)

Speed.Dev.#1.....:   480.8 MH/s (56.61ms)

Hashtype: MySQL323

Speed.Dev.#1.....: 25367.9 MH/s (68.73ms)

Hashtype: MySQL4.1/MySQL5

Speed.Dev.#1.....:  1759.9 MH/s (61.65ms)

Hashtype: Oracle H: Type (Oracle 7+)

Speed.Dev.#1.....:   491.5 MH/s (110.44ms)

Hashtype: Oracle S: Type (Oracle 11+)

Speed.Dev.#1.....:  3822.4 MH/s (56.99ms)

Hashtype: Oracle T: Type (Oracle 12+)

Speed.Dev.#1.....:    50151 H/s (65.22ms)

Hashtype: Sybase ASE

Speed.Dev.#1.....:   137.3 MH/s (49.02ms)

Hashtype: Episerver 6.x < .NET 4

Speed.Dev.#1.....:  3240.1 MH/s (67.56ms)

Hashtype: Episerver 6.x >= .NET 4

Speed.Dev.#1.....:  1317.0 MH/s (82.56ms)

Hashtype: Apache $apr1$ MD5, md5apr1, MD5 (APR)

Speed.Dev.#1.....:  4968.1 kH/s (84.36ms)

Hashtype: ColdFusion 10+

Speed.Dev.#1.....:   836.6 MH/s (65.15ms)

Hashtype: hMailServer

Speed.Dev.#1.....:  1329.5 MH/s (83.32ms)

Hashtype: nsldap, SHA-1(Base64), Netscape LDAP SHA

Speed.Dev.#1.....:  3872.9 MH/s (57.02ms)

Hashtype: nsldaps, SSHA-1(Base64), Netscape LDAP SSHA

Speed.Dev.#1.....:  3853.5 MH/s (56.99ms)

Hashtype: SSHA-256(Base64), LDAP {SSHA256}

Speed.Dev.#1.....:  1461.1 MH/s (74.55ms)

Hashtype: SSHA-512(Base64), LDAP {SSHA512}

Speed.Dev.#1.....:   495.7 MH/s (54.95ms)

Hashtype: LM

Speed.Dev.#1.....:  9632.2 MH/s (90.48ms)

Hashtype: NTLM

Speed.Dev.#1.....: 19079.4 MH/s (91.44ms)

Hashtype: Domain Cached Credentials (DCC), MS Cache

Speed.Dev.#1.....:  5422.3 MH/s (80.43ms)

Hashtype: Domain Cached Credentials 2 (DCC2), MS Cache 2

Speed.Dev.#1.....:   155.5 kH/s (67.06ms)

Hashtype: MS-AzureSync PBKDF2-HMAC-SHA256

Speed.Dev.#1.....:  5354.4 kH/s (65.00ms)

Hashtype: descrypt, DES (Unix), Traditional DES

Speed.Dev.#1.....:   469.5 MH/s (57.96ms)

Hashtype: BSDiCrypt, Extended DES

Speed.Dev.#1.....:   761.4 kH/s (92.63ms)

Hashtype: md5crypt, MD5 (Unix), Cisco-IOS $1$ (MD5)

Speed.Dev.#1.....:  4925.3 kH/s (85.03ms)

Hashtype: bcrypt $2*$, Blowfish (Unix)

Speed.Dev.#1.....:     7119 H/s (26.25ms)

Hashtype: sha256crypt $5$, SHA256 (Unix)

Speed.Dev.#1.....:   180.6 kH/s (58.42ms)

Hashtype: sha512crypt $6$, SHA512 (Unix)

Speed.Dev.#1.....:    73770 H/s (72.64ms)

Hashtype: OSX v10.4, OSX v10.5, OSX v10.6

Speed.Dev.#1.....:  3221.2 MH/s (67.54ms)

Hashtype: OSX v10.7

Speed.Dev.#1.....:   434.5 MH/s (62.56ms)

Hashtype: OSX v10.8+ (PBKDF2-SHA512)

Speed.Dev.#1.....:     6002 H/s (64.43ms)

Hashtype: AIX {smd5}

Speed.Dev.#1.....:  4924.1 kH/s (84.86ms)

Hashtype: AIX {ssha1}

Speed.Dev.#1.....: 21974.1 kH/s (67.64ms)

Hashtype: AIX {ssha256}

Speed.Dev.#1.....:  7233.0 kH/s (55.37ms)

Hashtype: AIX {ssha512}

Speed.Dev.#1.....:  3099.7 kH/s (64.55ms)

Hashtype: Cisco-PIX MD5

Speed.Dev.#1.....:  7695.3 MH/s (56.58ms)

Hashtype: Cisco-ASA MD5

Speed.Dev.#1.....:  8586.8 MH/s (50.69ms)

Hashtype: Cisco-IOS type 4 (SHA256)

Speed.Dev.#1.....:  1464.6 MH/s (74.04ms)

Hashtype: Cisco-IOS $8$ (PBKDF2-SHA256)

Speed.Dev.#1.....:    29064 H/s (93.37ms)

Hashtype: Cisco-IOS $9$ (scrypt)

Speed.Dev.#1.....:     3243 H/s (512.39ms)

Hashtype: Juniper NetScreen/SSG (ScreenOS)

Speed.Dev.#1.....:  6089.3 MH/s (71.22ms)

Hashtype: Juniper IVE

Speed.Dev.#1.....:  4955.5 kH/s (84.41ms)

Hashtype: Samsung Android Password/PIN

Speed.Dev.#1.....:  2582.1 kH/s (81.54ms)

Hashtype: Citrix NetScaler

Speed.Dev.#1.....:  3482.0 MH/s (62.55ms)

Hashtype: RACF

Speed.Dev.#1.....:  1293.1 MH/s (84.67ms)

Hashtype: GRUB 2

Speed.Dev.#1.....:    20867 H/s (65.27ms)

Hashtype: Radmin2

Speed.Dev.#1.....:  4052.1 MH/s (53.84ms)

Hashtype: SAP CODVN B (BCODE)

Speed.Dev.#1.....:  1151.8 MH/s (94.35ms)

Hashtype: SAP CODVN F/G (PASSCODE)

Speed.Dev.#1.....:   509.8 MH/s (106.97ms)

Hashtype: SAP CODVN H (PWDSALTEDHASH) iSSHA-1

Speed.Dev.#1.....:  2890.8 kH/s (72.84ms)

Hashtype: Lotus Notes/Domino 5

Speed.Dev.#1.....:   106.6 MH/s (127.91ms)

Hashtype: Lotus Notes/Domino 6

Speed.Dev.#1.....: 35739.2 kH/s (95.33ms)

Hashtype: Lotus Notes/Domino 8

Speed.Dev.#1.....:   314.6 kH/s (67.02ms)

Hashtype: PeopleSoft

Speed.Dev.#1.....:  3905.4 MH/s (55.73ms)

Hashtype: PeopleSoft PS_TOKEN

Speed.Dev.#1.....:  1501.8 MH/s (72.23ms)

Hashtype: 7-Zip

Speed.Dev.#1.....:     4583 H/s (90.24ms)

Hashtype: WinZip

Speed.Dev.#1.....:   518.6 kH/s (46.60ms)

Hashtype: RAR3-hp

Speed.Dev.#1.....:    17463 H/s (47.53ms)

Hashtype: RAR5

Speed.Dev.#1.....:    17731 H/s (93.43ms)

Hashtype: AxCrypt

Speed.Dev.#1.....:    58020 H/s (187.01ms)

Hashtype: AxCrypt in-memory SHA1

Speed.Dev.#1.....:  3630.8 MH/s (60.00ms)

Hashtype: TrueCrypt PBKDF2-HMAC-RIPEMD160 + XTS 512 bit

Speed.Dev.#1.....:   133.7 kH/s (94.99ms)

Hashtype: TrueCrypt PBKDF2-HMAC-SHA512 + XTS 512 bit

Speed.Dev.#1.....:   196.1 kH/s (59.29ms)

Hashtype: TrueCrypt PBKDF2-HMAC-Whirlpool + XTS 512 bit

Speed.Dev.#1.....:    17871 H/s (184.16ms)

Hashtype: TrueCrypt PBKDF2-HMAC-RIPEMD160 + XTS 512 bit + boot-mode

Speed.Dev.#1.....:   254.9 kH/s (87.38ms)

Hashtype: VeraCrypt PBKDF2-HMAC-RIPEMD160 + XTS 512 bit

Speed.Dev.#1.....:      405 H/s (97.70ms)

Hashtype: VeraCrypt PBKDF2-HMAC-SHA512 + XTS 512 bit

Speed.Dev.#1.....:      401 H/s (64.69ms)

Hashtype: VeraCrypt PBKDF2-HMAC-Whirlpool + XTS 512 bit

Speed.Dev.#1.....:       30 H/s (184.28ms)

Hashtype: VeraCrypt PBKDF2-HMAC-RIPEMD160 + XTS 512 bit + boot-mode

Speed.Dev.#1.....:      842 H/s (97.53ms)

Hashtype: VeraCrypt PBKDF2-HMAC-SHA256 + XTS 512 bit

Speed.Dev.#1.....:      527 H/s (50.22ms)

Hashtype: VeraCrypt PBKDF2-HMAC-SHA256 + XTS 512 bit + boot-mode

Speed.Dev.#1.....:     1331 H/s (50.31ms)

Hashtype: Android FDE <= 4.3

Speed.Dev.#1.....:   388.0 kH/s (67.89ms)

Hashtype: Android FDE (Samsung DEK)

Speed.Dev.#1.....:   141.9 kH/s (93.51ms)

Hashtype: eCryptfs

Speed.Dev.#1.....:     6432 H/s (64.27ms)

Hashtype: MS Office <= 2003 $0/$1, MD5 + RC4

Speed.Dev.#1.....:   113.4 MH/s (59.98ms)

Hashtype: MS Office <= 2003 $0/$1, MD5 + RC4, collider #1

Speed.Dev.#1.....:   161.5 MH/s (84.29ms)

Hashtype: MS Office <= 2003 $3/$4, SHA1 + RC4

Speed.Dev.#1.....:   139.2 MH/s (97.75ms)

Hashtype: MS Office <= 2003 $3/$4, SHA1 + RC4, collider #1

Speed.Dev.#1.....:   158.8 MH/s (85.77ms)

Hashtype: MS Office 2007

Speed.Dev.#1.....:    62629 H/s (69.50ms)

Hashtype: MS Office 2010

Speed.Dev.#1.....:    31265 H/s (69.61ms)

Hashtype: MS Office 2013

Speed.Dev.#1.....:     4262 H/s (63.66ms)

Hashtype: PDF 1.1 - 1.3 (Acrobat 2 - 4)

Speed.Dev.#1.....:   168.1 MH/s (81.03ms)

Hashtype: PDF 1.1 - 1.3 (Acrobat 2 - 4), collider #1

Speed.Dev.#1.....:   186.6 MH/s (73.01ms)

Hashtype: PDF 1.4 - 1.6 (Acrobat 5 - 8)

Speed.Dev.#1.....:  8302.2 kH/s (49.43ms)

Hashtype: PDF 1.7 Level 3 (Acrobat 9)

Speed.Dev.#1.....:  1468.5 MH/s (73.91ms)

Hashtype: PDF 1.7 Level 8 (Acrobat 10 - 11)

Speed.Dev.#1.....:    16166 H/s (342.94ms)

Hashtype: Password Safe v2

Speed.Dev.#1.....:   153.7 kH/s (55.31ms)

Hashtype: Password Safe v3

Speed.Dev.#1.....:   568.8 kH/s (84.80ms)

Hashtype: LastPass + LastPass sniffed

Speed.Dev.#1.....:  1080.5 kH/s (96.99ms)

Hashtype: 1Password, agilekeychain

Speed.Dev.#1.....:  1560.0 kH/s (67.13ms)

Hashtype: 1Password, cloudkeychain

Speed.Dev.#1.....:     5144 H/s (66.08ms)

Hashtype: Bitcoin/Litecoin wallet.dat

Speed.Dev.#1.....:     2112 H/s (64.29ms)

Hashtype: Blockchain, My Wallet

Speed.Dev.#1.....: 36431.5 kH/s (22.95ms)

Hashtype: KeePass 1 (AES/Twofish) and KeePass 2 (AES)

Speed.Dev.#1.....:    68870 H/s (131.75ms)

Hashtype: ArubaOS

Speed.Dev.#1.....:  3219.4 MH/s (67.68ms)

Started: xxx xxx xx xx:41:11 20xx
Stopped: xxx xxx xx xx:04:05 20xx
```
