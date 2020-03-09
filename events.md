## Activities & Events

### 28.02.2020: Demo of early RIOT-fp prototype at European Commission (Brussels)

At H2020 SPARTA project review at Brussels European Commission, a [preliminary prototype demo of RIOT-fp](https://future-proof-iot.github.io/RIOT-fp/files/(2020-02)-SPARTA-RIOT-fp-demo.pdf) was presented, demonstrating secure low-power IoT firmware update on an indoor air quality monitor.

### 19.02.2020: Draft Requirements Document for the LAKE protocol
The IETF has issued its last call for our draft [requirements for the LAKE protocol](https://tools.ietf.org/html/draft-ietf-lake-reqs-01).

### 06.02.2020: Preliminary design of a zero-touch enrollment protocol
We have published a [preliminary design for a zero-touch enrollment protocol](https://tools.ietf.org/html/draft-selander-ace-ake-authz-00) based on LAKE.



### 15.11.2019: New RIOT Release with Initial SUIT Support
The latest release ([Release-2019.10](https://github.com/RIOT-OS/RIOT/releases/tag/2019.10)) of RIOT is now available. This release brings a number of improvements and additional features, including initial support for SUIT-compliant secure IoT firmware updates, over the network. Check out this [example](https://github.com/RIOT-OS/RIOT/tree/master/examples/suit_update) which you could reproduce on your favorite low-power hardware!

### 19.09.2019: RIOT-fp Workshop Fall 2019
The first RIOT-fp workshop takes place in Paris on Sept. 19th 2019. Here is the [agenda](workshops/RIOT-fp-Workshop-2019-09-19-kickoff.md).

### 10.09.2019: Applicability of Refinement Type Theory for Embedded IoT Logic
We have published a paper investigating the [applicability of refinement type theory to IoT devices](https://ieeexplore.ieee.org/abstract/document/8715067). In practice, we consider the simple yet challenging verification of a stepper motor controller. The paper overviews the constraints which challenge thorough verification using F*. This study encompasses not only software artefacts such as the OS running on the device, but also physical artefacts, including a discrete real-time abstraction of its hardware architecture. A version of the paper not behind a paywall is also [available](https://www.irisa.fr/prive/talpin/papers/date19.pdf).

### 27.08.2019: IETF steps towards authenticated key exchange for OSCORE

A new working group called [LAKE](https://datatracker.ietf.org/wg/lake/about/) (Lightweight Authenticated Key Exchange) is being chartered in the IETF aiming to design a [key exchange](https://tools.ietf.org/html/draft-selander-lake-reqs) protocol for OSCORE. OSCORE is an application-layer protection mechanism for CoAP used in 6TiSCH networks. The LAKE outcome is important for RIOT-fp as one of our objectives is to design a zero-touch secure joining protocol for Internet of Things networks, with dependency on both OSCORE and LAKE.

### 07.06.2019: New publication on secure IoT firmware update

Together with ARM, we published a [new article](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8725488) in IEEE Access, which describes the guts of our preliminary prototype for secure firmware update on microcontroller-based IoT devices, using RIOT and the upcoming SUIT specification from IETF.

### 02.05.2019: New RIOT release!

RIOT 2019.04 is now [available](https://github.com/RIOT-OS/RIOT/releases/tag/2019.04), which includes a number of new features including porting of riotboot to a number of new platforms, and the ability for firmware to flash images into a separate boot slot. Basic IEEE 802.15.4 support was added on the nRF52840, as well as support for several new boards and new sensors.

### 26.04.2019: New website

The RIOT-fp [website](https://future-proof-iot.github.io/RIOT-fp) launched!

### 20.03.2019: RIOT-fp project start

The RIOT-fp project launched!



