Colors are specified using predefined color names, or RGB, HEX, HSL, RGBA, HSLA values.
# CSS Background Color
![[Pasted image 20241022232717.png]]
# CSS Text Color
![[Pasted image 20241022233125.png]]
# CSS Border Color
![[Pasted image 20241023075914.png]]
# RGB Value
Ab RGB color value is represents RED, GREEN, and BLUE light sources. A color can be represented using the formula `rgb(red, green, blue)`. Each parameter (red, green, blue) defines the intensity of the color between 0 and 255. For example, `rgb(255, 0, 0)` is displayed as red because red is set to the highest value and the others are set to 0.
To display black, set all color parameters to 0, like this: `rgb(0, 0, 0)`
To display white, set all color parameters to 255, like this `rgb(255, 255, 255)`
![[Pasted image 20241023082118.png]]
Shades of gray are often defined using equal values for all the 3 light sources:
![[Pasted image 20241023082254.png]]
# RGBA Value
RGBA color values are an extension of RGB color values with an alpha channel - which specifies the opacity for a color. An RGBA color value is specified with: `rgba(red, green, blue, alpha)`
The alpha parameter is a number between `0.0` (fully transparent) and `1.0` (not transparent at at all):
![[Pasted image 20241023083606.png]]
# HEX Colors
A hexadecimal color is specified with: `#RRGGBB,` where RR (red), GG (green) and BB (blue) hexadecimal integers specify the components of the color. The hexadecimal values are between `00` and `ff` (same as decimal 0-255). To display black, set all values to `00`, like this: `#000000`.
To display white, set all values to `ff`, like this: `ffffff`.
![[Pasted image 20241023084407.png]]
Shades of gray are often defined using equal values for all the 3 light sources:
![[Pasted image 20241023084503.png]]
The 3-digit hex code is a shorthand for some 6-digit hex codes. The 3-digit hex code has the following form: `#rgb` where r, g, and represent the red green and blue components with values between 0 and f. The 3-digit hex code can only be used when both the values (RR, GG, and BB) are the same for each component. So, if we have `#ff00cc`, it can be written like this: `#f0c`.
# HSL Colors
HSL stands for hue, saturation, and lightness. A color can be specified using HSL in the form:
`hsl(hue, saturation, lightness)`. Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue. Saturation is a percentage value. `0%` means a shade of gray, and `100%` is the full color. Lightness is also a percentage. `0%` is black, `50%` is neither light or dark, `100%` is white.
![[Pasted image 20241023085748.png]]
## Saturation
Saturation can be described as the intensity of a color.