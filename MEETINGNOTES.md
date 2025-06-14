# Meeting Notes
## 05/XX
- 4900 - 4 credits
- Get work done as early as possible
- 12 hours a week for senior project
- Projects have gone bad often due to saving up work
- Technical activities
- Brain computer interface
- Aquire signal of neurons
- Mesaure analog signals from brain
- Digitize and send
- Blackrock neruotech
- Over ethernet to computer that will save data and visualize
- Udp protocol is used to send
- Fpgas recieiving the data and saving into rams
- Cpu will be in charge of running ethernet stack and sockets and reading the data and sending through ethernet
- Cpu memcopys some data somewhere from fpga into dram then sent to kernel of cpu and shipped into the socket
- More data means memory limitations quickly
- You will saturate the dma's of dram
- Also saturate cpu and kernel
- This firmware will be provided
- This project aims to remove the cpu from the equation
- Put Ethernet upd stack inside the fpga
- Zync scale+ is the fpga.
- There is a dev kit in the lab
- Can be  on simpler fpga boards
- Fpga will have mac controller that can implement as an ip
- First stack will be to take fpga from zylinx to take packet.
- Meet with Lewan every 2 weeks
- Come up with a bloack diagram of the system
- Start getting hands dirty with fpga board - making led blink - installing some ethernet
- Up to us to self organize
- Mid july to august liyuan wont be available in person (wont be in US)
- Zynx 7000 boards somewhere
- Lab SMBB 1st floor *Pierre's lab
- Send UID to liyuan for access

## 06/13

### Wednesday - 18:00PM - Biweekly agreement (For now)

### Tasks:
	- Getting access to FPGA's 
	- Blink an LED
	- Git and Github create a repo
	- README to record our biweekly meeting (meeting record)
	- Take a look at the UDP protocol
	- Understand how Ethernet works with UDP
	- Vivado - Get familiar with and potentially install(?)
	- Vivado - Have to use vivado for new series Zylinx FPGA
	- Modelsim is in Vivado already
	- UDP - Get a broad overview
	- UDP - Start analyzing in hardware
	- UDP - Reference datasheet
	- Emulator for protocol
		○ Reading and writing behavior
		○ what is the waveform
	- DMA - DMA will help us remove the CPU
	- Understand DMA

### Formatted Tasks
	- We want to get familiarity with the FPGA board but we are waiting on Liyuan before we can do this
	- (Ian) - Create Github Repo and assign a Markdown file to track meeting notes
	- We currently plan on meeting Bi-weekly with Liyuan
		○ For the 3 of us senior bachelor's we will likely meet more but that is TBD
	- Get familiar with UDP and how it contributes to the Ethernet stack
	- Get familiar with how DMA will help us
		○ what is it?
		○ why will it help us?
	
### Outstanding Tasks for Liyuan
	- Get us access to labs
	- Check if we are actually using Vivado


### Liyuan's Role
Take questions to Liyuan (clarified that he wants to be hands off for his role and he is busy so don't treat him as another group member but as someone we can take clarifying questions to![image](https://github.com/user-attachments/assets/93f175c7-8b99-4a9a-9fda-f749d0199a1b)

