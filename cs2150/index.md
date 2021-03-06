Program and Data Representation: CS 2150 Specific Content
=========================================================

[Go up to the main README file][111] ([md][112])

Much of the rest of this git repo is meant to be generic to anybody who has a class such as this one.  But this page contains details specific to the CS 2150 version of the course at the University of Virginia.

------------------------------------------------------------

Links
-----

There are a number of links and other parts of this course that are **NOT** included in this repository.  They are:

- The set of online tools, which can be accessed through Collab or [here][160].
    - These tools are: [support requests][161], [lab submission][162], [regrades][163], [gradebook][164], [lab extensions][165], and the [office hours queue][166]
- The announcements, which are posted to the CS 2150 twitter feed: [\@UVaCS2150][151]
- The [CS 2150 Google calendar][150]
- Grading guidelines, which are available in the Collab wiki ([here][171] is the direct link, although Collab login is required)
- Email list archive, which is a Collab tool ([here][170] is the direct link, although Collab login is required)
- [Piazza][152]; Collab can log you in directly.

The parts of this course that are in this repo are:

- [Daily announcements slide set][102]
- [Course introduction slide set][80]
- [Course syllabus][103] ([md][104]): the course syllabus
- [Lab due dates][105] ([md][106]): When the various lab parts are due
- [UNIX honor pledge][172], which needs to be signed by all the students in the course; it is created from a [.tex][114] file
- [Generic review session slide set][113], which is really just a blank set of slides
- [Frivolous regrade policy][109] ([md][110]) for exams

------------------------------------------------------------

Labs and Tutorials
------------------

This is a series of links to the labs and tutorials that are elsewhere in this repository.  A bunch of notes:

- The lab parts are all due on specific times throughout the week, as detailed on the [lab due dates][105] ([md][106]) page
    - Each lab is for a given week, which (for sake of argument) we claim starts on a Monday
    - Which lab is done on which week is listed below in the semester schedule
