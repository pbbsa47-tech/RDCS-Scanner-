<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&duration=3000&pause=500&color=00FF00&center=true&vCenter=true&width=600&lines=SCANNER+by+RDCS;Ethical+Zone;Red+Dragon+Cyber+Security" alt="Typing SVG" />

<a href="https://github.com/pbbsa47-tech"><img src="https://img.shields.io/badge/GitHub-pbbsa47--tech-181717?style=for-the-badge&logo=github" /></a>
<a href="http://pbbs.unaux.com/"><img src="https://img.shields.io/badge/Website-pbbs.unaux.com-00BFFF?style=for-the-badge&logo=google-chrome" /></a>
<img src="https://img.shields.io/badge/Platform-Termux%20|%20Kali%20|%20Ubuntu%20|%20Parrot%20|%20Arch%20|%20Windows-00FF7F?style=for-the-badge" />

</div>

---

<h1 align="center">🔰 𝙎𝘾𝘼𝙉𝙉𝙀𝙍 – 𝙩𝙝𝙚 𝙐𝙡𝙩𝙞𝙢𝙖𝙩𝙚 𝙀𝙩𝙝𝙞𝙘𝙖𝙡 𝙃𝙖𝙘𝙠𝙞𝙣𝙜 𝙏𝙤𝙤𝙡</h1>
<h3 align="center">Developed by <a href="https://github.com/pbbsa47-tech">𝓜𝓐𝓣𝓡𝓘𝓧𝓢 𝓔𝓧𝓟𝓛𝓞𝓘𝓣𝓔𝓡 ☢️</a> | Team <span style="color:red">RDCS – Red Dragon Cyber Security</span></h3>
<h4 align="center">⚡ Ethical Zone Box – For Authorized Testing Only ⚡</h4>

---

## 🇧🇩 বাংলায় পড়ুন

### 🌟 SCANNER কী?
**SCANNER** একটি অল-ইন-ওয়ান নৈতিক হ্যাকিং টুল যা পোর্ট স্ক্যানিং, সার্ভিস ডিটেকশন, জিওলোকেশন, WAF সনাক্তকরণ, SQL ইনজেকশন চেক, CVE লুকআপ, স্টিল্থ মোড, প্রক্সি চেইনিং এবং রিপোর্ট জেনারেশন এক প্ল্যাটফর্মেই প্রদান করে। এটি সম্পূর্ণ কমান্ড-লাইন ভিত্তিক এবং টার্মাক্স, কালি লিনাক্স, উবুন্টু, প্যারট ওএস, ব্ল্যাক আর্চ, আর্চ লিনাক্স এবং উইন্ডোজে সমানভাবে কাজ করে।

### ⚠️ গুরুত্বপূর্ণ সতর্কতা
এই টুলটি **শুধুমাত্র অনুমোদিত নৈতিক পরীক্ষার জন্য**।  
অবৈধ ব্যবহারকারীদের বিরুদ্ধে কপিরাইট আইন অনুযায়ী ব্যবস্থা নেওয়া হবে।  
©️ সর্বস্বত্ব সংরক্ষিত – 𝓜𝓐𝓣𝓡𝓘𝓧𝓢 𝓔𝓧𝓟𝓛𝓞𝓘𝓣𝓔𝓡 & RDCS

