# Master's thesis

## Author

Julian Pszczołowski

## Title

Integrating the Kernel Address Sanitizer into the Mimiker Operating System

## Year

2020

## Abstract

Memory bugs are a source of an evergoing concern for the safety and correctness of programming languages like C and C++. The problem gets worse as the programs get bigger and more complex -- operating system (OS) kernels, on which the thesis concentrates, are a perfect example of that as the Linux kernel has grown to nearly 30 million lines of code in 2020. Here I provide an overview of memory bugs and explain why they are so dangerous in terms of application security. Then I discuss generic ways of finding memory bugs as well as state-of-the-art tools available in various OS kernels. Lastly, the focus is put on the Kernel Address Sanitizer (KASan), a tool for finding buffer overflows and uses of freed memory in the kernel-space, which has been recently integrated into many popular OSes including Linux, macOS and NetBSD. I describe the KASan thoroughly, but most importantly, I present how I've added it to the Mimiker (an open-source OS developed at the University of Wrocław) and show what are the benefits of my work.
