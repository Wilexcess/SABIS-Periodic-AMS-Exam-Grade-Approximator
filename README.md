# SABIS Periodic/AMS/Exam Grade Approximator

**SABIS Periodic/AMS/Exam Grade Approximator** is a web tool to estimate your exam grade based on mistakes, retakes, and fixed questions. It uses the SABIS grading formula to provide an **approximate percentage** for any assessment scenario.

---

## General Formula

$$
\text{Grade} =
\Big(\frac{100}{Q} \times (Q - M)\Big)
+ \Big(\frac{100}{Q} \times \frac{76}{100} \times (W - TP)\Big)
+ \Big(\frac{100}{Q} \times \frac{60}{100} \times S\Big)
+ \sum_{i=1}^{TP} \left[
\Big(\frac{100}{Q} \times \frac{BCR_i}{PQ_i}\Big) +
\Big(\frac{100}{Q} \times \frac{76}{100} \times \frac{ACR_i}{PQ_i}\Big)
\right]
$$

**Where:**

- **Q** = total questions  
- **M** = mistakes  
- **W** = fixed written questions  
- **S** = fixed static questions  
- **TP** = total partial modules  
- **PQᵢ** = total questions in partial i  
- **BCRᵢ** = correct before retake in partial i  
- **ACRᵢ** = correct after retake in partial i  

---

## Features

- Approximate grades from **total mistakes, fixed questions, and partial retakes**  
- Add multiple partial modules dynamically  
- Instant calculation and color-coded results  
- Debug mode shows detailed calculation steps  
- Reset and adjust inputs anytime  

---

## Usage

1. Open `https://wilexcess.github.io/SABIS-Periodic-AMS-Exam-Grade-Approximator/` in a browser
2. Enter **Total Questions (Q)**, **Mistakes (M)**, **Written (W)**, and **Static (S)**  
3. Add **Partial Questions** (PQ, BCR, ACR) if applicable  
4. Click **Calculate** to see your approximate grade  
5. Use **Reset** to clear inputs  

---

## License

This project uses **[CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)**:  

- Others can **fork or share** the repository  
- **Cannot sell or reuse the formula**  
- **Cannot modify the formula**  
- Must provide **credit** to the original author  
