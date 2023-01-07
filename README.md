# BIOS GUIDE FOR AMD RYZEN

List of relevant BIOS settings aiming for real-time response on AMD Ryzen systems.

## Introduction 

- Every setting is detailed with my personnal recommendation for each settings based on my researchs, commun sense and testing.																
- Those settings must not be applied simultaneously, test the impact of each settings on your performances and temps if you want to get the most out of this guide 			   - Feel free to make your own researchs																	
- Most options are likely to be hidden in your BIOS, there are several ways to access them but it's not the purpose of this guide		

 ## Processor core settings 
 
 **SMT Control**
 
 - Auto 
 - Enable
 - **Disable***
 
SMT Control (Simultaneous Multithreading or Hyperthreading) allows the CPU to execute multiple threads concurrently, each physical core appears as two logical cores to the operating system, and each logical core can execute its own thread. Using multiple execution threads per core requires resource sharing and is a possible source of inconsistent system response.

Some demanding games, optimized for multi-core usage will do better with SMT enabled but most competitve games don't benefit from SMT as it comes with a latency penalty so disable it if you have 6+ cores. Note that disabling SMT will give you lower power consumption and temperatures which gives you more headroom to overclock and will allow your CPU to achieve higher boost clocks.
