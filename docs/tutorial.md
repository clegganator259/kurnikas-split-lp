# Tutorial

## Planning your build - what decisions you need to make
This build has several options that are available as you build this keyboard depending on your requirements for durabillity, battery life and aesthetics.

### Which case?
There are two case options, the full case and the sandwich case. The full case is a taller, however it has space for a larger battery, and the full pcb is enclosed.

The sandwich case is lower profile and lighter, however it is less durable, the pro micro is exposed and the sides are open to any water ingress. It can also only take a battery that is small enoguh to fit under the promicro.

### Which encoder?
There are two options for the rotary encoder, the ec11 or ec12. The ec11 has a push button, however ec11s tend to be higher profiler than the lowest profile ec12 encoders. ec12 encoders are identical but don't have the push button.
### LEDs?
This keyboard supports RGB background LEDs, however they have a huge impact on battery life. I would not advise using LEDs unless you are going for the full case with a large battery.
### Didodes

This pcb supports both through hole and surface mount diodes

### Battery choice
If you are choosing the sandwich case this must be one of the small 3.7v 110mah batteries that can fit under the pro micro.

For the full case, your main constraint is thickness, anything 5mm or under should fit, this includes old phone batteries if you wish to recycle.

I would advise choosing a capacity 500mah or greater so you can take advantage of the nice-nano's faster charging capabillity (500ma vs 100ma)

### Switches/Keycaps

The fun bit! Here you can choose any choc v1 low profile switches with matching keycaps.

## Ordering/printing the parts
### PCB

To get the PCB made, you can use the [zip file](production/PCBGerberFiles.zip) and send it to a PCB maker, you will need at least 2 copies of the PCB, but that won't be an issue as most fabs have a minimum order quantity of 5

### Sandwich case
You will need to print 2 copies of each file

### Full case
You will need to print 1 copy of each file

## Starting construction

I will give examples based on one side of the PCB but my advice would be to do each of these steps with both pcbs laid out side by side. The one exception for this will be in adding the pro-micros, as the right hand side will have to be installed upside down.
