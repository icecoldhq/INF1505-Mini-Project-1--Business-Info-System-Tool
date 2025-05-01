
# 1. System Diagram

![System Flow Diagram](info_system_flow.png)


---

## 2. Step-by-Step Explanation

---

### a. **User Input**

The system starts by allowing the user to enter business-related data using an input device like a keyboard. This could include customer names, product details, sales amounts, or categories.

Before any data is entered, the business needs to have clear goals and understand what kind of data supports those goals. That’s why input is guided by organizational objectives — whether it's improving customer service, tracking sales, or reducing costs.

The system can accept input from **internal sources** (like employee reports or transaction logs) and **external sources** (like suppliers or customer feedback).

To maintain data integrity, a **validation check** is applied. This ensures data is not only clean but also secure, considering risks like cybercrime. Invalid or suspicious entries are flagged for review or rejected. This supports the goal of building a dependable data entry system.

---

### b. **Data Storage**

Once validated, the data is processed into usable **information** — not just raw values. The system temporarily holds this information in structures like **lists** or **dictionaries** (in memory), and optionally stores it in longer-term storage like **cloud services**, **NAS (Network-Attached Storage)**, or **databases**.

This prepares the information for categorization, making it easier to classify and retrieve.  
It directly supports **Goal 2** — structuring data for future applications and decisions.

---

### c. **Categorization**

Categorization is based on two dimensions: the **form** of the data and its **business purpose**.

- **Aggregated Data** might show total sales or average customer ratings — useful for managers.
- **Disaggregated Data** includes detailed, itemized entries — useful for transaction tracking.

The system uses logic to assign each entry to a type of **information system**:

| Type | Description | Use |
|------|-------------|-----|
| **TPS** | Transaction Processing System | For daily, repetitive operations like sales |
| **MIS** | Management Information System | For generating reports and insights |

By classifying data this way, users can see **which part of the business** the data supports — fulfilling **Goal 1**, the system overview.

Time orientation is also used (e.g., financial data from Q1) to help businesses make **period-based decisions**, like planning budgets or adjusting strategy.

---

### d. **Report Display**

After classification, the system generates simple output — such as printed summaries, tables, or visualizations — using an output device like a screen or printout.

This report shows:
- What data was entered
- How it was categorized
- What the totals or patterns are

These reports are not just technical outputs — they are tools for **decision-making**, especially under **Goal 1: Overview Tool**.

---

## 3. Why This Design?

This design was chosen to reflect **how businesses actually work** with information. Each part of the system represents a real-world step:

- Input → Validation → Processing → Categorization → Reporting

It maps directly onto **common business needs**, and helps the user understand **how data flows** through a business system.

- Easy-to-use interface mimics real-world data collection
- Validation logic reflects real concerns like data quality and cyber threats
- Categorization helps differentiate TPS vs MIS clearly
- Visual and written outputs support business understanding

This helps meet both project goals: **overview** and **categorization**.

---

## 4. Reflection (Optional)

### **What I learned:**

I now understand how **Information Systems** are designed not just to handle data, but to help **businesses make decisions**. I used Jupyter Notebooks, Git, and Python to build this system — with technical support from ChatGPT.

The code itself was assisted, but I developed a personal understanding of:
- Why validation matters
- How systems are structured
- What businesses do with categorized data

I also gained real experience working with tools like **Graphviz** and **Anaconda**, and learned to think like a systems analyst.

---

### **How this connects to Chapters 1–3:**

- **Chapter 1:** Helped me understand the *role* of information systems in achieving business goals.
- **Chapter 2:** Explained the *hardware/software components* I used to build the system.
- **Chapter 3:** Taught me about data types, validation, and how to turn data into actionable information — even though this was the hardest chapter to fully grasp.

I applied all three chapters in this project, even when I struggled — and made a real system based on them.

---

