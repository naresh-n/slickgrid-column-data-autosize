### slickgrid-column-data-autosize

This plug-in is for slickgrid to handle auto size columns considering header size, data size, cell-formats and max data width.

######Single column auto size
Double click on a column resize handle for auto size

######All columns auto size
Select a cell or row => control-shift-a => for whole grid auto size

######How it works

1. column will auto fit to max width if cell data width is more than given max width
   new Slick.AutoColumnSize(100) or default :200

2. column will auto fit to max data width in the row if header width is less than data width.

3. column will auto fit to header width in the row if header width is greater than data width.