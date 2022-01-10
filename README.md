This work relates to all the hardware designed especially for the automotives (12V or 24V system).

The two documents that have been shared give a complete picture of designing the power circuit  for the automotives and 
performing a step-down conversion from 12V or 24V to 5V, which is suitable for battery operated applications.

Power design for PCB board.pdf
Power design for PCB board.pdf describes in simple steps how to design a power circuit for any automotive.
While designing power circuit,following points need to be considered:-

  1)Reverse Polarity Protection - Either use a TI ic or diode or a MOSFET
  2)Transient Voltage Suppression - Use TVS diode
  3)External fuse - Either use any automotive standard fuse or PPTC
  4)Isolation
  5)Power supply filter - Use a LC filter either at the output or at the input of DC-DC converter.

Finally, I have come up with a circuit which contains least number of components and easy to implement on a PCB and can 
I have listed the appropriate part numbers and their specifications in the document.

DC-DC buck Selection.pdf
DC-DC buck Selection.pdf clearly describes the points considered for selecting the appropriate buck converter to 
step down the voltage from 12V to 5V 
I have selected TPS5420 and tested it for various scenarios. The test results are recorded in the document.

I have designed the complete power circuit and tested it in real-time in different automotives (of 12V/24v).

