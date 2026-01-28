# MD5 Hash Cracking Practice (John the Ripper)

This repository is created for **ethical hacking learning and practice** purposes.  
Here I practiced cracking **raw MD5 hashes** using **Hashcat** with the **RockYou wordlist** .

---

## Clone the Repository

```bash
git clone https://github.com/samrat-xyz/md5hash-cracking-by-hashcat.git
cd md5hash-cracking-by-hashcat
hashcat -m 0 -a 0 md5hash.txt /usr/share/wordlists/rockyou.txt
hashcat -m 0 md5hash.txt --show 
