
# English for Computer Science (CSE803001-5-1-24(N03)) <img src='img/nglthu.png' align='right'> 


Materials for the Class of CSE803001-5-1-24(N03)
# Part I. Lecturing about CPU ([Computer] Central Processing Unit)

## 1. Brief Introduction

| CPU            |How CPU can work| In/Out|
| :---------------- | :------: | ----: |
| How a CPU can work | <img src='img/CPU_work.png'>     |  <img src='img/CPU_calculation.png'> |


Step 1. Random access memory (RAM) fetches information from the hard disk of the Computer TO process.  It is a type of computer memory that Stores data and instructions FOR the central processing unit (CPU). RAM is often called a computer's main memory.

+ RAM fetches Information from Hard Disk of Computer to process.
  
+ It stores data and instructions for CPU

+ Information in RAM is Address and Value.
  
+ Value in RAM are Instructions, numbers, and letters by 0s and 1s bits patterns.
  
+ RAM overwrite data each time

+ Data in RAM lost when power is off
  

How a CPU can work
<img src='img/howCPUcanwork.png'>


Step 2. Control Unit Directs operations. It instructs the memory, Logic unit (e.g. ALU), and both output and input devices of the computer on how to respond to the program’s instructions.

   
<img src='img/controlunit.png'>

Step 3. Data moving inside a computer using Bus and stored in each Register

<img src='img/CPU_inside.png'>


| CPU            |On Main| Logic Gates|
| :---------------- | :------: | ----: |
|  | <img src='img/CPU_look.png'>     |  <img src='img/CPU_gates.png'> |


The work of central unit processing: The Loop of Step 1, 2 and 3. 

<img src='img/CPU_gates.png'>

+ Pipelining: Pipelining is the simplest form of concurrency to implement in a processor and
delivers around two to three times speed-up.

+ Clock rate


## 2. ARM architecture vs x86 Architecture

In brief: Their difference is different ISAs(Instruction Set Architectures), using different methods of handling the
same problem. 
The output will be the same but the way in which we handle a mathematical problem will be different. 

This difference in the ISA affects how many instruction cycles will be performed for any given task affecting the power usage, performance, memory usage, heat generation, and more. 

In technical terms: Change the way how [sets of] instructions have been  commanded and executed.

<img src='img/pipelinebranchBehaviourx86.png'>


+ A simple instruction set greatly simplifies the design of the pipeline.
  
+ A high clock rate with single-cycle execution.

+ Poor code Density due to fixed-length instruction set

+ Without caching, more main memory bandwidth being used for instruction fetching, resulting in a higher memory power consumption

+ When the processor incorporates an on-chip cache of a particular size, poor code density results in a smaller
pro-portion of the working set being held in the cache at any time, increasing the cache
miss rate, resulting in an even greater increase in the main memory bandwidth requirement and consequent power consumption.

In 1980 standard semiconductor memories (DRAMs - Dynamic Random Access Memories) could operate at around 3 MHz for random accesses and at 6 MHz for sequential (page mode) accesses. 

The CISC microprocessors of the time could access memory at most at 2 MHz, so memory bandwidth was not being exploited
to the full. 

RISC processors, being rather simpler, could be designed to operate at clock rates that would use all the available memory bandwidth.

+ RISC processors  won the performance battle and should cost less to design, 

+ RISCs generally have poor code density compared with CISCs.

+ RISCs don't execute x86 code.


| ARM vs x86           | ARM | x86|
| :---------------- | :------: | ----: |
| |   <img src='img/ARM.png'>   | <img src='img/x86.png'>  |
| Instruction set|    Using Architecture RISC (Reduced Instruction Set Computers)  | Using Architecture CISC (Complex Instruction Set Computing): process complex instructions simultaneously.   |
|Performance| Simple Command for simple task: Fast execution of single instructions|Complex Commands for many complex/simple tasks: Can do many tasks at once|
| |   System on Chip: increasing times of memory access. Need more RAM |Reduce times of memory access in chip x86. Optimisation of processing speed and RAM savings  |
|Energy efficiency| Future Energy Efficiency|High Power Consumption  |

x86: high raw processing power capabilities
ARM: uses a fraction of the power.

Summary of Comparision between x86 and ARM (Gupta, K. and Sharma, T., 2021)
 <img src='img/c1.png'>
 <img src='img/c2.png'>
 <img src='img/c3.png'>
 <img src='img/c4.png'>
### System on Chip

 A system on a chip  is an integrated circuit that integrates most or all components of a computer or electronic system.
 
 E.g. A system on a chip (SoC) is an integrated circuit that combines a CPU, memory, and other components into a single chip.

