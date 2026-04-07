# SIMULATION-OF-MEAN-AND-VARIANCE-USING-SCILAB-T1-C12-EVEN
AIM:

To write a program for mean, variance and cross correlation in SCILAB and verify the output.

#EQUIPMENTS NEEDED:

.Computer with i3 Processor

.SCI LAB

ALGORITHM:

Define the Function: Specify the function you want to simulate. For example, f(x)=sin⁡(x)f(x)=sin(x) or any other function.
Generate Sample Points: Decide on the range and the number of sample points. Generate these sample points within the desired range.
Evaluate the Function: Compute the function values at each of these sample points.
Compute Mean, Variance and Cross Correlation: Use Scilab's functions to calculate the mean and variance of the computed function values.
Display Results: Output the computed mean variance and Cross Correlation

PROCEDURE:

1.Refer Algorithms and write code for the experiment.

2.Open SCILAB in System

3.Type your code in New Editor

4.Save the file

5.Execute the code If any Error, correct it in code and execute again

6.Verify the generated results

PROGRAM:
```
clc;
clear;

// Given data
X = [12 13 14 15 16];

// Number of elements
N = length(X);

// Calculate Mean
mean_value = sum(X) / N;

// Calculate Variance
variance_value = sum((X - mean_value).^2) / N;

// Display Results
disp("Mean = ");
disp(mean_value);

disp("Variance = ");
disp(variance_value);
```

OUTPUT GRAPH:

<img width="349" height="211" alt="Screenshot 2026-04-07 121848" src="https://github.com/user-attachments/assets/d89e2557-64a7-4ac7-8d00-02674383678d" />

CALCULATION :

![WhatsApp Image 2026-04-07 at 12 20 20 PM](https://github.com/user-attachments/assets/9985e2be-3d09-4544-86cc-573fe95da723)
![WhatsApp Image 2026-04-07 at 12 20 20 PM (1)](https://github.com/user-attachments/assets/8926e5d9-2564-4dbe-afc9-69a09510aa35)



RESULT:

![WhatsApp Image 2026-04-07 at 12 22 20 PM](https://github.com/user-attachments/assets/4510a33d-eeb0-495b-b9df-9dfc797846ed)
