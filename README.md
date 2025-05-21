# 🇮🇳 Indian Election Result SQL Project

This project presents a comprehensive **SQL-based analysis of Indian General Election Results**. It focuses on extracting insights such as the number of seats won by political alliances (NDA, I.N.D.I.A., Others), performance of individual parties, voting patterns (EVM vs Postal), and constituency-level details.

---

## 📦 Database Structure

The project uses the following tables:

| Table Name                | Key Columns Used                              |
|---------------------------|-----------------------------------------------|
| `States`                 | State_Id, State                                |
| `Orders`                 | Order_ID, Order_Date, Order_Time               |
| `Constituencywise_Results` | Constituency_ID, Constituency_Name, Party_ID, Parliament_Constituency |
| `Partywise_Results`      | Party_ID, Party, Won, Party_Alliance           |
| `Constituencywise_Details` | Candidate, EVM_Votes, Postal_Votes, Total_Votes, Constituency_ID |

---

## 🗃️ Entity Relationship Diagram (ERD)

Here’s the ER diagram illustrating the structure of the election dataset used in this project:

![Election ER Diagram](https://github.com/user-attachments/assets/6210de14-a7da-4e00-9268-2fb3b363cd78)


---

## 🎯 Key Business Questions Answered

### 🟢 Basic Overview

1. **Total number of parliamentary seats in India**  
2. **Seats available per state for elections**

### 🟠 Party Performance

3. **Total seats won by NDA alliance**  
4. **Seats won by each NDA party**  
5. **Total seats won by I.N.D.I.A. alliance**  
6. **Seats won by each I.N.D.I.A. party**

### 🔵 Alliance and Vote Analysis

7. **Classifying parties as NDA, I.N.D.I.A., or Other (via `ALTER` + `UPDATE`)**  
8. **Which alliance won the most seats across all states?**  
9. **Distribution of EVM vs Postal votes in a specific constituency (e.g., Mathura)**  
10. **Top 10 candidates with the highest EVM votes in their constituencies**

---

## 🧠 SQL Concepts Used

- `JOIN` across multiple tables
- `GROUP BY`, `ORDER BY`
- `CASE WHEN` for conditional aggregation
- `DISTINCT`, `COUNT()`, `SUM()`, `MAX()`
- `ALTER TABLE` and `UPDATE` for adding classification
- Subqueries for top candidate analysis
- Filtering using `WHERE` for state or constituency-specific insights

---

## 🔗 GitHub Repository Link

https://github.com/Analyst-Rajat333/Indian-Election-Result-SQL-Project

---

## 👨‍💻 Author

**Rajat Saxena**  
📧 **Email**: [rajatsaxena950@gmail.com](mailto:rajatsaxena950@gmail.com)  
🔗 **GitHub**: [Analyst-Rajat333](https://github.com/Analyst-Rajat333)
