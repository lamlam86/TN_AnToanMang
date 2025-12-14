# TN_AnToanMang
# 500 CÂU HỎI TRẮC NGHIỆM NETWORK SECURITY
## PCSE402 - Network Security

---

## UNIT I: INTRODUCTION

**Câu 1:** Network Security là gì?
A. Các biện pháp bảo vệ dữ liệu trong quá trình truyền
B. Các công cụ bảo vệ dữ liệu và chống lại hacker
C. Các biện pháp bảo vệ dữ liệu trên tập hợp các mạng kết nối
**D. Tất cả các đáp án trên**

**Câu 2:** Có bao nhiêu loại tấn công bảo mật cơ bản?
A. 2
B. 3
**C. 4**
D. 5

**Câu 3:** Tấn công nào sau đây là tấn công thụ động (Passive Attack)?
A. Masquerade
B. Replay
**C. Traffic analysis**
D. Denial of service

**Câu 4:** Tấn công nào sau đây là tấn công chủ động (Active Attack)?
A. Release of message contents
B. Traffic analysis
**C. Modification of messages**
D. Cả A và B

**Câu 5:** Dịch vụ bảo mật nào đảm bảo thông tin chỉ có thể đọc bởi các bên được ủy quyền?
A. Authentication
**B. Confidentiality**
C. Integrity
D. Non-repudiation

**Câu 6:** Mô hình mã hóa đối xứng (Symmetric cipher) có bao nhiêu thành phần?
A. 3
B. 4
**C. 5**
D. 6

**Câu 7:** Hệ thống mã hóa được phân loại theo bao nhiều chiều độc lập?
A. 1
B. 2
**C. 3**
D. 4

**Câu 8:** DES sử dụng khóa có độ dài bao nhiêu bit?
**A. 56 bit**
B. 64 bit
C. 128 bit
D. 256 bit

**Câu 9:** AES hỗ trợ các độ dài khóa nào?
**A. 128, 192, 256 bit**
B. 64, 128, 256 bit
C. 128, 256, 512 bit
D. 56, 128, 256 bit

**Câu 10:** Triple DES (3DES) sử dụng bao nhiêu khóa?
A. 1 khóa
B. 2 khóa
C. 3 khóa
**D. Có thể 2 hoặc 3 khóa**

**Câu 11:** Feistel Cipher Structure sử dụng bao nhiêu vòng (rounds) trong DES?
A. 8 rounds
**B. 16 rounds**
C. 32 rounds
D. 64 rounds

**Câu 12:** Trong DES, block size là bao nhiêu bit?
A. 32 bit
B. 56 bit
**C. 64 bit**
D. 128 bit

**Câu 13:** AES sử dụng cấu trúc nào?
A. Feistel Network
**B. Substitution-Permutation Network**
C. Stream Cipher
D. Block Cipher với Feistel

**Câu 14:** AES với khóa 128-bit sử dụng bao nhiêu rounds?
A. 8 rounds
**B. 10 rounds**
C. 12 rounds
D. 14 rounds

**Câu 15:** AES với khóa 256-bit sử dụng bao nhiêu rounds?
A. 10 rounds
B. 12 rounds
**C. 14 rounds**
D. 16 rounds

**Câu 16:** Trong AES, mỗi block được xử lý như một ma trận có kích thước:
A. 2x2 bytes
B. 3x3 bytes
**C. 4x4 bytes**
D. 5x5 bytes

**Câu 17:** Chế độ hoạt động nào của block cipher sử dụng IV (Initialization Vector)?
A. ECB
B. CBC
C. CFB
**D. Cả B và C**

**Câu 18:** Cipher Block Chaining (CBC) mode có đặc điểm gì?
A. Mỗi block được mã hóa độc lập
**B. Block hiện tại được XOR với ciphertext của block trước**
C. Sử dụng stream cipher
D. Không cần khóa

**Câu 19:** Cipher Feedback (CFB) mode chuyển đổi block cipher thành:
**A. Stream cipher**
B. Hash function
C. Public key cipher
D. MAC function

**Câu 20:** Link encryption và End-to-end encryption khác nhau ở điểm nào?
**A. Link encryption mã hóa toàn bộ packet, End-to-end chỉ mã hóa data**
B. End-to-end mã hóa toàn bộ packet, Link encryption chỉ mã hóa data
C. Không có sự khác biệt
D. Link encryption nhanh hơn

**Câu 21:** Caesar cipher là loại mã hóa nào?
**A. Substitution cipher**
B. Transposition cipher
C. Stream cipher
D. Block cipher

**Câu 22:** Vigenere cipher là loại mã hóa nào?
A. Monoalphabetic cipher
**B. Polyalphabetic cipher**
C. Transposition cipher
D. Stream cipher

**Câu 23:** Playfair cipher xử lý plaintext theo đơn vị:
A. 1 ký tự
**B. 2 ký tự (digram)**
C. 3 ký tự (trigram)
D. 4 ký tự

**Câu 24:** Rail fence cipher là loại mã hóa nào?
A. Substitution cipher
**B. Transposition cipher**
C. Stream cipher
D. Block cipher

**Câu 25:** Trong DES, S-box có kích thước:
**A. 4x16**
B. 6x4
C. 8x4
D. 4x8

**Câu 26:** DES sử dụng bao nhiêu S-boxes?
A. 4
B. 6
**C. 8**
D. 16

**Câu 27:** Trong DES, Expansion Permutation mở rộng từ bao nhiêu bit lên bao nhiêu bit?
**A. 32 bit lên 48 bit**
B. 48 bit lên 64 bit
C. 32 bit lên 64 bit
D. 56 bit lên 64 bit

**Câu 28:** Cryptanalysis là gì?
A. Nghệ thuật viết mật mã
**B. Nghệ thuật phá mật mã**
C. Nghệ thuật tạo khóa
D. Nghệ thuật phân phối khóa

**Câu 29:** Ciphertext Only Attack (COA) là gì?
A. Tấn công khi biết cả plaintext và ciphertext
**B. Tấn công khi chỉ biết ciphertext**
C. Tấn công khi có thể chọn plaintext
D. Tấn công brute force

**Câu 30:** Known Plaintext Attack (KPA) là gì?
**A. Tấn công khi biết một số cặp plaintext-ciphertext**
B. Tấn công khi chỉ biết ciphertext
C. Tấn công khi có thể chọn plaintext
D. Tấn công dictionary

**Câu 31:** Chosen Plaintext Attack (CPA) là gì?
A. Tấn công khi biết một số cặp plaintext-ciphertext
B. Tấn công khi chỉ biết ciphertext
**C. Tấn công khi có thể chọn plaintext để mã hóa**
D. Tấn công brute force

**Câu 32:** Brute Force Attack là gì?
**A. Tấn công thử tất cả các khóa có thể**
B. Tấn công sử dụng từ điển
C. Tấn công phân tích thống kê
D. Tấn công timing

**Câu 33:** Birthday Attack được sử dụng chống lại:
A. Symmetric encryption
**B. Hash functions**
C. Public key encryption
D. MAC

**Câu 34:** Man-in-the-Middle Attack nhắm vào:
A. Symmetric encryption
**B. Public key cryptosystems với key exchange**
C. Hash functions
D. Block ciphers

**Câu 35:** Side Channel Attack khai thác:
A. Lỗ hổng trong thuật toán
**B. Lỗ hổng trong implementation vật lý**
C. Lỗ hổng trong giao thức
D. Lỗ hổng trong key management

**Câu 36:** Timing Attack là loại:
**A. Side Channel Attack**
B. Cryptanalytic Attack
C. Brute Force Attack
D. Dictionary Attack

**Câu 37:** Power Analysis Attack là loại:
**A. Side Channel Attack**
B. Cryptanalytic Attack
C. Brute Force Attack
D. Dictionary Attack

**Câu 38:** Trong Feistel Cipher, decryption sử dụng:
A. Cùng khóa như encryption
B. Khóa ngược lại
**C. Subkey theo thứ tự ngược**
D. Không cần khóa

**Câu 39:** Avalanche effect trong cryptography là gì?
**A. Thay đổi nhỏ trong plaintext tạo ra thay đổi lớn trong ciphertext**
B. Thay đổi lớn trong plaintext tạo ra thay đổi nhỏ trong ciphertext
C. Ciphertext không thay đổi khi plaintext thay đổi
D. Khóa không ảnh hưởng đến ciphertext

**Câu 40:** Completeness trong block cipher là gì?
**A. Mỗi bit của ciphertext phụ thuộc vào nhiều bit của plaintext**
B. Mỗi bit của plaintext phụ thuộc vào nhiều bit của ciphertext
C. Ciphertext độc lập với plaintext
D. Khóa độc lập với plaintext

**Câu 41:** Trong DES, key schedule tạo ra bao nhiêu subkeys?
A. 8
**B. 16**
C. 32
D. 64

**Câu 42:** DES sử dụng thuật toán nào?
A. AES
B. RSA
**C. Modified DES với 25 iterations**
D. Triple DES

**Câu 43:** Trong UNIX password system, salt có độ dài bao nhiêu bit?
A. 8 bit
**B. 12 bit**
C. 16 bit
D. 24 bit

**Câu 44:** UNIX password system sử dụng bao nhiêu lần encryption?
A. 1 lần
B. 10 lần
**C. 25 lần**
D. 50 lần

**Câu 45:** Salt trong UNIX password system có mục đích gì?
A. Tăng độ dài password
B. Ngăn duplicate passwords
C. Tăng tốc độ encryption
**D. Giảm độ phức tạp**

**Câu 46:** Trong CBC mode, lỗi trong một block ảnh hưởng đến:
A. Chỉ block đó
**B. Block đó và block tiếp theo**
C. Tất cả các block
D. Không ảnh hưởng gì

**Câu 47:** Trong CFB mode, lỗi trong một block ảnh hưởng đến:
A. Chỉ block đó
**B. Block đó và block tiếp theo**
C. Tất cả các block
D. Không ảnh hưởng gì

**Câu 48:** ECB mode có nhược điểm gì?
A. Chậm
**B. Không an toàn với plaintext giống nhau**
C. Cần IV
D. Phức tạp

**Câu 49:** Location of encryption devices có mấy cách tiếp cận?
A. 1
**B. 2**
C. 3
D. 4

**Câu 50:** Key distribution trong symmetric encryption có bao nhiêu phương pháp?
A. 2
B. 3
**C. 4**
D. 5

---

## UNIT II: PUBLIC KEY CRYPTOGRAPHY AND MESSAGE AUTHENTICATION

