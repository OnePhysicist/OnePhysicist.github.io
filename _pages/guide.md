---
permalink: /markdown/
title: "Research Field"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

{% include toc %}

## Maxwell's Equations

麦克斯韦方程组是经典电磁学的核心，描述了电场与磁场的基本规律。它由四个方程组成，可以写成微分形式或积分形式：

---

### **1. 高斯定律（电场的散度）**

* **微分形式**
  $$
  \nabla \cdot \mathbf{E} = \frac{\rho}{\varepsilon_0}
  $$
  电场的散度等于电荷密度除以真空介电常数，说明 **电荷是电场的源**。

* **积分形式**
  $$
  \oint_{\partial V} \mathbf{E} \cdot d\mathbf{A} = \frac{Q_{in}}{\varepsilon_0}
  $$
  电场穿过闭合曲面的通量等于包围电荷量与常数的比值。

---

### **2. 高斯定律（磁场的散度）**

* **微分形式**
  $$
  \nabla \cdot \mathbf{B} = 0
  $$
  磁场无源，即 **不存在“磁单极子”**。

* **积分形式**
  $$
  \oint_{\partial V} \mathbf{B} \cdot d\mathbf{A} = 0
  $$
  磁场穿过任意闭合曲面的通量为零。

---

### **3. 法拉第电磁感应定律**

* **微分形式**
  $$
  \nabla \times \mathbf{E} = - \frac{\partial \mathbf{B}}{\partial t}
  $$
  变化的磁场会产生旋转的电场。

* **积分形式**
  $$
  \oint_{\partial S} \mathbf{E} \cdot d\mathbf{l} = - \frac{d}{dt} \int_S \mathbf{B} \cdot d\mathbf{A}
  $$
  磁通量随时间的变化产生感应电动势。

---

### **4. 安培–麦克斯韦环路定律**

* **微分形式**
  $$
  \nabla \times \mathbf{B} = \mu_0 \mathbf{J} + \mu_0 \varepsilon_0 \frac{\partial \mathbf{E}}{\partial t}
  $$
  电流和变化的电场会产生旋转的磁场。

* **积分形式**
  $$
  \oint_{\partial S} \mathbf{B} \cdot d\mathbf{l} = \mu_0 I_{in} + \mu_0 \varepsilon_0 \frac{d}{dt} \int_S \mathbf{E} \cdot d\mathbf{A}
  $$

---

✨ 总结：

* 电荷产生电场（高斯电定律）。
* 不存在磁单极子（高斯磁定律）。
* 变化的磁场产生电场（法拉第定律）。
* 电流和变化的电场产生磁场（安培–麦克斯韦定律）。

这四个方程与 **洛伦兹力定律**
$$
\mathbf{F} = q(\mathbf{E} + \mathbf{v} \times \mathbf{B})
$$
共同构成了 **经典电磁学的完整理论体系**。

---

