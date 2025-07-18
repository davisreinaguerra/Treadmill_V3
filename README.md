# Treadmill_V3


# Pin Assignments
Function              | Due Pin  | Cam Nano Pin | Opto Nano Pin | Labjack T7 Pin | Alignment Notes                                | 
|---------------------|----------|--------------|---------------|----------------|--------------------------------------|
| LED Control Green   | n/a      | n/a          | n/a           | DAC0           ||
| LED Control Red     | n/a      | n/a          | n/a           | DAC1           || 
| Photodetector Green | n/a      | n/a          | n/a           | AIN0           ||
| Photodetector Red   | n/a      | n/a          | n/a           | AIN1           || 
| LED Copy Green      | n/a      | n/a          | n/a           | AIN2           ||
| LED Copy Red        | n/a      | n/a          | n/a           | AIN3           ||
| Audio Left          | DAC1     | n/a          | n/a           | AIN4           ||
| Audio Right         | DAC2     | n/a          | n/a           | AIN5           ||
| RotaryA             | n/a      | n/a          | n/a           | DIO0 (FIO0)    ||
| RotaryB             | n/a      | n/a          | n/a           | DIO1 (FIO1)    ||
| Running             | D2       | n/a          | n/a           | DIO2 (FIO2)    | Goes HIGH prior to initiation of session and LOW following the completion. Initiates photometry and camera |
| Cue                 | D3       | n/a          | n/a           | DIO3 (FIO3)    | Goes HIGH at start of cue period and LOW at end, regardless of whether a cue actually plays |
| Opto Trig           | D4       | n/a          | n/a           | DIO4 (FIO4)    | Initiates whatever program the Opto Nano is set to run |
| Lick                | D5       | n/a          | n/a           | DIO5 (FIO5)    | Records every lick event regardless of task structure
| Reward Solenoid     | D6       | n/a          | n/a           | DIO6 (FIO6)    | Square pulse profile matches open state of solenoid
| Airpuff Solenoid    | D7       | n/a          | n/a           | DIO7 (FIO7)    | Square pulse profile matches open state of solenoid
| Camera Frame Pulse  | n/a      | D5           | n/a           | DIO8 (EIO0)    | 
| Opto Pulse          | n/a      | n/a          | D5            | DIO9 (EIO1)    | Reports back the pulse sent to the laser by the Opto Nano for direct alignment to opto pulses |
