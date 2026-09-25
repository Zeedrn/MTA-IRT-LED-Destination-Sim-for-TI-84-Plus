## Codes here will not work properly because of unsuported characters are copied directly to here, go to Releases.

Lbl S
ClrHome
Disp "IRT Route?"
Input ":",I
If I=2
Then
DelVar I
Menu("Direction?","241 St",22,"Flatbush Av",2F,"New Lots Av",2N)
Else
If I=4
Then
DelVar I
Menu("Direction?","Woodlawn",4W,"Utica Av",4U,"New Lots Av",4N)
Else
If I=5
Then
DelVar I
Menu("Direction?","Dyre Av",5D,"Nereid Ave",5R,"Flatbush Av",5F,"Bowling Green",5B,"East 180 St",5E,"Utica Av",5U,"New Lots Av",5N)
Else
If I=7
Then
DelVar I
Menu("Type?","(7)-LCL",7L,"<7>-EXP",7E)
Else
DelVar I
ClrHome
Disp "Not a Valid Code"
Pause 
Goto S
End
End
End
End
End
End
Lbl 7L
Menu("Direction?","Flushing",7F,"34 ST-HYD",7H)
Lbl 7E
Menu("Direction?","Flushing",7M,"34 ST-HYD",7Y)
Lbl 22
ClrDraw
Circle(7,­6,6)
Text(3,6,"2")
Text(3,20,"TO 241 ST")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"2")
Text(3,20,"VIA 7TH AV EXP")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"2")
Text(3,20,"BRONX LCL")
For(T,0,1000,1)
End
Goto 22
Lbl 2F
ClrDraw
Circle(7,­6,6)
Text(3,6,"2")
Text(3,20,"TO FLATBUSH AV")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"2")
Text(3,20,"VIA 7TH AV EXP")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"2")
Text(3,20,"BROOKLYN EXP")
For(T,0,1000,1)
End
Goto 2F
Lbl 2N
ClrDraw
Circle(7,­6,6)
Text(3,6,"2")
Text(3,20,"TO NEW LOTS AV")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"2")
Text(3,20,"VIA 7TH AV EXP")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"2")
Text(3,20,"BROOKLYN LCL")
For(T,0,1000,1)
End
Goto 2N
Lbl 4W
ClrDraw
Circle(7,­6,6)
Text(3,6,"4")
Text(3,20,"TO WOODLAWN")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"4")
Text(3,20,"VIA LEXINGTON AV EXP")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"4")
Text(3,20,"BRONX EXP")
For(T,0,1000,1)
End
Circle(7,­6,6)
Goto 4W
Lbl 4U
ClrDraw
Circle(7,­6,6)
Text(3,6,"4")
Text(3,20,"TO UTICA AV")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"4")
Text(3,20,"VIA LEXINGTON AV EXP")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"4")
Text(3,20,"BROOKLYN EXP")
For(T,0,1000,1)
End
Goto 4U
Lbl 4N
ClrDraw
Circle(7,­6,6)
Text(3,6,"4")
Text(3,20,"TO NEW LOTS AV")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"4")
Text(3,20,"VIA LEXINGTON AV EXP")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"4")
Text(3,20,"BROOKLYN LCL")
For(T,0,1000,1)
End
Goto 4N
Lbl 5D
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,20,"TO DYRE AV")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,20,"VIA LEXINGTON AV EXP")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,20,"BRONX EXP")
For(T,0,1000,1)
End
Goto 5D
Lbl 5R
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,20,"TO NEREID AV")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,20,"VIA LEXINGTON AV EXP")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,20,"BRONX EXP")
For(T,0,1000,1)
End
Goto 5R
Lbl 5F
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,20,"TO FLATBUSH AV")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,20,"VIA LEXINGTON AV EXP")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,25,"BROOKLYN EXP")
For(T,0,1000,1)
End
Goto 5F
Lbl 5B
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,20,"TO BOWLING GREEN")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,20,"VIA LEXINGTON AV EXP")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,20,"BRONX EXP")
For(T,0,1000,1)
End
Goto 5B
Lbl 5E
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,20,"TO EAST 180 ST")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,20,"VIA LEXINGTON AV EXP")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,20,"BRONX LCL")
For(T,0,1000,1)
End
Goto 5E
Lbl 5U
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,20,"TO UTICA AV")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,20,"VIA LEXINGTON AV EXP")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,20,"BROOKLYN LCL")
For(T,0,1000,1)
End
Goto 5U
Lbl 5N
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,25,"TO NEW LOTS AV")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,25,"VIA LEXINGTON AV EXP")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"5")
Text(3,20,"BROOKLYN LCL")
For(T,0,1000,1)
End
Goto 5N
Lbl 7F
ClrDraw
Circle(7,­6,6)
Text(3,6,"7")
Text(3,20,"TO FLUSHING-MAIN ST")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"7")
Text(3,20,"VIA FLUSHING LCL")
For(T,0,1000,1)
End
Goto 7F
Lbl 7H
ClrDraw
Circle(7,­6,6)
Text(3,6,"7")
Text(3,20,"TO 34 ST-HUDSON YARDS")
For(T,0,1000,1)
End
ClrDraw
Circle(7,­6,6)
Text(3,6,"7")
Text(3,20,"VIA FLUSHING LCL")
For(T,0,1000,1)
End
Goto 7H
Lbl 7M
ClrDraw
Line(7,0,13,­6)
Line(13,­6,7,­12)
Line(7,­12,1,­6)
Line(1,­6,7,0)
Text(3,6,"7")
Text(3,20,"TO FLUSHING-MAIN ST")
For(T,0,1000,1)
End
ClrDraw
Line(7,0,13,­6)
Line(13,­6,7,­12)
Line(7,­12,1,­6)
Line(1,­6,7,0)
Text(3,6,"7")
Text(3,20,"VIA FLUSHING EXP")
For(T,0,1000,1)
End
Goto 7M
Lbl 7Y
ClrDraw
Line(7,0,13,­6)
Line(13,­6,7,­12)
Line(7,­12,1,­6)
Line(1,­6,7,0)
Text(3,6,"7")
Text(3,20,"TO 34 ST-HUDSON YARDS")
For(T,0,1000,1)
End
ClrDraw
Line(7,0,13,­6)
Line(13,­6,7,­12)
Line(7,­12,1,­6)
Line(1,­6,7,0)
Text(3,6,"7")
Text(3,20,"VIA FLUSHING EXP")
For(T,0,1000,1)
End
Goto 7Y
