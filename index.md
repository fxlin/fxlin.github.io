## Felix Xiaozhu Lin   林 小竹

Associate Prof. | William Wulf Faculty Fellow | UVA Computer Science | [CV](/cv.pdf) | [Contact](/contact.html)

PhD (Rice '14); MS/BS ('08/'06 Tsinghua). Grew up in a small midwestern town in China. Before UVA, six great years at [Purdue](./leaving.pdf).

<!--- 
**I care system software for addressing challenges raised by new workloads and new hardware. My recent work includes OS support for stream processing, for heterogeneous memory, and for wearable devices.**
-->

**Fall 2024: We are recruiting!**
(Recent projects) algo x sys x hw for: 

* LLMs: on-device execution, private data selection & training 
* Speech: execution of deep models on $35 hardware
* Stable diffusion: fast sampling on consumer CPU/GPU  
* Geometric deep learning: 3D vision, graph neural networks, etc. 
* Various old-fashioned, hardcore OS stuffs (see pubs below) 

I led a group of graduate/undergraduate students who are execited by building cool software stuffs. 

See our [group page](http://xsel.rocks) for current students and projects.

Virginia is for lovers! 

<!---- https://dailyprogress.com/uva-aerial/image_aa006d50-0868-11e4-b818-001a4bcf6878.html The UVA campus in the Fall, [credits](https://dailyprogress.com/uva-aerial/image_aa006d50-0868-11e4-b818-001a4bcf6878.html) -->

<img src="img\sunset_grounds_ss_18.jpg" alt="img/aerial.img" style="zoom: 33%;" />
The UVA campus at sunset, with Blue Ridge mountains in the back. Credit: UVA.

**Efforts on refreshing OS education** (UVA CS4414/CS6456). *Principles*: experience-based, with modern contents, and fun. *Summary*: four projects including an Arm64 baremetal kernel, multicore, trusted execution, and filesystem forensics.

The first offering in Fall'20 as CS6456. Well received!  [Materials](https://github.com/fxlin/os-course/tree/master/docs); [student feedbacks](https://github.com/fxlin/os-course/blob/master/Report%20for%20CS%206456%20-%20001%20Operating%20Systems%20Xiaozhu%20Lin_3E9C532B-F1EE-494A-A44F-3B9766CB3912en-US.pdf); [schedule](https://github.com/fxlin/os-course/blob/master/cs6456-fall20-schedule.pdf)

## Research ([Publications](https://thexsel.github.io/papers.html))

<!--- 
I care about systems software -- mostly for computers consuming power roughly in the (10 Milliwatt, 500 Watt) range. 
Today they include sensors, smart phones/devices, and edge servers. 
-->

I care about systems software. I work with a group of students with enthusiasm in systems software. See [XSEL](http://xsel.rocks). 

Our current work bases on two premises: 

### 1. Old kernels (e.g. Linux) are firmware 
* Reuse via Replay: GPU replay [ASPLOS'22, Eurosys'23]; Driverlet [Eurosys'22].
* Transkernel: unmodified Linux drivers on microcontroller-like cores ([ATC'19](https://arxiv.org/abs/1811.05000) and [HotMobile'17](https://thexsel.github.io/papers/hotmobile17.pdf)).
* Overwatch: safeguarding unmodified file systems for IoT devices ([preprint](https://arxiv.org/abs/1902.06327))
* Power sandbox: power awareness redefined ([Eurosys'18](https://thexsel.github.io/p/psbox/index.html)).

### 2. New OSes are defined by scenarios 
* STI: turbocharged NLP inference [ASPLOS'23]
* Elf: autonomous AI cameras ([Mobisys'20](https://arxiv.org/abs/1909.00841), [3-min video](https://www.dropbox.com/s/rv71kw1frkp9yqu/elf-3min.mp4?dl=0), [website](https://xumengwei.github.io/projects/elf.html), [slides](https://xumengwei.github.io/files/MobiSys-Elf-slides.pdf))
* VStore: managing large archival videos for analytics ([Eurosys'19](https://arxiv.org/abs/1810.01794)). 
* StreamBox: stream analytics with manycores ([ATC'17](https://thexsel.github.io/p/streambox/index.html)), with 3D-stacked memory ([ASPLOS'19](https://arxiv.org/abs/1901.01328)), and with Arm TrustZone ([ATC'19](https://arxiv.org/abs/1808.05078)).


My PhD work was on OS kernels for smartphones, e.g. the [K2 project](http://www.k2os.org) which won an award in ASPLOS'14. I continue to care about mobile/wearables, e.g. deep learning on them ([WWW'19](https://arxiv.org/abs/1812.05448) & [MobiCom'18](https://arxiv.org/abs/1712.01670)). 

## Doc, code, talks
* [Notes](https://bakhi.github.io/mobileGPU/) on hacking mobile GPUs
* [GPUReplay](https://github.com/bakhi/GPUReplay)
* [Driverlet](https://zaxguo.github.io/drvlet/index.html)
* Jun 2020: **"OS frontiers in the AI era"** For UVA graduate students. [slides](https://www.slideshare.net/secret/4GjP2jyTXuau6x) [video](https://youtu.be/Ntm388nz2CY)
* Mar 2019: **Overview** [slides](https://www.slideshare.net/secret/JS0VXXRm579Wnu)

## Useful 

[Need a reference letter from me?](/letter-policy.pdf)
| [How do I determine final grades for undergrad classes?](/final-grades.pdf)
| [How do we work with undergrads in research?](/undergrad-research.pdf)
| [To signature requesters](/sign.html)
| [Name in Chinese](/img/name.jpg)

<img src="img\forlovers.jpg" alt="img/forlovers.img" style="zoom:50%;" />
We are one-hour from the gorgeous Shenandoah national park. Unlimited outdoor fun. Photo: http://virginia.org