**Câu 51:** Message Authentication đảm bảo:
A. Confidentiality
**B. Authentication và Integrity**
C. Non-repudiation
D. Tất cả các đáp án trên

**Câu 52:** Có bao nhiêu cách tiếp cận Message Authentication?
A. 2
**B. 3**
C. 4
D. 5

**Câu 53:** MAC là viết tắt của:
**A. Message Authentication Code**
B. Message Access Control
C. Message Authentication Cipher
D. Message Access Code

**Câu 54:** MAC sử dụng:
A. Chỉ public key
B. Chỉ private key
**C. Secret key (symmetric)**
D. Hash function không khóa

**Câu 55:** Hash function tạo ra output có độ dài:
A. Biến đổi
**B. Cố định**
C. Phụ thuộc vào input
D. Không xác định

**Câu 56:** SHA-1 tạo ra hash có độ dài bao nhiêu bit?
A. 128 bit
**B. 160 bit**
C. 256 bit
D. 512 bit

**Câu 57:** SHA-256 tạo ra hash có độ dài bao nhiêu bit?
A. 128 bit
B. 160 bit
**C. 256 bit**
D. 512 bit

**Câu 58:** SHA-512 tạo ra hash có độ dài bao nhiêu bit?
A. 256 bit
B. 384 bit
**C. 512 bit**
D. 1024 bit

**Câu 59:** HMAC sử dụng hash function nào?
A. Chỉ MD5
B. Chỉ SHA-1
**C. Bất kỳ hash function nào**
D. Chỉ SHA-256

**Câu 60:** HMAC sử dụng bao nhiêu khóa?
**A. 1 khóa**
B. 2 khóa
C. 3 khóa
D. Không cần khóa

**Câu 61:** Trong HMAC, ipad có giá trị hex là:
**A. 36**
B. 5C
C. FF
D. 00

**Câu 62:** Trong HMAC, opad có giá trị hex là:
A. 36
**B. 5C**
C. FF
D. 00

**Câu 63:** Public Key Cryptography sử dụng:
A. 1 khóa
**B. 2 khóa (public và private)**
C. 3 khóa
D. Không cần khóa

**Câu 64:** RSA là viết tắt của:
**A. Rivest, Shamir, Adleman**
B. Rivest, Shamir, Algorithm
C. Random, Secure, Algorithm
D. Rivest, Secure, Adleman

**Câu 65:** Trong RSA, n được tính bằng:
A. p + q
**B. p * q**
C. p - q
D. p / q

**Câu 66:** Trong RSA, φ(n) được tính bằng:
**A. (p-1)(q-1)**
B. p*q
C. p+q
D. p-q

**Câu 67:** Trong RSA, e phải thỏa mãn điều kiện gì?
**A. 1 < e < φ(n) và gcd(e, φ(n)) = 1**
B. e > φ(n)
C. e = φ(n)
D. e < 1

**Câu 68:** Trong RSA, d được tính bằng:
A. e mod φ(n)
**B. e^(-1) mod φ(n)**
C. n mod e
D. φ(n) mod e

**Câu 69:** RSA encryption công thức là:
**A. C = M^e mod n**
B. C = M^d mod n
C. C = M*e mod n
D. C = M/e mod n

**Câu 70:** RSA decryption công thức là:
A. M = C^e mod n
**B. M = C^d mod n**
C. M = C*e mod n
D. M = C/e mod n

**Câu 71:** Độ an toàn của RSA dựa trên:
A. Discrete logarithm problem
**B. Factoring large numbers**
C. Hash collision
D. Brute force

**Câu 72:** Diffie-Hellman Key Exchange được sử dụng để:
A. Mã hóa dữ liệu
**B. Trao đổi khóa bí mật**
C. Tạo chữ ký số
D. Xác thực

**Câu 73:** Diffie-Hellman sử dụng:
A. Factoring problem
**B. Discrete logarithm problem**
C. Hash function
D. Symmetric encryption

**Câu 74:** Trong Diffie-Hellman, α là gì?
A. Private key
B. Public key
**C. Primitive root**
D. Modulus

**Câu 75:** Trong Diffie-Hellman, q là gì?
A. Private key
B. Public key
**C. Prime number**
D. Generator

**Câu 76:** ElGamal Cryptosystem dựa trên:
A. Factoring problem
**B. Discrete logarithm problem**
C. Hash function
D. Symmetric encryption

**Câu 77:** ElGamal encryption tạo ra bao nhiêu giá trị ciphertext?
A. 1
**B. 2**
C. 3
D. 4

**Câu 78:** Digital Signature sử dụng:
A. Public key để ký, private key để verify
**B. Private key để ký, public key để verify**
C. Secret key để ký và verify
D. Hash function để ký

**Câu 79:** Digital Signature đảm bảo:
A. Confidentiality
**B. Authentication và Non-repudiation**
C. Chỉ Authentication
D. Chỉ Integrity

**Câu 80:** Trong Digital Signature, thường ký:
A. Toàn bộ message
**B. Hash của message**
C. Một phần message
D. Không ký gì

**Câu 81:** Key Management liên quan đến:
A. Key generation
B. Key distribution
C. Key revocation
**D. Tất cả các đáp án trên**

**Câu 82:** Public key distribution có bao nhiêu phương pháp?
A. 2
B. 3
**C. 4**
D. 5

**Câu 83:** Public Announcement của public key có nhược điểm gì?
A. Chậm
**B. Có thể bị giả mạo**
C. Tốn bộ nhớ
D. Phức tạp

**Câu 84:** Public-key Certificate được ký bởi:
**A. Certificate Authority (CA)**
B. User
C. Server
D. Router

**Câu 85:** X.509 certificate chứa thông tin gì?
A. Public key
B. User identity
C. Validity period
**D. Tất cả các đáp án trên**

**Câu 86:** Session key là gì?
**A. Khóa dùng cho một session**
B. Khóa dùng cho nhiều session
C. Khóa công khai
D. Khóa riêng

**Câu 87:** Interchange key là gì?
A. Khóa dùng cho một session
**B. Khóa liên kết với principal**
C. Khóa công khai
D. Khóa riêng

**Câu 88:** Forward Search Attack được ngăn chặn bởi:
**A. Session key**
B. Interchange key
C. Public key
D. Hash function

**Câu 89:** Message Authentication Code (MAC) cung cấp:
A. Confidentiality
**B. Authentication và Integrity**
C. Non-repudiation
D. Tất cả các đáp án trên

**Câu 90:** Hash function một chiều có nghĩa là:
**A. Dễ tính hash, khó tìm input**
B. Dễ tìm input từ hash
C. Hash có thể đảo ngược
D. Hash không cố định

**Câu 91:** Collision resistance trong hash function là:
**A. Khó tìm hai input có cùng hash**
B. Dễ tìm hai input có cùng hash
C. Hash luôn giống nhau
D. Hash luôn khác nhau

**Câu 92:** Preimage resistance trong hash function là:
**A. Khó tìm input từ hash**
B. Dễ tìm input từ hash
C. Hash có thể đảo ngược
D. Hash không cố định

**Câu 93:** SHA-0 được công bố năm nào?
A. 1990
**B. 1993**
C. 1995
D. 2000

**Câu 94:** SHA-1 được thiết kế để:
A. Thay thế SHA-0
B. Thay thế MD5
C. Sửa lỗi SHA-0
**D. Cả A và C**

**Câu 95:** SHA-3 được chọn từ thuật toán nào?
A. MD5
B. SHA-2
**C. Keccak**
D. HMAC

**Câu 96:** Trong RSA, khóa công khai là:
**A. (n, e)**
B. (n, d)
C. (p, q)
D. (e, d)

**Câu 97:** Trong RSA, khóa riêng là:
A. (n, e)
**B. (n, d)**
C. (p, q)
D. (e, d)

**Câu 98:** RSA có thể được sử dụng cho:
A. Chỉ encryption
B. Chỉ digital signature
**C. Cả encryption và digital signature**
D. Chỉ key exchange

**Câu 99:** Diffie-Hellman không cung cấp:
A. Key exchange
B. Authentication
C. Encryption trực tiếp
**D. Cả B và C**

**Câu 100:** ElGamal encryption tạo ra ciphertext có kích thước:
A. Bằng plaintext
**B. Gấp đôi plaintext**
C. Bằng một nửa plaintext
D. Không xác định

---

## UNIT III: ELECTRONIC MAIL SECURITY

**Câu 101:** PGP là viết tắt của:
**A. Pretty Good Privacy**
B. Pretty Good Protection
C. Privacy Good Protocol
D. Protection Good Privacy

**Câu 102:** PGP cung cấp bao nhiêu loại dịch vụ?
A. 3
B. 4
**C. 5**
D. 6

**Câu 103:** PGP sử dụng hash function nào cho authentication?
A. MD5
**B. SHA-1**
C. SHA-256
D. SHA-512

**Câu 104:** Trong PGP authentication, hash code được mã hóa bằng:
A. Public key của người gửi
**B. Private key của người gửi**
C. Session key
D. Secret key

**Câu 105:** Trong PGP confidentiality, message được mã hóa bằng:
A. RSA
**B. CAST-128 hoặc IDEA hoặc 3DES**
C. AES
D. DES

**Câu 106:** Trong PGP confidentiality, session key được mã hóa bằng:
**A. Public key của người nhận**
B. Private key của người nhận
C. Secret key
D. Hash function

**Câu 107:** PGP compression sử dụng thuật toán nào?
**A. ZIP**
B. RAR
C. GZIP
D. BZIP2

**Câu 108:** PGP compression được thực hiện:
A. Trước khi ký
**B. Sau khi ký, trước khi mã hóa**
C. Sau khi mã hóa
D. Không bao giờ

**Câu 109:** PGP e-mail compatibility sử dụng:
**A. Base64 encoding**
B. Hex encoding
C. Binary encoding
D. ASCII encoding

**Câu 110:** Radix-64 conversion trong PGP là:
**A. Base64 encoding**
B. Hex encoding
C. Binary encoding
D. ASCII encoding

**Câu 111:** PGP session key có độ dài bao nhiêu bit?
A. 64 bit
**B. 128 bit**
C. 256 bit
D. 512 bit

**Câu 112:** PGP session key được tạo bằng:
**A. CAST-128**
B. RSA
C. DES
D. AES

**Câu 113:** PGP Key ID có độ dài bao nhiêu bit?
A. 32 bit
**B. 64 bit**
C. 128 bit
D. 256 bit

