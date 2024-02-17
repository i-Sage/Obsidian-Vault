---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
THE TRANSISTOR ^52pwNelP

PRINCIPLES OF SEMICONDUCTION ^Z7JYz6Gq

MECHANISM OF SEMI-CONDUCTION ^OEBv7jmE

As the name suggests a semiconducting material is one with a
conductivity lying between that of an insulator and that of a
conductor: That is to say one for which the resistivity lies
between, say           (a value typical for glass) and        
(approximately the value for copper). Typical values of the
resistivity of a semiconducting material lie between 1 and 100


Another essential characteristic of a semiconducting material is
that its electrical resistance decreases with increase in temperature
over a particular temperature range which is characteristic of the
semiconductor. The relationship between resistance and temperature
for a semiconductor could be written as: ^6BY1wp5o

where   is the resistance at an absolute temperature,
T, a and B are constants characteristic of the semi-
conductor material and e is the base of the natural
logarithms ^tVFNy1pU

Temperature ^4S8ri6Jn

resistance ^GF3kQ6ux

conductor ^CvN5hOaX

semi-conductor ^P5dn7rnv

The element most widely used in transistor manufacture is silicon. When pure
this element has very poor conductivity and are of little direct use in trans-
istor manufacture. But by the addition of a very small but controlled quan-
tity of a particular type of impurity the conductivity can be increased and
the material made suitable for use in transistors. 

    The behaviour of semiconductors can be explained in terms of atomic
theory. The atom is assumed to have a central nucleus which carries most
of the mass of the atom and has a positive charge. A number of electrons
carrying a negative charge revolve around the nucleus. The total number of
electrons revolving around a particular nucleus is sufficient to offset the 
positive nuclear charge, leaving the atom electrically neutral. ^eLRsUUlU

Nucleus
(Positively charged) ^xL9Evaqh

Electrons
(negatively charged) ^qvss8wZn

orbits of electrons ^n1Ej9m2i

THE PN-JUNCTION ^DQj5HUW4

The transistor is our most important example of an "active" component, a device that can
amplify, producing an output signal with more power in it than the input signal. The additional
power comes from an external source of power (the power supply, to be exact).

There are two major species of transistors: the BIPOLAR JUNCTION TRANSISTOR (BJTs)
which historically came first with their Nobel prize-winning invention in 1947 at Bell Laboratories.
The second is the FIELD-EFFECT TRANSISTOR (FETs), which is now the dominant species in
the digital world.. To give the coarest comparison, BJTs excel in accuracy and low noise,
whereas FETs excel in low power, high impedance, and high-current switching. ^VWYknmSl

FIRST TRANSISTOR MODEL: CURRENT AMPLIFIER ^kjKtOK4v

A bipolar transistor is a three-terminal device in which a small current applied to the base
controls a much larger current flowing between the collector and the emitter. It is available 
in two flavors (npn and pnp), which properties that meet the following rules for npn transistors
(for pnp simply reverse all polarities):

1.  POLARITY: The collector must be more positive that the emitter.
2. JUNCTIONS: The base-emitter and base-collector circuits behave like diodes in which a small
    current applied to the base controls a much larger current flowing between the collector and
    emitter. Normally the base-emitter diode is conducting, whereas the base collector diode is
    reverse-biased, ie., the applied voltage is in the opposite direction to easy current flow.
3. MAXIMUM RATINGS: Any given transistor has maximum values of                  that cannot
    be exceeded without costing the exceeder the price of a new transistor. There are also other
    limits, such as power dissipation       temperature and      that you must keep in mind.
4. CURRENT AMPLIFIER: When rules 1-3 are obeyed,   is roughly proportional to    and can be written
    as:


    where      the current gain (sometimes called     ) is typically about 100. Both     and     flow
    to the emitter.

NOTE: The collector current is not due to forward conduction of the base-collector diode; that diode
is reverse-biased. Just think of it as "transistor action."


    An important warning: The current gain beta is not a "good" transistor parameter; for instance,
its value can vary from 50 to 250 for different specimens of a given transistor type. It also depends
on the collector current, collector-to-emitter voltage, and temperature. A CIRCUIT THAT DEPENDS ON
A PARTICULAR VALUE FOR BETA IS A BAD CIRCUIT.


NOTE: The particular effect of rule 2. This means you can't go sticking an arbitrary voltage across the
base emitter terminals, because an enormous current will flow if the base is more positive than the emitter
by more than about 0.6v to 0.8v (forward diode drop). This rule also implies that an operating transistor
has ^NbFG3Cce

------- (i) ^f9AOQ3Iy

SOME BASIC TRANSISTOR CIRCUITS ^XMVlXqsN

TRANSISTOR SWITCH: This application, in which a small control current enables a much larger current to
flow in another circuit, is called a transistor switch. From the preceding rules it is easy to understand. When
the mechanical switch is open, there is no base current. So, from rule 4, there is no collector current. The 
load is off.
    When the switch is closed, the base rises to 0.6v (base-emitter diode is in forward conduction). The drop
across the base resistor is 9.4v, so the base current is 9.4mA. Blind application of rule 4 gives collector 
current of 940mA. That is wrong, because rule 4 holds only if rule 1 is obeyed: at a collector current of 100mA
the lamp has 10V across it. To get a higher current you would have to pull the collector below ground. A transistor
cannot do this, and the result is what's called SATURATION. The collector goes as close to ground as it can
and stays there. In this case, the lamp goes on, with its rated 10V across it.

    Also, transistor beta drops at low collector-to-base voltages, so some extra base current is necessary to
bring a transistor into full saturation. Incidentally, in a real circuit you would probably put a resistor from base
to ground (perhaps 10k) to make sure the base is at ground with the switch open. It wouldn't affect the ON
operation, because it would sink only 0.06MA from the base circuit. ^dEJU5I0v

10v, 0.1A
lamp ^J7409SEV

+10v ^Y3NDNN4o

1.0k ^WgxhwNG5

10k ^djN5L6UF

There are certain cautions to be observed when designing transistor switches:
1.  Choose the base resistor conservatively to get plenty of excess base current,
    especially when driving lamps, because of the reduced beta at low    . This is
    also a good idea for high-speed switching, because of capacitive effects and
    reduced beta at very high frequencies.
2. If the load swings below ground for some reason (eg, it is driven from ac or it 
    is inductive), use a diode in series with the collector (or a diode in reverse 
    direction to ground to prevent collector-base conduction on negative swings.
3. For inductive loads, protect the transistor with a diode across the load as 
    shown. Without the diode, the inductor will swing the collector to a large
    positive voltage when the switch is opened, most likely exceeding the collector
    emitter breakdown voltage as the inductor tries to maintain its "on" current
    from Vcc to the collector ^qIQL5ONZ

+Vcc ^fY8i5TU5

In high-side switching, the switch (transistor) is positioned between the positive supply voltage and the load. This
means that the switch controls the flow of current from the positive supply to the load. ^SxHRZ1Fu

HIGH-SIDE AND LOW-SIDE SWITCHING ^ruu66AXH

If we mildly stimulate a transistor, we find that the controlled current is more or less fixed regardless of how much
voltage we apply in the load. This is why the current/voltage characteristics curves tend to flatten with increasing
source voltages; whether BJT or MOSFET, the few charge carriers existing within the transistor to support this 
current are fixed in rate by the controlling stimulus.
    We see this current limiting behaviour for both BJTs(left) and MOSFETs(right) in the near-level portions of the
characteristic curves shown below. For the BJT we plot collector current Ic on the vertical axis and collector emitt-
er voltage (Vce) on the horizontal. For the MOSFET we plot drain current (Id) on the vertical axis and drain-source
voltage (Vds) on the horizontal. Each curve represents a different degree of fixed stimulus, Ib for the BJT and Vg
for the MOSFET: ^d9jPhwsF

TRANSISTOR SATURATION ^yNm17kSl

Ib = 0mA ^y9PlFdoK

Ib = 0.1mA ^wFuz3TM0

Ib = 0.2mA ^7yvlkmqY

Ib = 0.3mA ^k5kiHUDZ

Ib = 0.4mA ^Jee8STCQ

Ib = 0.5mA ^Ewk2RUih

VG = 0V ^eIeXDkeR

VG = 0.5V ^KV8Pgz3q

VG = 1.0V ^gomo1fRo

VG = 1.5V ^qQkkW5s0

VG = 25V ^25H65JUJ

VG = 30V ^rF1Xo9qL

    As we progress from left to right on the horizontal axis of each graph, increasing the applied voltage across each
transistor, we see a dramatic increase of current at first but then a "leveling" of current to a relatively fixed value,
that value dependent determined by the degree of stimulus. We call these nearly level portions of the graph the transi-
stors ACTIVE MODE where it more or less regulates current. An active transistor does not obey Ohm's Law.

    If our intention, however, is to use a BJT or a MOSFET as an on/off switch, we do not want the transistor to
be limiting current in any manner when we turn it on. What we'd rather have an "on" transistor do in any switching circuit
is behave as similar to a conductor as possible. Since we know transistors work by introducing charge carriers into 
formerly-depleted spaces, making a transistor behave as a good conductor means flooding its interior space with a 
plentiful supply of charge carriers. In other words, we need to saturate the transistor's interior with as many charge
carriers as we can to turn it fully "on".

    We see this SATURATION mode behavior in the near-vertical sections of the characteristic curves shown above:
Where the rise in current traces a steep upwards slope as voltage increases from zero.  ^mYvqBi5s

transistor behaves as a current regulator,
limiting current irrespective of the applied voltage ^HNmmjXTJ

ACTIVE MODE ^Cy94vBwc

SATURATION MODE

transistor behaves as a resistor, with 
current proportional to voltage ^sQqCDbDn

applied voltage (Vce or Vds) ^8BqPmvVF

resulting current (Ic or Id) ^flIqHw9w

    In saturated-mode transistors: we intentionally over-drive the transistor when turning it on in order to flood it's 
interior with a super-abundance of free charge carriers to make it as good an electrical conductor as it is capable of
being. This means we must design a saturated BJT switching circuit to force a base current significantly larger than
what the beta ratio would ordinarily require for the expected load current. Similarly, for a saturated MOSFET switching
circuit, we would design it to ensure we had more gate-source voltage than would ordinarily be necessary for the expec-
ted drain current.
    Compare the following BJT circuits, the left-hand circuit operating the transistor in its active mode and the right-
hand circuit operates the transistor in its saturated mode, each with the same source voltage and load resistance
values: ^qzc5WadQ

- ^u7zolONH

+ ^Rrh0JOaW

15V ^swJDTiF4

100k ^AbsDYJZB

1k ^FTaPoCm8

+ ^RPMdPyfv

- ^ZMCcX6tb

+ ^JtqAo99k

+ ^UNWKudPL

+ ^5u8gHeM1

- ^mAi3OKgH

- ^2NwjLfhg

- ^caJNeLuc

14.3 v ^tdmbDTtw

0.7 v ^Cpgx71Ur

10.71 v ^Nv9uHv4M

4.29 v ^Js9jo4qC

- ^4UB9NPPR

+ ^gdHvlQeG

15V ^iTTjHdZX

100k ^YZ7opqni

1k ^44zWQWcP

+ ^e5O7ZQlK

- ^8eP3BahE

+ ^PvFYzwnQ

+ ^FKRDeO2M

+ ^UBcJ8sb7

- ^zLjeL1wU

- ^5UDEduXl

- ^uAokdUy9

14.3 v ^ESK0Wnum

0.7 v ^UgBHJIlp

0.3 v ^hAiSpq0T

- ^U1NYa99L

+ ^165xkUij

15V ^oBXauMRN

100k ^JW5eQGEM

1k ^l9J7sZjG

+ ^Bb83L7n2

+ ^64m8QrmC

+ ^GQTlM1f3

+ ^NSiHzSFR

- ^xYCF4wiz

- ^iY54lAlh

- ^cQxha81A

14.3 v ^hM634Dao

0.7 v ^QZ3itHas

14.7v ^5WTneXTy

TRANSISTOR IN "ACTIVE" MODE ^kZIdWeGC

TRANSISTOR IN "SATURATED" MODE ^CIIAXexh

CALCULATIONS FOR SATURATION ^AtDP8JYf

1.  First, calculate maximum possible load current assuming the transistor is fully "on" (ie Vce = 0 volts) for a BJT and
Vds = 0 volts for a MOSFET). You may imagine the transistor being shorted and then calculate how much current the
load will allow for the given power supply voltage.

2. FOR A BJT, use the lowest advertised beta value shown in the transistor's datasheet to calculate the amount of
base current to ensure at least that much load current. Your circuit's base current should be made greater than this
to guarantee saturation just in case the real beta value is less than advertised, so consider this a low design limit.,
but still keeping in mind the maximum allowable transistor collector current. Choose a suitable base resistance and 
finally calculate the transistors power dissipation based on an assumed collector-emitter voltage drop of 0.3 V and 
determine how much heat-sinking is needed based on the datasheet thermal ratings.

3. For a MOSFET, research the transistor's turn-on or threshold gat-to-source voltage (Vgs (on)). Your circuit's gate
voltage will need to be more than this to guarantee saturation. So consider this a low design limit. Then research the
maximum allowable gate-source voltage. Your circuit's gate-source voltage will need to be less than this so as not to
harm the transistor, so consider this a high design limit. Design your circuit so that the amount of gate-source voltage
you impressupon the transistor is between these two design limit. Finally, calculate transistor power dissipation based on
the maximum possible load current and the transistor's Rds(on) parameter specified in the data sheet, and determine
how much heat-sinking the transistor will require (if any) ^c1seelS3

Load ^vGSYxb1o

+V ^o4TI0fiJ

High side switching ^eYHBiQbV

+ ^xfQPBU09

_ ^GJMQqmMM

transistor sources
current to the load ^dc9REdhB

Load ^hwPKcle9

+V ^PiUmBjUY

+ ^bslocdtl

_ ^DP2i0iJc

transistor sinks form
current from the load ^LYlaiYPK

Low-side switch ^SM0Av0cN

BJT SWITCH ^5QO6NEE2

Load ^aA9znVVn

+V ^Vw6d3hZs

+ ^LE33sASj

_ ^GZcHSbfE

transistor sources
current to the load ^nhmllACv

+V ^mv56UUqS

Load ^kcXZFyAg

+ ^RBwiYXFv

_ ^f17dAQae

transistor sinks form
current from the load ^AezTxbyK

+V ^1a48Ciwy

+V ^mbUaImGv

REMARKS: ^gMmFn5ZY

In either circuit, closing the mechanical switch causes the transistor to turn on and energize the load. However, the
load will not energize to the same degree in these two circuits. In the high-side circuit, the load will receive approx-
imately 0.7V less than +V when energized. But in the low side circuit the load will receive slightly more, about 0.3V
less than +V when energized. Recall that the base-emitter junction of a conducting transistor always drops approx-
imately 0.7V which is standard for a forward-biased silicon PN junction(Vbe). Turning our attention back to the sche-
matic diagrams, we see why the low-side switching configuration is able to achieve this saturation-on stat but the
high-side circuit cannot. In the high-side circuit the closed mechanical switch makes the base and collector terminals
electrically common to each other, which forces Vce to be exactly equal to Vbe, and thus Vce is approximately 0.7V.
However, in the low-side circuit, Vbe and Vce are not forced into equality, and so with proper sizing of the resistor
to saturate the transistor' base we may have Vbe = 0.7V and Vce = 0.3 volts or less. The freedom to satruate
the low-side NPN transistor but not the high-side NPN transistor means the low side-switched load can receive more
power and also that the low-side transistor will dissipate less power compared to the hiigh-side circuit Thus the low-
side switching configuration is more energy-efficient than the high-side using NPN transistors. An advantage of the
high-side NPN circuit, though is the ability to turn off faster than the low-side circuit for the same reason: a 
saturated BJT requires slightly more time to clear its base layer of all injected charge carriers that a non-satur-
ated BJT once current ceases through the base terminal. ^J629qwlP

PARALLELING TRANSISTORS ^RQAuwJk0

In applications where load current exceeds the current handling ability of any single transistor, multiple transistor
must be paralleled. Ideally, load current will be split into exactly equal portions according to the number of identical
transistors connected in parallel with each other. However, no two transistors are ever exactly the same and so we
must always expect some current imbalance. A prudent design choice is to parallel more transistors than strictly 
necessary assuming equal division of current, just in case one or more end up carrying more than their fair share.
    However, the problem may be more complicated than imperfect matches between paralleled transistors. If 
bipolar junction transistors are used, a phenomenon called THERMAL RUNAWAY may occur. The basis of thermal 
runaway is that BJTs are "minority carriers" devices and therefore drop less voltage (become more conductive) as
their temperature increases. Any imbalance between paralleled BJTs will result in the hotter transistor bearing more
of the load's current, which of course increases it's power dissipation and makes it hotter yet. The end-result is one
overheating transistor conducting most of the load current while the other transistors run cool. A clever solution to 
the problem of thermal runaway is to add resistances in series with the emitter terminal of each transistor so as to
introduce a (small) voltage drop proportional to its current. This additional resistance helps to solve the problem in
two different ways. First, the presence of additional resistances makes the transistor's effective collector-emmiter
resistance even seem smaller by  proportion, so that changes in the transistor's characteristics due to heat will
have less effect than before when the only factor determining current division was the effective collector-emitter
resistance of each transistor. The general strategy is know by the colorful name of SWAMPING OR BALLASTING.
Second the placement of said resistor on the emitter terminal of each transistor adds some negative feedback
which will  act tp decrease current if other factors makes that current increase. ^BkeSUzIo

load ^xHQblCQo

+V ^J6PH3VKz

--- ^FFZlkxem

swamping
resistors ^TDyMbbHz

interesting, FETs do not suffer from the problem of thermal runaway because their drain-source channel resistance naturally
increases with temperature, owing to the fact FETs are "majority carrier" devices. If one FET among a paralleled bank of
FETs happen to become hotter than the others, it automatically restricts current to force the others to carry more, and
thereby redistributes power dissipation to the other transistors ^1jkiyj3d

DARLINGTON AND SZIKLAI PAIR CONNECTIONS ^Xij5vgrP

Two common dual-transistor networks used to achieve greater amplification are the Darlington pair and Szikai pair.
Each contains two bipolar junction transistors, but while the Darlington pair uses same-type transistor the Sziklai
pair uses opposite-type transistors: ^qp4TBctF

Darlington Pair ^ohOJB8Ak

Sziklai Pair ^rHjzlNVI