- The lab is released the week before, typically on a Wednesday or Thursday
    - While a version of the lab will be in this github repo for some time prior, there **WILL** be modifications to that lab up until the "official" release, which is when it is announced as released on the twitter feed: [\@UVaCS2150](http://twitter.com/UVaCS2150)
- All the labs and tutorials can be found on the [labs page][107] ([md][108]) and the [tutorials page][100] ([md][101]).
    - In particular, these pages have additional details and links not described here

------------------------------------------------------------

Semester Schedule
-----------------

The links in the right-most column link directly to the lecture recording on Collab, and you have to be logged into Collab first before the link will work. Some plugins (such as NoScript) will block that link from working.  Unless otherwise indicated, both lectures stopped at the same point.

| Num | Date | Day of week | Lab & Tutorial (on Tue) | Planned topic | Actual lecture progress (and recording) | 
|-----|--------|-------------|----------------------------------------------------------|--------------------------|--------------------------| 
|1| Jan&nbsp;12 | Monday    | no lab this week | [Course introduction][80] | [course-introduction][80], slides [0][80] to [4-2][1000402] ([recording][201]) | 
|2| Jan&nbsp;14 | Wednesday | | [Course introduction][80], [01: C++][81] | [course-introduction][80], slides [5][10005] to [6-1][1000601] (end); [C++][81], slides [0][81] to [4-4][1010404] ([recording][202]) | 
|3| Jan&nbsp;16 | Friday    | | [01: C++][81] | [C++][81], slides [5][10105] to [6-8][1010608] ([recording][203]) | 
|     | Jan&nbsp;19 | Monday    | [Lab 1: Intro to C++][1] ([md][21]) / [Tutorial 1: Intro to UNIX][41] ([md][61]) | no class (MLK day) || 
|4| Jan&nbsp;21 | Wednesday | | [01: C++][81] | [C++][81], slides [7][10107] to [8-16][1010816] ([recording][204]) | 
|5| Jan&nbsp;23 | Friday    | | [01: C++][81] | [C++][81], slides [8-16][1010816] to [9-14][1010914] ([recording][205]) | 
|6| Jan&nbsp;26 | Monday    | [Lab 2: Linked lists][2] ([md][22]) / [Tutorial 2: LLDB][42] ([md][62]) *OR* [Tutorial 2: GDB][52] ([md][72]) (see [lab 2][2] for which one to pick) | [01: C++][81] | [C++][81], slides [9-15][1010915] to [11-5][1011105] ([recording][206]) | 
|7| Jan&nbsp;28 | Wednesday | | [01: C++][81], [02: Lists][82] | [C++][81], slides [11-6][1011106] to [12-13][1011213] (end); [lists][82], slides [0][82] to [3-4][1020304] ([recording][207]) | 
|8| Jan&nbsp;30 | Friday    | | [02: Lists][82] | [lists][82], slides [4][10204] to [6-6][1020606] ([recording][208]) | 
|9| Feb&nbsp;2  | Monday    | [Lab 3: Stacks][3] ([md][23]) / [Tutorial 3: More UNIX, part 1][63], introduction and sections 1-4 | [02: Lists][82], [03: Numbers][83] |  [lists][82], slides [6-7][1020607] to [8-3][1020803] (end); [numbers][83], slides [0][83] to [4-3][1030403] ([recording][209]) | 
|10| Feb&nbsp;4  | Wednesday | | [03: Numbers][83] | [numbers][83], slides [4-4][1030404] to [8-1][1030801] ([recording][210]) | 
|11| Feb&nbsp;6  | Friday    | | [03: Numbers][83] | [numbers][83], slides [8-1][1030801] to [8-16][1030816] ([recording][211]) | 
|12| Feb&nbsp;9  | Monday    | [Lab 4: Numbers][4] ([md][24]) / [Tutorial 4: More UNIX, part 2][64], sections 5-8 | [03: Numbers][83] | [numbers][83], slides [8-16][1030816] to [8-32][1030832] (end) ([recording][212]) | 
|13| Feb&nbsp;11 | Wednesday | | [04: Arrays & big-Oh][84] | [arrays & big-oh][84], slides [0][84] to [4-2][1040402] ([recording][213]) | 
|14| Feb&nbsp;13 | Friday    | | [04: Arrays & big-Oh][84] | [arrays & big-oh][84], slides [4-3][1040403] to [4-19][1040419] ([recording][214]) | 
|     | Feb&nbsp;15 | Sunday    | Exam 1 review session | Exam 1 review session | ([recording][215]) |
|15| Feb&nbsp;16 | Monday    | Exam 1 instead during Tuesday's lab | [04: Arrays & big-Oh][84], [05: Trees][85] | [arrays & big-oh][84], slides [4-20][1040420] to [5-7][1040507] (end); [trees][85], slides [0][85] to [3-5][1050305] ([recording][216]) | 
|16| Feb&nbsp;18 | Wednesday | | [05: Trees][85] || 
|17| Feb&nbsp;20 | Friday    | | [05: Trees][85] || 
|18| Feb&nbsp;23 | Monday    | [Lab 5: Trees][5] ([md][25]) / [Tutorial 5: make][45] ([md][65]) | [05: Trees][85] || 
|19| Feb&nbsp;25 | Wednesday | | [05: Trees][85] || 
|20| Feb&nbsp;28 | Friday    | | [06: Hashes][86] || 
|21| Mar&nbsp;2  | Monday    | | [06: Hashes][86] || 
|22| Mar&nbsp;4  | Wednesday | [Lab 6: Hashes][6] ([md][26]) / Tutorial 6: Shell scripting, part 1 (part of [this link][46]; the specific sections are mentioned on the [tutorials page][40]) | [06: Hashes][86], [07: IBCM][87] (machine language) || 
|23| Mar&nbsp;6  | Friday    | | [07: IBCM][87] (machine language) || 
|     | Mar&nbsp;9  | Monday    | | no class (spring break) || 
|     | Mar&nbsp;11 | Wednesday | | no class (spring break) || 
|     | Mar&nbsp;13 | Friday    | | no class (spring break) || 
|24| Mar&nbsp;16 | Monday    | [Lab 7: IBCM][7] ([md][27]) / Tutorial 7: Shell scripting, part 2 (remainder of [here][47], as described on the [tutorials page][40]) | [07: IBCM][87] (machine language) || 
|25| Mar&nbsp;18 | Wednesday || [07: IBCM][87] (machine language) || 
|26| Mar&nbsp;20 | Friday    | | [08: x86][88] (assembly language) || 
|27| Mar&nbsp;23 | Monday    | | [08: x86][88] (assembly language) || 
|28| Mar&nbsp;25 | Wednesday | [Lab 8: x86, part 1][8] ([md][28]) / [Tutorial 8: nasm][48], but you can skip some parts; see [here][100]) ([md][101]) for details | [08: x86][88] (assembly language) || 
|29| Mar&nbsp;27 | Friday    | | [08: x86][88] (assembly language) || 
|     | Mar&nbsp;29 | Sunday    | Exam 2 review session | Exam 2 review session || 
|30| Mar&nbsp;30 | Monday    | Exam 2 instead during Tuesday's lab | [08: x86][88], [09: Advanced C++][89] || 
|31| Apr&nbsp;1  | Wednesday || [09: Advanced C++][89] || 
|32| Apr&nbsp;3  | Friday    || [09: Advanced C++][89] || 
|33| Apr&nbsp;6  | Monday    | [Lab 9: x86, part 2][9] ([md][29]) / [Tutorial 9: C][49] ([md][69]) | [09: Advanced C++][89], [10: Heaps and Huffman coding][90]|| 
|34| Apr&nbsp;8  | Wednesday | | [10: Heaps and Huffman coding][90] || 
|35| Apr&nbsp;10 | Friday    | | [10: Heaps and Huffman coding][90] || 
|36| Apr&nbsp;13 | Monday    | [Lab 10: Huffman coding][10] ([md][30]) / [Tutorial 10: Objective C][50] ([md][70]) | [10: Heaps and Huffman coding][90], [11: Graphs][91] || 
|37| Apr&nbsp;15 | Wednesday | | [11: Graphs][91] || 
|38| Apr&nbsp;17 | Friday    | | [11: Graphs][91] || 
|39| Apr&nbsp;20 | Monday    | [Lab 11: Graphs][11] ([md][31]) / [Tutorial 11: doxygen][51] ([md][71]) | [11: Graphs][91] || 
|40| Apr&nbsp;22 | Wednesday || [11: Graphs][91], [12: Memory][92] || 
|41| Apr&nbsp;24 | Friday    | | [12: Memory][92] || 
|42| Apr&nbsp;27 | Monday    | [Lab 12: Objective C][12] ([md][32])| [12: Memory][92], [13: Esoteric PLs][93], [Course conclusion][94] || 
|     |Apr&nbsp;29| Wednesday | Final exam review session | Final exam review session || 
|     |May&nbsp;1| Friday    |Final exam from 2:00-5:00 in Gilmer 130| Final exam from 2:00-5:00 in Gilmer 130 || 

