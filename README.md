## Welcome to the release version of the FrankEnstein V2 Toolhead!

As the brainchild of KevinAKASam and successor to the orginal Frank toolhead, Frank 2 builds upon it's predecessor by being even more modular with support for a wide vareity of hotends and extruders for the Ender 3 and similar with its carriage plate mount as well as as any printer with a front MGN12H linear rail (with some tweaking depending on the printer). Frank 2 features double sided dual fan cooling for either 4010 or 5015 blower fans and well as the option of either 3010 or 4010 fans (with printed adapter) for hotend cooling. The entire tool head is held together securely by 4 screws to the mount and 2 from the extruder mount for easy assembly and disassembly. As in Frank 1, Frank 2 also uses standard Voron spec heat set inserts (M3x5x4) to ensure the longevity of your printed parts while assembling and dissaembling.

[![Frank V2 using the stock Ender hotend with the Papilio Lite, dual 4010 part cooling, and 3010 hotend cooling](./.images/FrankV2_Stock_Pap_4010_(512).png)](./.images/FrankV2_Stock_Pap_4010.png)

<dl>
<dt>Supported Hotends:</dt>
<dd>Dragon</dd>
<dd>Dragonfly BMO</dd>
<dd>Dragonfly BMS (7 fin)</dd>
<dd>Spider Pro</dd>
<dd>Spider V2</dd>
<dd>Stock Ender 3 (Creality Mk8)</dd>
<dd>Triangle Labs TR6</dd>
<dd>TZ V6</dd>
<dd><em>and most hotends that use one of the above mounting patterns...</em></dd>

<dt>Supported Extruders:</dt>
<dd>Bowden</dd>
<dd>LGX Lite</dd>
<dd>Orbiter 1.5</dd>
<dd>Orbiter 2.0</dd>
<dd>Papilio</dd>
<dd>Sherpa Mini (with or without K Face)</dd>
<dd><em>and most extruders that use one of the above mounting patterns...</em></dd>
</dl>

#### Bill of Materials

| Item                             					| Quantity                        |   |
|---------------------------------------------------|---------------------------------|---|
| **For Carriage Plate Base:**     					|                                 |   |
| &nbsp;&nbsp;Voron spec heatset insert       		| x6 (x7 for E3 V2 plate)         |   |
| &nbsp;&nbsp;M3x8 SHCS                       		| x2                              |   |
| &nbsp;&nbsp;**For BL/CR Touch Mount:**          	|                                 |   |
| &nbsp;&nbsp;&nbsp;&nbsp;M2x8mm SHCS               | x2                              |   |
|                                  					|                                 |   |
| **For MGN12H Base:**             					|                                 |   |
| &nbsp;&nbsp;300mm MGN12H Linear Rail        		| x1                              |   |
| &nbsp;&nbsp;Voron spec heatset insert       		| x10                             |   |
| &nbsp;&nbsp;M3x4mm or 5mm SHCS              		| x4                              |   |
| &nbsp;&nbsp;M3x35mm BHCS (preferred) or SHCS		| x2                              |   |
| &nbsp;&nbsp;**For Cable mount:**            		|                                 |   |
| &nbsp;&nbsp;&nbsp;&nbsp;M3x10mm SHCS              | x2                              |   |
| &nbsp;&nbsp;**For Klack Mount:**            		|                                 |   |
| &nbsp;&nbsp;&nbsp;&nbsp;M3x6mm SHCS               | x2                              |   |
|                                  					|                                 |   |
| **For Hotend Mount:**            					|                                 |   |
| &nbsp;&nbsp;Hotend of choice                		| x1                              |   |
| &nbsp;&nbsp;Voron spec heatset insert       		| x8 (or x10 for some hotends)    |   |
| &nbsp;&nbsp;Hotend mounting screws          		| Varies (Should come with hotend)|   |
| &nbsp;&nbsp;M3x35mm SHCS                   	    | x4                              |   |
| &nbsp;&nbsp;**For 3010 and 4010 Cooling:** 		|                                 |   |
| &nbsp;&nbsp;&nbsp;&nbsp;3010 or 4010 axial fan	| x1 (Ball bearing preferred)	  |   |
| &nbsp;&nbsp;&nbsp;&nbsp;M3x12mm SHCS              | x4                              |   |
| &nbsp;&nbsp;**For 4010 fan adapter:**       		|                                 |   |
| &nbsp;&nbsp;&nbsp;&nbsp;M3x8mm SHCS               | x4                              |   |
| &nbsp;&nbsp;&nbsp;&nbsp;Voron spec heatset insert | x4                              |   |
|                                 					|                                 |   |
| **For Extruder Mount:**          					|                                 |   |
| &nbsp;&nbsp;Extruder of choice              		| x1                              |   |
| &nbsp;&nbsp;Voron spec heatset insert       		| x2 to x4 depending on extruder  |   |
| &nbsp;&nbsp;M3x20mm SHCS or BHCS or         		| x2 (non-LGX Lite)               |   |
| &nbsp;&nbsp;M3x8mm SHCD or BHCS             		| x2 (LGX Lite ONLY)              |   |
| &nbsp;&nbsp;Extruder mounting screws        		| Varies (Mostly some amount of M3x6/8/10mms)|   |
|                                  					|                                 |   |
| **For Part Cooling:**            					|                                 |   |
| &nbsp;&nbsp;**For Dual 4010:**              		|                                 |   |
| &nbsp;&nbsp;&nbsp;&nbsp;4010 blower fan           | x2                              |   |
| &nbsp;&nbsp;&nbsp;&nbsp;M2x8mm SHCS               | x6                              |   |
| &nbsp;&nbsp;&nbsp;&nbsp;M2x10mm SHCS              | x2                              |   |
| &nbsp;&nbsp;&nbsp;&nbsp;M2 Washer                 | x2                              |   |
| &nbsp;&nbsp;**For Dual 5015:**              		|                                 |   |
| &nbsp;&nbsp;&nbsp;&nbsp;5015 blower fan           | x2                              |   |
| &nbsp;&nbsp;&nbsp;&nbsp;Voron spec heatset insert | x6                              |   |
| &nbsp;&nbsp;&nbsp;&nbsp;M3x8mm SHCS               | x2                              |   |
| &nbsp;&nbsp;&nbsp;&nbsp;M3x20mm SHCS              | x4                              |   |
| &nbsp;&nbsp;&nbsp;&nbsp;M3 Washer                 | x4                              |   |

#### Print Settings: The Magic 5

```
Infill:
* 55%
Walls/Perimeters:
* 5
Top Layers:
* 5
Bottom Layers:
* 5
```

Not finding exactly what you need? Check out [User Mods](./User_Mods) to see if it's been made or if it hasn't feel free to design it and request a pull in User Mods!

Have a question or just want to hang out with some cool people? [Join our discord here!](https://discord.gg/xqpKrxt9FC)

_Build guide coming..._

[![An exploded view of the above Frank](./.images/FrankV2_Stock_Pap_4010_exp_(512).png)](./.images/FrankV2_Stock_Pap_4010_exp.png)