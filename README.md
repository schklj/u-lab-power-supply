very impercise lab power supply, powered by a laptop power brick on LM2576S-ADJ buck converter IC with CC and CV/CC indication

# Specs 
* input voltage:        19.5 V
* min output voltage:   1.4 V
* max output voltage:   19.5 V
* output current:       2 A
* voltage ripple:       yes

# Issues
* when powered from a DC source with voltages other than 19.5 volts values for RV1 and R2 need to be recalculated according to LM2576S-ADJ datasheet
* L78L33 IC package should be TO-92, it will overheat otherwise
* when current is set to 2 amps and voltage is set to 19.5 volts CC/CV indicataion oscillates, becoming useless
