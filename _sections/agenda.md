---
location: agenda
head:
  title: SDSC Summer Institute Preliminary Agenda
---

* **Lesson material repository**: <https://github.com/sdsc/sdsc-summer-institute-2018>


**Monday, August 6 - 10, 2018
>Monday: 8:00am - 5:00pm
>Tuesday - Thursday: 8:30am - 5:00pm
>Friday: 8:30am - Noon

**Social Activities**
* Monday evening reception
* Thursday evening dinner

**General Sessions**
* Logging into Comet
* Launching, monitoring and cancelling jobs using Slurm
* Understanding the Comet file systems
* Virtual clusters: introduction and where to go if you need VCs
* Science Gateways: what they are, which ones exist and where to go if you need to build your own
* Singularity: introduction to containers, what they are, where to find them, how to run on Comet
* How to understand the performance of your software
* Git: introductory topics for folks new to Git, advanced topics for experienced Git users
* Tour SDSC Data Center

**Breakout Sessions**
>
**GPU Computing and Programming**
>This session provides an introduction to massively parallel computing with graphics processing units (GPUs). The use of GPUs is becoming increasingly popular across all scientific domains since GPUs can significantly accelerate time to solution for many computational tasks. Participants will be introduced to essential background of the GPU chip architecture and will learn how to program GPUs via the use of libraries, OpenACC compiler directives, and CUDA programming. The session will incorporate hands-on exercises for participants to acquire the skills to use and develop GPU aware applications. 
>
**Machine Learning Overview**
>SDSC Machine learning is an interdisciplinary field focused on the study and construction of computer systems that can learn from data without being explicitly programmed. Machine learning techniques can be used to uncover patterns in your data and gain insights into your problem. This session provides an overview of the fundamental machine learning algorithms and techniques used to explore, analyze, and leverage data to construct data-driven solutions applicable to any domain. Topics covered include the machine learning process, data exploration, data preparation, classification, and cluster analysis. Concepts and algorithms will be introduced, followed by exercises to allow hands-on experience using R and RStudio. 
>
**Scalable Machine Learning**
>Machine learning is an integral part of knowledge discovery in a wide variety of applications. From scientific domains to social media analytics, the data that needs to be analyzed has become massive and complex. This session provides an introduction to approaches that can be used to perform machine learning at scale. Tools and procedures for executing machine learning techniques on HPC will be presented. Spark will also be covered. In particular, we will use Spark's machine learning library, MLlib, to demonstrate how distributed computing can be used to provide scalable machine learning. Please note: Knowledge of fundamental machine learning algorithms and techniques is required. (See description for Machine Learning Overview.) 
>
**Parallel Computing using MPI & Open MP**
>This session is targeted at attendees who are looking for a hands-on introduction to parallel computing using MPI and Open MP programming. The session will start with an introduction and basic information for getting started with MPI. An overview of the common MPI routines that are useful for beginner MPI programmers, including MPI environment set up, point-to-point communications, and collective communications routines will be provided. Simple examples illustrating distributed memory computing, with the use of common MPI routines, will be covered. The OpenMP section will provide an overview of constructs and directives for specifying parallel regions, work sharing, synchronization and data scope. Simple examples will be used to illustrate the use of OpenMP shared-memory programming model, and important run time environment variables Hands on exercises for both MPI and OpenMP will be done in C and FORTRAN. 
>
**Performance Optimization** 
>This session is targeted at attendees who both do their own code development and need their calculations to finish as quickly as possible. We'll cover the effective use of cache, loop-level optimizations, force reductions, optimizing compilers and their limitations, short-circuiting, time-space tradeoffs and more. Exercises will be done mostly in C, but emphasis will be on general techniques that can be applied in any language. 
>
**Python for HPC**
>In this session we will introduce four key technologies in the Python ecosystem that provide significant benefits for scientific applications run in supercomputing environments. Previous Python experience is recommended but not required. (1) The Jupyter Notebook allows users to execute code on a single compute node through a local browser for interactive data exploration and visualization. The Jupyter Notebook supports live Python code, explanatory text, LaTeX equations and plots in the same document. (2) IPython Parallel provides a simple, flexible and scalable way of running thousands of Python serial jobs by spawning IPython kernels (namely engines) on any HPC batch scheduler.  (3) Numba makes it possible to run pure Python code on GPUs simply by decorating functions with the data types of the input and output arguments. Pure Python prototype code can be gradually optimized by pushing the most computationally intensive functions to the GPU without the need to implement code in CUDA or OpenCL. (4) Dask is a flexible parallel computing library that allows to build a distributed computation using simple operators and then let the library automatically handle distributing data, executing the computation hierarchically and gather back the results. 
>
**Scientific visualization with Visit and data sharing**
>Visualization is largely understood and used as an excellent communication tool by researchers. This narrow view often keeps scientists from fully using and developing their visualization skillset. This tutorial will provide a "from the ground up" understanding of visualization and its utility in error diagnostic and exploration of data for scientific insight. When used effectively visualization can provide a complementary and effective toolset for data analysis, which is one of the most challenging problems in computational domains. In this tutorial we plan to bridge these gaps by providing end users with fundamental visualization concepts, execution tools, customization and usage examples. Finally, a short introduction to SeedMe.org will be provided where users will learn how to share their visualization results ubiquitously. 





