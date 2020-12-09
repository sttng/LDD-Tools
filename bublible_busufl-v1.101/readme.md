## 2017-10-13 - v1.101 

* NEW: when moved positions of both Main and Render window are saved so they'll re-open at their respective last spot 
* UPDATE: some CMD GUI info texts UPDATE: some internal code optimization 
* CHANGE: default image resolution (now FullHD) and "samples" value (now 32 for perfect smoothing) 
* CHANGE: lowered intensity of color variation for black color CHANGE: TAB name of "AnimatorGIF" to "Animator" 
* CHANGE: increased level of metallic shine in Pearl shader 
* CHANGE: some of metallic and pearl colors look 
* CHANGE: trans-dark blue color/material is a bit darker now 
* FIX: for a single or "main" model (if more than 1 are loaded in BUSUFL) its Y-axis won't be set to 0 anymore = rotation (look) exactly as in LDD 
* FIX: if brick had non-existent material it'd end up in error, now it'll be rendered as "shadowless" constant white 
* FIX: all FLEX bricks should now render as expected 
* FIX: multicolored brick 47899 should now render as expected 
* FIX: multicolored brick 30361 should now render as expected 
* FIX: multicolored brick 16709 should now render as expected 
* FIX: multicolored torso brick 16360 should now render as expected 
* FIX: all decorations containing some tiny lines sections were rendered wrongly, basically without those parts (looked like bleached or "sunken") 
* FIX: rendering error if all LDD models in a .bsfm file were set to "off" 
* FIX: rendering time did not start immediately after clicking RENDER button 
* FIX: previous rendering window was not closed immediately after clicking RENDER button 
* FIX: unnecessary and annoying warning window of "BCKT(NaN shading sample)" disrupting flow of rendering process as render'd continue anyway 
* FIX: clicking CAMERA reset fdist button did not update the value for actual render 
* FIX: text in progressbar didn't update right after clicking on render button 
* FIX: MixShader's phong and pearl values were ignored when in 2nd position 
* FIX: GUI temporarily freeze when BUSUFL starts rendering searching for bricks in the .lxf 