------------------------------------------------------------

Grading Concerns
----------------

None yet!


[1]: ../labs/lab01/index.html
[2]: ../labs/lab02/index.html
[3]: ../labs/lab03/index.html
[4]: ../labs/lab04/index.html
[5]: ../labs/lab05/index.html
[6]: ../labs/lab06/index.html
[7]: ../labs/lab07/index.html
[8]: ../labs/lab08/index.html
[9]: ../labs/lab09/index.html
[10]: ../labs/lab10/index.html
[11]: ../labs/lab11/index.html
[12]: ../labs/lab12/index.html

[21]: ../labs/lab01/index.md
[22]: ../labs/lab02/index.md
[23]: ../labs/lab03/index.md
[24]: ../labs/lab04/index.md
[25]: ../labs/lab05/index.md
[26]: ../labs/lab06/index.md
[27]: ../labs/lab07/index.md
[28]: ../labs/lab08/index.md
[29]: ../labs/lab09/index.md
[30]: ../labs/lab10/index.md
[31]: ../labs/lab11/index.md
[32]: ../labs/lab12/index.md

[40]: ../tutorials/index.html
[41]: ../tutorials/01-intro-unix/index.html
[42]: ../tutorials/02-lldb/index.html
[43]: ../tutorials/03-04-more-unix/index.html
[44]: ../tutorials/03-04-more-unix/index.html
[45]: ../tutorials/05-make/index.html
[46]: http://en.wikibooks.org/wiki/Bash_Shell_Scripting
[47]: http://en.wikibooks.org/wiki/Bash_Shell_Scripting
[48]: http://cs.lmu.edu/~ray/notes/nasmexamples/
[49]: ../tutorials/09-c/index.html
[50]: ../tutorials/10-objc/index.html
[51]: ../tutorials/11-doxygen/index.html
[52]: ../tutorials/02-gdb/index.html

