Textual maze generation
========================

Java application that generates mazes using a variant of Prim's algorithm.
The maze is guaranteed to have a solution, which I found is often non-trivial.

Outputs a nicely formatted maze 
 # is a wall
 O is a room
 - | hallways
 S E start and end

 
Sample outputs

6x3 maze

        #############
        #S-O-O-O-O-O#
        #|#|#|###|###
        #O#O#O#O-O#O#
        #|#######|#|#
        #O-O-O#O-O-E#
        #############


10x4 maze

    #####################
    #S#O#O-O-O#O#O-O#O#O#
    #|#|###|###|###|#|#|#
    #O-O#O-O-O#O#O#O-O-O#
    ###|#####|#|#|###|#|#
    #O-O-O-O-O-O#O#O-O#O#
    #####|#|###|#|#|#####
    #O-O-O#O#O-O-O-O-O-E#
    #####################





