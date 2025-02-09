# Operating System (OS) Interview Questions with Answers

## 1. What is an Operating System?
An OS is system software that manages hardware and software resources and provides services for computer programs (e.g., Windows, Linux, macOS).

## 2. What are the types of Operating Systems?
- **Batch OS**
- **Time-sharing OS**
- **Distributed OS**
- **Network OS**
- **Real-Time OS**
- **Mobile OS**

## 3. What are system calls in OS?
System calls provide an interface between user programs and the OS (e.g., `fork()`, `exec()`, `open()`, `read()`, `write()`).

## 4. What is a kernel in an OS?
The **kernel** is the core part of the OS that manages system resources and hardware communication.

## 5. What are the types of kernels?
- **Monolithic Kernel** (e.g., Linux)
- **Microkernel** (e.g., Minix)
- **Hybrid Kernel** (e.g., Windows, macOS)

## 6. What is the difference between a process and a thread?
- **Process**: A running instance of a program, has its own memory space.
- **Thread**: A lightweight process that shares memory with other threads within the same process.

## 7. What are the different states of a process?
- **New** → **Ready** → **Running** → **Waiting** → **Terminated**

## 8. What is process scheduling?
It is the method the OS uses to decide which process runs next on the CPU.

## 9. What are scheduling algorithms in OS?
- **FCFS (First Come First Serve)**
- **SJF (Shortest Job First)**
- **Round Robin (RR)**
- **Priority Scheduling**
- **Multilevel Queue Scheduling**

## 10. What is a deadlock in OS?
A situation where two or more processes are waiting for resources indefinitely, causing a halt in execution.

## 11. What are the necessary conditions for deadlock?
1. **Mutual Exclusion**
2. **Hold and Wait**
3. **No Preemption**
4. **Circular Wait**

## 12. How to prevent a deadlock?
- **Avoid circular wait** by ordering resource allocation.
- **Use timeout-based resource allocation.**

## 13. What is paging in OS?
A memory management technique that divides the process into fixed-size pages and loads them into frames in physical memory.

## 14. What is segmentation?
Memory management technique that divides a process into variable-sized segments based on logical divisions.

## 15. What is virtual memory?
A memory management feature that allows the execution of processes larger than physical memory by using **swap space** on the disk.

## 16. What is thrashing in OS?
Excessive page swapping between RAM and disk, reducing system performance.

## 17. What is a page fault?
Occurs when a required page is not in memory, causing the OS to load it from disk.

## 18. What is demand paging?
A lazy-loading technique where pages are brought into memory only when needed.

## 19. What is a file system in OS?
The method used by the OS to organize and store files on a storage device.

## 20. What are different file allocation methods?
- **Contiguous Allocation**
- **Linked Allocation**
- **Indexed Allocation**

## 21. What are file permissions in OS?
Rules that define who can **read**, **write**, and **execute** files in a system.

## 22. What is inter-process communication (IPC)?
Mechanisms that allow processes to exchange data and signals.

## 23. What are different IPC mechanisms?
- **Pipes**
- **Message Queues**
- **Shared Memory**
- **Semaphores**

## 24. What is a semaphore in OS?
A synchronization primitive used to manage concurrent access to shared resources.

## 25. What is the difference between counting and binary semaphores?
- **Binary Semaphore**: Only takes values 0 or 1 (acts like a lock).
- **Counting Semaphore**: Takes multiple values to manage resource count.

## 26. What is mutual exclusion?
Ensuring that only one process accesses a shared resource at a time.

## 27. What is the difference between a hard and soft real-time system?
- **Hard Real-Time**: Strict deadlines (e.g., pacemakers, aircraft systems).
- **Soft Real-Time**: Flexible deadlines (e.g., video streaming, gaming).

## 28. What is spooling in OS?
A buffering process that allows slow devices (like printers) to keep up with fast data sources.

## 29. What is a context switch?
The process of saving and restoring a CPU’s state when switching between processes.

## 30. What is process synchronization?
Coordination of processes to prevent race conditions when accessing shared resources.

## 31. What is a race condition?
Occurs when multiple processes access and manipulate shared data simultaneously, leading to unpredictable results.

## 32. What is an inode in a file system?
A data structure that stores file metadata (size, owner, permissions, location).

## 33. What is fragmentation in memory management?
- **Internal Fragmentation**: Wasted memory inside allocated space.
- **External Fragmentation**: Wasted memory outside allocated space.

## 34. What is swapping in OS?
Temporarily moving inactive processes from RAM to disk to free up memory.

## 35. What is a bootloader?
A small program that initializes the OS when the system starts.

## 36. What is the difference between logical and physical addresses?
- **Logical Address**: Generated by the CPU.
- **Physical Address**: Actual location in memory.

## 37. What is a zombie process?
A process that has completed execution but still has an entry in the process table.

## 38. What is an orphan process?
A child process whose parent has terminated.

## 39. What is a shell in OS?
A command-line interface that allows users to interact with the OS.

## 40. What is a system daemon?
A background process that runs continuously (e.g., `cron`, `sshd`).

## 41. What is CPU scheduling?
Deciding which process runs next to maximize CPU utilization.

## 42. What is aging in scheduling?
A technique to prevent **starvation** by gradually increasing a process's priority.

## 43. What is disk scheduling?
Algorithms used to determine the order of disk I/O requests (e.g., FCFS, SSTF, SCAN, C-SCAN, LOOK).

## 44. What is a journaling file system?
A file system that keeps a log of changes before applying them to prevent corruption (e.g., ext3, NTFS).

## 45. What is the difference between a monolithic and microkernel?
- **Monolithic Kernel**: All OS services run in kernel mode.
- **Microkernel**: Only essential services run in kernel mode, others run in user mode.

## 46. What is a hypervisor?
Software that enables virtualization by running multiple OS instances (e.g., VMware, KVM, Hyper-V).

## 47. What is load balancing in OS?
Distributing workload evenly across processors to improve efficiency.

## 48. What is NUMA in multiprocessing?
Non-Uniform Memory Access, optimizing memory access in multi-core architectures.

## 49. What is DMA (Direct Memory Access)?
Allows hardware devices to access system memory without involving the CPU.

## 50. What is the difference between multiprogramming and multitasking?
- **Multiprogramming**: Running multiple programs in memory.
- **Multitasking**: Running multiple tasks by switching CPU time rapidly.

---
This document covers 50 key OS interview questions and answers. 🚀

