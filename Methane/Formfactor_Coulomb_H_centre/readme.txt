The form factor for a single electron ionised from the given configuration.
For the rates, you must multiply by the occupancy number.
eg for 1t, you should multiply by 6 (here we don't give separate files for 1tx, 1ty and 1tz as they will be identical after rotational averaging).

Outgoing electron wave functions are Coulomb waves. Form factors span the a reduced range compared to the other files, owing to the numerical challenge calculating with a Coulomb wave (there is no spherical symmetry with molecular bound states that help to simplify the problem).

In this folder you can find rate centred on 1 hydrogen atom. Specifically we assume the continuum electron is centred on the position (1.185992115777, 1.185992115777, 1.185992115777) Bohr in our Cartesian coordinate system.

The Coulomb wave form factors span the range E = 1 eV to 109.648 eV and:
for 2a1, q = 1 to 76.35 keV;
for 1t2, q = 1 to 38.89 keV,
where q is the momentum transfer [in keV] and E is the electron kinetic energy [in keV]. 

We do not include off-centre results for 1a as this orbital is strongly centred on the central carbon atom, which serves as the origin in the main calculation.

These results are given by the functionsfCH4CW2a and fCH4CW1t.

We have also provided tables/functions that use a rescaled Plane wave at high q i.e. we match the plane wave onto the Coulomb terms at the q values above, and use the rescaled Plane wave results above that value. These are accessed by the fCH4CWPW1a, fCH4CWPW2a and fCH4CWPW1t functions.

We have used the following Zeff values in our Coulomb wave calculation for methane
2a: 2.6
1t: 1.