**Câu 114:** PGP Key ID là:
**A. 64 bit cuối của public key**
B. 64 bit đầu của public key
C. Toàn bộ public key
D. Hash của public key

**Câu 115:** PGP Private Key Ring chứa:
A. Chỉ private keys
B. Chỉ public keys
**C. Cả private và public keys của user**
D. Keys của người khác

**Câu 116:** PGP Public Key Ring chứa:
A. Private keys của user
**B. Public keys của các user khác**
C. Cả private và public keys
D. Session keys

**Câu 117:** Signature trust field trong PGP chỉ ra:
**A. Độ tin cậy của signer**
B. Độ tin cậy của owner
C. Độ tin cậy của key
D. Độ tin cậy của message

**Câu 118:** Owner trust field trong PGP chỉ ra:
A. Độ tin cậy của signer
**B. Độ tin cậy của public key owner**
C. Độ tin cậy của key
D. Độ tin cậy của message

**Câu 119:** S/MIME là viết tắt của:
**A. Secure/Multipurpose Internet Mail Extension**
B. Secure/Multipurpose Internet Mail Exchange
C. Secure/Multimedia Internet Mail Extension
D. Secure/Multipurpose Internet Mail Encryption

**Câu 120:** MIME là viết tắt của:
**A. Multipurpose Internet Mail Extension**
B. Multipurpose Internet Mail Exchange
C. Multimedia Internet Mail Extension
D. Multipurpose Internet Mail Encryption

**Câu 121:** MIME được thiết kế để giải quyết vấn đề gì?
A. SMTP chỉ hỗ trợ 7-bit ASCII
B. SMTP không thể truyền binary files
C. SMTP có giới hạn kích thước
**D. Tất cả các đáp án trên**

**Câu 122:** MIME-Version header có giá trị:
**A. 1.0**
B. 2.0
C. 3.0
D. Tùy chọn

**Câu 123:** S/MIME cung cấp bao nhiêu chức năng?
A. 2
B. 3
**C. 4**
D. 5

**Câu 124:** Enveloped data trong S/MIME là:
**A. Encrypted content**
B. Signed content
C. Clear-signed content
D. Nested content

**Câu 125:** Signed data trong S/MIME:
**A. Chỉ có thể xem bởi S/MIME capable recipients**
B. Có thể xem bởi mọi người
C. Không thể xem
D. Chỉ có thể xem bởi sender

**Câu 126:** Clear-signed data trong S/MIME:
A. Chỉ có thể xem bởi S/MIME capable recipients
**B. Có thể xem bởi mọi người nhưng không verify được signature**
C. Không thể xem
D. Chỉ có thể xem bởi sender

**Câu 127:** IPsec là viết tắt của:
A. IP Security
**B. Internet Protocol Security**
C. Internet Privacy Security
D. IP Secure Protocol

**Câu 128:** IPsec được thiết kế cho:
A. Chỉ IPv4
B. Chỉ IPv6
**C. Cả IPv4 và IPv6**
D. Không phải IP

**Câu 129:** IPsec cung cấp security ở tầng nào?
A. Application layer
B. Transport layer
**C. Network layer**
D. Data link layer

**Câu 130:** IPsec có bao nhiêu protocol chính?
A. 1
**B. 2**
C. 3
D. 4

**Câu 131:** ESP là viết tắt của:
**A. Encapsulating Security Payload**
B. Encrypted Security Protocol
C. Encapsulating Secure Protocol
D. Encrypted Secure Payload

**Câu 132:** AH là viết tắt của:
**A. Authentication Header**
B. Access Header
C. Authentication Hash
D. Access Hash

**Câu 133:** ESP cung cấp:
A. Chỉ confidentiality
B. Chỉ authentication
**C. Confidentiality và optional authentication**
D. Chỉ integrity

**Câu 134:** AH cung cấp:
A. Confidentiality
**B. Authentication và Integrity**
C. Chỉ authentication
D. Chỉ integrity

**Câu 135:** Security Association (SA) là:
**A. Một kết nối logic**
B. Một kết nối vật lý
C. Một protocol
D. Một algorithm

**Câu 136:** SA được xác định bởi:
A. SPI
B. Destination IP
C. Security Protocol
**D. Tất cả các đáp án trên**

**Câu 137:** SPI là viết tắt của:
**A. Security Parameter Index**
B. Security Protocol Index
C. Secure Parameter Identifier
D. Secure Protocol Identifier

**Câu 138:** Transport mode trong IPsec bảo vệ:
A. Toàn bộ IP packet
**B. Chỉ IP payload**
C. Chỉ IP header
D. Không bảo vệ gì

**Câu 139:** Tunnel mode trong IPsec bảo vệ:
**A. Toàn bộ IP packet**
B. Chỉ IP payload
C. Chỉ IP header
D. Không bảo vệ gì

**Câu 140:** Transport mode thường được sử dụng cho:
A. Gateway-to-gateway
**B. Host-to-host**
C. Host-to-gateway
D. Tất cả các đáp án trên

**Câu 141:** Tunnel mode thường được sử dụng cho:
**A. Gateway-to-gateway**
B. Host-to-host
C. Chỉ host-to-host
D. Chỉ gateway-to-gateway

**Câu 142:** IKE là viết tắt của:
**A. Internet Key Exchange**
B. Internet Key Encryption
C. IP Key Exchange
D. IP Key Encryption

**Câu 143:** IKE dựa trên:
A. ISAKMP
B. Oakley
C. SKEME
**D. Tất cả các đáp án trên**

**Câu 144:** ISAKMP là viết tắt của:
**A. Internet Security Association and Key Management Protocol**
B. Internet Security Association Key Management Protocol
C. IP Security Association and Key Management Protocol
D. IP Security Association Key Management Protocol

**Câu 145:** Oakley protocol sử dụng:
A. RSA
**B. Diffie-Hellman**
C. DES
D. AES

**Câu 146:** Transport adjacency trong IPsec là:
**A. Áp dụng nhiều security protocol cho cùng một packet**
B. Áp dụng một security protocol cho nhiều packet
C. Tunneling nhiều lần
D. Không áp dụng gì

**Câu 147:** Iterated tunneling trong IPsec là:
A. Áp dụng nhiều security protocol cho cùng một packet
**B. Áp dụng nhiều lớp tunneling**
C. Chỉ một lớp tunneling
D. Không tunneling

**Câu 148:** IPsec có thể cung cấp:
A. Access control
B. Connectionless integrity
C. Data origin authentication
**D. Tất cả các đáp án trên**

**Câu 149:** ESP header nằm ở đâu trong IP packet?
A. Trước IP header
**B. Sau IP header, trước transport header**
C. Sau transport header
D. Cuối packet

**Câu 150:** AH header nằm ở đâu trong IP packet?
A. Trước IP header
**B. Sau IP header, trước transport header**
C. Sau transport header
D. Cuối packet

---

## UNIT IV: WEB SECURITY

**Câu 151:** Web Security cần bảo vệ ở những tầng nào?
A. Chỉ application layer
B. Chỉ transport layer
**C. Nhiều tầng**
D. Chỉ network layer

**Câu 152:** SSL là viết tắt của:
**A. Secure Socket Layer**
B. Secure Service Layer
C. Secure System Layer
D. Secure Session Layer

**Câu 153:** TLS là viết tắt của:
**A. Transport Layer Security**
B. Transport Layer System
C. Transport Layer Service
D. Transport Layer Socket

**Câu 154:** SSL/TLS hoạt động ở tầng nào?
A. Application layer
B. Transport layer
C. Network layer
**D. Between transport and application**

**Câu 155:** SSL có bao nhiêu lớp protocol?
A. 1
**B. 2**
C. 3
D. 4

**Câu 156:** SSL Record Protocol cung cấp:
A. Confidentiality
B. Message integrity
**C. Cả A và B**
D. Authentication

**Câu 157:** SSL Handshake Protocol được sử dụng để:
A. Mã hóa dữ liệu
**B. Xác thực và thỏa thuận khóa**
C. Nén dữ liệu
D. Phân mảnh dữ liệu

**Câu 158:** SSL Change Cipher Spec Protocol có mục đích:
**A. Thay đổi cipher suite**
B. Mã hóa dữ liệu
C. Xác thực
D. Nén dữ liệu

**Câu 159:** SSL Alert Protocol được sử dụng để:
**A. Gửi cảnh báo**
B. Mã hóa dữ liệu
C. Xác thực
D. Nén dữ liệu

**Câu 160:** SSL session là:
A. Một kết nối
**B. Một association giữa client và server**
C. Một protocol
D. Một algorithm

**Câu 161:** SSL connection là:
A. Một session
**B. Một transport connection**
C. Một protocol
D. Một algorithm

**Câu 162:** Trong SSL, một session có thể có:
A. Chỉ một connection
**B. Nhiều connections**
C. Không có connection
D. Không giới hạn

**Câu 163:** SSL Record Protocol fragment có kích thước tối đa:
**A. 2^14 bytes**
B. 2^16 bytes
C. 2^18 bytes
D. 2^20 bytes

**Câu 164:** SSL Record Protocol sử dụng compression nào mặc định?
A. ZIP
B. GZIP
**C. Null (không nén)**
D. RAR

**Câu 165:** SSL Record Protocol sử dụng MAC nào?
A. HMAC-MD5
B. HMAC-SHA1
**C. Cả A và B**
D. Chỉ MD5

**Câu 166:** TLS khác SSL ở điểm nào?
**A. Sử dụng Pseudo-random function thay vì Message digest**
B. Sử dụng Message digest thay vì Pseudo-random function
C. Không có sự khác biệt
D. TLS nhanh hơn

**Câu 167:** SET là viết tắt của:
**A. Secure Electronic Transaction**
B. Secure Electronic Transfer
C. Secure Exchange Transaction
D. Secure Exchange Transfer

**Câu 168:** SET được phát triển bởi:
A. IBM
B. Microsoft
**C. MasterCard và Visa**
D. RSA

**Câu 169:** SET cung cấp bao nhiêu dịch vụ?
A. 2
**B. 3**
C. 4
D. 5

**Câu 170:** SET sử dụng encryption nào?
A. RSA
B. DES
**C. Cả A và B**
D. AES

**Câu 171:** SET sử dụng digital signature với:
**A. RSA và SHA-1**
B. DES và MD5
C. AES và SHA-1
D. RSA và MD5

**Câu 172:** SET participants bao gồm:
A. Cardholder, Merchant
B. Issuer, Acquirer
C. Payment Gateway, CA
**D. Tất cả các đáp án trên**

