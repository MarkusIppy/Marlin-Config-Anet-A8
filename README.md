# Marlin-Config-Anet-A8


For MKS 1.4 Board 

E1 set as 2nd Z output
4488 Stepper drivers 

Pinning changes required from stock ANET A8 connectors 

End stop switches Ground wire needs to be relocated to Pin2 

I have a normally closed Z_Min endstop as my original one is broken 

So for a complete stock setup change :
#define Z_MIN_ENDSTOP_INVERTING false
to 
#define Z_MIN_ENDSTOP_INVERTING true 




