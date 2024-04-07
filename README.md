# Media-Queries-for-standard-devices
Media Queries for Standard Devices

Media queries can be used to check many things like the following :
<ul>
  <li>Width and height of the viewport</li>
  <li>Width and height of the device</li>
  <li>Orientation</li>
  <li>Resolution</li>
</ul>





```CSS

  /* Smartphones (portrait and landscape) ----------- */
@media only screen and (min-device-width : 320px) and (max-device-width : 480px) {

}

/* Smartphones (landscape) ----------- */
@media only screen and (min-width : 321px) {

}

/* Smartphones (portrait) ----------- */
@media only screen 
and (max-width : 320px) {

}

/* iPads (portrait and landscape) ----------- */
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px) {

}

/* iPads (landscape) ----------- */
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px) 
and (orientation : landscape) {

}

/* iPads (portrait) ----------- */
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px) 
and (orientation : portrait) {
	
}

/* iPad 3 (portrait and landscape) ----------- */
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px) 
and (-webkit-min-device-pixel-ratio : 2),
only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px) 
and (min-resolution: 192dpi) { 

}

/* Desktops and laptops ----------- */
@media only screen 
and (min-width : 1224px) {
	
}

/* Large screens ----------- */
@media only screen 
and (min-width : 1824px) {
	
}

/* Retina displays ----------- */
@media  only screen 
and (-webkit-min-device-pixel-ratio : 2), 
only screen 
and (min-resolution: 192dpi) {

}
```