**Câu 173:** Dual Signature trong SET liên kết:
**A. Order Information và Payment Information**
B. Chỉ Order Information
C. Chỉ Payment Information
D. Không liên kết gì

**Câu 174:** Dual Signature được tạo bằng cách:
A. Hash OI và PI riêng biệt
**B. Hash concatenation của hash OI và hash PI**
C. Mã hóa OI và PI
D. Nén OI và PI

**Câu 175:** Trong SET, merchant không thể đọc:
A. Order Information
**B. Payment Information**
C. Cả A và B
D. Không có gì

**Câu 176:** SNMP là viết tắt của:
**A. Simple Network Management Protocol**
B. Secure Network Management Protocol
C. Simple Network Management Process
D. Secure Network Management Process

**Câu 177:** SNMPv1 sử dụng:
**A. Community facility**
B. User-based security
C. Encryption
D. Digital signature

**Câu 178:** SNMPv2 cải thiện:
A. Security
B. Performance
C. Functionality
**D. Tất cả các đáp án trên**

**Câu 179:** SNMPv3 cung cấp:
A. Authentication
B. Privacy
C. Timeliness
**D. Tất cả các đáp án trên**

**Câu 180:** SNMPv3 User Security Model (USM) cung cấp:
A. Authentication với HMAC-MD5 hoặc HMAC-SHA1
B. Privacy với DES CBC
C. Timeliness protection
**D. Tất cả các đáp án trên**

**Câu 181:** Authoritative SNMP Engine trong SNMPv3 là:
A. Transmitter
B. Receiver
**C. Tùy thuộc vào loại message**
D. Cả A và B

**Câu 182:** SNMPv3 msgSecurityParameters chứa:
A. Authoritative Engine ID
B. Authoritative Engine Boots
C. Authoritative Engine Time
**D. Tất cả các đáp án trên**

**Câu 183:** View-Based Access Control trong SNMPv3:
**A. Kiểm soát truy cập vào MIB objects**
B. Kiểm soát authentication
C. Kiểm soát encryption
D. Kiểm soát timeliness

**Câu 184:** Web Security Threats bao gồm:
A. Passive attacks
B. Active attacks
**C. Cả A và B**
D. Chỉ server attacks

**Câu 185:** Web Traffic Security có thể được cung cấp ở:
A. IP layer
B. Transport layer
C. Application layer
**D. Tất cả các đáp án trên**

**Câu 186:** SSL/TLS cung cấp security ở:
A. IP layer
B. Transport layer
C. Application layer
**D. Between transport and application**

**Câu 187:** SET đảm bảo:
A. Confidentiality của thông tin thanh toán
B. Integrity của dữ liệu
C. Authentication của cardholder và merchant
**D. Tất cả các đáp án trên**

**Câu 188:** SET sử dụng X.509v3 certificates cho:
A. Cardholders
B. Merchants
C. Payment Gateways
**D. Tất cả các đáp án trên**

**Câu 189:** Payment Gateway trong SET:
A. Xử lý payment messages
B. Interface với bankcard networks
**C. Cả A và B**
D. Chỉ xác thực

**Câu 190:** SNMP Architecture bao gồm:
A. Message Processing
B. User Security Model
C. View-Based Access Control
**D. Tất cả các đáp án trên**

**Câu 191:** SNMPv3 message format bao gồm:
A. msgVersion
B. msgSecurityParameters
C. msgData
**D. Tất cả các đáp án trên**

**Câu 192:** SNMPv3 discovery process:
**A. Lấy thông tin về SNMP engine khác**
B. Xác thực user
C. Mã hóa message
D. Kiểm soát truy cập

**Câu 193:** SNMPv3 key management:
A. Key generation
B. Key update
C. Key use
**D. Tất cả các đáp án trên**

**Câu 194:** Web Security Requirements bao gồm:
A. Confidentiality
B. Integrity
C. Authentication
**D. Tất cả các đáp án trên**

**Câu 195:** SSL/TLS Handshake Protocol thực hiện:
A. Client và server authentication
B. Negotiation encryption algorithms
C. Key exchange
**D. Tất cả các đáp án trên**

**Câu 196:** SSL/TLS Record Protocol format bao gồm:
A. Content Type
B. Version
C. Compressed Length
**D. Tất cả các đáp án trên**

**Câu 197:** SET Payment Processing bao gồm:
A. Payment Authorization
B. Payment Capture
**C. Cả A và B**
D. Chỉ authorization

**Câu 198:** SNMPv3 timeliness protection chống lại:
A. Message delay
B. Message replay
**C. Cả A và B**
D. Message modification

**Câu 199:** Web Security có thể sử dụng:
A. IPsec
B. SSL/TLS
C. Application-specific security
**D. Tất cả các đáp án trên**

**Câu 200:** SSL/TLS có thể được sử dụng với:
A. HTTP
B. FTP
C. SMTP
**D. Tất cả các đáp án trên**

---

## UNIT V: SYSTEM SECURITY

**Câu 201:** Có bao nhiêu loại intruder?
A. 2
**B. 3**
C. 4
D. 5

**Câu 202:** Masquerader là:
**A. Người không được phép sử dụng hệ thống**
B. Người được phép nhưng lạm dụng quyền
C. Người chiếm quyền điều khiển hệ thống
D. Người hợp pháp

**Câu 203:** Misfeasor là:
A. Người không được phép sử dụng hệ thống
**B. Người được phép nhưng lạm dụng quyền**
C. Người chiếm quyền điều khiển hệ thống
D. Người ngoài hệ thống

**Câu 204:** Clandestine user là:
A. Người không được phép sử dụng hệ thống
B. Người được phép nhưng lạm dụng quyền
**C. Người chiếm quyền điều khiển hệ thống**
D. Người hợp pháp

**Câu 205:** Intrusion Detection dựa trên giả định:
**A. Hành vi của intruder khác với legitimate user**
B. Hành vi của intruder giống với legitimate user
C. Không có sự khác biệt
D. Tất cả đều giống nhau

**Câu 206:** Có bao nhiêu phương pháp Intrusion Detection?
A. 1
**B. 2**
C. 3
D. 4

**Câu 207:** Statistical Anomaly Detection bao gồm:
A. Threshold detection
B. Profile-based detection
**C. Cả A và B**
D. Rule-based detection

**Câu 208:** Rule-based Detection bao gồm:
A. Anomaly detection
B. Penetration identification
**C. Cả A và B**
D. Threshold detection

**Câu 209:** Audit Record chứa:
A. Subject
B. Object
C. Resource-Usage
**D. Tất cả các đáp án trên**

**Câu 210:** Statistical metrics bao gồm:
A. Counter
B. Gauge
C. Interval timer
**D. Tất cả các đáp án trên**

**Câu 211:** Password Protection là:
**A. Front line of defense**
B. Second line of defense
C. Third line of defense
D. Không quan trọng

**Câu 212:** UNIX password system sử dụng:
A. DES
**B. Modified DES**
C. AES
D. RSA

**Câu 213:** Salt trong UNIX password có mục đích:
A. Ngăn duplicate passwords
B. Tăng độ dài password
C. Ngăn hardware implementation
**D. Tất cả các đáp án trên**

**Câu 214:** Password cracking có thể thực hiện bằng:
A. Dictionary attack
B. Brute force
C. Personal information
**D. Tất cả các đáp án trên**

**Câu 215:** Password Selection Strategies bao gồm:
A. User education
B. Computer-generated passwords
C. Reactive password checking
**D. Tất cả các đáp án trên**

**Câu 216:** Proactive password checking:
**A. Kiểm tra password khi user chọn**
B. Kiểm tra password sau khi chọn
C. Không kiểm tra
D. Tự động tạo password

**Câu 217:** Markov model trong password checking:
A. Mô hình ngôn ngữ
B. Mô hình xác suất
C. Mô hình thống kê
**D. Tất cả các đáp án trên**

**Câu 218:** Bloom filter trong password checking:
A. Sử dụng hash functions
B. Giảm không gian lưu trữ
**C. Cả A và B**
D. Không sử dụng hash

**Câu 219:** Virus là:
A. Một chương trình độc lập
**B. Một đoạn code cần host program**
C. Một file dữ liệu
D. Một hệ điều hành

**Câu 220:** Virus có bao nhiêu giai đoạn?
A. 2
B. 3
**C. 4**
D. 5

**Câu 221:** Các giai đoạn của virus:
**A. Dormant, Propagation, Triggering, Execution**
B. Dormant, Execution, Propagation, Triggering
C. Propagation, Dormant, Triggering, Execution
D. Execution, Propagation, Dormant, Triggering

**Câu 222:** Virus có thể được:
A. Prepended to program
B. Postpended to program
C. Embedded in program
**D. Tất cả các đáp án trên**

**Câu 223:** Compressed virus:
A. Nén file để che giấu
B. Nén chính nó
**C. Nén host program**
D. Không nén gì

**Câu 224:** Antivirus Approaches có bao nhiêu thế hệ?
A. 2
B. 3
**C. 4**
D. 5

**Câu 225:** First-generation antivirus:
**A. Simple scanners**
B. Heuristic scanners
C. Activity traps
D. Full-featured protection

**Câu 226:** Second-generation antivirus:
A. Simple scanners
**B. Heuristic scanners**
C. Activity traps
D. Full-featured protection

**Câu 227:** Third-generation antivirus:
A. Simple scanners
B. Heuristic scanners
**C. Activity traps**
D. Full-featured protection

**Câu 228:** Fourth-generation antivirus:
A. Simple scanners
B. Heuristic scanners
C. Activity traps
**D. Full-featured protection**

**Câu 229:** Generic Decryption (GD) technology:
A. Phát hiện polymorphic viruses
B. Sử dụng CPU emulator
**C. Cả A và B**
D. Chỉ scan signatures

**Câu 230:** Digital Immune System được phát triển bởi:
A. Microsoft
**B. IBM**
C. Symantec
D. McAfee

**Câu 231:** Behavior-Blocking Software:
A. Monitor program behavior in real-time
B. Block malicious actions
**C. Cả A và B**
D. Chỉ scan files

**Câu 232:** DDoS là viết tắt của:
**A. Distributed Denial of Service**
B. Distributed Denial of System
C. Denial of Distributed Service
D. Denial of Distributed System

**Câu 233:** DDoS attack sử dụng:
A. Một máy tính
**B. Nhiều máy tính (botnet)**
C. Chỉ server
D. Chỉ client

