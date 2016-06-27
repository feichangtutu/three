# three
### copy a plane game

####DirectionalLight( hex, intensity )
*hex -- Numeric value of the RGB component of the color. 
*intensity -- Numeric value of the light's strength/intensity.

#####Properties
*.target
Target used for shadow camera orientation.

*.shadow
This property stores all relevant information for rendering the shadow of the light.

*.castShadow
If set to true light will cast dynamic shadows. Warning: This is expensive and requires tweaking to get shadows looking right.
Default — false.