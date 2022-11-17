## Introduction to CPU architecture and security

💬 *This repository aims to collect content and multiple materials on CPU's security and exploitation:<br>
mostly on how CPUs work and are designed and security vulnerabilities and attacks raised by its default implementation.*<br>

*CPU architecture and vulnerabilities are one of my main interest subjects.<br>
So I decided to use this repo to gather all info I could about this topic in one place*

*Enjoy! (:*


## 0x00 how computers work?

### books
- [ ] [How Computers Really Work](https://www.amazon.com/Amps-Apps-How-Computers-Work/dp/1718500661)
- [ ] [ Computer Organization and Architecture - William Stallings]()
- [ ] [Modern operating systems - Tanenbaum](https://www.amazon.com/Modern-Operating-Systems-Andrew-Tanenbaum/dp/013359162X)
- [ ] [Structured computer organization - Tanenbaum](https://www.pearson.com/en-us/subject-catalog/p/structured-computer-organization/P200000003183/9780137618446)
- [ ] [Computer Architecture and Security](http://www.iqytechnicalcollege.com/Computer%20Architecture%20and%20Security.pdf)

### courses & materials

**videos/series**
- [ ] [Computer Architecture Complete Course](https://www.youtube.com/watch?v=9nuAjYRbITQ)
- [ ] [CS50 Lectures](https://www.youtube.com/watch?v=8mAITcNt710)
- [ ] [Digital Design & Computer Architecture - ETH Zürich](https://www.youtube.com/playlist?list=PL5Q2soXY2Zi_FRrloMa2fUYWPGiZUBQo2)
- [ ] [How do computers work?](https://www.youtube.com/watch?v=7J7X7aZvMXQ)
- [ ] [Exploring How Computers Work](https://www.youtube.com/playlist?list=PLFt_AvWsXl0dPhqVsKt1Ni_46ARyiCGSq)
- [ ] [Build a 65c02-based computer from scratch](https://www.youtube.com/playlist?list=PLowKtXNTBypFbtuVMUVXNR0z1mu7dp7eH)

**others**
- [ ] [CS 61 - Systems Programming and Machine Organization (2022)](https://cs61.seas.harvard.edu/site/2022/#gsc.tab=0)

## CPU 101

### videos/series
- [ ] [CPU Design series](https://www.youtube.com/playlist?list=PLqCJpWy5Fohdz6Nu2yG6Loubocqk3sRNR)
- [ ] [Architecture All Access - Intel Series](https://www.youtube.com/playlist?list=PL8t1FdN2Tj3ZVAzTY-FvsS0qy-mEfRdoj)
- [ ] [How A CPU Works | The CPU Explained](https://www.youtube.com/watch?v=XQq_1yaVDpM)
- [ ] [How a CPU works - In One Lesson](https://www.youtube.com/watch?v=cNN_tTXABUA)
- [ ] [Inside the CPU - Computerphile](https://www.youtube.com/watch?v=IAkj32VPcUE)
- [ ] [Physics of Computer Chips - Computerphile](https://www.youtube.com/watch?v=xkLAhU74f3s)
- [ ] [The Fetch-Execute Cycle - Tom Scott](https://www.youtube.com/watch?v=Z5JC9Ve1sfI)
- [ ] [Coding Communication & CPU Microarchitectures](https://www.youtube.com/watch?v=FkeRMQzD-0Y)
- [ ] [Evolution Of CPU Processing Power](https://www.youtube.com/playlist?list=PLC7a8fNahjQ8IkiD5f7blIYrro9oeIfJU)

### docs & articles
- [ ] [Understanding the fundamentals of CPU architecture ](https://uu.diva-portal.org/smash/get/diva2:1217222/FULLTEXT01.pdf)
- [ ] [A hackers tour of the x86 CPU architecture](https://www.secureideas.com/blog/2021/04/a-hackers-tour-of-the-x86-cpu-architecture.html)
- [ ] [Stanford CS155 - Processor Security](https://cs155.stanford.edu/lectures/17-processor.pdf)
- [ ] [The purpose of the CPU](https://www.bbc.co.uk/bitesize/guides/zhppfcw/revision/1)

### programming
- [ ] [Design Your Own CPU Instruction Set](https://www.youtube.com/watch?v=wjHlvQfo5uI)
- [ ] [Building A CPU From Scratch](https://www.youtube.com/playlist?list=PLilenfQGj6CEG6iZ4TQJ10PI7pCWsy1AO)

### CPU vulnerabilities

**videos/conferences**
- [ ] [[Red Hat] Understanding Microarchitectural Data Sampling (aka MDS, ZombieLoad, RIDL & Fallout)](https://www.youtube.com/watch?v=Xn-wY6Ir1hw)
- [ ] [Discover vulnerabilities in Intel CPUs - LiveOverflow](https://www.youtube.com/watch?v=x_R1DeZxGc0)
- [ ] [How CPUs Access Hardware - Another SerenityOS Exploit](https://www.youtube.com/watch?v=1hpqiWKFGQs)
- [ ] [[Blackhat] The Memory Sinkhole - Unleashing An X86 Design Flaw Allowing Universal Privilege Escalation](https://www.youtube.com/watch?v=lR0nh-TdpVg)
- [ ] [[Blackhat] Breaking the x86 Instruction Set - Chris Domas](https://www.youtube.com/watch?v=KrksBdWcZgQ)
- [ ] [[Blackhat] GOD MODE UNLOCKED - Hardware Backdoors in x86 CPUs](https://www.youtube.com/watch?v=_eSAF_qT_FY)
- [ ] [Exploiting vulnerabilities in the CPU microcode - Pedro Candel](https://www.youtube.com/watch?v=V_C0y-fh1Cw)
- [ ] [Microarchitectural Incontinence - Daniel Gruss](https://www.youtube.com/watch?v=cAWmNp3Ukqk)
- [ ] [[RSA Conference] Spectre Attacks: Exploiting Speculative Execution](https://www.youtube.com/watch?v=NnbDolQSF2c)
- [ ] [[IEEE Symposium] RIDL: Rogue In-Flight Data Load](https://www.youtube.com/watch?v=1Y0h4JyK3fs)

**articles & blogs**
- [ ] [Side Channel Vulnerabilities: Microarchitectural Data Sampling and Transactional Asynchronous Abort](https://www.intel.com/content/www/us/en/architecture-and-technology/mds.html)
- [ ] [Intel software security guidance](https://www.intel.com/content/www/us/en/developer/topic-technology/software-security-guidance/overview.html)
- [ ] [Foreshadow - Breaking the virtual memory abstraction with transient out-of-order execution](https://foreshadowattack.eu/)
- [ ] [LVI - Hijacking transient execution with load value injection](https://lviattack.eu/)
- [ ] [MDS: Microarchitectural Data Sampling](https://mdsattacks.com/)
- [ ] [Zombie Load attack](https://zombieloadattack.com/)
- [ ] [Meltdown and Spectre Vulnerabilities in modern computers leak passwords and sensitive data](https://spectreattack.com/)
- [ ] [Platypus - software-based power side-channel attacks](https://platypusattack.com/)
- [ ] [Pluntervolt - corrupting the integrity of Intel SGX on Intel Core](https://plundervolt.com/)
- [ ] [TPM Fail -  timing leakage on Intel firmware-based TPM](https://tpm.fail/)
- [ ] [netCAT - network-based cache side-channel attack](https://www.vusec.net/projects/netcat/)
- [ ] [LazyFP - Exploiting lazy FPU state switching](https://blog.cyberus-technology.de/posts/2018-06-06-intel-lazyfp-vulnerability.html)

**tools & exploits**
- [ ] [Portsmash](https://github.com/bbbrumley/portsmash)

### papers
- [ ] [Microarchitectural attacks and Countermeasures](https://www.diva-portal.org/smash/get/diva2:483610/FULLTEXT01.pdf)
- [ ] [Speculose: Analyzing the Security Implications of Speculative Execution in CPUs](https://arxiv.org/pdf/1801.04084.pdf)
- [ ] [Platypus: Software-based Power Side-Channel Attacks on x86](https://platypusattack.com/platypus.pdf)
- [ ] [Plundervolt: Software-based Fault Injection Attacks against Intel SGX](https://plundervolt.com/doc/plundervolt.pdf)
- [ ] [SgxPectre Attacks: Stealing Intel Secrets from SGX Enclaves via Speculative Execution](https://arxiv.org/pdf/1802.09085.pdf)
- [ ] [Spectre Returns! Speculation Attacks using the Return Stack Buffer](https://arxiv.org/pdf/1807.07940.pdf)