[61]: ../tutorials/01-intro-unix/index.md
[62]: ../tutorials/02-lldb/index.md
[63]: ../tutorials/03-04-more-unix/index.html
[64]: ../tutorials/03-04-more-unix/index.html
[65]: ../tutorials/05-make/index.md
[69]: ../tutorials/09-c/index.md
[70]: ../tutorials/10-objc/index.md
[71]: ../tutorials/11-doxygen/index.md
[72]: ../tutorials/02-gdb/index.md

[80]: course-introduction.html
[81]: ../slides/01-cpp.html
[82]: ../slides/02-lists.html
[83]: ../slides/03-numbers.html
[84]: ../slides/04-arrays-bigoh.html
[85]: ../slides/05-trees.html
[86]: ../slides/06-hashes.html
[87]: ../slides/07-ibcm.html
[88]: ../slides/08-x86.html
[89]: ../slides/09-advanced-cpp.html
[90]: ../slides/10-heaps-huffman.html
[91]: ../slides/11-graphs.html
[92]: ../slides/12-memory.html
[93]: ../slides/13-esoteric-pls.html
[94]: course-conclusion.html

[100]: ../tutorials/index.html
[101]: ../tutorials/index.md
[102]: daily-announcements.html
[103]: syllabus.html
[104]: syllabus.md
[105]: labduedates.html
[106]: labduedates.md
[107]: ../labs/index.html
[108]: ../labs/index.md
[109]: frivolous-regrades.html
[110]: frivolous-regrades.md
[111]: ../README.html
[112]: ../README.md
[113]: exam-review.html
[114]: unix-honor-pledge.tex

[150]: https://www.google.com/calendar/embed?src=1ea0dfillqvhlop8d7t0m8afuo%40group.calendar.google.com&amp;amp;ctz=America/New_York
[151]: http://twitter.com/UVaCS2150
[152]: https://piazza.com/

[160]: https://libra.cs.virginia.edu/~pedagogy/
[161]: https://libra.cs.virginia.edu/~pedagogy/support.php
[162]: https://libra.cs.virginia.edu/~pedagogy/submit.php
[163]: https://libra.cs.virginia.edu/~pedagogy/regrades.php
[164]: https://libra.cs.virginia.edu/~pedagogy/gradebook.php
[165]: https://libra.cs.virginia.edu/~pedagogy/labextension.php
[166]: https://libra.cs.virginia.edu/~pedagogy/queue.php

