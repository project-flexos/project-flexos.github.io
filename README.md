<p align="center">
  <img width="200" src="https://github.com/project-flexos/project-flexos.github.io/raw/main/logo/SVG/logo-flexos-png.svg">
<link rel="shortcut icon" type="image/png" href="logo/FAVICON/flexos-favicon-8.png">
</p>

* * *
**News**
- Hugo's [PhD thesis was published](https://pure.manchester.ac.uk/ws/portalfiles/portal/317271609/FULL_TEXT.PDF).
- FlexOS will be presented at the [Huawei Future Device Technology Summit’23](https://github.com/project-flexos/project-flexos.github.io/raw/main/docs/Huawei_Future_Device_Summit_Helsinki.pdf).
- We have ported FlexOS to the [CHERI/ARM Morello](https://www.arm.com/architecture/cpu/morello) platform, to learn more check out our [PLOS'23](https://plos-workshop.org/2023/) paper "[Software Compartmentalization Trade-Offs with Hardware Capabilities](https://arxiv.org/abs/2309.11332)".
- Our follow-up work, [ConfFuzz](https://conffuzz.github.io/), was accepted at NDSS'23!
- We will hold a FlexOS session at the [Lyon Unikraft Hackathon](https://unikraft.org/community/hackathons/2022-05-lyon/).
- FlexOS will be presented [at SPMA'22](https://sites.google.com/view/spma22eurosys/home).
- Our FlexOS [paper](https://arxiv.org/abs/2112.06566) was awarded the Distinguised Artifact Award at [ASPLOS'22](https://asplos-conference.org/)!
- FlexOS will be presented [at FGBS'22](https://www.betriebssysteme.org/aktivitaeten/treffen/2022-hamburg/programm/).
- FlexOS will be presented [at FOSDEM](https://fosdem.org/2022/schedule/event/tee_flexos/) as part of the Hardware-Aided Trusted Computing track.
- Our FlexOS [paper](https://arxiv.org/abs/2112.06566) was accepted to appear
at [ASPLOS 2022](https://asplos-conference.org/).

* * *

Operating Systems (OSes) have historically been classified according to their isolation properties: monolithic OSes, microkernels, single-address-space OSes, or unikernels... Decades of experience in research and industry showed that there is no silver bullet and that different use-cases might demand different approaches to optimize safety and performance.

What if we tried to design an operating system able to be easily reconfigured into any of these points in the OS design space? What if the OS could be a microkernel, a unikernel, or a monolithic OS, at will, and using a wide range of hardware- and software-backed isolation mechanisms?

FlexOS is an effort to try and answer these questions. FlexOS is an OS allowing users to easily specialize the safety and isolation strategy of an OS at compilation/deployment time, instead of design time. Depending on the configuration, the same FlexOS code can mimic a microkernel with multiple address-spaces, a single-address-space OS with Intel MPK compartments, or many other OS isolation approaches. A prototype of FlexOS on top of [Unikraft](https://unikraft.org/), a popular library OS framework, is available [on GitHub](https://github.com/project-flexos/unikraft).

### Getting Started

Our [main README](https://github.com/project-flexos/unikraft) provides a step-by-step guide to get started with our prototype. The README of our ASPLOS [artifact evaluation repository](https://github.com/project-flexos/asplos22-ae) is also a great starting point to reproduce our experiments and create new ones.

### Publications

* **Software Compartmentalization Trade-Offs with Hardware Capabilities.**<br/>J. A. Kressel, H. Lefeuvre, P. Olivier.<br/>[**PLOS'23**](https://www.plos-workshop.org/2023/) [[ArXiv](https://arxiv.org/abs/2309.11332)]

* **FlexOS: Towards Flexible OS Isolation.**<br/>H. Lefeuvre, V-A. Bădoiu, A. Jung, S. Teodorescu, S. Rauch, F. Huici, C. Raiciu, P. Olivier.<br/>[**ASPLOS'22**](https://asplos-conference.org/) [[ACM](https://dl.acm.org/doi/10.1145/3503222.3507759)] [[ArXiv](https://arxiv.org/abs/2112.06566)] [[Artifact](https://github.com/project-flexos/asplos22-ae)] [[YouTube](https://www.youtube.com/watch?v=fKkV4yp97Wc)]

* **FlexOS: Easy Specialization of OS Safety Properties.**<br/>H. Lefeuvre.<br/>[**Middleware DW'21**](https://middleware-conf.github.io/2021/call-for-doctoral-symposium/) [[ACM](https://dl.acm.org/doi/abs/10.1145/3491087.3493683)] [[YouTube](https://www.youtube.com/watch?v=jH9sNBuvp0Q)]

* **FlexOS: Making OS Isolation Flexible.**<br/>H. Lefeuvre, V-A. Bădoiu, S. Teodorescu, P. Olivier, T. Mosnoi, R. Deaconescu, F. Huici, C. Raiciu.<br/>[**HotOS'21**](https://sigops.org/s/conferences/hotos/2021/) [[ACM](https://dl.acm.org/doi/abs/10.1145/3458336.3465292)] [[YouTube](https://www.youtube.com/watch?v=0abQORrJLS4)]

### Presentations

* **Rethinking the OS for Isolation Flexibility with FlexOS.**<br/>[**FOSDEM'22**](https://fosdem.org/2022/schedule/event/tee_flexos/) [[Video](http://bofh.nikhef.nl/events/FOSDEM/2022/D.trusted-hardware/tee_flexos.webm)]

* **Retrotting Isolation into Unikraft with FlexOS.**<br/>[**USoC'21**](https://usoc21.unikraft.org/) [[YouTube](https://www.youtube.com/watch?v=XjVzZeq1Pww)]

* **FlexOS : Vers une Isolation Flexible du Noyau.**<br/>[**COMPAS'21**](https://2021.compas-conference.fr/) [[HAL](https://hal.archives-ouvertes.fr/hal-03283641/)]

* Other Presentations (no recording): [**SPMA'22**](https://sites.google.com/view/spma22eurosys/home), [**FGBS'22**](https://www.betriebssysteme.org/aktivitaeten/treffen/2022-hamburg/programm/), [**Huawei Future Device Technology Summit’23**](https://github.com/project-flexos/project-flexos.github.io/raw/main/docs/Huawei_Future_Device_Summit_Helsinki.pdf) [[Slides](/slides/flexos-huawei-helsinki23.pdf)].

### Tutorials

* **FlexOS Session at the [Lyon Unikraft Hackathon](https://unikraft.org/community/hackathons/2022-05-lyon/)** [[Slides]](/slides/flexos-lyon-tutorial.pdf)

### Student Theses

* **VM/EPT: A Virtualisation-based Isolation Backend for FlexOS.**<br/>S. Rauch, 2022, Master Thesis at [KIT](https://os.itec.kit.edu/index.php) [[PDF](https://os.itec.kit.edu/97_3826.php)]
* **Enforcing Control-Flow Integrity in FlexOS**<br/>M. Krajewski, 2023, BSc Thesis at [The University of Manchester](https://www.manchester.ac.uk/) [[PDF](https://github.com/project-flexos/project-flexos.github.io/raw/main/docs/mateusz-krajewski-report.pdf)]
* **Exploring Software Compartmentalisation with Hardware Capabilities**<br/>J. A. Kressel, 2023, MPhil Thesis at [The University of Manchester](https://www.manchester.ac.uk/) [[PDF](https://pure.manchester.ac.uk/ws/portalfiles/portal/280560037/FULL_TEXT.PDF)]
* **Towards Safe, Flexible, and Easy Software Compartmentalisation**<br/>H. Lefeuvre, 2024, PhD Thesis at [The University of Manchester](https://www.manchester.ac.uk/) [[PDF](https://pure.manchester.ac.uk/ws/portalfiles/portal/317271609/FULL_TEXT.PDF)]

### Contact

~~[Hugo Lefeuvre](https://owl.eu.com), The University of Manchester: hugo.lefeuvre *at* manchester.ac.uk~~ (graduated)

[Hugo Lefeuvre](https://owl.eu.com), The University of British Columbia: hugo.lefeuvre *at* ubc.ca

[Pierre Olivier](https://sites.google.com/view/pierreolivier), The University of Manchester: pierre.olivier *at* manchester.ac.uk

* * *

FlexOS is an open-source project resulting from a collaboration between the University of Manchester, Politehnica University of Bucharest, and NEC Laboratories Europe.

FlexOS is supported in part by a studentship from NEC Labs Europe, EU H2020 grants 825377 ([UNICORE](https://unicore-project.eu/)), 871793 ([ACCORDION](https://www.accordion-project.eu/)) and 758815 (CORNET), as well as the UK’s EPSRC grants EP/V012134/1 ([UniFaaS](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/V012134/1)) and EP/V000225/1 ([SCorCH](https://scorch-project.github.io/)). UPB authors are partly supported by VMWare gift funding.

FlexOS logo made by [Kerbreizh Informatique](https://www.kerbreizh-informatique.fr/communication/).