**Câu 234:** Botnet là:
A. Một máy tính
**B. Mạng các máy tính bị điều khiển**
C. Một server
D. Một client

**Câu 235:** IoT devices dễ bị tấn công vì:
A. Hard-coded credentials
B. Không thể update firmware
C. Thiếu security features
**D. Tất cả các đáp án trên**

**Câu 236:** Firewall là:
A. Một máy tính đơn
B. Một tập hợp hệ thống
**C. Cả A và B**
D. Một protocol

**Câu 237:** Firewall đặt ở đâu?
**A. Giữa premise network và Internet**
B. Trong premise network
C. Ngoài Internet
D. Không xác định

**Câu 238:** Firewall characteristics:
A. Tất cả traffic phải đi qua firewall
B. Chỉ authorized traffic được phép
C. Firewall phải immune to penetration
**D. Tất cả các đáp án trên**

**Câu 239:** Firewall sử dụng bao nhiêu kỹ thuật?
A. 2
B. 3
**C. 4**
D. 5

**Câu 240:** Firewall techniques:
A. Service control
B. Direction control
C. User control
**D. Tất cả các đáp án trên**

**Câu 241:** Có bao nhiêu loại firewall?
A. 2
**B. 3**
C. 4
D. 5

**Câu 242:** Packet filtering router:
A. Lọc packets dựa trên rules
B. Forward hoặc discard packets
**C. Cả A và B**
D. Chỉ forward

**Câu 243:** Application-level gateway:
A. Còn gọi là proxy server
B. Relay application-level traffic
**C. Cả A và B**
D. Chỉ filter packets

**Câu 244:** Circuit-level gateway:
A. Set up TCP connections
B. Relay TCP segments
**C. Cả A và B**
D. Chỉ filter packets

**Câu 245:** Firewall limitations:
A. Không bảo vệ attacks bypass firewall
B. Không bảo vệ internal threats
C. Không bảo vệ virus
**D. Tất cả các đáp án trên**

**Câu 246:** Trusted Systems:
A. Data Access Control
B. Concept of Trusted Systems
C. Trojan Horse Defense
**D. Tất cả các đáp án trên**

**Câu 247:** Intrusion Detection có thể:
A. Phát hiện intrusion nhanh
B. Serve as deterrent
C. Collect information về intrusion techniques
**D. Tất cả các đáp án trên**

**Câu 248:** False positive trong Intrusion Detection là:
**A. Authorized user bị nhận diện là intruder**
B. Intruder không bị phát hiện
C. Cả A và B
D. Không có gì

**Câu 249:** False negative trong Intrusion Detection là:
A. Authorized user bị nhận diện là intruder
**B. Intruder không bị phát hiện**
C. Cả A và B
D. Không có gì

**Câu 250:** Honeypot là:
A. Decoy system
B. Lure attackers away
C. Collect information về attackers
**D. Tất cả các đáp án trên**

---

## UNIT I: INTRODUCTION (Tiếp theo)

**Câu 251:** Trong DES, Initial Permutation (IP) và Final Permutation (FP) có mục đích gì?
A. Tăng độ bảo mật
**B. Không có ý nghĩa cryptography**
C. Tăng tốc độ
D. Giảm độ phức tạp

**Câu 252:** DES được công bố năm nào?
A. 1970
B. 1975
**C. 1977**
D. 1980

**Câu 253:** AES được chọn làm standard năm nào?
A. 1997
B. 2000
**C. 2001**
D. 2002

**Câu 254:** Trong AES, SubBytes operation sử dụng:
**A. S-box**
B. P-box
C. Permutation
D. XOR

**Câu 255:** Trong AES, MixColumns operation:
A. Hoán vị các cột
**B. Biến đổi toán học các cột**
C. XOR các cột
D. Nén các cột

**Câu 256:** AES với khóa 192-bit sử dụng bao nhiêu rounds?
A. 10 rounds
**B. 12 rounds**
C. 14 rounds
D. 16 rounds

**Câu 257:** Trong DES, mỗi S-box nhận input bao nhiêu bit?
A. 4 bit
**B. 6 bit**
C. 8 bit
D. 10 bit

**Câu 258:** Trong DES, mỗi S-box tạo ra output bao nhiêu bit?
A. 2 bit
**B. 4 bit**
C. 6 bit
D. 8 bit

**Câu 259:** Output Feedback (OFB) mode tương tự:
A. CBC mode
B. CFB mode
C. ECB mode
**D. Stream cipher**

**Câu 260:** Counter (CTR) mode sử dụng:
A. Counter value
B. IV
**C. Cả A và B**
D. Không cần gì

**Câu 261:** Trong CBC mode, IV phải:
A. Giống nhau cho mọi message
**B. Khác nhau cho mỗi message**
C. Luôn là 0
D. Không quan trọng

**Câu 262:** Stream cipher xử lý:
A. Một block tại một thời điểm
**B. Một bit hoặc byte tại một thời điểm**
C. Toàn bộ message
D. Chỉ header

**Câu 263:** Block cipher xử lý:
**A. Một block tại một thời điểm**
B. Một bit tại một thời điểm
C. Toàn bộ message
D. Chỉ header

**Câu 264:** Monoalphabetic cipher có bao nhiêu khóa có thể?
A. 25
**B. 26!**
C. 2^26
D. 26^2

**Câu 265:** Vigenere cipher sử dụng:
A. Một khóa dài bằng message
B. Khóa lặp lại
**C. Cả A và B**
D. Không cần khóa

**Câu 266:** Row Transposition Cipher sử dụng:
A. Substitution
**B. Permutation của columns**
C. XOR
D. Hash

**Câu 267:** Trong DES, key được chia thành:
**A. 2 phần 28-bit**
B. 2 phần 32-bit
C. 4 phần 14-bit
D. 8 phần 7-bit

**Câu 268:** Trong DES, mỗi round key có độ dài:
A. 32 bit
**B. 48 bit**
C. 56 bit
D. 64 bit

**Câu 269:** DES được thay thế bởi:
A. Triple DES
**B. AES**
C. RSA
D. Cả A và B

**Câu 270:** AES được thiết kế bởi:
A. NIST
**B. Joan Daemen và Vincent Rijmen**
C. RSA Laboratories
D. IBM

**Câu 271:** Trong AES, AddRoundKey operation:
**A. XOR với round key**
B. Cộng với round key
C. Nhân với round key
D. Chia cho round key

**Câu 272:** AES Key Expansion tạo ra:
A. 10 round keys cho 128-bit key
B. 12 round keys cho 192-bit key
C. 14 round keys cho 256-bit key
**D. Tất cả các đáp án trên**

**Câu 273:** Trong DES, Permutation Choice 1 (PC-1):
**A. Chọn 56 bit từ 64 bit key**
B. Chọn 48 bit từ 56 bit key
C. Chọn 32 bit từ 48 bit
D. Không có PC-1

**Câu 274:** Trong DES, Permutation Choice 2 (PC-2):
A. Chọn 56 bit từ 64 bit key
**B. Chọn 48 bit từ 56 bit key**
C. Chọn 32 bit từ 48 bit
D. Không có PC-2

**Câu 275:** DES được phát triển bởi:
**A. IBM**
B. NIST
C. RSA
D. Microsoft

**Câu 276:** Trong Feistel Cipher, left và right halves được swap:
**A. Sau mỗi round**
B. Sau tất cả rounds
C. Trước mỗi round
D. Không bao giờ swap

**Câu 277:** AES không sử dụng:
**A. Feistel structure**
B. Substitution-Permutation Network
C. S-boxes
D. Rounds

**Câu 278:** Trong AES, ShiftRows operation:
**A. Shift các hàng sang trái**
B. Shift các hàng sang phải
C. Shift các cột
D. Không shift gì

**Câu 279:** AES block size là:
A. 64 bit
**B. 128 bit**
C. 192 bit
D. 256 bit

**Câu 280:** DES effective key length là:
**A. 56 bit**
B. 64 bit
C. 48 bit
D. 32 bit

**Câu 281:** Trong DES, 8 bits của key được sử dụng cho:
**A. Parity checking**
B. Encryption
C. Decryption
D. Key expansion

**Câu 282:** Triple DES với 2 keys có key length:
A. 56 bit
**B. 112 bit**
C. 168 bit
D. 224 bit

**Câu 283:** Triple DES với 3 keys có key length:
A. 56 bit
B. 112 bit
**C. 168 bit**
D. 224 bit

**Câu 284:** AES được chọn từ:
**A. 5 finalists**
B. 10 candidates
C. 15 algorithms
D. 20 proposals

**Câu 285:** Trong AES, State matrix có kích thước:
**A. 4x4 bytes**
B. 4x4 bits
C. 8x8 bytes
D. 16x16 bits

**Câu 286:** ECB mode không an toàn vì:
A. Chậm
**B. Plaintext giống nhau tạo ciphertext giống nhau**
C. Cần IV
D. Phức tạp

**Câu 287:** CBC mode cần:
**A. IV unique cho mỗi message**
B. IV giống nhau
C. Không cần IV
D. IV tùy ý

**Câu 288:** CFB mode cho phép:
**A. Block cipher hoạt động như stream cipher**
B. Stream cipher hoạt động như block cipher
C. Chỉ block cipher
D. Chỉ stream cipher

**Câu 289:** OFB mode tương tự CFB nhưng:
**A. Feedback từ output của encryption**
B. Feedback từ ciphertext
C. Không có feedback
D. Feedback từ plaintext

**Câu 290:** CTR mode cho phép:
A. Parallel encryption
B. Random access
**C. Cả A và B**
D. Chỉ sequential

**Câu 291:** Link encryption mã hóa:
A. Chỉ data
**B. Toàn bộ packet**
C. Chỉ header
D. Không mã hóa gì

**Câu 292:** End-to-end encryption mã hóa:
**A. Chỉ data**
B. Toàn bộ packet
C. Chỉ header
D. Không mã hóa gì

**Câu 293:** Key distribution option 1 là:
**A. Physical delivery**
B. Encrypted delivery
C. Public key delivery
D. No delivery

**Câu 294:** Key distribution option 4 sử dụng:
A. Physical delivery
**B. Trusted third party**
C. Public announcement
D. Manual exchange

**Câu 295:** Trong symmetric encryption, số lượng keys cần cho n users:
A. n
**B. n(n-1)/2**
C. n^2
D. 2n

**Câu 296:** Trong public key encryption, số lượng keys cần cho n users:
A. n
**B. 2n**
C. n(n-1)/2
D. n^2

