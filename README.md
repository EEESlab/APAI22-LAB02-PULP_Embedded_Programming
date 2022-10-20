# APAI-LAB02: Basics of Embedded Programming on PULP

## Summary:
The target device for the lab sessions is the multi-core [PULP](https://github.com/pulp-platform/pulp) platform. 
The PULP Virtual Platform simulator GVSOC, which is included within the [PULP SDK](https://github.com/pulp-platform/pulp-sdk), will be used during the class. 

- **Subject(s)**: hello-world, vector sum, matrix-vector mul, profiling code execution;
- **Programming Language**: C;
- **Lab duration**: 3h 
- **Objective**: Embedded programming & profiling. You will learn basics of embedded programming, the pulp architecture, basic operations (sum & matmul), and how to profile your code execution (MAC, cycles) !

## Assignment
[Assignent + instructions](https://docs.google.com/document/d/1jco30-x0BoXLR27nCj2tT3Mn0cHa9t0PUyEDg4QMqUA/edit?usp=sharing):        
- 2 tasks        
- Time for delivery: 1 week        
- Submission deadline:  **Oct 27th 2022 (23:59:59)** -- delivery on Virtuale

## Quickstart
### How to clone the code on you VM

Open a terminal and go to your working directory.
```
git clone https://github.com/EEESlab/APAI22-LAB02-PULP_Embedded_Programming/
cd EEESlab/APAI22-LAB02-PULP_Embedded_Programming/
```
### How to run the code
to run the code enter in a terminal 
`make clean all run`

DO NOT FORGET: on every new terminal you open, you must do `source /pulp/sourceme.sh` once. Then you can do `make clean all run`
