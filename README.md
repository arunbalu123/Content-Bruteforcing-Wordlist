# Content Bruteforcing Wordlist
  
#### Wordlist for content(directory) bruteforce discovering with Burp or dirsearch

- burp-wordlist.txt - size: 40M 

`wget https://file.io/qa01jl`
- dirsearch-wordlist.txt - size: 102M

`wget https://file.io/s7tJn8`

Usage example:

`python3 dirsearch.py -u https://example.com -e "php" -w ../Content-Bruteforcing-Wordlist/dirsearch-wordlist.txt`
