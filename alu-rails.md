# Inner construction 

I need some material to store and connect 3 of the [Odroid
stacks](stackrack.md) safely in the box. 

I have a small wood workshop, but wood (and multiplex boards and
similar) is not looking suitable for this project.

I started to search for aluminium system profiles. 

## Aluminium system profiles

These system profiles use grooves (named t-slots) on squared profiles which can
use suitable t-slot nuts with threads in them to connect to other profiles with
some specialized connector types for different connections. 

![Aluminium profile system, i-type)](pics/aluprofile_sm.jpg)

In europe are two predominant, quite similar looking but not compatible
systems present, i do not know if other markets have them also or use different
systems. 

These systems are named with a letter for the inventors (B for
[Bosch-Rexroth](https://www.boschrexroth.com/de/de/produkte/produktgruppen/montagetechnik/themen/aluminiumprofile-loesungen-komponenten/)
or I for [Item](https://www.item24.com/de-de/profiltechnik)), there are a lot
of other manufacturers which build them also, all profiles of one type are
compatible to the same system.

The differences between the systems are the shapes of the t-slots, the shapes
of the nuts and their thread diameters - from my perspective: It does not
matter which system is used, but you need to stay into the choosen system.

I found this (german) pages useful to dive into the alu profile thingie:
- [Aluprofile - Materialkunde](https://www.franzek.com/aluprofile-materialkunde)
- [Aluprofilverbinder und Nutsteine](https://www.franzek.com/aluprofilverbinder-und-nutensteine-camper-ausbau/)

The profiles are available from 20mm edge length up to 80mm, Item provides a
profile in a [wood compound
material](https://www.item24.com/de-de/profil-kh-8-40x40-anthrazit-62686) which
looks very interesting for me (it can be worked with wood sawblades and other
wood tools), but only on 40x40mm - i am very sure that 20x20 is strong enough
for this purpose.

After some wild drawings to get a somehow realistic idea how many running
meters of that profile system i would need, i decided to buy  I-type rails in
20x20mm with 5mm t-slot, the t-slot nuts with a spring loaded sphere - these
can be slotted in from the side, not only from the end.  See pictures below.
The diameter of the threads in these nuts is M5.

![Aluminium profiles in the shop)](pics/alu-profiles_sm.jpg)

I ordered also plenty 90° angles and suitable (lol, read later)
screws to construct an inner cage for the odroid stacks and for the display in
the lid.

![Aluminium profile angles, i-type)](pics/alu-angle_sm.jpg)
![Aluminium nuts and bolts)](pics/alu-nuts-and-angles_sm.jpg)

I ordered also some metal working tools i did not had so far: 
- An aluminium blade for my miter saw
- A M5 thread cutter (to grind threads into the end of a profile) and 
- A steel needle to apply marks for measurements.

I am a desperate stick welder (on agriculture equipment and other 
big game stuff) and i am able to use an angle grinder, but i do not
consider me as a metal guy, but hey - its only Albert „Al“uminium Borland and there is also
a [tools chapter](tools.md) later to describe that better.

![Al uminium](https://hallmark.brightspotcdn.com/dims4/default/e7ca8f1/2147483647/strip/true/crop/2450x2450+0+0/resize/600x600!/format/webp/quality/90/?url=http%3A%2F%2Fhallmark-channel-brightspot.s3.amazonaws.com%2F96%2Faf%2F6ffe50a5d7536f7c1ae6f288e890%2Fhi-21-color-photo.jpg)

### t-slot nuts

There are different types.  For me important: I need to set or remove them at
any time, even if rails are already screwed together.  There are types which
can only applied from the front side (slide in).  Other can be squeezed in
anywhere, some of them click in right in place (they have springloaded balls in them),
other needed to be fidled into the right position and directly screwed to not
flipping in a bad position.

![Nutstein I-Type 5 M5](https://www.motedis.com/media-images/product/4226_0/w-700/Nutenstein-mit-Steg-I-Typ-Nut-5-M5.webp)

### You might be screwed

Its a system. 

You just need the damn right screws - i ordered the rails, t-slot nuts, screws,
angles all together, and i ordered 12mm long screws - i learned very fast that
this configuration needs 10mm screws as the angles wiggled around with some mm
thread left between screw head and angle.

As you might expect, this is normed (a german DIN 7380) - and it seems not
possible to get these on a saturday afternoon in a local hardware store, they
have them with a much bigger pozidrive head only and these colide with each
other in the 90° angles i use to connect the profiles.

![wrong screws](pics/wrong-screw-head_sm.jpg)

I needed to stop and order the right ones. 

Does someone need 200 pieces 12mm M5 DIN 7380 with hex head? Or 200x 10mm M5 not
normed bighead pozidrive?

## Construction

I started to build a first set of rails around the handle bulb. The connector
angles help to create perfect fitting.

See [chips warning](tools.md#sawing-aluminium) before you run your saw.

![ground work](pics/ground-rig_sm.jpg)

The handle bulb is 20.something mm high, so the 20mm rails match perfectly.

I was a little concerned about the edges of the box - they are rounded. But
thats not a problem for this type of construction.

I did not needed much time to find a way to pinch the stackracks in a secure
and sturdy way in all dimensions between these rails and started to cut and
mount rails.

Please note that at this time i worked with mockups, one stack had no odroids
and no switch, one is only 3 pieces not four - this will be fixed later.

I will also add some [dense foam](frame-box-connection#foam) between rails and
stacks to have some suspension against hard impacts.

![intermediate cage](pics/cage_sm.jpg)
![intermediate cage](pics/cage-with-stacks_sm.jpg)

It is really easy to use these angles to connect rails in a very sturdy way.
There are also preformed corners to connect two or three rails directly in the
corner, but they are more expensive and there is no margin left for adjusting
some 1/10 mm if neccessary.

![with powersupply](pics/cage-psu_sm.jpg)

I mounted the odroid stacks inbetween the rails with some
[foam](frame-box-connection.md#foam), that was a little bit tricky besides to
find the right type of foam.

My odroid-stacks are asymetric by attaching my [rackmount fan
connector](https://www.thingiverse.com/thing:5867495) on the right side, i
needed different thick foam to get a even pressure on both sides of a stack.

![foam3](pics/foam3_sm.jpg)
![foam4](pics/foam4_sm.jpg)

The stacks are completly trapped between rails on all sides. 

The rails on the top do bend very slighly - with one stack more it would need
more downforce support in the middle or bigger diameters for this long
unsupported distance.

The PSU is the most heavy single peace in that case, it is also trapped on all
sides.  It is really easy to build tight fitting cages with this connection
triangles as they are movable in both directions until really screwed down.


