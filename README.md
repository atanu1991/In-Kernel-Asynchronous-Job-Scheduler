# In-Kernel-Asynchronous-Job-Scheduler

This assignment is about implmentation of a system call for asynchronous
and concurrent processing of files at the kernel level, kernel locking,
efficiency, and callbacks. A system call is written in this assignment which can
be loaded into the kernel. The types of functions perfomed by this sytem call
include encryption/decryption, checksum, compress/decompression and
concatenation of files. Some or most of the operations mentioned above take
a lot of time to complete. The system call is designed in such a way, that the
user need not wait for processing to complete as the system call just enques
the task onto the queue and returns. The user is later notified via callback
mechanism about the status of the task.

Source code available on request
