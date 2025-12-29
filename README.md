### Elastic Beam Case

This case shows an elastic beam splitted into two segments. Each segment of the beam is simulated in OpenRadioss and coupled with preCICE. A pressure load is applied to s2, which causes some deformation.
s2 then sends the updated displacements to s1 via preCICE. s1, sends back the force (currently commented out).

### How to Run

You need to start two terminals. In each terminal you will need to run the OpenRadioss similution, e.g., call the engine. Alternatively, run the provided script in each terminal: `source start_s1.sh` in terminal 1 and `source start_s2.sh` in terminal 2. This will only work if run `radioss_setup.sh` previously, but first you have to update the `OPENRADIOSS_PATH` to the path to OpenRadioss in your system. 


### Disclaimer:
The original case was created by Elisa Santoro and Mathias Andrae
