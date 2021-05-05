# Notes

## **Zombie Process**

A process which has finished the execution but still has entry in the process table to report to its parent process is known as a zombie process. A child process always first becomes a zombie before being removed from the process table. The parent process reads the exit status of the child process which reaps off the child process entry from the process table.

## Orphan Process

* A process whose parent process no more exists i.e. either finished or terminated without waiting for its child process to terminate is called an orphan process.
* Parent finishes execution and exits while the child process is still executing and is called an orphan process now
* The orphan process is soon adopted by init process, once its parent process dies.

{% hint style="info" %}
Only the shared memory segments are shared between the parent process and the newly forked child process. Copies of the stack and the heap are made for the newly created process
{% endhint %}

## Process Control Block

{% embed url="https://www.studytonight.com/operating-system/operating-system-processes" %}

