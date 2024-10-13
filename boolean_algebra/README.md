# Boolean Algebra

Boolean algebra is used to do arithmetic with bits of values True (1) or False (0).
There are three basic operations: 'and', 'or' and 'not'.

### AND Gate
The AND gate will only output the value 1 (logic high) if **ALL** the inpputs are at 1. Otherwise, the output is going to be 0 (logic low).

Here is an example of AND gate circuits with inputs 1 and 0 to test different cases:

![image](https://github.com/user-attachments/assets/51449cfe-5bc0-4a58-bcdc-93c19e55b1a5)

In this and gate ciruit, you can see the output values based on the input values. There are three cases shown:

1. if both of the inputs are 0, then the output will be 0 (the circuit is off).
2. if one of the inputs is 1 and the other input is 0, then the circuit will still not turn on, because both of the inputs have to be 1 in order for the circuit to turn on.
3. if both of the inputes are 1, then the circuit will turn on.

#### AND Gate Truth Table

According to google, the most striaghtforward definition of a truth table is "a diagram of the outputs from all possible combinations of inputs". If there are **_n_** number of inputs, then the corresponding truth table will have **_2^n_** rows.

Here is the truth table for an AND gate.

![image](https://github.com/user-attachments/assets/a29ead3e-79d2-45ed-9648-dea0f938dbf3)

### OR Gate
The OR gate will output 0 if and only if **ALL** of the inputs are 0, otherwise the output will be 1. 

Here is an example of an OR gate with outputs 0 and 1:

![image](https://github.com/user-attachments/assets/19bc51f5-8144-4cb6-81d9-e567b4af2bc3)

1. if both of the inputs are 0, the output is 0 (the circuit is off).
2. if one of the inputs is 1 and the other input is 0, **_unlike the AND gate_**, the circuit will still turn on.
3. if both of the inputs are 1, then the circuit will still turn on.

Here is the truth table for an OR gate:

![image](https://github.com/user-attachments/assets/c586f325-2c2d-4d83-afb1-438f0b144f6a)

// note to self: finish not, reinstate wiki articles to add more
