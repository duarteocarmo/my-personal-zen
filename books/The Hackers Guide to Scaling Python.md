# The Hackers Guide to Scaling Python
- The cats are a bit mixed up. The standard output is shared across all the processes printing cats, and they are stepping on each other’s toes. The way to fix that is to lock the standard output until the cat is fully printed on the screen. This is easily done by using a multiprocessing.Lock.
