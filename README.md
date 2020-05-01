# Multi-Tasking-VS-Multi-Threading
**MULTI-TASKING:**
Multitasking is when a CPU is provided to execute multiple tasks at a time. Multitasking involves often CPU switching between the tasks, so that users can collaborate with each program together. Unlike multithreading, In multitasking, the processes share separate memory and resources.

![multi-tasking](https://techdifferences.com/wp-content/uploads/2017/01/Multitasking.jpg)

**MULTI-THREADING:**
Multithreading is a system in which many threads are created from a process through which the computer power is increased. In multithreading, CPU is provided in order to execute many threads from a process at a time, and in multithreading, process creation is performed according to cost.

![Multi-Threading example](https://techdifferences.com/wp-content/uploads/2017/01/Multithreading.jpg)
-
![Multi-Threading example](https://techdifferences.com/wp-content/uploads/2017/01/multithreading-1.jpg)

## **Multi tasking and Multi threading comparisons**

|**BASIC**|Multitasking let CPU to execute multiple tasks at the same time.|Multithreading let CPU to execute multiple threads of a process simultaneously.|
|----|--------------|-----------------|
|**Switching**|In multitasking CPU switches between programs frequently.|In multithreading CPU switches between the threads frequently.|
|**Memory and Resource**|In multitasking system has to allocate separate memory and resources to each program that CPU is executing.|In multithreading system has to allocate memory to a process, multiple threads of that process shares the same memory and resources allocated to the process.|
|**Costly**|It is costly.|It is is less costlier as threads are easy to create then a process.|
|**Responsiveness**|it is less responsive.|Multi threading is more responsive as if one thread isn’t working then another thread would work.|
|**Resource sharing**|It doesn’t allow|It allows resource sharing.|
