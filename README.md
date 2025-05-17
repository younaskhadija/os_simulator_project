#  Operating System Simulator 

This project is a simulation of an Operating System created as part of the  final term project. 
It demonstrates core OS concepts such as "process scheduling", "multitasking", "memory management", and "user kernel modes".



##  Features

- Custom OS name with loading screen
- User-defined RAM, Hard Drive, and CPU core setup
- Basic built-in applications:
  - Notepad (auto-save)
  - Calculator
  - File operations (Create, Move, Copy, Delete)
  - File info checker
  - Time display
  - Mini-games (e.g., Minesweeper)
- Multi-process execution with:
  - Separate terminal windows for each process
  - Resource checks before allocation
  - Task-specific memory usage
- Manual interrupt support (Close/Minimize tasks)
- Ready queue-based process scheduling
- Multilevel queue scheduling with different algorithms
- User Mode and Kernel Mode
- Graceful shutdown with a goodbye message

##  Technologies Used

- Bash scripting
- Linux terminal
- Sleep, `exec` commands, semaphores, and condition variables

