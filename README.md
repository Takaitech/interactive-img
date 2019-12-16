# INTERACTIVE IMAGE

## Change Image


Identify src in image tag and Replace text inside the double quotes with new image file name
or a url to the new image.

</br>
Examples:(Don't use parentheses) 

```
<img 
    class="interactive-image" 
    src="(insert-new-image-file-name.jpg)" />

or

<img 
    class="interactive-image" 
    src="(insert-new-image-URL.com)" />
```

</br>
</br>
</br>

## Move Image Point

Change left and top values to X and Y coordinates of image for desired position 

-Must be percentage values

-Keep right and left point on their current sides (center can be placed anywhere around the center of image)

-Must change to same percentage on both image-point and pop-up-box (see below)

</br>   
Example: (Don't use parentheses) 

``` 
    <div
        class="image-point right pulse"
        style="
            left: (Insert new X coordinate)%;
            top: (Insert new Y coordinate)%;
        "
    >
    <div
        class="pop-up-box"
        style="
            left: (Insert same X coordinate as image point)%;
            top: (Insert same Y coordinate as image point)%;
        "
    >
```