# geosx_mrst

## Example 1 ##
### Based on MRST example at: ###
https://bitbucket.org/mrst/mrst-autodiff/src/master/compositional/examples/compositionalExample3DSixComponents.m

GEOSX input file name: input_5comp.xml  
JUTUL input file name: input_5comp.jl  
MRST input file name: input_5comp.m  
MRST solution file name: mrst_soln.png

* GEOSX has MAX_COMPONENT=5, and so last component of original example (i.e. 'C25-80') is not used.


## Example 2 ##
### Based on MRST example at: ###
https://bitbucket.org/mrst/mrst-autodiff/src/master/sequential/examples/compositionalHybridUpwind.m

GEOSX input file name: co2_brine_2d_vertical.xml

* Phase density calculations seems to be matching.
* Gravity segregation is more prominent in mrst solution as compared to geosx.