[170]: https://collab.itc.virginia.edu/portal/site/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/page/d7063d9b-9eac-4ace-81ec-ad9bc490773a
[171]: https://collab.itc.virginia.edu/portal/site/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/page/a2db052c-c714-443e-b1fb-f1706a74f9a3
[172]: unix-honor-pledge-s15.pdf

[201]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/course-introduction-1/course-introduction-1.htm
[202]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/01-cpp-1/01-cpp-1.htm
[203]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/01-cpp-2/01-cpp-2.htm
[204]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/01-cpp-3/01-cpp-3.htm
[205]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/01-cpp-4/01-cpp-4.htm
[206]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/01-cpp-5/01-cpp-5.htm
[207]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/02-lists-1/02-lists-1.htm
[208]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/02-lists-2/02-lists-2.htm
[209]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/03-numbers-1/03-numbers-1.htm
[210]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/03-numbers-2/03-numbers-2.htm
[211]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/03-numbers-3/03-numbers-3.htm
[212]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/03-numbers-4/03-numbers-4.htm
[213]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/04-arrays-bigoh-1/04-arrays-bigoh-1.htm
[214]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/04-arrays-bigoh-2/04-arrays-bigoh-2.htm
[215]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/exam1-review/exam1-review.htm
[216]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/05-trees-1/05-trees-1.htm
[217]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/05-trees-2/05-trees-2.htm
[218]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/05-trees-3/05-trees-3.htm
[219]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/05-trees-4/05-trees-4.htm
[220]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/05-trees-5/05-trees-5.htm
[221]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/06-hashes-1/06-hashes-1.htm
[222]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/06-hashes-2/06-hashes-2.htm
[223]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/07-ibcm-1/07-ibcm-1.htm
[224]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/07-ibcm-2/07-ibcm-2.htm
[225]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/07-ibcm-3/07-ibcm-3.htm
[226]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/07-ibcm-4/07-ibcm-4.htm
[227]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/08-x86-1/08-x86-1.htm
[228]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/08-x86-2/08-x86-2.htm
[229]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/08-x86-3/08-x86-3.htm
[230]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/08-x86-4/08-x86-4.htm
[231]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/09-advanced-cpp-1/09-advanced-cpp-1.htm
[232]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/09-advanced-cpp-2/09-advanced-cpp-2.htm
[233]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/exam2-review/exam2-review.htm
[234]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/09-advanced-cpp-3/09-advanced-cpp-3.htm
[235]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/10-heaps-huffman-1/10-heaps-huffman-1.htm
[236]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/10-heaps-huffman-2/10-heaps-huffman-2.htm
[237]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/10-heaps-huffman-3/10-heaps-huffman-3.htm
[238]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/11-graphs-1/11-graphs-1.htm
[239]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/11-graphs-2/11-graphs-2.htm
[240]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/11-graphs-3/11-graphs-3.htm
[241]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/11-graphs-4/11-graphs-4.htm
[242]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/12-memory-1/12-memory-1.htm
[243]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/course-conclusion/course-conclusion.htm
[244]: https://collab.itc.virginia.edu/access/content/group/1b09d7e7-bd84-4b3e-9ef4-8e020dbef1f0/lectures/final-review/final-review.htm

