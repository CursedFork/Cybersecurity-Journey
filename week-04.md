# Week 04 – Job, Certification Update, Pi-Hole

**Dates:** Started this Journal on January 20th, 2026

**Study Focus:**
- CompTIA CySA+ - Chapter 3-4
- Home Lab Development - Pi-Hole Setup

**Objectives:**
- Configure Pi-Hole
- Complete objectives for Chapters 3-4 of the CySA+ textbook I have
---
**1/20/2026:**
- It's been a while since I have last uploaded, I have been busy with work and life in general and have been working without documenting it
- My job has been great, so far I have been learning about documents for security investigations
- My company has offered to pay for me to get CySA+ and PECB-ISO27001 Lead Auditor certifications --> I have been studying for these whenever I can, hoping to get CySA+ by the end of February
- I ordered a Raspberry Pi in order to make a Pi-Hole, here's how it went:
1. I downloaded a 64-bit installation of Raspberry Pi Lite OS, and had trouble with the default disk writer that is on the official Pi website (several failed writes)
2. I used Balena Etcher to put a 32-bit installation on the Pi, because ChatGPT said it would be fine for my project, and *surprise!* it was not
3. I used Balena Etcher to put the 64-bit installation on the Pi, then could not SSH into it even after adding a file named "SSH" with no extension per the documentation because of a failed login attempt with the default credentials
4. Turns out, the default credentials do not exist on the default installation of Raspberry Pi Lite anymore because it was considered a security issue. So I plugged the Pi into a separate monitor and set it up before plugging it into my router again
5. After getting it connected to the router it was a pretty standard installation of the Pi-Hole resources, and from there everything worked great. I only wish I knew it no longer works for YouTube or Hulu ads...
