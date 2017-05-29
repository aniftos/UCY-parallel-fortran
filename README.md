UCY-parallel-fortran
====================
Code jams and homework exercises for Parallel Programming in Modern Fortran course at the University of Cyprus

[Homework 1](#homework-1) &middot;
[Homework 2](#homework-2) &middot;

Homework 1
----------
In this assignment, you start writing the world's longest Hello world program with modern Fortran features:
* Blocks
* Deferred-lenth character variables (`character(len=:), allocatable :: foo`)
* Collective subroutine:
```fortran
call co_broadcast(input,source_image=1)
```

### To Do
- [ ] Write the my_message() function
- [ ] Go out for frappe

Homework 2
----------
In this assignment, you will use the co_sum collective subroutine to sum integers across all images.
### To Do
- [ ] Fork this repository by clicking "Fork" in the upper right corner of the browser page (don't click the number next to "Fork")
- [ ] Clone your fork and install the sourcery library:
```bash
  git clone https:github.com/sourceryinstitute/UCY-parallel-fortran-<instert-your-github-username-here>
  cd UCY-parallel-fortran-<instert-your-github-username-here>/src/homework2/library
  make install
```
- [ ] Search for "Assignment" src/homework2/procedural_fireworks/main.f90 and complete the listed steps.
- [ ] Bring your instructor a frappe to receive an A for the day.
----------
