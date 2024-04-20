# cluster-in-a-box

Buiilding a Demo / Lab K8S Cluster in a easy to move box

After my first attempt of building an 18 node lab cluster for an former
employer and some back and forth with the [stacked odroids](stackrack.md) i saw
a 6 nodes kubernetes cluster in a [pelicase style](https://www.peli.com/)
rugged case on the KubeConEu Paris 2034 booth of
[BrainGu](https://braingu.com/).

FIXME: Ask Tim from BrainGu for permission to show a picture of his setup.

I directly started to think how i could build something similar based on my
[Odroids](hardware.md).

This is some documentation about the build process, what i considered, what i
**not** considered, what worked, what turned out not working at all for anybody
else who things to do similar stuff.

## Learning from the past

### The 18 node lab cluster 

was considered to simulate our production bare metal
setup in three different DC locations, having the same full redundancy mechs
(multiple switches per DC, psu per DC, bgp routing, hsm, bootstrapping with
dedicated origin nodes per DC and stuff like that) as the real production setup
 - we wanted to check and train our assumptions.

[Pictures of this labcluster](https://photos.app.goo.gl/ya45xb5jxJ1xBKEp7) 

Known problems:
- I built that rack by plywood and flightcase aluminium profiles, i was very
    heavy and was not really easy to carry around. We used that thing to find
    problem with our setup, but we never moved it to conferences or customers
    to showcase our setup - it was just to heavy and difficult to transport.
- Switches, Powersupplies and Nodes could not be changed in a easy way, in that case we
    would need a to do a lot of dissassambly work.
- The rack was not as stable from corner to a diagonal corner as it had no back
    lid to stabilize it.
- Starting with COVID-19 and working from home we
    missed a BMC to restart single nodes. I built a relay switchboard system to
    powercycle individual nodes from remote. 

### Small Stacks

with Odroids worked out really great. This model allows a small (3 to 5 node)
stack which is easy to carry around to demonstrate things.