# Embedded files
40b16b8aa5e21c55e4f7425bd854cb84ef653bcf: $$10^{12}\Omega-cm$$
d01c378f0e71883236fcff6b56cab900e8bdcb0a: $$10^{-6}\Omega-cm$$
bf04537a94eacf3b02ab8178e3fd0b57e1cfb8ba: $$\Omega-cm$$
d7c5262fa16cecbf93f6f473e9782f939f09285d: $$R_t = ae^{bT}$$
349f36bd4b842d3f25d56397c557d318b3f4c357: $$R_t$$
11af85614fd6fb7e94bc6fd190a8da653848513f: $$I_c, I_B \text{, and } V_{CE}$$
5a7f7463f9e793a69a1f025d09e6849fb46dcb2c: $$(I_CV_{CE})$$
729d3f7e3830330f4dcb4cf4d76a00e26529f552: $$V_{BE}$$
43ec797001f6b8783a2cfb080fa73afa236236ef: $$I_B$$
9acc1a622ecb86d789939eaa3c3ec7560bb5d85a: $$I_C$$
0581128948c5de27301f7a077fa7f05728bc32bc: $$I_C = h_{FE}I_B = \beta I_B$$
41e2c08ac54bbda9a669f01ba7476c4c3f6d6aa2: $$\beta$$
456efa608f72423418b4e3ba6d21d31e0e1e298f: $$h_{FE}$$
f19404b25b6e212b176fe8ee69cf63ae23afe540: $$I_C$$
b166ea421f231f3eb74c5ac1eff17c69a2e2c7eb: $$I_B$$
83af6afa1b6dbec1584aa89cfc91ad5dd0e6d8e3: $$V_B \approx V_E + 0.6V$$
7ad0fd3fe0d920c915e1bc331fee6a71462e2aa0: $$I_B = 143\mu A$$
43ee42987ef430b8b83601e828cb599a7ee3a42d: $$I_C = 4.29mA$$
9157261e76b3639744c5bfde6c409db044722a17: $$\beta = 30$$
4ed707dc498b1c8c839ccbc6216602fd4c5930f1: $$I_B = 143\mu A$$
e411680c9c312b4ac8ce918915cfe677d0a6b81c: $$I_C = 4.29mA$$
7dfc742828ed5a6857b746471eed2bb1ea85008b: $$\beta = 30$$

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.0.20",
	"elements": [
		{
			"type": "text",
			"version": 165,
			"versionNonce": 1788922095,
			"isDeleted": false,
			"id": "52pwNelP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -200.09145301429905,
			"y": -520.6185778621793,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 185.59982299804688,
			"height": 25,
			"seed": 1246388805,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414116,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "THE TRANSISTOR",
			"rawText": "THE TRANSISTOR",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "THE TRANSISTOR",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "line",
			"version": 168,
			"versionNonce": 1857643850,
			"isDeleted": false,
			"id": "vMzoLvYTZMvxWn555I5yc",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -210.2647318228928,
			"y": -497.2930926326871,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 203.7528076171875,
			"height": 0,
			"seed": 476885733,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320957,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					203.7528076171875,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 449,
			"versionNonce": 593478017,
			"isDeleted": false,
			"id": "Z7JYz6Gq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -329.7037995824606,
			"y": -236.92861340648776,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 210.0812530517578,
			"height": 14.591910687071438,
			"seed": 1137933859,
			"groupIds": [
				"XbhpC7RIjYzKPpmcctmhD"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414117,
			"link": null,
			"locked": false,
			"fontSize": 11.673528549657151,
			"fontFamily": 1,
			"text": "PRINCIPLES OF SEMICONDUCTION",
			"rawText": "PRINCIPLES OF SEMICONDUCTION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "PRINCIPLES OF SEMICONDUCTION",
			"lineHeight": 1.25,
			"baseline": 10
		},
		{
			"type": "text",
			"version": 480,
			"versionNonce": 1862115265,
			"isDeleted": false,
			"id": "OEBv7jmE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -332.07773914479395,
			"y": -213.33532715686152,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 129.01792907714844,
			"height": 8.954136512181579,
			"seed": 1122946563,
			"groupIds": [
				"oIWBt2vo180SCpyeukTjr",
				"XbhpC7RIjYzKPpmcctmhD"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707327045937,
			"link": null,
			"locked": false,
			"fontSize": 7.163309209745263,
			"fontFamily": 1,
			"text": "MECHANISM OF SEMI-CONDUCTION",
			"rawText": "MECHANISM OF SEMI-CONDUCTION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "MECHANISM OF SEMI-CONDUCTION",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 1393,
			"versionNonce": 1448140814,
			"isDeleted": false,
			"id": "6BY1wp5o",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -329.9117434997973,
			"y": -198.90988139830998,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 278.4420471191406,
			"height": 131.15875910502564,
			"seed": 1752669389,
			"groupIds": [
				"oIWBt2vo180SCpyeukTjr",
				"XbhpC7RIjYzKPpmcctmhD"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "ceHBZQkmd5S47lb4zixJN",
					"type": "arrow"
				}
			],
			"updated": 1707838502041,
			"link": null,
			"locked": false,
			"fontSize": 8.071308252616962,
			"fontFamily": 1,
			"text": "As the name suggests a semiconducting material is one with a\nconductivity lying between that of an insulator and that of a\nconductor: That is to say one for which the resistivity lies\nbetween, say           (a value typical for glass) and        \n(approximately the value for copper). Typical values of the\nresistivity of a semiconducting material lie between 1 and 100\n\n\nAnother essential characteristic of a semiconducting material is\nthat its electrical resistance decreases with increase in temperature\nover a particular temperature range which is characteristic of the\nsemiconductor. The relationship between resistance and temperature\nfor a semiconductor could be written as:",
			"rawText": "As the name suggests a semiconducting material is one with a\nconductivity lying between that of an insulator and that of a\nconductor: That is to say one for which the resistivity lies\nbetween, say           (a value typical for glass) and        \n(approximately the value for copper). Typical values of the\nresistivity of a semiconducting material lie between 1 and 100\n\n\nAnother essential characteristic of a semiconducting material is\nthat its electrical resistance decreases with increase in temperature\nover a particular temperature range which is characteristic of the\nsemiconductor. The relationship between resistance and temperature\nfor a semiconductor could be written as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "As the name suggests a semiconducting material is one with a\nconductivity lying between that of an insulator and that of a\nconductor: That is to say one for which the resistivity lies\nbetween, say           (a value typical for glass) and        \n(approximately the value for copper). Typical values of the\nresistivity of a semiconducting material lie between 1 and 100\n\n\nAnother essential characteristic of a semiconducting material is\nthat its electrical resistance decreases with increase in temperature\nover a particular temperature range which is characteristic of the\nsemiconductor. The relationship between resistance and temperature\nfor a semiconductor could be written as:",
			"lineHeight": 1.25,
			"baseline": 127
		},
		{
			"type": "line",
			"version": 238,
			"versionNonce": 1868831434,
			"isDeleted": false,
			"id": "wPJ5k1lHdBOZ-tvCpaMjf",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -333.413036922995,
			"y": -204.32217221133374,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 133.69490247599998,
			"height": 0,
			"seed": 932275843,
			"groupIds": [
				"oIWBt2vo180SCpyeukTjr",
				"XbhpC7RIjYzKPpmcctmhD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320957,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					133.69490247599998,
					0
				]
			]
		},
		{
			"type": "image",
			"version": 297,
			"versionNonce": 1016549078,
			"isDeleted": false,
			"id": "hCdjOmdJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -276.14254803920636,
			"y": -166.38745828255452,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.04240517492967,
			"height": 6.1727570107011465,
			"seed": 44240,
			"groupIds": [
				"oIWBt2vo180SCpyeukTjr",
				"XbhpC7RIjYzKPpmcctmhD"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320957,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "40b16b8aa5e21c55e4f7425bd854cb84ef653bcf",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 330,
			"versionNonce": 1986670986,
			"isDeleted": false,
			"id": "l7-2uVCw1h1t1qu9DHTnM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -107.50039722290974,
			"y": -166.9977628762351,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.76080230475053,
			"height": 6.041406728218515,
			"seed": 627209219,
			"groupIds": [
				"oIWBt2vo180SCpyeukTjr",
				"XbhpC7RIjYzKPpmcctmhD"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320958,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "d01c378f0e71883236fcff6b56cab900e8bdcb0a",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 311,
			"versionNonce": 565380118,
			"isDeleted": false,
			"id": "IvVJSxUY",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -83.02751581254716,
			"y": -146.4556315954922,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.979101583486763,
			"height": 4.26622749438669,
			"seed": 80147,
			"groupIds": [
				"oIWBt2vo180SCpyeukTjr",
				"XbhpC7RIjYzKPpmcctmhD"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320958,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "bf04537a94eacf3b02ab8178e3fd0b57e1cfb8ba",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 255,
			"versionNonce": 1241477194,
			"isDeleted": false,
			"id": "t9IGiXzS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -230.5330054295923,
			"y": -63.960731365349915,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 44.013171582773204,
			"height": 10.721157180419114,
			"seed": 83115,
			"groupIds": [
				"oIWBt2vo180SCpyeukTjr",
				"XbhpC7RIjYzKPpmcctmhD"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320958,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "d7c5262fa16cecbf93f6f473e9782f939f09285d",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 706,
			"versionNonce": 465006546,
			"isDeleted": false,
			"id": "tVFNy1pU",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -205.3252142998055,
			"y": -31.022669545695805,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 117.11454772949219,
			"height": 21.465602046058116,
			"seed": 682741891,
			"groupIds": [
				"_I_qcAx_7rFndpWg3yYCc",
				"oIWBt2vo180SCpyeukTjr",
				"XbhpC7RIjYzKPpmcctmhD"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502042,
			"link": null,
			"locked": false,
			"fontSize": 4.293120409211623,
			"fontFamily": 1,
			"text": "where   is the resistance at an absolute temperature,\nT, a and B are constants characteristic of the semi-\nconductor material and e is the base of the natural\nlogarithms",
			"rawText": "where   is the resistance at an absolute temperature,\nT, a and B are constants characteristic of the semi-\nconductor material and e is the base of the natural\nlogarithms",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "where   is the resistance at an absolute temperature,\nT, a and B are constants characteristic of the semi-\nconductor material and e is the base of the natural\nlogarithms",
			"lineHeight": 1.25,
			"baseline": 19
		},
		{
			"type": "image",
			"version": 348,
			"versionNonce": 1576982282,
			"isDeleted": false,
			"id": "Il7Gn1Gz",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -192.7648547238741,
			"y": -29.479062139845524,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.14189512104689,
			"height": 3.1064213407851673,
			"seed": 42409,
			"groupIds": [
				"_I_qcAx_7rFndpWg3yYCc",
				"oIWBt2vo180SCpyeukTjr",
				"XbhpC7RIjYzKPpmcctmhD"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320958,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "349f36bd4b842d3f25d56397c557d318b3f4c357",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 606,
			"versionNonce": 658863766,
			"isDeleted": false,
			"id": "ceHBZQkmd5S47lb4zixJN",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -320.2879762580495,
			"y": -1.7386566842741118,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 59.90558220612112,
			"seed": 202286787,
			"groupIds": [
				"qOR1cmUS23ERhXJN8J1gg",
				"XbhpC7RIjYzKPpmcctmhD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320958,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "6BY1wp5o",
				"focus": 0.9308741812429651,
				"gap": 6.10688340288911
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-59.90558220612112
				]
			]
		},
		{
			"type": "arrow",
			"version": 424,
			"versionNonce": 1927505354,
			"isDeleted": false,
			"id": "D_Jffo_ok5LtaDOvoaXYc",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -327.1623872467884,
			"y": -3.702771666878867,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 75.37301334300041,
			"height": 0,
			"seed": 1501133,
			"groupIds": [
				"qOR1cmUS23ERhXJN8J1gg",
				"XbhpC7RIjYzKPpmcctmhD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320958,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					75.37301334300041,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 429,
			"versionNonce": 734409686,
			"isDeleted": false,
			"id": "n_QtyFMwUnVVwhIETNSJc",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -320.2879762580495,
			"y": -21.982684834299356,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 65.21664496774955,
			"height": 17.474747352175726,
			"seed": 1689602499,
			"groupIds": [
				"qOR1cmUS23ERhXJN8J1gg",
				"XbhpC7RIjYzKPpmcctmhD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320958,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					65.21664496774955,
					-17.474747352175726
				]
			]
		},
		{
			"type": "line",
			"version": 562,
			"versionNonce": 29891722,
			"isDeleted": false,
			"id": "qZSZSfO_6AQ-oGPFm7RO2",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -293.52687200172164,
			"y": -54.636147717837105,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 31.91690266581643,
			"height": 30.689341061235154,
			"seed": 719429187,
			"groupIds": [
				"qOR1cmUS23ERhXJN8J1gg",
				"XbhpC7RIjYzKPpmcctmhD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320958,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.2275718641279796,
					17.922579994908588
				],
				[
					15.71293354023371,
					28.97074387130489
				],
				[
					31.91690266581643,
					30.689341061235154
				]
			]
		},
		{
			"type": "text",
			"version": 485,
			"versionNonce": 1941784854,
			"isDeleted": false,
			"id": "4S8ri6Jn",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -295.1278469083718,
			"y": -1.5038908965607263,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 16.648971557617188,
			"height": 3.3532835778038903,
			"seed": 19918285,
			"groupIds": [
				"qOR1cmUS23ERhXJN8J1gg",
				"XbhpC7RIjYzKPpmcctmhD"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320959,
			"link": null,
			"locked": false,
			"fontSize": 2.6826268622431124,
			"fontFamily": 1,
			"text": "Temperature",
			"rawText": "Temperature",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Temperature",
			"lineHeight": 1.25,
			"baseline": 2
		},
		{
			"type": "text",
			"version": 487,
			"versionNonce": 677903178,
			"isDeleted": false,
			"id": "GF3kQ6ux",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.71238898038469,
			"x": -333.00994212745167,
			"y": -35.08527603748668,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.597015380859375,
			"height": 3.3990609250049304,
			"seed": 517632579,
			"groupIds": [
				"qOR1cmUS23ERhXJN8J1gg",
				"XbhpC7RIjYzKPpmcctmhD"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320959,
			"link": null,
			"locked": false,
			"fontSize": 2.7192487400039442,
			"fontFamily": 1,
			"text": "resistance",
			"rawText": "resistance",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "resistance",
			"lineHeight": 1.25,
			"baseline": 2
		},
		{
			"type": "text",
			"version": 443,
			"versionNonce": 831893070,
			"isDeleted": false,
			"id": "CvN5hOaX",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -251.87205901064226,
			"y": -42.0478480468321,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.795791625976562,
			"height": 3.9424277033422452,
			"seed": 1499423949,
			"groupIds": [
				"qOR1cmUS23ERhXJN8J1gg",
				"XbhpC7RIjYzKPpmcctmhD"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502044,
			"link": null,
			"locked": false,
			"fontSize": 3.153942162673796,
			"fontFamily": 1,
			"text": "conductor",
			"rawText": "conductor",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "conductor",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 526,
			"versionNonce": 354288138,
			"isDeleted": false,
			"id": "P5dn7rnv",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -258.0845533827569,
			"y": -25.86656037861286,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.984161376953125,
			"height": 3.3775874328427906,
			"seed": 339853069,
			"groupIds": [
				"qOR1cmUS23ERhXJN8J1gg",
				"XbhpC7RIjYzKPpmcctmhD"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320959,
			"link": null,
			"locked": false,
			"fontSize": 2.7020699462742326,
			"fontFamily": 1,
			"text": "semi-conductor",
			"rawText": "semi-conductor",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "semi-conductor",
			"lineHeight": 1.25,
			"baseline": 2
		},
		{
			"type": "rectangle",
			"version": 295,
			"versionNonce": 1430420374,
			"isDeleted": false,
			"id": "23CI9UjGJxdxqpbFntIB0",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -342.76986508338445,
			"y": -221.04146021460338,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 300.82608736478386,
			"height": 446.6046025202827,
			"seed": 838761152,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1707241320959,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1286,
			"versionNonce": 513648018,
			"isDeleted": false,
			"id": "eLRsUUlU",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 2,
			"opacity": 100,
			"angle": 0,
			"x": -338.4015711626895,
			"y": 19.263278572345982,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 292.0780334472656,
			"height": 114.33786742829014,
			"seed": 1344124803,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502048,
			"link": null,
			"locked": false,
			"fontSize": 7.622524495219342,
			"fontFamily": 1,
			"text": "The element most widely used in transistor manufacture is silicon. When pure\nthis element has very poor conductivity and are of little direct use in trans-\nistor manufacture. But by the addition of a very small but controlled quan-\ntity of a particular type of impurity the conductivity can be increased and\nthe material made suitable for use in transistors. \n\n    The behaviour of semiconductors can be explained in terms of atomic\ntheory. The atom is assumed to have a central nucleus which carries most\nof the mass of the atom and has a positive charge. A number of electrons\ncarrying a negative charge revolve around the nucleus. The total number of\nelectrons revolving around a particular nucleus is sufficient to offset the \npositive nuclear charge, leaving the atom electrically neutral.",
			"rawText": "The element most widely used in transistor manufacture is silicon. When pure\nthis element has very poor conductivity and are of little direct use in trans-\nistor manufacture. But by the addition of a very small but controlled quan-\ntity of a particular type of impurity the conductivity can be increased and\nthe material made suitable for use in transistors. \n\n    The behaviour of semiconductors can be explained in terms of atomic\ntheory. The atom is assumed to have a central nucleus which carries most\nof the mass of the atom and has a positive charge. A number of electrons\ncarrying a negative charge revolve around the nucleus. The total number of\nelectrons revolving around a particular nucleus is sufficient to offset the \npositive nuclear charge, leaving the atom electrically neutral.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The element most widely used in transistor manufacture is silicon. When pure\nthis element has very poor conductivity and are of little direct use in trans-\nistor manufacture. But by the addition of a very small but controlled quan-\ntity of a particular type of impurity the conductivity can be increased and\nthe material made suitable for use in transistors. \n\n    The behaviour of semiconductors can be explained in terms of atomic\ntheory. The atom is assumed to have a central nucleus which carries most\nof the mass of the atom and has a positive charge. A number of electrons\ncarrying a negative charge revolve around the nucleus. The total number of\nelectrons revolving around a particular nucleus is sufficient to offset the \npositive nuclear charge, leaving the atom electrically neutral.",
			"lineHeight": 1.25,
			"baseline": 112
		},
		{
			"type": "ellipse",
			"version": 221,
			"versionNonce": 2111477974,
			"isDeleted": false,
			"id": "0HdBENz3GaQnH1xUvve6v",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -195.73708009806228,
			"y": 160.40287319144656,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 10.585740760414314,
			"height": 10.585740760414314,
			"seed": 2117394403,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320959,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 172,
			"versionNonce": 1431865226,
			"isDeleted": false,
			"id": "tX7j4Q_OvpadmXpH6GhES",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -192.41013276119406,
			"y": 149.81712400520234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3269473368682214,
			"height": 3.3269473368682383,
			"seed": 1174607885,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "JuggvV8FFf0KylIcqBGz7",
					"type": "arrow"
				}
			],
			"updated": 1707241320959,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 179,
			"versionNonce": 805113366,
			"isDeleted": false,
			"id": "ueF4gZIXQ4QmA0RCuF4pC",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -191.5037199035914,
			"y": 178.84414570901978,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3269473368682214,
			"height": 3.3269473368682383,
			"seed": 479503149,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "JuggvV8FFf0KylIcqBGz7",
					"type": "arrow"
				}
			],
			"updated": 1707241320959,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 248,
			"versionNonce": 615712330,
			"isDeleted": false,
			"id": "Xc9fFmPSRhmerNCP5U0Wp",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -205.11301493302744,
			"y": 151.63181182880152,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 29.035182120014326,
			"height": 29.763320427348177,
			"seed": 13211789,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320959,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 198,
			"versionNonce": 2023676758,
			"isDeleted": false,
			"id": "eYrx_bfBKo89AFwv4Wzjr",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -211.1620024311243,
			"y": 145.58283275653451,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 41.43561070402792,
			"height": 41.43561070402792,
			"seed": 762889443,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320959,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 229,
			"versionNonce": 164605194,
			"isDeleted": false,
			"id": "AT5pfKhuLEtUajLcjtoJV",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -191.80523401138436,
			"y": 143.4656829192857,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3269473368682214,
			"height": 3.3269473368682214,
			"seed": 1374532227,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320959,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 206,
			"versionNonce": 2115305622,
			"isDeleted": false,
			"id": "ESKG2k9EcX1X1qg07-qqS",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -171.87444329527145,
			"y": 164.35532464499022,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3269473368682214,
			"height": 3.3269473368682214,
			"seed": 102944173,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320959,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 206,
			"versionNonce": 1512668106,
			"isDeleted": false,
			"id": "uRXWFKIRe3ASHzgxgxeYq",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -192.02956751787278,
			"y": 186.44313201222448,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3269473368682214,
			"height": 3.3269473368682214,
			"seed": 1795728099,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320960,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 206,
			"versionNonce": 1410629078,
			"isDeleted": false,
			"id": "5nhc9P13Jt__3MH35SsP5",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -213.56517970092617,
			"y": 164.07922705289974,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3269473368682214,
			"height": 3.3269473368682214,
			"seed": 208380301,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320960,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 206,
			"versionNonce": 64713354,
			"isDeleted": false,
			"id": "VH3kZY261tAd8TI4u9n0H",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -206.93883749075587,
			"y": 150.82654263255924,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3269473368682214,
			"height": 3.3269473368682214,
			"seed": 1119319299,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320960,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 206,
			"versionNonce": 1337086742,
			"isDeleted": false,
			"id": "vbPe1ef2HDK0NrTDNDcKx",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -176.29200476871833,
			"y": 177.60800906533072,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3269473368682214,
			"height": 3.3269473368682214,
			"seed": 324274541,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320960,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 206,
			"versionNonce": 2040566090,
			"isDeleted": false,
			"id": "yhOqt6Of_6wJEEDhuI0YL",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -177.67249272917047,
			"y": 150.82654263255924,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3269473368682214,
			"height": 3.3269473368682214,
			"seed": 1816064803,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320960,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 208,
			"versionNonce": 1533247574,
			"isDeleted": false,
			"id": "OmBgNP7j3mbinxvKcypY0",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -208.5427194776696,
			"y": 177.5552970738721,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3269473368682214,
			"height": 3.3269473368682214,
			"seed": 1621067085,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320960,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 276,
			"versionNonce": 517199882,
			"isDeleted": false,
			"id": "jqIkgkTtNPzx1NxZKbI3f",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -217.51346036870066,
			"y": 139.53382840677793,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 54.13850130169112,
			"height": 55.15360150033608,
			"seed": 1553294275,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320960,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 211,
			"versionNonce": 1258096022,
			"isDeleted": false,
			"id": "dJ8akkL6iWlb6SUfqVZBG",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -203.5729628200419,
			"y": 140.44024126438063,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3269473368682214,
			"height": 3.3269473368682214,
			"seed": 2115455789,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320960,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 206,
			"versionNonce": 862996170,
			"isDeleted": false,
			"id": "4H99Y2amQzHCX4s8WSsYV",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -182.09005420261735,
			"y": 140.8870293173038,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3269473368682214,
			"height": 3.3269473368682214,
			"seed": 985757475,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320960,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 207,
			"versionNonce": 800318166,
			"isDeleted": false,
			"id": "uecSiYcdzXR6jkaIt-Ufk",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -179.32907828171304,
			"y": 190.58459589358088,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3269473368682214,
			"height": 3.3269473368682214,
			"seed": 381174093,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "3Gs9ez4Hcd0fF-SYITAGA",
					"type": "arrow"
				}
			],
			"updated": 1707241320960,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 206,
			"versionNonce": 1074847114,
			"isDeleted": false,
			"id": "asy6sdSF9AD7fUhgunfIo",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -203.34956879358032,
			"y": 190.03240070940004,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3269473368682214,
			"height": 3.3269473368682214,
			"seed": 656646467,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320960,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 207,
			"versionNonce": 740104214,
			"isDeleted": false,
			"id": "O_op2ICPV6Q1U4XC_Vaz3",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -166.62858904555333,
			"y": 175.12313073651694,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3269473368682214,
			"height": 3.3269473368682214,
			"seed": 1392824621,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "UiSGt3T0dMKe46T4UsHrQ",
					"type": "arrow"
				}
			],
			"updated": 1707241320960,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 206,
			"versionNonce": 32545866,
			"isDeleted": false,
			"id": "FPdlSnH90OKmUzVF-4eDt",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -166.62858904555333,
			"y": 155.52020169809646,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3269473368682214,
			"height": 3.3269473368682214,
			"seed": 1380415331,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320960,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 206,
			"versionNonce": 1210950998,
			"isDeleted": false,
			"id": "09bT4esZrY_sPqTz_i__2",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -218.8110339506443,
			"y": 173.46654518397432,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3269473368682214,
			"height": 3.3269473368682214,
			"seed": 706442509,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320960,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 207,
			"versionNonce": 1458209546,
			"isDeleted": false,
			"id": "BBuugeEsszRryZWPuWIFZ",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -217.15444839810175,
			"y": 151.9309330009209,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3269473368682214,
			"height": 3.3269473368682214,
			"seed": 1906407811,
			"groupIds": [
				"CoE9v_qh9rLF5JWf1U66p",
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "DIRfLDuD-TYuX2TzRrAgh",
					"type": "arrow"
				}
			],
			"updated": 1707241320960,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 670,
			"versionNonce": 1161464470,
			"isDeleted": false,
			"id": "JuggvV8FFf0KylIcqBGz7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -148.78266683027033,
			"y": 146.53221123669334,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 44.82647914968169,
			"height": 20.227899272984008,
			"seed": 370215245,
			"groupIds": [
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320961,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "xL9Evaqh",
				"focus": 1.0519168385683388,
				"gap": 6.931434803836424
			},
			"endBinding": {
				"elementId": "ueF4gZIXQ4QmA0RCuF4pC",
				"focus": -8.464802566532484,
				"gap": 12.591301158125187
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-44.82647914968169,
					20.227899272984008
				]
			]
		},
		{
			"type": "text",
			"version": 248,
			"versionNonce": 2144201057,
			"isDeleted": false,
			"id": "xL9Evaqh",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -141.8512320264339,
			"y": 143.95048697741083,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 29.323165893554688,
			"height": 7.7356624753022105,
			"seed": 597988301,
			"groupIds": [
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "JuggvV8FFf0KylIcqBGz7",
					"type": "arrow"
				}
			],
			"updated": 1707348414126,
			"link": null,
			"locked": false,
			"fontSize": 3.0942649901208843,
			"fontFamily": 1,
			"text": "Nucleus\n(Positively charged)",
			"rawText": "Nucleus\n(Positively charged)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Nucleus\n(Positively charged)",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "arrow",
			"version": 831,
			"versionNonce": 1912129494,
			"isDeleted": false,
			"id": "UiSGt3T0dMKe46T4UsHrQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -145.87276993675374,
			"y": 189.06375080607793,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 16.661753158064208,
			"height": 11.086093544000855,
			"seed": 550848739,
			"groupIds": [
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320961,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "qvss8wZn",
				"focus": -0.4056689640342864,
				"gap": 4.160803955427184
			},
			"endBinding": {
				"elementId": "O_op2ICPV6Q1U4XC_Vaz3",
				"focus": -0.21329383862291335,
				"gap": 1.0432560467850827
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-16.661753158064208,
					-11.086093544000855
				]
			]
		},
		{
			"type": "arrow",
			"version": 828,
			"versionNonce": 1555613834,
			"isDeleted": false,
			"id": "3Gs9ez4Hcd0fF-SYITAGA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -149.8659401033865,
			"y": 194.30006111737174,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 23.140198953635338,
			"height": 0.1555557997671986,
			"seed": 992736035,
			"groupIds": [
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320961,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "qvss8wZn",
				"focus": 0.5789298238889146,
				"gap": 8.153974122059935
			},
			"endBinding": {
				"elementId": "uecSiYcdzXR6jkaIt-Ufk",
				"focus": 1.121190696670594,
				"gap": 3.367141387900922
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-23.140198953635338,
					-0.1555557997671986
				]
			]
		},
		{
			"type": "text",
			"version": 345,
			"versionNonce": 2122145046,
			"isDeleted": false,
			"id": "qvss8wZn",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -141.71196598132656,
			"y": 192.48856937005567,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 38.16487121582031,
			"height": 9.828970612741742,
			"seed": 1529231907,
			"groupIds": [
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "UiSGt3T0dMKe46T4UsHrQ",
					"type": "arrow"
				},
				{
					"id": "3Gs9ez4Hcd0fF-SYITAGA",
					"type": "arrow"
				}
			],
			"updated": 1707241320961,
			"link": null,
			"locked": false,
			"fontSize": 3.931588245096697,
			"fontFamily": 1,
			"text": "Electrons\n(negatively charged)",
			"rawText": "Electrons\n(negatively charged)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Electrons\n(negatively charged)",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "arrow",
			"version": 351,
			"versionNonce": 946022218,
			"isDeleted": false,
			"id": "DIRfLDuD-TYuX2TzRrAgh",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -242.6737897577326,
			"y": 161.1410744661202,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 24.096758730678317,
			"height": 4.173192091665523,
			"seed": 433551459,
			"groupIds": [
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320961,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "n1Ej9m2i",
				"focus": 0.027916093191540634,
				"gap": 5.686201426110969
			},
			"endBinding": {
				"elementId": "BBuugeEsszRryZWPuWIFZ",
				"focus": -7.258653765970888,
				"gap": 10.45588519559359
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					24.096758730678317,
					4.173192091665523
				]
			]
		},
		{
			"type": "text",
			"version": 175,
			"versionNonce": 1346194006,
			"isDeleted": false,
			"id": "n1Ej9m2i",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -273.59497400211876,
			"y": 156.16258593337744,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 25.221237182617188,
			"height": 3.400211920066194,
			"seed": 1587921613,
			"groupIds": [
				"xmklfOK43kQ_QwtgOpUeD"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "DIRfLDuD-TYuX2TzRrAgh",
					"type": "arrow"
				}
			],
			"updated": 1707241320961,
			"link": null,
			"locked": false,
			"fontSize": 2.720169536052955,
			"fontFamily": 1,
			"text": "orbits of electrons",
			"rawText": "orbits of electrons",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "orbits of electrons",
			"lineHeight": 1.25,
			"baseline": 2
		},
		{
			"type": "text",
			"version": 186,
			"versionNonce": 459839791,
			"isDeleted": false,
			"id": "DQj5HUW4",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -94.90493121013188,
			"y": -548.6767916494947,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 132.74916076660156,
			"height": 17.294107454552382,
			"seed": 2069748739,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414128,
			"link": null,
			"locked": false,
			"fontSize": 13.835285963641905,
			"fontFamily": 1,
			"text": "THE PN-JUNCTION",
			"rawText": "THE PN-JUNCTION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "THE PN-JUNCTION",
			"lineHeight": 1.25,
			"baseline": 12
		},
		{
			"type": "text",
			"version": 1532,
			"versionNonce": 1604760718,
			"isDeleted": false,
			"id": "VWYknmSl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 5.4552911688939645,
			"y": -333.70523418453587,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 271.61566162109375,
			"height": 64.73281152729399,
			"seed": 1354778189,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502053,
			"link": null,
			"locked": false,
			"fontSize": 5.754027691315021,
			"fontFamily": 1,
			"text": "The transistor is our most important example of an \"active\" component, a device that can\namplify, producing an output signal with more power in it than the input signal. The additional\npower comes from an external source of power (the power supply, to be exact).\n\nThere are two major species of transistors: the BIPOLAR JUNCTION TRANSISTOR (BJTs)\nwhich historically came first with their Nobel prize-winning invention in 1947 at Bell Laboratories.\nThe second is the FIELD-EFFECT TRANSISTOR (FETs), which is now the dominant species in\nthe digital world.. To give the coarest comparison, BJTs excel in accuracy and low noise,\nwhereas FETs excel in low power, high impedance, and high-current switching.",
			"rawText": "The transistor is our most important example of an \"active\" component, a device that can\namplify, producing an output signal with more power in it than the input signal. The additional\npower comes from an external source of power (the power supply, to be exact).\n\nThere are two major species of transistors: the BIPOLAR JUNCTION TRANSISTOR (BJTs)\nwhich historically came first with their Nobel prize-winning invention in 1947 at Bell Laboratories.\nThe second is the FIELD-EFFECT TRANSISTOR (FETs), which is now the dominant species in\nthe digital world.. To give the coarest comparison, BJTs excel in accuracy and low noise,\nwhereas FETs excel in low power, high impedance, and high-current switching.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The transistor is our most important example of an \"active\" component, a device that can\namplify, producing an output signal with more power in it than the input signal. The additional\npower comes from an external source of power (the power supply, to be exact).\n\nThere are two major species of transistors: the BIPOLAR JUNCTION TRANSISTOR (BJTs)\nwhich historically came first with their Nobel prize-winning invention in 1947 at Bell Laboratories.\nThe second is the FIELD-EFFECT TRANSISTOR (FETs), which is now the dominant species in\nthe digital world.. To give the coarest comparison, BJTs excel in accuracy and low noise,\nwhereas FETs excel in low power, high impedance, and high-current switching.",
			"lineHeight": 1.25,
			"baseline": 63
		},
		{
			"type": "line",
			"version": 164,
			"versionNonce": 117791946,
			"isDeleted": false,
			"id": "kjrJxx-toKG5JG1CpY9Sx",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 41.90731816245079,
			"y": -535.3795611054363,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 144.87679902848743,
			"height": 0,
			"seed": 1969932195,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320961,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-144.87679902848743,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 386,
			"versionNonce": 1521951570,
			"isDeleted": false,
			"id": "kjKtOK4v",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 7.214672910425648,
			"y": -259.5523988940197,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 169.59228515625,
			"height": 8.087454488412709,
			"seed": 1342979821,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502054,
			"link": null,
			"locked": false,
			"fontSize": 6.469963590730167,
			"fontFamily": 1,
			"text": "FIRST TRANSISTOR MODEL: CURRENT AMPLIFIER",
			"rawText": "FIRST TRANSISTOR MODEL: CURRENT AMPLIFIER",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "FIRST TRANSISTOR MODEL: CURRENT AMPLIFIER",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "line",
			"version": 106,
			"versionNonce": 1284715402,
			"isDeleted": false,
			"id": "nmnvTMKk_hqIyVwIFxlGj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 5.59853980075431,
			"y": -252.82911069453203,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 173.3953507116136,
			"height": 0,
			"seed": 1508688621,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320961,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					173.3953507116136,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 3071,
			"versionNonce": 387564833,
			"isDeleted": false,
			"id": "NbFG3Cce",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 6.324895161955382,
			"y": -248.72137476165338,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 308.8247985839844,
			"height": 246.44938280252802,
			"seed": 1450286883,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414135,
			"link": null,
			"locked": false,
			"fontSize": 5.798809007118306,
			"fontFamily": 1,
			"text": "A bipolar transistor is a three-terminal device in which a small current applied to the base\ncontrols a much larger current flowing between the collector and the emitter. It is available \nin two flavors (npn and pnp), which properties that meet the following rules for npn transistors\n(for pnp simply reverse all polarities):\n\n1.  POLARITY: The collector must be more positive that the emitter.\n2. JUNCTIONS: The base-emitter and base-collector circuits behave like diodes in which a small\n    current applied to the base controls a much larger current flowing between the collector and\n    emitter. Normally the base-emitter diode is conducting, whereas the base collector diode is\n    reverse-biased, ie., the applied voltage is in the opposite direction to easy current flow.\n3. MAXIMUM RATINGS: Any given transistor has maximum values of                  that cannot\n    be exceeded without costing the exceeder the price of a new transistor. There are also other\n    limits, such as power dissipation       temperature and      that you must keep in mind.\n4. CURRENT AMPLIFIER: When rules 1-3 are obeyed,   is roughly proportional to    and can be written\n    as:\n\n\n    where      the current gain (sometimes called     ) is typically about 100. Both     and     flow\n    to the emitter.\n\nNOTE: The collector current is not due to forward conduction of the base-collector diode; that diode\nis reverse-biased. Just think of it as \"transistor action.\"\n\n\n    An important warning: The current gain beta is not a \"good\" transistor parameter; for instance,\nits value can vary from 50 to 250 for different specimens of a given transistor type. It also depends\non the collector current, collector-to-emitter voltage, and temperature. A CIRCUIT THAT DEPENDS ON\nA PARTICULAR VALUE FOR BETA IS A BAD CIRCUIT.\n\n\nNOTE: The particular effect of rule 2. This means you can't go sticking an arbitrary voltage across the\nbase emitter terminals, because an enormous current will flow if the base is more positive than the emitter\nby more than about 0.6v to 0.8v (forward diode drop). This rule also implies that an operating transistor\nhas",
			"rawText": "A bipolar transistor is a three-terminal device in which a small current applied to the base\ncontrols a much larger current flowing between the collector and the emitter. It is available \nin two flavors (npn and pnp), which properties that meet the following rules for npn transistors\n(for pnp simply reverse all polarities):\n\n1.  POLARITY: The collector must be more positive that the emitter.\n2. JUNCTIONS: The base-emitter and base-collector circuits behave like diodes in which a small\n    current applied to the base controls a much larger current flowing between the collector and\n    emitter. Normally the base-emitter diode is conducting, whereas the base collector diode is\n    reverse-biased, ie., the applied voltage is in the opposite direction to easy current flow.\n3. MAXIMUM RATINGS: Any given transistor has maximum values of                  that cannot\n    be exceeded without costing the exceeder the price of a new transistor. There are also other\n    limits, such as power dissipation       temperature and      that you must keep in mind.\n4. CURRENT AMPLIFIER: When rules 1-3 are obeyed,   is roughly proportional to    and can be written\n    as:\n\n\n    where      the current gain (sometimes called     ) is typically about 100. Both     and     flow\n    to the emitter.\n\nNOTE: The collector current is not due to forward conduction of the base-collector diode; that diode\nis reverse-biased. Just think of it as \"transistor action.\"\n\n\n    An important warning: The current gain beta is not a \"good\" transistor parameter; for instance,\nits value can vary from 50 to 250 for different specimens of a given transistor type. It also depends\non the collector current, collector-to-emitter voltage, and temperature. A CIRCUIT THAT DEPENDS ON\nA PARTICULAR VALUE FOR BETA IS A BAD CIRCUIT.\n\n\nNOTE: The particular effect of rule 2. This means you can't go sticking an arbitrary voltage across the\nbase emitter terminals, because an enormous current will flow if the base is more positive than the emitter\nby more than about 0.6v to 0.8v (forward diode drop). This rule also implies that an operating transistor\nhas",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "A bipolar transistor is a three-terminal device in which a small current applied to the base\ncontrols a much larger current flowing between the collector and the emitter. It is available \nin two flavors (npn and pnp), which properties that meet the following rules for npn transistors\n(for pnp simply reverse all polarities):\n\n1.  POLARITY: The collector must be more positive that the emitter.\n2. JUNCTIONS: The base-emitter and base-collector circuits behave like diodes in which a small\n    current applied to the base controls a much larger current flowing between the collector and\n    emitter. Normally the base-emitter diode is conducting, whereas the base collector diode is\n    reverse-biased, ie., the applied voltage is in the opposite direction to easy current flow.\n3. MAXIMUM RATINGS: Any given transistor has maximum values of                  that cannot\n    be exceeded without costing the exceeder the price of a new transistor. There are also other\n    limits, such as power dissipation       temperature and      that you must keep in mind.\n4. CURRENT AMPLIFIER: When rules 1-3 are obeyed,   is roughly proportional to    and can be written\n    as:\n\n\n    where      the current gain (sometimes called     ) is typically about 100. Both     and     flow\n    to the emitter.\n\nNOTE: The collector current is not due to forward conduction of the base-collector diode; that diode\nis reverse-biased. Just think of it as \"transistor action.\"\n\n\n    An important warning: The current gain beta is not a \"good\" transistor parameter; for instance,\nits value can vary from 50 to 250 for different specimens of a given transistor type. It also depends\non the collector current, collector-to-emitter voltage, and temperature. A CIRCUIT THAT DEPENDS ON\nA PARTICULAR VALUE FOR BETA IS A BAD CIRCUIT.\n\n\nNOTE: The particular effect of rule 2. This means you can't go sticking an arbitrary voltage across the\nbase emitter terminals, because an enormous current will flow if the base is more positive than the emitter\nby more than about 0.6v to 0.8v (forward diode drop). This rule also implies that an operating transistor\nhas",
			"lineHeight": 1.25,
			"baseline": 244
		},
		{
			"type": "image",
			"version": 219,
			"versionNonce": 934818378,
			"isDeleted": false,
			"id": "fWh72Acc",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 204.40266993538998,
			"y": -176.54600375638574,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 41.12308384356196,
			"height": 5.62366958544437,
			"seed": 2097,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320961,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "11af85614fd6fb7e94bc6fd190a8da653848513f",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 195,
			"versionNonce": 1691512662,
			"isDeleted": false,
			"id": "coLJ69Mc",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 109.90130099693602,
			"y": -160.9114657955548,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.416603565216022,
			"height": 4.823059448829052,
			"seed": 47376,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320961,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "5a7f7463f9e793a69a1f025d09e6849fb46dcb2c",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 113,
			"versionNonce": 1531926794,
			"isDeleted": false,
			"id": "QZn4p2DY",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 179.5552809919699,
			"y": -160.81190878594452,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9.593161843039782,
			"height": 4.496794613924898,
			"seed": 50124,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320962,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "729d3f7e3830330f4dcb4cf4d76a00e26529f552",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 85,
			"versionNonce": 1186337942,
			"isDeleted": false,
			"id": "ORQGb2kE",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 159.654470923666,
			"y": -152.6485991684684,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.854658647017066,
			"height": 4.622098931855579,
			"seed": 41013,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320962,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "43ec797001f6b8783a2cfb080fa73afa236236ef",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 165,
			"versionNonce": 919840714,
			"isDeleted": false,
			"id": "nTNqBdOk",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 240.11989173332518,
			"y": -153.84364533324106,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7.049693714488651,
			"height": 5.565547669333146,
			"seed": 88417,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320962,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "9acc1a622ecb86d789939eaa3c3ec7560bb5d85a",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 180,
			"versionNonce": 259199446,
			"isDeleted": false,
			"id": "5h75IOMI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 91.57483260313307,
			"y": -142.1032000083689,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 103.59159346161508,
			"height": 11.275275478815246,
			"seed": 48724,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320962,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "0581128948c5de27301f7a077fa7f05728bc32bc",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 120,
			"versionNonce": 1411996015,
			"isDeleted": false,
			"id": "f9AOQ3Iy",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 207.97362274505016,
			"y": -141.59552739588082,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 49.6739501953125,
			"height": 14.294898244166301,
			"seed": 387650477,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414137,
			"link": null,
			"locked": false,
			"fontSize": 11.43591859533304,
			"fontFamily": 1,
			"text": "------- (i)",
			"rawText": "------- (i)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "------- (i)",
			"lineHeight": 1.25,
			"baseline": 10
		},
		{
			"type": "image",
			"version": 153,
			"versionNonce": 1243506454,
			"isDeleted": false,
			"id": "IBzONmuW",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 36.94945972596071,
			"y": -125.91382123074888,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.5239156087239705,
			"height": 5.79903609664353,
			"seed": 1232,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320962,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "41e2c08ac54bbda9a669f01ba7476c4c3f6d6aa2",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 175,
			"versionNonce": 984595786,
			"isDeleted": false,
			"id": "bQ41Da2a",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 150.28409714883514,
			"y": -125.93719367777695,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11.2196295441319,
			"height": 5.428853005225113,
			"seed": 71677,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320962,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "456efa608f72423418b4e3ba6d21d31e0e1e298f",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 101,
			"versionNonce": 1462572118,
			"isDeleted": false,
			"id": "zepDkM6U",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 274.8392142483751,
			"y": -128.54366044670874,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9.749567909846222,
			"height": 7.6970272972470175,
			"seed": 27506,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320962,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "f19404b25b6e212b176fe8ee69cf63ae23afe540",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 144,
			"versionNonce": 1293779978,
			"isDeleted": false,
			"id": "7e2N3i1n",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 249.80048598851644,
			"y": -126.45711550158231,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8.428098648313476,
			"height": 6.653762090773797,
			"seed": 10125,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320962,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "b166ea421f231f3eb74c5ac1eff17c69a2e2c7eb",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 178,
			"versionNonce": 1081350550,
			"isDeleted": false,
			"id": "prhxwVaQ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 20.921969709568387,
			"y": -9.69026726614743,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 54.15289306640628,
			"height": 6.3960109920952295,
			"seed": 82508,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320962,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "83af6afa1b6dbec1584aa89cfc91ad5dd0e6d8e3",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 450,
			"versionNonce": 1134850762,
			"isDeleted": false,
			"id": "XMVlXqsN",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4.506388324273786,
			"y": 27.071283456137564,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 132.37579345703125,
			"height": 8.541675401770245,
			"seed": 133138893,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320962,
			"link": null,
			"locked": false,
			"fontSize": 6.833340321416196,
			"fontFamily": 1,
			"text": "SOME BASIC TRANSISTOR CIRCUITS",
			"rawText": "SOME BASIC TRANSISTOR CIRCUITS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "SOME BASIC TRANSISTOR CIRCUITS",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 1688,
			"versionNonce": 308498703,
			"isDeleted": false,
			"id": "dEJU5I0v",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 6.166008927199364,
			"y": 42.1265973833074,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 329.822509765625,
			"height": 107.10131570051306,
			"seed": 2129573155,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707327046175,
			"link": null,
			"locked": false,
			"fontSize": 5.712070170694029,
			"fontFamily": 1,
			"text": "TRANSISTOR SWITCH: This application, in which a small control current enables a much larger current to\nflow in another circuit, is called a transistor switch. From the preceding rules it is easy to understand. When\nthe mechanical switch is open, there is no base current. So, from rule 4, there is no collector current. The \nload is off.\n    When the switch is closed, the base rises to 0.6v (base-emitter diode is in forward conduction). The drop\nacross the base resistor is 9.4v, so the base current is 9.4mA. Blind application of rule 4 gives collector \ncurrent of 940mA. That is wrong, because rule 4 holds only if rule 1 is obeyed: at a collector current of 100mA\nthe lamp has 10V across it. To get a higher current you would have to pull the collector below ground. A transistor\ncannot do this, and the result is what's called SATURATION. The collector goes as close to ground as it can\nand stays there. In this case, the lamp goes on, with its rated 10V across it.\n\n    Also, transistor beta drops at low collector-to-base voltages, so some extra base current is necessary to\nbring a transistor into full saturation. Incidentally, in a real circuit you would probably put a resistor from base\nto ground (perhaps 10k) to make sure the base is at ground with the switch open. It wouldn't affect the ON\noperation, because it would sink only 0.06MA from the base circuit.",
			"rawText": "TRANSISTOR SWITCH: This application, in which a small control current enables a much larger current to\nflow in another circuit, is called a transistor switch. From the preceding rules it is easy to understand. When\nthe mechanical switch is open, there is no base current. So, from rule 4, there is no collector current. The \nload is off.\n    When the switch is closed, the base rises to 0.6v (base-emitter diode is in forward conduction). The drop\nacross the base resistor is 9.4v, so the base current is 9.4mA. Blind application of rule 4 gives collector \ncurrent of 940mA. That is wrong, because rule 4 holds only if rule 1 is obeyed: at a collector current of 100mA\nthe lamp has 10V across it. To get a higher current you would have to pull the collector below ground. A transistor\ncannot do this, and the result is what's called SATURATION. The collector goes as close to ground as it can\nand stays there. In this case, the lamp goes on, with its rated 10V across it.\n\n    Also, transistor beta drops at low collector-to-base voltages, so some extra base current is necessary to\nbring a transistor into full saturation. Incidentally, in a real circuit you would probably put a resistor from base\nto ground (perhaps 10k) to make sure the base is at ground with the switch open. It wouldn't affect the ON\noperation, because it would sink only 0.06MA from the base circuit.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "TRANSISTOR SWITCH: This application, in which a small control current enables a much larger current to\nflow in another circuit, is called a transistor switch. From the preceding rules it is easy to understand. When\nthe mechanical switch is open, there is no base current. So, from rule 4, there is no collector current. The \nload is off.\n    When the switch is closed, the base rises to 0.6v (base-emitter diode is in forward conduction). The drop\nacross the base resistor is 9.4v, so the base current is 9.4mA. Blind application of rule 4 gives collector \ncurrent of 940mA. That is wrong, because rule 4 holds only if rule 1 is obeyed: at a collector current of 100mA\nthe lamp has 10V across it. To get a higher current you would have to pull the collector below ground. A transistor\ncannot do this, and the result is what's called SATURATION. The collector goes as close to ground as it can\nand stays there. In this case, the lamp goes on, with its rated 10V across it.\n\n    Also, transistor beta drops at low collector-to-base voltages, so some extra base current is necessary to\nbring a transistor into full saturation. Incidentally, in a real circuit you would probably put a resistor from base\nto ground (perhaps 10k) to make sure the base is at ground with the switch open. It wouldn't affect the ON\noperation, because it would sink only 0.06MA from the base circuit.",
			"lineHeight": 1.25,
			"baseline": 105
		},
		{
			"type": "line",
			"version": 413,
			"versionNonce": 283085194,
			"isDeleted": false,
			"id": "frvrCx-5VzazfBcYcKJJd",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 133.68840315179526,
			"y": 180.58796203077287,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.1515025401532162,
			"height": 6.363495083351788,
			"seed": 874668323,
			"groupIds": [
				"RlgVHILVBT07tRzlQ0wUB",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320962,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.1515025401532162,
					6.363495083351788
				]
			]
		},
		{
			"type": "line",
			"version": 425,
			"versionNonce": 366947350,
			"isDeleted": false,
			"id": "T5Rgp6qEvbFTdK3PJl3dt",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 126.3183704379559,
			"y": 184.01869288821493,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8.33313907589123,
			"height": 0.15151641147167005,
			"seed": 538985667,
			"groupIds": [
				"RlgVHILVBT07tRzlQ0wUB",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320962,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.33313907589123,
					-0.15151641147167005
				]
			]
		},
		{
			"type": "line",
			"version": 431,
			"versionNonce": 470403146,
			"isDeleted": false,
			"id": "dbaH-8J34lXcwxDnpvJrJ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 127.07591781701822,
			"y": 183.8671834124025,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 3.6362967760909046,
			"height": 0.15151641147167005,
			"seed": 98612323,
			"groupIds": [
				"RlgVHILVBT07tRzlQ0wUB",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320962,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					3.6362967760909046,
					0.15151641147167005
				]
			]
		},
		{
			"type": "line",
			"version": 421,
			"versionNonce": 1485650262,
			"isDeleted": false,
			"id": "tVvm04DM-UuOP6kxiOz5f",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 127.00101121336942,
			"y": 184.17106090177373,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.9090707261931127,
			"height": 0,
			"seed": 624046083,
			"groupIds": [
				"RlgVHILVBT07tRzlQ0wUB",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320962,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.9090707261931127,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 950,
			"versionNonce": 754855690,
			"isDeleted": false,
			"id": "g-FJTN1Sjnj39MJf_Kanm",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.1415926535897913,
			"x": 192.2621392446935,
			"y": 168.4831646982065,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.70563496510734,
			"height": 8.866945750373805,
			"seed": 1572129347,
			"groupIds": [
				"JRTuIZgbKTBnoXdxR16ab",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320963,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.796865626112219,
					-0.25334892806530385
				],
				[
					-4.233105517234365,
					-5.8268513899073175
				],
				[
					-5.744918041064016,
					2.786745432401185
				],
				[
					-7.785877405261414,
					-5.320165130816357
				],
				[
					-8.919743718704405,
					3.040094360466488
				],
				[
					-10.96070308290181,
					-4.8134904687650355
				],
				[
					-11.641029791538372,
					0.5066746620513194
				],
				[
					-16.70563496510734,
					0.2533373310256597
				]
			]
		},
		{
			"type": "line",
			"version": 754,
			"versionNonce": 1283956374,
			"isDeleted": false,
			"id": "k_n8SrQ6FBKmsx34ywylY",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 166.28273667058258,
			"y": 175.9178922400776,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.2718898236847025,
			"height": 0,
			"seed": 199686275,
			"groupIds": [
				"jp79t2OaZvh3b9HABpxzW",
				"x1nzmPXlspCbw8ePRiA-w",
				"U_ZHYlJIefJ2IWJH_8zHY",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320963,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.2718898236847025,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 791,
			"versionNonce": 1480048074,
			"isDeleted": false,
			"id": "kE6dh5tiBxBqhA0RRKOpt",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 168.8848346409927,
			"y": 173.502409838648,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 10.357164078389308,
			"seed": 1981476899,
			"groupIds": [
				"jp79t2OaZvh3b9HABpxzW",
				"x1nzmPXlspCbw8ePRiA-w",
				"U_ZHYlJIefJ2IWJH_8zHY",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320963,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					10.357164078389308
				]
			]
		},
		{
			"type": "line",
			"version": 828,
			"versionNonce": 914578390,
			"isDeleted": false,
			"id": "uqi0qrWJ1ydVcaQ6uWBV8",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 169.96012765048832,
			"y": 182.9361793764099,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.949864177213169,
			"height": 3.3590802416397203,
			"seed": 1378808771,
			"groupIds": [
				"jp79t2OaZvh3b9HABpxzW",
				"x1nzmPXlspCbw8ePRiA-w",
				"U_ZHYlJIefJ2IWJH_8zHY",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320963,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.949864177213169,
					-3.3590802416397203
				]
			]
		},
		{
			"type": "line",
			"version": 803,
			"versionNonce": 1792111754,
			"isDeleted": false,
			"id": "kbLFw6CZo_bzryb0gJv1u",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 161.34026884214077,
			"y": 180.86036006852072,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 5.557502676208944,
			"seed": 4293475,
			"groupIds": [
				"jp79t2OaZvh3b9HABpxzW",
				"x1nzmPXlspCbw8ePRiA-w",
				"U_ZHYlJIefJ2IWJH_8zHY",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320963,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					5.557502676208944
				]
			]
		},
		{
			"type": "line",
			"version": 780,
			"versionNonce": 2090168598,
			"isDeleted": false,
			"id": "xOp52Ospo-kgP9igf5tfm",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 176.5511668754869,
			"y": 186.3637901919524,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 5.449357570655802,
			"seed": 1486954243,
			"groupIds": [
				"jp79t2OaZvh3b9HABpxzW",
				"x1nzmPXlspCbw8ePRiA-w",
				"U_ZHYlJIefJ2IWJH_8zHY",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320963,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-5.449357570655802
				]
			]
		},
		{
			"type": "line",
			"version": 898,
			"versionNonce": 1451643722,
			"isDeleted": false,
			"id": "xCYyvkvWMNwt9incOHo5l",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 162.86933844679595,
			"y": 179.71563285880146,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.969208473997548,
			"height": 3.009744999707776,
			"seed": 634144419,
			"groupIds": [
				"jp79t2OaZvh3b9HABpxzW",
				"x1nzmPXlspCbw8ePRiA-w",
				"U_ZHYlJIefJ2IWJH_8zHY",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320963,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.969208473997548,
					3.009744999707776
				]
			]
		},
		{
			"type": "line",
			"version": 1284,
			"versionNonce": 2050154070,
			"isDeleted": false,
			"id": "N2lPbqt120roCS5uYc80M",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.719790134349058,
			"x": 164.55920372702798,
			"y": 181.28683162433003,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 2.09981514948573,
			"height": 2.491093218262655,
			"seed": 1584495171,
			"groupIds": [
				"x1nzmPXlspCbw8ePRiA-w",
				"U_ZHYlJIefJ2IWJH_8zHY",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320963,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.049907574742863,
					2.491093218262655
				],
				[
					1.0499075747428668,
					2.491093218262655
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 597,
			"versionNonce": 498162186,
			"isDeleted": false,
			"id": "SElx_-LCGqVQA6dYSvcc8",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 7.853981633974481,
			"x": 162.01390553016606,
			"y": 169.82955930210557,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 13.809552104519076,
			"height": 20.714328156778617,
			"seed": 527383011,
			"groupIds": [
				"U_ZHYlJIefJ2IWJH_8zHY",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320963,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 959,
			"versionNonce": 1412473750,
			"isDeleted": false,
			"id": "siRbLiFDOmijH05OHcX7c",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.1415926535897913,
			"x": 160.97206373496627,
			"y": 168.8635245891426,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.70563496510734,
			"height": 8.866945750373805,
			"seed": 1689080259,
			"groupIds": [
				"kcl-QHrl1ITsnRoPrAy6O",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320963,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.796865626112219,
					-0.25334892806530385
				],
				[
					-4.233105517234365,
					-5.8268513899073175
				],
				[
					-5.744918041064016,
					2.786745432401185
				],
				[
					-7.785877405261414,
					-5.320165130816357
				],
				[
					-8.919743718704405,
					3.040094360466488
				],
				[
					-10.96070308290181,
					-4.8134904687650355
				],
				[
					-11.641029791538372,
					0.5066746620513194
				],
				[
					-16.70563496510734,
					0.2533373310256597
				]
			]
		},
		{
			"type": "ellipse",
			"version": 690,
			"versionNonce": 1062045898,
			"isDeleted": false,
			"id": "VVEkVQGvxSI-oI7XBsRRg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 15.707963267948951,
			"x": 196.45606883371855,
			"y": 187.67273670965176,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 11.175903976900166,
			"height": 11.175903976900166,
			"seed": 832552973,
			"groupIds": [
				"FOb3h8xJ29rMb-uc-rjwF",
				"mSFnvq8bDnmj7fJWA8KyZ",
				"QT_QPVaeFrOuwqigiynv2",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320963,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2013,
			"versionNonce": 1287897302,
			"isDeleted": false,
			"id": "kz6I4kqirksAZXK812bFL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 15.707963267948951,
			"x": 198.3441994044031,
			"y": 196.62411133497557,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 7.428970056841954,
			"height": 6.394081872649196,
			"seed": 1965438573,
			"groupIds": [
				"FOb3h8xJ29rMb-uc-rjwF",
				"mSFnvq8bDnmj7fJWA8KyZ",
				"QT_QPVaeFrOuwqigiynv2",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320963,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.0757299227636825,
					-1.0639303258049342
				],
				[
					1.3112608693454018,
					-2.0998520325561087
				],
				[
					1.3474056117542326,
					-3.6180668412830217
				],
				[
					1.5567079863845477,
					-4.964034659918972
				],
				[
					2.1010104126093148,
					-6.0570183447388395
				],
				[
					3.157219655675525,
					-6.330307860513613
				],
				[
					4.335261190495399,
					-5.756506441890873
				],
				[
					5.166329962092117,
					-4.579263930253227
				],
				[
					5.078420142683197,
					-2.474538306221389
				],
				[
					3.9361147828038336,
					-1.2771883783050715
				],
				[
					2.7126839295041654,
					-2.534548022004387
				],
				[
					2.657512579190993,
					-4.415294432823883
				],
				[
					3.411831320106103,
					-5.708252096691611
				],
				[
					4.771952842483693,
					-6.306611789773392
				],
				[
					5.788268210116412,
					-6.079154698639778
				],
				[
					6.266277826825615,
					-5.068739129486433
				],
				[
					6.334169103909771,
					-3.6848827856399056
				],
				[
					6.351975063853686,
					-2.1510998715653944
				],
				[
					6.588389244904029,
					-0.9942565151897224
				],
				[
					7.428970056841954,
					0.06377401213558351
				]
			]
		},
		{
			"type": "rectangle",
			"version": 650,
			"versionNonce": 586538890,
			"isDeleted": false,
			"id": "ya-H-1LkgibOxR4TvbH3V",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 15.707963267948951,
			"x": 194.63998443747226,
			"y": 183.9716256523667,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 14.901205302533555,
			"height": 14.901205302533555,
			"seed": 1095688397,
			"groupIds": [
				"mSFnvq8bDnmj7fJWA8KyZ",
				"QT_QPVaeFrOuwqigiynv2",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320963,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 725,
			"versionNonce": 394343958,
			"isDeleted": false,
			"id": "4eEsiaMHRVOYSYf6q3-zc",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 15.707963267948951,
			"x": 198.36528576310488,
			"y": 191.42222830363352,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 7.450602651266777,
			"seed": 733167405,
			"groupIds": [
				"QT_QPVaeFrOuwqigiynv2",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320963,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-7.450602651266777
				]
			]
		},
		{
			"type": "line",
			"version": 680,
			"versionNonce": 82140746,
			"isDeleted": false,
			"id": "xF0efUFCe1tFffYJPq6yH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 15.707963267948951,
			"x": 205.76932214780203,
			"y": 191.42222830363355,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.04656626657041736,
			"height": 7.450602651266777,
			"seed": 1522323853,
			"groupIds": [
				"QT_QPVaeFrOuwqigiynv2",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320963,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.04656626657041736,
					-7.450602651266777
				]
			]
		},
		{
			"type": "line",
			"version": 364,
			"versionNonce": 761135958,
			"isDeleted": false,
			"id": "GIVlxY3VoAc9x5rSRkzg5",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 211.9697327162843,
			"y": 178.91620461880967,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.26614144001992773,
			"height": 11.178622769824381,
			"seed": 950887693,
			"groupIds": [
				"HhML-mIc4FO8TGk7Q68Vv",
				"-MKi5Ev8w2zXdSsHNmamj",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320963,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.26614144001992773,
					11.178622769824381
				]
			]
		},
		{
			"type": "line",
			"version": 363,
			"versionNonce": 1643578634,
			"isDeleted": false,
			"id": "hhvG5kXuuJYjgfH8uZrHd",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 212.4302245629011,
			"y": 184.9906365321376,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11.444788577308145,
			"height": 0,
			"seed": 1966553965,
			"groupIds": [
				"-MKi5Ev8w2zXdSsHNmamj",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320964,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					11.444788577308145,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 255,
			"versionNonce": 548350102,
			"isDeleted": false,
			"id": "Xk9S2mfYo__BenZIRln7A",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 188.69788262208186,
			"y": 193.80639143211303,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.842170943040401e-14,
			"height": 19.97739911333565,
			"seed": 1706963149,
			"groupIds": [
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320964,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.842170943040401e-14,
					-19.97739911333565
				]
			]
		},
		{
			"type": "line",
			"version": 244,
			"versionNonce": 1671812042,
			"isDeleted": false,
			"id": "VIU6QUkVgsF6J6tAWjv0N",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 147.53754085392515,
			"y": 172.623458372857,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 22.388467005177347,
			"seed": 42792739,
			"groupIds": [
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320964,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					22.388467005177347
				]
			]
		},
		{
			"type": "line",
			"version": 271,
			"versionNonce": 1898554838,
			"isDeleted": false,
			"id": "fSiiFmxQxbMGFMzk4Meny",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 129.97119523908447,
			"y": 170.21239527879766,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.25521598678975,
			"height": 10.333146737097877,
			"seed": 614077453,
			"groupIds": [
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320964,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					10.333146737097877
				],
				[
					18.25521598678975,
					10.333146737097877
				]
			]
		},
		{
			"type": "line",
			"version": 270,
			"versionNonce": 1275906698,
			"isDeleted": false,
			"id": "-oX0WQfbGTXWOThKaysBb",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 167.85938234990863,
			"y": 175.37896864734628,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.842170943040401e-14,
			"height": 18.94410075208549,
			"seed": 849675149,
			"groupIds": [
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320964,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.842170943040401e-14,
					-18.94410075208549
				]
			]
		},
		{
			"type": "line",
			"version": 216,
			"versionNonce": 1608678166,
			"isDeleted": false,
			"id": "5flUYl6n_y5xmQ9dbVvxk",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 172.85373932491598,
			"y": 169.69573650260776,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 8.26652122790415,
			"height": 0,
			"seed": 1247531021,
			"groupIds": [
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320964,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-8.26652122790415,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 492,
			"versionNonce": 1642522954,
			"isDeleted": false,
			"id": "WtSVAayNGn3XeoYzGPEpa",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.258879658455111,
			"x": 191.45800763413013,
			"y": 165.19752409631926,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.310358030362282,
			"height": 0.08451940337353375,
			"seed": 1526753613,
			"groupIds": [
				"zla36gB_0etQrrmoLKoxO",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320964,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.310358030362282,
					0.08451940337353375
				]
			]
		},
		{
			"type": "ellipse",
			"version": 462,
			"versionNonce": 1129228374,
			"isDeleted": false,
			"id": "iS6jKKzQ3KRUbyQj0U-bv",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.258879658455111,
			"x": 195.93451400032552,
			"y": 164.5793742826667,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.0142018894970077,
			"height": 1.0142018894970077,
			"seed": 387954605,
			"groupIds": [
				"zla36gB_0etQrrmoLKoxO",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320964,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 461,
			"versionNonce": 1552887818,
			"isDeleted": false,
			"id": "2aMf7sRCFMhNb0IS8hm9d",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.258879658455111,
			"x": 196.74318241731788,
			"y": 164.57688609145578,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 3.042605668491023,
			"height": 2.0284037789940155,
			"seed": 50739725,
			"groupIds": [
				"zla36gB_0etQrrmoLKoxO",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320964,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					3.042605668491023,
					-2.0284037789940155
				]
			]
		},
		{
			"type": "line",
			"version": 421,
			"versionNonce": 1531129238,
			"isDeleted": false,
			"id": "3E2LnH69oE7nMN3yLc3Np",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.258879658455111,
			"x": 201.33943473956816,
			"y": 164.87170550206616,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.394885171482166,
			"height": 0.08451166562718443,
			"seed": 128807021,
			"groupIds": [
				"zla36gB_0etQrrmoLKoxO",
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320964,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.394885171482166,
					-0.08451166562718443
				]
			]
		},
		{
			"type": "line",
			"version": 249,
			"versionNonce": 1342217930,
			"isDeleted": false,
			"id": "OIpJ2U34gleO-W8FcLPZ1",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 199.54768333758702,
			"y": 178.47890691113668,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.632966326252273,
			"height": 8.266511632339643,
			"seed": 796677699,
			"groupIds": [
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320964,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-8.266511632339643
				],
				[
					19.632966326252273,
					-7.922069249691788
				]
			]
		},
		{
			"type": "text",
			"version": 376,
			"versionNonce": 1623619841,
			"isDeleted": false,
			"id": "J7409SEV",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 193.21479272325666,
			"y": 202.39948677688824,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.930862426757812,
			"height": 12.124150677677237,
			"seed": 328873613,
			"groupIds": [
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414141,
			"link": null,
			"locked": false,
			"fontSize": 4.849660271070895,
			"fontFamily": 1,
			"text": "10v, 0.1A\nlamp",
			"rawText": "10v, 0.1A\nlamp",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "10v, 0.1A\nlamp",
			"lineHeight": 1.25,
			"baseline": 10
		},
		{
			"type": "text",
			"version": 306,
			"versionNonce": 1337611151,
			"isDeleted": false,
			"id": "Y3NDNN4o",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 217.1195919448543,
			"y": 181.97366254069277,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 8.427902221679688,
			"height": 5.0225960888821,
			"seed": 72469347,
			"groupIds": [
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414141,
			"link": null,
			"locked": false,
			"fontSize": 4.01807687110568,
			"fontFamily": 1,
			"text": "+10v",
			"rawText": "+10v",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+10v",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 313,
			"versionNonce": 708637390,
			"isDeleted": false,
			"id": "WgxhwNG5",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 177.3296881932129,
			"y": 154.01334636280163,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 8.78802490234375,
			"height": 6.400341630562359,
			"seed": 705725603,
			"groupIds": [
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502064,
			"link": null,
			"locked": false,
			"fontSize": 5.120273304449887,
			"fontFamily": 1,
			"text": "1.0k",
			"rawText": "1.0k",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1.0k",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "text",
			"version": 284,
			"versionNonce": 1063717295,
			"isDeleted": false,
			"id": "djN5L6UF",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948957,
			"x": 147.1192008744814,
			"y": 154.0589833387941,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 6.9815826416015625,
			"height": 6.0559088434790205,
			"seed": 498994797,
			"groupIds": [
				"RSHeOtggMnQCJUgLUz9lg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414142,
			"link": null,
			"locked": false,
			"fontSize": 4.844727074783217,
			"fontFamily": 1,
			"text": "10k",
			"rawText": "10k",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "10k",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "line",
			"version": 82,
			"versionNonce": 1833225558,
			"isDeleted": false,
			"id": "z9i13TF93GXlYHkxFu-tN",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2.8211423224592806,
			"y": 33.9129386401267,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 133.56778114487406,
			"height": 0,
			"seed": 1810039373,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320964,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					133.56778114487406,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 525,
			"versionNonce": 759141910,
			"isDeleted": false,
			"id": "syZvHH4BapP4iUc6iFMXr",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -10.78429514178589,
			"y": -339.39530857692597,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 346.7143104731326,
			"height": 1577.2173023865557,
			"seed": 1266847459,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1707241476153,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1375,
			"versionNonce": 1515907346,
			"isDeleted": false,
			"id": "qIQL5ONZ",
			"fillStyle": "solid",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3.574280059354635,
			"y": 219.83527313377667,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 237.22312927246094,
			"height": 93.82781136414349,
			"seed": 9128461,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502067,
			"link": null,
			"locked": false,
			"fontSize": 5.774019160870369,
			"fontFamily": 1,
			"text": "There are certain cautions to be observed when designing transistor switches:\n1.  Choose the base resistor conservatively to get plenty of excess base current,\n    especially when driving lamps, because of the reduced beta at low    . This is\n    also a good idea for high-speed switching, because of capacitive effects and\n    reduced beta at very high frequencies.\n2. If the load swings below ground for some reason (eg, it is driven from ac or it \n    is inductive), use a diode in series with the collector (or a diode in reverse \n    direction to ground to prevent collector-base conduction on negative swings.\n3. For inductive loads, protect the transistor with a diode across the load as \n    shown. Without the diode, the inductor will swing the collector to a large\n    positive voltage when the switch is opened, most likely exceeding the collector\n    emitter breakdown voltage as the inductor tries to maintain its \"on\" current\n    from Vcc to the collector",
			"rawText": "There are certain cautions to be observed when designing transistor switches:\n1.  Choose the base resistor conservatively to get plenty of excess base current,\n    especially when driving lamps, because of the reduced beta at low    . This is\n    also a good idea for high-speed switching, because of capacitive effects and\n    reduced beta at very high frequencies.\n2. If the load swings below ground for some reason (eg, it is driven from ac or it \n    is inductive), use a diode in series with the collector (or a diode in reverse \n    direction to ground to prevent collector-base conduction on negative swings.\n3. For inductive loads, protect the transistor with a diode across the load as \n    shown. Without the diode, the inductor will swing the collector to a large\n    positive voltage when the switch is opened, most likely exceeding the collector\n    emitter breakdown voltage as the inductor tries to maintain its \"on\" current\n    from Vcc to the collector",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "There are certain cautions to be observed when designing transistor switches:\n1.  Choose the base resistor conservatively to get plenty of excess base current,\n    especially when driving lamps, because of the reduced beta at low    . This is\n    also a good idea for high-speed switching, because of capacitive effects and\n    reduced beta at very high frequencies.\n2. If the load swings below ground for some reason (eg, it is driven from ac or it \n    is inductive), use a diode in series with the collector (or a diode in reverse \n    direction to ground to prevent collector-base conduction on negative swings.\n3. For inductive loads, protect the transistor with a diode across the load as \n    shown. Without the diode, the inductor will swing the collector to a large\n    positive voltage when the switch is opened, most likely exceeding the collector\n    emitter breakdown voltage as the inductor tries to maintain its \"on\" current\n    from Vcc to the collector",
			"lineHeight": 1.25,
			"baseline": 92
		},
		{
			"type": "line",
			"version": 780,
			"versionNonce": 790489546,
			"isDeleted": false,
			"id": "SyQQE3Aye-82Bk692xkBY",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 12.569356385853787,
			"x": 291.8037048278105,
			"y": 299.26527482525944,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.1515025401532162,
			"height": 6.363495083351788,
			"seed": 1272020589,
			"groupIds": [
				"fEARKIJSpNFJrYQcVqwZr",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320965,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.1515025401532162,
					6.363495083351788
				]
			]
		},
		{
			"type": "line",
			"version": 792,
			"versionNonce": 1231417302,
			"isDeleted": false,
			"id": "DIcOAlmidL9z5PGGXAKW-",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 12.569356385853787,
			"x": 287.70114549509447,
			"y": 305.6754312892562,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8.33313907589123,
			"height": 0.15151641147167005,
			"seed": 860956877,
			"groupIds": [
				"fEARKIJSpNFJrYQcVqwZr",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320965,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.33313907589123,
					-0.15151641147167005
				]
			]
		},
		{
			"type": "line",
			"version": 798,
			"versionNonce": 1544691850,
			"isDeleted": false,
			"id": "nTu1nfVDFKg9wOxq0uLrA",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 12.569356385853787,
			"x": 290.07052019859503,
			"y": 307.08916159153125,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 3.6362967760909046,
			"height": 0.15151641147167005,
			"seed": 908887853,
			"groupIds": [
				"fEARKIJSpNFJrYQcVqwZr",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320965,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					3.6362967760909046,
					0.15151641147167005
				]
			]
		},
		{
			"type": "line",
			"version": 788,
			"versionNonce": 1040549142,
			"isDeleted": false,
			"id": "SaqkbabZqF960SwHvSfLQ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 12.569356385853787,
			"x": 291.6604112422282,
			"y": 308.60166660710235,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.9090707261931127,
			"height": 0,
			"seed": 1456281997,
			"groupIds": [
				"fEARKIJSpNFJrYQcVqwZr",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320965,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.9090707261931127,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1121,
			"versionNonce": 852590410,
			"isDeleted": false,
			"id": "IZyt7_d0c4bauuW6pl1gf",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 12.569356385853787,
			"x": 281.345833502489,
			"y": 267.11789852492484,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.2718898236847025,
			"height": 0,
			"seed": 1930680909,
			"groupIds": [
				"tnU-YMbGPLd9ZtiYaKyWi",
				"pJE1DI8h4DZ4AdKb1VLxX",
				"zqbKJ7nwG5m4NHxDQPgAI",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320965,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.2718898236847025,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1158,
			"versionNonce": 1015050838,
			"isDeleted": false,
			"id": "PNmb-nyM-uYDGAJO0Y4bt",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 12.569356385853787,
			"x": 286.7447646767389,
			"y": 261.9814132481699,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 10.357164078389308,
			"seed": 496830637,
			"groupIds": [
				"tnU-YMbGPLd9ZtiYaKyWi",
				"pJE1DI8h4DZ4AdKb1VLxX",
				"zqbKJ7nwG5m4NHxDQPgAI",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320965,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					10.357164078389308
				]
			]
		},
		{
			"type": "line",
			"version": 1195,
			"versionNonce": 532088330,
			"isDeleted": false,
			"id": "spdvEyBGtjNrQq50-OY0a",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 12.569356385853787,
			"x": 286.85606863030466,
			"y": 265.2970164179933,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.949864177213169,
			"height": 3.3590802416397203,
			"seed": 1337027341,
			"groupIds": [
				"tnU-YMbGPLd9ZtiYaKyWi",
				"pJE1DI8h4DZ4AdKb1VLxX",
				"zqbKJ7nwG5m4NHxDQPgAI",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320965,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.949864177213169,
					-3.3590802416397203
				]
			]
		},
		{
			"type": "line",
			"version": 1170,
			"versionNonce": 531347350,
			"isDeleted": false,
			"id": "MNrz_LS0MWGHNte6RJ-Ki",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 12.569356385853787,
			"x": 291.68033578910683,
			"y": 271.9405799088309,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 5.557502676208944,
			"seed": 1506443629,
			"groupIds": [
				"tnU-YMbGPLd9ZtiYaKyWi",
				"pJE1DI8h4DZ4AdKb1VLxX",
				"zqbKJ7nwG5m4NHxDQPgAI",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320965,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					5.557502676208944
				]
			]
		},
		{
			"type": "line",
			"version": 1147,
			"versionNonce": 1270723786,
			"isDeleted": false,
			"id": "zbuZro4deQcGeHLdKXDj6",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 12.569356385853787,
			"x": 291.7257519873812,
			"y": 262.2331798001625,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 5.449357570655802,
			"seed": 1093782477,
			"groupIds": [
				"tnU-YMbGPLd9ZtiYaKyWi",
				"pJE1DI8h4DZ4AdKb1VLxX",
				"zqbKJ7nwG5m4NHxDQPgAI",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320965,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-5.449357570655802
				]
			]
		},
		{
			"type": "line",
			"version": 1265,
			"versionNonce": 532436182,
			"isDeleted": false,
			"id": "WLzBFn8CMPjAU5__05768",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 12.569356385853787,
			"x": 286.78912018000176,
			"y": 269.1935814017619,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.969208473997548,
			"height": 3.009744999707776,
			"seed": 637585965,
			"groupIds": [
				"tnU-YMbGPLd9ZtiYaKyWi",
				"pJE1DI8h4DZ4AdKb1VLxX",
				"zqbKJ7nwG5m4NHxDQPgAI",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320965,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.969208473997548,
					3.009744999707776
				]
			]
		},
		{
			"type": "line",
			"version": 1650,
			"versionNonce": 142642058,
			"isDeleted": false,
			"id": "Lk-T1zOPIJd_TxfAAyHEI",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 8.435164886228362,
			"x": 290.5832185388516,
			"y": 270.25155965358607,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 2.09981514948573,
			"height": 2.491093218262655,
			"seed": 1763769485,
			"groupIds": [
				"pJE1DI8h4DZ4AdKb1VLxX",
				"zqbKJ7nwG5m4NHxDQPgAI",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320965,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.049907574742863,
					2.491093218262655
				],
				[
					1.0499075747428668,
					2.491093218262655
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 963,
			"versionNonce": 642206230,
			"isDeleted": false,
			"id": "XhzUkKX6EmCwko__VmFNv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 12.569356385853787,
			"x": 281.3458144745483,
			"y": 256.7734801819311,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 13.809552104519076,
			"height": 20.714328156778617,
			"seed": 306963181,
			"groupIds": [
				"zqbKJ7nwG5m4NHxDQPgAI",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320965,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 727,
			"versionNonce": 1010469450,
			"isDeleted": false,
			"id": "lgdBDehWjB2gyCdEqGRZ5",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 12.569356385853787,
			"x": 292.12564571990083,
			"y": 220.27587092887933,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.26614144001992773,
			"height": 11.178622769824381,
			"seed": 1327619981,
			"groupIds": [
				"l2eTmNnp7fs9eQE0osC2y",
				"hkhn8A6DTM7jy6aGw4IS7",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320965,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.26614144001992773,
					11.178622769824381
				]
			]
		},
		{
			"type": "line",
			"version": 726,
			"versionNonce": 574723926,
			"isDeleted": false,
			"id": "zDWrQ3vARkmBzC2U8It7P",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 12.569356385853787,
			"x": 286.7110609045126,
			"y": 219.45295502913226,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11.444788577308145,
			"height": 0,
			"seed": 1815635437,
			"groupIds": [
				"hkhn8A6DTM7jy6aGw4IS7",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320965,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					11.444788577308145,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 611,
			"versionNonce": 1304867082,
			"isDeleted": false,
			"id": "NHDBb3ylAnZgWFKLFqpLD",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 12.569356385853787,
			"x": 291.8177037313786,
			"y": 277.3282974077924,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 22.388467005177347,
			"seed": 278892205,
			"groupIds": [
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320966,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					22.388467005177347
				]
			]
		},
		{
			"type": "line",
			"version": 612,
			"versionNonce": 1543519382,
			"isDeleted": false,
			"id": "_McK-jOhWsimQr-Ohnqxe",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 12.569356385853787,
			"x": 271.9285627382785,
			"y": 232.36002023642016,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.632966326252273,
			"height": 8.266511632339643,
			"seed": 525619629,
			"groupIds": [
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320966,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-8.266511632339643
				],
				[
					19.632966326252273,
					-7.922069249691788
				]
			]
		},
		{
			"type": "text",
			"version": 460,
			"versionNonce": 1005676814,
			"isDeleted": false,
			"id": "fY8i5TU5",
			"fillStyle": "solid",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 6.286171078674199,
			"x": 285.8153877768069,
			"y": 209.5307317826374,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.842315673828125,
			"height": 7.494629381879674,
			"seed": 576563491,
			"groupIds": [
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502068,
			"link": null,
			"locked": false,
			"fontSize": 5.995703505503739,
			"fontFamily": 1,
			"text": "+Vcc",
			"rawText": "+Vcc",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+Vcc",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "rectangle",
			"version": 686,
			"versionNonce": 1228421590,
			"isDeleted": false,
			"id": "2Pf5OBKx2QZMt_4eIIjeK",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 14.140152712648678,
			"x": 278.67470650462707,
			"y": 238.87903493062498,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 26.327717739472504,
			"height": 8.775905913157501,
			"seed": 1672909709,
			"groupIds": [
				"yeYemGB9cdu0zAefk3R91",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320966,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 680,
			"versionNonce": 820082314,
			"isDeleted": false,
			"id": "wuX7AwCrNrrLVHgTSwlCe",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 14.140152712648678,
			"x": 289.61183538259615,
			"y": 254.23682138136152,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.387952956578751,
			"height": 0,
			"seed": 1947638253,
			"groupIds": [
				"dkcDssEk7d3INE4JsroL-",
				"yeYemGB9cdu0zAefk3R91",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320966,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.387952956578751,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 679,
			"versionNonce": 1627295510,
			"isDeleted": false,
			"id": "954UF6uVnz2Mxko-JG5JN",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 14.140152712648678,
			"x": 294.0652953661302,
			"y": 232.29715439304684,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.387952956578751,
			"height": 0,
			"seed": 1533465677,
			"groupIds": [
				"dkcDssEk7d3INE4JsroL-",
				"yeYemGB9cdu0zAefk3R91",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320966,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-4.387952956578751,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1246,
			"versionNonce": 524686666,
			"isDeleted": false,
			"id": "8-RtD5UCO_YqklsjlmjNt",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 14.140152712648678,
			"x": 290.99042785617735,
			"y": 251.56828912345102,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.325509010658318,
			"height": 3.8090807011531127,
			"seed": 897630893,
			"groupIds": [
				"n49evnyx6eDYZSRBxRJ0M",
				"dkcDssEk7d3INE4JsroL-",
				"yeYemGB9cdu0zAefk3R91",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320966,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.05400557485021229,
					-2.202414849359696
				],
				[
					0.7695794416151259,
					-3.328093550143584
				],
				[
					2.1754120619348893,
					-3.8090807011531127
				],
				[
					3.5491788721864164,
					-3.329781224357628
				],
				[
					4.251251345238976,
					-2.1433462518672517
				],
				[
					4.325509010658318,
					-0.06075627170643894
				]
			]
		},
		{
			"type": "line",
			"version": 1274,
			"versionNonce": 1875393622,
			"isDeleted": false,
			"id": "SDX0qSnOVIs-JcX2otvf8",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 14.140152712648678,
			"x": 291.0007684869363,
			"y": 247.25713700174438,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.325509010658318,
			"height": 3.8090807011531127,
			"seed": 1728963853,
			"groupIds": [
				"n49evnyx6eDYZSRBxRJ0M",
				"dkcDssEk7d3INE4JsroL-",
				"yeYemGB9cdu0zAefk3R91",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320966,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.05400557485021229,
					-2.202414849359696
				],
				[
					0.7695794416151259,
					-3.328093550143584
				],
				[
					2.1754120619348893,
					-3.8090807011531127
				],
				[
					3.5491788721864164,
					-3.329781224357628
				],
				[
					4.251251345238976,
					-2.1433462518672517
				],
				[
					4.325509010658318,
					-0.06075627170643894
				]
			]
		},
		{
			"type": "line",
			"version": 1290,
			"versionNonce": 2099829770,
			"isDeleted": false,
			"id": "vEAGpRSLrFH9LF15iVpev",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 14.140152712648678,
			"x": 290.99193022533905,
			"y": 242.86913809705484,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.325509010658318,
			"height": 3.8090807011531127,
			"seed": 59226989,
			"groupIds": [
				"n49evnyx6eDYZSRBxRJ0M",
				"dkcDssEk7d3INE4JsroL-",
				"yeYemGB9cdu0zAefk3R91",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320966,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.05400557485021229,
					-2.202414849359696
				],
				[
					0.7695794416151259,
					-3.328093550143584
				],
				[
					2.1754120619348893,
					-3.8090807011531127
				],
				[
					3.5491788721864164,
					-3.329781224357628
				],
				[
					4.251251345238976,
					-2.1433462518672517
				],
				[
					4.325509010658318,
					-0.06075627170643894
				]
			]
		},
		{
			"type": "line",
			"version": 1303,
			"versionNonce": 1802125718,
			"isDeleted": false,
			"id": "IBLSO3NWl-Q3i20pyfYgq",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 14.140152712648678,
			"x": 291.0487799506536,
			"y": 238.52521504742202,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.325509010658318,
			"height": 3.8090807011531127,
			"seed": 1933034957,
			"groupIds": [
				"n49evnyx6eDYZSRBxRJ0M",
				"dkcDssEk7d3INE4JsroL-",
				"yeYemGB9cdu0zAefk3R91",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320966,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.05400557485021229,
					-2.202414849359696
				],
				[
					0.7695794416151259,
					-3.328093550143584
				],
				[
					2.1754120619348893,
					-3.8090807011531127
				],
				[
					3.5491788721864164,
					-3.329781224357628
				],
				[
					4.251251345238976,
					-2.1433462518672517
				],
				[
					4.325509010658318,
					-0.06075627170643894
				]
			]
		},
		{
			"type": "line",
			"version": 1291,
			"versionNonce": 142920394,
			"isDeleted": false,
			"id": "K4Biyxde25cEd6eYdP6I0",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 25.13572700021296,
			"x": 266.69836165563686,
			"y": 240.81587236398417,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 10.727410887480815,
			"height": 5.3637054437404075,
			"seed": 1713115075,
			"groupIds": [
				"9UdXsFRP_OnObVLXHyU-N",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320966,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.727410887480815,
					0
				],
				[
					5.3637054437404075,
					-5.3637054437404075
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1231,
			"versionNonce": 1192861398,
			"isDeleted": false,
			"id": "lxPxt_ll96gXV6zijLcmB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 23.56493067341806,
			"x": 272.07039801769776,
			"y": 229.98011622789258,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 0,
			"height": 10.727410887480815,
			"seed": 1345003363,
			"groupIds": [
				"9UdXsFRP_OnObVLXHyU-N",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320966,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					10.727410887480815
				]
			]
		},
		{
			"type": "line",
			"version": 1167,
			"versionNonce": 133489034,
			"isDeleted": false,
			"id": "E2vXwHgxC_1ra5moVMdQG",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 23.56493067341806,
			"x": 264.01650893376706,
			"y": 238.13401964211494,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 16.09111633122131,
			"height": 0,
			"seed": 821508867,
			"groupIds": [
				"9UdXsFRP_OnObVLXHyU-N",
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320966,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					16.09111633122131,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 463,
			"versionNonce": 1198216214,
			"isDeleted": false,
			"id": "uB4TMUsl7LFtIUqkT5e8j",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.286171078674199,
			"x": 272.0943507893763,
			"y": 242.59112374168808,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 20.295654632499748,
			"height": 14.441150582775322,
			"seed": 616991843,
			"groupIds": [
				"xdO5r8PHSv0QZPiJSDR-k"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320966,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					14.441150582775322
				],
				[
					20.295654632499748,
					14.441150582775322
				]
			]
		},
		{
			"type": "line",
			"version": 77,
			"versionNonce": 917774410,
			"isDeleted": false,
			"id": "lBHyoRu7cCqf7DvvYWNkA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 5.762077167085593,
			"y": 47.46568865659164,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 63.170674641927135,
			"height": 0,
			"seed": 1288339466,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320966,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					63.170674641927135,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 1680,
			"versionNonce": 1448370518,
			"isDeleted": false,
			"id": "SxHRZ1Fu",
			"fillStyle": "solid",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1.0366493522302278,
			"y": 343.2845569116302,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 324.92486572265625,
			"height": 14.43504790217592,
			"seed": 1983487958,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320967,
			"link": null,
			"locked": false,
			"fontSize": 5.774019160870369,
			"fontFamily": 1,
			"text": "In high-side switching, the switch (transistor) is positioned between the positive supply voltage and the load. This\nmeans that the switch controls the flow of current from the positive supply to the load.",
			"rawText": "In high-side switching, the switch (transistor) is positioned between the positive supply voltage and the load. This\nmeans that the switch controls the flow of current from the positive supply to the load.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "In high-side switching, the switch (transistor) is positioned between the positive supply voltage and the load. This\nmeans that the switch controls the flow of current from the positive supply to the load.",
			"lineHeight": 1.25,
			"baseline": 12
		},
		{
			"type": "text",
			"version": 295,
			"versionNonce": 1157625554,
			"isDeleted": false,
			"id": "ruu66AXH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -0.574427874522442,
			"y": 332.30048191928427,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 102.49588012695312,
			"height": 6.4237563687808175,
			"seed": 1585922070,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502069,
			"link": null,
			"locked": false,
			"fontSize": 5.139005095024654,
			"fontFamily": 1,
			"text": "HIGH-SIDE AND LOW-SIDE SWITCHING",
			"rawText": "HIGH-SIDE AND LOW-SIDE SWITCHING",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "HIGH-SIDE AND LOW-SIDE SWITCHING",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "line",
			"version": 197,
			"versionNonce": 1462355606,
			"isDeleted": false,
			"id": "MNdaot0jhY6i7XrPdTkDo",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -0.3220714786028367,
			"y": 338.9414678720867,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 102.65595862686702,
			"height": 0,
			"seed": 1784147850,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320967,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					102.65595862686702,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 2788,
			"versionNonce": 2013239631,
			"isDeleted": false,
			"id": "d9jPhwsF",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 401.9371767141783,
			"y": -345.2851634459163,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 334.4364013671875,
			"height": 64.26078942030783,
			"seed": 856744266,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707327046282,
			"link": null,
			"locked": false,
			"fontSize": 5.712070170694029,
			"fontFamily": 1,
			"text": "If we mildly stimulate a transistor, we find that the controlled current is more or less fixed regardless of how much\nvoltage we apply in the load. This is why the current/voltage characteristics curves tend to flatten with increasing\nsource voltages; whether BJT or MOSFET, the few charge carriers existing within the transistor to support this \ncurrent are fixed in rate by the controlling stimulus.\n    We see this current limiting behaviour for both BJTs(left) and MOSFETs(right) in the near-level portions of the\ncharacteristic curves shown below. For the BJT we plot collector current Ic on the vertical axis and collector emitt-\ner voltage (Vce) on the horizontal. For the MOSFET we plot drain current (Id) on the vertical axis and drain-source\nvoltage (Vds) on the horizontal. Each curve represents a different degree of fixed stimulus, Ib for the BJT and Vg\nfor the MOSFET:",
			"rawText": "If we mildly stimulate a transistor, we find that the controlled current is more or less fixed regardless of how much\nvoltage we apply in the load. This is why the current/voltage characteristics curves tend to flatten with increasing\nsource voltages; whether BJT or MOSFET, the few charge carriers existing within the transistor to support this \ncurrent are fixed in rate by the controlling stimulus.\n    We see this current limiting behaviour for both BJTs(left) and MOSFETs(right) in the near-level portions of the\ncharacteristic curves shown below. For the BJT we plot collector current Ic on the vertical axis and collector emitt-\ner voltage (Vce) on the horizontal. For the MOSFET we plot drain current (Id) on the vertical axis and drain-source\nvoltage (Vds) on the horizontal. Each curve represents a different degree of fixed stimulus, Ib for the BJT and Vg\nfor the MOSFET:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "If we mildly stimulate a transistor, we find that the controlled current is more or less fixed regardless of how much\nvoltage we apply in the load. This is why the current/voltage characteristics curves tend to flatten with increasing\nsource voltages; whether BJT or MOSFET, the few charge carriers existing within the transistor to support this \ncurrent are fixed in rate by the controlling stimulus.\n    We see this current limiting behaviour for both BJTs(left) and MOSFETs(right) in the near-level portions of the\ncharacteristic curves shown below. For the BJT we plot collector current Ic on the vertical axis and collector emitt-\ner voltage (Vce) on the horizontal. For the MOSFET we plot drain current (Id) on the vertical axis and drain-source\nvoltage (Vds) on the horizontal. Each curve represents a different degree of fixed stimulus, Ib for the BJT and Vg\nfor the MOSFET:",
			"lineHeight": 1.25,
			"baseline": 62
		},
		{
			"type": "rectangle",
			"version": 267,
			"versionNonce": 2057339862,
			"isDeleted": false,
			"id": "JLaxigZ_8ALifC4YYWQwj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 389.475383286995,
			"y": -364.4728238990638,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 347.55489002574564,
			"height": 779.201215700768,
			"seed": 1833260298,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1707241320967,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 37,
			"versionNonce": 772910241,
			"isDeleted": false,
			"id": "yNm17kSl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 428.08290984494147,
			"y": -390.41923887585375,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 281.7197570800781,
			"height": 25,
			"seed": 1951708746,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414148,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "TRANSISTOR SATURATION",
			"rawText": "TRANSISTOR SATURATION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "TRANSISTOR SATURATION",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "line",
			"version": 212,
			"versionNonce": 315463958,
			"isDeleted": false,
			"id": "jkWNbdEeaPWCjRYEEDI8M",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 408.3501483438556,
			"y": -123.01551891450623,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 128.5630254775567,
			"seed": 1385086154,
			"groupIds": [
				"Tpl4IqRv10KBT3A7F3Aw5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320967,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-128.5630254775567
				]
			]
		},
		{
			"type": "line",
			"version": 167,
			"versionNonce": 2101652298,
			"isDeleted": false,
			"id": "RYmQniwUAsDCvND8e-RZw",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 407.21996068834056,
			"y": -145.60585861225763,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 120.27166836927539,
			"height": 0,
			"seed": 1242469130,
			"groupIds": [
				"Tpl4IqRv10KBT3A7F3Aw5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320967,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					120.27166836927539,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 364,
			"versionNonce": 1730545238,
			"isDeleted": false,
			"id": "-_DjdsWQqNts6LRaL5ZnE",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 409.0419753501717,
			"y": -145.12915942663255,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 120.20115916781889,
			"height": 88.11356778607677,
			"seed": 324411350,
			"groupIds": [
				"Tpl4IqRv10KBT3A7F3Aw5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320967,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					18.84511153805604,
					-74.87105601682518
				],
				[
					120.20115916781889,
					-88.11356778607677
				]
			]
		},
		{
			"type": "line",
			"version": 246,
			"versionNonce": 182759946,
			"isDeleted": false,
			"id": "sYhkJn2UA4R4DByENywHM",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 409.04198953931194,
			"y": -145.12921618319353,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 119.69184707269106,
			"height": 70.28711236384203,
			"seed": 203769366,
			"groupIds": [
				"Tpl4IqRv10KBT3A7F3Aw5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320967,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					17.317107854256236,
					-58.57261492024539
				],
				[
					119.69184707269106,
					-70.28711236384203
				]
			]
		},
		{
			"type": "line",
			"version": 158,
			"versionNonce": 142527382,
			"isDeleted": false,
			"id": "r3pXCoo8-rJNPT4hDHTuU",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 409.04198953931194,
			"y": -145.60585861225763,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 120.13582510957553,
			"height": 51.88596913115812,
			"seed": 1181391126,
			"groupIds": [
				"Tpl4IqRv10KBT3A7F3Aw5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320967,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					18.335767517362594,
					-44.82076977215553
				],
				[
					120.13582510957553,
					-51.88596913115812
				]
			]
		},
		{
			"type": "line",
			"version": 136,
			"versionNonce": 1549131978,
			"isDeleted": false,
			"id": "Bft4H_94r7qYENtvo92Av",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 408.5326632550438,
			"y": -145.4792197060318,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 121.08911615193088,
			"height": 36.60619479225484,
			"seed": 213324042,
			"groupIds": [
				"Tpl4IqRv10KBT3A7F3Aw5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320967,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					22.410391980647884,
					-32.08760557088244
				],
				[
					121.08911615193088,
					-36.60619479225484
				]
			]
		},
		{
			"type": "line",
			"version": 172,
			"versionNonce": 621603030,
			"isDeleted": false,
			"id": "nYZ_EKfb_bAlnwRx505cn",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 409.00931541562005,
			"y": -145.92319865325925,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 120.07045385188242,
			"height": 20.340388799231125,
			"seed": 1428790230,
			"groupIds": [
				"Tpl4IqRv10KBT3A7F3Aw5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320967,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					20.373076201720153,
					-18.335760422792553
				],
				[
					120.07045385188242,
					-20.340388799231125
				]
			]
		},
		{
			"type": "line",
			"version": 137,
			"versionNonce": 758331274,
			"isDeleted": false,
			"id": "eh4eOUlcFbl_NuhE--P7f",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 406.89926203037936,
			"y": -132.21307357265755,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 131.55531552007508,
			"height": 0,
			"seed": 1246754506,
			"groupIds": [
				"Tpl4IqRv10KBT3A7F3Aw5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320967,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					131.55531552007508,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 147,
			"versionNonce": 1550147094,
			"isDeleted": false,
			"id": "y9PlFdoK",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 517.6140628984408,
			"y": -152.36838900522196,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.37060546875,
			"height": 4.955840070143048,
			"seed": 798125642,
			"groupIds": [
				"Tpl4IqRv10KBT3A7F3Aw5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320967,
			"link": null,
			"locked": false,
			"fontSize": 3.964672056114438,
			"fontFamily": 1,
			"text": "Ib = 0mA",
			"rawText": "Ib = 0mA",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Ib = 0mA",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 157,
			"versionNonce": 230143562,
			"isDeleted": false,
			"id": "wFuz3TM0",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 518.6156626605427,
			"y": -172.38040316474203,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 20.525100708007812,
			"height": 4.955840070143048,
			"seed": 2005020106,
			"groupIds": [
				"Tpl4IqRv10KBT3A7F3Aw5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320968,
			"link": null,
			"locked": false,
			"fontSize": 3.9646720561144386,
			"fontFamily": 1,
			"text": "Ib = 0.1mA",
			"rawText": "Ib = 0.1mA",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Ib = 0.1mA",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 157,
			"versionNonce": 326970198,
			"isDeleted": false,
			"id": "7yvlkmqY",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 518.180543030634,
			"y": -189.35005545238255,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 22.268478393554688,
			"height": 4.955840070143049,
			"seed": 1238485514,
			"groupIds": [
				"Tpl4IqRv10KBT3A7F3Aw5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320968,
			"link": null,
			"locked": false,
			"fontSize": 3.964672056114439,
			"fontFamily": 1,
			"text": "Ib = 0.2mA",
			"rawText": "Ib = 0.2mA",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Ib = 0.2mA",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 162,
			"versionNonce": 1321098506,
			"isDeleted": false,
			"id": "k5kiHUDZ",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 518.6156493817455,
			"y": -203.89494623795267,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 22.145919799804688,
			"height": 4.955840070143048,
			"seed": 630967882,
			"groupIds": [
				"Tpl4IqRv10KBT3A7F3Aw5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320968,
			"link": null,
			"locked": false,
			"fontSize": 3.9646720561144386,
			"fontFamily": 1,
			"text": "Ib = 0.3mA",
			"rawText": "Ib = 0.3mA",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Ib = 0.3mA",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 159,
			"versionNonce": 1219055766,
			"isDeleted": false,
			"id": "Jee8STCQ",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 517.268767692864,
			"y": -222.72968527908594,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 21.983840942382812,
			"height": 4.955840070143048,
			"seed": 1629043338,
			"groupIds": [
				"Tpl4IqRv10KBT3A7F3Aw5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320968,
			"link": null,
			"locked": false,
			"fontSize": 3.9646720561144386,
			"fontFamily": 1,
			"text": "Ib = 0.4mA",
			"rawText": "Ib = 0.4mA",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Ib = 0.4mA",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 160,
			"versionNonce": 1841441738,
			"isDeleted": false,
			"id": "Ewk2RUih",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 517.7078523716464,
			"y": -240.6111261832937,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 21.896865844726562,
			"height": 4.955840070143048,
			"seed": 1898122954,
			"groupIds": [
				"Tpl4IqRv10KBT3A7F3Aw5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320968,
			"link": null,
			"locked": false,
			"fontSize": 3.964672056114438,
			"fontFamily": 1,
			"text": "Ib = 0.5mA",
			"rawText": "Ib = 0.5mA",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Ib = 0.5mA",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "line",
			"version": 322,
			"versionNonce": 1738460630,
			"isDeleted": false,
			"id": "n05YxErrfGEXIqHoSpV8m",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 597.6454968096419,
			"y": -121.62136912105845,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 135.0713270616274,
			"seed": 1656265430,
			"groupIds": [
				"RH_o39PpweoUGZ_XjJvw6"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320968,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-135.0713270616274
				]
			]
		},
		{
			"type": "line",
			"version": 265,
			"versionNonce": 14557834,
			"isDeleted": false,
			"id": "1iY0GYPmzAyf8AaXtYZrI",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 585.6311414400807,
			"y": -128.80310580784547,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 140.304427200136,
			"height": 0,
			"seed": 231395350,
			"groupIds": [
				"RH_o39PpweoUGZ_XjJvw6"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320968,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					140.304427200136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 332,
			"versionNonce": 494052118,
			"isDeleted": false,
			"id": "sbInpYB3u8wF9lFQ5fcSQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 597.3703943003194,
			"y": -130.15600443499935,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 131.03161366574204,
			"height": 121.99494221445593,
			"seed": 1411966998,
			"groupIds": [
				"RH_o39PpweoUGZ_XjJvw6"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320968,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					53.215893495816786,
					-110.44809007644294
				],
				[
					131.03161366574204,
					-121.99494221445593
				]
			]
		},
		{
			"type": "line",
			"version": 191,
			"versionNonce": 583876938,
			"isDeleted": false,
			"id": "gigzSi-CNG3uQ7kaxpLy8",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 598.4202079405626,
			"y": -129.65396130463066,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 128.5214329790154,
			"height": 101.91346874854872,
			"seed": 606501642,
			"groupIds": [
				"RH_o39PpweoUGZ_XjJvw6"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320968,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					54.72200190785283,
					-92.37477514596378
				],
				[
					128.5214329790154,
					-101.91346874854872
				]
			]
		},
		{
			"type": "line",
			"version": 184,
			"versionNonce": 748277846,
			"isDeleted": false,
			"id": "wMVBzB8ar3xeHPzpPRJDB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 598.4202079405626,
			"y": -129.15193216030863,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 128.01938984864688,
			"height": 83.33811068770089,
			"seed": 1630581002,
			"groupIds": [
				"RH_o39PpweoUGZ_XjJvw6"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320968,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					56.22810332686549,
					-75.80754764845068
				],
				[
					128.01938984864688,
					-83.33811068770089
				]
			]
		},
		{
			"type": "line",
			"version": 173,
			"versionNonce": 1592428554,
			"isDeleted": false,
			"id": "pUOHgh6KHOD7G6BG5-QvA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 597.9181927822872,
			"y": -129.15193216030863,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 131.03162065876555,
			"height": 64.76273864080639,
			"seed": 1276725706,
			"groupIds": [
				"RH_o39PpweoUGZ_XjJvw6"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320968,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					58.23624787624689,
					-58.738304992662215
				],
				[
					131.03162065876555,
					-64.76273864080639
				]
			]
		},
		{
			"type": "line",
			"version": 142,
			"versionNonce": 1089033622,
			"isDeleted": false,
			"id": "mf0hbQLAUmmNOyDxmJc80",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 599.4242662292065,
			"y": -130.15600443499935,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 128.5214329790154,
			"height": 44.179250016623826,
			"seed": 1999735498,
			"groupIds": [
				"RH_o39PpweoUGZ_XjJvw6"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320968,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					54.72201589389948,
					-39.66090380144571
				],
				[
					128.5214329790154,
					-44.179250016623826
				]
			]
		},
		{
			"type": "line",
			"version": 157,
			"versionNonce": 489748170,
			"isDeleted": false,
			"id": "tohySU6EgN3L6pFFTqAdo",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 598.4202079405626,
			"y": -128.64988902993997,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 128.52140500692198,
			"height": 28.616080807754766,
			"seed": 1276345546,
			"groupIds": [
				"RH_o39PpweoUGZ_XjJvw6"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320968,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					56.228117312912154,
					-26.105921100098012
				],
				[
					128.52140500692198,
					-28.616080807754766
				]
			]
		},
		{
			"type": "text",
			"version": 254,
			"versionNonce": 1133916886,
			"isDeleted": false,
			"id": "eIeXDkeR",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 710.722272800789,
			"y": -163.2391591924923,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 15.99609375,
			"height": 4.863900632757151,
			"seed": 182703126,
			"groupIds": [
				"RH_o39PpweoUGZ_XjJvw6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320968,
			"link": null,
			"locked": false,
			"fontSize": 3.8911205062057204,
			"fontFamily": 1,
			"text": "VG = 0V",
			"rawText": "VG = 0V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "VG = 0V",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 258,
			"versionNonce": 238783882,
			"isDeleted": false,
			"id": "KV8Pgz3q",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 708.2017405164637,
			"y": -184.74617444873704,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.452606201171875,
			"height": 4.86390063275715,
			"seed": 1408895190,
			"groupIds": [
				"RH_o39PpweoUGZ_XjJvw6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320969,
			"link": null,
			"locked": false,
			"fontSize": 3.89112050620572,
			"fontFamily": 1,
			"text": "VG = 0.5V",
			"rawText": "VG = 0.5V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "VG = 0.5V",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 262,
			"versionNonce": 792029206,
			"isDeleted": false,
			"id": "gomo1fRo",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 711.8680987281687,
			"y": -203.53626028372545,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.10797119140625,
			"height": 4.863900632757151,
			"seed": 1965715606,
			"groupIds": [
				"RH_o39PpweoUGZ_XjJvw6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320969,
			"link": null,
			"locked": false,
			"fontSize": 3.8911205062057204,
			"fontFamily": 1,
			"text": "VG = 1.0V",
			"rawText": "VG = 1.0V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "VG = 1.0V",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 260,
			"versionNonce": 390417482,
			"isDeleted": false,
			"id": "qQkkW5s0",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 708.6600352929269,
			"y": -220.03487223639814,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 17.836715698242188,
			"height": 4.863900632757151,
			"seed": 1328476246,
			"groupIds": [
				"RH_o39PpweoUGZ_XjJvw6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320969,
			"link": null,
			"locked": false,
			"fontSize": 3.891120506205721,
			"fontFamily": 1,
			"text": "VG = 1.5V",
			"rawText": "VG = 1.5V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "VG = 1.5V",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 259,
			"versionNonce": 1673262422,
			"isDeleted": false,
			"id": "25H65JUJ",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 710.0349196223162,
			"y": -239.74154762431286,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.483856201171875,
			"height": 4.863900632757151,
			"seed": 274630678,
			"groupIds": [
				"RH_o39PpweoUGZ_XjJvw6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320969,
			"link": null,
			"locked": false,
			"fontSize": 3.8911205062057204,
			"fontFamily": 1,
			"text": "VG = 25V",
			"rawText": "VG = 25V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "VG = 25V",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 257,
			"versionNonce": 1042887434,
			"isDeleted": false,
			"id": "rF1Xo9qL",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 710.0349196223162,
			"y": -261.2814021180801,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.634979248046875,
			"height": 4.863900632757151,
			"seed": 1383086038,
			"groupIds": [
				"RH_o39PpweoUGZ_XjJvw6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320969,
			"link": null,
			"locked": false,
			"fontSize": 3.891120506205721,
			"fontFamily": 1,
			"text": "VG = 30V",
			"rawText": "VG = 30V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "VG = 30V",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 4504,
			"versionNonce": 71112526,
			"isDeleted": false,
			"id": "mYvqBi5s",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 393.75557918769056,
			"y": -113.56545963675597,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 341.03521728515625,
			"height": 99.96122798714552,
			"seed": 1133688086,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502078,
			"link": null,
			"locked": false,
			"fontSize": 5.712070170694029,
			"fontFamily": 1,
			"text": "    As we progress from left to right on the horizontal axis of each graph, increasing the applied voltage across each\ntransistor, we see a dramatic increase of current at first but then a \"leveling\" of current to a relatively fixed value,\nthat value dependent determined by the degree of stimulus. We call these nearly level portions of the graph the transi-\nstors ACTIVE MODE where it more or less regulates current. An active transistor does not obey Ohm's Law.\n\n    If our intention, however, is to use a BJT or a MOSFET as an on/off switch, we do not want the transistor to\nbe limiting current in any manner when we turn it on. What we'd rather have an \"on\" transistor do in any switching circuit\nis behave as similar to a conductor as possible. Since we know transistors work by introducing charge carriers into \nformerly-depleted spaces, making a transistor behave as a good conductor means flooding its interior space with a \nplentiful supply of charge carriers. In other words, we need to saturate the transistor's interior with as many charge\ncarriers as we can to turn it fully \"on\".\n\n    We see this SATURATION mode behavior in the near-vertical sections of the characteristic curves shown above:\nWhere the rise in current traces a steep upwards slope as voltage increases from zero. ",
			"rawText": "    As we progress from left to right on the horizontal axis of each graph, increasing the applied voltage across each\ntransistor, we see a dramatic increase of current at first but then a \"leveling\" of current to a relatively fixed value,\nthat value dependent determined by the degree of stimulus. We call these nearly level portions of the graph the transi-\nstors ACTIVE MODE where it more or less regulates current. An active transistor does not obey Ohm's Law.\n\n    If our intention, however, is to use a BJT or a MOSFET as an on/off switch, we do not want the transistor to\nbe limiting current in any manner when we turn it on. What we'd rather have an \"on\" transistor do in any switching circuit\nis behave as similar to a conductor as possible. Since we know transistors work by introducing charge carriers into \nformerly-depleted spaces, making a transistor behave as a good conductor means flooding its interior space with a \nplentiful supply of charge carriers. In other words, we need to saturate the transistor's interior with as many charge\ncarriers as we can to turn it fully \"on\".\n\n    We see this SATURATION mode behavior in the near-vertical sections of the characteristic curves shown above:\nWhere the rise in current traces a steep upwards slope as voltage increases from zero. ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "    As we progress from left to right on the horizontal axis of each graph, increasing the applied voltage across each\ntransistor, we see a dramatic increase of current at first but then a \"leveling\" of current to a relatively fixed value,\nthat value dependent determined by the degree of stimulus. We call these nearly level portions of the graph the transi-\nstors ACTIVE MODE where it more or less regulates current. An active transistor does not obey Ohm's Law.\n\n    If our intention, however, is to use a BJT or a MOSFET as an on/off switch, we do not want the transistor to\nbe limiting current in any manner when we turn it on. What we'd rather have an \"on\" transistor do in any switching circuit\nis behave as similar to a conductor as possible. Since we know transistors work by introducing charge carriers into \nformerly-depleted spaces, making a transistor behave as a good conductor means flooding its interior space with a \nplentiful supply of charge carriers. In other words, we need to saturate the transistor's interior with as many charge\ncarriers as we can to turn it fully \"on\".\n\n    We see this SATURATION mode behavior in the near-vertical sections of the characteristic curves shown above:\nWhere the rise in current traces a steep upwards slope as voltage increases from zero. ",
			"lineHeight": 1.25,
			"baseline": 98
		},
		{
			"type": "text",
			"version": 620,
			"versionNonce": 1115527023,
			"isDeleted": false,
			"id": "HNmmjXTJ",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 535.539831190061,
			"y": -6.407376849900004,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 67.85981750488281,
			"height": 6.920333518886798,
			"seed": 1907448726,
			"groupIds": [
				"mUAx8roq5BL33c6wHOVBK"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707327047728,
			"link": null,
			"locked": false,
			"fontSize": 2.768133407554719,
			"fontFamily": 1,
			"text": "transistor behaves as a current regulator,\nlimiting current irrespective of the applied voltage",
			"rawText": "transistor behaves as a current regulator,\nlimiting current irrespective of the applied voltage",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "transistor behaves as a current regulator,\nlimiting current irrespective of the applied voltage",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "line",
			"version": 286,
			"versionNonce": 439556054,
			"isDeleted": false,
			"id": "Kd_eoIvG9AeFKehg4R-pT",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 514.7908427587633,
			"y": 70.23788902877956,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 73.98106262711087,
			"seed": 538565718,
			"groupIds": [
				"Pfbhuyh1eo-R8h9fs41bI",
				"mUAx8roq5BL33c6wHOVBK"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320969,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-73.98106262711087
				]
			]
		},
		{
			"type": "line",
			"version": 263,
			"versionNonce": 671840394,
			"isDeleted": false,
			"id": "aONccmdY-sngYHYbFkP-W",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 499.9946230646127,
			"y": 65.73470887317134,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 120.29965094144609,
			"height": 0,
			"seed": 758767574,
			"groupIds": [
				"Pfbhuyh1eo-R8h9fs41bI",
				"mUAx8roq5BL33c6wHOVBK"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320969,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					120.29965094144609,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 264,
			"versionNonce": 1257090326,
			"isDeleted": false,
			"id": "L2RqS64ZqTsRrMgZEjpHA",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 514.7908427587633,
			"y": 67.02133433503386,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 14.152898002308802,
			"height": 61.114790086664584,
			"seed": 1868677206,
			"groupIds": [
				"Pfbhuyh1eo-R8h9fs41bI",
				"mUAx8roq5BL33c6wHOVBK"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320969,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					14.152898002308802,
					-61.114790086664584
				]
			]
		},
		{
			"type": "line",
			"version": 329,
			"versionNonce": 1709168458,
			"isDeleted": false,
			"id": "2HM4jtUzCPlrqy1VNqT3k",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 528.9437407610721,
			"y": 6.549848018389952,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 86.84733516755716,
			"height": 0,
			"seed": 1601306838,
			"groupIds": [
				"Pfbhuyh1eo-R8h9fs41bI",
				"mUAx8roq5BL33c6wHOVBK"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320969,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					75.91100978081533,
					0
				],
				[
					86.84733516755716,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 328,
			"versionNonce": 1243847254,
			"isDeleted": false,
			"id": "Cy94vBwc",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 559.2199657341828,
			"y": 10.894975633315283,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 21.858154296875,
			"height": 3.770652996536796,
			"seed": 1105456342,
			"groupIds": [
				"Pfbhuyh1eo-R8h9fs41bI",
				"mUAx8roq5BL33c6wHOVBK"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320969,
			"link": null,
			"locked": false,
			"fontSize": 3.0165223972294366,
			"fontFamily": 1,
			"text": "ACTIVE MODE",
			"rawText": "ACTIVE MODE",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "ACTIVE MODE",
			"lineHeight": 1.25,
			"baseline": 2
		},
		{
			"type": "text",
			"version": 559,
			"versionNonce": 916826607,
			"isDeleted": false,
			"id": "sQqCDbDn",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 530.6086421018543,
			"y": 36.863273373189,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 56.535675048828125,
			"height": 14.449389177799244,
			"seed": 656191190,
			"groupIds": [
				"Pfbhuyh1eo-R8h9fs41bI",
				"mUAx8roq5BL33c6wHOVBK"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414184,
			"link": null,
			"locked": false,
			"fontSize": 2.8898778355598487,
			"fontFamily": 1,
			"text": "SATURATION MODE\n\ntransistor behaves as a resistor, with \ncurrent proportional to voltage",
			"rawText": "SATURATION MODE\n\ntransistor behaves as a resistor, with \ncurrent proportional to voltage",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "SATURATION MODE\n\ntransistor behaves as a resistor, with \ncurrent proportional to voltage",
			"lineHeight": 1.25,
			"baseline": 13
		},
		{
			"type": "text",
			"version": 434,
			"versionNonce": 1588191126,
			"isDeleted": false,
			"id": "8BqPmvVF",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 545.0040394179473,
			"y": 70.23781734149497,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 55.642425537109375,
			"height": 5.057242614757069,
			"seed": 1469837462,
			"groupIds": [
				"Pfbhuyh1eo-R8h9fs41bI",
				"mUAx8roq5BL33c6wHOVBK"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320969,
			"link": null,
			"locked": false,
			"fontSize": 4.045794091805655,
			"fontFamily": 1,
			"text": "applied voltage (Vce or Vds)",
			"rawText": "applied voltage (Vce or Vds)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "applied voltage (Vce or Vds)",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 425,
			"versionNonce": 794128513,
			"isDeleted": false,
			"id": "flIqHw9w",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.71238898038469,
			"x": 481.34230848913614,
			"y": 27.464001059512924,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 47.075469970703125,
			"height": 4.371090664230147,
			"seed": 192606678,
			"groupIds": [
				"Pfbhuyh1eo-R8h9fs41bI",
				"mUAx8roq5BL33c6wHOVBK"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414189,
			"link": null,
			"locked": false,
			"fontSize": 3.496872531384118,
			"fontFamily": 1,
			"text": "resulting current (Ic or Id)",
			"rawText": "resulting current (Ic or Id)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "resulting current (Ic or Id)",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 6078,
			"versionNonce": 1441010401,
			"isDeleted": false,
			"id": "qzc5WadQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 394.2913141417784,
			"y": 79.3313160714522,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 342.7688903808594,
			"height": 64.26078942030783,
			"seed": 1232932234,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707327047733,
			"link": null,
			"locked": false,
			"fontSize": 5.712070170694029,
			"fontFamily": 1,
			"text": "    In saturated-mode transistors: we intentionally over-drive the transistor when turning it on in order to flood it's \ninterior with a super-abundance of free charge carriers to make it as good an electrical conductor as it is capable of\nbeing. This means we must design a saturated BJT switching circuit to force a base current significantly larger than\nwhat the beta ratio would ordinarily require for the expected load current. Similarly, for a saturated MOSFET switching\ncircuit, we would design it to ensure we had more gate-source voltage than would ordinarily be necessary for the expec-\nted drain current.\n    Compare the following BJT circuits, the left-hand circuit operating the transistor in its active mode and the right-\nhand circuit operates the transistor in its saturated mode, each with the same source voltage and load resistance\nvalues:",
			"rawText": "    In saturated-mode transistors: we intentionally over-drive the transistor when turning it on in order to flood it's \ninterior with a super-abundance of free charge carriers to make it as good an electrical conductor as it is capable of\nbeing. This means we must design a saturated BJT switching circuit to force a base current significantly larger than\nwhat the beta ratio would ordinarily require for the expected load current. Similarly, for a saturated MOSFET switching\ncircuit, we would design it to ensure we had more gate-source voltage than would ordinarily be necessary for the expec-\nted drain current.\n    Compare the following BJT circuits, the left-hand circuit operating the transistor in its active mode and the right-\nhand circuit operates the transistor in its saturated mode, each with the same source voltage and load resistance\nvalues:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "    In saturated-mode transistors: we intentionally over-drive the transistor when turning it on in order to flood it's \ninterior with a super-abundance of free charge carriers to make it as good an electrical conductor as it is capable of\nbeing. This means we must design a saturated BJT switching circuit to force a base current significantly larger than\nwhat the beta ratio would ordinarily require for the expected load current. Similarly, for a saturated MOSFET switching\ncircuit, we would design it to ensure we had more gate-source voltage than would ordinarily be necessary for the expec-\nted drain current.\n    Compare the following BJT circuits, the left-hand circuit operating the transistor in its active mode and the right-\nhand circuit operates the transistor in its saturated mode, each with the same source voltage and load resistance\nvalues:",
			"lineHeight": 1.25,
			"baseline": 62
		},
		{
			"type": "line",
			"version": 782,
			"versionNonce": 1091429258,
			"isDeleted": false,
			"id": "23E0mfXSMPNHpGRSQajQT",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 452.71785565879605,
			"y": 222.8112251217768,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7.395498935142382,
			"height": 0,
			"seed": 348817878,
			"groupIds": [
				"XXdZJ4SKRIuRmDq30jYb6",
				"oLB7xUtjDyTlm8ass6Vsw",
				"xu8jbDuibWaEaSauI5K9z"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320970,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.395498935142382,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 819,
			"versionNonce": 165376534,
			"isDeleted": false,
			"id": "IJ4w2P3cZs234LSimX-ET",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 460.29172945980423,
			"y": 215.59410105249978,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 14.529210297359215,
			"seed": 633790230,
			"groupIds": [
				"XXdZJ4SKRIuRmDq30jYb6",
				"oLB7xUtjDyTlm8ass6Vsw",
				"xu8jbDuibWaEaSauI5K9z"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320970,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					14.529210297359215
				]
			]
		},
		{
			"type": "line",
			"version": 856,
			"versionNonce": 693953098,
			"isDeleted": false,
			"id": "-MI-ryXRhWcnvq2ydSO25",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 460.4330146229061,
			"y": 220.23447670849848,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.943755745277265,
			"height": 4.712176312656966,
			"seed": 386305110,
			"groupIds": [
				"XXdZJ4SKRIuRmDq30jYb6",
				"oLB7xUtjDyTlm8ass6Vsw",
				"xu8jbDuibWaEaSauI5K9z"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320970,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.943755745277265,
					-4.712176312656966
				]
			]
		},
		{
			"type": "line",
			"version": 831,
			"versionNonce": 1360052054,
			"isDeleted": false,
			"id": "XogEZ-UrlBg-rBG7UUoXp",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 467.2470659561562,
			"y": 229.54427379616195,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 7.796161622973306,
			"seed": 912167318,
			"groupIds": [
				"XXdZJ4SKRIuRmDq30jYb6",
				"oLB7xUtjDyTlm8ass6Vsw",
				"xu8jbDuibWaEaSauI5K9z"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320970,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					7.796161622973306
				]
			]
		},
		{
			"type": "line",
			"version": 808,
			"versionNonce": 350095626,
			"isDeleted": false,
			"id": "jE2y1L8gnLgRA1NUtnF6e",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 467.24706595615515,
			"y": 215.92646860832153,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 7.6444537839046705,
			"seed": 1325657814,
			"groupIds": [
				"XXdZJ4SKRIuRmDq30jYb6",
				"oLB7xUtjDyTlm8ass6Vsw",
				"xu8jbDuibWaEaSauI5K9z"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320970,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-7.6444537839046705
				]
			]
		},
		{
			"type": "line",
			"version": 926,
			"versionNonce": 917136534,
			"isDeleted": false,
			"id": "JPc5AL4wjxTcG__fmsHEh",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 460.3687571041094,
			"y": 225.7008416100135,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.970892261982761,
			"height": 4.222122746266289,
			"seed": 2106303510,
			"groupIds": [
				"XXdZJ4SKRIuRmDq30jYb6",
				"oLB7xUtjDyTlm8ass6Vsw",
				"xu8jbDuibWaEaSauI5K9z"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320970,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.970892261982761,
					4.222122746266289
				]
			]
		},
		{
			"type": "line",
			"version": 1313,
			"versionNonce": 722229194,
			"isDeleted": false,
			"id": "lEOTgzV6SQSQfa8l-Suy8",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 2.148993807554163,
			"x": 465.69452137018067,
			"y": 227.17950215070934,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 2.94565729204934,
			"height": 3.494548987013066,
			"seed": 65712470,
			"groupIds": [
				"oLB7xUtjDyTlm8ass6Vsw",
				"xu8jbDuibWaEaSauI5K9z"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320970,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.4728286460246671,
					3.494548987013066
				],
				[
					1.4728286460246724,
					3.494548987013066
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 626,
			"versionNonce": 475881942,
			"isDeleted": false,
			"id": "y28qU_nmSg2w2soYOzlyo",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.2831853071795845,
			"x": 452.71785565879605,
			"y": 208.28201482441668,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 19.372280396478953,
			"height": 29.05842059471843,
			"seed": 494278294,
			"groupIds": [
				"xu8jbDuibWaEaSauI5K9z"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320970,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1610,
			"versionNonce": 1812123274,
			"isDeleted": false,
			"id": "iXsSilM2ENkU6EewbYHzp",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179579,
			"x": 425.68839597967707,
			"y": 222.67330318961692,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.058420594718495,
			"height": 6.517799797126422,
			"seed": 1390597078,
			"groupIds": [
				"dQVxzE1SMBRa2v2Tj7R0O",
				"IL4NiDSSpNnJ6MeMb7iwf"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320970,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.601348240340154,
					0
				],
				[
					6.436992411107873,
					-3.289086397713253
				],
				[
					9.620529979427882,
					3.228713399413169
				],
				[
					12.84924337884105,
					-3.2287133994131674
				],
				[
					16.07795677825421,
					3.228713399413169
				],
				[
					19.306670177667378,
					-3.2287133994131674
				],
				[
					22.535383577080545,
					3.228713399413169
				],
				[
					24.091154425267565,
					0.028712714315384184
				],
				[
					29.058420594718495,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1095,
			"versionNonce": 1698608918,
			"isDeleted": false,
			"id": "ARjaeIMT18WD7VzIz5VlF",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179579,
			"x": 425.68839597967707,
			"y": 217.6964802422103,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 29.05842059471843,
			"height": 9.686140198239698,
			"seed": 1313204502,
			"groupIds": [
				"IL4NiDSSpNnJ6MeMb7iwf"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320970,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1541,
			"versionNonce": 477916490,
			"isDeleted": false,
			"id": "nlHOsIyNS6pEw2uHr4TVg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948877,
			"x": 452.48271048524435,
			"y": 195.67781884078383,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.058420594718495,
			"height": 6.517799797126422,
			"seed": 789861974,
			"groupIds": [
				"aQ0mnqwRkgZ9OXXgxRb0y",
				"z87jT7a2XwOdD7QrTugyZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320970,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.601348240340154,
					0
				],
				[
					6.436992411107873,
					-3.289086397713253
				],
				[
					9.620529979427882,
					3.228713399413169
				],
				[
					12.84924337884105,
					-3.2287133994131674
				],
				[
					16.07795677825421,
					3.228713399413169
				],
				[
					19.306670177667378,
					-3.2287133994131674
				],
				[
					22.535383577080545,
					3.228713399413169
				],
				[
					24.091154425267565,
					0.028712714315384184
				],
				[
					29.058420594718495,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1026,
			"versionNonce": 1237541974,
			"isDeleted": false,
			"id": "g3OygtniFrFmUmkQK4Op2",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948877,
			"x": 452.5862768343812,
			"y": 190.80456224251392,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 29.05842059471843,
			"height": 9.686140198239698,
			"seed": 1579359126,
			"groupIds": [
				"z87jT7a2XwOdD7QrTugyZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320970,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 591,
			"versionNonce": 794334223,
			"isDeleted": false,
			"id": "u7zolONH",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 501.71742464679005,
			"y": 218.76039580055644,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.9843902587890625,
			"height": 6.053837623899673,
			"seed": 1638349014,
			"groupIds": [
				"c3AmYCyCcyWirksTbMP6p"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707348414190,
			"link": null,
			"locked": false,
			"fontSize": 4.843070099119738,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "ellipse",
			"version": 728,
			"versionNonce": 734030230,
			"isDeleted": false,
			"id": "Ajl3OlSVzJSh_gEb7zeqO",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 494.37210658975073,
			"y": 210.68860244877223,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.65925013390248,
			"height": 15.65925013390248,
			"seed": 825601558,
			"groupIds": [
				"2J-oB7How4lFXFzXIhTfP",
				"c3AmYCyCcyWirksTbMP6p"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320970,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 593,
			"versionNonce": 2134227041,
			"isDeleted": false,
			"id": "Rrh0JOaW",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 501.0716918201588,
			"y": 212.46440467170075,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 3.01763916015625,
			"height": 6.053837623899673,
			"seed": 163806038,
			"groupIds": [
				"c3AmYCyCcyWirksTbMP6p"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707348414191,
			"link": null,
			"locked": false,
			"fontSize": 4.843070099119738,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "line",
			"version": 651,
			"versionNonce": 1785382614,
			"isDeleted": false,
			"id": "38MvUB_jsww1TEZQnyaJh",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 502.44389994153516,
			"y": 210.20429543886027,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.3228811931926569,
			"height": 8.717526178415529,
			"seed": 1101373590,
			"groupIds": [
				"IlCbg80xWi2qD_KQOpn0k",
				"c3AmYCyCcyWirksTbMP6p"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320971,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.3228811931926569,
					-8.717526178415529
				]
			]
		},
		{
			"type": "line",
			"version": 653,
			"versionNonce": 1537882506,
			"isDeleted": false,
			"id": "oawbTGQB8RBAcmscaFIlf",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 502.8474940430874,
			"y": 226.50930056920956,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.5560855818192,
			"seed": 479272406,
			"groupIds": [
				"P5xYMVG1e819pV78-kN1T",
				"c3AmYCyCcyWirksTbMP6p"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320971,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					8.5560855818192
				]
			]
		},
		{
			"type": "line",
			"version": 408,
			"versionNonce": 911703062,
			"isDeleted": false,
			"id": "VHyDLmR0lOH2hdJzkxde9",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 467.2484219177655,
			"y": 181.49542966369856,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.01509530714465,
			"height": 33.15824023868515,
			"seed": 163635926,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320971,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-11.40643659305147
				],
				[
					35.01509530714465,
					-11.40643659305147
				],
				[
					35.01509530714461,
					21.751803645633686
				]
			]
		},
		{
			"type": "line",
			"version": 398,
			"versionNonce": 436107338,
			"isDeleted": false,
			"id": "_PPr1IINAWBQO2nzhpxZV",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 467.2484219177655,
			"y": 236.93600462328286,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.54563377234851,
			"height": 16.181216270439688,
			"seed": 416037078,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320971,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					13.793822736776324
				],
				[
					35.54563377234851,
					13.793822736776324
				],
				[
					35.54563377234851,
					-2.3873935336633645
				]
			]
		},
		{
			"type": "line",
			"version": 427,
			"versionNonce": 1702594902,
			"isDeleted": false,
			"id": "GDCk9rf4mhpNGjyCtvf-p",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 468.0442185306636,
			"y": 170.0889930706472,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 41.11621375760404,
			"height": 52.78791219331892,
			"seed": 1542227082,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320971,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-41.11621375760404,
					0
				],
				[
					-41.11621375760404,
					52.78791219331892
				]
			]
		},
		{
			"type": "text",
			"version": 231,
			"versionNonce": 40450607,
			"isDeleted": false,
			"id": "swJDTiF4",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 514.221326074317,
			"y": 214.40931216139003,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 9.051162719726562,
			"height": 8.067900550825032,
			"seed": 821840138,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414192,
			"link": null,
			"locked": false,
			"fontSize": 6.454320440660025,
			"fontFamily": 1,
			"text": "15V",
			"rawText": "15V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "15V",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 304,
			"versionNonce": 993873042,
			"isDeleted": false,
			"id": "AbsDYJZB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 438.6913456904545,
			"y": 227.40978786839477,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 4.16796875,
			"height": 2.4555797063607687,
			"seed": 1621474262,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502087,
			"link": null,
			"locked": false,
			"fontSize": 1.964463765088615,
			"fontFamily": 1,
			"text": "100k",
			"rawText": "100k",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "100k",
			"lineHeight": 1.25,
			"baseline": 1
		},
		{
			"type": "text",
			"version": 295,
			"versionNonce": 348134479,
			"isDeleted": false,
			"id": "FTaPoCm8",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 458.1221648941516,
			"y": 193.82847651281142,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.6885986328125,
			"height": 4.460637957899774,
			"seed": 1400515798,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "BlVMtnT5YSMjS79YNxW_l",
					"type": "arrow"
				}
			],
			"updated": 1707348414193,
			"link": null,
			"locked": false,
			"fontSize": 3.5685103663198188,
			"fontFamily": 1,
			"text": "1k",
			"rawText": "1k",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1k",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "image",
			"version": 521,
			"versionNonce": 2015210454,
			"isDeleted": false,
			"id": "hBbIba6p",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 411.46411716295813,
			"y": 198.5447990717947,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11.551308724972904,
			"height": 2.067076298153046,
			"seed": 42560,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "b43L1gJqkn74XvboFZJTv",
					"type": "arrow"
				}
			],
			"updated": 1707241320971,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "7ad0fd3fe0d920c915e1bc331fee6a71462e2aa0",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 440,
			"versionNonce": 1657021578,
			"isDeleted": false,
			"id": "np7AjJ7F",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 448.3374503061123,
			"y": 175.2149260885329,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.06838394132692,
			"height": 2.60089660058315,
			"seed": 79308,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "BlVMtnT5YSMjS79YNxW_l",
					"type": "arrow"
				}
			],
			"updated": 1707241320971,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "43ee42987ef430b8b83601e828cb599a7ee3a42d",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 815,
			"versionNonce": 912638230,
			"isDeleted": false,
			"id": "BlVMtnT5YSMjS79YNxW_l",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 471.425497474362,
			"y": 174.2976440730018,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 11.286620872784283,
			"seed": 1751448406,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320971,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "JtqAo99k",
				"focus": 7.242430333742734,
				"gap": 11.110618985255087
			},
			"endBinding": {
				"elementId": "Js9jo4qC",
				"focus": -3.615702352566773,
				"gap": 10.053327624894791
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					11.286620872784283
				]
			]
		},
		{
			"type": "image",
			"version": 323,
			"versionNonce": 480445258,
			"isDeleted": false,
			"id": "ryeB9uGh",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 453.3978505115122,
			"y": 208.71130128454067,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.735381328091938,
			"height": 3.3031942547975195,
			"seed": 38836,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320971,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "9157261e76b3639744c5bfde6c409db044722a17",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 492,
			"versionNonce": 897134166,
			"isDeleted": false,
			"id": "b43L1gJqkn74XvboFZJTv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 422.69259509408215,
			"y": 173.59502596889214,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 18.9185570285415,
			"seed": 1204658582,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320971,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "tdmbDTtw",
				"focus": -5.113045003083623,
				"gap": 14.791374118610307
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					18.9185570285415
				]
			]
		},
		{
			"type": "line",
			"version": 297,
			"versionNonce": 1555565066,
			"isDeleted": false,
			"id": "MT2Y2y6Ja6SNX3hODAFZ0",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 469.39201555352844,
			"y": 214.93027555410944,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.072066902078859,
			"height": 14.37086309134304,
			"seed": 951189514,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320971,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.072066902078859,
					0
				],
				[
					5.072066902078859,
					14.37086309134304
				],
				[
					0.42267175121230594,
					14.37086309134304
				]
			]
		},
		{
			"type": "line",
			"version": 319,
			"versionNonce": 1915548566,
			"isDeleted": false,
			"id": "a5hcFjYVbB5tqsLC6ndxG",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 474.30962013123616,
			"y": 186.64090605486385,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.072066902078859,
			"height": 14.37086309134304,
			"seed": 94960266,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320971,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.072066902078859,
					0
				],
				[
					5.072066902078859,
					14.37086309134304
				],
				[
					0.42267175121230594,
					14.37086309134304
				]
			]
		},
		{
			"type": "line",
			"version": 402,
			"versionNonce": 1241397450,
			"isDeleted": false,
			"id": "2mwrqOqmgf0NreJ4-Ouaa",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 2.305470122240127,
			"x": 453.70540404947616,
			"y": 226.47503536428653,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.072066902078859,
			"height": 14.37086309134304,
			"seed": 1289513238,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320972,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.072066902078859,
					0
				],
				[
					5.072066902078859,
					14.37086309134304
				],
				[
					0.42267175121230594,
					14.37086309134304
				]
			]
		},
		{
			"type": "text",
			"version": 347,
			"versionNonce": 1543090322,
			"isDeleted": false,
			"id": "RPMdPyfv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 432.339123593886,
			"y": 207.4819775161461,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.1913957213604394,
			"height": 6.402419396533775,
			"seed": 1520319830,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838500913,
			"link": null,
			"locked": false,
			"fontSize": 5.12193551722702,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "text",
			"version": 263,
			"versionNonce": 1693879454,
			"isDeleted": false,
			"id": "ZMCcX6tb",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 445.3641147192182,
			"y": 207.3137413125704,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.6433436309126839,
			"height": 5.013396663157383,
			"seed": 966910550,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707476805907,
			"link": null,
			"locked": false,
			"fontSize": 4.010717330525907,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "line",
			"version": 464,
			"versionNonce": 2125039126,
			"isDeleted": false,
			"id": "AtzSkTiqRMS6u8d7HLZp7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.71296528607089,
			"x": 437.65516095692243,
			"y": 207.54152261424517,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.072066902078859,
			"height": 14.37086309134304,
			"seed": 1664047638,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320972,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.072066902078859,
					0
				],
				[
					5.072066902078859,
					14.37086309134304
				],
				[
					0.42267175121230594,
					14.37086309134304
				]
			]
		},
		{
			"type": "text",
			"version": 360,
			"versionNonce": 1042602382,
			"isDeleted": false,
			"id": "JtqAo99k",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 481.38653020336056,
			"y": 185.4082630582569,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.1913957213604394,
			"height": 6.402419396533775,
			"seed": 1693907786,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "BlVMtnT5YSMjS79YNxW_l",
					"type": "arrow"
				}
			],
			"updated": 1707838500913,
			"link": null,
			"locked": false,
			"fontSize": 5.12193551722702,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "text",
			"version": 357,
			"versionNonce": 1180290642,
			"isDeleted": false,
			"id": "UNWKudPL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 476.4345748249613,
			"y": 213.53813933773446,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.1913957213604394,
			"height": 6.402419396533775,
			"seed": 138905482,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838500914,
			"link": null,
			"locked": false,
			"fontSize": 5.12193551722702,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "text",
			"version": 354,
			"versionNonce": 1068398542,
			"isDeleted": false,
			"id": "5u8gHeM1",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 444.8320913525618,
			"y": 231.63604516963605,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.1913957213604394,
			"height": 6.402419396533775,
			"seed": 527989706,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838500914,
			"link": null,
			"locked": false,
			"fontSize": 5.12193551722702,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "text",
			"version": 226,
			"versionNonce": 1962710082,
			"isDeleted": false,
			"id": "mAi3OKgH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 477.3752820365815,
			"y": 227.3233466777651,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.6433436309126839,
			"height": 5.013396663157383,
			"seed": 455386134,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707476805907,
			"link": null,
			"locked": false,
			"fontSize": 4.010717330525907,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 220,
			"versionNonce": 1442269406,
			"isDeleted": false,
			"id": "2NwjLfhg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 481.5731212082482,
			"y": 197.87984444057017,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.6433436309126839,
			"height": 5.013396663157383,
			"seed": 1260114902,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707476805907,
			"link": null,
			"locked": false,
			"fontSize": 4.010717330525907,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 216,
			"versionNonce": 514112514,
			"isDeleted": false,
			"id": "caJNeLuc",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 456.19940433947335,
			"y": 239.5511307556312,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.6433436309126839,
			"height": 5.013396663157383,
			"seed": 888937366,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707476805908,
			"link": null,
			"locked": false,
			"fontSize": 4.010717330525907,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 288,
			"versionNonce": 575634058,
			"isDeleted": false,
			"id": "tdmbDTtw",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 436.7755049227589,
			"y": 207.30495711604394,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 6.8162841796875,
			"height": 2.9629332791829732,
			"seed": 850711242,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "b43L1gJqkn74XvboFZJTv",
					"type": "arrow"
				}
			],
			"updated": 1707241320972,
			"link": null,
			"locked": false,
			"fontSize": 2.3703466233463786,
			"fontFamily": 1,
			"text": "14.3 v",
			"rawText": "14.3 v",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "14.3 v",
			"lineHeight": 1.25,
			"baseline": 2
		},
		{
			"type": "text",
			"version": 311,
			"versionNonce": 140692246,
			"isDeleted": false,
			"id": "Cpgx71Ur",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 446.9096882575073,
			"y": 237.88507185549813,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.9527435302734375,
			"height": 2.9629332791829732,
			"seed": 898419350,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320972,
			"link": null,
			"locked": false,
			"fontSize": 2.3703466233463786,
			"fontFamily": 1,
			"text": "0.7 v",
			"rawText": "0.7 v",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0.7 v",
			"lineHeight": 1.25,
			"baseline": 2
		},
		{
			"type": "text",
			"version": 314,
			"versionNonce": 1012111690,
			"isDeleted": false,
			"id": "Nv9uHv4M",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 477.70365179127094,
			"y": 222.14785996468706,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 7.2315216064453125,
			"height": 2.9629332791829732,
			"seed": 783780438,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320972,
			"link": null,
			"locked": false,
			"fontSize": 2.3703466233463786,
			"fontFamily": 1,
			"text": "10.71 v",
			"rawText": "10.71 v",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "10.71 v",
			"lineHeight": 1.25,
			"baseline": 2
		},
		{
			"type": "text",
			"version": 308,
			"versionNonce": 390395990,
			"isDeleted": false,
			"id": "Js9jo4qC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 481.47882509925677,
			"y": 193.03495437852186,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 7.6869049072265625,
			"height": 2.9629332791829732,
			"seed": 2109039126,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "BlVMtnT5YSMjS79YNxW_l",
					"type": "arrow"
				}
			],
			"updated": 1707241320972,
			"link": null,
			"locked": false,
			"fontSize": 2.3703466233463786,
			"fontFamily": 1,
			"text": "4.29 v",
			"rawText": "4.29 v",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "4.29 v",
			"lineHeight": 1.25,
			"baseline": 2
		},
		{
			"type": "line",
			"version": 840,
			"versionNonce": 635822090,
			"isDeleted": false,
			"id": "Tl-zBV_PDNuwUOfLMhH3G",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 619.4693125374642,
			"y": 223.68081120249872,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7.395498935142382,
			"height": 0,
			"seed": 1792750602,
			"groupIds": [
				"6SyosRExnpS7Ji_tcz2ww",
				"yOId7FHSJRRFqiA6ueJgt",
				"IKhWOCCDwAziyPq4pCJCW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320973,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.395498935142382,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 877,
			"versionNonce": 2079292822,
			"isDeleted": false,
			"id": "ecKl9oAbv2ceqkbrkcPFP",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 627.0431863384724,
			"y": 216.4636871332217,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 14.529210297359215,
			"seed": 1043079882,
			"groupIds": [
				"6SyosRExnpS7Ji_tcz2ww",
				"yOId7FHSJRRFqiA6ueJgt",
				"IKhWOCCDwAziyPq4pCJCW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320973,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					14.529210297359215
				]
			]
		},
		{
			"type": "line",
			"version": 914,
			"versionNonce": 453070538,
			"isDeleted": false,
			"id": "5j6iYndWQvM5E-lusFzA-",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 627.1844715015743,
			"y": 221.1040627892204,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.943755745277265,
			"height": 4.712176312656966,
			"seed": 1055996298,
			"groupIds": [
				"6SyosRExnpS7Ji_tcz2ww",
				"yOId7FHSJRRFqiA6ueJgt",
				"IKhWOCCDwAziyPq4pCJCW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320973,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.943755745277265,
					-4.712176312656966
				]
			]
		},
		{
			"type": "line",
			"version": 889,
			"versionNonce": 194468566,
			"isDeleted": false,
			"id": "hRmIhAjO_KmPhbuOOUN9k",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 633.9985228348244,
			"y": 230.41385987688386,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 7.796161622973306,
			"seed": 2087024714,
			"groupIds": [
				"6SyosRExnpS7Ji_tcz2ww",
				"yOId7FHSJRRFqiA6ueJgt",
				"IKhWOCCDwAziyPq4pCJCW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320973,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					7.796161622973306
				]
			]
		},
		{
			"type": "line",
			"version": 866,
			"versionNonce": 541123978,
			"isDeleted": false,
			"id": "eR8XYYjhWDybeNxBDfjJu",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 633.9985228348235,
			"y": 216.79605468904344,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 7.6444537839046705,
			"seed": 1717821194,
			"groupIds": [
				"6SyosRExnpS7Ji_tcz2ww",
				"yOId7FHSJRRFqiA6ueJgt",
				"IKhWOCCDwAziyPq4pCJCW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320973,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-7.6444537839046705
				]
			]
		},
		{
			"type": "line",
			"version": 984,
			"versionNonce": 751931414,
			"isDeleted": false,
			"id": "rxAgBJNC0wjiC54TvA27g",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 627.1202139827776,
			"y": 226.57042769073541,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.970892261982761,
			"height": 4.222122746266289,
			"seed": 963079626,
			"groupIds": [
				"6SyosRExnpS7Ji_tcz2ww",
				"yOId7FHSJRRFqiA6ueJgt",
				"IKhWOCCDwAziyPq4pCJCW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320973,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.970892261982761,
					4.222122746266289
				]
			]
		},
		{
			"type": "line",
			"version": 1371,
			"versionNonce": 1860150346,
			"isDeleted": false,
			"id": "l3ZT4jdk3eH1Z4L9jtjU5",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 2.148993807554163,
			"x": 632.4459782488489,
			"y": 228.04908823143126,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 2.94565729204934,
			"height": 3.494548987013066,
			"seed": 1787503754,
			"groupIds": [
				"yOId7FHSJRRFqiA6ueJgt",
				"IKhWOCCDwAziyPq4pCJCW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320973,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.4728286460246671,
					3.494548987013066
				],
				[
					1.4728286460246724,
					3.494548987013066
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 684,
			"versionNonce": 731061590,
			"isDeleted": false,
			"id": "N4pg1of85vNThe27UXbsN",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.2831853071795845,
			"x": 619.4693125374642,
			"y": 209.1516009051386,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 19.372280396478953,
			"height": 29.05842059471843,
			"seed": 327811914,
			"groupIds": [
				"IKhWOCCDwAziyPq4pCJCW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320973,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1668,
			"versionNonce": 1622706954,
			"isDeleted": false,
			"id": "-DlDvMK9G-TKPxd4wzkBv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179579,
			"x": 592.4398528583454,
			"y": 223.54288927033883,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.058420594718495,
			"height": 6.517799797126422,
			"seed": 1589578250,
			"groupIds": [
				"UDmsuaIT9T-ul5soz0ab2",
				"0dKnNvL45s-NcugLXRgOK"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320973,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.601348240340154,
					0
				],
				[
					6.436992411107873,
					-3.289086397713253
				],
				[
					9.620529979427882,
					3.228713399413169
				],
				[
					12.84924337884105,
					-3.2287133994131674
				],
				[
					16.07795677825421,
					3.228713399413169
				],
				[
					19.306670177667378,
					-3.2287133994131674
				],
				[
					22.535383577080545,
					3.228713399413169
				],
				[
					24.091154425267565,
					0.028712714315384184
				],
				[
					29.058420594718495,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1153,
			"versionNonce": 221315734,
			"isDeleted": false,
			"id": "KMvqR5TFUohG1_arQ40aU",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179579,
			"x": 592.4398528583454,
			"y": 218.56606632293222,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 29.05842059471843,
			"height": 9.686140198239698,
			"seed": 1931819210,
			"groupIds": [
				"0dKnNvL45s-NcugLXRgOK"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320973,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1599,
			"versionNonce": 1548130762,
			"isDeleted": false,
			"id": "_YweOS-6FiJtI0RXB9aaa",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948877,
			"x": 619.2341673639125,
			"y": 196.54740492150574,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.058420594718495,
			"height": 6.517799797126422,
			"seed": 1616351114,
			"groupIds": [
				"vN5N3mMwQPu6Gf7Y2Z4P8",
				"hp1EIJb7yboAGav00vXmC"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320973,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.601348240340154,
					0
				],
				[
					6.436992411107873,
					-3.289086397713253
				],
				[
					9.620529979427882,
					3.228713399413169
				],
				[
					12.84924337884105,
					-3.2287133994131674
				],
				[
					16.07795677825421,
					3.228713399413169
				],
				[
					19.306670177667378,
					-3.2287133994131674
				],
				[
					22.535383577080545,
					3.228713399413169
				],
				[
					24.091154425267565,
					0.028712714315384184
				],
				[
					29.058420594718495,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1084,
			"versionNonce": 1684029398,
			"isDeleted": false,
			"id": "wfsBcyjnWy2E04oS4vF8Y",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 1.5707963267948877,
			"x": 619.3377337130494,
			"y": 191.67414832323584,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 29.05842059471843,
			"height": 9.686140198239698,
			"seed": 177278538,
			"groupIds": [
				"hp1EIJb7yboAGav00vXmC"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320973,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 632,
			"versionNonce": 1729248161,
			"isDeleted": false,
			"id": "4UB9NPPR",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 668.4688815254583,
			"y": 219.62998188127835,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.9843902587890625,
			"height": 6.053837623899673,
			"seed": 380417290,
			"groupIds": [
				"HiXwu7onrisoeBFr8p5Yo"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707348414195,
			"link": null,
			"locked": false,
			"fontSize": 4.843070099119738,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "text",
			"version": 649,
			"versionNonce": 1996065519,
			"isDeleted": false,
			"id": "U1NYa99L",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 668.4688815254583,
			"y": 219.62998188127835,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.9843902587890625,
			"height": 6.053837623899673,
			"seed": 380417290,
			"groupIds": [
				"HiXwu7onrisoeBFr8p5Yo"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707348414195,
			"link": null,
			"locked": false,
			"fontSize": 4.843070099119738,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "ellipse",
			"version": 786,
			"versionNonce": 1368272714,
			"isDeleted": false,
			"id": "YZhjBw7Wvfsu5arFaP83R",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 661.123563468419,
			"y": 211.55818852949415,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.65925013390248,
			"height": 15.65925013390248,
			"seed": 1445299146,
			"groupIds": [
				"ipqJxn3xwGvnJjrX57XVf",
				"HiXwu7onrisoeBFr8p5Yo"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320974,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 634,
			"versionNonce": 929832833,
			"isDeleted": false,
			"id": "gdHvlQeG",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 667.823148698827,
			"y": 213.33399075242266,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 3.01763916015625,
			"height": 6.053837623899673,
			"seed": 857111178,
			"groupIds": [
				"HiXwu7onrisoeBFr8p5Yo"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707348414195,
			"link": null,
			"locked": false,
			"fontSize": 4.843070099119738,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "text",
			"version": 651,
			"versionNonce": 1552438543,
			"isDeleted": false,
			"id": "165xkUij",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 667.823148698827,
			"y": 213.33399075242266,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 3.01763916015625,
			"height": 6.053837623899673,
			"seed": 857111178,
			"groupIds": [
				"HiXwu7onrisoeBFr8p5Yo"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707348414196,
			"link": null,
			"locked": false,
			"fontSize": 4.843070099119738,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "line",
			"version": 709,
			"versionNonce": 319293334,
			"isDeleted": false,
			"id": "zXJkBtzFO1hNSItHUuezN",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 669.1953568202034,
			"y": 211.0738815195822,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.3228811931926569,
			"height": 8.717526178415529,
			"seed": 473602378,
			"groupIds": [
				"x-gVqTMlZ7hDiLKgp2PUA",
				"HiXwu7onrisoeBFr8p5Yo"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320974,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.3228811931926569,
					-8.717526178415529
				]
			]
		},
		{
			"type": "line",
			"version": 711,
			"versionNonce": 118383818,
			"isDeleted": false,
			"id": "rZahoWzaThusqSnCM_re2",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 669.5989509217557,
			"y": 227.37888664993147,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.5560855818192,
			"seed": 1894572042,
			"groupIds": [
				"EzFBRhoF8GVuM-mOpCNIl",
				"HiXwu7onrisoeBFr8p5Yo"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320974,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					8.5560855818192
				]
			]
		},
		{
			"type": "line",
			"version": 466,
			"versionNonce": 51291350,
			"isDeleted": false,
			"id": "VLqMl_10iIffpR4h6j41x",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 633.9998787964337,
			"y": 182.36501574442048,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.01509530714465,
			"height": 33.15824023868515,
			"seed": 1831358154,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320974,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-11.40643659305147
				],
				[
					35.01509530714465,
					-11.40643659305147
				],
				[
					35.01509530714461,
					21.751803645633686
				]
			]
		},
		{
			"type": "line",
			"version": 456,
			"versionNonce": 1983593354,
			"isDeleted": false,
			"id": "6GxyW0SGiNIMXaAgDxE7k",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 633.9998787964337,
			"y": 237.80559070400477,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.54563377234851,
			"height": 16.181216270439688,
			"seed": 361227658,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320974,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					13.793822736776324
				],
				[
					35.54563377234851,
					13.793822736776324
				],
				[
					35.54563377234851,
					-2.3873935336633645
				]
			]
		},
		{
			"type": "line",
			"version": 485,
			"versionNonce": 181377558,
			"isDeleted": false,
			"id": "p7JUEF5zv74Wiiw0tPvWd",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 634.7956754093318,
			"y": 170.95857915136912,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 41.11621375760404,
			"height": 52.78791219331892,
			"seed": 591832138,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320974,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-41.11621375760404,
					0
				],
				[
					-41.11621375760404,
					52.78791219331892
				]
			]
		},
		{
			"type": "text",
			"version": 272,
			"versionNonce": 1319012193,
			"isDeleted": false,
			"id": "iTTjHdZX",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 680.9727829529852,
			"y": 215.27889824211195,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 9.051162719726562,
			"height": 8.067900550825032,
			"seed": 1883212554,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414196,
			"link": null,
			"locked": false,
			"fontSize": 6.454320440660025,
			"fontFamily": 1,
			"text": "15V",
			"rawText": "15V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "15V",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 344,
			"versionNonce": 460914062,
			"isDeleted": false,
			"id": "YZ7opqni",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 605.4428025691227,
			"y": 228.2793739491167,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 4.16796875,
			"height": 2.4555797063607687,
			"seed": 1659738570,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502090,
			"link": null,
			"locked": false,
			"fontSize": 1.964463765088615,
			"fontFamily": 1,
			"text": "100k",
			"rawText": "100k",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "100k",
			"lineHeight": 1.25,
			"baseline": 1
		},
		{
			"type": "text",
			"version": 336,
			"versionNonce": 1190720321,
			"isDeleted": false,
			"id": "44zWQWcP",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 624.8736217728199,
			"y": 194.69806259353334,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.6885986328125,
			"height": 4.460637957899774,
			"seed": 1517015178,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "UxAhWSs1WhqgHC3PAIAXH",
					"type": "arrow"
				}
			],
			"updated": 1707348414196,
			"link": null,
			"locked": false,
			"fontSize": 3.5685103663198188,
			"fontFamily": 1,
			"text": "1k",
			"rawText": "1k",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1k",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 289,
			"versionNonce": 2008259919,
			"isDeleted": false,
			"id": "oBXauMRN",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 680.9727829529852,
			"y": 215.27889824211195,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 9.051162719726562,
			"height": 8.067900550825032,
			"seed": 1883212554,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414196,
			"link": null,
			"locked": false,
			"fontSize": 6.454320440660025,
			"fontFamily": 1,
			"text": "15V",
			"rawText": "15V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "15V",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 362,
			"versionNonce": 852093522,
			"isDeleted": false,
			"id": "JW5eQGEM",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 605.4428025691227,
			"y": 228.2793739491167,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 4.16796875,
			"height": 2.4555797063607687,
			"seed": 1659738570,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502090,
			"link": null,
			"locked": false,
			"fontSize": 1.964463765088615,
			"fontFamily": 1,
			"text": "100k",
			"rawText": "100k",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "100k",
			"lineHeight": 1.25,
			"baseline": 1
		},
		{
			"type": "text",
			"version": 353,
			"versionNonce": 890313583,
			"isDeleted": false,
			"id": "l9J7sZjG",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 624.8736217728199,
			"y": 194.69806259353334,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.6885986328125,
			"height": 4.460637957899774,
			"seed": 1517015178,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "UxAhWSs1WhqgHC3PAIAXH",
					"type": "arrow"
				}
			],
			"updated": 1707348414196,
			"link": null,
			"locked": false,
			"fontSize": 3.5685103663198188,
			"fontFamily": 1,
			"text": "1k",
			"rawText": "1k",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1k",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "image",
			"version": 579,
			"versionNonce": 1405363850,
			"isDeleted": false,
			"id": "6sBYMZRhl62s29D8o0HPp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 578.2155740416264,
			"y": 199.41438515251662,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11.551308724972904,
			"height": 2.067076298153046,
			"seed": 443887434,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "yuG5RACIPT49GVuigG5tt",
					"type": "arrow"
				}
			],
			"updated": 1707241320975,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "4ed707dc498b1c8c839ccbc6216602fd4c5930f1",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 498,
			"versionNonce": 1457446678,
			"isDeleted": false,
			"id": "Ifb8LxKBPc3UAfQj_HNSZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 615.0889071847805,
			"y": 176.08451216925482,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.06838394132692,
			"height": 2.60089660058315,
			"seed": 929347082,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "UxAhWSs1WhqgHC3PAIAXH",
					"type": "arrow"
				}
			],
			"updated": 1707241320975,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "e411680c9c312b4ac8ce918915cfe677d0a6b81c",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 1370,
			"versionNonce": 844285258,
			"isDeleted": false,
			"id": "UxAhWSs1WhqgHC3PAIAXH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 637.4746052748332,
			"y": 175.18260492190362,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.896393394580599,
			"seed": 37053642,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320975,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "64m8QrmC",
				"focus": 7.682582003744768,
				"gap": 11.09524421707519
			},
			"endBinding": {
				"elementId": "iY54lAlh",
				"focus": -14.204752320800274,
				"gap": 14.670432204807867
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					8.896393394580599
				]
			]
		},
		{
			"type": "image",
			"version": 381,
			"versionNonce": 1696500822,
			"isDeleted": false,
			"id": "QX93qeZ4mKrJ4yAZKz8F0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 620.1493073901804,
			"y": 209.58088736526258,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.735381328091938,
			"height": 3.3031942547975195,
			"seed": 1954691978,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320975,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "7dfc742828ed5a6857b746471eed2bb1ea85008b",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 931,
			"versionNonce": 1797229578,
			"isDeleted": false,
			"id": "yuG5RACIPT49GVuigG5tt",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 589.5091200089963,
			"y": 206.6180792129623,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.1368683772161603e-13,
			"height": 10.612736222193348,
			"seed": 478558794,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320975,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "hM634Dao",
				"focus": 5.113045003083611,
				"gap": 14.017841792430886
			},
			"endBinding": {
				"elementId": "hM634Dao",
				"focus": -5.113045003083606,
				"gap": 14.791374118610278
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					1.1368683772161603e-13,
					10.612736222193348
				]
			]
		},
		{
			"type": "line",
			"version": 355,
			"versionNonce": 24547734,
			"isDeleted": false,
			"id": "Wr9OUK_DJMBB-TucVSvhJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 636.1434724321966,
			"y": 215.79986163483136,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.072066902078859,
			"height": 14.37086309134304,
			"seed": 152854794,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320975,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.072066902078859,
					0
				],
				[
					5.072066902078859,
					14.37086309134304
				],
				[
					0.42267175121230594,
					14.37086309134304
				]
			]
		},
		{
			"type": "line",
			"version": 377,
			"versionNonce": 1680177866,
			"isDeleted": false,
			"id": "ibRKdBIhlUQ54xMM2DiJr",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 641.0610770099045,
			"y": 187.51049213558576,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.072066902078859,
			"height": 14.37086309134304,
			"seed": 901754826,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320975,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.072066902078859,
					0
				],
				[
					5.072066902078859,
					14.37086309134304
				],
				[
					0.42267175121230594,
					14.37086309134304
				]
			]
		},
		{
			"type": "line",
			"version": 460,
			"versionNonce": 1998319318,
			"isDeleted": false,
			"id": "lcoITs25Hku-OYucAnEnO",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 2.305470122240127,
			"x": 620.4568609281444,
			"y": 227.34462144500844,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.072066902078859,
			"height": 14.37086309134304,
			"seed": 1988830858,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320975,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.072066902078859,
					0
				],
				[
					5.072066902078859,
					14.37086309134304
				],
				[
					0.42267175121230594,
					14.37086309134304
				]
			]
		},
		{
			"type": "text",
			"version": 387,
			"versionNonce": 846214162,
			"isDeleted": false,
			"id": "e5O7ZQlK",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 599.0905804725542,
			"y": 208.351563596868,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.1913957213604394,
			"height": 6.402419396533775,
			"seed": 1681507658,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838500917,
			"link": null,
			"locked": false,
			"fontSize": 5.12193551722702,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "text",
			"version": 303,
			"versionNonce": 404127006,
			"isDeleted": false,
			"id": "8eP3BahE",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 612.1155715978864,
			"y": 208.1833273932923,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.6433436309126839,
			"height": 5.013396663157383,
			"seed": 1210485770,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707476805910,
			"link": null,
			"locked": false,
			"fontSize": 4.010717330525907,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 405,
			"versionNonce": 317345294,
			"isDeleted": false,
			"id": "Bb83L7n2",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 599.0905804725542,
			"y": 208.351563596868,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.1913957213604394,
			"height": 6.402419396533775,
			"seed": 1681507658,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838500917,
			"link": null,
			"locked": false,
			"fontSize": 5.12193551722702,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "line",
			"version": 522,
			"versionNonce": 100839766,
			"isDeleted": false,
			"id": "7SUi8Tl7FWn12ryNFZ8PD",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.71296528607089,
			"x": 604.4066178355906,
			"y": 208.41110869496708,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.072066902078859,
			"height": 14.37086309134304,
			"seed": 139229898,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320975,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.072066902078859,
					0
				],
				[
					5.072066902078859,
					14.37086309134304
				],
				[
					0.42267175121230594,
					14.37086309134304
				]
			]
		},
		{
			"type": "text",
			"version": 401,
			"versionNonce": 573825490,
			"isDeleted": false,
			"id": "PvFYzwnQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 648.1379870820288,
			"y": 186.2778491389788,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.1913957213604394,
			"height": 6.402419396533775,
			"seed": 323391882,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "UxAhWSs1WhqgHC3PAIAXH",
					"type": "arrow"
				}
			],
			"updated": 1707838500917,
			"link": null,
			"locked": false,
			"fontSize": 5.12193551722702,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "text",
			"version": 398,
			"versionNonce": 886135886,
			"isDeleted": false,
			"id": "FKRDeO2M",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 643.1860317036296,
			"y": 214.40772541845638,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.1913957213604394,
			"height": 6.402419396533775,
			"seed": 1280299082,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838500917,
			"link": null,
			"locked": false,
			"fontSize": 5.12193551722702,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "text",
			"version": 395,
			"versionNonce": 1086052242,
			"isDeleted": false,
			"id": "UBcJ8sb7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 611.58354823123,
			"y": 232.50563125035796,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.1913957213604394,
			"height": 6.402419396533775,
			"seed": 2000893706,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838500917,
			"link": null,
			"locked": false,
			"fontSize": 5.12193551722702,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "text",
			"version": 267,
			"versionNonce": 2020731842,
			"isDeleted": false,
			"id": "zLjeL1wU",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 644.1267389152497,
			"y": 228.19293275848702,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.6433436309126839,
			"height": 5.013396663157383,
			"seed": 614188490,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707476805910,
			"link": null,
			"locked": false,
			"fontSize": 4.010717330525907,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 261,
			"versionNonce": 1891969374,
			"isDeleted": false,
			"id": "5UDEduXl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 648.3245780869165,
			"y": 198.74943052129208,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.6433436309126839,
			"height": 5.013396663157383,
			"seed": 494173322,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707476805910,
			"link": null,
			"locked": false,
			"fontSize": 4.010717330525907,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 256,
			"versionNonce": 1216553858,
			"isDeleted": false,
			"id": "uAokdUy9",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 622.9508612181417,
			"y": 240.4207168363531,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.6433436309126839,
			"height": 5.013396663157383,
			"seed": 1334336330,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707476805910,
			"link": null,
			"locked": false,
			"fontSize": 4.010717330525907,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 328,
			"versionNonce": 882989898,
			"isDeleted": false,
			"id": "ESK0Wnum",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 603.5269618014272,
			"y": 208.17454319676585,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 6.8162841796875,
			"height": 2.9629332791829732,
			"seed": 959603210,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "yuG5RACIPT49GVuigG5tt",
					"type": "arrow"
				}
			],
			"updated": 1707241320976,
			"link": null,
			"locked": false,
			"fontSize": 2.3703466233463786,
			"fontFamily": 1,
			"text": "14.3 v",
			"rawText": "14.3 v",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "14.3 v",
			"lineHeight": 1.25,
			"baseline": 2
		},
		{
			"type": "text",
			"version": 352,
			"versionNonce": 1697404502,
			"isDeleted": false,
			"id": "UgBHJIlp",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 613.6611451361755,
			"y": 238.75465793622004,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.9527435302734375,
			"height": 2.9629332791829732,
			"seed": 1433243850,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320976,
			"link": null,
			"locked": false,
			"fontSize": 2.3703466233463786,
			"fontFamily": 1,
			"text": "0.7 v",
			"rawText": "0.7 v",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0.7 v",
			"lineHeight": 1.25,
			"baseline": 2
		},
		{
			"type": "text",
			"version": 416,
			"versionNonce": 321610250,
			"isDeleted": false,
			"id": "hAiSpq0T",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 643.5186541025671,
			"y": 223.2515711009871,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 6.2901458740234375,
			"height": 2.9629332791829732,
			"seed": 131393418,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320976,
			"link": null,
			"locked": false,
			"fontSize": 2.3703466233463786,
			"fontFamily": 1,
			"text": "0.3 v",
			"rawText": "0.3 v",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0.3 v",
			"lineHeight": 1.25,
			"baseline": 2
		},
		{
			"type": "text",
			"version": 418,
			"versionNonce": 456958606,
			"isDeleted": false,
			"id": "64m8QrmC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 648.1379870820288,
			"y": 186.2778491389788,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.1913957213604394,
			"height": 6.402419396533775,
			"seed": 323391882,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "UxAhWSs1WhqgHC3PAIAXH",
					"type": "arrow"
				}
			],
			"updated": 1707838500918,
			"link": null,
			"locked": false,
			"fontSize": 5.12193551722702,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "text",
			"version": 415,
			"versionNonce": 1044321618,
			"isDeleted": false,
			"id": "GQTlM1f3",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 643.1860317036296,
			"y": 214.40772541845638,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.1913957213604394,
			"height": 6.402419396533775,
			"seed": 1280299082,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838500918,
			"link": null,
			"locked": false,
			"fontSize": 5.12193551722702,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "text",
			"version": 412,
			"versionNonce": 417669326,
			"isDeleted": false,
			"id": "NSiHzSFR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 611.58354823123,
			"y": 232.50563125035796,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.1913957213604394,
			"height": 6.402419396533775,
			"seed": 2000893706,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838500918,
			"link": null,
			"locked": false,
			"fontSize": 5.12193551722702,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "text",
			"version": 285,
			"versionNonce": 1330924958,
			"isDeleted": false,
			"id": "xYCF4wiz",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 644.1267389152497,
			"y": 228.19293275848702,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.6433436309126839,
			"height": 5.013396663157383,
			"seed": 614188490,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707476805911,
			"link": null,
			"locked": false,
			"fontSize": 4.010717330525907,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 279,
			"versionNonce": 957834050,
			"isDeleted": false,
			"id": "iY54lAlh",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 648.3245780869165,
			"y": 198.74943052129208,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.6433436309126839,
			"height": 5.013396663157383,
			"seed": 494173322,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "UxAhWSs1WhqgHC3PAIAXH",
					"type": "arrow"
				}
			],
			"updated": 1707476805911,
			"link": null,
			"locked": false,
			"fontSize": 4.010717330525907,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 274,
			"versionNonce": 284486110,
			"isDeleted": false,
			"id": "cQxha81A",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 622.9508612181417,
			"y": 240.4207168363531,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.6433436309126839,
			"height": 5.013396663157383,
			"seed": 1334336330,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707476805911,
			"link": null,
			"locked": false,
			"fontSize": 4.010717330525907,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 346,
			"versionNonce": 1943763798,
			"isDeleted": false,
			"id": "hM634Dao",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 603.5269618014272,
			"y": 208.17454319676585,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 6.8162841796875,
			"height": 2.9629332791829732,
			"seed": 959603210,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "yuG5RACIPT49GVuigG5tt",
					"type": "arrow"
				}
			],
			"updated": 1707241320976,
			"link": null,
			"locked": false,
			"fontSize": 2.3703466233463786,
			"fontFamily": 1,
			"text": "14.3 v",
			"rawText": "14.3 v",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "14.3 v",
			"lineHeight": 1.25,
			"baseline": 2
		},
		{
			"type": "text",
			"version": 369,
			"versionNonce": 1714228490,
			"isDeleted": false,
			"id": "QZ3itHas",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 613.6611451361755,
			"y": 238.75465793622004,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.9527435302734375,
			"height": 2.9629332791829732,
			"seed": 1433243850,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320977,
			"link": null,
			"locked": false,
			"fontSize": 2.3703466233463786,
			"fontFamily": 1,
			"text": "0.7 v",
			"rawText": "0.7 v",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0.7 v",
			"lineHeight": 1.25,
			"baseline": 2
		},
		{
			"type": "text",
			"version": 529,
			"versionNonce": 683516054,
			"isDeleted": false,
			"id": "5WTneXTy",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 648.4644005113688,
			"y": 194.37277752613133,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.2991790771484375,
			"height": 2.9629332791829732,
			"seed": 144926282,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "UxAhWSs1WhqgHC3PAIAXH",
					"type": "arrow"
				}
			],
			"updated": 1707241320977,
			"link": null,
			"locked": false,
			"fontSize": 2.3703466233463786,
			"fontFamily": 1,
			"text": "14.7v",
			"rawText": "14.7v",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "14.7v",
			"lineHeight": 1.25,
			"baseline": 2
		},
		{
			"type": "text",
			"version": 374,
			"versionNonce": 64674762,
			"isDeleted": false,
			"id": "kZIdWeGC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 439.47661614443155,
			"y": 164.06912057549042,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 49.06452941894531,
			"height": 3.643628851498604,
			"seed": 1818992842,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "yuG5RACIPT49GVuigG5tt",
					"type": "arrow"
				}
			],
			"updated": 1707241320977,
			"link": null,
			"locked": false,
			"fontSize": 2.9149030811988834,
			"fontFamily": 1,
			"text": "TRANSISTOR IN \"ACTIVE\" MODE",
			"rawText": "TRANSISTOR IN \"ACTIVE\" MODE",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "TRANSISTOR IN \"ACTIVE\" MODE",
			"lineHeight": 1.25,
			"baseline": 2
		},
		{
			"type": "text",
			"version": 416,
			"versionNonce": 1621695958,
			"isDeleted": false,
			"id": "CIIAXexh",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 607.1795110602834,
			"y": 162.61417847211808,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 56.42918395996094,
			"height": 3.643628851498604,
			"seed": 1802963670,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320977,
			"link": null,
			"locked": false,
			"fontSize": 2.9149030811988834,
			"fontFamily": 1,
			"text": "TRANSISTOR IN \"SATURATED\" MODE",
			"rawText": "TRANSISTOR IN \"SATURATED\" MODE",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "TRANSISTOR IN \"SATURATED\" MODE",
			"lineHeight": 1.25,
			"baseline": 2
		},
		{
			"type": "text",
			"version": 219,
			"versionNonce": 652090318,
			"isDeleted": false,
			"id": "AtDP8JYf",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 404.4124283370207,
			"y": 270.8134942379392,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 94.60432434082031,
			"height": 6.7180788942909935,
			"seed": 1003916042,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502095,
			"link": null,
			"locked": false,
			"fontSize": 5.374463115432794,
			"fontFamily": 1,
			"text": "CALCULATIONS FOR SATURATION",
			"rawText": "CALCULATIONS FOR SATURATION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CALCULATIONS FOR SATURATION",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "line",
			"version": 64,
			"versionNonce": 548598550,
			"isDeleted": false,
			"id": "QTl4Jfa4Pd66un_im6XgX",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 398.2941364306123,
			"y": 277.89491376778767,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 98.29400139885968,
			"height": 0,
			"seed": 1704291146,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320977,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					98.29400139885968,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 8094,
			"versionNonce": 779743562,
			"isDeleted": false,
			"id": "c1seelS3",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 392.82050073131427,
			"y": 283.7792928646439,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 341.7196044921875,
			"height": 128.52157884061566,
			"seed": 1728432074,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320977,
			"link": null,
			"locked": false,
			"fontSize": 5.712070170694029,
			"fontFamily": 1,
			"text": "1.  First, calculate maximum possible load current assuming the transistor is fully \"on\" (ie Vce = 0 volts) for a BJT and\nVds = 0 volts for a MOSFET). You may imagine the transistor being shorted and then calculate how much current the\nload will allow for the given power supply voltage.\n\n2. FOR A BJT, use the lowest advertised beta value shown in the transistor's datasheet to calculate the amount of\nbase current to ensure at least that much load current. Your circuit's base current should be made greater than this\nto guarantee saturation just in case the real beta value is less than advertised, so consider this a low design limit.,\nbut still keeping in mind the maximum allowable transistor collector current. Choose a suitable base resistance and \nfinally calculate the transistors power dissipation based on an assumed collector-emitter voltage drop of 0.3 V and \ndetermine how much heat-sinking is needed based on the datasheet thermal ratings.\n\n3. For a MOSFET, research the transistor's turn-on or threshold gat-to-source voltage (Vgs (on)). Your circuit's gate\nvoltage will need to be more than this to guarantee saturation. So consider this a low design limit. Then research the\nmaximum allowable gate-source voltage. Your circuit's gate-source voltage will need to be less than this so as not to\nharm the transistor, so consider this a high design limit. Design your circuit so that the amount of gate-source voltage\nyou impressupon the transistor is between these two design limit. Finally, calculate transistor power dissipation based on\nthe maximum possible load current and the transistor's Rds(on) parameter specified in the data sheet, and determine\nhow much heat-sinking the transistor will require (if any)",
			"rawText": "1.  First, calculate maximum possible load current assuming the transistor is fully \"on\" (ie Vce = 0 volts) for a BJT and\nVds = 0 volts for a MOSFET). You may imagine the transistor being shorted and then calculate how much current the\nload will allow for the given power supply voltage.\n\n2. FOR A BJT, use the lowest advertised beta value shown in the transistor's datasheet to calculate the amount of\nbase current to ensure at least that much load current. Your circuit's base current should be made greater than this\nto guarantee saturation just in case the real beta value is less than advertised, so consider this a low design limit.,\nbut still keeping in mind the maximum allowable transistor collector current. Choose a suitable base resistance and \nfinally calculate the transistors power dissipation based on an assumed collector-emitter voltage drop of 0.3 V and \ndetermine how much heat-sinking is needed based on the datasheet thermal ratings.\n\n3. For a MOSFET, research the transistor's turn-on or threshold gat-to-source voltage (Vgs (on)). Your circuit's gate\nvoltage will need to be more than this to guarantee saturation. So consider this a low design limit. Then research the\nmaximum allowable gate-source voltage. Your circuit's gate-source voltage will need to be less than this so as not to\nharm the transistor, so consider this a high design limit. Design your circuit so that the amount of gate-source voltage\nyou impressupon the transistor is between these two design limit. Finally, calculate transistor power dissipation based on\nthe maximum possible load current and the transistor's Rds(on) parameter specified in the data sheet, and determine\nhow much heat-sinking the transistor will require (if any)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1.  First, calculate maximum possible load current assuming the transistor is fully \"on\" (ie Vce = 0 volts) for a BJT and\nVds = 0 volts for a MOSFET). You may imagine the transistor being shorted and then calculate how much current the\nload will allow for the given power supply voltage.\n\n2. FOR A BJT, use the lowest advertised beta value shown in the transistor's datasheet to calculate the amount of\nbase current to ensure at least that much load current. Your circuit's base current should be made greater than this\nto guarantee saturation just in case the real beta value is less than advertised, so consider this a low design limit.,\nbut still keeping in mind the maximum allowable transistor collector current. Choose a suitable base resistance and \nfinally calculate the transistors power dissipation based on an assumed collector-emitter voltage drop of 0.3 V and \ndetermine how much heat-sinking is needed based on the datasheet thermal ratings.\n\n3. For a MOSFET, research the transistor's turn-on or threshold gat-to-source voltage (Vgs (on)). Your circuit's gate\nvoltage will need to be more than this to guarantee saturation. So consider this a low design limit. Then research the\nmaximum allowable gate-source voltage. Your circuit's gate-source voltage will need to be less than this so as not to\nharm the transistor, so consider this a high design limit. Design your circuit so that the amount of gate-source voltage\nyou impressupon the transistor is between these two design limit. Finally, calculate transistor power dissipation based on\nthe maximum possible load current and the transistor's Rds(on) parameter specified in the data sheet, and determine\nhow much heat-sinking the transistor will require (if any)",
			"lineHeight": 1.25,
			"baseline": 126
		},
		{
			"type": "text",
			"version": 288,
			"versionNonce": 55582806,
			"isDeleted": false,
			"id": "eYHBiQbV",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 38.30449069107419,
			"y": 385.76879389423533,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 34.50018310546875,
			"height": 4.932202138729214,
			"seed": 77528522,
			"groupIds": [
				"R9MIoMe1h5FddYY4sjVUy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320977,
			"link": null,
			"locked": false,
			"fontSize": 3.9457617109833714,
			"fontFamily": 1,
			"text": "High side switching",
			"rawText": "High side switching",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "High side switching",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "line",
			"version": 506,
			"versionNonce": 830552074,
			"isDeleted": false,
			"id": "qNR8Hidwck96zLFotpsTg",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 87.41466492069705,
			"y": 375.0730133639175,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.461804929441249,
			"height": 28.258104370436513,
			"seed": 1996124502,
			"groupIds": [
				"kUMb3Xqx-j2Lt2P6A9_Bh",
				"nDCHksaQ30AFmV6GkxO3n",
				"R9MIoMe1h5FddYY4sjVUy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320977,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					9.136083244259726
				],
				[
					-4.249350995989811,
					9.136083244259726
				],
				[
					-4.461804929441249,
					19.546967896931235
				],
				[
					-0.637400704205893,
					19.759421830382685
				],
				[
					-0.42494677075445375,
					28.258104370436513
				]
			]
		},
		{
			"type": "line",
			"version": 449,
			"versionNonce": 206939542,
			"isDeleted": false,
			"id": "g9pbRCwiHwE2m_i__73Mx",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 80.86312358354292,
			"y": 383.7919388109731,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.21245393345143934,
			"height": 9.985937881917053,
			"seed": 411948694,
			"groupIds": [
				"kUMb3Xqx-j2Lt2P6A9_Bh",
				"nDCHksaQ30AFmV6GkxO3n",
				"R9MIoMe1h5FddYY4sjVUy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320977,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.21245393345143934,
					9.985937881917053
				]
			]
		},
		{
			"type": "line",
			"version": 461,
			"versionNonce": 1232185034,
			"isDeleted": false,
			"id": "bCaCecj6WcTTK8tCj3a_u",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 80.45028305645137,
			"y": 389.23739586262633,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.586499879361943,
			"height": 0,
			"seed": 352490454,
			"groupIds": [
				"kUMb3Xqx-j2Lt2P6A9_Bh",
				"nDCHksaQ30AFmV6GkxO3n",
				"R9MIoMe1h5FddYY4sjVUy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320977,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-6.586499879361943,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 304,
			"versionNonce": 2096661206,
			"isDeleted": false,
			"id": "xq7ONn8tqXZhSnlek-jJT",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 75.00364048671923,
			"y": 403.6829773431774,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 23.858205167996093,
			"height": 11.133824647355837,
			"seed": 1793044042,
			"groupIds": [
				"nDCHksaQ30AFmV6GkxO3n",
				"R9MIoMe1h5FddYY4sjVUy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320977,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 224,
			"versionNonce": 1323711882,
			"isDeleted": false,
			"id": "cf2Io-UR-tyZ0G76uVFD7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 86.93273753191438,
			"y": 414.4191602528107,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 19.881832101193847,
			"seed": 1385782794,
			"groupIds": [
				"nDCHksaQ30AFmV6GkxO3n",
				"R9MIoMe1h5FddYY4sjVUy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320977,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					19.881832101193847
				]
			]
		},
		{
			"type": "line",
			"version": 330,
			"versionNonce": 667793430,
			"isDeleted": false,
			"id": "d4Q6PrJ0GgBjV9yMYLWQ1",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 87.27255319644424,
			"y": 432.71583062261084,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.1778169007219368,
			"height": 7.468765687602083,
			"seed": 1962491658,
			"groupIds": [
				"8LlnpvSTxRUqXkPQEVxUt",
				"nDCHksaQ30AFmV6GkxO3n",
				"R9MIoMe1h5FddYY4sjVUy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320977,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.1778169007219368,
					7.468765687602083
				]
			]
		},
		{
			"type": "line",
			"version": 342,
			"versionNonce": 1327103050,
			"isDeleted": false,
			"id": "II1JadnM0x4e0YTT_KGiv",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 82.47120382584288,
			"y": 440.1845963102129,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9.780515641924614,
			"height": 0.17783318133910597,
			"seed": 240176586,
			"groupIds": [
				"8LlnpvSTxRUqXkPQEVxUt",
				"nDCHksaQ30AFmV6GkxO3n",
				"R9MIoMe1h5FddYY4sjVUy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320978,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.780515641924614,
					-0.17783318133910597
				]
			]
		},
		{
			"type": "line",
			"version": 348,
			"versionNonce": 1154106710,
			"isDeleted": false,
			"id": "1lCjr6_Du800AQWAIzlMU",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 85.2275285932046,
			"y": 441.87395455077433,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.26788238781836,
			"height": 0.17783318133910597,
			"seed": 457737354,
			"groupIds": [
				"8LlnpvSTxRUqXkPQEVxUt",
				"nDCHksaQ30AFmV6GkxO3n",
				"R9MIoMe1h5FddYY4sjVUy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320978,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.26788238781836,
					0.17783318133910597
				]
			]
		},
		{
			"type": "line",
			"version": 338,
			"versionNonce": 2011685642,
			"isDeleted": false,
			"id": "CxwnHg1rjWlT4C0X_baO6",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 87.0947362957223,
			"y": 443.65223752231384,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.0669665268002977,
			"height": 0,
			"seed": 94069578,
			"groupIds": [
				"8LlnpvSTxRUqXkPQEVxUt",
				"nDCHksaQ30AFmV6GkxO3n",
				"R9MIoMe1h5FddYY4sjVUy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320978,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.0669665268002977,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 287,
			"versionNonce": 1383911442,
			"isDeleted": false,
			"id": "vGSYxb1o",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 80.05394312520772,
			"y": 407.54825310143224,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.654403686523438,
			"height": 6.631208169721408,
			"seed": 536649546,
			"groupIds": [
				"nDCHksaQ30AFmV6GkxO3n",
				"R9MIoMe1h5FddYY4sjVUy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502099,
			"link": null,
			"locked": false,
			"fontSize": 5.304966535777126,
			"fontFamily": 1,
			"text": "Load",
			"rawText": "Load",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Load",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "line",
			"version": 338,
			"versionNonce": 63631818,
			"isDeleted": false,
			"id": "sVwEsGW-xji0kAtt6oQE-",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 87.62885609744191,
			"y": 371.29285405416414,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.2193439177291594,
			"height": 9.213006861938046,
			"seed": 467207446,
			"groupIds": [
				"5hvovu4gVgxPp6SrMs2Ky",
				"7SJ9kTcbNzxn3yjO4fwQ9",
				"nDCHksaQ30AFmV6GkxO3n",
				"R9MIoMe1h5FddYY4sjVUy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320978,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.2193439177291594,
					9.213006861938046
				]
			]
		},
		{
			"type": "line",
			"version": 337,
			"versionNonce": 669870038,
			"isDeleted": false,
			"id": "CrIuZZ5L5jaq2eweu0gpF",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 83.24171666696324,
			"y": 370.6347821354543,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9.432370862428396,
			"height": 0,
			"seed": 333705814,
			"groupIds": [
				"7SJ9kTcbNzxn3yjO4fwQ9",
				"nDCHksaQ30AFmV6GkxO3n",
				"R9MIoMe1h5FddYY4sjVUy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320978,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.432370862428396,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 267,
			"versionNonce": 635316362,
			"isDeleted": false,
			"id": "o4TI0fiJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 83.66732520522339,
			"y": 363.05389180423504,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 7.7799530029296875,
			"height": 8.53723206924,
			"seed": 1861731210,
			"groupIds": [
				"nDCHksaQ30AFmV6GkxO3n",
				"R9MIoMe1h5FddYY4sjVUy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320978,
			"link": null,
			"locked": false,
			"fontSize": 6.829785655392,
			"fontFamily": 1,
			"text": "+V",
			"rawText": "+V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+V",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 273,
			"versionNonce": 286267023,
			"isDeleted": false,
			"id": "xfQPBU09",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 89.51455080481506,
			"y": 396.31206029889773,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 4.684738948999503,
			"height": 9.398290319818399,
			"seed": 218888406,
			"groupIds": [
				"nDCHksaQ30AFmV6GkxO3n",
				"R9MIoMe1h5FddYY4sjVUy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414204,
			"link": null,
			"locked": false,
			"fontSize": 7.518632255854718,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 265,
			"versionNonce": 1015378446,
			"isDeleted": false,
			"id": "GJMQqmMM",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 91.12100846818558,
			"y": 417.06869590357314,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.516815185546875,
			"height": 3.8279170978852313,
			"seed": 261479894,
			"groupIds": [
				"nDCHksaQ30AFmV6GkxO3n",
				"R9MIoMe1h5FddYY4sjVUy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502101,
			"link": null,
			"locked": false,
			"fontSize": 3.062333678308185,
			"fontFamily": 1,
			"text": "_",
			"rawText": "_",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "_",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 356,
			"versionNonce": 1313668562,
			"isDeleted": false,
			"id": "dc9REdhB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 93.34123963452433,
			"y": 386.80537790934983,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 31.195220947265625,
			"height": 8.016910573813057,
			"seed": 1044679242,
			"groupIds": [
				"nDCHksaQ30AFmV6GkxO3n",
				"R9MIoMe1h5FddYY4sjVUy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502102,
			"link": null,
			"locked": false,
			"fontSize": 3.206764229525223,
			"fontFamily": 1,
			"text": "transistor sources\ncurrent to the load",
			"rawText": "transistor sources\ncurrent to the load",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "transistor sources\ncurrent to the load",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "line",
			"version": 487,
			"versionNonce": 1545670154,
			"isDeleted": false,
			"id": "KNlB3Ltm9gRqg_r_bXncf",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 235.23095768883775,
			"y": 398.82776701794177,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.008467208543471,
			"height": 31.720299599170048,
			"seed": 880450442,
			"groupIds": [
				"BesUN72jqraWYjWhQRQIs",
				"dEps7rcjHUdRGyGxN6CHx"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320978,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					10.255440133983742
				],
				[
					-4.769983326830861,
					10.255440133983742
				],
				[
					-5.008467208543471,
					21.9418708989799
				],
				[
					-0.7154953155062104,
					22.180354780692525
				],
				[
					-0.4770114337935997,
					31.720299599170048
				]
			]
		},
		{
			"type": "line",
			"version": 430,
			"versionNonce": 1019621270,
			"isDeleted": false,
			"id": "yAMeZrC-iFbEDOLsFGu1u",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 227.87671865968716,
			"y": 408.6149390001068,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.2384838817126108,
			"height": 11.209419331202557,
			"seed": 2121439818,
			"groupIds": [
				"BesUN72jqraWYjWhQRQIs",
				"dEps7rcjHUdRGyGxN6CHx"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320978,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.2384838817126108,
					11.209419331202557
				]
			]
		},
		{
			"type": "line",
			"version": 442,
			"versionNonce": 2108079306,
			"isDeleted": false,
			"id": "siSeopIj4cDSYOrPYampH",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 227.41329673179152,
			"y": 414.72757581638126,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7.393480707143092,
			"height": 0,
			"seed": 779927818,
			"groupIds": [
				"BesUN72jqraWYjWhQRQIs",
				"dEps7rcjHUdRGyGxN6CHx"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320978,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-7.393480707143092,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 265,
			"versionNonce": 583519446,
			"isDeleted": false,
			"id": "RIkVsw5_w63JpvIweWIeo",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 235.07143437436622,
			"y": 429.1636349128003,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.19960310467947298,
			"height": 8.383842105650759,
			"seed": 1022764362,
			"groupIds": [
				"93IdW0lgRxqDM6rH4iDm7",
				"dEps7rcjHUdRGyGxN6CHx"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320978,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.19960310467947298,
					8.383842105650759
				]
			]
		},
		{
			"type": "line",
			"version": 277,
			"versionNonce": 671650698,
			"isDeleted": false,
			"id": "gLEBXB_MqdLiZFsNsrGxV",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 229.68182159216218,
			"y": 437.547477018451,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.978828669087592,
			"height": 0.19962138000493346,
			"seed": 173468682,
			"groupIds": [
				"93IdW0lgRxqDM6rH4iDm7",
				"dEps7rcjHUdRGyGxN6CHx"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320978,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.978828669087592,
					-0.19962138000493346
				]
			]
		},
		{
			"type": "line",
			"version": 283,
			"versionNonce": 690209302,
			"isDeleted": false,
			"id": "eKqtzy0dG5QwRlfV5vk5f",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 232.77585246794862,
			"y": 439.44381616485884,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.79078519284018,
			"height": 0.19962138000493346,
			"seed": 1701894858,
			"groupIds": [
				"93IdW0lgRxqDM6rH4iDm7",
				"dEps7rcjHUdRGyGxN6CHx"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320979,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.79078519284018,
					0.19962138000493346
				]
			]
		},
		{
			"type": "line",
			"version": 273,
			"versionNonce": 1031901770,
			"isDeleted": false,
			"id": "dKAV4kVC6WaobtmK6wOlJ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 234.8718312696868,
			"y": 441.4399751389319,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.19769172937868,
			"height": 0,
			"seed": 215937418,
			"groupIds": [
				"93IdW0lgRxqDM6rH4iDm7",
				"dEps7rcjHUdRGyGxN6CHx"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320979,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.19769172937868,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 301,
			"versionNonce": 47124310,
			"isDeleted": false,
			"id": "xg7LwptZ4JlZD01yI3mAC",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 234.13232116774333,
			"y": 375.3911752299539,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.24621802985849633,
			"height": 10.341788466731819,
			"seed": 1849923338,
			"groupIds": [
				"bGgv01bgmvihLfWv8fLbB",
				"-Q7mPZNclVdSwOkRLSOnK",
				"U0vKPu3Ujcl2FhEoGsZww",
				"dEps7rcjHUdRGyGxN6CHx"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320979,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.24621802985849633,
					10.341788466731819
				]
			]
		},
		{
			"type": "line",
			"version": 300,
			"versionNonce": 552384778,
			"isDeleted": false,
			"id": "k9chWKQ4dPNzSaIoltieN",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 229.20766750754575,
			"y": 374.6524760537586,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.588029039900134,
			"height": 0,
			"seed": 479208906,
			"groupIds": [
				"-Q7mPZNclVdSwOkRLSOnK",
				"U0vKPu3Ujcl2FhEoGsZww",
				"dEps7rcjHUdRGyGxN6CHx"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320979,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.588029039900134,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 233,
			"versionNonce": 739547922,
			"isDeleted": false,
			"id": "PiUmBjUY",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 229.23907324747873,
			"y": 365.69642320301557,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 8.733156226097563,
			"height": 9.583217452733615,
			"seed": 1474092170,
			"groupIds": [
				"U0vKPu3Ujcl2FhEoGsZww",
				"dEps7rcjHUdRGyGxN6CHx"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838500932,
			"link": null,
			"locked": false,
			"fontSize": 7.666573962186893,
			"fontFamily": 1,
			"text": "+V",
			"rawText": "+V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+V",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "rectangle",
			"version": 330,
			"versionNonce": 566560714,
			"isDeleted": false,
			"id": "w7TlI6flDQRKLE90jsK-Z",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 221.299329147248,
			"y": 386.3075105959615,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.781322834204428,
			"height": 12.497945682026494,
			"seed": 269750218,
			"groupIds": [
				"vEy5bnRf5eBrku6zIIbEx",
				"dEps7rcjHUdRGyGxN6CHx"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320979,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 315,
			"versionNonce": 1197998158,
			"isDeleted": false,
			"id": "hwPKcle9",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 226.96839705991846,
			"y": 389.75361479783413,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.20482672593246,
			"height": 7.443666676668088,
			"seed": 870068298,
			"groupIds": [
				"vEy5bnRf5eBrku6zIIbEx",
				"dEps7rcjHUdRGyGxN6CHx"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502102,
			"link": null,
			"locked": false,
			"fontSize": 5.9549333413344705,
			"fontFamily": 1,
			"text": "Load",
			"rawText": "Load",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Load",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "text",
			"version": 305,
			"versionNonce": 1488152786,
			"isDeleted": false,
			"id": "bslocdtl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 235.80269103395892,
			"y": 378.47984169850884,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.258715201067458,
			"height": 10.549772934397799,
			"seed": 1575271242,
			"groupIds": [
				"vEy5bnRf5eBrku6zIIbEx",
				"dEps7rcjHUdRGyGxN6CHx"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838500932,
			"link": null,
			"locked": false,
			"fontSize": 8.439818347518239,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "text",
			"version": 291,
			"versionNonce": 1129411474,
			"isDeleted": false,
			"id": "DP2i0iJc",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 237.1596240470202,
			"y": 400.88686736602483,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.8251764759142763,
			"height": 4.29691516437093,
			"seed": 2097332746,
			"groupIds": [
				"vEy5bnRf5eBrku6zIIbEx",
				"dEps7rcjHUdRGyGxN6CHx"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502102,
			"link": null,
			"locked": false,
			"fontSize": 3.4375321314967433,
			"fontFamily": 1,
			"text": "_",
			"rawText": "_",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "_",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 485,
			"versionNonce": 1801373326,
			"isDeleted": false,
			"id": "LYlaiYPK",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 238.75915694829933,
			"y": 410.2121669311763,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 38.54071044921875,
			"height": 8.999145941549804,
			"seed": 3272906,
			"groupIds": [
				"dEps7rcjHUdRGyGxN6CHx"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502103,
			"link": null,
			"locked": false,
			"fontSize": 3.5996583766199213,
			"fontFamily": 1,
			"text": "transistor sinks form\ncurrent from the load",
			"rawText": "transistor sinks form\ncurrent from the load",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "transistor sinks form\ncurrent from the load",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 268,
			"versionNonce": 1104786518,
			"isDeleted": false,
			"id": "SM0Av0cN",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 191.48445560274286,
			"y": 412.424154634334,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 28.29559326171875,
			"height": 4.740498066327722,
			"seed": 829899210,
			"groupIds": [
				"dEps7rcjHUdRGyGxN6CHx"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320979,
			"link": null,
			"locked": false,
			"fontSize": 3.7923984530621775,
			"fontFamily": 1,
			"text": "Low-side switch",
			"rawText": "Low-side switch",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Low-side switch",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 63,
			"versionNonce": 433478049,
			"isDeleted": false,
			"id": "5QO6NEE2",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 84.95496635139074,
			"y": -367.3228812776438,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 131.2598876953125,
			"height": 25,
			"seed": 886012310,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414207,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "BJT SWITCH",
			"rawText": "BJT SWITCH",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "BJT SWITCH",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 332,
			"versionNonce": 1821161878,
			"isDeleted": false,
			"id": "YRzIztBuBwyQTr1HVjAFS",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 79.7784748835762,
			"y": 515.2295409864854,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 23.858205167996093,
			"height": 11.133824647355837,
			"seed": 1666838486,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320979,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 252,
			"versionNonce": 2061882058,
			"isDeleted": false,
			"id": "7Mf52sIPeJM0UjAS4Ztn6",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 91.70757192877136,
			"y": 525.9657238961187,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 19.881832101193847,
			"seed": 2038007062,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320979,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					19.881832101193847
				]
			]
		},
		{
			"type": "line",
			"version": 359,
			"versionNonce": 1831671510,
			"isDeleted": false,
			"id": "4RD07oUv1VS5oqiNyonij",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 91.64927732254145,
			"y": 544.2623942659189,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.1778169007219368,
			"height": 7.468765687602083,
			"seed": 1769239126,
			"groupIds": [
				"514Sx0-tveelIZEyPXAHg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320979,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.1778169007219368,
					7.468765687602083
				]
			]
		},
		{
			"type": "line",
			"version": 371,
			"versionNonce": 418703754,
			"isDeleted": false,
			"id": "LFnFnJSXTW8khUT_p_s42",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 86.84792795194008,
			"y": 551.7311599535209,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9.780515641924614,
			"height": 0.17783318133910597,
			"seed": 236959638,
			"groupIds": [
				"514Sx0-tveelIZEyPXAHg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320980,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.780515641924614,
					-0.17783318133910597
				]
			]
		},
		{
			"type": "line",
			"version": 377,
			"versionNonce": 1280298006,
			"isDeleted": false,
			"id": "po2qasKclXAP1tWjNg2JP",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 89.6042527193018,
			"y": 553.4205181940823,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.26788238781836,
			"height": 0.17783318133910597,
			"seed": 531649750,
			"groupIds": [
				"514Sx0-tveelIZEyPXAHg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320980,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.26788238781836,
					0.17783318133910597
				]
			]
		},
		{
			"type": "line",
			"version": 367,
			"versionNonce": 980625482,
			"isDeleted": false,
			"id": "sd_-muXct6YboIscPC8BV",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 91.4714604218195,
			"y": 555.1988011656218,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.0669665268002977,
			"height": 0,
			"seed": 129714710,
			"groupIds": [
				"514Sx0-tveelIZEyPXAHg"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320980,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.0669665268002977,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 314,
			"versionNonce": 331428178,
			"isDeleted": false,
			"id": "aA9znVVn",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 84.82877752206468,
			"y": 519.0948167447403,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.654403686523438,
			"height": 6.631208169721408,
			"seed": 892704598,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502104,
			"link": null,
			"locked": false,
			"fontSize": 5.304966535777126,
			"fontFamily": 1,
			"text": "Load",
			"rawText": "Load",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Load",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "line",
			"version": 366,
			"versionNonce": 2000391946,
			"isDeleted": false,
			"id": "ladrCATDHc31C2Wtuvytb",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 92.40369049429887,
			"y": 482.8394176974722,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.2193439177291594,
			"height": 9.213006861938046,
			"seed": 1886665878,
			"groupIds": [
				"XglSwHrs0-JdGRcCL6iR9",
				"1SR7a8LKR-HG4mSWkemtj"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320980,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.2193439177291594,
					9.213006861938046
				]
			]
		},
		{
			"type": "line",
			"version": 365,
			"versionNonce": 1464876694,
			"isDeleted": false,
			"id": "Bht_r6dbw2Peo4VEMzRjy",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 88.0165510638202,
			"y": 482.1813457787624,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9.432370862428396,
			"height": 0,
			"seed": 791427542,
			"groupIds": [
				"1SR7a8LKR-HG4mSWkemtj"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320980,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.432370862428396,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 294,
			"versionNonce": 868818378,
			"isDeleted": false,
			"id": "Vw6d3hZs",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 88.44215960208035,
			"y": 474.60045544754314,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 7.7799530029296875,
			"height": 8.53723206924,
			"seed": 1752338198,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320980,
			"link": null,
			"locked": false,
			"fontSize": 6.829785655392,
			"fontFamily": 1,
			"text": "+V",
			"rawText": "+V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+V",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 300,
			"versionNonce": 2013035905,
			"isDeleted": false,
			"id": "LE33sASj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 94.28938520167202,
			"y": 507.8586239422058,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 4.684738948999503,
			"height": 9.398290319818399,
			"seed": 1757166678,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414208,
			"link": null,
			"locked": false,
			"fontSize": 7.518632255854718,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 292,
			"versionNonce": 1763886286,
			"isDeleted": false,
			"id": "GZcHSbfE",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 95.89584286504254,
			"y": 528.6152595468812,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.516815185546875,
			"height": 3.8279170978852313,
			"seed": 635322774,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502104,
			"link": null,
			"locked": false,
			"fontSize": 3.062333678308185,
			"fontFamily": 1,
			"text": "_",
			"rawText": "_",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "_",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 383,
			"versionNonce": 1123235602,
			"isDeleted": false,
			"id": "nhmllACv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 98.11607403138129,
			"y": 498.3519415526579,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 31.195220947265625,
			"height": 8.016910573813057,
			"seed": 319659734,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502104,
			"link": null,
			"locked": false,
			"fontSize": 3.206764229525223,
			"fontFamily": 1,
			"text": "transistor sources\ncurrent to the load",
			"rawText": "transistor sources\ncurrent to the load",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "transistor sources\ncurrent to the load",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "line",
			"version": 322,
			"versionNonce": 1161802570,
			"isDeleted": false,
			"id": "4mr_xFYm7ydhe8JB_eYKY",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 235.46470643234179,
			"y": 533.1459925019998,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.19960310467947298,
			"height": 8.383842105650759,
			"seed": 747930582,
			"groupIds": [
				"n1VePMblIwvzglt4i9OP6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320980,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.19960310467947298,
					8.383842105650759
				]
			]
		},
		{
			"type": "line",
			"version": 334,
			"versionNonce": 1983872598,
			"isDeleted": false,
			"id": "6isoSMB4SkseNxKzq7CQd",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 230.07509365013775,
			"y": 541.5298346076505,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.978828669087592,
			"height": 0.19962138000493346,
			"seed": 1715575062,
			"groupIds": [
				"n1VePMblIwvzglt4i9OP6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320980,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.978828669087592,
					-0.19962138000493346
				]
			]
		},
		{
			"type": "line",
			"version": 340,
			"versionNonce": 775862794,
			"isDeleted": false,
			"id": "UR4jT1vGC-Mv9TGrVApck",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 233.16912452592422,
			"y": 543.4261737540584,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.79078519284018,
			"height": 0.19962138000493346,
			"seed": 739903062,
			"groupIds": [
				"n1VePMblIwvzglt4i9OP6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320980,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.79078519284018,
					0.19962138000493346
				]
			]
		},
		{
			"type": "line",
			"version": 330,
			"versionNonce": 1705591702,
			"isDeleted": false,
			"id": "Vs5fYf6UDwYjGnDB-VgYn",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 235.2651033276624,
			"y": 545.4223327281314,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.19769172937868,
			"height": 0,
			"seed": 250792854,
			"groupIds": [
				"n1VePMblIwvzglt4i9OP6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320980,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.19769172937868,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 333,
			"versionNonce": 388950218,
			"isDeleted": false,
			"id": "fG7-qE-5htdryf9TCezy9",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 234.92371458744594,
			"y": 486.937738873262,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.24621802985849633,
			"height": 10.341788466731819,
			"seed": 1023469782,
			"groupIds": [
				"u29TYbmiBhzo_XfJm97H6",
				"IRnEP4u_fZPQAaU1jtuRG",
				"Zomx3yGCA9dlXjOHZu4UP"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320980,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.24621802985849633,
					10.341788466731819
				]
			]
		},
		{
			"type": "line",
			"version": 332,
			"versionNonce": 1713922262,
			"isDeleted": false,
			"id": "Ba7RnUyo5eaCa_k4-Ffke",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 229.99906092724837,
			"y": 486.1990396970667,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.588029039900134,
			"height": 0,
			"seed": 1440308758,
			"groupIds": [
				"IRnEP4u_fZPQAaU1jtuRG",
				"Zomx3yGCA9dlXjOHZu4UP"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320981,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.588029039900134,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 264,
			"versionNonce": 733118098,
			"isDeleted": false,
			"id": "mv56UUqS",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 230.03046666718137,
			"y": 477.24298684632356,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 8.733156226097563,
			"height": 9.583217452733615,
			"seed": 1047604054,
			"groupIds": [
				"Zomx3yGCA9dlXjOHZu4UP"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838500936,
			"link": null,
			"locked": false,
			"fontSize": 7.666573962186893,
			"fontFamily": 1,
			"text": "+V",
			"rawText": "+V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+V",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "rectangle",
			"version": 362,
			"versionNonce": 1532089878,
			"isDeleted": false,
			"id": "JnMo2gXhPPRri2zMzgH3F",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 222.0907225669506,
			"y": 497.8540742392696,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.781322834204428,
			"height": 12.497945682026494,
			"seed": 1964855446,
			"groupIds": [
				"Cf0EUqtfCe0OuuUABPu8M"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320981,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 346,
			"versionNonce": 38599438,
			"isDeleted": false,
			"id": "kcXZFyAg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 227.75979047962107,
			"y": 501.3001784411422,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.20482672593246,
			"height": 7.443666676668088,
			"seed": 1704119766,
			"groupIds": [
				"Cf0EUqtfCe0OuuUABPu8M"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502104,
			"link": null,
			"locked": false,
			"fontSize": 5.9549333413344705,
			"fontFamily": 1,
			"text": "Load",
			"rawText": "Load",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Load",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "text",
			"version": 336,
			"versionNonce": 29940818,
			"isDeleted": false,
			"id": "RBwiYXFv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 236.5940844536616,
			"y": 490.02640534181694,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.258715201067458,
			"height": 10.549772934397799,
			"seed": 1021747990,
			"groupIds": [
				"Cf0EUqtfCe0OuuUABPu8M"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838500936,
			"link": null,
			"locked": false,
			"fontSize": 8.439818347518239,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "text",
			"version": 322,
			"versionNonce": 1365148882,
			"isDeleted": false,
			"id": "f17dAQae",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 237.95101746672287,
			"y": 512.4334310093328,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.8251764759142763,
			"height": 4.29691516437093,
			"seed": 1032704086,
			"groupIds": [
				"Cf0EUqtfCe0OuuUABPu8M"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502104,
			"link": null,
			"locked": false,
			"fontSize": 3.4375321314967433,
			"fontFamily": 1,
			"text": "_",
			"rawText": "_",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "_",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 516,
			"versionNonce": 1565944142,
			"isDeleted": false,
			"id": "AezTxbyK",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 239.55055036800195,
			"y": 521.7587305744843,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 38.54071044921875,
			"height": 8.999145941549804,
			"seed": 324883862,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502104,
			"link": null,
			"locked": false,
			"fontSize": 3.5996583766199213,
			"fontFamily": 1,
			"text": "transistor sinks form\ncurrent from the load",
			"rawText": "transistor sinks form\ncurrent from the load",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "transistor sinks form\ncurrent from the load",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "line",
			"version": 416,
			"versionNonce": 265761738,
			"isDeleted": false,
			"id": "NioDTjNorx-YrbJ4NgQrn",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 48.8778034232128,
			"y": 486.10436342254974,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.2193439177291594,
			"height": 9.213006861938046,
			"seed": 34105238,
			"groupIds": [
				"I0fipOnd3rLrpax93k5tp",
				"Lj5OkUrITwQrsIQrIXVF2"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320981,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.2193439177291594,
					9.213006861938046
				]
			]
		},
		{
			"type": "line",
			"version": 415,
			"versionNonce": 1665025494,
			"isDeleted": false,
			"id": "FWBCNUOnqpHnDstCztVvL",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 44.49066399273413,
			"y": 485.44629150384,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9.432370862428396,
			"height": 0,
			"seed": 1929577686,
			"groupIds": [
				"Lj5OkUrITwQrsIQrIXVF2"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320981,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.432370862428396,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 336,
			"versionNonce": 722610826,
			"isDeleted": false,
			"id": "1a48Ciwy",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 44.557110653752986,
			"y": 478.2245680527437,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 7.7799530029296875,
			"height": 8.53723206924,
			"seed": 1027078678,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320981,
			"link": null,
			"locked": false,
			"fontSize": 6.829785655392,
			"fontFamily": 1,
			"text": "+V",
			"rawText": "+V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+V",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "line",
			"version": 232,
			"versionNonce": 1717771030,
			"isDeleted": false,
			"id": "TstclXvdyJ-cA2-tf8Q0u",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 53.167938761406745,
			"y": 502.67865151169866,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8.095699243028422,
			"height": 0.1587440451796578,
			"seed": 842677206,
			"groupIds": [
				"dIRtK-jDPTgMDSYWuqu9h"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320981,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.095699243028422,
					0.1587440451796578
				]
			]
		},
		{
			"type": "ellipse",
			"version": 202,
			"versionNonce": 2034256202,
			"isDeleted": false,
			"id": "h7Q63Fe0mHYuURoWKoA1f",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 61.581126094794485,
			"y": 501.6468370175427,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.9048704101243346,
			"height": 1.9048704101243346,
			"seed": 510677270,
			"groupIds": [
				"dIRtK-jDPTgMDSYWuqu9h"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320981,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 201,
			"versionNonce": 1891321942,
			"isDeleted": false,
			"id": "THHuGZNk2omgq8w8ZiGCk",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 63.168508414559504,
			"y": 501.7262163066365,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.714611230373004,
			"height": 3.809740820248669,
			"seed": 1571929686,
			"groupIds": [
				"dIRtK-jDPTgMDSYWuqu9h"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320981,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.714611230373004,
					-3.809740820248669
				]
			]
		},
		{
			"type": "line",
			"version": 161,
			"versionNonce": 29134858,
			"isDeleted": false,
			"id": "x9H3L-nEL0aVWbm7Bo4az",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 71.74042526011901,
			"y": 502.519907466519,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8.25445782121597,
			"height": 0.15872951217176806,
			"seed": 617841558,
			"groupIds": [
				"dIRtK-jDPTgMDSYWuqu9h"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320981,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.25445782121597,
					-0.15872951217176806
				]
			]
		},
		{
			"type": "line",
			"version": 126,
			"versionNonce": 1914424726,
			"isDeleted": false,
			"id": "lMUhwAKzPg84MQyIF998a",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 48.99335072137361,
			"y": 495.52078506870726,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.134033203125014,
			"height": 7.183247550589101,
			"seed": 1553848842,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320981,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					7.183247550589101
				],
				[
					11.134033203125014,
					7.183247550589101
				]
			]
		},
		{
			"type": "line",
			"version": 462,
			"versionNonce": 679608010,
			"isDeleted": false,
			"id": "PsiKm9eDjkR6glU0YdZYx",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 172.23246028476802,
			"y": 511.0985559980475,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.2193439177291594,
			"height": 9.213006861938046,
			"seed": 1654458582,
			"groupIds": [
				"AspBavkgsiOA-mOs_Q8np",
				"_el1Im7voJSfSxypV5pC4"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320982,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.2193439177291594,
					9.213006861938046
				]
			]
		},
		{
			"type": "line",
			"version": 461,
			"versionNonce": 398043862,
			"isDeleted": false,
			"id": "j_nQJlFa-FU6xpS7j7hJV",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 167.84532085428935,
			"y": 510.44048407933775,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9.432370862428396,
			"height": 0,
			"seed": 854687254,
			"groupIds": [
				"_el1Im7voJSfSxypV5pC4"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320982,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.432370862428396,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 382,
			"versionNonce": 439063946,
			"isDeleted": false,
			"id": "mbUaImGv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 167.9117675153082,
			"y": 503.21876062824145,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 7.7799530029296875,
			"height": 8.53723206924,
			"seed": 59067222,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320982,
			"link": null,
			"locked": false,
			"fontSize": 6.829785655392,
			"fontFamily": 1,
			"text": "+V",
			"rawText": "+V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+V",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "line",
			"version": 296,
			"versionNonce": 539615254,
			"isDeleted": false,
			"id": "4q73T641EvGbt6Uef8ad4",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 179.70752215290932,
			"y": 523.6137680409947,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8.095699243028422,
			"height": 0.1587440451796578,
			"seed": 1118662806,
			"groupIds": [
				"nIdlcIFpohtOl1ALGtsRr"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320982,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.095699243028422,
					0.1587440451796578
				]
			]
		},
		{
			"type": "ellipse",
			"version": 266,
			"versionNonce": 938759242,
			"isDeleted": false,
			"id": "3-_ZjbKDaDU0Cc8eO8QoZ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 188.1207094862971,
			"y": 522.5819535468388,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.9048704101243346,
			"height": 1.9048704101243346,
			"seed": 1277095382,
			"groupIds": [
				"nIdlcIFpohtOl1ALGtsRr"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320982,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 265,
			"versionNonce": 794914134,
			"isDeleted": false,
			"id": "DcnCjHNt34JUVhY9xA-NP",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 189.70809180606213,
			"y": 522.6613328359326,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.714611230373004,
			"height": 3.809740820248669,
			"seed": 1022280470,
			"groupIds": [
				"nIdlcIFpohtOl1ALGtsRr"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320982,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.714611230373004,
					-3.809740820248669
				]
			]
		},
		{
			"type": "line",
			"version": 225,
			"versionNonce": 62339850,
			"isDeleted": false,
			"id": "nA-J8gVpXQ93yLL59Va0d",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 198.2800086516216,
			"y": 523.455023995815,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8.25445782121597,
			"height": 0.15872951217176806,
			"seed": 1200746582,
			"groupIds": [
				"nIdlcIFpohtOl1ALGtsRr"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320982,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.25445782121597,
					-0.15872951217176806
				]
			]
		},
		{
			"type": "line",
			"version": 188,
			"versionNonce": 582308502,
			"isDeleted": false,
			"id": "d5pV9oQKdnjdU4vvlSubj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 171.91093451233954,
			"y": 516.4559216095299,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.134033203125014,
			"height": 7.183247550589101,
			"seed": 131954070,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320982,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					7.183247550589101
				],
				[
					11.134033203125014,
					7.183247550589101
				]
			]
		},
		{
			"type": "line",
			"version": 655,
			"versionNonce": 200231370,
			"isDeleted": false,
			"id": "k-JikfLNkCehOt96RDhLk",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 223.49055467581883,
			"y": 523.2005496435436,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.112408747438394,
			"height": 2.8610914886974683,
			"seed": 838552150,
			"groupIds": [
				"ZCYNZ1K9XvEWh8zjWN2nG"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320982,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-3.199808877038606,
					-0.08174793014017334
				],
				[
					-4.84296724341241,
					-1.8801462630879442
				],
				[
					-6.5725859598083805,
					0.8991972954693501
				],
				[
					-8.907585478649004,
					-1.7166541448166672
				],
				[
					-10.20480743356045,
					0.9809452256095241
				],
				[
					-12.539806952401076,
					-1.553165768554459
				],
				[
					-13.31814804296241,
					0.16348837626220725
				],
				[
					-19.112408747438394,
					0.08174418813110407
				]
			]
		},
		{
			"type": "text",
			"version": 86,
			"versionNonce": 412752530,
			"isDeleted": false,
			"id": "gMmFn5ZY",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3.162203983174498,
			"y": 454.0707682028593,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.305084228515625,
			"height": 12.295944557923917,
			"seed": 1421110102,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502105,
			"link": null,
			"locked": false,
			"fontSize": 9.836755646339133,
			"fontFamily": 1,
			"text": "REMARKS:",
			"rawText": "REMARKS:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "REMARKS:",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "line",
			"version": 39,
			"versionNonce": 1471643786,
			"isDeleted": false,
			"id": "_XXjKxQ2I_3VQX7JZruwP",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 0.993930057393186,
			"y": 465.252640761453,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 50.828662109375,
			"height": 0,
			"seed": 1439399114,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320982,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					50.828662109375,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 3869,
			"versionNonce": 1775309455,
			"isDeleted": false,
			"id": "J629qwlP",
			"fillStyle": "solid",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1.4743178182851295,
			"y": 579.9676642246092,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 336.70989990234375,
			"height": 115.48038321740736,
			"seed": 688040842,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707327047767,
			"link": null,
			"locked": false,
			"fontSize": 5.774019160870369,
			"fontFamily": 1,
			"text": "In either circuit, closing the mechanical switch causes the transistor to turn on and energize the load. However, the\nload will not energize to the same degree in these two circuits. In the high-side circuit, the load will receive approx-\nimately 0.7V less than +V when energized. But in the low side circuit the load will receive slightly more, about 0.3V\nless than +V when energized. Recall that the base-emitter junction of a conducting transistor always drops approx-\nimately 0.7V which is standard for a forward-biased silicon PN junction(Vbe). Turning our attention back to the sche-\nmatic diagrams, we see why the low-side switching configuration is able to achieve this saturation-on stat but the\nhigh-side circuit cannot. In the high-side circuit the closed mechanical switch makes the base and collector terminals\nelectrically common to each other, which forces Vce to be exactly equal to Vbe, and thus Vce is approximately 0.7V.\nHowever, in the low-side circuit, Vbe and Vce are not forced into equality, and so with proper sizing of the resistor\nto saturate the transistor' base we may have Vbe = 0.7V and Vce = 0.3 volts or less. The freedom to satruate\nthe low-side NPN transistor but not the high-side NPN transistor means the low side-switched load can receive more\npower and also that the low-side transistor will dissipate less power compared to the hiigh-side circuit Thus the low-\nside switching configuration is more energy-efficient than the high-side using NPN transistors. An advantage of the\nhigh-side NPN circuit, though is the ability to turn off faster than the low-side circuit for the same reason: a \nsaturated BJT requires slightly more time to clear its base layer of all injected charge carriers that a non-satur-\nated BJT once current ceases through the base terminal.",
			"rawText": "In either circuit, closing the mechanical switch causes the transistor to turn on and energize the load. However, the\nload will not energize to the same degree in these two circuits. In the high-side circuit, the load will receive approx-\nimately 0.7V less than +V when energized. But in the low side circuit the load will receive slightly more, about 0.3V\nless than +V when energized. Recall that the base-emitter junction of a conducting transistor always drops approx-\nimately 0.7V which is standard for a forward-biased silicon PN junction(Vbe). Turning our attention back to the sche-\nmatic diagrams, we see why the low-side switching configuration is able to achieve this saturation-on stat but the\nhigh-side circuit cannot. In the high-side circuit the closed mechanical switch makes the base and collector terminals\nelectrically common to each other, which forces Vce to be exactly equal to Vbe, and thus Vce is approximately 0.7V.\nHowever, in the low-side circuit, Vbe and Vce are not forced into equality, and so with proper sizing of the resistor\nto saturate the transistor' base we may have Vbe = 0.7V and Vce = 0.3 volts or less. The freedom to satruate\nthe low-side NPN transistor but not the high-side NPN transistor means the low side-switched load can receive more\npower and also that the low-side transistor will dissipate less power compared to the hiigh-side circuit Thus the low-\nside switching configuration is more energy-efficient than the high-side using NPN transistors. An advantage of the\nhigh-side NPN circuit, though is the ability to turn off faster than the low-side circuit for the same reason: a \nsaturated BJT requires slightly more time to clear its base layer of all injected charge carriers that a non-satur-\nated BJT once current ceases through the base terminal.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "In either circuit, closing the mechanical switch causes the transistor to turn on and energize the load. However, the\nload will not energize to the same degree in these two circuits. In the high-side circuit, the load will receive approx-\nimately 0.7V less than +V when energized. But in the low side circuit the load will receive slightly more, about 0.3V\nless than +V when energized. Recall that the base-emitter junction of a conducting transistor always drops approx-\nimately 0.7V which is standard for a forward-biased silicon PN junction(Vbe). Turning our attention back to the sche-\nmatic diagrams, we see why the low-side switching configuration is able to achieve this saturation-on stat but the\nhigh-side circuit cannot. In the high-side circuit the closed mechanical switch makes the base and collector terminals\nelectrically common to each other, which forces Vce to be exactly equal to Vbe, and thus Vce is approximately 0.7V.\nHowever, in the low-side circuit, Vbe and Vce are not forced into equality, and so with proper sizing of the resistor\nto saturate the transistor' base we may have Vbe = 0.7V and Vce = 0.3 volts or less. The freedom to satruate\nthe low-side NPN transistor but not the high-side NPN transistor means the low side-switched load can receive more\npower and also that the low-side transistor will dissipate less power compared to the hiigh-side circuit Thus the low-\nside switching configuration is more energy-efficient than the high-side using NPN transistors. An advantage of the\nhigh-side NPN circuit, though is the ability to turn off faster than the low-side circuit for the same reason: a \nsaturated BJT requires slightly more time to clear its base layer of all injected charge carriers that a non-satur-\nated BJT once current ceases through the base terminal.",
			"lineHeight": 1.25,
			"baseline": 113
		},
		{
			"type": "line",
			"version": 107,
			"versionNonce": 1389027146,
			"isDeleted": false,
			"id": "uwQxTHUZ_ijTIrV4pRMzg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -0.5546525679740455,
			"y": 722.408078713305,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 113.95459056764271,
			"height": 0,
			"seed": 1089939786,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320982,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					113.95459056764271,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 453,
			"versionNonce": 994906710,
			"isDeleted": false,
			"id": "d1fh1hxceJHbFGPKZ0ELN",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 79.48683972138747,
			"y": 502.2389902943678,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.32448871910266,
			"height": 0,
			"seed": 971677462,
			"groupIds": [
				"BmImn5YndxVPviSpOcwlI",
				"uHaDEaQ02fmWHBv_d7LxS",
				"uDjUMGhaXQ9EBqb45K4-Z"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320982,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.32448871910266,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 490,
			"versionNonce": 964978186,
			"isDeleted": false,
			"id": "V6dBDj4wa6pdxjMhUgpwJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 85.96387120154435,
			"y": 496.06704433631904,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 12.425101731334298,
			"seed": 1890733142,
			"groupIds": [
				"BmImn5YndxVPviSpOcwlI",
				"uHaDEaQ02fmWHBv_d7LxS",
				"uDjUMGhaXQ9EBqb45K4-Z"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320982,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					12.425101731334298
				]
			]
		},
		{
			"type": "line",
			"version": 527,
			"versionNonce": 1541691286,
			"isDeleted": false,
			"id": "XOXLMmkdEq9MTWNEkTs38",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 86.0846955608,
			"y": 500.0354045167666,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.938166615173053,
			"height": 4.029762723675923,
			"seed": 1687310742,
			"groupIds": [
				"BmImn5YndxVPviSpOcwlI",
				"uHaDEaQ02fmWHBv_d7LxS",
				"uDjUMGhaXQ9EBqb45K4-Z"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320982,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.938166615173053,
					-4.029762723675923
				]
			]
		},
		{
			"type": "line",
			"version": 502,
			"versionNonce": 81728714,
			"isDeleted": false,
			"id": "7_xs2_7ZGl-ye5vMnhKcp",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 91.91194145272252,
			"y": 507.9969642674245,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 6.667127758276997,
			"seed": 12562134,
			"groupIds": [
				"BmImn5YndxVPviSpOcwlI",
				"uHaDEaQ02fmWHBv_d7LxS",
				"uDjUMGhaXQ9EBqb45K4-Z"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320983,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					6.667127758276997
				]
			]
		},
		{
			"type": "line",
			"version": 479,
			"versionNonce": 199292118,
			"isDeleted": false,
			"id": "oL7MvB_zpV1o8zaHaKxHC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 91.91194145272176,
			"y": 496.35127868965003,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 6.537390126617051,
			"seed": 30368790,
			"groupIds": [
				"BmImn5YndxVPviSpOcwlI",
				"uHaDEaQ02fmWHBv_d7LxS",
				"uDjUMGhaXQ9EBqb45K4-Z"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320983,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-6.537390126617051
				]
			]
		},
		{
			"type": "line",
			"version": 597,
			"versionNonce": 1450568586,
			"isDeleted": false,
			"id": "U1XMZcgZNUjAAlMY3zMpa",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 86.02974376426657,
			"y": 504.7101348435941,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.961373243324144,
			"height": 3.6106783211799347,
			"seed": 1236693334,
			"groupIds": [
				"BmImn5YndxVPviSpOcwlI",
				"uHaDEaQ02fmWHBv_d7LxS",
				"uDjUMGhaXQ9EBqb45K4-Z"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320983,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.961373243324144,
					3.6106783211799347
				]
			]
		},
		{
			"type": "line",
			"version": 983,
			"versionNonce": 1691871766,
			"isDeleted": false,
			"id": "79N0LQ2-3MS5hb0kftJpd",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 2.148993807554163,
			"x": 90.58423512675088,
			"y": 505.97465695238316,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 2.519069568840371,
			"height": 2.9884712093857204,
			"seed": 868865686,
			"groupIds": [
				"uHaDEaQ02fmWHBv_d7LxS",
				"uDjUMGhaXQ9EBqb45K4-Z"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320983,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.2595347844201832,
					2.9884712093857204
				],
				[
					1.2595347844201876,
					2.9884712093857204
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 296,
			"versionNonce": 1686366794,
			"isDeleted": false,
			"id": "JPHQxFHagNZttEGSqYkxy",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.2831853071795845,
			"x": 79.48683972138747,
			"y": 489.8138885630328,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 16.56680230844573,
			"height": 24.850203462668595,
			"seed": 1757320150,
			"groupIds": [
				"uDjUMGhaXQ9EBqb45K4-Z"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320983,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 530,
			"versionNonce": 96352086,
			"isDeleted": false,
			"id": "JC4DJ8bVeTUjjk4RPNAu6",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 222.86966282158795,
			"y": 523.2750976283801,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.425812399001678,
			"height": 0,
			"seed": 1602690198,
			"groupIds": [
				"czwTXL6Ny3l_oJZ-2MZFM",
				"tnpnxhdDgR9MqpIb5zYNR",
				"Fgaaj6AvQATw-LBsJFhMt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320983,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.425812399001678,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 567,
			"versionNonce": 1709445386,
			"isDeleted": false,
			"id": "S9Lu0Jn516B6IzD7OcDKr",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 229.45046184621197,
			"y": 517.0042718550004,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 12.624162412197853,
			"seed": 2028149206,
			"groupIds": [
				"czwTXL6Ny3l_oJZ-2MZFM",
				"tnpnxhdDgR9MqpIb5zYNR",
				"Fgaaj6AvQATw-LBsJFhMt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320983,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					12.624162412197853
				]
			]
		},
		{
			"type": "line",
			"version": 604,
			"versionNonce": 1726536854,
			"isDeleted": false,
			"id": "sCsUejvnRguG7R0O52tok",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 229.5732219143043,
			"y": 521.0362085353844,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.033301086910746,
			"height": 4.0943229444965334,
			"seed": 407727894,
			"groupIds": [
				"czwTXL6Ny3l_oJZ-2MZFM",
				"tnpnxhdDgR9MqpIb5zYNR",
				"Fgaaj6AvQATw-LBsJFhMt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320983,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.033301086910746,
					-4.0943229444965334
				]
			]
		},
		{
			"type": "line",
			"version": 579,
			"versionNonce": 2115067850,
			"isDeleted": false,
			"id": "ucqCAOtapEYHpQA31sRSZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 235.49382523378657,
			"y": 529.1253192340323,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 6.773940806545248,
			"seed": 440081494,
			"groupIds": [
				"czwTXL6Ny3l_oJZ-2MZFM",
				"tnpnxhdDgR9MqpIb5zYNR",
				"Fgaaj6AvQATw-LBsJFhMt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320983,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					6.773940806545248
				]
			]
		},
		{
			"type": "line",
			"version": 556,
			"versionNonce": 772594134,
			"isDeleted": false,
			"id": "D6f2GFQ7ewbLAqa84UXFM",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 235.49382523378583,
			"y": 517.2930598840375,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 6.64212466785572,
			"seed": 75571606,
			"groupIds": [
				"czwTXL6Ny3l_oJZ-2MZFM",
				"tnpnxhdDgR9MqpIb5zYNR",
				"Fgaaj6AvQATw-LBsJFhMt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320983,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-6.64212466785572
				]
			]
		},
		{
			"type": "line",
			"version": 674,
			"versionNonce": 690411146,
			"isDeleted": false,
			"id": "wRnnYYT-Y5SOtIK4A_qN7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 229.5173897433265,
			"y": 525.7858320117275,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.056879504951383,
			"height": 3.668524453995153,
			"seed": 1515486934,
			"groupIds": [
				"czwTXL6Ny3l_oJZ-2MZFM",
				"tnpnxhdDgR9MqpIb5zYNR",
				"Fgaaj6AvQATw-LBsJFhMt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320983,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.056879504951383,
					3.668524453995153
				]
			]
		},
		{
			"type": "line",
			"version": 1060,
			"versionNonce": 37695254,
			"isDeleted": false,
			"id": "ztxMRTu05OMkZkUU6-qV-",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 2.148993807554163,
			"x": 234.14484792501335,
			"y": 527.0706128385042,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 2.559427202472573,
			"height": 3.036349055905177,
			"seed": 1883911190,
			"groupIds": [
				"tnpnxhdDgR9MqpIb5zYNR",
				"Fgaaj6AvQATw-LBsJFhMt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320983,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.2797136012362842,
					3.036349055905177
				],
				[
					1.2797136012362889,
					3.036349055905177
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 373,
			"versionNonce": 668955978,
			"isDeleted": false,
			"id": "w7rFggy--c3WTimWFPUaJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.2831853071795845,
			"x": 222.86966282158795,
			"y": 510.65093521618155,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 16.83221654959714,
			"height": 25.248324824395706,
			"seed": 1079460182,
			"groupIds": [
				"Fgaaj6AvQATw-LBsJFhMt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320983,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 295,
			"versionNonce": 1235722063,
			"isDeleted": false,
			"id": "RQAuwJk0",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2.0771574526041903,
			"y": 713.7551080206442,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 109.85545349121094,
			"height": 9.192272071813216,
			"seed": 57829654,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414211,
			"link": null,
			"locked": false,
			"fontSize": 7.3538176574505725,
			"fontFamily": 1,
			"text": "PARALLELING TRANSISTORS",
			"rawText": "PARALLELING TRANSISTORS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "PARALLELING TRANSISTORS",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 6617,
			"versionNonce": 1033896225,
			"isDeleted": false,
			"id": "BkeSUzIo",
			"fillStyle": "solid",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2.4542442228569996,
			"y": 725.8580110657347,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 338.86627197265625,
			"height": 137.13295507067124,
			"seed": 1799919306,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414214,
			"link": null,
			"locked": false,
			"fontSize": 5.774019160870369,
			"fontFamily": 1,
			"text": "In applications where load current exceeds the current handling ability of any single transistor, multiple transistor\nmust be paralleled. Ideally, load current will be split into exactly equal portions according to the number of identical\ntransistors connected in parallel with each other. However, no two transistors are ever exactly the same and so we\nmust always expect some current imbalance. A prudent design choice is to parallel more transistors than strictly \nnecessary assuming equal division of current, just in case one or more end up carrying more than their fair share.\n    However, the problem may be more complicated than imperfect matches between paralleled transistors. If \nbipolar junction transistors are used, a phenomenon called THERMAL RUNAWAY may occur. The basis of thermal \nrunaway is that BJTs are \"minority carriers\" devices and therefore drop less voltage (become more conductive) as\ntheir temperature increases. Any imbalance between paralleled BJTs will result in the hotter transistor bearing more\nof the load's current, which of course increases it's power dissipation and makes it hotter yet. The end-result is one\noverheating transistor conducting most of the load current while the other transistors run cool. A clever solution to \nthe problem of thermal runaway is to add resistances in series with the emitter terminal of each transistor so as to\nintroduce a (small) voltage drop proportional to its current. This additional resistance helps to solve the problem in\ntwo different ways. First, the presence of additional resistances makes the transistor's effective collector-emmiter\nresistance even seem smaller by  proportion, so that changes in the transistor's characteristics due to heat will\nhave less effect than before when the only factor determining current division was the effective collector-emitter\nresistance of each transistor. The general strategy is know by the colorful name of SWAMPING OR BALLASTING.\nSecond the placement of said resistor on the emitter terminal of each transistor adds some negative feedback\nwhich will  act tp decrease current if other factors makes that current increase.",
			"rawText": "In applications where load current exceeds the current handling ability of any single transistor, multiple transistor\nmust be paralleled. Ideally, load current will be split into exactly equal portions according to the number of identical\ntransistors connected in parallel with each other. However, no two transistors are ever exactly the same and so we\nmust always expect some current imbalance. A prudent design choice is to parallel more transistors than strictly \nnecessary assuming equal division of current, just in case one or more end up carrying more than their fair share.\n    However, the problem may be more complicated than imperfect matches between paralleled transistors. If \nbipolar junction transistors are used, a phenomenon called THERMAL RUNAWAY may occur. The basis of thermal \nrunaway is that BJTs are \"minority carriers\" devices and therefore drop less voltage (become more conductive) as\ntheir temperature increases. Any imbalance between paralleled BJTs will result in the hotter transistor bearing more\nof the load's current, which of course increases it's power dissipation and makes it hotter yet. The end-result is one\noverheating transistor conducting most of the load current while the other transistors run cool. A clever solution to \nthe problem of thermal runaway is to add resistances in series with the emitter terminal of each transistor so as to\nintroduce a (small) voltage drop proportional to its current. This additional resistance helps to solve the problem in\ntwo different ways. First, the presence of additional resistances makes the transistor's effective collector-emmiter\nresistance even seem smaller by  proportion, so that changes in the transistor's characteristics due to heat will\nhave less effect than before when the only factor determining current division was the effective collector-emitter\nresistance of each transistor. The general strategy is know by the colorful name of SWAMPING OR BALLASTING.\nSecond the placement of said resistor on the emitter terminal of each transistor adds some negative feedback\nwhich will  act tp decrease current if other factors makes that current increase.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "In applications where load current exceeds the current handling ability of any single transistor, multiple transistor\nmust be paralleled. Ideally, load current will be split into exactly equal portions according to the number of identical\ntransistors connected in parallel with each other. However, no two transistors are ever exactly the same and so we\nmust always expect some current imbalance. A prudent design choice is to parallel more transistors than strictly \nnecessary assuming equal division of current, just in case one or more end up carrying more than their fair share.\n    However, the problem may be more complicated than imperfect matches between paralleled transistors. If \nbipolar junction transistors are used, a phenomenon called THERMAL RUNAWAY may occur. The basis of thermal \nrunaway is that BJTs are \"minority carriers\" devices and therefore drop less voltage (become more conductive) as\ntheir temperature increases. Any imbalance between paralleled BJTs will result in the hotter transistor bearing more\nof the load's current, which of course increases it's power dissipation and makes it hotter yet. The end-result is one\noverheating transistor conducting most of the load current while the other transistors run cool. A clever solution to \nthe problem of thermal runaway is to add resistances in series with the emitter terminal of each transistor so as to\nintroduce a (small) voltage drop proportional to its current. This additional resistance helps to solve the problem in\ntwo different ways. First, the presence of additional resistances makes the transistor's effective collector-emmiter\nresistance even seem smaller by  proportion, so that changes in the transistor's characteristics due to heat will\nhave less effect than before when the only factor determining current division was the effective collector-emitter\nresistance of each transistor. The general strategy is know by the colorful name of SWAMPING OR BALLASTING.\nSecond the placement of said resistor on the emitter terminal of each transistor adds some negative feedback\nwhich will  act tp decrease current if other factors makes that current increase.",
			"lineHeight": 1.25,
			"baseline": 135
		},
		{
			"type": "line",
			"version": 554,
			"versionNonce": 1828905366,
			"isDeleted": false,
			"id": "WAIbAcLkeREtZhPw61Xsr",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 103.75619583280758,
			"y": 931.1678115605305,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.774504308973386,
			"height": 0,
			"seed": 979809610,
			"groupIds": [
				"xDW6VNPydV0JgPYQ6F4QZ",
				"WJVcaOhBCHqrbAETbOTK4",
				"55HOjYVGZOKj-L9p7VsL1",
				"kul_09sDv2ELBzW7h0Tg3",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320984,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.774504308973386,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 591,
			"versionNonce": 38152906,
			"isDeleted": false,
			"id": "cj2Ci7lymARSysVCrsBMS",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 109.66997761860682,
			"y": 925.532584728383,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 11.344601385770602,
			"seed": 724925450,
			"groupIds": [
				"xDW6VNPydV0JgPYQ6F4QZ",
				"WJVcaOhBCHqrbAETbOTK4",
				"55HOjYVGZOKj-L9p7VsL1",
				"kul_09sDv2ELBzW7h0Tg3",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320984,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					11.344601385770602
				]
			]
		},
		{
			"type": "line",
			"version": 628,
			"versionNonce": 1285439190,
			"isDeleted": false,
			"id": "BG9hSWwcm2DD62CEIdkyP",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 109.78029496031436,
			"y": 929.1558519961923,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.421777194913532,
			"height": 3.679330179168784,
			"seed": 201157322,
			"groupIds": [
				"xDW6VNPydV0JgPYQ6F4QZ",
				"WJVcaOhBCHqrbAETbOTK4",
				"55HOjYVGZOKj-L9p7VsL1",
				"kul_09sDv2ELBzW7h0Tg3",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320984,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.421777194913532,
					-3.679330179168784
				]
			]
		},
		{
			"type": "line",
			"version": 603,
			"versionNonce": 42615178,
			"isDeleted": false,
			"id": "dz5EkRt08YlBU8a8wH5_B",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 115.10079721857886,
			"y": 936.4250658612532,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 6.087347085047694,
			"seed": 1398374794,
			"groupIds": [
				"xDW6VNPydV0JgPYQ6F4QZ",
				"WJVcaOhBCHqrbAETbOTK4",
				"55HOjYVGZOKj-L9p7VsL1",
				"kul_09sDv2ELBzW7h0Tg3",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320984,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					6.087347085047694
				]
			]
		},
		{
			"type": "line",
			"version": 580,
			"versionNonce": 1935406102,
			"isDeleted": false,
			"id": "iEiMdzDMJeYGAHF0ovrNo",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 115.10079721857818,
			"y": 925.7921017535473,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 5.968891578787789,
			"seed": 1820639306,
			"groupIds": [
				"xDW6VNPydV0JgPYQ6F4QZ",
				"WJVcaOhBCHqrbAETbOTK4",
				"55HOjYVGZOKj-L9p7VsL1",
				"kul_09sDv2ELBzW7h0Tg3",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320984,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-5.968891578787789
				]
			]
		},
		{
			"type": "line",
			"version": 698,
			"versionNonce": 2006810698,
			"isDeleted": false,
			"id": "7IhLyyCLEOvOS8CaUZMMC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 109.73012183170877,
			"y": 933.42406269503,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.442965749468221,
			"height": 3.2966898116198355,
			"seed": 593110794,
			"groupIds": [
				"xDW6VNPydV0JgPYQ6F4QZ",
				"WJVcaOhBCHqrbAETbOTK4",
				"55HOjYVGZOKj-L9p7VsL1",
				"kul_09sDv2ELBzW7h0Tg3",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320984,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.442965749468221,
					3.2966898116198355
				]
			]
		},
		{
			"type": "line",
			"version": 1084,
			"versionNonce": 2066809174,
			"isDeleted": false,
			"id": "Fpm_xJaYGzSMBd-9SGrc6",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 2.148993807554163,
			"x": 113.8885496771741,
			"y": 934.5786205874235,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 2.3000085423405325,
			"height": 2.7285905062518987,
			"seed": 273987018,
			"groupIds": [
				"WJVcaOhBCHqrbAETbOTK4",
				"55HOjYVGZOKj-L9p7VsL1",
				"kul_09sDv2ELBzW7h0Tg3",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320984,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.1500042711702643,
					2.7285905062518987
				],
				[
					1.1500042711702683,
					2.7285905062518987
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 398,
			"versionNonce": 1297803018,
			"isDeleted": false,
			"id": "3fzDVGSTVRB7BZnjVasoX",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.2831853071795845,
			"x": 103.75619583280758,
			"y": 919.8232101747594,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 15.12613518102747,
			"height": 22.689202771541204,
			"seed": 76508298,
			"groupIds": [
				"55HOjYVGZOKj-L9p7VsL1",
				"kul_09sDv2ELBzW7h0Tg3",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320984,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 856,
			"versionNonce": 2003986070,
			"isDeleted": false,
			"id": "r8pnMLi6QEzk_hSwNgbWr",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179576,
			"x": 110.69165204792847,
			"y": 966.4402524476409,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 10.755271443652566,
			"height": 0,
			"seed": 904601878,
			"groupIds": [
				"0CP-bVI0GcjIcVKmqn9qw",
				"Fs0oTyhtlujqHNLO3fh19",
				"JWUSsozEdWCvsz5isizHe",
				"kul_09sDv2ELBzW7h0Tg3",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320984,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.755271443652566,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 854,
			"versionNonce": 1010660810,
			"isDeleted": false,
			"id": "YNv29i04ziU8nUKIaYzcD",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179576,
			"x": 112.4841972885369,
			"y": 968.2327976882495,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.170180962435048,
			"height": 0,
			"seed": 1565691478,
			"groupIds": [
				"0CP-bVI0GcjIcVKmqn9qw",
				"Fs0oTyhtlujqHNLO3fh19",
				"JWUSsozEdWCvsz5isizHe",
				"kul_09sDv2ELBzW7h0Tg3",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320984,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.170180962435048,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 853,
			"versionNonce": 1221927894,
			"isDeleted": false,
			"id": "A_ruyO7JN3COutLzecl9Q",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179576,
			"x": 114.27674252914565,
			"y": 970.0253429288582,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 3.585090481217524,
			"height": 0,
			"seed": 400184214,
			"groupIds": [
				"0CP-bVI0GcjIcVKmqn9qw",
				"Fs0oTyhtlujqHNLO3fh19",
				"JWUSsozEdWCvsz5isizHe",
				"kul_09sDv2ELBzW7h0Tg3",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320984,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					3.585090481217524,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 885,
			"versionNonce": 895495306,
			"isDeleted": false,
			"id": "uwkMA73FlAKFkDCa1xJkC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179576,
			"x": 115.52439320982452,
			"y": 971.8041890584436,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 1.0916880643006555,
			"height": 0,
			"seed": 1337422038,
			"groupIds": [
				"0CP-bVI0GcjIcVKmqn9qw",
				"Fs0oTyhtlujqHNLO3fh19",
				"JWUSsozEdWCvsz5isizHe",
				"kul_09sDv2ELBzW7h0Tg3",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320984,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.0916880643006555,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 823,
			"versionNonce": 1903048982,
			"isDeleted": false,
			"id": "9GIaNS1OgPvFO-yGB6RAX",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179576,
			"x": 116.06652873444514,
			"y": 959.2700714852058,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 0,
			"height": 7.563067590513735,
			"seed": 1618929174,
			"groupIds": [
				"Fs0oTyhtlujqHNLO3fh19",
				"MBlvWr5ZTdZ8z6pzP_C_3",
				"JWUSsozEdWCvsz5isizHe",
				"kul_09sDv2ELBzW7h0Tg3",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320984,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					7.563067590513735
				]
			]
		},
		{
			"type": "rectangle",
			"version": 656,
			"versionNonce": 1316883274,
			"isDeleted": false,
			"id": "kSGoJ3R_q9dBkpqc9dGqR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179576,
			"x": 108.50346114393139,
			"y": 959.2700714852058,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 15.12613518102747,
			"height": 15.126135181027513,
			"seed": 1797632854,
			"groupIds": [
				"MBlvWr5ZTdZ8z6pzP_C_3",
				"JWUSsozEdWCvsz5isizHe",
				"kul_09sDv2ELBzW7h0Tg3",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320984,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1457,
			"versionNonce": 1756538454,
			"isDeleted": false,
			"id": "mIsRwCszKWPnUtloq3B3i",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 7.809125643163043,
			"x": 104.27596570682584,
			"y": 951.1578550346205,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.689202771541254,
			"height": 5.0891851034804825,
			"seed": 1768209622,
			"groupIds": [
				"R7Ctsh9eD4Me2P9Vol7Fj",
				"C4cmB-N0pMp0WquEkRFlT",
				"kul_09sDv2ELBzW7h0Tg3",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320984,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					3.592794140591648,
					0
				],
				[
					5.02608961758383,
					-2.5681625733092295
				],
				[
					7.511838255676038,
					2.5210225301712526
				],
				[
					10.03286078584729,
					-2.521022530171251
				],
				[
					12.553883316018537,
					2.5210225301712526
				],
				[
					15.074905846189788,
					-2.521022530171251
				],
				[
					17.59592837636104,
					2.5210225301712526
				],
				[
					18.810695026375864,
					0.022419270692967206
				],
				[
					22.689202771541254,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 942,
			"versionNonce": 770839050,
			"isDeleted": false,
			"id": "YwCt7ZFF3F5ZSz2ZdywSL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 7.809125643163043,
			"x": 104.35675035502297,
			"y": 947.3491251100493,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 22.689202771541204,
			"height": 7.563067590513906,
			"seed": 1856156182,
			"groupIds": [
				"C4cmB-N0pMp0WquEkRFlT",
				"kul_09sDv2ELBzW7h0Tg3",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320984,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 582,
			"versionNonce": 1870097302,
			"isDeleted": false,
			"id": "3EnNrYJqB8AI4ShIR8gLg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 136.38457852820255,
			"y": 930.0451032371909,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.774504308973386,
			"height": 0,
			"seed": 225203414,
			"groupIds": [
				"qoaGGeO_P5GljVGSPAgnN",
				"QztD5_eh4OgSDFt2oXiFC",
				"xtVPfxss-K_c-8SuQ7VT0",
				"2bjUBUpodi6D17ayFEFK8",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320984,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.774504308973386,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 619,
			"versionNonce": 1991721162,
			"isDeleted": false,
			"id": "IpWbXjP_6NpULhx0Fcvkm",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 142.2983603140018,
			"y": 924.4098764050432,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 11.344601385770602,
			"seed": 1576487446,
			"groupIds": [
				"qoaGGeO_P5GljVGSPAgnN",
				"QztD5_eh4OgSDFt2oXiFC",
				"xtVPfxss-K_c-8SuQ7VT0",
				"2bjUBUpodi6D17ayFEFK8",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320985,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					11.344601385770602
				]
			]
		},
		{
			"type": "line",
			"version": 656,
			"versionNonce": 1676773590,
			"isDeleted": false,
			"id": "R2WWF1LUBCbuHxXjIO1AK",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 142.40867765570928,
			"y": 928.0331436728522,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.421777194913532,
			"height": 3.679330179168784,
			"seed": 1676777302,
			"groupIds": [
				"qoaGGeO_P5GljVGSPAgnN",
				"QztD5_eh4OgSDFt2oXiFC",
				"xtVPfxss-K_c-8SuQ7VT0",
				"2bjUBUpodi6D17ayFEFK8",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320985,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.421777194913532,
					-3.679330179168784
				]
			]
		},
		{
			"type": "line",
			"version": 631,
			"versionNonce": 879269770,
			"isDeleted": false,
			"id": "lAGMgJIzTFO9MuXPeHIbB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 147.72917991397384,
			"y": 935.3023575379134,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 6.087347085047694,
			"seed": 1739603094,
			"groupIds": [
				"qoaGGeO_P5GljVGSPAgnN",
				"QztD5_eh4OgSDFt2oXiFC",
				"xtVPfxss-K_c-8SuQ7VT0",
				"2bjUBUpodi6D17ayFEFK8",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320985,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					6.087347085047694
				]
			]
		},
		{
			"type": "line",
			"version": 608,
			"versionNonce": 364248598,
			"isDeleted": false,
			"id": "j4h9-tHfiJRNsim7-yMpW",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 147.72917991397316,
			"y": 924.6693934302077,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 5.968891578787789,
			"seed": 1592277462,
			"groupIds": [
				"qoaGGeO_P5GljVGSPAgnN",
				"QztD5_eh4OgSDFt2oXiFC",
				"xtVPfxss-K_c-8SuQ7VT0",
				"2bjUBUpodi6D17ayFEFK8",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320985,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-5.968891578787789
				]
			]
		},
		{
			"type": "line",
			"version": 726,
			"versionNonce": 1195447882,
			"isDeleted": false,
			"id": "qFcTxliEG7CjaUnU4sh1e",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 142.35850452710375,
			"y": 932.3013543716902,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.442965749468221,
			"height": 3.2966898116198355,
			"seed": 1085181718,
			"groupIds": [
				"qoaGGeO_P5GljVGSPAgnN",
				"QztD5_eh4OgSDFt2oXiFC",
				"xtVPfxss-K_c-8SuQ7VT0",
				"2bjUBUpodi6D17ayFEFK8",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320985,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.442965749468221,
					3.2966898116198355
				]
			]
		},
		{
			"type": "line",
			"version": 1112,
			"versionNonce": 431606614,
			"isDeleted": false,
			"id": "4JTR-GH_MqhfHVJLhgpec",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 2.148993807554163,
			"x": 146.51693237256904,
			"y": 933.455912264084,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 2.3000085423405325,
			"height": 2.7285905062518987,
			"seed": 1501051990,
			"groupIds": [
				"QztD5_eh4OgSDFt2oXiFC",
				"xtVPfxss-K_c-8SuQ7VT0",
				"2bjUBUpodi6D17ayFEFK8",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320985,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.1500042711702643,
					2.7285905062518987
				],
				[
					1.1500042711702683,
					2.7285905062518987
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 426,
			"versionNonce": 1343995146,
			"isDeleted": false,
			"id": "DwWrFKdqoqaEaQ5CS46bm",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.2831853071795845,
			"x": 136.38457852820255,
			"y": 918.7005018514196,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 15.12613518102747,
			"height": 22.689202771541204,
			"seed": 521814422,
			"groupIds": [
				"xtVPfxss-K_c-8SuQ7VT0",
				"2bjUBUpodi6D17ayFEFK8",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320985,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 884,
			"versionNonce": 508686486,
			"isDeleted": false,
			"id": "4fMY_wJDaB-ZFTf17-Oj_",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179576,
			"x": 143.32003474332345,
			"y": 965.3175441243013,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 10.755271443652566,
			"height": 0,
			"seed": 80322262,
			"groupIds": [
				"SBt8tDrL2ZNyXt3kUH36e",
				"cyZ2GOnQ5zUtN5Z_h2sFe",
				"cSc64U3HeVpbYPEOA_Qn0",
				"2bjUBUpodi6D17ayFEFK8",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320985,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.755271443652566,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 882,
			"versionNonce": 477334474,
			"isDeleted": false,
			"id": "8cu79g_X9q2ozts5dwqzj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179576,
			"x": 145.11257998393188,
			"y": 967.1100893649098,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.170180962435048,
			"height": 0,
			"seed": 1327191062,
			"groupIds": [
				"SBt8tDrL2ZNyXt3kUH36e",
				"cyZ2GOnQ5zUtN5Z_h2sFe",
				"cSc64U3HeVpbYPEOA_Qn0",
				"2bjUBUpodi6D17ayFEFK8",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320985,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.170180962435048,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 881,
			"versionNonce": 1060335062,
			"isDeleted": false,
			"id": "Cog2O49VyzWXq-jW5nB00",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179576,
			"x": 146.90512522454063,
			"y": 968.9026346055186,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 3.585090481217524,
			"height": 0,
			"seed": 1745117526,
			"groupIds": [
				"SBt8tDrL2ZNyXt3kUH36e",
				"cyZ2GOnQ5zUtN5Z_h2sFe",
				"cSc64U3HeVpbYPEOA_Qn0",
				"2bjUBUpodi6D17ayFEFK8",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320985,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					3.585090481217524,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 913,
			"versionNonce": 308511370,
			"isDeleted": false,
			"id": "jpjq2XSPz-GQqVul0DSHo",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179576,
			"x": 148.15277590521947,
			"y": 970.6814807351041,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 1.0916880643006555,
			"height": 0,
			"seed": 853132950,
			"groupIds": [
				"SBt8tDrL2ZNyXt3kUH36e",
				"cyZ2GOnQ5zUtN5Z_h2sFe",
				"cSc64U3HeVpbYPEOA_Qn0",
				"2bjUBUpodi6D17ayFEFK8",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320985,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.0916880643006555,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 851,
			"versionNonce": 1500726038,
			"isDeleted": false,
			"id": "qCwh86FUh5WK0W6ggfvYl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179576,
			"x": 148.69491142984012,
			"y": 958.1473631618662,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 0,
			"height": 7.563067590513735,
			"seed": 1615889366,
			"groupIds": [
				"cyZ2GOnQ5zUtN5Z_h2sFe",
				"J_ipFGtqnBfg55K9SSEGC",
				"cSc64U3HeVpbYPEOA_Qn0",
				"2bjUBUpodi6D17ayFEFK8",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320985,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					7.563067590513735
				]
			]
		},
		{
			"type": "rectangle",
			"version": 684,
			"versionNonce": 480682314,
			"isDeleted": false,
			"id": "pWQr27_whKt_tY2qoIhsH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179576,
			"x": 141.13184383932636,
			"y": 958.1473631618662,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 15.12613518102747,
			"height": 15.126135181027513,
			"seed": 1115527446,
			"groupIds": [
				"J_ipFGtqnBfg55K9SSEGC",
				"cSc64U3HeVpbYPEOA_Qn0",
				"2bjUBUpodi6D17ayFEFK8",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320985,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1485,
			"versionNonce": 1602646102,
			"isDeleted": false,
			"id": "wLUmBuFRn0kKqSicL3G0W",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 7.809125643163043,
			"x": 136.9043484022208,
			"y": 950.035146711281,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.689202771541254,
			"height": 5.0891851034804825,
			"seed": 550897238,
			"groupIds": [
				"6FSrvEeaMDBA1ti952X6Y",
				"Z0QCy5iBihFTRuIcUr-PN",
				"2bjUBUpodi6D17ayFEFK8",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320985,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					3.592794140591648,
					0
				],
				[
					5.02608961758383,
					-2.5681625733092295
				],
				[
					7.511838255676038,
					2.5210225301712526
				],
				[
					10.03286078584729,
					-2.521022530171251
				],
				[
					12.553883316018537,
					2.5210225301712526
				],
				[
					15.074905846189788,
					-2.521022530171251
				],
				[
					17.59592837636104,
					2.5210225301712526
				],
				[
					18.810695026375864,
					0.022419270692967206
				],
				[
					22.689202771541254,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 970,
			"versionNonce": 379054090,
			"isDeleted": false,
			"id": "4MfXNkcUM-PM5kgsWxFe8",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 7.809125643163043,
			"x": 136.98513305041791,
			"y": 946.2264167867093,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 22.689202771541204,
			"height": 7.563067590513906,
			"seed": 204393366,
			"groupIds": [
				"Z0QCy5iBihFTRuIcUr-PN",
				"2bjUBUpodi6D17ayFEFK8",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320985,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 595,
			"versionNonce": 759297430,
			"isDeleted": false,
			"id": "S8VEhWylUfJqMv0mv-xhR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 169.07331952257363,
			"y": 931.4126534118068,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.774504308973386,
			"height": 0,
			"seed": 1457874966,
			"groupIds": [
				"PzbhRcLhmw6_BItw3uC4N",
				"Vnk3CmwQSsBbYA1VQ9iH5",
				"Ka-XZ_1weUCVMCaLYv4dr",
				"K3r93LGyBAsvnXzXZWgnM",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320985,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.774504308973386,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 632,
			"versionNonce": 942823114,
			"isDeleted": false,
			"id": "Ps8hfLQKOmK4HeHDKOF3x",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 174.98710130837287,
			"y": 925.7774265796593,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 11.344601385770602,
			"seed": 359396694,
			"groupIds": [
				"PzbhRcLhmw6_BItw3uC4N",
				"Vnk3CmwQSsBbYA1VQ9iH5",
				"Ka-XZ_1weUCVMCaLYv4dr",
				"K3r93LGyBAsvnXzXZWgnM",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320985,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					11.344601385770602
				]
			]
		},
		{
			"type": "line",
			"version": 669,
			"versionNonce": 1541067478,
			"isDeleted": false,
			"id": "JaMxBlP4V0OE7oj11Y5wb",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 175.09741865008044,
			"y": 929.4006938474683,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.421777194913532,
			"height": 3.679330179168784,
			"seed": 1982782102,
			"groupIds": [
				"PzbhRcLhmw6_BItw3uC4N",
				"Vnk3CmwQSsBbYA1VQ9iH5",
				"Ka-XZ_1weUCVMCaLYv4dr",
				"K3r93LGyBAsvnXzXZWgnM",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320986,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.421777194913532,
					-3.679330179168784
				]
			]
		},
		{
			"type": "line",
			"version": 644,
			"versionNonce": 34663818,
			"isDeleted": false,
			"id": "4k_0PX7flOEwDFNNVg2tv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 180.4179209083449,
			"y": 936.6699077125293,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 6.087347085047694,
			"seed": 534976470,
			"groupIds": [
				"PzbhRcLhmw6_BItw3uC4N",
				"Vnk3CmwQSsBbYA1VQ9iH5",
				"Ka-XZ_1weUCVMCaLYv4dr",
				"K3r93LGyBAsvnXzXZWgnM",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320986,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					6.087347085047694
				]
			]
		},
		{
			"type": "line",
			"version": 621,
			"versionNonce": 367396886,
			"isDeleted": false,
			"id": "3o4WTaG4RWcNCTWPPk-9W",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 180.41792090834429,
			"y": 926.0369436048236,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 5.968891578787789,
			"seed": 446541078,
			"groupIds": [
				"PzbhRcLhmw6_BItw3uC4N",
				"Vnk3CmwQSsBbYA1VQ9iH5",
				"Ka-XZ_1weUCVMCaLYv4dr",
				"K3r93LGyBAsvnXzXZWgnM",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320986,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-5.968891578787789
				]
			]
		},
		{
			"type": "line",
			"version": 739,
			"versionNonce": 695118922,
			"isDeleted": false,
			"id": "XvqZcEtRbOw2q4w-XejpA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 175.04724552147485,
			"y": 933.6689045463063,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.442965749468221,
			"height": 3.2966898116198355,
			"seed": 601070166,
			"groupIds": [
				"PzbhRcLhmw6_BItw3uC4N",
				"Vnk3CmwQSsBbYA1VQ9iH5",
				"Ka-XZ_1weUCVMCaLYv4dr",
				"K3r93LGyBAsvnXzXZWgnM",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241320986,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.442965749468221,
					3.2966898116198355
				]
			]
		},
		{
			"type": "line",
			"version": 1125,
			"versionNonce": 1800967510,
			"isDeleted": false,
			"id": "_lJTj7XpR4eml894HgEZS",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 2.148993807554163,
			"x": 179.20567336694015,
			"y": 934.8234624386998,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 2.3000085423405325,
			"height": 2.7285905062518987,
			"seed": 39444374,
			"groupIds": [
				"Vnk3CmwQSsBbYA1VQ9iH5",
				"Ka-XZ_1weUCVMCaLYv4dr",
				"K3r93LGyBAsvnXzXZWgnM",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320986,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.1500042711702643,
					2.7285905062518987
				],
				[
					1.1500042711702683,
					2.7285905062518987
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 440,
			"versionNonce": 69636874,
			"isDeleted": false,
			"id": "EyeOUWOXwGjSGGtL24l0r",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.2831853071795845,
			"x": 169.07331952257363,
			"y": 920.0680520260357,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 15.12613518102747,
			"height": 22.689202771541204,
			"seed": 1516600534,
			"groupIds": [
				"Ka-XZ_1weUCVMCaLYv4dr",
				"K3r93LGyBAsvnXzXZWgnM",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320986,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 897,
			"versionNonce": 629635734,
			"isDeleted": false,
			"id": "TaMC0aXth7T-0Ny65yTQ6",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179576,
			"x": 176.00877573769452,
			"y": 966.685094298917,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 10.755271443652566,
			"height": 0,
			"seed": 25915926,
			"groupIds": [
				"CWJXqcV2WbswXG6qiy3I0",
				"sJWg-osWJScD_aFXalvz0",
				"DVOqTvS74qJLq-AijcZOp",
				"K3r93LGyBAsvnXzXZWgnM",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320986,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.755271443652566,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 895,
			"versionNonce": 1957929418,
			"isDeleted": false,
			"id": "OY7uHq7d4sfhl-ylQ0gOM",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179576,
			"x": 177.80132097830295,
			"y": 968.4776395395259,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.170180962435048,
			"height": 0,
			"seed": 1388363606,
			"groupIds": [
				"CWJXqcV2WbswXG6qiy3I0",
				"sJWg-osWJScD_aFXalvz0",
				"DVOqTvS74qJLq-AijcZOp",
				"K3r93LGyBAsvnXzXZWgnM",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320986,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.170180962435048,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 894,
			"versionNonce": 455587798,
			"isDeleted": false,
			"id": "2JgFhgld15bBRluQ4wZ3t",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179576,
			"x": 179.59386621891173,
			"y": 970.2701847801345,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 3.585090481217524,
			"height": 0,
			"seed": 39478422,
			"groupIds": [
				"CWJXqcV2WbswXG6qiy3I0",
				"sJWg-osWJScD_aFXalvz0",
				"DVOqTvS74qJLq-AijcZOp",
				"K3r93LGyBAsvnXzXZWgnM",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320986,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					3.585090481217524,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 926,
			"versionNonce": 1446041738,
			"isDeleted": false,
			"id": "L1Ulh-s9YyetmJ20mpPTm",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179576,
			"x": 180.8415168995906,
			"y": 972.0490309097197,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 1.0916880643006555,
			"height": 0,
			"seed": 1913479638,
			"groupIds": [
				"CWJXqcV2WbswXG6qiy3I0",
				"sJWg-osWJScD_aFXalvz0",
				"DVOqTvS74qJLq-AijcZOp",
				"K3r93LGyBAsvnXzXZWgnM",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320986,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.0916880643006555,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 864,
			"versionNonce": 72240406,
			"isDeleted": false,
			"id": "qZ5z3Pzh64KvnbAv48wYB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179576,
			"x": 181.38365242421116,
			"y": 959.5149133364819,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 0,
			"height": 7.563067590513735,
			"seed": 82753302,
			"groupIds": [
				"sJWg-osWJScD_aFXalvz0",
				"27c4XtCwdfZbNg5f7nyh7",
				"DVOqTvS74qJLq-AijcZOp",
				"K3r93LGyBAsvnXzXZWgnM",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320986,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					7.563067590513735
				]
			]
		},
		{
			"type": "rectangle",
			"version": 697,
			"versionNonce": 1750677322,
			"isDeleted": false,
			"id": "pkMvdfY-Hn50yfF2Hyo_W",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.283185307179576,
			"x": 173.8205848336975,
			"y": 959.5149133364819,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 15.12613518102747,
			"height": 15.126135181027513,
			"seed": 1936942166,
			"groupIds": [
				"27c4XtCwdfZbNg5f7nyh7",
				"DVOqTvS74qJLq-AijcZOp",
				"K3r93LGyBAsvnXzXZWgnM",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320986,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1498,
			"versionNonce": 1315977814,
			"isDeleted": false,
			"id": "MOkcEO1IhH5Rhp35FT0cU",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 7.809125643163043,
			"x": 169.59308939659195,
			"y": 951.4026968858968,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.689202771541254,
			"height": 5.0891851034804825,
			"seed": 527460758,
			"groupIds": [
				"XNoZ5cMdbj6D3Vgsb8VkL",
				"OCmgGMYtTwsyd2lCqCCnt",
				"K3r93LGyBAsvnXzXZWgnM",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320986,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					3.592794140591648,
					0
				],
				[
					5.02608961758383,
					-2.5681625733092295
				],
				[
					7.511838255676038,
					2.5210225301712526
				],
				[
					10.03286078584729,
					-2.521022530171251
				],
				[
					12.553883316018537,
					2.5210225301712526
				],
				[
					15.074905846189788,
					-2.521022530171251
				],
				[
					17.59592837636104,
					2.5210225301712526
				],
				[
					18.810695026375864,
					0.022419270692967206
				],
				[
					22.689202771541254,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 983,
			"versionNonce": 998751754,
			"isDeleted": false,
			"id": "1kP-3vutAq7ZUo23ZSzx5",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 7.809125643163043,
			"x": 169.67387404478905,
			"y": 947.5939669613253,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 22.689202771541204,
			"height": 7.563067590513906,
			"seed": 1746585302,
			"groupIds": [
				"OCmgGMYtTwsyd2lCqCCnt",
				"K3r93LGyBAsvnXzXZWgnM",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320986,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 266,
			"versionNonce": 1885503382,
			"isDeleted": false,
			"id": "C8b8C15u4m0vyLtwnprsD",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 126.97349325526059,
			"y": 889.148837237366,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 40.743092211388344,
			"height": 16.13587610069481,
			"seed": 1228653142,
			"groupIds": [
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320986,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 164,
			"versionNonce": 481782986,
			"isDeleted": false,
			"id": "zBPDfFTvVs4ogm9Xr3R0B",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 114.06478787947455,
			"y": 919.7398340987875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 66.15708976523355,
			"height": 0,
			"seed": 343838230,
			"groupIds": [
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320986,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.15708976523355,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 122,
			"versionNonce": 1046093014,
			"isDeleted": false,
			"id": "sZpybgPnFK_QQF6K19IXd",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 147.54673472174267,
			"y": 920.1432304394009,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 14.925687078853997,
			"seed": 542750602,
			"groupIds": [
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320987,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-14.925687078853997
				]
			]
		},
		{
			"type": "ellipse",
			"version": 162,
			"versionNonce": 25379722,
			"isDeleted": false,
			"id": "TIx_e-yg_pzwko2-TAo_v",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 145.93314374025053,
			"y": 917.3194448170302,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 4.03396902517372,
			"height": 4.03396902517372,
			"seed": 1484246730,
			"groupIds": [
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320987,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 184,
			"versionNonce": 627728865,
			"isDeleted": false,
			"id": "xHQblCQo",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 141.2057629779917,
			"y": 894.0126257605523,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 11.996994018554688,
			"height": 7.314154111914419,
			"seed": 134472394,
			"groupIds": [
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707327047793,
			"link": null,
			"locked": false,
			"fontSize": 5.8513232895315355,
			"fontFamily": 1,
			"text": "load",
			"rawText": "load",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "load",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "line",
			"version": 225,
			"versionNonce": 1948664394,
			"isDeleted": false,
			"id": "iqnRBDRq_0ku_tETsRgWG",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 147.4894329101386,
			"y": 876.5409955457112,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.2933330286988745,
			"height": 12.320739203595135,
			"seed": 1743486678,
			"groupIds": [
				"x7Q2BtUY1YmE75k8R_E1x",
				"FtipOgsRFoWv0PR9mPzBr",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320987,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.2933330286988745,
					12.320739203595135
				]
			]
		},
		{
			"type": "line",
			"version": 224,
			"versionNonce": 2047696726,
			"isDeleted": false,
			"id": "8pI5VPCNdqA-3_L143beq",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 141.62242319412,
			"y": 875.6609427454543,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12.614099089374095,
			"height": 0,
			"seed": 855716886,
			"groupIds": [
				"FtipOgsRFoWv0PR9mPzBr",
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320987,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.614099089374095,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 137,
			"versionNonce": 2014964737,
			"isDeleted": false,
			"id": "J6PH3VKz",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 142.2370025039413,
			"y": 866.5217756561894,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 9.04457054846313,
			"height": 9.924943982279334,
			"seed": 570721098,
			"groupIds": [
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707322798991,
			"link": null,
			"locked": false,
			"fontSize": 7.939955185823468,
			"fontFamily": 1,
			"text": "+V",
			"rawText": "+V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+V",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "line",
			"version": 264,
			"versionNonce": 1460864150,
			"isDeleted": false,
			"id": "K-qUEC3cbVNrrIG-UOadA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 168.9267688694519,
			"y": 931.3872621613191,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 77.45219854048966,
			"height": 56.475555114356226,
			"seed": 311194058,
			"groupIds": [
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320987,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-7.261145369120209,
					0
				],
				[
					-7.261145369120209,
					56.475555114356226
				],
				[
					-77.45219854048966,
					56.475555114356226
				]
			]
		},
		{
			"type": "line",
			"version": 179,
			"versionNonce": 452835274,
			"isDeleted": false,
			"id": "i8oL8dZP5clQBK9-Glgpv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 137.46182058736508,
			"y": 929.773699275016,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 9.278132691225942,
			"height": 58.08916295296167,
			"seed": 499349398,
			"groupIds": [
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320987,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-9.278132691225942,
					0
				],
				[
					-9.278132691225942,
					58.08916295296167
				]
			]
		},
		{
			"type": "line",
			"version": 146,
			"versionNonce": 1722941910,
			"isDeleted": false,
			"id": "ngkqrgBQYnolm9HTmxUFs",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 104.38326446667278,
			"y": 930.9838602016678,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 9.278121453150396,
			"height": 57.28235903365895,
			"seed": 282338058,
			"groupIds": [
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320987,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-9.278121453150396,
					0
				],
				[
					-9.278121453150396,
					57.28235903365895
				]
			]
		},
		{
			"type": "ellipse",
			"version": 164,
			"versionNonce": 382217866,
			"isDeleted": false,
			"id": "iuik81lzmZ3xwr3DHhlqS",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 125.85829687645642,
			"y": 985.5182203848917,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 4.03396902517372,
			"height": 4.03396902517372,
			"seed": 1972455638,
			"groupIds": [
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320987,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 164,
			"versionNonce": 1006589718,
			"isDeleted": false,
			"id": "EbCQu5TBBN2ccwlcPkZlw",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 93.08411279374043,
			"y": 985.5182203848917,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 4.03396902517372,
			"height": 4.03396902517372,
			"seed": 122158346,
			"groupIds": [
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320987,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 166,
			"versionNonce": 1771573134,
			"isDeleted": false,
			"id": "FFZlkxem",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 83.0758957154173,
			"y": 981.4139375305713,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 9.287796020507812,
			"height": 10.696960467444644,
			"seed": 643182678,
			"groupIds": [
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502114,
			"link": null,
			"locked": false,
			"fontSize": 9.30170475429969,
			"fontFamily": 2,
			"text": "---",
			"rawText": "---",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "---",
			"lineHeight": 1.15,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 245,
			"versionNonce": 1064305750,
			"isDeleted": false,
			"id": "TDyMbbHz",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 188.61651217009572,
			"y": 942.0895849278925,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 25.219100952148438,
			"height": 14.425473358459705,
			"seed": 1247552022,
			"groupIds": [
				"vDNsx7tIhIZVv0s-fi3MW"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320987,
			"link": null,
			"locked": false,
			"fontSize": 5.770189343383882,
			"fontFamily": 1,
			"text": "swamping\nresistors",
			"rawText": "swamping\nresistors",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "swamping\nresistors",
			"lineHeight": 1.25,
			"baseline": 12
		},
		{
			"type": "text",
			"version": 7181,
			"versionNonce": 851547146,
			"isDeleted": false,
			"id": "1jkiyj3d",
			"fillStyle": "solid",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2.6724159232962563,
			"y": 999.4548164488376,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 326.46453857421875,
			"height": 26.2781289531549,
			"seed": 2122006474,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320987,
			"link": null,
			"locked": false,
			"fontSize": 5.2556257906309805,
			"fontFamily": 1,
			"text": "interesting, FETs do not suffer from the problem of thermal runaway because their drain-source channel resistance naturally\nincreases with temperature, owing to the fact FETs are \"majority carrier\" devices. If one FET among a paralleled bank of\nFETs happen to become hotter than the others, it automatically restricts current to force the others to carry more, and\nthereby redistributes power dissipation to the other transistors",
			"rawText": "interesting, FETs do not suffer from the problem of thermal runaway because their drain-source channel resistance naturally\nincreases with temperature, owing to the fact FETs are \"majority carrier\" devices. If one FET among a paralleled bank of\nFETs happen to become hotter than the others, it automatically restricts current to force the others to carry more, and\nthereby redistributes power dissipation to the other transistors",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "interesting, FETs do not suffer from the problem of thermal runaway because their drain-source channel resistance naturally\nincreases with temperature, owing to the fact FETs are \"majority carrier\" devices. If one FET among a paralleled bank of\nFETs happen to become hotter than the others, it automatically restricts current to force the others to carry more, and\nthereby redistributes power dissipation to the other transistors",
			"lineHeight": 1.25,
			"baseline": 24
		},
		{
			"type": "text",
			"version": 150,
			"versionNonce": 1832181103,
			"isDeleted": false,
			"id": "Xij5vgrP",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -2.143875738777334,
			"y": 1041.8761911827553,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 204.3535614013672,
			"height": 10.175796702967567,
			"seed": 1490758166,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414219,
			"link": null,
			"locked": false,
			"fontSize": 8.140637362374054,
			"fontFamily": 1,
			"text": "DARLINGTON AND SZIKLAI PAIR CONNECTIONS",
			"rawText": "DARLINGTON AND SZIKLAI PAIR CONNECTIONS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "DARLINGTON AND SZIKLAI PAIR CONNECTIONS",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "line",
			"version": 76,
			"versionNonce": 2051441354,
			"isDeleted": false,
			"id": "QVs_gg0MtvKFIDLZGwezF",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4.091321141041973,
			"y": 1053.44206040069,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 203.59292356518415,
			"height": 0,
			"seed": 2032011274,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241320988,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					203.59292356518415,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 7110,
			"versionNonce": 660404306,
			"isDeleted": false,
			"id": "qp4TBctF",
			"fillStyle": "solid",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2.2793170744427584,
			"y": 1057.4237026432427,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 331.463134765625,
			"height": 21.65257185326388,
			"seed": 501233930,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707838502118,
			"link": null,
			"locked": false,
			"fontSize": 5.774019160870369,
			"fontFamily": 1,
			"text": "Two common dual-transistor networks used to achieve greater amplification are the Darlington pair and Szikai pair.\nEach contains two bipolar junction transistors, but while the Darlington pair uses same-type transistor the Sziklai\npair uses opposite-type transistors:",
			"rawText": "Two common dual-transistor networks used to achieve greater amplification are the Darlington pair and Szikai pair.\nEach contains two bipolar junction transistors, but while the Darlington pair uses same-type transistor the Sziklai\npair uses opposite-type transistors:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Two common dual-transistor networks used to achieve greater amplification are the Darlington pair and Szikai pair.\nEach contains two bipolar junction transistors, but while the Darlington pair uses same-type transistor the Sziklai\npair uses opposite-type transistors:",
			"lineHeight": 1.25,
			"baseline": 20
		},
		{
			"type": "line",
			"version": 430,
			"versionNonce": 1706896778,
			"isDeleted": false,
			"id": "uqHN_UCODwXotYgNhyKtP",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 77.28833873365349,
			"y": 1114.5778813437173,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8.230109480344098,
			"height": 0,
			"seed": 1436847882,
			"groupIds": [
				"jIfiZrTwxox03-ipsxfXh",
				"Ic-ESuGsSbUmJ-1Kv0LZo",
				"BSoSTlKNDRL8R7SVhAhiR",
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241555178,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.230109480344098,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 467,
			"versionNonce": 1301474378,
			"isDeleted": false,
			"id": "nKKLlgX9RcWkUzaOV-HPl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 85.71695337064658,
			"y": 1106.5462770200218,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 16.168887651649296,
			"seed": 1561468362,
			"groupIds": [
				"jIfiZrTwxox03-ipsxfXh",
				"Ic-ESuGsSbUmJ-1Kv0LZo",
				"BSoSTlKNDRL8R7SVhAhiR",
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241555178,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					16.168887651649296
				]
			]
		},
		{
			"type": "line",
			"version": 504,
			"versionNonce": 432198410,
			"isDeleted": false,
			"id": "qpULLDiO1pdX-x3jFgyAQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 85.87418310869053,
			"y": 1111.710336945352,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7.727385331210244,
			"height": 5.243963562696983,
			"seed": 627037322,
			"groupIds": [
				"jIfiZrTwxox03-ipsxfXh",
				"Ic-ESuGsSbUmJ-1Kv0LZo",
				"BSoSTlKNDRL8R7SVhAhiR",
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241555178,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.727385331210244,
					-5.243963562696983
				]
			]
		},
		{
			"type": "line",
			"version": 479,
			"versionNonce": 214426058,
			"isDeleted": false,
			"id": "U45Tpev9z7SipgazCxTlH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 93.45722638530377,
			"y": 1122.0707804993588,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.675988496007013,
			"seed": 1883812682,
			"groupIds": [
				"jIfiZrTwxox03-ipsxfXh",
				"Ic-ESuGsSbUmJ-1Kv0LZo",
				"BSoSTlKNDRL8R7SVhAhiR",
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241555178,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					8.675988496007013
				]
			]
		},
		{
			"type": "line",
			"version": 456,
			"versionNonce": 1639782538,
			"isDeleted": false,
			"id": "DkD8q6woAvshPj0cJFCAU",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 93.45722638530277,
			"y": 1106.9161535349283,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.507159842861213,
			"seed": 271038986,
			"groupIds": [
				"jIfiZrTwxox03-ipsxfXh",
				"Ic-ESuGsSbUmJ-1Kv0LZo",
				"BSoSTlKNDRL8R7SVhAhiR",
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241555178,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-8.507159842861213
				]
			]
		},
		{
			"type": "line",
			"version": 574,
			"versionNonce": 945649482,
			"isDeleted": false,
			"id": "1uMzRRmadQzEXLFGbU0sD",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 85.80267388135239,
			"y": 1117.7936021845908,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7.757584308366491,
			"height": 4.69860556346002,
			"seed": 1408755914,
			"groupIds": [
				"jIfiZrTwxox03-ipsxfXh",
				"Ic-ESuGsSbUmJ-1Kv0LZo",
				"BSoSTlKNDRL8R7SVhAhiR",
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241555178,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.757584308366491,
					4.69860556346002
				]
			]
		},
		{
			"type": "line",
			"version": 960,
			"versionNonce": 17038858,
			"isDeleted": false,
			"id": "n3F74Hx4TWEft5ijkduVl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 2.148993807554163,
			"x": 91.72947116178865,
			"y": 1119.4391352636862,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 3.2780860652876638,
			"height": 3.88892230257476,
			"seed": 1934901130,
			"groupIds": [
				"Ic-ESuGsSbUmJ-1Kv0LZo",
				"BSoSTlKNDRL8R7SVhAhiR",
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241555178,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.639043032643829,
					3.88892230257476
				],
				[
					1.6390430326438348,
					3.88892230257476
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 274,
			"versionNonce": 1756081354,
			"isDeleted": false,
			"id": "j-PMD202l2sqrh8ATrXqC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.2831853071795845,
			"x": 77.28833873365349,
			"y": 1098.408993692067,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 21.558516868865727,
			"height": 32.33777530329859,
			"seed": 2054667850,
			"groupIds": [
				"BSoSTlKNDRL8R7SVhAhiR",
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241555178,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 508,
			"versionNonce": 1156547466,
			"isDeleted": false,
			"id": "_llLWr5FI6jGIa_o_BiIH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 93.6592048699758,
			"y": 1130.948743371305,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8.230109480344098,
			"height": 0,
			"seed": 2011512534,
			"groupIds": [
				"YVtVAmdvKi6AS_FrF8tK5",
				"UqFTEemagFbrVbN5iFvPF",
				"rVBAj-yaHmJ2an6O9CNUD",
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241555178,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.230109480344098,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 545,
			"versionNonce": 688714,
			"isDeleted": false,
			"id": "-bJrALS9TaQixFg2NcxVA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 102.08781950696887,
			"y": 1122.9171390476095,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 16.168887651649296,
			"seed": 499315734,
			"groupIds": [
				"YVtVAmdvKi6AS_FrF8tK5",
				"UqFTEemagFbrVbN5iFvPF",
				"rVBAj-yaHmJ2an6O9CNUD",
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241555178,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					16.168887651649296
				]
			]
		},
		{
			"type": "line",
			"version": 582,
			"versionNonce": 81242378,
			"isDeleted": false,
			"id": "jnhbkP5yK7xm9H56Wh41j",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 102.24504924501282,
			"y": 1128.0811989729398,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7.727385331210244,
			"height": 5.243963562696983,
			"seed": 1085800790,
			"groupIds": [
				"YVtVAmdvKi6AS_FrF8tK5",
				"UqFTEemagFbrVbN5iFvPF",
				"rVBAj-yaHmJ2an6O9CNUD",
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241555178,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.727385331210244,
					-5.243963562696983
				]
			]
		},
		{
			"type": "line",
			"version": 557,
			"versionNonce": 718403530,
			"isDeleted": false,
			"id": "OUw3fDJqR4E7PCbdoOnXc",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 109.82809252162609,
			"y": 1138.4416425269467,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.675988496007013,
			"seed": 1947821718,
			"groupIds": [
				"YVtVAmdvKi6AS_FrF8tK5",
				"UqFTEemagFbrVbN5iFvPF",
				"rVBAj-yaHmJ2an6O9CNUD",
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241555178,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					8.675988496007013
				]
			]
		},
		{
			"type": "line",
			"version": 534,
			"versionNonce": 571764362,
			"isDeleted": false,
			"id": "4uio8EFV06Kg9dPmSXSkm",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 109.8280925216251,
			"y": 1123.2870155625162,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.507159842861213,
			"seed": 412885974,
			"groupIds": [
				"YVtVAmdvKi6AS_FrF8tK5",
				"UqFTEemagFbrVbN5iFvPF",
				"rVBAj-yaHmJ2an6O9CNUD",
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241555178,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-8.507159842861213
				]
			]
		},
		{
			"type": "line",
			"version": 652,
			"versionNonce": 1599737162,
			"isDeleted": false,
			"id": "kx-yx-Tc2O2F3cgtaFNg-",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 102.17354001767471,
			"y": 1134.1644642121787,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7.757584308366491,
			"height": 4.69860556346002,
			"seed": 810891542,
			"groupIds": [
				"YVtVAmdvKi6AS_FrF8tK5",
				"UqFTEemagFbrVbN5iFvPF",
				"rVBAj-yaHmJ2an6O9CNUD",
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241555178,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.757584308366491,
					4.69860556346002
				]
			]
		},
		{
			"type": "line",
			"version": 1038,
			"versionNonce": 134075402,
			"isDeleted": false,
			"id": "OlgSkxWA_Eim6_e8wamKc",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 2.148993807554163,
			"x": 108.10033729811097,
			"y": 1135.8099972912742,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 3.2780860652876638,
			"height": 3.88892230257476,
			"seed": 851027542,
			"groupIds": [
				"UqFTEemagFbrVbN5iFvPF",
				"rVBAj-yaHmJ2an6O9CNUD",
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241555179,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.639043032643829,
					3.88892230257476
				],
				[
					1.6390430326438348,
					3.88892230257476
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 352,
			"versionNonce": 1576714954,
			"isDeleted": false,
			"id": "9xfjlUxF1qmMIauot06Xr",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.2831853071795845,
			"x": 93.6592048699758,
			"y": 1114.7798557196547,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 21.558516868865727,
			"height": 32.33777530329859,
			"seed": 1620994966,
			"groupIds": [
				"rVBAj-yaHmJ2an6O9CNUD",
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241555179,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 149,
			"versionNonce": 736876938,
			"isDeleted": false,
			"id": "ph898rFCv5pi1SJ-f346R",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 109.89920608034582,
			"y": 1146.6094281138758,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 0,
			"height": 10.029001665597553,
			"seed": 768188810,
			"groupIds": [
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241555179,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					10.029001665597553
				]
			]
		},
		{
			"type": "line",
			"version": 213,
			"versionNonce": 822876234,
			"isDeleted": false,
			"id": "OalJ6e8SIfFZlKj1w3xfC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 109.86648411930328,
			"y": 1086.363022219541,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 0,
			"height": 28.94125974710903,
			"seed": 639979402,
			"groupIds": [
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241555179,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					28.94125974710903
				]
			]
		},
		{
			"type": "line",
			"version": 167,
			"versionNonce": 221675274,
			"isDeleted": false,
			"id": "yrZPPbo2N0NREtSz6IoHM",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 93.49505919509774,
			"y": 1099.046755269725,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 16.51835326761099,
			"height": 6.194381448170556,
			"seed": 1079839050,
			"groupIds": [
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241555179,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-6.194381448170556
				],
				[
					16.51835326761099,
					-6.194381448170556
				]
			]
		},
		{
			"type": "ellipse",
			"version": 155,
			"versionNonce": 753274314,
			"isDeleted": false,
			"id": "ujuNgm0hbBkFsqr_RrZod",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 108.63667416307409,
			"y": 1091.6222598189772,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 2.2122823169236705,
			"height": 2.507248362032123,
			"seed": 1646990858,
			"groupIds": [
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241555179,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 216,
			"versionNonce": 892716170,
			"isDeleted": false,
			"id": "vPUzRdIwxcma0h3RloY3n",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 108.1990498090672,
			"y": 1082.9522713404451,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.201273472307649,
			"height": 3.201273472307649,
			"seed": 184770250,
			"groupIds": [
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241555179,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 178,
			"versionNonce": 1876992842,
			"isDeleted": false,
			"id": "YS_fvlMBK2fHamxGuber5",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 108.43354038696121,
			"y": 1156.497477590304,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.8022185158751065,
			"height": 2.8022185158751065,
			"seed": 871422486,
			"groupIds": [
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241555179,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 221,
			"versionNonce": 927050250,
			"isDeleted": false,
			"id": "UsWVl5FKSNPzqhh3zbm-5",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 73.60353162220606,
			"y": 1113.2703262393827,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.201273472307649,
			"height": 3.201273472307649,
			"seed": 2104113686,
			"groupIds": [
				"_CbyVpowmp6Y5dw3V01qA"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241555179,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 574,
			"versionNonce": 1311577482,
			"isDeleted": false,
			"id": "26revPGNxSHCqCkuVkhLh",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 226.3072707882888,
			"y": 1128.1182585391007,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8.185721496354299,
			"height": 0,
			"seed": 1417201238,
			"groupIds": [
				"H-qoWQTJ7miRsfYwZ39aW",
				"h78_IDFD3Sb3HD6dedn65",
				"uyjo8yycre1z15SPt0XOC",
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.185721496354299,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 611,
			"versionNonce": 1875235914,
			"isDeleted": false,
			"id": "xAnD3N9Zwqb6Q16Xn3BVj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 234.6904268305382,
			"y": 1120.1299715886412,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 16.081682939740137,
			"seed": 1031375766,
			"groupIds": [
				"H-qoWQTJ7miRsfYwZ39aW",
				"h78_IDFD3Sb3HD6dedn65",
				"uyjo8yycre1z15SPt0XOC",
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					16.081682939740137
				]
			]
		},
		{
			"type": "line",
			"version": 648,
			"versionNonce": 1163442954,
			"isDeleted": false,
			"id": "g1XgM7ZjE4-cuP7u4Z-d_",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 234.84680857122422,
			"y": 1125.2661798541806,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7.685708722024916,
			"height": 5.215680953429149,
			"seed": 1823451350,
			"groupIds": [
				"H-qoWQTJ7miRsfYwZ39aW",
				"h78_IDFD3Sb3HD6dedn65",
				"uyjo8yycre1z15SPt0XOC",
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.685708722024916,
					-5.215680953429149
				]
			]
		},
		{
			"type": "line",
			"version": 623,
			"versionNonce": 492882378,
			"isDeleted": false,
			"id": "oBozTaSxRZsLar6nkPePH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 242.38895372802986,
			"y": 1135.570745755077,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.629195723763074,
			"seed": 565190166,
			"groupIds": [
				"H-qoWQTJ7miRsfYwZ39aW",
				"h78_IDFD3Sb3HD6dedn65",
				"uyjo8yycre1z15SPt0XOC",
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					8.629195723763074
				]
			]
		},
		{
			"type": "line",
			"version": 600,
			"versionNonce": 1056505994,
			"isDeleted": false,
			"id": "vRqNUDg_yaI7Fx_7HJHxy",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 242.38895372802895,
			"y": 1120.4978532245173,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.461277625157376,
			"seed": 1634724694,
			"groupIds": [
				"H-qoWQTJ7miRsfYwZ39aW",
				"h78_IDFD3Sb3HD6dedn65",
				"uyjo8yycre1z15SPt0XOC",
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-8.461277625157376
				]
			]
		},
		{
			"type": "line",
			"version": 718,
			"versionNonce": 1440505674,
			"isDeleted": false,
			"id": "S-jhPArqWNAJhb6Y1LsaS",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 234.77568501924625,
			"y": 1131.3166358239084,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7.715744825076302,
			"height": 4.673264268909401,
			"seed": 1245974678,
			"groupIds": [
				"H-qoWQTJ7miRsfYwZ39aW",
				"h78_IDFD3Sb3HD6dedn65",
				"uyjo8yycre1z15SPt0XOC",
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.715744825076302,
					4.673264268909401
				]
			]
		},
		{
			"type": "line",
			"version": 1104,
			"versionNonce": 1583736330,
			"isDeleted": false,
			"id": "e99Rhn_g3iYqCODV-_-w5",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 2.148993807554163,
			"x": 240.67051691897612,
			"y": 1132.9532939425742,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 3.2604061508064914,
			"height": 3.8679479253424125,
			"seed": 1742835158,
			"groupIds": [
				"h78_IDFD3Sb3HD6dedn65",
				"uyjo8yycre1z15SPt0XOC",
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.6302030754032426,
					3.8679479253424125
				],
				[
					1.6302030754032484,
					3.8679479253424125
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 418,
			"versionNonce": 294687946,
			"isDeleted": false,
			"id": "z3Vq-pKGIPrR8bBSTjM9F",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.2831853071795845,
			"x": 226.3072707882888,
			"y": 1112.0365755993596,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 21.442243919653517,
			"height": 32.163365879480274,
			"seed": 123560726,
			"groupIds": [
				"uyjo8yycre1z15SPt0XOC",
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 801,
			"versionNonce": 1358392202,
			"isDeleted": false,
			"id": "V2HJEZY26lk_jVmDyq94K",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 211.35238563730695,
			"y": 1113.5013752638156,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7.601833564507601,
			"height": 0,
			"seed": 1254433942,
			"groupIds": [
				"OdAt0_xAfgF6pV0nzaLTG",
				"Fmo86rGga5Xrb1EVHygVg",
				"sffegduco9IgYv_Bu0wdw",
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.601833564507601,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 826,
			"versionNonce": 315976266,
			"isDeleted": false,
			"id": "T_r2bbHdvQEXDJs4qFF0E",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 219.1375707314818,
			"y": 1120.9198572986566,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 14.934575675404156,
			"seed": 1595941334,
			"groupIds": [
				"OdAt0_xAfgF6pV0nzaLTG",
				"Fmo86rGga5Xrb1EVHygVg",
				"sffegduco9IgYv_Bu0wdw",
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-14.934575675404156
				]
			]
		},
		{
			"type": "line",
			"version": 863,
			"versionNonce": 1308987658,
			"isDeleted": false,
			"id": "Wn6tq4crVoBiINjyFymUl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 219.28279775462744,
			"y": 1116.1500150306695,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7.137486726874225,
			"height": 4.843646164995863,
			"seed": 1101625110,
			"groupIds": [
				"OdAt0_xAfgF6pV0nzaLTG",
				"Fmo86rGga5Xrb1EVHygVg",
				"sffegduco9IgYv_Bu0wdw",
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.137486726874225,
					4.843646164995863
				]
			]
		},
		{
			"type": "line",
			"version": 838,
			"versionNonce": 1711464394,
			"isDeleted": false,
			"id": "U_Keu-7fXCL9aNv9mMa8I",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 226.28696131271113,
			"y": 1106.5804743410672,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.013674752655959,
			"seed": 1255547990,
			"groupIds": [
				"OdAt0_xAfgF6pV0nzaLTG",
				"Fmo86rGga5Xrb1EVHygVg",
				"sffegduco9IgYv_Bu0wdw",
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-8.013674752655959
				]
			]
		},
		{
			"type": "line",
			"version": 815,
			"versionNonce": 384325258,
			"isDeleted": false,
			"id": "86m0_DrGHdqsFTz-YTE1R",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 226.28696131271204,
			"y": 1120.5782166786314,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 7.857734260588447,
			"seed": 2088446358,
			"groupIds": [
				"OdAt0_xAfgF6pV0nzaLTG",
				"Fmo86rGga5Xrb1EVHygVg",
				"sffegduco9IgYv_Bu0wdw",
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					7.857734260588447
				]
			]
		},
		{
			"type": "line",
			"version": 933,
			"versionNonce": 1634792778,
			"isDeleted": false,
			"id": "KiXp_cZLQJHyHukMsLEUR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 219.21674744924024,
			"y": 1110.5311383938656,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7.165380353162969,
			"height": 4.339920090248809,
			"seed": 1439532758,
			"groupIds": [
				"OdAt0_xAfgF6pV0nzaLTG",
				"Fmo86rGga5Xrb1EVHygVg",
				"sffegduco9IgYv_Bu0wdw",
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.165380353162969,
					-4.339920090248809
				]
			]
		},
		{
			"type": "line",
			"version": 1544,
			"versionNonce": 1995947018,
			"isDeleted": false,
			"id": "1dw3FCo2G-Gb9yk4fpTTd",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0.9729558637639641,
			"x": 221.04852125587053,
			"y": 1111.3181901565308,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 3.027841213772838,
			"height": 3.5920470025435165,
			"seed": 660749334,
			"groupIds": [
				"Fmo86rGga5Xrb1EVHygVg",
				"sffegduco9IgYv_Bu0wdw",
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.5139206068864164,
					-3.5920470025435165
				],
				[
					1.5139206068864217,
					-3.5920470025435165
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 516,
			"versionNonce": 628599498,
			"isDeleted": false,
			"id": "4BLGDz82mSeGxbIDgwiAM",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 211.35238563730695,
			"y": 1098.5667995884112,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 19.91276756720554,
			"height": 29.869151350808313,
			"seed": 1731086678,
			"groupIds": [
				"sffegduco9IgYv_Bu0wdw",
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 215,
			"versionNonce": 1133232522,
			"isDeleted": false,
			"id": "h8sfqV-0nB1edmxfj8zet",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 242.4177356765811,
			"y": 1112.3420444448234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 0,
			"height": 29.5698682567584,
			"seed": 1541920010,
			"groupIds": [
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-29.5698682567584
				]
			]
		},
		{
			"type": "line",
			"version": 200,
			"versionNonce": 477036618,
			"isDeleted": false,
			"id": "S1b_XNl56pqqCN4XUSOoT",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 226.2732620153322,
			"y": 1099.0865843017216,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 16.3144081136564,
			"height": 8.497091899009042,
			"seed": 1053110934,
			"groupIds": [
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-8.497091899009042
				],
				[
					16.3144081136564,
					-8.497091899009042
				]
			]
		},
		{
			"type": "line",
			"version": 185,
			"versionNonce": 1543268106,
			"isDeleted": false,
			"id": "91ZkxjvG-bnuR6YIbSu3A",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 242.41773567658097,
			"y": 1143.6715537985062,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 0,
			"height": 14.954875682298894,
			"seed": 1378145110,
			"groupIds": [
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					14.954875682298894
				]
			]
		},
		{
			"type": "ellipse",
			"version": 193,
			"versionNonce": 2058286538,
			"isDeleted": false,
			"id": "8s6YMkFxQ425opY9QkqcA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 240.84430096366603,
			"y": 1089.3435178856428,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 2.5491304103075954,
			"height": 2.8890087838054663,
			"seed": 1122220822,
			"groupIds": [
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 208,
			"versionNonce": 698461322,
			"isDeleted": false,
			"id": "x7xDBpGB-5iXmvxXjf7q4",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 240.87391663667646,
			"y": 1079.6807340648918,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.2288918916449085,
			"height": 3.2288918916449085,
			"seed": 993185814,
			"groupIds": [
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 209,
			"versionNonce": 1049594698,
			"isDeleted": false,
			"id": "UoNuCFyW9TlWB4du918sU",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 240.79988573924803,
			"y": 1158.282642908431,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.2288918916449085,
			"height": 3.2288918916449085,
			"seed": 1962635210,
			"groupIds": [
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 298,
			"versionNonce": 533959178,
			"isDeleted": false,
			"id": "x4iiSwC2vE8RikgHaDKST",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 207.86419366470756,
			"y": 1111.521274302742,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.201273472307649,
			"height": 3.201273472307649,
			"seed": 2053648458,
			"groupIds": [
				"mjXQQ2cc5CrMjklhYaBQX"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241490933,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 98,
			"versionNonce": 1394947329,
			"isDeleted": false,
			"id": "ohOJB8Ak",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 36.10197689943972,
			"y": 1144.0015521971598,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 63.16107177734375,
			"height": 10.68957698997135,
			"seed": 1653773898,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707348414220,
			"link": null,
			"locked": false,
			"fontSize": 8.55166159197708,
			"fontFamily": 1,
			"text": "Darlington Pair",
			"rawText": "Darlington Pair",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Darlington Pair",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "text",
			"version": 63,
			"versionNonce": 131259734,
			"isDeleted": false,
			"id": "rHjzlNVI",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 198.87757293990873,
			"y": 1146.75821556115,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.11982727050781,
			"height": 8.434357347475496,
			"seed": 1765072586,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1707241515414,
			"link": null,
			"locked": false,
			"fontSize": 6.747485877980397,
			"fontFamily": 1,
			"text": "Sziklai Pair",
			"rawText": "Sziklai Pair",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Sziklai Pair",
			"lineHeight": 1.25,
			"baseline": 6
		}
	],
	"appState": {
		"theme": "dark",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1e1e1e",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "solid",
		"currentItemStrokeWidth": 0.5,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 0,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 2284.589449420998,
		"scrollY": 820.9125266868596,
		"zoom": {
			"value": 0.15000000000000002
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"gridColor": {
			"Bold": "#C9C9C9FF",
			"Regular": "#EDEDEDFF"
		},
		"currentStrokeOptions": null,
		"previousGridSize": null,
		"frameRendering": {
			"enabled": true,
			"clip": true,
			"name": true,
			"outline": true
		}
	},
	"files": {}
}
```
%%