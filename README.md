Question
The reader-writer problem is a classic synchronization problem in computer 
science, where multiple process execution (or thread) competes for shared 
resources. The reader-writer problem has two types of threads: readers and 
writers. Readers only read the shared resource, while writers read and write to 
it. The problem is to ensure that no writer thread is allowed to enter the critical 
section while a reader thread is accessing the shared resource and vice versa. 
Additionally, multiple readers can read the shared resources, but only single 
writers can access shared resources simultaneously.
