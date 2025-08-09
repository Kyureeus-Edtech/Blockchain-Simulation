# Blockchain Simulatoion —  Practical Assignment

## 📌 Objective
Learn how blockchain works by interacting with a live simulator.  
Understand how **data changes**, **hashes**, **mining**, and **multiple nodes** affect chain validity.

---

## 🛠 Steps to Complete
1.get into Blockchain Simulation Lab
2. **Add ≥3 blocks**.
3. Edit a non-genesis block → watch the chain turn **Invalid**.
4. **Mine** the edited block (and subsequent invalid blocks) until the chain is **Valid**.
5. Add **≥2 more nodes** (total **≥3 nodes**) and confirm all show **Valid** status.
6. Use **Share → PNG/PDF** to export:
- `A_invalid_<rollno>.png/pdf` — before mining (invalid chain)
- `B_valid_<rollno>.png/pdf` — after mining (valid chain)
- `C_nodes_<rollno>.png/pdf` — ≥3 nodes, all valid
7. Create a `REFLECTION.md` file (150–250 words) answering:
- What changed in the hash when you edited data?
- Why did the chain become invalid, and how did mining fix it?
- Role of nonce during mining (include final nonce(s)).
- How nodes maintain the same chain (consensus).
8. Commit & push all files to your GitHub Classroom repo.

---

## 📂 Submission Checklist

A_invalid_<rollno>.png/pdf
B_valid_<rollno>.png/pdf
C_nodes_<rollno>.png/pdf
REFLECTION.md


**Commit message format:**
Blockchain Simulator — 3 screenshots + reflection — <Your Name> (<Roll No>)


---

## ✅ Grading Rubric (100 pts)
| Criteria | Points |
|----------|--------|
| A Invalid screenshot (overlay + invalid state) | 20 |
| B Valid screenshot (overlay + valid chain) | 20 |
| C Nodes screenshot (≥3 nodes valid) | 20 |
| Reflection quality (accuracy + clarity + nonce/time notes) | 30 |
| Repo hygiene (filenames + commit format) | 10 |
| **Total** | **100** |

---

## ⚠️ Notes
- Use the **Share** button for exports — it expands fields and adds your details automatically.
- Be patient while mining; record nonce/time for reflection.
- Editing earlier blocks will require sequential re-mining to restore validity.
