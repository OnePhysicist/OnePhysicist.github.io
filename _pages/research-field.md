---
permalink: /research-field/
title: "Research Field"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

{% include toc %}

## Maxwell's Equations

### **1. Gauss’s Law for Electricity**

* **Differential form**
  $$
  \nabla \cdot \mathbf{E} = \frac{\rho}{\varepsilon_0}
  $$
  The divergence of the electric field equals the charge density over the permittivity of free space. Charges are the sources of the electric field.

* **Integral form**
  $$
  \oint_{\partial V} \mathbf{E} \cdot d\mathbf{A} = \frac{Q_{in}}{\varepsilon_0}
  $$
  The electric flux through a closed surface is proportional to the enclosed charge.

---

### **2. Gauss’s Law for Magnetism**

* **Differential form**
  $$
  \nabla \cdot \mathbf{B} = 0
  $$
  Magnetic fields have no divergence — there are no magnetic monopoles.

* **Integral form**
  $$
  \oint_{\partial V} \mathbf{B} \cdot d\mathbf{A} = 0
  $$
  The net magnetic flux through a closed surface is always zero.

---

### **3. Faraday’s Law of Induction**

* **Differential form**
  $$
  \nabla \times \mathbf{E} = - \frac{\partial \mathbf{B}}{\partial t}
  $$
  A changing magnetic field induces a circulating electric field.

* **Integral form**
  $$
  \oint_{\partial S} \mathbf{E} \cdot d\mathbf{l} = - \frac{d}{dt} \int_S \mathbf{B} \cdot d\mathbf{A}
  $$
  The induced electromotive force equals the negative rate of change of magnetic flux.

---

### **4. Ampère–Maxwell Law**

* **Differential form**
  $$
  \nabla \times \mathbf{B} = \mu_0 \mathbf{J} + \mu_0 \varepsilon_0 \frac{\partial \mathbf{E}}{\partial t}
  $$
  Currents and time-varying electric fields produce circulating magnetic fields.

* **Integral form**
  $$
  \oint_{\partial S} \mathbf{B} \cdot d\mathbf{l} = \mu_0 I_{in} + \mu_0 \varepsilon_0 \frac{d}{dt} \int_S \mathbf{E} \cdot d\mathbf{A}
  $$

---

✨ **Summary:**

* Charges produce electric fields (Gauss’s law for electricity).
* No magnetic monopoles exist (Gauss’s law for magnetism).
* Changing magnetic fields induce electric fields (Faraday’s law).
* Currents and changing electric fields induce magnetic fields (Ampère–Maxwell law).

Together with the **Lorentz force law**
$$
\mathbf{F} = q(\mathbf{E} + \mathbf{v} \times \mathbf{B}),
$$
they form the foundation of **classical electromagnetism**.

---
