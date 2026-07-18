# simplecpuarchitecture,howeverythingworks
von newman and  harrward architecture 

### von new man
one control unit , one alu unit, this architecture is used these days, he suggested
there should be a small memomory within the cpu(registers)
he also suggested, there should be a larger memory that holds **instrctuions** and **data** only 1 bus is required



### harward

this is similar to harvard architecture but that suggested that there should be different memories , instructions and data should be held in **seperate memories unit ** . means there should be **two** seperate busses

<img width="1358" height="325" alt="image" src="https://github.com/user-attachments/assets/3310518d-3535-48d2-864b-96e583e12ca4" />


hardware of harvard is more complicated, but it is faster. as there is no bottlenet.

## now a different video.
cpu is a particular type of a processor, there are different type of processors.

Processors generally have 3 main units in it , an **ALU**, a **CU** and **registers** . Control unit has a unit which is called a decoder, which will decode instructions.

There are 2 main components of ALU. one that perfroms mathematical calculations and the other which does boolean operations

## another video (special purpose registers) 
Memory inside the processor. quite small.There are either **general purpose**register or either **special** purpose registers.
General purpose registers are for everyone to use.They are for the programmer to use .
Generally 5 different spr.
-Program counter 
-Memory data register 
-Current Instruction Register 
-Accumulator 
-Memory Address regsiter

Program counter(hold the adress for the next instruction). Memory address register, (holds the address of the data/instruction being  fetched or written to ).MAR stores the address of the memory location that the CPU wants to access. For example, if the CPU wants to read data from memory address 500, it puts 500 into the MAR. The memory controller then uses that address to find the required data.




## another video(busses) 
<img width="536" height="292" alt="image" src="https://github.com/user-attachments/assets/21d4570f-a61d-4822-b5ac-87c0ad1f4e1e" />

bus is a collection of parallel wires through which data is teransmited. we use the term **width** to tell, how many bits can it transfer at a time.

**ADDRESS BUS** is unidirectional , send a memory address from the cpu to the memory.Address of the memory we need to read from.
**Data Bus** sends the actual data or instruction to and from the memory .
**control bus** it carries commands from the cpu to other devices and status messaged back from the devices
it looks something like this 
<img width="265" height="132" alt="image" src="https://github.com/user-attachments/assets/04a821ca-ff2e-4edc-bbb6-240b5bcae7b1" />

So a fetch looks something like this, First of all command bus tells the cpu that i have to read, then the  address is loaded into the bus, then the bus takes that address and give it to the memory and memory loads the data in the data bus. The data could be an instruction aswell .


## Fetch execute cycle (another video) 

**Fetch**, the whole purpose of fetch is to take the instruction from the memory and give it to the cpu.MAR is used for any memory access, including accessing instructions and data.

