[![Build Status](https://travis-ci.org/naresh-n/slickgrid-column-data-autosize.svg?branch=master)](https://travis-ci.org/naresh-n/slickgrid-column-data-autosize)

### slickgrid-column-data-autosize

This plug-in is for slickgrid to handle auto size columns based on the header size, data size, cell-formats and max data length.

######Single column auto size
Double click on a column resize handle.

######All columns auto size
Select a cell or row => Ctrl-Shift-a

######How it works

1. Column will auto fit to given/default max width if cell data width is more than given max width.
   Slick.AutoColumnSize(100) or default :200

    OR

2. Column will auto fit to max data width in the row if header width is lesser than data width.

    OR

3. Column will auto fit to header width if header width is greater than data width.

######Browser
    <script src="../src/slick.autocolumnsize.js"></script>

######Bower
    npm install slickgrid-column-data-autosize
    
######Usage
      
      grid = new Slick.Grid("#myGrid", data, columns, options);
      grid.registerPlugin( new Slick.AutoColumnSize());
      [OR]
      grid.registerPlugin( new Slick.AutoColumnSize(200));



######Using simple cell text
https://cdn.rawgit.com/naresh-n/slickgrid-column-data-autosize/master/examples/example-1.html

######Using cell formatter
https://cdn.rawgit.com/naresh-n/slickgrid-column-data-autosize/master/examples/example-2.html
