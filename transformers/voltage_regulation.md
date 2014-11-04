#Voltage Regulation

Voltage Regulation is a  transformer's ability to keep output voltage constant.

Ideal transformer has the same output voltage level at full load and at no load. However, practical transformers output voltage varies according the load current and power factor.

$$V_{reg}=\frac{V_2(No\;Load)-V_2(Full\;Load)}{V_2(No\;Load)}$$

A smaller voltage regulation means a better design for a power transformer.

A capacitive load can result in negative voltage regulation.

---
#### Example:
For the same transformer(1000 VA) used in the no-load, short-circuit tests, calculate the voltage regulation when:

- a) 0.8 pf lagging rated current
- b) 1.0 pf rated current
- c) 0.8 pf leading rated current

at the primary side, if the input voltage of the transformer is kept at 230 V.

Equivalent circuit of the transformer is:

![](../images/simplified_transformer.gif)
$$R_{c}=1763~\Omega \quad X_{m}=534.3~\Omega\quad R_{eq}=0.558~\Omega\quad
X_{eq}=2.13~\Omega\quad$$

As the input voltage is kept constant, the parallel branch can be neglected and the equivalent circuit becomes:
![](../images/mostsimplified.png)

$$\vec{V_1}=\vec{V_2'}+(R_{eq}+jX_{eq})\vec{I_1}$$
At no load, \\(I_1=0\\), thus:
$$\vec{V_2'}_{no~load}=\vec{V_1'}=230~V$$

When the machine operates at rated load:
$$I_{rated}=\frac{S_{rated}}{V_{rated}}=\frac{1000}{230}=4.35~A$$

**a) 0.8 pf lagging rated current:**
$$\vec{V_1}=\vec{V_2'}+(R_{eq}+jX_{eq})\vec{I_1}$$
$$\vec{V_2'}=\vec{V_1}-(R_{eq}+jX_{eq})\vec{I_1}$$
$$\vec{V_2'}=230 \angle 0-(0.558+j2.13)4.35\angle{-37}=222.5\angle -1.5$$

$$V_{reg}=\frac{V_2(No\;Load)-V_2(Full\;Load)}{V_2(No\;Load)}$$
$$V_{reg}=\frac{230-222.5}{230}=3.26\%$$

**b) 1.0 pf resistive rated current:**

$$\vec{V_2'}=230 \angle 0-(0.558+j2.13)4.35\angle{0}=227.8\angle -2.3$$

$$V_{reg}=\frac{230-227.8}{230}=0.96\%$$

**c) 0.8 pf leading rated current:**

$$\vec{V_2'}=230 \angle 0-(0.558+j2.13)4.35\angle{37}=233.8\angle -2.18$$

$$V_{reg}=\frac{230-233.8}{230}=-1.65\%$$

with capacitive load negative voltage regulation is achieved.
