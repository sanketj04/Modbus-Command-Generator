# Modbus Command Generator v1

## **1. Read command tab**

### **Select Modbus protocol mode in which slave is set.**

     1. Serial RTU
     2. Serial ASCII
     3. TCP IP
     4. RTUoverTCP

**Select device's slave ID :**

     1. Enter slave device's (Analyser/Energy meter/Other modbus device) ID configured in the device itself. 

**Select one of the four available read function codes**

     1. Read coil status (01)
     2. Read input status (02)
     3. Read holding registers (03)
     4. Read input registers (04)

**Enter starting address :**

     1. Enter the address of the first coil or register to be read.

**Enter read length**

     1. Enter the number of coils or registers required to be read.
     2. Press enter key to generate the command.

**Copy command**

     1. Click copy icon below the command to copy command to the clipboard. 

## **2. Write command tab**

### **Select Modbus protocol mode in which slave is set.**

     1. Serial RTU
     2. Serial ASCII
     3. TCP IP
     4. RTUoverTCP

**Select device's slave ID :**

     1. Enter slave device's (Analyser/Energy meter/Other modbus device) ID configured in the device itself. 

**Select one of the four available write function codes**

     1. Force single coil (05)
     2. Preset single holding register (06)
     3. Force multiple coils (15)
     4. Preset multiple holding registers (16)

**Enter starting address :**

     1. Enter the address of the first coil or register to be written.

**Enter write length**

     1. Enter the number of coils or registers required to be written in case of multiple.

**Write address and its value**

     1. Enter the address and its value against it and press enter.
     2. Repeat this for every address.
    
**Copy command**

     1. Click copy icon below the command to copy command to the clipboard. 

