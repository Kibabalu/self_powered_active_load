# self_powered_active_load

Self powered active load based on the legendary LM10 Operational Amplifier and Voltage Reference IC originally designed by Bob Widlar.

![Schematics](self_powered_active_load_schematics.png)

Independently of the applied voltage, the circuit composed by the transistors Q3, Q4, Q5, and Q6 generates a constant voltage of 1.2V to supply the LM10 using the LM10 reference buffer itself. Thus, it is controlling its own supply voltage. Q3, Q4, and Q5 arde composing a current mirror and Q6 is the final control element. This works down to an applied voltage of 2V. 

The main function of the circuit, the load current control, is done by the remaining precision operational amplifier. Four Sziklai-like output stages functions as final control elements for the current load.

For the heat to be dissipated a appropriate heat sink is needed. Here the Sink LA6 from Fischer with a length of 150mm is used.

The Circuit is mainly adopted from the source: Joel Setton; _Precision active load operates as low as 2V_, EDN, 2005

![Schematics](self_powered_active_load.png)

