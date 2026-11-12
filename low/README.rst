.. _low_z:

*****
low_z
*****

This  case checks the evolutions of a 0.8 to 2 |Msun|, Z=1e-4 metallicity model from the pre-main sequence to core hydrogen depletion.

This test case has 2 parts. Click to see a larger version of a plot.

* Part 1 (``inlist_zams``) creates a 0.8 |Msun|, Z=1e-4 metallicity model and evolves it to the main sequence.

* Part 2 (``inlist_low_z``) continues the evolution until the mass fraction of hydrogen is less than 1e-6. A novelty of this inlist is exercising the custom opacity table controls desscribed at :ref:`kap/defaults:kap module controls`.


