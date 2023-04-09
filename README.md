# self_powered_active_load

Self powered active load based on the legendary LM10 Operational Amplifier and Voltage Reference IC originally designed by Bob Widlar.

![Schematics](self_powered_active_load_schematics.png)

Independently of the applied voltage, the circuit generates a constant voltage of 1.2V to supply the LM10 using the LM10 reference buffer. Thus, it is controlling its own supply voltage. This works down to an applied voltage of 2V. The load current control is done by the remaining precision operational amplifier. Four SWziklai-like output stages functions as final control elements. For the heat to be dissipated a appropriate heat sink is needed.

![Schematics](self_powered_active_load.png)
Circuit adopted from:
Joel Setton; Precision active load operates as low as 2V, EDN, 2005
