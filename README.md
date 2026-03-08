<div align="center">

<img height="150" src="https://www.francocorbelli.it/nuovosito/immagini/testone.jpg" style="border-radius: 50%"/>

# dott. Franco Corbelli

> *I build fast, append-only backup tools that survive ransomware — and forensic imaging tools that hold up in court*

Developer from Italy &nbsp;·&nbsp; ⚙️ Systems programmer &nbsp;·&nbsp; 🗜 Compression enthusiast &nbsp;·&nbsp; 🔍 Digital forensics

<a href="http://www.francocorbelli.it">
<img src="https://img.shields.io/badge/Website-francocorbelli.it-blue?style=for-the-badge&logo=google-chrome&logoColor=white"/>
</a>

<img src="https://visitor-badge.laobi.icu/badge?page_id=fcorbelli.fcorbelli"/>

</div>

---

## 👋 About Me

I'm an Italian developer interested in **making data last forever** — safely, efficiently, and without trusting the cloud with your secrets.

My focus areas:

| 🗜 Compression | 🛡 Anti-ransomware | 💾 Backup & Recovery | 🔍 Digital Forensics |
|:-:|:-:|:-:|:-:|
| Efficient algorithms | Append-only writes | Incremental transfers | Forensic disk imaging |
| Long-term archival | Immutable history | Cross-platform tools | SHA-256 chain of custody |

I also happen to love 🐱 **Ragdoll** and **Norwegian Forest Cats**.

---

## 🚀 Featured Projects

### 🗜 [zpaqfranz](https://github.com/fcorbelli/zpaqfranz)

**ZPAQ-based compression and backup tool — ransomware-resistant by design**

Built on Dr. Matt Mahoney's ZPAQ technology, zpaqfranz adds:

- 🔒 **Append-only incremental backups** → previous backups are never overwritten
- ☁️ **Efficient cloud transfers** via `rsync --append` or internal append mechanism
- ♾️ **Immutable history** → all versions kept forever unless explicitly deleted
- 🧩 **Cross-platform** → Windows, Linux, macOS, FreeBSD, Solaris and many more...

<div align="center">

<img src="https://www.francocorbelli.it/zpaqfranz/zpaqfranz.jpg" height="200"/>

</div>

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/fcorbelli/zpaqfranz?style=social)](https://github.com/fcorbelli/zpaqfranz)
&nbsp;
<a href="https://sourceforge.net/projects/zpaqfranz/">
<img src="https://img.shields.io/badge/SourceForge-zpaqfranz-orange?style=flat&logo=sourceforge"/>
</a>

**⭐ Please leave a review on SourceForge — it really helps!**

</div>

---

### 🐱 [catpaq](https://github.com/fcorbelli/catpaq)

**Open-source cross-platform GUI for zpaqfranz**

Makes ZPAQ technology accessible to everyone — no command line needed.

- 🖥️ Portable GUI for Windows, macOS, Linux
- ⚡ Compile once, run almost identically everywhere
- 🎯 Designed for non-experts

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/fcorbelli/catpaq?style=social)](https://github.com/fcorbelli/catpaq)
&nbsp;
<a href="https://sourceforge.net/projects/catpaq/">
<img src="https://img.shields.io/badge/SourceForge-catpaq-orange?style=flat&logo=sourceforge"/>
</a>

**⭐ Please leave a review on SourceForge — it really helps!**

</div>

---

## 🛡 Ransomware-Resistant Backup Philosophy

Most backup tools overwrite old data. That's a ransomware's best friend.

My approach is different:

```
Traditional backup:  v1 → v2 → v3   (v1 and v2 are GONE)
zpaqfranz:           v1 + v2 + v3   (ALL versions kept FOREVER)
```

**Core principles:**
- ✅ **Never overwrite** — always append
- ✅ **Incremental** — only changes are transferred
- ✅ **Verifiable** — checksums on everything
- ✅ **Cloud-compatible** — works with any storage that supports append

---

## 🔍 Digital Forensics

zpaqfranz includes dedicated extensions for **computer forensics and legal evidence handling**, following Italian and international standards.

### Forensic disk imaging
- 📀 **Bit-perfect image acquisition** — full sector-by-sector copies of drives and media
- 🔐 **SHA-256 hashing** — the standard required by Italian law (*Legge 48/2008*) for evidence integrity
- 📋 **Automatic acquisition reports** — timestamped logs ready for court submission
- 🔗 **Chain of custody support** — every operation is logged and verifiable

### Why SHA-256 matters in Italian forensics
Italian law (*Legge 48/2008*, ratifying the Budapest Convention on Cybercrime) mandates that digital evidence must be acquired without alteration and its integrity verified with a cryptographic hash. SHA-256 is the accepted standard in Italian courts and law enforcement.

```
Acquire image  →  Compute SHA-256  →  Store in ZPAQ archive  →  Hash never changes
     ↓                  ↓                      ↓                       ↓
  Bit-perfect       Court-admissible       Append-only              Tamper-proof
```

This makes zpaqfranz a practical tool not just for IT professionals, but also for **CTU (Consulenti Tecnici d'Ufficio)**, **lawyers**, and **law enforcement** dealing with digital evidence in Italy.

---

## 🛠 Languages and Tools

<div align="center">

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="40" title="C++"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gcc/gcc-original.svg" height="40" title="GCC"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="40" title="Linux"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/debian/debian-original.svg" height="40" title="Debian"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apache/apache-original.svg" height="40" title="Apache"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" title="MySQL"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" height="40" title="PHP"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jquery/jquery-original.svg" height="40" title="jQuery"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vim/vim-original.svg" height="40" title="Vim"/>

</div>

---

## 🔥 GitHub Stats

<div align="center">

<img src="https://streak-stats.demolab.com?user=fcorbelli&theme=dark&border_radius=5"/>

<br><br>


<img src="https://github-readme-stats.vercel.app/api?username=fcorbelli&show_icons=true&theme=dracula"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=fcorbelli&layout=compact&theme=dracula"/>

</div>

---

## 📈 Activity Graph

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=fcorbelli&theme=dracula"/>

</div>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/fcorbelli/fcorbelli/output/snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/fcorbelli/fcorbelli/output/snake.svg"/>
  <img alt="contribution snake animation" src="https://raw.githubusercontent.com/fcorbelli/fcorbelli/output/snake.svg"/>
</picture>

</div>

---

## 🙏 Credits

The **ZPAQ compression technology** was created by **[Dr. Matt Mahoney](https://mattmahoney.net/)**.
All major credit for the underlying technology goes to him.

---

<div align="center">

⭐ If you find my work useful, consider **starring the repos** or **leaving a review on SourceForge**

</div>
