Folder contents:

.oln	Board Outline
.smt	Soldermask Top
.stf	Stiffener Bottom
.top	Single copper layer

Other specifications:

Length L = 20mm
Pitch p = 1.00mm

Terminations: Exposed copper on the same side (not like in attached drawing where copper is exposed on opposite sides.)
	Termination 1: 
		S1 = 3mm exposed traces 
		d1 = 0 , i.e. no backing 
		for direct soldering to a PCB
	Termination 2: 
		S2 = 5mm exposed traces 
		d2 = 8mm backing 
		for a total thickness of ~0.30mm for inserting into a LIF/ZIF connector.

The cable will be bent by a narrow bend radius (~10mm) once at installation. In my tests I found this to work fine with the copper thickness ct = 0.035 products as the product in the attached drawing.

The current rating should be >= 1A like for most off-the-shelve FFCs with 1.00mm pitch.