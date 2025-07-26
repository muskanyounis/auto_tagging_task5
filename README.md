# 🏷️ Task 5: Auto Tagging Support Tickets using LLM (flan-t5-base)

This project uses a lightweight Hugging Face model (`flan-t5-base`) to automatically assign category tags to customer support tickets. The goal is to automate ticket triage using LLMs without any API keys.

---

## 📂 Input

- A CSV file named `support_tickets.csv` with one column:
ticket
My internet is not working.
I was overcharged this month.
I can't access my account.


---

## ⚙️ Tech Stack

- Python (Colab)
- HuggingFace Transformers
- `flan-t5-base` (local model)
- Matplotlib for charts
- WordCloud for tag visualization

---

## 🧠 Workflow

1. Load the CSV file.
2. Use prompt-based generation to classify each ticket.
3. Assign predicted tag (`billing`, `technical`, etc.).
4. Save results in `auto_tagged_tickets.csv`.
5. Visualize using:
   - Bar chart (tag count)
   - Pie chart (top 5 tags)
   - Box plot (ticket length vs tag)
   - Word cloud (for each tag)

---

## 📊 Output Visuals

- ✅ Tag Distribution Bar Chart
- ✅ Top 5 Tags Pie Chart
- ✅ Ticket Length Box Plot
- ✅ Word Clouds per Tag

