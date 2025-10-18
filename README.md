# ⚙️ Static Program Analysis - Coursework Solutions

This repository contains my personal solutions for the coursework of the **DCC831 - Static Program Analysis** discipline. The original assignments and framework were provided by the course instructor.

> Original assignment repository: [https://github.com/pronesto/DCC888/tree/main](https://github.com/pronesto/DCC888/tree/main)

---

## 🚀 Implemented Analyses & Tasks

This project was a series of hands-on assignments designed to build a static analyzer from the ground up for a custom Intermediate Representation (IR).

* **📊 Control-Flow Graphs (CFGs)**
    * Solved three simple programming problems by manually designing their respective **Control-Flow Graphs** in the course's IR language.
    * Validated the solutions by running the developed code against a few test cases.

* **📄 Parsing**
    * Wrote a **parser** for the IR language, capable of transforming textual code into its corresponding CFG data structure.
    * The parser correctly handles both forward and backward branches to build an accurate graph representation.

* **🔍 Data-Flow Analyses**
    * Implemented the classic **liveness analysis** on the CFGs to determine which variables are "live" at each program point.

* **🔄 Worklist Algorithms**
    * Developed a toy **worklist solver** to enable the iterative computation of analyses like **reaching definitions**.

* **👑 Dominance**
    * Implemented **dominance analysis** for the CFGs using the Data-Flow equations method.

* **Φ Phi-Functions**
    * Added support for **phi-functions** to the CFGs, enabling the correct interpretation of programs that use this SSA-form construct.

* **👉 Alias Analysis**
    * Implemented an **Andersen's-style points-to analysis** to determine which memory locations pointers could refer to.

* **✅ Type Checking**
    * Built a simple **type checker** to validate correct type usage within the IR language.

* **✨ Sparse Constant Propagation**
    * Implemented a **sparse constant propagation** analysis, a powerful optimization technique, for the course's IR.
