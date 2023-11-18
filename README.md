# home_heating_analysis
Some spreadsheets to analyze your home's power usage, especially for space heating.

The tables in each sheet of the heating analysis workbook are the utility bills for each house. If you look at the quantity used per day, you can choose a threshold which breaks those values into the heating season or out. In the non-heating season, the energy (for the two oil-fired houses) is just used for domestic hot water (DHW). If you take the amount of energy used to make DHW average off from the total, you can get the oil used for space heating. 

Once the energy usage for space heating is isolated, various calculations are done to compare it with using electric heat pumps for heating.

The electrical baseboard house is so well insulated, that getting away from the electric baseboards is not great economics.

The real killer in all this is domestic hot water. Mini-split heat pumps are popular in my region, and likely excellent for space heating. But, they won't remove the need for fuel oil. There is still a need a "primary heating source", and some replacement for heating domestic hot water.

The heat_loss_estimate sheet calculates heat loss for example structures. Enter the components of the structure (walls, attic, windows, doors), their thermal insulation value (in R-value, RSI or U-factor), their area and the temperature differential expected. The 26'x20' garage example shows some Imperial to metric conversion as required.
