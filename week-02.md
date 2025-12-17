# Week 02 – A+ Core 1 Exam Approaching and Home Lab Start

**Dates:** Started this Journal on December 11th, 2025

**Study Focus:**
- CompTIA A+ Core 1 - Virtualization, Mobile Devices, and Networking
- Home Lab Start
- Linux Journey Website Start

**Objectives:**
- Studying daily, aim to finish CompTIA A+ core 1 by the end of the week.
- Repair rediscovered old PC from 2005 that I found in my basement.
- Use repaired PC to begin home lab setup. It is unlikely that it would be super advanced, but it is a start, and a lesson in diagnostic. 
---

**12/11/2025:**
- I found a PC in my parents' basement, and figured it would be a good use of my time to try to get it working.
- I opened it up and dusted it with compressed air, and having not been dusted in at least a decade, there was quite a bit caked up.
- After plugging it into a monitor using VGA, it failed to display anything. I also plugged in a keyboard and mouse, none of which indicated being powered, which suggests a POST issue.
- I also noticed an odd buzzing sound, and originally wrote it off as "maybe it's just a sound old PCs make". (I would later discover this was important)
- Steps Taken to Diagnose:
1. The first thing I did was unplug everything and open the PC again.
2. I plugged in only the power cable and, being careful to keep my hands clear, powered the PC on, which revealed that the internal fans were working fine.
3. I looked into the buzzing sound noted earlier, and discovered that it indicates that the GPU was likely not functional.
4. I took out and reslotted the GPU twice, once to test, and the second time after cleaning the pins with diluted isopropol alcohol and a microfiber cloth. Neither attempt worked.
5. I ordered a component online after ensuring that it would be compatible with the existing hardware. If this does not work, I will investigate further. 
---
**12/12/2025:**
- I scheduled my CompTIA A+ Core 1 1201 exam for next Saturday, December 20th.
- My replacement GPU for the old PC is coming tomorrow.
- I did some more practice questions today and I am feeling reasonably confident about my upcoming exam.
- I signed up for a newsletter called "Tldr" which is supposed to give me daily news on technology, including cybersecurity, hardware, IT, and AI, based on how I set my preferences. 
---
**12/13/2025:**
- The replacement GPU for my old PC project arrived today. However, in spite of being allegedly compatible it did not display anything on the screen. 
- Process:
1. I unplugged everything from the tower, and opened the PC. 
2. I removed the old GPU from the PCIe slot, and after taking the new GPU freshly out of its packaging, I slotted it in. 
3. I plugged in the power cable and turned it on. The PC still beeped, so I looked into further options. 
4. One suggestion I found was to clear the CMOS, so I followed the instructions I found and removed the battery from the motherboard and let it sit for 10 minutes, then put it back in. 
5. After plugging cables back in and turning the PC on again, there was no beeping and the keyboard received power sincd its lights came on. However, it did not display anything. 
6. I looked further into this issue and learned that even though it was technically compatible, Dell towers like the one I am working on do not support Display Port cables, which is the only connector type on the new GPU. 
7. I returned the new GPU and ordered one after ensuring it has the right connections. 
- After this situation, I got back to studying for my exam and took some practice quizzes and another practice exam.
---
**12/14/2025:**
- I flipped through my flashcards and studied more of my practice questions.
- I took a couple practice quizzes and another exam.
- My brother requested a basic PC, intended to be useful in work, for Christmas, so my parents approached me to put together a parts list.
- Since I already have a CPU and GPU sitting around, not to mention a drive with Windows 11 to boot with, I compiled a list of parts that were compatible, and ordered them.
- I realized that this build gave me a few opportunities to work on small projects that could be discussed for my resume, for instance:
1. A pre-loaded desktop complete with an operating system, and some useful applications for PC maintenance. Could frame this on my resume as "Bootable USB Maintenance and Recovery Kit."
2. It would count towards my freelance builds, and I could say it is a "Custom PC Build and Hardware Compatibility Integration."
3. "Hardware Lifecycle Extension" would also be a potential project listing, since I am extending the lifespan of two parts that still function, that I retired from my main PC.
- Overall, today was well spent on planning a few other projects that I can do in the next few weeks after I finish the Old PC restoration project.
- I am also happy that I have continued to perform gradually better in my practice exams and quizzes.
---
**12/15/2025:**
- I continued to progress in my study aid app, and took a couple more practice quizzes and exams.
- The second graphics card I ordered for my old PC project arrived today, so I slotted it in:
1. First, the PC was unplugged from any power connection.
2. The old GPU was removed.
3. Following similar procedure to the last time, I cleared the CMOS by removing one of the RAM sticks and the motherboard battery.
4. The computer successfully made it through POST, and displayed on the monitor through DVI.
5. It works now; however, since it is running Windows XP, I thought it best not to attempt to connect it to the wifi on account of its potential vulnerabilities.
6. Strangely enough, after reinserting the old RAM stick, the same issue occurred, and it failed to POST. I wonder whether both the RAM and the old GPU were both defective.
7. System is now operational, just with only one stick of RAM for now.
- I feel very excited having successfully revived the old PC, even if it is not very fast or modern. It's still a win.
- This endeavor has been an interesting insight into the IT field, and I am eager to continue more projects.
- I will be adding my full documentation of this project to my "projects" folder, which I will be adding to this repository right after this commit.
---
**12/16/2025:**
- I landed the job at Geek Squad as an Advanced Repair Technitian!
- I officially have an IT job, which is nice for a start in my experience as a computer science professional.
- I also decided to boot Debian 12 on my old PC project, and my goal is to try and get a Pi-Hole ad blocker running on that soon.
- This was chosen because it is the latest version of debian that will run on a 32-bit architecture, which this old PC is.
- With my core 1 exam on the horizon, I will be continuing to study vigorously as I await final onboarding steps for my careers.
