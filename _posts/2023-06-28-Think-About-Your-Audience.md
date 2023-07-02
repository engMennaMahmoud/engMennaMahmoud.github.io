Yayyy five weeks as an Outreachy Intern already 🎉. This week marks my fifth week as an Outreahcy intern under Linux Kernel working on improving Linux Security via Architectural Capabilities (Morello-Linux). So you might be wondering what is Morello-Linux.


##What is Morello-Linux?

Morello is a research program with the potential to radically change the way we design and program processors in the future to improve built-in security. Funded by the UK government’s Industrial Strategy Challenge Fund (ISCF) Digital Security by Design (DSbD) program and led by Arm, Morello has a transformative goal to radically update the security foundations of the digital computing infrastructure that underpins the entire global economy. The main anticipated output of DSbD is a technology platform prototype, designed and produced by Arm: The Morello evaluation board.

Morello focuses on new ways of designing CPU architecture that can make processors more robust and deter certain key security breaches. As part of an additional 5-year research program funded by UK Research and Innovation (UKRI), Morello will be used to produce and test a prototype technology that, if successful, could be implemented in future hardware.

Arm is collaborating with the University of Cambridge and SRI International on its Capability Hardware Enhanced RISC Instructions (CHERI) architecture. Arm has developed a prototype architecture that adapts the hardware concepts of CHERI.

This new approach to cybersecurity requires extensive exploration work and involves a significant change in how the architecture of the hardware is designed and how software running on devices is programmed to take advantage of the new features.

Using this new technology, Arm has designed a prototype system-on-chip (SoC) and a development board, called the Morello board. This will enable industry and academic partners to test the new prototype architecture in real-world use cases.

##What is my role during the internship?

Improving Linux Security via Architectural Capabilities (Morello-Linux)

Capabilities are tokens of authority that are unforgeable and delegable. The Morello architecture extends the Armv8.2-A profile with features that implement the CHERI capabilities and protection model. It implements 129-bit CHERI capabilities with compressed bounds, which provide a compromise between memory consumption and bounds precision. The Morello architecture also inherits the rules for architectural features and extensions from Armv8.2-A. There is ongoing work on Linux kernel support with fine-grained memory protection and scalable compartmentalization features. Hence, Morello hardware features introduce new opportunities for designing kernel abstractions to achieve intra-kernel privilege separation and sandboxing mechanisms. 

My role is to contribute to improving the security of Linux kernel subsystems with CHERI capabilities. Contribute to different sub-projects, including: 
(1) enabling and testing existing security features on Morelo Linux.
(2) introducing new abstractions for compartmentalization and sandboxing into the kernel. 
(3) hardening the kernel's security-sensitive subsystems.
(4) analyzing the security of the current state of the Morello-Linux. 

##Conclusion

By understanding this project, you will be better equipped to navigate the technical challenges of working on the Morello and CHERI and contribute to their development.
