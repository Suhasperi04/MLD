
# MLD (Memory Leak Detection Tool)

This project implements a C library for detecting memory leaks in C applications.

## How to Run the Application

### Step 1: Compile the MLD Library
```bash
gcc -g -c mld.c -o mld.o
```

### Step 2: Compile Your Application
Replace `"application_name.c"` with your application's source file:
```bash
gcc -g -c "application_name.c" -o "application_name.o"
```

### Step 3: Create an Executable for Your Application
Combine the MLD library with your application object file:
```bash
gcc -g -o "application" mld.o "application_name.o"
```

### Step 4: Run Your Application
```bash
./application
```



## Notes
Ensure you have a C compiler like GCC installed before running the commands. This tool is designed to integrate easily with your C projects.

---