[1000402]: ../cs2150/course-introduction.html#/4/2
[10005]: ../cs2150/course-introduction.html#/5
[1000601]: ../cs2150/course-introduction.html#/6/1
[1010404]: ../slides/01-cpp.html#/4/4
[10105]: ../slides/01-cpp.html#/5
[1010608]: ../slides/01-cpp.html#/6/8
[10107]: ../slides/01-cpp.html#/7
[1010816]: ../slides/01-cpp.html#/8/16
[1010914]: ../slides/01-cpp.html#/9/14
[1010915]: ../slides/01-cpp.html#/9/15
[1011105]: ../slides/01-cpp.html#/11/5
[1011106]: ../slides/01-cpp.html#/11/6
[1011213]: ../slides/01-cpp.html#/12/13
[1020304]: ../slides/02-lists.html#/3/4
[10204]: ../slides/02-lists.html#/4
[1020606]: ../slides/02-lists.html#/6/6
[1020607]: ../slides/02-lists.html#/6/7
[1020803]: ../slides/02-lists.html#/8/3
[1030403]: ../slides/03-numbers.html#/4/3
[1030404]: ../slides/03-numbers.html#/4/4
[1030801]: ../slides/03-numbers.html#/8/1
[1030816]: ../slides/03-numbers.html#/8/16
[1030832]: ../slides/03-numbers.html#/8/32
[1040402]: ../slides/04-arrays-bigoh.html#/4/2
[1040403]: ../slides/04-arrays-bigoh.html#/4/3
[1040419]: ../slides/04-arrays-bigoh.html#/4/19
[1040420]: ../slides/04-arrays-bigoh.html#/4/20
[1040507]: ../slides/04-arrays-bigoh.html#/5/7
[1050305]: ../slides/05-trees.html#/3/5
[1050311]: ../slides/05-trees.html#/3/11
[1050416]: ../slides/05-trees.html#/4/16
[1050417]: ../slides/05-trees.html#/4/17
[1050617]: ../slides/05-trees.html#/6/17
[1050703]: ../slides/05-trees.html#/7/3
[1050709]: ../slides/05-trees.html#/7/9
[1050909]: ../slides/05-trees.html#/9/9
[1060413]: ../slides/06-hashes.html#/4/13
[10605]: ../slides/06-hashes.html#/5
[1060608]: ../slides/06-hashes.html#/6/8
[1060609]: ../slides/06-hashes.html#/6/9
[1060706]: ../slides/06-hashes.html#/7/6
[1070302]: ../slides/07-ibcm.html#/3/2
[1070303]: ../slides/07-ibcm.html#/3/3
[1070415]: ../slides/07-ibcm.html#/4/15
[10705]: ../slides/07-ibcm.html#/5
[1070511]: ../slides/07-ibcm.html#/5/11
[1070604]: ../slides/07-ibcm.html#/6/4
[1080410]: ../slides/08-x86.html#/4/10
[10805]: ../slides/08-x86.html#/5
[1080607]: ../slides/08-x86.html#/6/7
[1080608]: ../slides/08-x86.html#/6/8
[1080804]: ../slides/08-x86.html#/8/4
[1080914]: ../slides/08-x86.html#/9/14
[1080915]: ../slides/08-x86.html#/9/15
[1080932]: ../slides/08-x86.html#/9/32
[1090308]: ../slides/09-advanced-cpp.html#/3/8
[1090518]: ../slides/09-advanced-cpp.html#/5/18
[1090708]: ../slides/09-advanced-cpp.html#/7/8
[1090710]: ../slides/09-advanced-cpp.html#/7/10
[1100408]: ../slides/10-heaps-huffman.html#/4/8
[11005]: ../slides/10-heaps-huffman.html#/5
[1100508]: ../slides/10-heaps-huffman.html#/5/8
[1100705]: ../slides/10-heaps-huffman.html#/7/5
[1100808]: ../slides/10-heaps-huffman.html#/8/8
[1110304]: ../slides/11-graphs.html#/3/4
[1110305]: ../slides/11-graphs.html#/3/5
[1110408]: ../slides/11-graphs.html#/4/8
[11105]: ../slides/11-graphs.html#/5
[1110513]: ../slides/11-graphs.html#/5/13
[11106]: ../slides/11-graphs.html#/6
[1110806]: ../slides/11-graphs.html#/8/6
[1110814]: ../slides/11-graphs.html#/8/14
[1120308]: ../slides/12-memory.html#/3/8
[1120325]: ../slides/12-memory.html#/3/25
[1130325]: ../slides/13-esoteric-pls.html#/3/25
[12009]: course-conclusion.html#/9
