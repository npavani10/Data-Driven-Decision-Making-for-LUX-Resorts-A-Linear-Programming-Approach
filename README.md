# 🏨 LUX* Resorts & Hotels: Revenue Optimization through Linear Programming

**Contributors**: Pavani Narla, Mikhail Joel Charles, Pranay Rai  
**Tool Used**: Excel Solver (Linear Programming)

---

## 📘 Project Overview

This case study focuses on optimizing room allocation strategy for **LUX\*** Resorts & Hotels across various **seasons and locations** using a **Linear Programming (LP)** model.

### 🎯 Objectives:
- Achieve the target **EBITA of €38 million** from **foreign guests**.
- Determine **net revenue from local guests** to support **CSR programs**.
- Optimize room mix strategy across 10 hotel locations, balancing **occupancy and revenue**.

---

## 🏨 Company Background

- Formerly Naiade Hotels, rebranded to **LUX\*** with a focus on **guest satisfaction**, innovation, and **social responsibility**.
- Operates **10 hotels** across **Mauritius, China, Maldives, and Réunion**.
- Faces challenges from **seasonal demand**, **limited room inventory**, and **variable pricing**.

---

## 🛠️ Methods and Model

### ✅ Model Type:
- **Linear Programming (LP)**

### 🎯 Objective Function:
- **Maximize net revenue** from foreign and local guests while meeting the EBITA target.

### 🧮 Decision Variables:
- Room nights allocated per hotel for:
  - **Foreign guests**
  - **Local guests** (only in Mauritius)

### 🔐 Constraints:
#### For Foreign Guests:
- Minimum EBITA requirement of €38 million
- Maximum occupancy per season (based on 95% occupancy rate)
- Minimum nights required to generate revenue

#### For Local Guests:
- Room availability post foreign bookings
- 50% discount on Average Room Rate (ARR) applied to locals

---

## 📈 Assumptions

### 🔹 Explicit:
- Known demand and seasonal ARR
- Fixed number of rooms
- Fixed price points

### 🔹 Implicit:
- Operational uniformity across locations
- Stable market conditions
- Consistent demand elasticity

---

## 🧮 Solver Results

### 🔸 Objective Outcome:
- Achieved EBITA: **€39.1 million**
- Surplus over target: **€1.1 million**

### 🔸 Local Guest Revenue:
- Unsold room nights sold to locals at discount generated an additional **€200,947** in revenue.

### 🔸 Optimization Strategy:
- Solver allocated room nights across hotels while honoring occupancy and revenue constraints.
- Model respected max/min stay durations, pricing limits, and capacity availability.

---

## 💡 Recommendations

- **Tap into the local market**: Utilize unsold capacity by offering discounted rates to local guests.
- **Optimize pricing**: Adjust pricing seasonally to align with demand while maintaining revenue targets.
- **Use LP modeling routinely**: Implement such optimization models to guide seasonal booking strategies.

---

## 🧾 Summary & Conclusion

- The LP model proved effective in balancing **profitability and resource utilization**.
- Showed potential for increased revenue through **data-driven decision making**.
- The strategy supports both **business growth** and **community engagement** (via CSR).

---

## 📬 Contact

For more information or collaboration, reach out to:

- 📧 Pavani Narla – [GitHub](https://github.com/npavani10)
