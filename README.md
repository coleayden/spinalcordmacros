Spinal cord macros were created for use in ImageJ/Fiji for automated cell density quantification in user defined regions of interest.
Macros were created to quantify cell counts in spinal cord transverse section and allow user to outline defined regions (lesions, whole cord and gray matter).
Combination of background subtraction, removing outliers, moments thresholding and analyze particles functions are used to identify and count positive cells.
For double positive cell counting and inverted mask is applied from the less selective channel (ex- Olig2 or Aspa) applied over the more selective channel (ex- GFP) to identify double positive cells.
Single positive cells are also quantified for all channels.
User can outline individual lesions or lesions as a whole.
QA image is generated showing counted cells with bare outlines.
To calculate non-lesion white matter density, of whole cord cell density was subtracted from gray matter and total lesions densities (this was done due to ease at outlining gray matter compared to going around lesions for non-lesion white matter).
With this approach all lesions would need to be outlined to correctly quantify total non-lesion white matter density.
Single region of non-lesion white matter could also be outlined with minimal adjustment of macro if desired.
Resolution of 20x images used for all macros was 0.65pixel/micron and may need to be adjusted.
