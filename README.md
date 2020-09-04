# Voltage-Regulators

  
In this document we will show what are the different types of Voltage regulators and what are its basic different circuit structures.

First of all I would like to tell you that there are 3 types of voltage regulator which I am going to discuss about.First is the normal voltage regulator second is the SMPS and third is the LDO (Low dropout)

People I have seen find it difficult to understand the SMPS after they learnt the normal voltage regulators but if we see the circuit then we will see that both the circuit is 90 percent same only 3 components are added in an SMPS which is shown in Pic 1.

Lets discuss about the  NORMAL VOLTAGE REGULATOR Pic 1 fig a.

A voltage regulator has an op-Amp working in the non inverting mode and it has got a resistor divider working as a negative feedback.The input is also in series with a NPN transistor.Now what happens is that the output voltage will try to meet the difference bewtween the inputs of a op-Amp.That is how the voltage is regulated in the circuit.The reference voltage should be applied at the non inverting end of the amplifier.When my load increases then my difference between the reference and the input load increases and hence the transistor acting like an active resistor will make a bigger Vce drop as the ouput of the OPAMP will be more and hence the load voltage will decrease and vice versa.

Now coming to the SMPS or the switch mode voltage regulator as it is shown in the Pic 1 fig b.It is just that the inductor a diode and a filter capacitor is being used unlike the normal voltage regulator as shown in the Pic.Another important component which is added is the PWM or the pulse generator.So as a whole the two circuit works almost similarly with few alterations as discussed.

Now comes a little bit different type of a Voltage regulator which we call the LDO (Low drop out).It came after the above 2 regulators,so why did it come after all.Did the above 2 regulators had any diadvantages which was overcomed by this LDO.The answer is yes .In a normal voltage regulator the voltage drop is around 30 to 40 percent and they are not very easy to integrate in a chip due to its size.This 2 disadvantages are overcomed by the LDO

LDO

A LDO is just the same as that of a normal voltage regulator but the NPN transistor is replaced by a PNP transistor.Why? The only reason is that ,if we check the output charateristics of a PNP transistor we find that the saturation current is less than that of NPN transistor and hence the saturation voltage and if the saturation voltage is less then the voltage drop will be less and hence at the output we will get a higher voltage as the drop is very small .PIC 2.Other functions and working are similar to that of the normal regulator.


