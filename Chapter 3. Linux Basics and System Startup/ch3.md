### Learning Objectives

By the end of this chapter, you should be able to:

Identify Linux filesystems.
Identify the differences between partitions and filesystems.
Describe the boot process.
Install Linux on a computer.


---

### The Boot Process

The Linux boot process is the procedure for initializing the system. It consists of everything that happens from when the computer power is first switched on until the user interface is fully operational. 

Having a good understanding of the steps in the boot process may help you with troubleshooting problems, as well as with tailoring the computer's performance to your needs. 

On the other hand, the boot process can be rather technical, and you can start using Linux without knowing all the details. 

| # | Process  |
|---|----------|
| 1 | Power ON |
| 2 | BIOS |
| 3 | Master boot record |
| 4 | Boot loader (e.g. GRUP) |
| 5 | Kernel (Linux OS) |
| 6 | Initial RAM disk - initramsfs image |
| 7 | /sbin/init (parent process) |
| 8 | Command shell using getty |
| 9 | X Windows System (GUI) |

---

### BIOS - The First Step

