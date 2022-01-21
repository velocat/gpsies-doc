<!-- markdownlint-disable-next-line first-line-heading -->
!> This section is under development! [TODO](../todo.md )

In addition to the basic (pre-installed) maps, you can use your own (third-party) maps.

> [!WARNING]
> To use this feature, you need the basic concepts of displaying map tiles, layers.

> [!TIP]
> To add **basic** map types, you can read the [demo page](https://leaflet-extras.github.io/leaflet-providers/preview/) , which has a preview of the maps and the correct data for adding them.

### Adding

1. Enter the name of your personal card
1. Select the card type option

>- ***Basic***
>- ***WMS***
>- ***WMTS***
>- ***Overlays***

1. URL (link to get tiles)
1. Zoom (zoom)
1. Copyright, attributes

### Editing

To edit, click :fa fa-edit: in the map block.  
In the window that opens, change the card details.  
The editing process is similar to adding a new personal card.  

### Import

click the `IMPORT` button  
Specify a link to a previously exported set of personal cards or a separate card.

### Export

- ***separate personal card***  
  in the maps section, click :fa fa-share: and in the window that opens, copy the encoded link.
- ***package of all personal cards***  
  click the `EXPORT` button and copy the encoded link in the window that opens.

### Delete

- ***separate personal card***  
  In the maps section, click :fa fa-trash: , the selected card will be deleted.
- ***package of all personal cards***  
  click the `DELETE` button, all added personal cards will be deleted.

### Sorting

Personal cards can also be sorted as basic (preset cards):

- to **change the order** move the block with the name of the map to the desired location
- to **hide**, press :fa fa-eye: in the map block

?> Personal maps, their sorting and configuration are saved in the browser's local storage.  
?> About how to configure local storage: [link](../main-config.md?id=Save-settings)
