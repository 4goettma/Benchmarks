## Nvidia GTX 970 (EVGA FTW ACX2.0) Hashcat Benchmark

**System** Dell Optiplex 330

**CPU** Intel Core 2 Duo E4500 Processor (2.2 GHz, 2 MB L2 cache, 800 MHz FSB)

**RAM** 2 GB DDR2 Non-ECC SDRAM, 667 MHz (or 800 MHz ?)

**GPU** Nvidia GTX 970 (EVGA FTW ACX 2.0) (Base 1216 MHz, Boost 1367 MHz)

**OS** Windows 7 Professional 64 bit

**Software** Hashcat v3.5.0, Nvidia driver 382.05

### Benchmark

```
hashcat (v3.5.0) starting in benchmark mode...

Device #1: GeForce GTX 970, 1024/4096 MB allocatable, 13MCU

Hashtype: MD4

Speed.Dev.#1.....: 21078.7 MH/s (82.52ms)

Hashtype: MD5

Speed.Dev.#1.....: 11554.5 MH/s (75.13ms)

Hashtype: Half MD5

Speed.Dev.#1.....:  7341.8 MH/s (59.04ms)

Hashtype: SHA1

Speed.Dev.#1.....:  3931.6 MH/s (55.24ms)

Hashtype: SHA-256

Speed.Dev.#1.....:  1462.7 MH/s (73.80ms)

Hashtype: SHA-384

Speed.Dev.#1.....:   487.0 MH/s (55.64ms)

Hashtype: SHA-512

Speed.Dev.#1.....:   497.4 MH/s (54.50ms)

Hashtype: SHA-3 (Keccak)

Speed.Dev.#1.....:   380.0 MH/s (71.38ms)

Hashtype: SipHash

Speed.Dev.#1.....: 13661.8 MH/s (63.60ms)

Hashtype: Skip32 (PT = $salt, key = $pass)

Speed.Dev.#1.....:  2511.5 MH/s (13.16ms)

Hashtype: RIPEMD-160

Speed.Dev.#1.....:  2251.9 MH/s (96.31ms)

Hashtype: Whirlpool

Speed.Dev.#1.....:   126.7 MH/s (107.28ms)

Hashtype: GOST R 34.11-94

Speed.Dev.#1.....:   119.8 MH/s (113.51ms)

Hashtype: GOST R 34.11-2012 (Streebog) 256-bit

Speed.Dev.#1.....: 24990.2 kH/s (269.25ms)

Hashtype: GOST R 34.11-2012 (Streebog) 512-bit

Speed.Dev.#1.....: 24851.7 kH/s (270.77ms)

Hashtype: DES (PT = $salt, key = $pass)

Speed.Dev.#1.....:  9415.3 MH/s (92.13ms)

Hashtype: 3DES (PT = $salt, key = $pass)

Speed.Dev.#1.....:   250.4 MH/s (54.21ms)

Hashtype: phpass, WordPress (MD5), phpBB3 (MD5), Joomla (MD5)

Speed.Dev.#1.....:  3319.0 kH/s (62.37ms)

Hashtype: scrypt

Speed.Dev.#1.....:   318.8 kH/s (19.18ms)

Hashtype: PBKDF2-HMAC-MD5

Speed.Dev.#1.....:  3666.6 kH/s (56.05ms)

Hashtype: PBKDF2-HMAC-SHA1

Speed.Dev.#1.....:  1538.6 kH/s (56.55ms)

Hashtype: PBKDF2-HMAC-SHA256

Speed.Dev.#1.....:   570.4 kH/s (80.26ms)

Hashtype: PBKDF2-HMAC-SHA512

Speed.Dev.#1.....:   204.9 kH/s (60.06ms)

Hashtype: Skype

Speed.Dev.#1.....:  6191.7 MH/s (70.17ms)

Hashtype: WPA/WPA2

Speed.Dev.#1.....:   190.1 kH/s (69.40ms)

Hashtype: IKE-PSK MD5

Speed.Dev.#1.....:   908.7 MH/s (59.75ms)

Hashtype: IKE-PSK SHA1

Speed.Dev.#1.....:   382.3 MH/s (70.95ms)

Hashtype: NetNTLMv1 / NetNTLMv1+ESS

Speed.Dev.#1.....: 10632.6 MH/s (81.75ms)

Hashtype: NetNTLMv2

Speed.Dev.#1.....:   831.7 MH/s (65.31ms)

Hashtype: IPMI2 RAKP HMAC-SHA1

Speed.Dev.#1.....:   767.5 MH/s (70.66ms)

Hashtype: Kerberos 5 AS-REQ Pre-Auth etype 23

Speed.Dev.#1.....:   138.5 MH/s (98.00ms)

Hashtype: Kerberos 5 TGS-REP etype 23

Speed.Dev.#1.....:   145.1 MH/s (93.55ms)

Hashtype: DNSSEC (NSEC3)

Speed.Dev.#1.....:  1563.1 MH/s (69.21ms)

Hashtype: PostgreSQL CRAM (MD5)

Speed.Dev.#1.....:  3197.0 MH/s (67.92ms)

Hashtype: MySQL CRAM (SHA1)

Speed.Dev.#1.....:  1087.1 MH/s (49.81ms)

Hashtype: SIP digest authentication (MD5)

Speed.Dev.#1.....:  1724.0 MH/s (62.76ms)

Hashtype: SMF (Simple Machines Forum) > v1.1

Speed.Dev.#1.....:  3162.1 MH/s (68.73ms)

Hashtype: vBulletin < v3.8.5

Speed.Dev.#1.....:  3277.9 MH/s (66.24ms)

Hashtype: vBulletin >= v3.8.5

Speed.Dev.#1.....:  2336.5 MH/s (93.06ms)

Hashtype: IPB2+ (Invision Power Board), MyBB 1.2+

Speed.Dev.#1.....:  2381.5 MH/s (91.30ms)

Hashtype: WBB3 (Woltlab Burning Board)

Speed.Dev.#1.....:   611.8 MH/s (88.75ms)

Hashtype: OpenCart

Speed.Dev.#1.....:   974.9 MH/s (55.70ms)

Hashtype: Joomla < 2.5.18

Speed.Dev.#1.....: 11436.2 MH/s (76.02ms)

Hashtype: PHPS

Speed.Dev.#1.....:  3251.1 MH/s (66.72ms)

Hashtype: Drupal7

Speed.Dev.#1.....:    25626 H/s (64.36ms)

Hashtype: osCommerce, xt:Commerce

Speed.Dev.#1.....:  6127.6 MH/s (70.85ms)

Hashtype: PrestaShop

Speed.Dev.#1.....:  4006.6 MH/s (54.16ms)

Hashtype: Django (SHA-1)

Speed.Dev.#1.....:  3158.9 MH/s (68.69ms)

Hashtype: Django (PBKDF2-SHA256)

Speed.Dev.#1.....:    28728 H/s (94.17ms)

Hashtype: MediaWiki B type

Speed.Dev.#1.....:  3178.7 MH/s (68.32ms)

Hashtype: Redmine

Speed.Dev.#1.....:  1319.9 MH/s (82.01ms)

Hashtype: PunBB

Speed.Dev.#1.....:  1311.6 MH/s (82.57ms)

Hashtype: PostgreSQL

Speed.Dev.#1.....: 11541.0 MH/s (75.34ms)

Hashtype: MSSQL (2000)

Speed.Dev.#1.....:  3877.8 MH/s (55.96ms)

Hashtype: MSSQL (2005)

Speed.Dev.#1.....:  3873.5 MH/s (56.02ms)

Hashtype: MSSQL (2012, 2014)

Speed.Dev.#1.....:   477.8 MH/s (56.76ms)

Hashtype: MySQL323

Speed.Dev.#1.....: 24442.4 MH/s (71.14ms)

Hashtype: MySQL4.1/MySQL5

Speed.Dev.#1.....:  1754.4 MH/s (61.63ms)

Hashtype: Oracle H: Type (Oracle 7+)

Speed.Dev.#1.....:   490.4 MH/s (110.47ms)

Hashtype: Oracle S: Type (Oracle 11+)

Speed.Dev.#1.....:  3901.3 MH/s (55.39ms)

Hashtype: Oracle T: Type (Oracle 12+)

Speed.Dev.#1.....:    50408 H/s (65.60ms)

Hashtype: Sybase ASE

Speed.Dev.#1.....:   136.9 MH/s (48.95ms)

Hashtype: Episerver 6.x < .NET 4

Speed.Dev.#1.....:  3162.7 MH/s (68.73ms)

Hashtype: Episerver 6.x >= .NET 4

Speed.Dev.#1.....:  1296.8 MH/s (83.54ms)

Hashtype: Apache $apr1$ MD5, md5apr1, MD5 (APR)

Speed.Dev.#1.....:  4961.5 kH/s (83.86ms)

Hashtype: ColdFusion 10+

Speed.Dev.#1.....:   842.0 MH/s (64.51ms)

Hashtype: hMailServer

Speed.Dev.#1.....:  1284.3 MH/s (84.34ms)

Hashtype: nsldap, SHA-1(Base64), Netscape LDAP SHA

Speed.Dev.#1.....:  3882.2 MH/s (55.91ms)

Hashtype: nsldaps, SSHA-1(Base64), Netscape LDAP SSHA

Speed.Dev.#1.....:  3889.9 MH/s (55.85ms)

Hashtype: SSHA-256(Base64), LDAP {SSHA256}

Speed.Dev.#1.....:  1450.0 MH/s (74.62ms)

Hashtype: SSHA-512(Base64), LDAP {SSHA512}

Speed.Dev.#1.....:   493.2 MH/s (54.98ms)

Hashtype: LM

Speed.Dev.#1.....:  9366.4 MH/s (92.62ms)

Hashtype: NTLM

Speed.Dev.#1.....: 19056.0 MH/s (91.32ms)

Hashtype: Domain Cached Credentials (DCC), MS Cache

Speed.Dev.#1.....:  5332.3 MH/s (81.55ms)

Hashtype: Domain Cached Credentials 2 (DCC2), MS Cache 2

Speed.Dev.#1.....:   154.6 kH/s (67.15ms)

Hashtype: MS-AzureSync PBKDF2-HMAC-SHA256

Speed.Dev.#1.....:  5154.0 kH/s (65.53ms)

Hashtype: descrypt, DES (Unix), Traditional DES

Speed.Dev.#1.....:   464.9 MH/s (58.17ms)

Hashtype: BSDiCrypt, Extended DES

Speed.Dev.#1.....:   757.9 kH/s (92.72ms)

Hashtype: md5crypt, MD5 (Unix), Cisco-IOS $1$ (MD5)

Speed.Dev.#1.....:  4958.9 kH/s (83.96ms)

Hashtype: bcrypt $2*$, Blowfish (Unix)

Speed.Dev.#1.....:     6784 H/s (27.33ms)

Hashtype: sha256crypt $5$, SHA256 (Unix)

Speed.Dev.#1.....:   180.6 kH/s (58.14ms)

Hashtype: sha512crypt $6$, SHA512 (Unix)

Speed.Dev.#1.....:    73728 H/s (72.61ms)

Hashtype: OSX v10.4, OSX v10.5, OSX v10.6

Speed.Dev.#1.....:  3165.3 MH/s (68.69ms)

Hashtype: OSX v10.7

Speed.Dev.#1.....:   433.7 MH/s (62.57ms)

Hashtype: OSX v10.8+ (PBKDF2-SHA512)

Speed.Dev.#1.....:     5860 H/s (65.83ms)

Hashtype: AIX {smd5}

Speed.Dev.#1.....:  4948.6 kH/s (84.00ms)

Hashtype: AIX {ssha1}

Speed.Dev.#1.....: 21767.5 kH/s (67.97ms)

Hashtype: AIX {ssha256}

Speed.Dev.#1.....:  7298.8 kH/s (54.60ms)

Hashtype: AIX {ssha512}

Speed.Dev.#1.....:  3086.9 kH/s (64.33ms)

Hashtype: Cisco-PIX MD5

Speed.Dev.#1.....:  7683.3 MH/s (56.54ms)

Hashtype: Cisco-ASA MD5

Speed.Dev.#1.....:  8528.3 MH/s (50.90ms)

Hashtype: Cisco-IOS type 4 (SHA256)

Speed.Dev.#1.....:  1463.0 MH/s (73.97ms)

Hashtype: Cisco-IOS $8$ (PBKDF2-SHA256)

Speed.Dev.#1.....:    28829 H/s (94.04ms)

Hashtype: Cisco-IOS $9$ (scrypt)

Speed.Dev.#1.....:     3232 H/s (513.81ms)

Hashtype: Juniper NetScreen/SSG (ScreenOS)

Speed.Dev.#1.....:  6071.0 MH/s (71.56ms)

Hashtype: Juniper IVE

Speed.Dev.#1.....:  4980.5 kH/s (83.57ms)

Hashtype: Samsung Android Password/PIN

Speed.Dev.#1.....:  2581.8 kH/s (81.23ms)

Hashtype: Citrix NetScaler

Speed.Dev.#1.....:  3468.7 MH/s (62.66ms)

Hashtype: RACF

Speed.Dev.#1.....:  1247.6 MH/s (87.14ms)

Hashtype: GRUB 2

Speed.Dev.#1.....:    19978 H/s (65.79ms)

Hashtype: Radmin2

Speed.Dev.#1.....:  4027.4 MH/s (53.90ms)

Hashtype: SAP CODVN B (BCODE)

Speed.Dev.#1.....:  1149.9 MH/s (94.21ms)

Hashtype: SAP CODVN F/G (PASSCODE)

Speed.Dev.#1.....:   522.4 MH/s (104.11ms)

Hashtype: SAP CODVN H (PWDSALTEDHASH) iSSHA-1

Speed.Dev.#1.....:  2865.4 kH/s (73.02ms)

Hashtype: Lotus Notes/Domino 5

Speed.Dev.#1.....:   105.4 MH/s (129.01ms)

Hashtype: Lotus Notes/Domino 6

Speed.Dev.#1.....: 35589.3 kH/s (95.47ms)

Hashtype: Lotus Notes/Domino 8

Speed.Dev.#1.....:   312.7 kH/s (67.08ms)

Hashtype: PeopleSoft

Speed.Dev.#1.....:  3863.3 MH/s (56.18ms)

Hashtype: PeopleSoft PS_TOKEN

Speed.Dev.#1.....:  1506.0 MH/s (71.85ms)

Hashtype: 7-Zip

Speed.Dev.#1.....:     4615 H/s (89.28ms)

Hashtype: WinZip

Speed.Dev.#1.....:   515.3 kH/s (46.55ms)

Hashtype: RAR3-hp

Speed.Dev.#1.....:    18975 H/s (43.37ms)

Hashtype: RAR5

Speed.Dev.#1.....:    17557 H/s (94.16ms)

Hashtype: AxCrypt

Speed.Dev.#1.....:    57876 H/s (186.99ms)

Hashtype: AxCrypt in-memory SHA1

Speed.Dev.#1.....:  3666.6 MH/s (59.01ms)

Hashtype: TrueCrypt PBKDF2-HMAC-RIPEMD160 + XTS 512 bit

Speed.Dev.#1.....:   132.4 kH/s (95.23ms)

Hashtype: TrueCrypt PBKDF2-HMAC-SHA512 + XTS 512 bit

Speed.Dev.#1.....:   193.3 kH/s (59.61ms)

Hashtype: TrueCrypt PBKDF2-HMAC-Whirlpool + XTS 512 bit

Speed.Dev.#1.....:    17874 H/s (183.61ms)

Hashtype: TrueCrypt PBKDF2-HMAC-RIPEMD160 + XTS 512 bit + boot-mode

Speed.Dev.#1.....:   253.1 kH/s (87.08ms)

Hashtype: VeraCrypt PBKDF2-HMAC-RIPEMD160 + XTS 512 bit

Speed.Dev.#1.....:      403 H/s (97.54ms)

Hashtype: VeraCrypt PBKDF2-HMAC-SHA512 + XTS 512 bit

Speed.Dev.#1.....:      402 H/s (64.98ms)

Hashtype: VeraCrypt PBKDF2-HMAC-Whirlpool + XTS 512 bit

Speed.Dev.#1.....:       30 H/s (184.17ms)

Hashtype: VeraCrypt PBKDF2-HMAC-RIPEMD160 + XTS 512 bit + boot-mode

Speed.Dev.#1.....:      839 H/s (97.43ms)

Hashtype: VeraCrypt PBKDF2-HMAC-SHA256 + XTS 512 bit

Speed.Dev.#1.....:      528 H/s (50.43ms)

Hashtype: VeraCrypt PBKDF2-HMAC-SHA256 + XTS 512 bit + boot-mode

Speed.Dev.#1.....:     1336 H/s (50.44ms)

Hashtype: Android FDE <= 4.3

Speed.Dev.#1.....:   385.1 kH/s (68.00ms)

Hashtype: Android FDE (Samsung DEK)

Speed.Dev.#1.....:   140.1 kH/s (94.23ms)

Hashtype: eCryptfs

Speed.Dev.#1.....:     6386 H/s (64.23ms)

Hashtype: MS Office <= 2003 $0/$1, MD5 + RC4

Speed.Dev.#1.....:   125.2 MH/s (53.97ms)

Hashtype: MS Office <= 2003 $0/$1, MD5 + RC4, collider #1

Speed.Dev.#1.....:   159.2 MH/s (85.31ms)

Hashtype: MS Office <= 2003 $3/$4, SHA1 + RC4

Speed.Dev.#1.....:   151.8 MH/s (89.40ms)

Hashtype: MS Office <= 2003 $3/$4, SHA1 + RC4, collider #1

Speed.Dev.#1.....:   170.4 MH/s (79.50ms)

Hashtype: MS Office 2007

Speed.Dev.#1.....:    62211 H/s (69.40ms)

Hashtype: MS Office 2010

Speed.Dev.#1.....:    31033 H/s (69.53ms)

Hashtype: MS Office 2013

Speed.Dev.#1.....:     4234 H/s (63.59ms)

Hashtype: PDF 1.1 - 1.3 (Acrobat 2 - 4)

Speed.Dev.#1.....:   173.7 MH/s (78.22ms)

Hashtype: PDF 1.1 - 1.3 (Acrobat 2 - 4), collider #1

Speed.Dev.#1.....:   190.3 MH/s (71.35ms)

Hashtype: PDF 1.4 - 1.6 (Acrobat 5 - 8)

Speed.Dev.#1.....:  8345.6 kH/s (48.35ms)

Hashtype: PDF 1.7 Level 3 (Acrobat 9)

Speed.Dev.#1.....:  1460.1 MH/s (73.99ms)

Hashtype: PDF 1.7 Level 8 (Acrobat 10 - 11)

Speed.Dev.#1.....:    18707 H/s (354.84ms)

Hashtype: Password Safe v2

Speed.Dev.#1.....:   160.1 kH/s (51.51ms)

Hashtype: Password Safe v3

Speed.Dev.#1.....:   569.4 kH/s (84.18ms)

Hashtype: LastPass + LastPass sniffed

Speed.Dev.#1.....:  1092.2 kH/s (95.41ms)

Hashtype: 1Password, agilekeychain

Speed.Dev.#1.....:  1554.6 kH/s (66.70ms)

Hashtype: 1Password, cloudkeychain

Speed.Dev.#1.....:     5135 H/s (65.73ms)

Hashtype: Bitcoin/Litecoin wallet.dat

Speed.Dev.#1.....:     2095 H/s (64.34ms)

Hashtype: Blockchain, My Wallet

Speed.Dev.#1.....: 36586.7 kH/s (22.68ms)

Hashtype: KeePass 1 (AES/Twofish) and KeePass 2 (AES)

Speed.Dev.#1.....:    68397 H/s (131.91ms)

Hashtype: ArubaOS

Speed.Dev.#1.....:  3157.7 MH/s (68.79ms)

Started: xxx xxx xx xx:30:15 20xx
Stopped: xxx xxx xx xx:45:45 20xx
```
