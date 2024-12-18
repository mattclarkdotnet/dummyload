# A cheap 2ohm dummy load with 300W power handling

This started as a bit of a joke at audiosciencereview.com, but turned out to work quite well - see thread (https://www.audiosciencereview.com/forum/index.php?threads/silly-surface-mount-dummy-load-module.58077/).

Instead of using large wire wound resistors for dummy loads for amplifier testing, why not use cheap SMD resistors and boards?  This is the result.  a 1.97ohm board.  Yes that's a bit lower than 2ohms in oder to allow for other losses

## Key points

* Single sided aluminium for the board to improve thermal performance
* The heatsinks can be connected to the exposed aluminium on the back of the board, and also to the resistors on the front
* Use 4R7 2W 100ppm 1% resistors 19 parallel and 8 serial, for a total of 1.97ohms per board using 152 resistors. This is to allow a bit of headroom for connector and trace resistance
* Vertical height of 133mm to fit a 140x140mm ducted case
* 2mm wide (1mm internal diameter) thermal vias under each resistor to address the heat buildup from the resistor undersides.
* Using these heatsinks: https://www.aliexpress.com/item/32831608617.html as they are cheap and fit nicely
* M4 holes for cable connection - but note these are only on the top side, you must insulate any screws/bolts/washers on the underside due to the use of single sided aluminium board

## Power handling

These boards are intended to have heatsinks on both sides and be fitted into a 140x140mm ducted case with 140mm fans at each end to evacuate the heat.  Do not run them at high power without high volume forced cooling.  With heatsinks and forced air they can run at 200W/board continuously. 400W per board is easily done with heatsinks and forced air for up to 5 seconds.  Bare boards with no heatsinks or forced air are at your own risk.
