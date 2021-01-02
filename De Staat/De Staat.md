# [X] Coal
## REQ
1200 ```Coal```
## OUT
1x Pure(1200) = 1200 ```Coal```

---------- 
# [X] Iron Ore
## REQ
1200 ```Iron Ore```
## OUT
4x Impure(300) = 1200 ```Iron Ore```

-----------
# [x] Copper Ore
## REQ
1600 ```Copper Ore```
## OUT
2x Normal(600) = 1200 ```Copper Ore```
2x Impure(300) = 600 ```Copper Ore```
Total: 1800 ```Copper Ore```

-----------------
# [x] Iron Ingot
## UNIT - Smelter
### IN
30 ```Iron Ore```
### OUT
30 ```Iron Ingot```

## UNITS
40 ```Smelters```
## IN
1200 ```Iron Ore```
## OUT
1200 ```Iron Ingot```

-----------------
# [x] Copper Ingot
## UNIT - Smelter
### IN
30 ```Copper Ore```
### OUT
30 ```Copper Ingot```

## UNITS
60 ```Smelters```
## IN
1800 ```Copper Ore```
## OUT
1600 ```Copper Ingot```
200 ```Copper Ingot``` !BONUS!

-----------------
# [x] Alternate: Solid Steel Ingot
## UNIT - Foundry
### IN
40 ```Iron Ingot```
40 ```Coal```
### OUT
60 ```Steel Ingot```

## UNITS
30 ```Foundries```
## IN
1200 ```Iron Ingot```
1200 ```Coal```
## OUT
1800 ```Steel Ingot```

-----------------
# [x] Steel Pipe
## UNIT - Constructor
### IN
30 ```Steel Ingot```
### OUT
20 ```Steel Pipe```

## UNITS
60 ```Constructors```
## IN
1800 ```Steel Ingot```
## OUT
1200 ```Steel Pipe```

-----------------
# [x] Wire
## UNIT - Constructor
### IN
15 ```Copper Ingot```
### OUT
30 ```Wire```

## UNITS
120 ```Constructors```
## IN
1800 ```Copper Ingot```
## OUT
3200 ```Wire```
400 ```Wire``` !BONUS!

-----------------
# [x] Stator
## UNIT - Assembler
### IN
15 ```Steel Pipe```
40 ```Wire```
### OUT
5 ```Stator```

## UNITS
80 ```Assemblers```
## IN
1200 ```Steel Pipe```
3200 ```Wire```
## OUT
400 ```Stator```

//TODO: Further use of 400 ```Wire```?