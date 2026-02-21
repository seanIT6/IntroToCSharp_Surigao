# Prelim Lab 01 - Codac Logistics Delivery & Fuel Auditor

**Student:** Sean Howard Surigao
**Course:** Introduction to C# Programming
**Instructor:** Justin Louise Neypes

---

## Description

A console-based C# application developed for Codac Logistics that tracks daily fuel expenses and delivery performance for a single vehicle over a 5-day work week. The program collects driver profile information, validates distance input, calculates fuel efficiency, and generates a full financial audit report.

---

## Features

- Driver profile input (name and weekly fuel budget)
- Distance input validation using a `while` loop (1.0 – 5000.0 km)
- 5-day fuel expense tracking using a 1D `decimal` array
- Fuel efficiency rating calculation (High / Standard / Low Efficiency)
- Weekly budget comparison with a `bool` status flag
- Formatted audit report output using string interpolation

---

## C# Concepts Demonstrated

| Concept | Usage |
|---|---|
| `string` | Driver's full name |
| `decimal` | Fuel budget and daily expenses |
| `double` | Total distance traveled |
| `bool` | Budget status check |
| `while` loop | Distance input validation |
| `for` loop | Daily expense entry and report display |
| `if / else if / else` | Efficiency rating logic |
| 1D Array (`decimal[]`) | Storing 5 days of fuel expenses |
| String Interpolation | Formatted console output |

---

## How to Run

1. Make sure you have the [.NET SDK](https://dotnet.microsoft.com/download) installed
2. Clone this repository:
   ```
   git clone https://github.com/SeanHoward/IntroToCSharp_Surigao.git
   ```
3. Navigate into the project folder:
   ```
   cd IntroToCSharp_Surigao
   ```
4. Run the program:
   ```
   dotnet run
   ```

---

## Sample Output

```
========================================
  CODAC LOGISTICS - Fuel & Delivery Audit
========================================

Enter Driver's Full Name: Maria Santos
Enter Weekly Fuel Budget (PHP): 5000
Enter Total Distance Traveled this week (km, 1.0 - 5000.0): 850

--- Daily Fuel Expense Entry ---
Enter fuel cost for Day 1 (PHP): 820
Enter fuel cost for Day 2 (PHP): 750
Enter fuel cost for Day 3 (PHP): 910
Enter fuel cost for Day 4 (PHP): 680
Enter fuel cost for Day 5 (PHP): 795

========================================
       CODAC LOGISTICS - AUDIT REPORT
========================================
  Driver Name       : Maria Santos
  Total Distance    : 850.00 km
  Weekly Budget     : PHP 5000.00
----------------------------------------
  5-Day Fuel Expense Breakdown:
    Day 1           : PHP 820.00
    Day 2           : PHP 750.00
    Day 3           : PHP 910.00
    Day 4           : PHP 680.00
    Day 5           : PHP 795.00
----------------------------------------
  Total Fuel Spent  : PHP 3955.00
  Avg Daily Expense : PHP 791.00
  Efficiency Ratio  : 0.21 km/PHP
  Efficiency Rating : Low Efficiency / Maintenance Required
----------------------------------------
  Budget Status     : UNDER BUDGET (Saved PHP 1045.00)
  Under Budget?     : True
========================================
  End of Audit Report
========================================
```

---

## Author

**Sean Howard Surigao**
Introduction to C# Programming — Prelim Activity 01
