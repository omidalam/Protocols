
## Standard STORM buffer

*   400 uL Dilution Buffer
*   100 uL of 50% Glucose
*   5 uL of BME
*   10 uL of Oxygen Scavenger (GLOX) solution (Make fresh each week)
*   Optional: Add 5uL COT for brighter switching cycles (requires higher laser power).  

### Component Recipes:
1.  Dilution Buffer
  * 50 mM NaCl 10-200* mM Tris, pH 8.0
2.  50% (m/v) Glucose stock 
3.  Oxygen Scavenger (GLOX) 
   * 100 uL of Dilution Buffer (see above) 
   * 7 mg Glucose Oxidase, or 14 mg of Pyranose Oxidase** (Sigma-Aldrich) 
   * 25 uL of catalase (16 mg/mL stock; Sigma Aldrich) 
   * Dissolve glucose oxidase in Dilution Buffer, vortex to mix. After mixing the catalase suspension well, add catalase to glucose oxidase solution.
   * Centrifuge at maximum speed for 1 min.  Use the yellow supernatant for imaging buffers. 
   *  Store working tube at 4C for up to 1 week.
4.  BME
   * Beta-mercaptoethanol (Sigma-Aldrich 63689-25ML-F). 
   * Use straight.  Store at 4C. 
5.  COT 
   * Cyclooctatetraene (138924 Sigma Aldrich).  
   * Dilute 0.0208 g COT in 1 mL of DMSO.  Aliquot and store frozen


> *(higher molar Tris recommended for longer STORM imaging)
> 
> **Pyranose Oxidase is more expensive but ensures stable buffer pH in buffers exposed to air.  Glucose oxidase will cause buffer pH to drop rapidly (pH ~4 or less) if exposed to air for a few hours.  

### MEA buffer
* Dissolve 77 mg MEA (a.k.a. cysteamine, Sigma-Aldrich) in 360 mM HCl for a 1M stock solution.
* make fresh before use.
* use at 10 mM final concentration instead of BME 

### Comparison of MEA and BME
* Alexa647 / Cy5 switching in BME will give more photons per cycle and is a more stable compound (MEA should be made fresh and STORM buffer with MEA will deteriorate faster).  
* MEA has a longer duty cycle and is good for very dense samples.  MEA is also more sensitive to 405 stimulation and may therefore be better when not using activator dyes.  


## Recommendations for imaging with 750 dyes
* For cy7, prepare STORM buffer as above with COT.   Replace 5 uL BME with 5 uL of 1M MEA.
* For Alexa 750 prepare STORM buffer as above with COT. Replace 5 uL BME with 2 uL of 1M MEA.
   - if dyes are still dimmer than desired, decrease to 1 uL of 1M MEA per 500 uL buffer.  

## TCEP Buffer

*   0.2 M Tris pH 9  (200 uL Tris 1M pH 9.0)
*   1 mM Methyl viologen. (10 uL of 0.1 M stock.  Make fresh from powder.) (25.7 mg / mL)  (Toxic!)
*   1 mM Ascorbic Acid (10 uL of 0.1 M stock.  Make fresh from powder.)   (17.6 mg/mL)
*   25 mM TCEP (50 uL of a 0.5 M stock vial.  $5/vial, use fresh, no more than 1 day).
*   1% Glox (usual strength.  10 uL in 1 mL)
*   5% glucose
*   ddH2O -- fill to 1000 uL.

### TCEP Buffer information

*   See [publication][1] for more details
*   750 in TCEP 2800 photon (compared to 700 in BME and 3-400 in MEA).
*   Allows for ~equal photon yield 750 and 647 imaging.
*   Can image both at 200 Hz. (750 still better at 60 Hz.) 
*   not as robust -- concentration of TCEP matters, laser power effects duty cycle (higher laser power = lower duty cycle.  necessary for dense imaging)
*   750 gas laser causes vibrations that errode ability to see 'hollow' structure of microtubules (in any channel)
*   897 ultra camera runs at 60 Hz in 512x512 
*   not compatible with other dyes (e.g. Cy3B). 


 [1]: http://pubs.acs.org/doi/pdf/10.1021/ja3105279

## Trolox Buffer (conventional imaging)
Recipe from Kok Hao Chen
### buffer composition
* 50mM Tris, 200mM NaCl (or 2xSSC), 
* 10% Glucose, 
*  saturating amount (~2mM) of Trolox. 
  
### Prep protocol
1. Add all the ingredients together with ~10mg of Trolox in 10mL of total volume. Trolox is in way excess and it will not dissolve completely. 
2. Sonicate the mix for ~5-10mins and then leave the mix in the cold room shaking overnight. 
3. Filter the mix the next day morning, and the buffer is ready to be used. 