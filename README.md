# leak-lookup

leak-lookup is a small python program for discovering if an email address has any leaked passwords associated with it. If the email address does has leaked passwords associated with it, leak-lookup then searches for the databases that contain the aformentioned password, and prompts the user to download it.

_The developers of this program do not take any responsibilty for the misuse of this program. It is the end user's responsibility to obey all applicable local, state and federal laws._

```
$ leak-lookup -h

---------- Usage ----------
leak-lookup [options] [search term]
---------------------------
Options:
    -h: Prints this help message
    -p: Searches haveibeenpwned.com
    -d: Searches for leaked database
---------------------------


$ leak-lookup -p test@example.com
test@example.com has 63 public leaks avalible

Download databases:
1) 000webhost: Compromised data: Email addresses, IP addresses, Names, Passwords
2) 2,844 Separate Data Breaches (unverified): Compromised data: Email addresses, Passwords
3) 7k7k (unverified): Compromised data: Email addresses, Passwords, Usernames
4) 8tracks: Compromised data: Email addresses, Passwords
5) Adobe: Compromised data: Email addresses, Password hints, Passwords, Usernames
6) Anti Public Combo List (unverified): Compromised data: Email addresses, Passwords
7) Bitcoin Talk: Compromised data: Dates of birth, Email addresses, Genders, IP addresses, Passwords, Security questions and answers, Usernames, Website activity
8) Bitly: Compromised data: Email addresses, Passwords, Usernames
9) Bolt: Compromised data: Email addresses, IP addresses, Passwords, Usernames
10) BTC-E: Compromised data: Account balances, Email addresses, IP addresses, Passwords, Usernames, Website activity
11) CashCrate: Compromised data: Email addresses, Names, Passwords, Physical addresses
12) Coupon Mom / Armor Games (unverified): Compromised data: Email addresses, Passwords
13) Dailymotion: Compromised data: Email addresses, Passwords, Usernames
14) diet.com: Compromised data: Dates of birth, Eating habits, Email addresses, IP addresses, Names, Passwords, Physical attributes, Usernames
15) Disqus: Compromised data: Email addresses, Passwords, Usernames
16) Dodonew.com (unverified): Compromised data: Email addresses, Usernames
17) Dropbox: Compromised data: Email addresses, Passwords
18) Elance: Compromised data: Email addresses, Employers, Geographic locations, Passwords, Phone numbers, Usernames
19) Evony: Compromised data: Email addresses, IP addresses, Passwords, Usernames
20) Exploit.In (unverified): Compromised data: Email addresses, Passwords
21) Fashion Nexus: Compromised data: Browser user agent details, Dates of birth, Email addresses, Genders, IP addresses, Names, Passwords, Phone numbers, Physical addresses, Purchases
22) Funimation: Compromised data: Dates of birth, Email addresses, Passwords, Usernames
23) Gaadi: Compromised data: Email addresses, Genders, Geographic locations, IP addresses, Names, Passwords, Phone numbers, Usernames
24) Gawker: Compromised data: Email addresses, Passwords, Usernames
25) GeekedIn: Compromised data: Email addresses, Geographic locations, Names, Professional skills, Usernames, Years of professional experience
26) GFAN (unverified): Compromised data: Email addresses, IP addresses, Passwords, Usernames
27) Heroes of Newerth: Compromised data: Email addresses, Passwords, Usernames
28) iMesh: Compromised data: Email addresses, IP addresses, Passwords, Usernames
29) Last.fm: Compromised data: Email addresses, Passwords, Usernames, Website activity
30) Lifeboat: Compromised data: Email addresses, Passwords, Usernames
31) LinkedIn: Compromised data: Email addresses, Passwords
32) Little Monsters: Compromised data: Dates of birth, Email addresses, Passwords, Usernames
33) mail.ru Dump (unverified): Compromised data: Email addresses, Passwords
34) MCBans: Compromised data: Email addresses, IP addresses, Passwords, Usernames, Website activity
35) MPGH: Compromised data: Email addresses, IP addresses, Passwords, Usernames
36) mSpy: Compromised data: Device usage tracking data
37) MySpace: Compromised data: Email addresses, Passwords, Usernames
38) NetEase (unverified): Compromised data: Email addresses, Passwords
39) Nihonomaru: Compromised data: Email addresses, IP addresses, Passwords, Usernames
40) Onliner Spambot: Compromised data: Email addresses, Passwords
41) OwnedCore: Compromised data: Email addresses, IP addresses, Passwords, Usernames
42) Patreon: Compromised data: Email addresses, Payment histories, Physical addresses, Private messages, Website activity
43) PayAsUGym: Compromised data: Browser user agent details, Email addresses, IP addresses, Names, Partial credit card data, Passwords, Phone numbers, Website activity
44) Pemiblanc (unverified): Compromised data: Email addresses, Passwords
45) QIP: Compromised data: Email addresses, Passwords, Usernames, Website activity
46) QuinStreet: Compromised data: Dates of birth, Email addresses, IP addresses, Passwords, Usernames, Website activity
47) R2Games: Compromised data: Email addresses, IP addresses, Passwords, Usernames
48) River City Media Spam List: Compromised data: Email addresses, IP addresses, Names, Physical addresses
49) Staminus: Compromised data: Credit cards, Email addresses, IP addresses, Passwords, Support tickets, Usernames
50) Stratfor: Compromised data: Credit cards, Email addresses, Names, Passwords, Phone numbers, Physical addresses, Usernames
51) Ticketfly: Compromised data: Email addresses, Names, Phone numbers, Physical addresses
52) Trik Spam Botnet: Compromised data: Email addresses
53) Trillian: Compromised data: Dates of birth, Email addresses, IP addresses, Names, Passwords, Usernames
54) tumblr: Compromised data: Email addresses, Passwords
55) vBulletin: Compromised data: Dates of birth, Email addresses, Homepage URLs, Instant messenger identities, IP addresses, Passwords, Security questions and answers, Spoken languages, Website activity
56) VK: Compromised data: Email addresses, Names, Passwords, Phone numbers
57) We Heart It: Compromised data: Email addresses, Passwords, Usernames
58) WHMCS: Compromised data: Email addresses, Email messages, Employers, IP addresses, Names, Partial credit card data, Passwords, Payment histories, Physical addresses, Website activity
59) Wishbone: Compromised data: Auth tokens, Dates of birth, Email addresses, Genders, Names, Phone numbers, Usernames
60) XSplit: Compromised data: Email addresses, Names, Passwords, Usernames
61) Yahoo: Compromised data: Email addresses, Passwords
62) Yatra: Compromised data: Dates of birth, Email addresses, Names, Passwords, Phone numbers, Physical addresses, PINs
63) Zomato: Compromised data: Email addresses, Passwords, Usernames
a) Download all
q) Quit
>> 1
Which file would you like to download?
1) 000webhost_13mil_plain_Oct_2015.7z (286.17 MB)
2) 000webhost.com.txt.gz (315.25 KB)
a) All
q) Quit
>>
[################################] 316/316 - 00:00:01
```
