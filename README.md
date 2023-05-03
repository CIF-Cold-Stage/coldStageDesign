# coldStageDesign
Design files for the cold stage instrument

The repository contains FreeCAD files and .stl files for the cold stage. FreeCAD files can be modified to suit user's preferences while .stl files are helpful to quickly print the designs. 

**Table 1.** Required files and thier location.


Part | .stl | .FCStd
---|---|---
Cold Stage Controller  | [Box_1](https://github.com/CIF-Cold-Stage/coldStageDesign/blob/main/stl/Box_1.stl), [Box_2](https://github.com/CIF-Cold-Stage/coldStageDesign/blob/main/stl/Box_2.stl) | [Box](https://github.com/CIF-Cold-Stage/coldStageDesign/blob/main/frecad/Box.FCStd)
Cold Stage Cell | [Cell](https://github.com/CIF-Cold-Stage/coldStageDesign/blob/main/stl/Body.stl) | [Cell](https://github.com/CIF-Cold-Stage/coldStageDesign/blob/main/freecad/Body.FCStd)
Spacer  | [Spacer](https://github.com/CIF-Cold-Stage/coldStageDesign/blob/main/stl/Spacer.stl) | [Spacer](https://github.com/CIF-Cold-Stage/coldStageDesign/blob/main/freecad/Stand/Spacer.FCStd)
Stand Base | [Base](https://github.com/CIF-Cold-Stage/coldStageDesign/blob/main/stl/Stand_Part1.stl) | [Base](https://github.com/CIF-Cold-Stage/coldStageDesign/blob/main/freecad/Stand/Stand_Part1.FCStd)
Base Supplements | [S1_S2](https://github.com/CIF-Cold-Stage/coldStageDesign/blob/main/stl/small_parts.stl) | [S1](https://github.com/CIF-Cold-Stage/coldStageDesign/blob/main/freecad/Stand/Stand_Part1_S1.FCStd), [S2](https://github.com/CIF-Cold-Stage/coldStageDesign/blob/main/freecad/Stand/Stand_Part1_S2.FCStd)
Stabilizer | [Mid](https://github.com/CIF-Cold-Stage/coldStageDesign/blob/main/stl/Stand_Part2.stl) | [Mid](https://github.com/CIF-Cold-Stage/coldStageDesign/blob/main/freecad/Stand/Stand_Part2.FCStd)
Stand Top | [Top_1](https://github.com/CIF-Cold-Stage/coldStageDesign/blob/main/stl/Stand_Part3_1.stl), [Top_2](https://github.com/CIF-Cold-Stage/coldStageDesign/blob/main/stl/Stand_Part3_2.stl) | [Top_1](https://github.com/CIF-Cold-Stage/coldStageDesign/blob/main/freecad/Stand/Stand_Part3_1.FCStd), [Top_2](https://github.com/CIF-Cold-Stage/coldStageDesign/blob/main/freecad/Stand/Stand_Part3_2.FCStd)


A summary of used parts is given below.

### Cold Stage Controller Box

<img src = "images/Box.png" width = "600"> 

```Cold Stage Controller``` 

The temperature controller TC-36-25-RS23 and power supply LCS150US12 are held within the cold stage controller box. It also has banana plug sockets, 3.5 mm audio mount, USB pass through connector and 3 pin rocker switch. 
The base and cover needs to be printed seperately and are given in Table 1 as **Box_1** and **Box_2**.

### Cold Stage Cell

<img src = "images/Body.png" width = "450"> <img src = "images/Spacers.png" width = "200">

```Cold Stage Cell and Spacers```

Cold stage cell houses the heat sink, TEC element, cold plate and glass cover. Thermal paste needs to be applied to heat sink, TEC element and cold plate. There are two small holes in the cell to insert thermistor cable that connects to the cold plate. Nitrogen is supplied through one of the openings to prevent condensation.
Cold stage cell needs spacers to firmly hold heat sink, TEC element and cold plate together.

The cell prints as a single design and is given as **Cell** while spacers are given as **Spacer** in Table 1.

### Cold Stage Stand

The stand has six different design files that can be easily assembled after printing. Stand can be assembled using 15 mm outer diameter - 25 mm length aluminum tube and screws.

<img src = "images/Stand_Base.png" width = "500"> <img src = "images/Stand_Base_S1.png" width = "200"> <img src = "images/Stand_Base_S2.png" width = "200"> 

```Stand Base and Supplements```

The base houses the cold stage cell. The base requires two supplement parts. 
Base file can be printed using **Base** in Table 1.
All supplement parts can be printed using **S1_S2** in Table 1.

<img src = "images/Stand_Mid.png" width = "500">

```Stand Stabilizer```

Stabilizer is used to provide stability to the three aluminum rods holiding the stand.
It can be printed using **Mid** in Table 1.

<img src = "images/Stand_Top2.png" width = "500">
<img src = "images/Stand_Top1.png" width = "500">

```Stand Top```

There are two design files for the stand top. It houses the camera used to capture freeze events on the cold plate.
The parts can be printed using **Top_1** and **Top_2** in Table 1.



