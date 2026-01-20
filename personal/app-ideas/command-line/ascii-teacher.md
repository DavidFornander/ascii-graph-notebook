# The ascii teacher / visualize any data you pipe into it. 

Light weight cli utility for generating ascii right in the terminal.


Pipe to ascii -> ```cat car-engine.txt | ascii``` ->            
                                                    



        1. INTAKE         2. COMPRESSION        3. POWER          4. EXHAUST
       (Fuel/Air In)         (Squeeze)           (Ignition)        (Fumes Out)
  
        Spark Plug          Spark Plug          Spark Plug          Spark Plug
           _!_                 _!_                 _!_                 _!_
          /   \               /   \               /   \               /   \
    Intake | | Exhaust       | | | |             | | | |             | | | | Exhaust
    Valve  | | Valve         | | | |             | | | |             | | Open
    Open  _| |_ Closed      _| |_  |_           _| |_  |_           _| |_
         | v   |           |      |            | \ /  |            |     ^ |
         | ->  |           |      |            | *!* |            |   ->  |
         |     |           |  ^   |            |      |            |  ^    |
         | P   |           |  |   |            |  |   |            |  |    |
         |__|__|           |__|__|             |__|__|             |__|__|
            |                 |                   |                   |
            O (Crank)         O                   O                   O
          __|__             __|__               __|__               __|__
  
      Piston moves       Piston moves        Spark ignites!      Piston moves
         DOWN                 UP              Force pushes            UP
                                              Piston DOWN

You can also run ```ascii "visualize the pistons in a car engine"```
    
          Cyl 1       Cyl 2       Cyl 3       Cyl 4
        +-------+   +-------+   +-------+   +-------+
        |       |   | ##### |   | ##### |   |       |
        |       |   | ##### |   | ##### |   |       |
        | ##### |   | ##### |   | ##### |   | ##### |
        | ##### |   |   |   |   |   |   |   | ##### |
        +---+---+   +---+---+   +---+---+   +---+---+
            |           |           |           |
            |           |           |           |
        ----O-----------O-----------O-----------O----  <-- Cam/Crank Shaft
       (Bottom)       (Top)       (Top)      (Bottom)
    

    The ascii teacher who will visualize any data you pipe into it. 

You can also run ```ascii "Go in depth on one piston/cylinder"```
    
    
         ___________
        |  TIMING   |
        |   BELT    |
        |___________|
              |
        ______|______
       /   SPARK!    \
      |      \ /      |
      |     * | * |  <--- EXPLOSION
      |    * |  * |       pushes down
      |   ____v____   |
      |  | PISTON  |  |
      |  |_________|  |
      |      |        |
      |      | Rod    |
      |      |        |
      |_____(O)_______|    