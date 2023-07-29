# Level 3 - Directed Test (Given Design)

### Error screenshot

<img src="imgs/error.png" width="350">

### Observations

1. **Missing Lines**: The diff output shows that four lines are missing in the "spike.dump" log when compared to the "rtl.dump" log. These lines have addresses "0x80000054," "0x80000058," "0x8000005c," and "0x80000060."

2. **Differences in Values**: For each missing line, the values of the instruction, registers (x and x30), and immediate values are different in the "spike.dump" log compared to the "rtl.dump" log. These differences indicate that the program's behavior and register values deviated from the expected behavior in the "spike" simulation.

3. **Address and Instruction Information**: The addresses (e.g., "0x80000054") and instructions (e.g., "0x01efa023") provide information about the program counter and the instructions being executed at those points in the simulation.

4. **Register Values**: The values of the registers (e.g., "x30," "x") represent the register states after executing the corresponding instructions