# Part 1 of the PintOS project for CSE421: Operating Systems

PintOS is a small operating system, written in C, first developed at Stanford for usage in OS coursework. PintOS is deliberately missing several features, implemented by the student in non-contiguous projects. In CSE421, these projects were done in two-student teams. In my particular case, my teammate and I pair-programmed together remotely over Zoom due to Covid restrictions.

Project 1 implements the following:
  -Alarm Clock (current timer uses busy-waiting and simply sleeps, not multi-threaded)
  -Priority Scheduling (maintain ready and waiting theads lists, use semaphores and locks, select next thread based on priority among the ready list)
  -Priority Donation (prevent priority inversion by implementing donation of priority between threads waiting on the same lock)
  -Multivel Feedback Queue Scheduler (4.4BSD Scheduler, activated with the "-mltq" kernel option)