**Câu 297:** DES được công bố trong:
**A. FIPS PUB 46**
B. FIPS PUB 197
C. RFC 1321
D. RFC 2401

**Câu 298:** AES được công bố trong:
A. FIPS PUB 46
**B. FIPS PUB 197**
C. RFC 1321
D. RFC 2401

**Câu 299:** Trong DES, function f sử dụng:
**A. Expansion, S-boxes, Permutation**
B. Chỉ S-boxes
C. Chỉ Permutation
D. Chỉ Expansion

**Câu 300:** AES được chọn vì:
A. Nhanh
B. An toàn
C. Hiệu quả
**D. Tất cả các đáp án trên**

---

## UNIT II: PUBLIC KEY CRYPTOGRAPHY AND MESSAGE AUTHENTICATION (Tiếp theo)

**Câu 301:** Message Authentication không cung cấp:
A. Authentication
B. Integrity
**C. Confidentiality**
D. Non-repudiation

**Câu 302:** MAC không cung cấp:
A. Authentication
B. Integrity
**C. Non-repudiation**
D. Cả A và B

**Câu 303:** Hash function không cần:
**A. Secret key**
B. Input message
C. Output fixed length
D. One-way property

**Câu 304:** MAC cần:
**A. Secret key**
B. Public key
C. Private key
D. Không cần key

**Câu 305:** SHA-224 tạo ra hash có độ dài:
**A. 224 bit**
B. 256 bit
C. 384 bit
D. 512 bit

**Câu 306:** SHA-384 tạo ra hash có độ dài:
A. 224 bit
B. 256 bit
**C. 384 bit**
D. 512 bit

**Câu 307:** SHA-2 family bao gồm:
**A. SHA-224, SHA-256, SHA-384, SHA-512**
B. Chỉ SHA-256
C. Chỉ SHA-512
D. SHA-1, SHA-256

**Câu 308:** HMAC được thiết kế để:
A. Tăng tốc độ hash
**B. Tăng độ an toàn của hash với key**
C. Giảm độ dài hash
D. Tăng độ dài hash

**Câu 309:** Trong HMAC, K+ là:
**A. Key padded với zeros**
B. Key padded với ones
C. Key không đổi
D. Key được hash

**Câu 310:** HMAC algorithm có công thức:
**A. H[(K+ opad) || H[(K+ ipad) || M]]**
B. H[(K+ ipad) || H[(K+ opad) || M]]
C. H[K || M]
D. H[M || K]

**Câu 311:** RSA được công bố năm nào?
A. 1976
**B. 1977**
C. 1978
D. 1979

**Câu 312:** Trong RSA, p và q phải là:
**A. Số nguyên tố**
B. Số chẵn
C. Số lẻ
D. Bất kỳ số nào

**Câu 313:** Trong RSA, n phải:
**A. Lớn**
B. Nhỏ
C. Bằng p hoặc q
D. Không quan trọng

**Câu 314:** RSA encryption sử dụng:
**A. Public key (n, e)**
B. Private key (n, d)
C. Secret key
D. Hash function

**Câu 315:** RSA decryption sử dụng:
A. Public key (n, e)
**B. Private key (n, d)**
C. Secret key
D. Hash function

**Câu 316:** RSA digital signature sử dụng:
A. Public key để ký
**B. Private key để ký**
C. Secret key để ký
D. Hash để ký

**Câu 317:** RSA signature verification sử dụng:
**A. Public key**
B. Private key
C. Secret key
D. Hash

**Câu 318:** Diffie-Hellman được công bố năm nào?
A. 1975
**B. 1976**
C. 1977
D. 1978

**Câu 319:** Trong Diffie-Hellman, shared secret K được tính:
A. K = (YB)^XA mod q
B. K = (YA)^XB mod q
**C. Cả A và B đều đúng**
D. K = XA * XB mod q

**Câu 320:** Diffie-Hellman không cung cấp:
A. Key exchange
B. Authentication
C. Encryption
**D. Cả B và C**

**Câu 321:** ElGamal public key là:
**A. (p, g, y)**
B. (p, g, x)
C. (p, q, y)
D. (g, x, y)

**Câu 322:** ElGamal private key là:
A. p
B. g
**C. x**
D. y

**Câu 323:** Trong ElGamal, y được tính:
**A. y = g^x mod p**
B. y = g^p mod x
C. y = x^g mod p
D. y = p^x mod g

**Câu 324:** ElGamal encryption tạo ra:
A. C1 = g^k mod p
B. C2 = (P * y^k) mod p
**C. Cả A và B**
D. Chỉ C1

**Câu 325:** ElGamal decryption sử dụng:
A. C1 và private key x
B. C2 và private key x
**C. Cả C1 và C2 với private key x**
D. Chỉ public key

**Câu 326:** Digital Signature đảm bảo:
A. Message authentication
B. Data integrity
C. Non-repudiation
**D. Tất cả các đáp án trên**

**Câu 327:** Digital Signature thường ký hash vì:
A. Hash ngắn hơn
B. Hash nhanh hơn
C. Hash an toàn hơn
**D. Tất cả các đáp án trên**

**Câu 328:** Public key certificate chứa:
A. Public key
B. Identity
C. Signature của CA
**D. Tất cả các đáp án trên**

**Câu 329:** Certificate Authority (CA) là:
**A. Trusted third party**
B. User
C. Server
D. Router

**Câu 330:** Public key infrastructure (PKI) bao gồm:
A. CA
B. Certificates
C. Users
**D. Tất cả các đáp án trên**

**Câu 331:** Key revocation là:
**A. Hủy bỏ key**
B. Tạo key mới
C. Phân phối key
D. Mã hóa key

**Câu 332:** Certificate revocation list (CRL) chứa:
**A. Danh sách certificates đã bị hủy**
B. Danh sách keys mới
C. Danh sách users
D. Danh sách CAs

**Câu 333:** Session key được sử dụng cho:
**A. Một session**
B. Nhiều sessions
C. Tất cả sessions
D. Không session nào

**Câu 334:** Interchange key được sử dụng cho:
A. Một session
**B. Nhiều sessions**
C. Tất cả sessions
D. Key exchange

**Câu 335:** Forward search attack được ngăn chặn bởi:
**A. Session key**
B. Interchange key
C. Public key
D. Hash

**Câu 336:** MAC cung cấp:
A. Authentication
B. Integrity
**C. Cả A và B**
D. Confidentiality

**Câu 337:** MAC không cung cấp:
A. Authentication
B. Integrity
**C. Non-repudiation**
D. Cả A và B

**Câu 338:** Hash function cung cấp:
A. Authentication
**B. Integrity**
C. Confidentiality
D. Non-repudiation

**Câu 339:** Hash function không cung cấp:
A. Integrity
B. Authentication
C. Confidentiality
**D. Cả B và C**

**Câu 340:** HMAC-MD5 sử dụng:
**A. MD5 hash function**
B. SHA-1 hash function
C. SHA-256 hash function
D. Bất kỳ hash nào

**Câu 341:** HMAC-SHA1 sử dụng:
A. MD5 hash function
**B. SHA-1 hash function**
C. SHA-256 hash function
D. Bất kỳ hash nào

**Câu 342:** Trong RSA, để tính d từ e và φ(n), cần:
**A. Extended Euclidean Algorithm**
B. Euclidean Algorithm
C. Fast Exponentiation
D. Modular Inverse

**Câu 343:** RSA có thể bị tấn công nếu:
A. p và q quá nhỏ
B. e quá nhỏ
**C. Cả A và B**
D. n quá lớn

**Câu 344:** Diffie-Hellman key exchange dễ bị:
**A. Man-in-the-middle attack**
B. Brute force attack
C. Dictionary attack
D. Timing attack

**Câu 345:** ElGamal encryption tạo ciphertext:
**A. Gấp đôi plaintext**
B. Bằng plaintext
C. Một nửa plaintext
D. Không xác định

**Câu 346:** Digital Signature với RSA:
A. Sign với private key
B. Verify với public key
**C. Cả A và B**
D. Sign với public key

**Câu 347:** X.509 certificate version 3 có:
A. Extensions
B. Basic fields
C. Signature
**D. Tất cả các đáp án trên**

**Câu 348:** Certificate chain là:
**A. Chuỗi certificates từ root CA đến end entity**
B. Một certificate
C. Danh sách CAs
D. Không có gì

**Câu 349:** Root CA là:
**A. CA tự ký certificate**
B. CA được ký bởi CA khác
C. User
D. Server

**Câu 350:** Intermediate CA là:
**A. CA được ký bởi root CA**
B. CA tự ký
C. End entity
D. User

---

## UNIT III: ELECTRONIC MAIL SECURITY (Tiếp theo)

**Câu 351:** PGP message component chứa:
A. Actual data
B. Filename
C. Timestamp
**D. Tất cả các đáp án trên**

**Câu 352:** PGP signature component chứa:
A. Timestamp
B. Message digest
C. Key ID
**D. Tất cả các đáp án trên**

**Câu 353:** PGP session key component chứa:
A. Session key
B. Recipient public key ID
**C. Cả A và B**
D. Chỉ session key

**Câu 354:** PGP key ring structure chứa:
A. Timestamp
B. Key ID
C. Public/Private key
**D. Tất cả các đáp án trên**

**Câu 355:** PGP message generation bao gồm:
A. Signing message
B. Encrypting message
**C. Cả A và B**
D. Chỉ signing

**Câu 356:** PGP message reception bao gồm:
A. Decrypting message
B. Authenticating message
**C. Cả A và B**
D. Chỉ decrypting

**Câu 357:** PGP sử dụng passphrase để:
A. Encrypt private key
B. Decrypt private key
**C. Cả A và B**
D. Encrypt public key

**Câu 358:** PGP web of trust là:
**A. Hệ thống tin cậy phân tán**
B. Hệ thống CA tập trung
C. Không có hệ thống
D. Hệ thống đơn giản

**Câu 359:** S/MIME sử dụng:
**A. X.509 certificates**
B. PGP keys
C. Symmetric keys
D. Hash functions

**Câu 360:** S/MIME được chuẩn hóa bởi:
**A. IETF**
B. NIST
C. ISO
D. IEEE

**Câu 361:** MIME Content-Type header chỉ định:
A. Loại dữ liệu
B. Encoding
C. Transfer encoding
**D. Tất cả các đáp án trên**

**Câu 362:** MIME Content-Transfer-Encoding chỉ định:
A. Loại dữ liệu
**B. Cách encode để truyền**
C. Version
D. ID

