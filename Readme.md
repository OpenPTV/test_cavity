# Test data for OpenPTV "cavity"

This is a set of data measured using 3D-PTV method and kept in a working folder suitable
for the OpenPTV software (www.openptv.net)

## This particular branch is for the PBI 

PBI is the "Particle Bureau of Investigation" - a new Python package that uses the 
OpenPTV library (`liboptv`), see  <https://github.com/yosefm/pbi> 

It uses YAML type of parameter files instead of .par files
used in Tcl/Tk and OpenPTV-Python versions, originated from the ETH Zurich code. This 
branch shall have both .par and YAML files compatible with PBI

## How to use it

    git clone https://github.com/openptv/test_cavity

Read PBI Readme for the next steps.     

## Source of this data and credits

This set of data is recorded at the Alex Liberzon laboratory at the School of Mechanical 
Engineering, Tel Aviv University, http://alex-lab.github.io by the team of Reut Elfassi, 
David Ratner and Mark Kreizer (all Master students at that time) 

The setup is a lid-driven cavity in a cubic cavity of a 1:1:1 ratio. The top lid is a 
plastic belt driving system constructed for our laboratory by the I.T.E.S. 
http://www.ites.co.il/index.html

The 4 cameras are located on two sides of the cavity (positive and negative 'z'). More 
details are available from the Reut Elfassi (Kramer) thesis. 


## License

`BY-SA` – [Attribution-ShareAlike](https://github.com/idleberg/Creative-Commons-Markdown/blob/master/4.0/by-sa.markdown)
