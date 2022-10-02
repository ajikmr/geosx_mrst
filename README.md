# geosx_mrst

## Exampe 1 ##
### Based on MRST example at: ###
https://bitbucket.org/mrst/mrst-autodiff/src/master/compositional/examples/compositionalExample3DSixComponents.m

GEOSX input file name: input_5comp.xml
MRST input file name: input_5comp.m

* GEOSX has MAX_COMPONENT=5, and so last component of original example (i.e. 'C25-80') is not used.
* Initial pressure (p_i) in original example is 150bar. GEOSX run fails with 150 bar, and so 200 bar is used. MRST run fails with 200 bar of p_i.


## Exampe 2 ##
### Based on MRST example at: ###
https://bitbucket.org/mrst/mrst-autodiff/src/master/sequential/examples/compositionalHybridUpwind.m

GEOSX input file name: co2_brine_2d_vertical.xml

* Phase density calculations seems to be matching.
* Gravity segregation is more prominent in mrst solution as compared to geosx.
