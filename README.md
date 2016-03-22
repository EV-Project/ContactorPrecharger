# ContactorPrecharger
A simple precharge circuit for large battery packs

This precharger uses off-the-shelf parts available locally in most places, and should be fairly insensitive to part selection.

The 4n35 optocoupler is used to measure the voltage across the contactor.
The MOC3021 optotriac is used to permit current to pass through the charge resistors.
The high votlage NPN transistor prevents the triac from actually latching, and increases the current carrying capacity.

