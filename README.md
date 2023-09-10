# SparkLink_1.0_Task_2
Implement the functionality of the CD4017 decade counter using Verilog.

# Question
Design a Verilog module that replicates the operation of the CD4017 integrated circuit, which is a decade counter, The module should count from O to 9 sequentially with clock pulses and produce the corresponding output on IO output pins. Additionally, the functionality of Reset and Clock enable needs to be implemented. Ensure that the Verilog code accurately represents the CD4017*s behaviour (Consider the timing diagram given in the datasheet).

![image](https://github.com/CroosJJSE/SparkLink_1.0_Task_2/assets/141708783/6fa6fbb8-c580-4309-84b4-b2629704bd4a)

# timing diagram
![image](https://github.com/CroosJJSE/SparkLink_1.0_Task_2/assets/141708783/a8fb9554-53b6-4778-84fc-0ecddbf8f66b)


# Observation from its timing diagram
1.Reset is a synchronus active low input.

![image](https://github.com/CroosJJSE/SparkLink_1.0_Task_2/assets/141708783/ab416608-d824-46e9-8b73-5c25f5c04f55)

2.  '1' is shifting in the output.
3.  after 9 starts from 0.
4.  carry out is 1 while out < 4 else it is zero.
5.  when clock en turns on, stay in the output (no increment)
![image](https://github.com/CroosJJSE/SparkLink_1.0_Task_2/assets/141708783/6d33286e-69d5-4041-bed9-da1459540ed8)


check the files



