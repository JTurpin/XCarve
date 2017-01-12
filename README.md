# Parallel CNC Stepconf settings

### Basic settings

Setting | Value |
 --- | :----: |
Machine Name | XCarve 
Axis Configuration | XYZ
Machine Units | mm
Driver Type | Other
Step Time |	1900
Step Space | 1900
Direction Hold |	650
Direction Setup |	650
Base Period Maximum Jitter | 50000

[Pololu DRV8825](https://www.pololu.com/product/2133)

---

### Parallel Port (DB-25) pin mappings

 pin |  mapping | 
:---: | :---------:
 1    | **enable**         
 2    | **X** step         
 3    | **X** dir          
 4    | **Y** step         
 5    | **Y** dir          
 6    | **Z** step         
 7    | **Z** dir          
 8    | **A** step         
 9    | **A** dir          
 10   | **E-Stop**         
 11   | **X** Limit        
 12   | **Y** Limit        
 13   | **Z** Limit        
 14   | Spindle dir        
 15   | **A** Limit        
 16   | Spindle PWM        
 17   | Aux 1              

### Parallel Port Setup

| Outputs | Inputs ||


#### Outputs

pin |  mapping | Inverted 
:---: | :---------: | :---:   
1  | enable      | * 
2  | X Step      |
3  | X Dir       |
4  | Y Step      |
5  | Y Dir       |
6  | Z Step      | 
7  | Z Dir       |
8  | Y Step      |
9  | Y Dir       | * 
14 | Spindle Dir |
16 | Spindle PWM |
17 | Aux 1       |

#### Inputs
pin | mapping | Inverted 
:---: | :--------: | :---:
10 | E-Stop |
11 | X Limit |
12 | Y Limit |
13 | Z Limit |
15 | A Limit |

---

### X axis configuration

Setting | Value |
 --- | :----: |
Motor Steps Per Revolution | 200
Driver Microstepping | 2
Pulley Ratio | 12.5
Leadscrew Pitch | 0
Maximum Velocity | 500
Maximum Acceleration | 600
Home Location | 0
Table Travel | 1000
Home Switch Location | 0
Home Search Velocity | -30
Home Latch Direction | Opposite

---

### Y axis configuration
Setting | Value |
 --- | :----: |
Motor Steps Per Revolution | 200
Driver Microstepping | 2
Pulley Ratio | 12.5
Leadscrew Pitch | 0
Maximum Velocity | 500
Maximum Acceleration | 600
Home Location | 0
Table Travel | 1000
Home Switch Location | 0
Home Search Velocity | -30
Home Latch Direction | Opposite

---

### Z axis configuration
Setting | Value |
 --- | :----: |
Motor Steps Per Revolution | 200
Driver Microstepping | 2
Pulley Ratio | 12.5
Leadscrew Pitch | 0
Maximum Velocity | 500
Maximum Acceleration | 600
Home Location | 0
Table Travel | 1000
Home Switch Location | 0
Home Search Velocity | -30
Home Latch Direction | Opposite

---

### Spindle Configuration
Not used

### Options
Not used

