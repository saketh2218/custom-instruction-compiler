# custom-instruction-compiler
# Custom Instruction Compiler Simulation

This project demonstrates how to design and implement a custom instruction `fcomplex` for the equation:

```
D = (A * B) / (C * D) + E
```

## 🔧 Instruction Details

- **Custom Instruction**: `fcomplex rd, rs1, rs2, rs3, rs4, rs5`
- **Operation**: `rd = (rs1 * rs2) / (rs3 * rs4) + rs5`

## 📂 Files Included

- `main.py` — Main controller script.
- `1_lexical_analysis.py` — Input parser.
- `2_syntax_analysis.py` — Placeholder for syntax check.
- `3_semantic_analysis.py` — Ensures all variables are present and valid.
- `4_intermediate_code.py` — The custom `fcomplex` function.
- `5_code_generation.py` — Output logic.
- `input.txt` — Sample input file.
- `screenshot.png` — Output image placeholder.
- `README.md` — This file.

## ▶️ How to Run

1. Make sure you have **Python 3.x** installed.
2. Modify `input.txt` as needed. Example content:

```
A = 4
B = 5
C = 2
D = 2
E = 3
```

3. Run the following:

```bash
python main.py input.txt output.txt
```

4. See your result in `output.txt`.

## 📷 Output Screenshot

![output](screenshot.png)

---

