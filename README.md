### slickgrid-column-data-autosize

This plug-in is for slickgrid to handle auto size columns based on the header size, data size, cell-formats and max data length.

######Single column auto size
Double click on a column resize handle for auto size

######All columns auto size
Select a cell or row => Ctrl-Shift-a => for whole grid auto size

######How it works

1. Column will auto fit to provided max width if cell data width is more than given max width.
   Slick.AutoColumnSize(100) or default :200

    OR

2. Column will auto fit to max data width in the row if header width is lesser than data width.

    OR

3. Column will auto fit to header width if header width is greater than data width.


######Using simple cell text
https://cdn.rawgit.com/naresh-n/slickgrid-column-data-autosize/master/examples/example-1.html

######Using cell formatter
https://cdn.rawgit.com/naresh-n/slickgrid-column-data-autosize/master/examples/example-2.html
