# Information Retrieval and Web Search – MSc Course (Zanjan University)

This repository hosts the homework templates and evaluation framework for the **Information Retrieval and Web Search** MSc course at **Zanjan University**.  
Students will use this repository to complete assignments, evaluate their solutions, and submit reports.

---

## 📂 Repository Structure

- **Homework Templates**  
  Each homework assignment has a predefined template in this repository. Students should check out the template and implement their solution.

- **Evaluation with BEIR**  
  All homeworks are evaluated using the [BEIR library](https://github.com/beir-cellar/beir).  
  - The **best evaluation results** for each homework must be saved in a file named:  
    ```
    irws_{homework_id}_best_value.csv
    ```
    Example: `irws_hw1_best_value.csv`

- **Reports**  
  For each homework, students must prepare a **PDF report** containing analysis of the achieved results.  
  - The report must be named:  
    ```
    irws_{homework_id}_report.pdf
    ```
    Example: `irws_hw1_report.pdf`

- **Code**
  All code implementation placed in a Jupyter Notebook file named:
  ```
  IRWS_{homework_id}.ipynb
  ```
---

## ⚠️ Important Instructions

Because of **automatic AI-based evaluation**, all students must:

- Create their repository with the **exact name**:  **irws**
- Place the following files in the repository for each homework:  
  - `irws_{homework_id}_best_value.csv`  
  - `irws_{homework_id}_report.pdf`
  - `IRWS_{homework_id}.ipynb`
  

⚠️ **If any student does not follow these instructions, their exercises will not be reviewed.**

**Please, to develop any code, maximum utilize using any LLMs to achieve rapid and complete development.**

---

## 📝 Homework Guidelines

1. **Implement your solution** in the provided template.
2. **Run evaluation** using the BEIR library.
3. **Save best results** in `{homework_id}_best.csv`.
4. **Write a report** (`{homework_id}_report.pdf`) including:
 - Description of your approach
 - Analysis of achieved results
 - Discussion of strengths and weaknesses
 - Possible improvements
5. **Submit your code** in `irws_{homework_id}.ipynb`.

---

## 📘 First Homework

- **Topic:** Persian Information Retrieval  
- **Dataset:** [Hamshahri Corpus](http://ece.ut.ac.ir/dbrg/hamshahri/)  
- **Model:** TF-IDF  

Students are required to:
- Implement a TF-IDF based retrieval system for Persian documents.
- Evaluate performance using BEIR.
- Save the best results in `hw1_best.csv`.
- Submit a detailed report as `hw1_report.pdf`.
- Provide code in `irws_hw1.ipynb`.

---

## ✅ Submission Checklist

- [ ] Homework solution implemented in template  
- [ ] Evaluation performed with BEIR  
- [ ] `{homework_id}_best.csv` file created  
- [ ] `{homework_id}_report.pdf` uploaded with analysis  
- [ ] `irws_{homework_id}.ipynb` notebook included  

---

## 📌 Notes

- Follow naming conventions strictly.  
- Reports must include **clear analysis** of results, not just raw numbers.  
- Late submissions may not be accepted.  

---

## 📚 References

- [BEIR: Benchmarking IR](https://github.com/beir-cellar/beir)  
- [Hamshahri Corpus](http://ece.ut.ac.ir/dbrg/hamshahri/)  
- Manning, Raghavan, and Schütze – *Introduction to Information Retrieval*  

---

### 🚀 Good luck, and happy searching!

