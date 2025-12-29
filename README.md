### Elastic Beam Case
This case shows an elastic beam splitted into two segments. Each segment of the beam is simulated in OpenRadioss and coupled with preCICE. A pressure load is applied to s2, which causes some deformation.
s2 then sends the updated displacements to s1 via preCICE. s1, sends back the force (currently commented out).