### 🔧 ইন্সটলেশন (সব ওএস)
**টার্মাক্স (অ্যান্ড্রয়েড):**
```bash
pkg update && pkg upgrade
pkg install python nmap git
pip install rich requests
git clone https://github.com/pbbsa47-tech/Scanner.git
cd Scanner
python scanner.py
কালি / প্যারট / উবুন্টু / ডেবিয়ান:

bash
sudo apt update && sudo apt install python3 python3-pip nmap -y
pip3 install rich requests
git clone https://github.com/pbbsa47-tech/Scanner.git
cd Scanner
python3 scanner.py
আর্চ / ব্ল্যাক আর্চ:

bash
sudo pacman -Syu python python-pip nmap
pip install rich requests
git clone https://github.com/pbbsa47-tech/Scanner.git
cd Scanner
python scanner.py
উইন্ডোজ:

Python 3.10+ ইন্সটল করুন python.org

Nmap nmap.org থেকে ডাউনলোড করে ইন্সটল করুন

তারপর:

cmd
pip install rich requests
git clone https://github.com/pbbsa47-tech/Scanner.git
cd Scanner
python scanner.py
🖥️ ব্যবহার পদ্ধতি
স্ক্রিপ্ট রান করুন: python scanner.py

মেনু থেকে নির্বাচন করুন:

1 : নতুন স্ক্যান শুরু (IP/URL দিন)

2 : প্রক্সি চেইন কনফিগার

3 : স্টিল্থ মোড টগল

4 : HTML/JSON রিপোর্ট তৈরি

5 : বের হওয়া

স্ক্যান শেষে বিস্তারিত ফলাফল এবং দুর্বলতা রিপোর্ট দেখুন।

📚 ফিচারসমূহ
🎯 IP/URL থেকে জিওলোকেশন, WAF সনাক্তকরণ

🔍 Nmap বা বিল্ট-ইন সকেট স্ক্যানার (টপ 1000+ পোর্ট)

🛡️ ফায়ারওয়াল ও OS ডিটেকশন

💉 SQL ইনজেকশন চেক (GET প্যারামিটার)

📚 CVE ডাটাবেজ অনুসন্ধান (NVD API)

🕵️ স্টিল্থ মোড (র‍্যান্ডম ইউজার-এজেন্ট, ডিলে)

🔗 প্রক্সি চেইনিং (HTTP/SOCKS5)

📄 HTML/JSON রিপোর্ট

🇬🇧 English
🌟 What is SCANNER?
SCANNER is a powerful, all-in-one ethical hacking tool that bundles:

Port scanning & service detection

Geolocation & WAF fingerprinting

SQL injection testing

CVE database lookup

Stealth mode with User‑Agent rotation

Proxy chaining

HTML/JSON reporting

All from a smooth, Kali‑style terminal interface. It runs natively on Windows, Termux, Kali Linux, Ubuntu, Parrot OS, Black Arch, Arch Linux.

⚠️ Legal & Copyright
This tool is meant for AUTHORIZED security testing only.
Unauthorized use is illegal. The developers assume no liability for misuse.

©️ All rights reserved.
This software is protected by copyright law. Redistribution, modification, or copying without explicit permission from 𝓜𝓐𝓣𝓡𝓘𝓧𝓢 𝓔𝓧𝓟𝓛𝓞𝓘𝓣𝓔𝓡 (RDCS) is strictly prohibited.
Violators will be pursued under applicable international copyright legislation.

💾 Installation (All OS)
Termux (Android):

bash
pkg update && pkg upgrade
pkg install python nmap git
pip install rich requests
git clone https://github.com/pbbsa47-tech/Scanner.git
cd Scanner
python scanner.py
Kali / Parrot / Ubuntu / Debian:

bash
sudo apt update && sudo apt install python3 python3-pip nmap -y
pip3 install rich requests
git clone https://github.com/pbbsa47-tech/Scanner.git
cd Scanner
python3 scanner.py
Arch / Black Arch:

bash
sudo pacman -Syu python python-pip nmap
pip install rich requests
git clone https://github.com/pbbsa47-tech/Scanner.git
cd Scanner
python scanner.py
Windows:

Install Python 3.10+ from python.org

Download and install Nmap from nmap.org

Then:

cmd
pip install rich requests
git clone https://github.com/pbbsa47-tech/Scanner.git
cd Scanner
python scanner.py
🖥️ How to Use
Run the script: python scanner.py

From the interactive menu choose:

1 – Start a new scan (enter IP or URL)

2 – Configure proxy chaining

3 – Toggle stealth mode

4 – Generate HTML / JSON report

5 – Exit

After scanning, detailed results, vulnerabilities, and CVEs are displayed.

📋 Features
🎯 Geolocation, WAF detection

🔍 Nmap scan (top 1000 ports, service + OS detection) with fallback socket scanner

🛡️ Firewall filtering analysis

💉 SQLi error‑based detection

📚 CVE lookup via NVD

🕵️ Stealth mode (random delays, User‑Agent rotation)

🔗 Proxy chaining with live testing

📄 Export to HTML & JSON reports

🛡️ Ethical Notice
This tool is a Box of Ethical Zone.
Use it only on systems you own or have explicit permission to test.
“Fear Allah and stay within the boundaries of halal.”

👤 Credits
Developer: 𝓜𝓐𝓣𝓡𝓘𝓧𝓢 𝓔𝓧𝓟𝓛𝓞𝓘𝓣𝓔𝓡 ☢️

Team: RDCS – Red Dragon Cyber Security

GitHub: pbbsa47-tech

Website: http://pbbs.unaux.com/

©️ Copyright
text
© 2026 𝓜𝓐𝓣𝓡𝓘𝓧𝓢 𝓔𝓧𝓟𝓛𝓞𝓘𝓣𝓔𝓡 ☢️ | RDCS – Red Dragon Cyber Security
All rights reserved. Unauthorized copying or redistribution of this file,
via any medium, is strictly prohibited. Proprietary and confidential.
text.