A simple processor should require fewer transistors and less silicon area. 
Therefore a whole CPU will fit on a chip at an earlier stage in process technology development, and once the technology has developed beyond the point where either CPU will fit on a chip.
RISC CPU leaves more die area free for performance-enhancing features such as cache memory, memory management functions, floating-point hardware, and so on.

###  The Look 
Some of the  CPUs up to 2025.

M4 Max features a 16-core CPU that’s up to 2.2x faster than the CPU in M1 Max, and up to 2.5x faster than the latest AI PC chip

![M4 Max](https://nglthu.github.io/English_5_1_24/img/M4Max.png)

Sourced: M4 Max by Apple (Apple.com, 2025)

| Intel           |Back | Front|
| :---------------- | :------: | ----: |
| Intel Core 9| <img src='img/intelCore9_back.png'>     |  <img src='img/intelCore9_front.png'> |
| Intel 14th gen| Support for the Intel® 700 series chipsets and backward compatibility with the Intel® 600 series chipsets allow you to access the features you need for any task.  | This architecture features performance cores, Efficient-cores and Intel® Thread Director2. With up to 24 cores (8 Performance-cores and 16 Efficient-cores) and up to 32 threads. The Intel® Core i9 processor P-cores are capable of reaching 6.0 GHz with Intel® Thermal Velocity Boost3 4 to elevate performance.|

Source: Intel® Core™ Desktop Processors by Intel (Intel.com, 2025)

## CPU History


### The Best CPUs for 2025

| The Best CPUs for 2025            | Mainstream, Budget, Fast-end| Game and High End Destop Flatform (HEDt)|
| :---------------- | :------: | ----: |
| In terms of Mainstream, Budget, Fast-end, High-end, Game| <img src='img/list1.png'>     |  <img src='img/list2.png'> |

Sourced: The Best CPUs for 2025 (John Burek & Michael Justin Allen Sexton, 2025)



# Part II. Required Reading Materials: CPU


Changing Trends in Computer Architecture: A Comprehensive Analysis of ARM and x86 Processors
Gupta, K. and Sharma, T., 2021. Changing trends in computer architecture: A comprehensive analysis of arm and x86 processors. International Journal of Scientific Research in Computer Science, Engineering and Information Technology, 7.



# Part III. Listening Materials: CPU


## CPU Brief Introduction

[![Watch the video: How a CPU can work](https://nglthu.github.io/English_5_1_24/img/howCPUcanwork.png)](https://www.youtube.com/watch?v=cNN_tTXABUA&t=544s)

[![Watch the video: How a CPU can work](https://nglthu.github.io/English_5_1_24/img/CPU.png)](https://www.youtube.com/watch?v=vqs_0W-MSB0)


  
# Part III. Writing 
## Writing Technique of POWER

This new strategic technique is called the Power strategy. 
This strategy contains the following steps:

1. "P" which stands for picking ideas. In this stage, students are asked to think of what they are writing and this stage is considered to be pre-writing stage then students write freely and then choose the most important ideas to write about.
   
2. "O" refers to organizing ideas. In this stage, students put their ideas into well-organized order according to the sequence and the importance of the ideas.
   
3. "W" stands for writing and this stage is the stage of actual writing to what had been arranged before.
   
4. "E" means evaluating what had been written according to a writing rubric see appendix (A) and your supporting/evidence/experiment results.
   
5. "R" means re-examining and rereading what had been written to make sure of its quality.



   ![POWER](https://nglthu.github.io/English_5_1_24/img/appendix.png)
## Writing Technique of Tone (Zobel, Justin, 2005)

+ Objective
  
+ Accurate
  
## Writing Technique of Good Style (Zobel, Justin, 2005).

+ Tone (Objective and Accurate)
+ Examples
+ Motivation
+ Balance
+ Voice (Active)
+ Reference and Citation

## Writing Avoidance
+ Straw man
+ Analogies
+ Obfuscation (Ambiguous)
+ The upper hand
  


## Short_paper

<h1>Writing Materials: CPU</h1>

```
Gupta, K. and Sharma, T. (2021) said "The shift in the industry towards ARM processors can change how we write softwares which in turn will affect the whole software development environment."

Please write a short paper to explain and discuss these points of view. 

Reference:  Changing Trends in Computer Architecture(Gupta, K. and Sharma, T., 2021)

```

![ARM vs x86](https://nglthu.github.io/English_5_1_24/img/x66_arm.png)

```
On page 26 of the book "ARM System of Chip Architecture" (The University of Manchester, n.d), it said "one of the drawbacks of RISC is when the processor incorporates an on-chip cache of a particular size, poor code density results in a smaller proportion of the working set being held in the cache at any time, increasing the cache miss rate, resulting in an even greater increase in the main memory bandwidth requirement and consequent power consumption."

Using the writing techniques of POWER, Good Style (Zobel, Justin, 2005) and  "so-called myth" of Linguistic injustice (Englander Karen, 2019, p.30), to research how Apple Chip can reduce power and have power efficiency in their model. 


```

# Vocabulary
 
   Look up the vocabulary and Explanation.
   Example

| Words            | Meaning | Category|
| :---------------- | :------: | ----: |
| CPU |     |  |
| Core-level|     |  |
| Chip-level|     |  |
| Real-time |     |  |
| Logic gates|     |  |
| GPU|     |  |
| quantum-safe system |    |  |
| stochastic [stəˈkastik]|     |  |
| ARM  |     |  |
| x86 |    |  |
| ultra-high frequency pipeline design |     |  |
| self-modifying code |     |  |
| random graph |     |  |
| bipartite [bīˈpärˌtīt] graph |     |  |
| High-Level understanding of the microprocessor core |     |  |
| Branch Prediction Unit |     |  |
| System on Chip|     |  |
| On-chip Integrated Deflate Accelerator|     |  |
| On-chip Integrated Artificial Intelligence Accelerator |     |  |
| zero downtime|     |  |
| redundancy|     |  |
| system-on-chip (SoC /ˌˈɛsoʊsiː/; pl. SoCs /ˌˈɛsoʊsiːz/)|     |  |
| |     |  |
| |     |  |
| |     |  |

# Speaking materials: CPU [Practice]
## Conversation


3.1 Conversation: Discuss the type of CPU  that you bought recently

| Name            | Role | Conversation|
| :---------------- | :------: | ----: |
| Nhat | Listener   |  |
| Lan |  Speaker about your current CPU   |  |
| Duyen |     | Friend to share Conversation |



3.2 Conversation: Now mentioning which ARM and/or x86 can boost you in work, and its advance.

| Name            | Role | Conversation|
| :---------------- | :------: | ----: |
| Bao | Listener    |  |
| Van |     | Speaker Which ARM or x86 can boost your software development.  |

3.3 Conversation: Finally, mentioning about System on Chip CPU.

| Name            | Role | Conversation|
| :---------------- | :------: | ----: |
| Bao | Listener    |  |
| Van |     | Speaker whether System on Chip CPU is CPU inside CPU ?.  |

# Comprehensive / Advanced Exercises

# Grammar Lesson

Prefix in English (Tiền tố trong tiếng Anh)

| Prefix/Meaning            |Prefix/Meaning | Prefix/Meaning|
| :---------------- | :------: | ----: |
| <img src='img/1_anti.png'> | <img src='img/2_auto.png'>     |  <img src='img/3_co.png'> |
| <img src='img/4_dis.png'> | <img src='img/5_hyper.png'>     |  <img src='img/6_inter.png'> |
| <img src='img/7_non.png'> | <img src='img/8_post.png'>     |  <img src='img/9_trans.png'> |
| <img src='img/10_un.png'> | <img src='img/11_pre.png'>     |  <img src='img/12_ex.png'> |
| <img src='img/13_mis.png'> | <img src='img/14_over.png'>     |  <img src='img/15_under.png'> |

| more... |  


# Reference

1. John Burek & Michael Justin Allen Sexton, 2024.  "The Best CPUs for 2025". Retrieved from https://www.pcmag.com/picks/the-best-cpus
2. Apple.com, 2025. "M4 Max". Retrieved from https://www.apple.com/newsroom/2024/10/apple-introduces-m4-pro-and-m4-max/
3. Intel.com, 2025. "Intel® Core™ Desktop Processors" Retrieved from https://www.intel.com/content/www/us/en/products/docs/processors/core/core-14th-gen-desktop-brief.html
4. Changing Trends in Computer Architecture: A Comprehensive Analysis of ARM and x86 Processors
Gupta, K. and Sharma, T., 2021. Changing trends in computer architecture: A comprehensive analysis of arm and x86 processors. International Journal of Scientific Research in Computer Science, Engineering and Information Technology, 7.
5. Karen, Englander, 2019. English for research publication purposes : critical plurilingual pedagogies /, Routledge
6. Zobel, Justin, 2005. Writing for computer science, Springer.
7. The University of Manchester, n.d., "ARM system on Chip". Retrieved from http://www.cs.man.ac.uk/amulet/publications/books/ARMsysArch

# Hanoi, January 2025 <img src='img/logo.png' align='right'> 
