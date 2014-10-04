# Flux Linkage

Flux linkage is the total flux linked by the coil. TThe unit of the flux linkage is turn.Weber.

$$\lambda = N_{turns} \Phi$$

![](http://img.tfd.com/mgh/cep/thumb/B-magnetic-flux-field-of-a-short-coil.jpg)

#Faraday's Law

Kirchhoff's voltage law is just a simplified version of Faraday's Law and it is not valid when there is an external magnetic field. (Please watch: [Kirchhoff's Law vs Faraday's Law](http://www.youtube.com/watch?v=eqjl-qRy71w))

Faraday's Law can be expressed in integral form as:

### \\(\oint \vec{E} dl = -\frac{\partial\Phi}{\partial t}\\)

For a single turn coil, the induced voltage is:

\\(e = -\frac{d \Phi}{dt} = -\frac{d\oint \vec{B} d\vec{A}}{dt} \\)

If the number of turns is $$N_{turns}$$, then the induced voltage becomes:

$$e(t) = \frac{\mathrm{d} \lambda(t)}{\mathrm{d}t}$$
$$e(t) = N_{turns} \times \frac{\mathrm{d} \Phi(t)}{\mathrm{d}t}$$

If the magnetic flux distribution is uniform:

$$e(t) = N_{turns} \times Area \times \frac{\mathrm{d} B(t)}{\mathrm{d}t}$$

Methods to generate voltage in a coil:
- Varying magnetic flux by an AC excitation
- Varying flux linkage by changing area
- Motion or rotation of the coil thorugh a static field

# Inductance
There is a direct coupling between inductors in electric circuits and magnetic circuits:

Consider a basic magnetic circuit with a coil:

From the side of the electric circuit:

$$e(t) =L \frac{\mathrm{d}I}{\mathrm{d}t}$$

From Faraday's Law
$$e(t) = \frac{\mathrm{d} \lambda}{\mathrm{d}t}$$

Thus:

$$L \frac{\mathrm{d}I}{\mathrm{d}t} = \frac{\mathrm{d} \lambda}{\mathrm{d}t} $$

$$L = \frac{\mathrm{d} \lambda}{\mathrm{d}I} $$

**Inductance is the flux created per current.**



