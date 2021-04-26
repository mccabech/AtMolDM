The form factor for a single electron ionised from the given configuration.
For the rates, you must multiply by the occupancy number.
eg for 2t, you should multiply by 6 (here we don't give separate files for 2tx, 2ty and 2tz as they will be identical after rotational averaging).

Outgoing electron wave functions are Coulomb waves. Form factors span the a reduced range compared to the other files, owing to the numerical challenge calculating with a Coulomb wave.

The Coulomb wave form factors span the range E = 1 eV to 109.648 eV and:
for 1a, q = 1 to 100 keV;
for 2a, q = 1 to 76.35 keV;
for 2t, q = 1 to 38.89 keV,
where q is the momentum transfer [in keV] and E is the electron kinetic energy [in keV]. 

These results are given by the functions fCH4CW1a, fCH4CW2a and fCH4CW2t.

At high q, we have also provided tables/functions that use a rescaled Plane wave ie we match the plane wave onto the Coulomb terms at the q values above, and use the rescaled Plane wave results above that value. These are accessed by the fCH4CWPW1a, fCH4CWPW2a and fCH4CWPW2t functions.

We have used the following Zeff values in our Coulomb wave calculation for methane
1a: 3.7
2a: 2.6
2t: 1.


