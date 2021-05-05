# APIs and System Calls

### WAIT

**Syntax: `wait(int *status)`**

**Returns**

* **pid of child process**: If `wait` returns because the status of a child is reported
* -**1:** . If an error occurs

**Arguments**

The status argument of `wait` is a pointer to an integer variable. If it is not `NULL`, this function stores the return status of the child in this location. The child returns its status by calling `exit, _exit` or `return` from main.



## EXEC

{% embed url="https://man7.org/linux/man-pages/man3/exec.3.html" %}

All `exec` functions return **–1** if unsuccessful. In case of success these functions never return to the calling function.



## \*\*\*\*





\*\*\*\*

\`\`

\`\`

