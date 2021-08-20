# Requirements
## Introduction
This product is a powerful tool which helps in designing and implementing electronic circuits. It has various components as features like Filters, Amplifiers, Logic gates, etc which are related to electronics. It takes input from the user through Command line and gives the output through the same.

## Research
Many websites were available which would implement only one of the features of our product alone. For example, there are pages or sites for calculating fiters' RC values or implementing logic gates. But we could not find anything integrated to this extent.

## State of Art
### Ageing - Time
 * Usually these type of calculations were done manually, handwritten. Even in colleges, we still practice all these manually. This project is an idea for automating all the calculations and design which will reduce the time consumed and errors committed.
### Ageing - Cost
 * The cost parameter for this project was none. All the softwares and features were freely available on the internet.
 
## 4W&#39;s and 1&#39;H

### Who:
 * Electical,Electronics,control systems,instrumentation engineers and students;people who need to design or use circuits related to electronics.

### What:
 * This project gives out the parameters or the values required to design or implelment the type of electronic component according to the user inputs. 

### When:
 * This project can be used whenever there is a need to implement or design electronic components.

### Where:
 * This project can be used colleges/universities,labs or even for individual uses.

### How:
 * The user can follow the (add link for implementation). Then the user enters their requirements and the output will be displayed.

## SWOT Analysis
![SWOT ANALYSIS](https://github.com/TanmayBhilkar/SDLC_AUG_TEAM_7/blob/main/1_Requirements/SWOT.jpg)


## Features
| Sl. No. | Component | Description |
| ------- | ----------- | ------------- |
| 01 | Design of filters | Taking input like frequency and gain from the user and returning the circuit parameters for design | 
| 02 | OP-AMP |Just to check Wheteher the given parameter forms the given Amplifier or Not.|
| 03 | Logic Gates | To implement different Logic gates like AND, OR, NOT, NAND, NOR, XOR, and XNOR Gates |  
| 04 | 3 variable K-Map | To produce simplified expression for 3 variable minterms input |
| 05 |Multiplexer & Demultiplexer |To implement in different Combinational logic design |
## High Level Requirements: 
| ID | Description | Status |
| ----- | ----------- | ------- |
| HR01 | Application should implement various electronic component design | TBD |
| HR02 | Application should take input from the user | TBD |
| HR03 | Application should print output to the user | TBD |
| HR04 | Application should work on both Linux and Windows | TBD |
| HR05 | Application should follow clean code rules | TBD |

##  Low level Requirements:
 
| ID | Description | HR ID | Status |
| ------ | --------- | ------ | ----- |
| LR01 | Application should be able to run on the CLI of the user | HR02,HR03 | TBD |
| LR02 | Application should use makefile option for different commands | HR04 | TBD |
| LR03 | Application should comply with different checks like valgrind,cppcheck,build etc. | HR05 | TBD |
| LR04 | Application to be used with a GUI to provide inputs and print outputs | HR02,HR03 | Future |
| LR11 | Application should consider all the different types of active filters available to design | HR01 | TBD |
| LR21 | Implementation of different Logic Gates | HR01 | TBD |
| LR22 | Implement test cases to check the implementation of Logic Gates | HR05 | TBD |
| LR31 | Application shall take the number of minterms (max. 8) and what the minterms are as input | HR02 | TBD |
| LR32 | Application shall print the simplified 3 variable expression as output | HR03 | TBD |
| LR41 | Application shall print the output of the logic design in simplified form | HR03 | TBD |
| LR42 | Application shall minimes the IC pakage count | HR02 | TBD |
