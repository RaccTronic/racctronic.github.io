# racctronic.github.io
#FUSES
- # Types
	- Fuses can be
		- **non-resettable**
			- conventional appliance may be rated as high as 600 V
		- **resettable** (*solid-state, polymeric positive temperature coefficient, PTC or PPTC*)
			- seldom rated above 100 V
	- Many variations on the package and sizes
	- **Automotive** specific, **barell** fuses, **strip** (fusible link) and **THT** (**subminiature** fuses)
- # Defining values
	- ### Choosing the amperage
		- **Exception** of that would be when current spikes are relevant in the design. Then the current surge of a duration *t* [s] of a fuse is given by the formula: $$I^2t = I^2 \cdot t$$
		  **Some semiconductors also have this rating (I2t) and should be protected with a similarly rated fuse**
		- For *__resettable fuses__* the maximum safe level of current is known as the *hold current* and the current that triggers its response is termed the *trip current*
	- ### Choosing the voltage rating
		- A fuse can always be used at a lower voltage than the rating.
	- ### Time of delay
		- Fuses may be fast acting, medium acting or slow-blowing. 
		  **None of the terms describing the speed of action of a fuse has been standardized with a specific time or time range, so design-driven datasheet inspection is needed.**
	- ### Temperature dependence of current rating
		- Non-resettable fuses are affected to the minor extent.
		- Resettable fuses are highly sensitive to ambient temperature and should be kept at room temperature to sustain current ratings.
		- Approximate idea of temperature sensitivity:
		  ![Screenshot_20220205_214213.png](../assets/Screenshot_20220205_214213_1644094234102_0.png)
- # Important comments
	- ### Remember to check for the voltage drop presented by a fuse
	- ### A size of the fuse should never be used as a guide to its ratings, but it is relevant to the fuse function