**Câu 363:** S/MIME signed data format:
**A. Base64 encoded**
B. Binary
C. ASCII
D. Hex

**Câu 364:** S/MIME enveloped data format:
A. Base64 encoded
**B. Binary**
C. ASCII
D. Hex

**Câu 365:** IPsec Security Association (SA) là:
**A. One-way**
B. Two-way
C. Multi-way
D. No-way

**Câu 366:** IPsec SA được xác định bởi:
A. SPI
B. Destination IP address
C. Security Protocol (AH/ESP)
**D. Tất cả các đáp án trên**

**Câu 367:** IPsec có thể sử dụng:
A. AH only
B. ESP only
C. Both AH and ESP
**D. Tất cả các đáp án trên**

**Câu 368:** ESP trong transport mode:
**A. Bảo vệ IP payload**
B. Bảo vệ IP header
C. Bảo vệ toàn bộ packet
D. Không bảo vệ gì

**Câu 369:** ESP trong tunnel mode:
A. Bảo vệ IP payload
B. Bảo vệ IP header
**C. Bảo vệ toàn bộ packet**
D. Không bảo vệ gì

**Câu 370:** AH trong transport mode:
**A. Bảo vệ IP payload và một phần header**
B. Chỉ bảo vệ IP payload
C. Bảo vệ toàn bộ packet
D. Không bảo vệ gì

**Câu 371:** AH trong tunnel mode:
**A. Bảo vệ toàn bộ inner packet**
B. Chỉ bảo vệ payload
C. Chỉ bảo vệ header
D. Không bảo vệ gì

**Câu 372:** ESP header chứa:
A. SPI
B. Sequence Number
C. Payload Data
**D. Tất cả các đáp án trên**

**Câu 373:** AH header chứa:
A. Next Header
B. Payload Length
C. SPI
**D. Tất cả các đáp án trên**

**Câu 374:** IKE Phase 1:
**A. Establishes IKE SA**
B. Establishes IPsec SA
C. Establishes both
D. Establishes nothing

**Câu 375:** IKE Phase 2:
A. Establishes IKE SA
**B. Establishes IPsec SA**
C. Establishes both
D. Establishes nothing

**Câu 376:** ISAKMP cung cấp:
A. Framework cho key exchange
B. Framework cho SA establishment
**C. Cả A và B**
D. Chỉ encryption

**Câu 377:** Oakley protocol cung cấp:
A. Key exchange mechanism
B. Authentication
**C. Cả A và B**
D. Chỉ encryption

**Câu 378:** IPsec có thể được sử dụng cho:
A. VPN
B. Secure remote access
C. Extranet connectivity
**D. Tất cả các đáp án trên**

**Câu 379:** IPsec benefits bao gồm:
A. Transparent to applications
B. Transparent to users
C. Strong security
**D. Tất cả các đáp án trên**

**Câu 380:** IPsec có thể cung cấp:
A. Confidentiality
B. Authentication
C. Integrity
**D. Tất cả các đáp án trên**

**Câu 381:** PGP key revocation:
A. Hủy bỏ key
B. Tạo key mới
**C. Cả A và B**
D. Không có gì

**Câu 382:** PGP trust levels:
A. Complete trust
B. Marginal trust
C. No trust
**D. Tất cả các đáp án trên**

**Câu 383:** S/MIME certificate processing:
A. Verifies certificate chain
B. Checks revocation
**C. Cả A và B**
D. Chỉ verify

**Câu 384:** S/MIME enhanced security services:
A. Signed receipts
B. Security labels
C. Secure mailing lists
**D. Tất cả các đáp án trên**

**Câu 385:** IPsec AH protocol number:
A. 50
**B. 51**
C. 52
D. 53

**Câu 386:** IPsec ESP protocol number:
**A. 50**
B. 51
C. 52
D. 53

**Câu 387:** IPsec có thể sử dụng encryption algorithms:
A. DES
B. 3DES
C. AES
**D. Tất cả các đáp án trên**

**Câu 388:** IPsec có thể sử dụng authentication algorithms:
A. HMAC-MD5
B. HMAC-SHA1
**C. Cả A và B**
D. Chỉ MD5

**Câu 389:** IPsec key management có thể:
A. Manual
B. Automated (IKE)
**C. Cả A và B**
D. Chỉ manual

**Câu 390:** IPsec có thể được implement ở:
A. Host
B. Gateway
**C. Cả A và B**
D. Chỉ host

**Câu 391:** PGP compression được thực hiện:
**A. Sau signing, trước encryption**
B. Trước signing
C. Sau encryption
D. Không bao giờ

**Câu 392:** PGP segmentation:
A. Chia message thành segments
B. Sau tất cả processing
**C. Cả A và B**
D. Chỉ chia

**Câu 393:** S/MIME message format:
**A. MIME format với security**
B. PGP format
C. Plain text
D. Binary

**Câu 394:** IPsec transport adjacency:
**A. AH và ESP trên cùng packet**
B. Chỉ AH
C. Chỉ ESP
D. Không có gì

**Câu 395:** IPsec iterated tunneling:
**A. Nhiều lớp tunnel**
B. Một lớp tunnel
C. Không tunnel
D. Chỉ transport

**Câu 396:** PGP key escrow:
A. Lưu trữ key
B. Backup key
**C. Cả A và B**
D. Không có gì

**Câu 397:** S/MIME certificate handling:
**A. X.509v3**
B. PGP certificates
C. Self-signed
D. Không cần certificate

**Câu 398:** IPsec anti-replay protection sử dụng:
A. Sequence numbers
B. Timestamps
C. Nonces
**D. Tất cả các đáp án trên**

**Câu 399:** PGP trust model:
**A. Web of trust**
B. Hierarchical
C. Cả A và B
D. Không có model

**Câu 400:** IPsec có thể protect:
A. TCP
B. UDP
C. ICMP
**D. Tất cả các đáp án trên**

---

## UNIT IV: WEB SECURITY (Tiếp theo)

**Câu 401:** SSL/TLS cung cấp:
A. Confidentiality
B. Integrity
C. Authentication
**D. Tất cả các đáp án trên**

**Câu 402:** SSL/TLS handshake protocol thực hiện:
A. Negotiate cipher suite
B. Authenticate server
C. Optionally authenticate client
**D. Tất cả các đáp án trên**

**Câu 403:** SSL/TLS record protocol:
A. Fragments data
B. Compresses data
C. Adds MAC
**D. Tất cả các đáp án trên**

**Câu 404:** SSL/TLS có thể sử dụng cipher suites:
A. RSA với DES
B. RSA với 3DES
C. RSA với AES
**D. Tất cả các đáp án trên**

**Câu 405:** SSL/TLS version 3.0:
**A. SSLv3**
B. TLS 1.0
C. TLS 1.2
D. TLS 1.3

**Câu 406:** TLS 1.0 tương đương:
A. SSLv2
**B. SSLv3**
C. TLS 1.2
D. TLS 1.3

**Câu 407:** SSL/TLS master secret được tạo từ:
A. Pre-master secret
B. Client random
C. Server random
**D. Tất cả các đáp án trên**

**Câu 408:** SSL/TLS session resumption:
A. Sử dụng session ID
B. Tái sử dụng master secret
**C. Cả A và B**
D. Tạo session mới

**Câu 409:** SET dual signature liên kết:
**A. OI và PI**
B. Chỉ OI
C. Chỉ PI
D. Không liên kết gì

**Câu 410:** SET dual signature được tạo:
**A. Hash(H(OI) || H(PI))**
B. Hash(OI || PI)
C. Hash(OI) || Hash(PI)
D. Encrypt(OI || PI)

**Câu 411:** SET purchase request chứa:
A. PI
B. Dual signature
C. OIMD
**D. Tất cả các đáp án trên**

**Câu 412:** SET payment authorization:
A. Merchant requests authorization
B. Gateway authorizes
**C. Cả A và B**
D. Chỉ request

**Câu 413:** SET payment capture:
A. Merchant requests payment
B. Gateway processes payment
**C. Cả A và B**
D. Chỉ request

**Câu 414:** SNMPv1 community string:
**A. Password đơn giản**
B. Encrypted password
C. Digital signature
D. Certificate

**Câu 415:** SNMPv2 improvements:
A. Bulk operations
B. Better error handling
C. Security enhancements
**D. Tất cả các đáp án trên**

**Câu 416:** SNMPv3 security features:
A. Authentication
B. Privacy
C. Access control
**D. Tất cả các đáp án trên**

**Câu 417:** SNMPv3 USM authentication:
A. HMAC-MD5-96
B. HMAC-SHA1-96
**C. Cả A và B**
D. Chỉ MD5

**Câu 418:** SNMPv3 USM privacy:
**A. DES CBC**
B. AES
C. 3DES
D. Tất cả các đáp án trên

**Câu 419:** SNMPv3 authoritative engine:
A. Determines timeliness
B. Maintains clock
**C. Cả A và B**
D. Chỉ receiver

**Câu 420:** SNMPv3 view-based access control:
A. Controls MIB access
B. Defines views
**C. Cả A và B**
D. Chỉ authentication

**Câu 421:** SSL/TLS có thể sử dụng với:
A. HTTPS
B. FTPS
C. SMTPS
**D. Tất cả các đáp án trên**

**Câu 422:** SSL/TLS certificate:
A. X.509 format
B. Contains public key
C. Signed by CA
**D. Tất cả các đáp án trên**

**Câu 423:** SSL/TLS cipher suite specifies:
A. Key exchange algorithm
B. Encryption algorithm
C. MAC algorithm
**D. Tất cả các đáp án trên**

**Câu 424:** SET certificate hierarchy:
A. Root CA
B. Brand CA
C. Geo-Political CA
**D. Tất cả các đáp án trên**

**Câu 425:** SET cardholder certificate:
A. Links cardholder to account
B. Contains public key
C. Signed by CA
**D. Tất cả các đáp án trên**

**Câu 426:** SET merchant certificate:
A. Two certificates
B. One for signing
C. One for key exchange
**D. Tất cả các đáp án trên**

**Câu 427:** SNMPv3 message processing:
A. Handles version
B. Handles security
C. Handles PDU
**D. Tất cả các đáp án trên**

**Câu 428:** SNMPv3 engine ID:
A. Unique identifier
B. 12-32 octets
**C. Cả A và B**
D. Chỉ 12 octets

**Câu 429:** SNMPv3 engine boots:
A. Number of reboots
B. 0 to 2^31-1
**C. Cả A và B**
D. Chỉ counter

