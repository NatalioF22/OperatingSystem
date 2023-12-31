<h1 align="center">Operating System</h1>

## Steps

### Completed Steps:
- [x] **Step 1:** Implement the `writeSector()` function.
- [x] **Step 2:** Integrate the `dir` command into the shell.
- [x] **Step 3:** Develop the `deleteFile()` function.
- [x] **Step 4:** Create the `writeFile()` function.
- [x] **Step 5:** Add the `copy` command to the shell.
- [x] **Step 6:** Introduce the `create` command to the shell (Note: currently supports only single-line files).

### How to Verify

1. **Compile the Load File:**
   Run the following command to compile `loadFile.c`:
   ```bash
   gcc -o loadFile loadFile.c
   ```

2. **Compile the Operating System:**
   Use the provided script to compile the OS:
   ```bash
   ./compileOS.sh
   ```

3. **Run the Simulator:**
   Start the operating system simulator with:
   ```bash
   java -jar simulator.jar
   ```

4. **Test New Shell Commands:**
   Try out the newly added commands in the shell:
   - List directory contents:
     ```bash
     dir
     ```
   - Copy a file:
     ```bash
     copy [source_file] [destination_file]
     ```
   - Create a new file:
     ```bash
     create [file_name]
     ```

---
