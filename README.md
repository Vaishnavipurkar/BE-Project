# BE_PROJECT
This Python script implements Shor's Algorithm for integer factorization using quantum computing. Shor's Algorithm is particularly efficient for factoring large numbers, which is a problem that classical computers find computationally expensive.

Here's a brief explanation of the code for your interviewer:

1. **Header Section:**
   - The initial section contains information about the course, project, and author.

2. **Import Statements:**
   - Importing necessary libraries and modules like `random`, `sys`, `numpy`, and the Qiskit library for quantum computing.

3. **Function Definitions:**
   - Several functions are defined to perform specific tasks, such as `swap_registers`, `qft`, `egcd`, `modinv`, `getAngles`, `ccphase`, `phiADD`, and others. These functions are building blocks for the quantum circuit.

4. **Quantum Circuit for Period Finding:**
   - The `periodFinding` function creates a quantum circuit for finding the period of a function in Fourier space. It uses controlled modular addition and the quantum Fourier transform.

5. **Steps 1 and 2 of Shor's Algorithm:**
   - The `Step1` function randomly selects a number `a` and checks if the greatest common divisor (gcd) of `a` and `N` is not equal to 1. If true, it returns the factors directly. Otherwise, it proceeds to `Step2`.
   - The `Step2` function executes the quantum circuit to find the period (`r`). If the conditions are satisfied, it calculates potential factors using `gcd` and checks further conditions.

6. **Shor's Algorithm Execution:**
   - The `MyShor` function repeatedly performs Steps 1 and 2 until it finds factors.

7. **Main Function:**
   - The `main` function takes a command-line argument for the number to be factored, calls `MyShor`, and prints the factors.

8. **Script Execution:**
   - The `if __name__ == "__main__":` block ensures that the `main` function is called when the script is executed.

The code utilizes quantum gates and circuits to perform operations efficiently, taking advantage of quantum parallelism and interference to factorize large numbers. Shor's Algorithm is a quantum algorithm that outperforms classical algorithms for this specific problem.
* Shor's Algorithm Code
![image](https://github.com/Shailaja87/BE_PROJECT/assets/79163613/ed80d98b-1738-423d-a6e6-a94ee1b078cc)


RESULT!!!!!!!!!!!!!!!!!!!!!!
![image](https://github.com/Shailaja87/BE_PROJECT/assets/79163613/f208988f-07fb-483d-abf4-a849fc947e03)





SYSTEM PROCESSING TIME FOR TERMINAL


![image](https://github.com/Shailaja87/BE_PROJECT/assets/79163613/d6aca275-97f1-41b5-8481-ec401ef6b5ab)