**Câu 430:** SNMPv3 engine time:
A. Seconds since last boot increment
B. 0 to 2^31-1
**C. Cả A và B**
D. Chỉ timestamp

**Câu 431:** SSL/TLS alert protocol levels:
A. Warning
B. Fatal
**C. Cả A và B**
D. Chỉ warning

**Câu 432:** SSL/TLS change cipher spec:
A. Single message
B. Value 1
**C. Cả A và B**
D. Multiple messages

**Câu 433:** SET payment gateway certificate:
A. Links gateway to acquirer
B. Contains public key
C. Signed by CA
**D. Tất cả các đáp án trên**

**Câu 434:** SNMPv3 discovery:
A. Gets engine information
B. Gets time information
**C. Cả A và B**
D. Chỉ engine ID

**Câu 435:** SNMPv3 key localization:
A. Derives keys for engines
B. Uses password
**C. Cả A và B**
D. Chỉ password

**Câu 436:** SSL/TLS renegotiation:
A. New handshake
B. New keys
**C. Cả A và B**
D. Chỉ handshake

**Câu 437:** SET order information:
A. Visible to merchant
B. Not visible to bank
**C. Cả A và B**
D. Visible to all

**Câu 438:** SET payment information:
A. Visible to bank
B. Not visible to merchant
**C. Cả A và B**
D. Visible to all

**Câu 439:** SNMPv3 context:
A. Collection of MIB objects
B. Access control scope
**C. Cả A và B**
D. Chỉ MIB

**Câu 440:** SSL/TLS compression:
A. Optional
B. Usually null
**C. Cả A và B**
D. Required

**Câu 441:** SET certificate request:
A. Cardholder requests certificate
B. Merchant requests certificate
**C. Cả A và B**
D. Chỉ cardholder

**Câu 442:** SNMPv3 user-based security:
A. User name
B. Authentication
C. Privacy
**D. Tất cả các đáp án trên**

**Câu 443:** SSL/TLS session ticket:
A. Alternative to session ID
B. Stateless resumption
**C. Cả A và B**
D. Chỉ session ID

**Câu 444:** SET certificate registration:
A. In-person
B. Secure authenticated
**C. Cả A và B**
D. Public

**Câu 445:** SNMPv3 notification:
A. Trap
B. Inform
**C. Cả A và B**
D. Chỉ trap

**Câu 446:** SSL/TLS perfect forward secrecy:
A. Ephemeral keys
B. Long-term keys
C. Cả A và B
**D. Chỉ ephemeral**

**Câu 447:** SET certificate chain:
A. Root to end entity
B. Multiple certificates
**C. Cả A và B**
D. Single certificate

**Câu 448:** SNMPv3 proxy:
A. Forwarder
B. Translator
**C. Cả A và B**
D. Chỉ forwarder

**Câu 449:** SSL/TLS client authentication:
A. Optional
B. Uses certificate
**C. Cả A và B**
D. Required

**Câu 450:** SET certificate revocation:
A. CRL
B. OCSP
**C. Cả A và B**
D. Chỉ CRL

---

## UNIT V: SYSTEM SECURITY (Tiếp theo)

**Câu 451:** Intrusion Detection System (IDS) có thể:
A. Host-based
B. Network-based
**C. Cả A và B**
D. Chỉ host-based

**Câu 452:** Intrusion Prevention System (IPS):
A. Detects intrusions
B. Prevents intrusions
**C. Cả A và B**
D. Chỉ detects

**Câu 453:** Statistical anomaly detection methods:
A. Mean and standard deviation
B. Multivariate
C. Markov process
**D. Tất cả các đáp án trên**

**Câu 454:** Rule-based anomaly detection:
A. Learns patterns
B. Detects deviations
**C. Cả A và B**
D. Chỉ learns

**Câu 455:** Rule-based penetration identification:
A. Expert system
B. Known attack patterns
**C. Cả A và B**
D. Chỉ expert system

**Câu 456:** Distributed Intrusion Detection:
A. Multiple sensors
B. Central analysis
**C. Cả A và B**
D. Chỉ sensors

**Câu 457:** Honeypot purposes:
A. Divert attackers
B. Collect information
C. Delay attackers
**D. Tất cả các đáp án trên**

**Câu 458:** Password policy should require:
A. Minimum length
B. Complexity
C. Regular changes
**D. Tất cả các đáp án trên**

**Câu 459:** Password hashing should use:
A. Fast algorithm
**B. Slow algorithm**
C. Reversible
D. Simple

**Câu 460:** Password salt purpose:
A. Prevent rainbow tables
B. Prevent duplicate detection
**C. Cả A và B**
D. Chỉ rainbow tables

**Câu 461:** Virus types:
A. Boot sector virus
B. File virus
C. Macro virus
**D. Tất cả các đáp án trên**

**Câu 462:** Worm là:
A. Self-replicating
B. Standalone program
**C. Cả A và B**
D. Needs host

**Câu 463:** Trojan horse là:
A. Appears legitimate
B. Contains malicious code
**C. Cả A và B**
D. Self-replicating

**Câu 464:** Polymorphic virus:
A. Changes appearance
B. Same functionality
**C. Cả A và B**
D. Chỉ changes

**Câu 465:** Metamorphic virus:
A. Changes code
B. Changes appearance
**C. Cả A và B**
D. Chỉ code

**Câu 466:** Antivirus signature-based detection:
A. Matches known patterns
B. Fast
**C. Cả A và B**
D. Chỉ patterns

**Câu 467:** Antivirus heuristic detection:
A. Analyzes behavior
B. Detects unknown viruses
**C. Cả A và B**
D. Chỉ behavior

**Câu 468:** Antivirus sandbox:
A. Isolated environment
B. Safe execution
**C. Cả A và B**
D. Chỉ isolated

**Câu 469:** DDoS attack types:
A. Volumetric
B. Protocol
C. Application layer
**D. Tất cả các đáp án trên**

**Câu 470:** Botnet command and control:
A. Centralized
B. Decentralized
**C. Cả A và B**
D. Chỉ centralized

**Câu 471:** Firewall stateful inspection:
A. Tracks connections
B. Analyzes packets
**C. Cả A và B**
D. Chỉ tracks

**Câu 472:** Firewall application proxy:
A. Understands protocols
B. Filters content
**C. Cả A và B**
D. Chỉ protocols

**Câu 473:** Firewall deep packet inspection:
A. Analyzes payload
B. Detects threats
**C. Cả A và B**
D. Chỉ payload

**Câu 474:** Next-generation firewall (NGFW):
A. Application awareness
B. Intrusion prevention
C. Advanced threat protection
**D. Tất cả các đáp án trên**

**Câu 475:** Firewall DMZ (Demilitarized Zone):
A. Semi-trusted network
B. Between internal and external
**C. Cả A và B**
D. Chỉ external

**Câu 476:** Trusted Computing Base (TCB):
A. Security-critical components
B. Must be trusted
**C. Cả A và B**
D. Chỉ components

**Câu 477:** Reference Monitor:
A. Mediates access
B. Always invoked
C. Tamper-proof
**D. Tất cả các đáp án trên**

**Câu 478:** Access Control Matrix:
A. Subjects
B. Objects
C. Permissions
**D. Tất cả các đáp án trên**

**Câu 479:** Mandatory Access Control (MAC):
A. System-enforced
B. User cannot override
**C. Cả A và B**
D. Chỉ system

**Câu 480:** Discretionary Access Control (DAC):
A. User-controlled
B. Owner decides
**C. Cả A và B**
D. Chỉ user

**Câu 481:** Role-Based Access Control (RBAC):
A. Based on roles
B. Users assigned roles
**C. Cả A và B**
D. Chỉ roles

**Câu 482:** Intrusion Detection false positive rate:
A. Should be low
B. High rate causes alert fatigue
**C. Cả A và B**
D. Chỉ low

**Câu 483:** Intrusion Detection false negative rate:
A. Should be low
B. Missed attacks
**C. Cả A và B**
D. Chỉ low

**Câu 484:** Base-rate fallacy trong IDS:
A. Low attack rate
B. High false positive rate
**C. Cả A và B**
D. Chỉ low rate

**Câu 485:** Honeynet là:
A. Network of honeypots
B. More complex
**C. Cả A và B**
D. Chỉ network

**Câu 486:** Password manager:
A. Stores passwords
B. Generates passwords
**C. Cả A và B**
D. Chỉ stores

**Câu 487:** Two-factor authentication (2FA):
A. Something you know
B. Something you have
**C. Cả A và B**
D. Chỉ know

**Câu 488:** Multi-factor authentication (MFA):
A. Two or more factors
B. More secure
**C. Cả A và B**
D. Chỉ two

**Câu 489:** Zero-day attack:
A. Unknown vulnerability
B. No patch available
**C. Cả A và B**
D. Chỉ unknown

**Câu 490:** Advanced Persistent Threat (APT):
A. Long-term attack
B. Sophisticated
C. Targeted
**D. Tất cả các đáp án trên**

**Câu 491:** Security Operations Center (SOC):
A. Monitors security
B. Responds to incidents
**C. Cả A và B**
D. Chỉ monitors

**Câu 492:** Incident response process:
A. Preparation
B. Detection
C. Containment
**D. Tất cả các đáp án trên**

**Câu 493:** Vulnerability assessment:
A. Identifies weaknesses
B. Evaluates risks
**C. Cả A và B**
D. Chỉ identifies

**Câu 494:** Penetration testing:
A. Simulates attacks
B. Tests defenses
**C. Cả A và B**
D. Chỉ simulates

**Câu 495:** Security awareness training:
A. Educates users
B. Reduces risks
**C. Cả A và B**
D. Chỉ educates

**Câu 496:** Data Loss Prevention (DLP):
A. Prevents data leakage
B. Monitors data
**C. Cả A và B**
D. Chỉ prevents

**Câu 497:** Endpoint Detection and Response (EDR):
A. Monitors endpoints
B. Detects threats
C. Responds to incidents
**D. Tất cả các đáp án trên**

**Câu 498:** Security orchestration:
A. Automates tasks
B. Coordinates tools
**C. Cả A và B**
D. Chỉ automates

**Câu 499:** Threat intelligence:
A. Information about threats
B. Helps defense
**C. Cả A và B**
D. Chỉ information

**Câu 500:** Security Information and Event Management (SIEM):
A. Collects logs
B. Analyzes events
C. Detects threats
**D. Tất cả các đáp án trên**
