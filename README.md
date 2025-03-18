# TAC-Optimization-Pattern-Empirical-Discovery

# 📌 Overview

This repository documents an empirical observation in compiler optimization: temporary variables in Three-Address Code (TAC) are reduced by approximately 50% after optimization.

# 🔍 Key Findings:

•	TAC-generated temporary variables consistently reduce by around 50% post-optimization.
•	This pattern holds for arithmetic expressions but may vary for control flow and function calls.
•	The reduction occurs due to compiler optimizations like Common Subexpression Elimination (CSE), Constant Folding, and Dead Code Elimination.

# ⏳ Why This Matters?

This pattern has not been formally documented in compiler research. By publishing this, we establish early credit for the observation and encourage further study.

# 🚀 Next Steps

•	Collect more data from multiple compilers (LLVM, GCC, etc.).
•	Investigate why this pattern consistently occurs.
•	Publish findings in an academic paper or preprint.
# 📜 License & Attribution

This research is published by MD. RAIHAN KABIR NIBIR (22-49956-3) & SADIA AFRIN (22-49854-3). If you reference or build upon this work, please credit the original discovery.
