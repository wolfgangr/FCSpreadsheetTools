Forked from the official Repo:
https://github.com/HoWilgh/FCSpreadsheetTools

looks like somebody had to lift it from python 2 to python 3 see the issue here:

https://github.com/HoWilgh/FCSpreadsheetTools/issues/1
NameError: name 'xrange' is not defined. Did you mean: 'range'? - Python version issue? #1 

I'll give it a try 


See also
https://forum.freecad.org/viewtopic.php?style=3&p=754707#p754707

___
ok, looks like replacing `xrange` by `range` restores previous behaviour to quite some amount.
In my opinion, to keep it as part of "1.0", however, some more investment into maturity might be fine.
I'll leave it for now in the current 'works for me' condition.
___



# FCSpreadsheetTools
The macro was developed for the use in FreeCAD (http://www.freecadweb.org/).

It helps managing cells inside FreeCAD's Spreadsheet-workbench. With its help one is able to:
*  Cut/delete data and/or alias information in the selected area of cells.
*  Copy data and/or an alias information in the selected area of cells to clipboard.
*  Paste data and/or alias information in the selected area of cells from clipboard.

More information can be found in the FreeCAD forum: http://forum.freecadweb.org/ and in particular on https://forum.freecadweb.org/viewtopic.php?f=22&t=20508&hilit=spreadsheet#p158443 .

![Screenshot of the ui](https://github.com/HoWilgh/FCSpreadsheetTools/blob/master/Screenshot%20from%202017-09-02%2020-01-49.png)
