# Test data for OpenPTV "cavity"

This is a set of data measured using 3D-PTV method and kept in a working folder suitable
for the OpenPTV software (www.openptv.net)

## How to use it

    git clone https://github.com/openptv/test_cavity
    python pyptv_gui.py test_cavity
    

## Source of this data and credits

This set of data is recorded at the Alex Liberzon laboratory at the School of Mechanical 
Engineering, Tel Aviv University, http://turbulencelab.sites.tau.ac.il by the team of Reut Elfassi, 
David Ratner and Mark Kreizer (all Master students at that time) 

The setup is a lid-driven cavity in a cubic cavity of a 1:1:1 ratio. The top lid is a 
plastic belt driving system constructed for our laboratory by the I.T.E.S. 
http://www.ites.co.il/index.html

The 4 cameras are located on two sides of the cavity (positive and negative 'z'). More 
details are available from the Reut Elfassi (Kramer) thesis. 


## Working with plugins

Plugins is a system of extensions to PyPTV without the need to change the GUI

1. copy the `sequence_plugins.txt` and `tracking_plugins.txt` to the working folder
2. copy the `plugins/` directory to the working folder
3. modify the code in various plugins so it performs instead of the default sequence or default tracker
4. Open the GUI and Plugins -> Choose , then run the rest: Init -> Sequence 


Note, the specific branch `plugin_remback` requires installation of the `pip install rembg[cpu]` or `pip install rembg[gpu]`



## License

`BY-SA` – [Attribution-ShareAlike](https://github.com/idleberg/Creative-Commons-Markdown/blob/master/4.0/by-sa.markdown)
