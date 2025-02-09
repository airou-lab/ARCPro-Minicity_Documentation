
# ARCPro Documentation

You can find more information about ArcPro in our WiKi page here:
(https://airou-lab.github.io/docs/arc/index.html)
#ARCPro Building Construction

## Lets get started! 
For the Bill of Materials, please go to our [ARCPro BOM](https://docs.google.com/spreadsheets/d/1xc6m2KjmdyQvV1nY1KGfAFUgrYJwhJbU0oIUqCPX6PE/edit?usp=sharing).

We recommend following step 1 (below) while you wait for the ordered materials to arrive to save time. 

# How to build

## 1: Download .STEP or .stl files
If you want to modify the car, you will need to download the CAD files. Note, we strongly recommend to use Solidworks, but it requires a subscription. However, since we provided .STEP files as well, you can modify on ANSYS as its free, but be warned, its far more difficult to work with. If you want to use our design without modification, please download the .stl files. This should include:
```
2 Chassis Extension (left and right)
4 Chassis Supports
8 Platform Supports
3 Platforms (they're labeled 1,2, and 3)
Combined, it takes around 20 hours and 500g of filament per car to 3D print (at 25% infill on Prusa printer)
```
After printing, ensure the parts were printed well, and you have all the parts mentioned above.

## 2: Remove all prexisting parts from the chassis
This includes the existing ESC (On top of the servo motor), protective casing over the driveshaft, but keep the servo motor and DC motor.

## 3: Measure the length of your chassis. 
This means from one edge to another, NOT from wheel to the other. **Mark the center**

## 4: Both left and right, mark 2 inchs. Do the same for the opposite side of the chassis. Carefully drill al 3 holes using a M3 drill bit. 
Be very careful not to drill into the Servo motor or DC motor.

## 5: Place the chassis extension. 
Screw the extension with in M2.5 14mm and secure with a hex nut. 

## 6: Secure Chassis Supports on top of the chassis extension, aligned with the holes. 
Ensure you insert the hex nuts into slots of additional support.

## 7: Referring to Platform 1, on the top (has a T at the bottom)
Secure the power converter with the M2.5 Panhead screws and plastic washers underneath the converter (between the board and the platform.) Flip the platform over and attach the hex nuts.
**Refer to VESC Documentation to reprogram _BEFORE_ attaching to platform**

## 8: Attach Platform Supports to Platform 1
Securing the supports will make it easier than if you secured the platform first. Use Flathead M2.5x10mm screw and insert hex nuts into slots of support.

## 9: Secure Platform 1 to Chassis Supports
Use Flathead M2.5x10mm screws. Insert hex nuts into slots of support.

## 10: Attach platform supports to top of Platform 2 
