1. Introduction
---------------

  This package contains a modification of a Tetris game originally
  written by Per Cederberg <per@percederberg.net>.  It has been
  modified slightly to serve as the basis for a class project.

  This work is free software; you can redistribute it and/or modify 
  it under the terms of the GNU General Public License as published 
  by the Free Software Foundation; either version 2 of the License, 
  or (at your option) any later version.
 
  This work is distributed in the hope that it will be useful, but 
  WITHOUT ANY WARRANTY; without even the implied warranty of 
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the 
  separate LICENCE.txt file for more details.



2. Background
-------------

  The history of Tetris is described elsewhere, most notably by one
  of the original authors in the following web page:

    http://vadim.www.media.mit.edu/Tetris.htm



3. Installation & Running
-------------------------

  After building (ant) the game can be run using the following
  command:
  
    java -jar dist/tetris.jar     
  
  The game supports a number of configuration parameters as properties
  on the command-line (-Dname=value). All color values should be
  specified with hexadecimal values for their red, green, and blue
  components, in the format '#RRGGBB' (like '#ff8080' for example).
  
    tetris.color.background       - Game background color.
    tetris.color.label            - Text color of the labels.
    tetris.color.button           - Start and pause button bolor.
    tetris.color.board.background - Background game board color.
    tetris.color.board.message    - Game board message color.
    tetris.color.figure.square    - Color of the square figure.
    tetris.color.figure.line      - Color of the line figure.
    tetris.color.figure.s         - Color of the 's' curved figure.
    tetris.color.figure.z         - Color of the 'z' curved figure.
    tetris.color.figure.right     - Color of the right angle figure.
    tetris.color.figure.left      - Color of the left angle figure.
    tetris.color.figure.triangle  - Color of the triangle figure.
        
  The game can be controlled with the following keyboard controls:

    <Left Arrow>
        Moves the falling figure to the left.
    <Right Arrow>
        Moves the falling figure to the right.
    <Up Arrow> or <Space>
        Rotates the falling figure counter-clockwise.
    <Shift> + <Up Arrow> or <Space>
        Rotates the falling figure clockwise.
    <Ctrl> + <Up Arrow> or <Space>
        Rotates the falling figure randomly.
    <Down Arrow>
        Moves the falling figure all the way down.
    N
        Toggles preview of next figure.
    P
        Pauses or resumes the game.
    S
        Increases the falling speed (by one of ten steps).



5. Contributions
----------------

  If you find this program useful or interesting, please consider
  contributing to this project. The easiest way to contribute is to
  report errors or issues regarding the use of this program. If you
  are able to fix the issue in the sources or provide test data to
  demonstrate the problem, it would be ever better. Of course, you are
  also very welcome to do any additions or improvements to the source
  code.
