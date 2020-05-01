# Multitasking

The word multitasking means running or operating concurrently in two more programs. Multitasking is done when the CPU is used to perform several tasks at a time while we run a program with several threads and all threads performing tasks independently in a single program are known as multitasking. Multitasking includes regularly CPU switching between the duties, so that users can cooperate with every application together. Unlike multi-threading, In multitasking, the strategies proportion separate memory and resources. As multitasking includes CPU switching between the tasks rapidly, So the little time is needed so that it will switch from the only consumer to next. In programming world, there are two primary ways to improve the throughput of a program, by the usage of multi-threading and by the use of multitasking. Both take benefit of parallelism to efficaciously make use of immense energy of CPU and improve the throughput of your program. Actually, multi-threading is nothing however a thread primarily based multi-tasking.Both are used to parallelize things to be able to take full gain of steeply-priced hardware and CPU. Multitasking is an capability of a laptop to execute a couple of applications at the identical time at the same time as multi-threading is the potential of a process to execute multiple threads at the identical time. Sometimes multitasking is beneficial and different time multi-threading. In computing, multitasking is a method with the aid of which a couple of tasks, also known as processes, share commonplace processing resources together with a CPU. With a multitasking OS, such as Windows XP, you may simultaneously run a couple of packages. Multitasking refers to the potential of the OS to quick transfer between every computing mission to present the influence the different packages are executing multiple actions concurrently.


As CPU clock speeds have increased step by step over time, not most effective do programs run faster, but O's can switch between packages extra fast. This provides higher overall performance. Many actions can happen straight away on a PC, and person applications can run faster.

#### Types of Multitasking
Two kinds of multitasking:
1. Process based Multitasking
2. Thread based Multitasking

##### 1.Process based Multitasking:
process based multi-tasking is about allowing several programs to execute concurrently e.g java Compiler and Text editors processes are heavy weight tasks that required their own address space and inter-process communication is expensive and limited further context switching from one process to another process is expensive and limited.
##### 2.Thread based Multitasking:
Thread is a lightweight sub process, which are independent to each other.
There are two types of Thread
1. Single Thread
2. Multiple Thread

#### 1.Single Thread:
A task or process that is made up of only one thread. A program that supports single thread is referred as single threaded application.
![](https://image.slidesharecdn.com/chap221-141222203658-conversion-gate02/95/chap2-2-1-5-638.jpg?cb=1419302278)
>note this is copyright image use for educational purpose only

#### 2. Multiple Thread:
A task or process that is made of more than one thread is multiple threads. A program that supports more than one thread is multi-threaded application.
![](https://i.stack.imgur.com/8EoLM.png)
>note this is copyright image use for educational purpose only


### Single Core
Those computer which having a single CPU core, only one task runs at any point in time, meaning that the CPU is actively executing instructions for that task. Multitasking solves this problem by scheduling which task may run at any given time and when another waiting task gets a turn.
![](https://images.slideplayer.com/24/7483714/slides/slide_3.jpg)
>note this is copyright image use for educational purpose only


# Multicore
When running on a multicore system, multitasking OS's can truly execute multiple tasks concurrently. The multiple computing engines work independently on different tasks.
For example, on a dual-core system, four applications - such as word processing, e-mail, Web browsing, and antivirus software - can each access a separate processor core at the same time. You can multitask by checking e-mail and typing a letter simultaneously, thus improving overall performance for applications.

![](https://www.reviversoft.com/blog/wp-content/uploads/2011/02/multi-core_cpu.png)

The OS executes multiple applications more efficiently by splitting the different applications, or processes, between the separate CPU cores. The computer can spread the work - each core is managing and switching through half as many applications as before - and deliver better overall throughput and performance. In effect, the applications are running in parallel.












