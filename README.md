# Cybersecurity Learning Roadmap

## While You Train:
- Write walkthroughs of everything you complete
- Build a GitHub repo of notes and solved labs (This is your portfolio)
- Explain vulnerabilities in plain English after each lab (If you can't explain it, you don't understand it)

---

## Categories
1. [Phase 1 - Basics](#phase-1---basics-1-2-weeks)
2. [Phase 2 - Core Foundations](#phase-2---core-foundations-4-6-weeks)
3. [Phase 3 - Deep Dive](#phase-3---deep-dive-6-8-weeks)
4. [Phase 4 - Expanding](#phase-4---expanding-10-12-weeks)
5. [Phase 5 - Specialization](#phase-5---specialization-10-12-weeks)

---

## Phase 1 - Basics (~1-2 Weeks)

**Goal:** Get comfy with vocab, concepts, and the Linux command line. Don't linger here.

### Daily Practice
* **Hacksplaining** - Teaches you the vocab and concepts of common web vulnerabilities in a digestible way so you understand them in the future.
  https://www.hacksplaining.com/lessons
  * Go through all lessons EXCEPT for:
    * AI: Bias and Unreliability
    * AI: Data Extraction Attacks
    * AI: Prompt Injection
    * XML Bombs
    * XML External Entities
  * (At the time of writing there are 37 lessons so ~3-6 a day is recommended)

* **Linux Journey** - Linux is used in almost every lab in every phase. Cover the specified sections. Don't bother making an account or doing the quizzes. Just read, take notes, and practice in terminal.
  https://linuxjourney.com
  * Under "Grasshopper" read everything except "Advanced Text-Fu" and "Getting Started"
  * Under "Journeyman" read lessons 1 and 6 in "The Filesystem" and lesson 8 in "Process Utilization"
  * Under "Networking Nomad" read lesson 4 in "Troubleshooting". Skip "Network Config" and read everything else
  * (At the time of writing this would be 14 sections so ~1-3 a day is recommended)

---

## Phase 2 - Core Foundations (~4-6 Weeks)

**Goal:** Get hands on experience with how systems and vulnerabilities actually work.

### Daily Practice - Work Through These Sequentially

* **OverTheWire (Bandit)** - Work through the Bandit wargame. It's beginner friendly and teaches Linux fundamentals through actual challenges.
  http://overthewire.org

* **CyLab (Easy)** - Work through the easy CTFs while getting comfortable with OverTheWire. Reinforces the fundamentals you're building.
  https://cylabacademy.org/

* **Hacker101** - Free informational videos give you structure. Watch through the specified playlists.
  * Playlists:
    * https://www.youtube.com/watch?v=LSqC9qgEMi0 (single video NOT playlist)
    * https://www.hacker101.com/playlists/pentesting_series
    * https://www.hacker101.com/playlists/web_hacking
    * https://www.hacker101.com/playlists/cryptography

---

## Phase 3 - Deep Dive (~6-8 Weeks)

**Goal:** Diving deeper into many of the topics covered in the past phases.

### Daily Practice - This Is Your Main Home

* **PortSwigger Web Security Academy** - The best free web security resource that exists. Work through labs systematically. Write a walkthrough for every lab you complete.
  https://portswigger.net/web-security

* **OverTheWire (Natas)** - Next Level of OverTheWire. Pairs well with PortSwigger.
  http://overthewire.org/wargames/natas/

* **CyLab (Medium)** - Your skills are sharp enough now to learn from the medium challenges.
  https://cylabacademy.org/

### Supplemental - Watch Alongside Labs
* **LiveOverflow - Web Hacking Playlist** - Watch alongside PortSwigger. Helps concepts click by seeing how an experienced person thinks through web vulnerabilities.
  https://www.youtube.com/playlist?list=PLhixgUqwRTjx2BmNF5-GddyqZcizwLLGP

---

## Phase 4 - Expanding (~10-12 Weeks)

**Goal:** Build out skills beyond web, full machine pentesting, cryptography, and tooling. Pick what interests you and go deep.

### Daily Practice - Pick Based on Your Interests

* **OverTheWire (Leviathan)** - Final fundamental wargame from OverTheWire. Good warmup before Exploitation Education.
  http://overthewire.org/wargames/leviathan/

* **Exploitation Education** - Low-level skills: binary exploitation, memory corruption, format strings. Important if you want to go deeper than web vulnerabilities.
  https://exploit.education/

* **The Cryptopals Crypto Challenges** - If you want to understand cryptography by breaking it rather than just reading about it. Excellent depth, genuinely hard, very rewarding.
  https://cryptopals.com/

* **CyLab (Hard)** - By now you have the background in binary exploitation and cryptography to tackle the hard challenges meaningfully rather than just guessing.
  https://cylabacademy.org/

### When You're Ready - Add These

* **Metasploit Unleashed** - The most complete free guide to Metasploit.
  https://www.offensive-security.com/metasploit-unleashed/

* **flAWS System** - Learn AWS security by exploiting intentional mistakes in a real AWS environment. Pairs directly with AWS training.
  http://flaws.cloud/

### Supplemental - Watch Alongside Labs
* **LiveOverflow - Binary Exploitation Playlist** - Watch alongside Exploitation Education. Covers binary exploitation from beginner to advanced.
  https://www.youtube.com/playlist?list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN

---

## Phase 5 - Specialization (~10-12 Weeks)

**Goal:** Build credentials. By this phase you should have a sense of whether you want to go offensive (pentesting, bug bounty), defensive (blue team, threat intel), or cloud security.

### Certifications & Credentials

* **CompTIA Security+ Certification** - More details will be added in the future...

* **AWS Cloud Certified** - Cloud security skills are in high demand. Training is free, exam is $100. Worth it when you're ready to specialize in cloud.
  https://www.youtube.com/watch?v=3hLmDS179YE *(Requires an AWS account)*

### Threat Intelligence / Blue Team Path

* **ATT&CK Cyber Threat Intelligence Training** - 4-hour training on how to use the MITRE ATT&CK framework for threat intelligence. Teaches you how attackers are categorized and tracked — a blue team mindset that employers care about.
  https://www.youtube.com/playlist?list=PLLGRmm150VfBd_bk6fGqTqxr8SBeDcprb
