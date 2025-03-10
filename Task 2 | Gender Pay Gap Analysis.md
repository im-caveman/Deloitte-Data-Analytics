# Here is the background information on my task
After a worrisome number of internal complaints about gender inequality in terms of salary, Daikibo Industrial wants us to help them investigate.

The Forensic Tech team has build an algorithm to quantify `level of gender pay equality` for most job roles within the company, in all company locations. Now I have to finish the job

---
# Here is your task
We have processed all data on employee compensation and generated an Excel file (Equality Table.xlsx, available in the Resources) containing 3 columns:
1. `Factory`
2. `Job Role`
3. `Equality Score` (integer; ranging between -100 and +100; 0 is ideal)

### Your task
- Create a 4th column (`Equality Class`), classifying the equality score into 3 types:
    - Fair (+-10)
    - Unfair (<-10 AND >10)
    - Highly Discriminative (<-20 AND >20)

**Examples:**
- 6 -> Fair
- -9 -> Unfair
- -30 -> Highly Discriminative

---
### Required Data
[Task 2 Equality Table.xlsx](https://github.com/user-attachments/files/19160540/Task.2.Equality.Table.xlsx)
