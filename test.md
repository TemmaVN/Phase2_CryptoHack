#Crypto
https://cryptohack.org/
 - Phase 2 của CryptoHack sẽ giới thiệu một số thuật toán cần thiết của Crypto yêu cầu code giải thuật toán (nên dùng python cho dễ)
 - Đề: https://cryptohack.org/courses/modular/gcd/
 - Giải: Bài yêu cầu tính USCLN của a và b (gọi phép là gcd)
 - Thuật toán:
 - Giả sử q = gcd(a,b) (a>b)
 - ==> a ≡ b ≡ a%b ≡ 0 (mod q)
 - ==> gcd(a,b) = gcd(b,a%b)
 - Dùng đệ quy hoặc vòng lặp để giải
 ```
 def gcd(a,b):
     if b == 0: return a
     else: return gcd(b,a%b)

#a=66528
#b=52920
#print(gcd(a,b))

```
