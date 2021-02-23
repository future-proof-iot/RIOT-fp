## Activities & Related News


### 18.01.2021: Towards a Formally Verified RIOT Bootloader Using Rust and Hacspec

We are developing further [Hacspec](https://github.com/hacspec/hacspec) combined with a rewrite of the [RIOT bootloader in Rust](https://github.com/hacspec/hacspec/tree/master/examples/riot-bootloader/src) towards producing a formally verified bootloader for RIOT applicable on low-power microcontrollers.
Potential perspectives with this workflow include formally verifying other modules in RIOT core, provided by [RIOT-rs](https://github.com/future-proof-iot/RIOT-rs), an experimental drop-in replacement core for RIOT, based on the Rust embedded ecosystem.


### 03.12.2020: Minimal Virtual Machines for Low-power Microcontrollers with rBPF

WVirtual machines (VM) are widely used to host and isolate software modules. However, extremely small memory and low-energy budgets have so far prevented wide use of VMs on typical microcontroller-based IoT devices. We just published a paper showing that a register-based VM using extended Berkeley Packet Filters (eBPF) is a promising approach to host small software modules, isolated from OS software, and updatable on-demand, over low-power networks. Execution time and memory overhead with our [prototype design and implementation rBPF](https://arxiv.org/pdf/2011.12047.pdf) seem quite tolerable for microcontroller-based IoT devices.


### 19.11.2020: First EDHOC Implementations and First Interop Tests!
We published the first [EDHOC implementation](https://github.com/TimothyClaeys/py-edhoc)! This implementation is in Python. In parallel we are already hard at work on a separate [EDHOC implementation in C](https://github.com/TimothyClaeys/EDHOC-C). We next plan to publish EDHOC-C integration in RIOT and OpenWSN, and to participate in interoperability fests in the context of IETF (LAKE working group). Check out [EDHOC draft specifications](https://tools.ietf.org/html/draft-ietf-lake-edhoc-04)!

### 28.10.2020: Formal Verification of Elliptic Curve Cryptography (at ECC 2020)
We participate in [ECC 2020](https://eccworkshop.org/2020/): several RIOT-fp contributors take part in a panel dedicated to formal verification of Elliptic Curve Cryptography. Tune in!

### 15.09.2020: RIOT Summit 2020
The yearly meetup for the RIOT community took place online this year. Featuring 170 registered participants from 4 continents, a keynote from Andrew S. Tanenbaum, and a variety of talks covering virtually all aspects of IoT, including security. In retrospect: you can check out the [slides](https://summit.riot-os.org/2020) of plenary talks & breakout sessions, as well as their [video recordings](https://www.youtube.com/watch?v=t2nhqepSxb4&list=PLDXXQJiSjPKHpZpiPee7OYaJpUmmfV6Nh) on Youtube.

### 11.09.2020: Tutorial at IEEE Euro S&P Conference
We have conducted online the [IEEE Security & Privacy tutorial on Microcontroller-based IoT Security](https://future-proof-iot.github.io/Tutorial/) based on the RIOT-fp prototype software platform, and leveraging our open access testbed FIT IoT-lab for remote participants.

### 02.08.2020: EDHOC Draft Specification
Following the formation of the LAKE working group at IETF, a preliminary [draft specification](https://tools.ietf.org/html/draft-ietf-lake-edhoc-01) is out fro Ephemeral Diffie-Hellman Over COSE (EDHOC). By reusing COSE for cryptography, CBOR for encoding, and CoAP for transport, the aim is to keep additional code footprint very low -- a goal we certainly value in RIOT-fp, in the context of which work is about to start implementating EDHOC.

### 24.07.2020: OpenWSN Network Stack Support in New RIOT Release 
The latest [RIOT release 2020.07](https://github.com/RIOT-OS/RIOT/releases/tag/2020.07) has been released. New network protocols were ported for RIOT such as MQTT and the lookup clientcomponent for CoRE RD. The OpenWSN network stack with 6TiSCH support is now also supported in RIOT. 546 pull requests, composed of 10452 commits, have been merged since the last release 3 months ago, and 84 issues have been solved. 64 people contributed with code in 106 days!

### 15.07.2020: New SUIT draft Specification Released
We have published a new version (-09) of the IETF draft specification for the [SUIT manifest](https://tools.ietf.org/html/draft-ietf-suit-manifest-09) which secures IoT software updates metadata by re-using CBOR and COSE, end-to-end while in transit from the authorized software OEM to the IoT device, in a low-power manner.

### 28.06.2020 Faster Isogeny-based Cryptosystems
We have a new publication on isogeny-based cryptosystems, which offer particularly small key-sizes. In particular, we focused on CSIDH, which appeared after the initial deadline for the NIST process.  While CSIDH has some important potential applications, it currently imposes an inconvenient computational cost, and adapting it to IoT devices is a significant challenge.  We have made an important algorithmic advance: in our [publication](https://arxiv.org/abs/2003.10118) at ANTS-XIV, we give an algorithm which computes large-degree isogenies in square-root (rather than linear) time. This kindles hope for producing efficient, side-channel-aware CSIDH implementations for microcontrollers!

### 04.06.2020: MooC on IoT and Security with Microcontrollers
The first season of the MooC is a wrap! We have co-authored and released a new [massive online course on low-power IoT](https://www.fun-mooc.fr/courses/course-v1:inria+41020+session01/about), featuring a large part with hands-on activities using RIOT. Of course, there was a module dedicated to IoT security featuring SUIT-compliant IoT software udates! There were 6,757 participants from 110 countries for this first session this semester. Next session in Feb. 2021. Be there!

### 27.04.2020: Information Flow Control with LIO* 
In the larger context of our work on composing formal guarantees on embedded code, we have published a new [report](https://arxiv.org/pdf/2004.12885.pdf) on low-level information flow control with F*.

### 09.03.2020: New IETF Draft Standard Specification for Secure IoT software Updates
We have published a new version (-04) of the IETF draft specification for the [SUIT manifest](https://tools.ietf.org/html/draft-ietf-suit-manifest-04) which secures IoT software updates metadata, end-to-end while in transit from the authorized software OEM to the IoT device, in a low-power manner.

### 28.02.2020: Demo of Early RIOT-fp Prototype at European Commission (Brussels)
At H2020 SPARTA project review at Brussels European Commission, a [preliminary prototype demo of RIOT-fp](https://future-proof-iot.github.io/RIOT-fp/files/(2020-02)-SPARTA-RIOT-fp-demo.pdf) was presented, demonstrating secure low-power IoT firmware update on an indoor air quality monitor.

### 19.02.2020: Draft Requirements Document for the LAKE protocol
The IETF has issued its last call for our draft [requirements for the LAKE protocol](https://tools.ietf.org/html/draft-ietf-lake-reqs-01).

### 06.02.2020: Preliminary Design of a Zero-touch Enrollment Protocol
We have published a [preliminary design for a zero-touch enrollment protocol](https://tools.ietf.org/html/draft-selander-ace-ake-authz-00) based on LAKE.

### 15.11.2019: New RIOT Release with Initial SUIT Support
The latest release ([Release-2019.10](https://github.com/RIOT-OS/RIOT/releases/tag/2019.10)) of RIOT is now available. This release brings a number of improvements and additional features, including initial support for SUIT-compliant secure IoT firmware updates, over the network. Check out this [example](https://github.com/RIOT-OS/RIOT/tree/master/examples/suit_update) which you could reproduce on your favorite low-power hardware!

### 19.09.2019: RIOT-fp Workshop Fall 2019
The first RIOT-fp workshop takes place in Paris on Sept. 19th 2019. Here is the [agenda](workshops/RIOT-fp-Workshop-2019-09-19-kickoff.md).

### 10.09.2019: Applicability of Refinement Type Theory for Embedded IoT Logic
We have published a paper investigating the [applicability of refinement type theory to IoT devices](https://ieeexplore.ieee.org/abstract/document/8715067). In practice, we consider the simple yet challenging verification of a stepper motor controller. The paper overviews the constraints which challenge thorough verification using F*. This study encompasses not only software artefacts such as the OS running on the device, but also physical artefacts, including a discrete real-time abstraction of its hardware architecture. A version of the paper not behind a paywall is also [available](https://www.irisa.fr/prive/talpin/papers/date19.pdf).

### 27.08.2019: IETF steps Towards Authenticated Key Exchange for OSCORE

A new working group called [LAKE](https://datatracker.ietf.org/wg/lake/about/) (Lightweight Authenticated Key Exchange) is being chartered in the IETF aiming to design a [key exchange](https://tools.ietf.org/html/draft-selander-lake-reqs) protocol for OSCORE. OSCORE is an application-layer protection mechanism for CoAP used in 6TiSCH networks. The LAKE outcome is important for RIOT-fp as one of our objectives is to design a zero-touch secure joining protocol for Internet of Things networks, with dependency on both OSCORE and LAKE.

### 07.06.2019: New Publication on secure IoT Firmware Update

Together with ARM, we published a [new article](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8725488) in IEEE Access, which describes the guts of our preliminary prototype for secure firmware update on microcontroller-based IoT devices, using RIOT and the upcoming SUIT specification from IETF.

### 02.05.2019: New RIOT release!

RIOT 2019.04 is now [available](https://github.com/RIOT-OS/RIOT/releases/tag/2019.04), which includes a number of new features including porting of riotboot to a number of new platforms, and the ability for firmware to flash images into a separate boot slot. Basic IEEE 802.15.4 support was added on the nRF52840, as well as support for several new boards and new sensors.

### 26.04.2019: New website

The RIOT-fp [website](https://future-proof-iot.github.io/RIOT-fp) launched!

### 20.03.2019: RIOT-fp project start

The RIOT-fp project launched!



