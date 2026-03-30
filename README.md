<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=230&section=header&text=Emergent%20Recursive%20Evolution&fontSize=38&fontAlignY=35&fontColor=ffffff&animation=fadeIn&desc=LaTeX%20as%20a%20Self-Evolving%20System&descAlignY=55&descSize=18" />
</p>

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=22&duration=3000&color=9D4EDD&center=true&vCenter=true&width=700&lines=Text+becomes+state;State+becomes+process;Process+becomes+evolution;Evolution+becomes+structure" />

<br><br>

<img src="https://img.shields.io/badge/Engine-LaTeX-blueviolet?style=for-the-badge">
<img src="https://img.shields.io/badge/System-expl3-purple?style=for-the-badge">
<img src="https://img.shields.io/badge/Concept-Generative%20Computation-black?style=for-the-badge">

<br><br>
# 🧬 Emergent Recursive Evolution System

*A self-evolving linguistic system implemented entirely in LaTeX.*
*Text enters as structure. It leaves as something… altered.*

---

</div>

## ✨ Overview

This project transforms LaTeX into a symbolic evolution engine, where sentences undergo mutation, selection, and recursive transformation.

Two core systems are included:
* **Evolution Matrix** → Parallel mutation + selection
* **Evolution Table** → Sequential staged evolution

---

### 🧪 Evolution Matrix

```latex
\EvolutionMatrix{
  The system processes data efficiently,
  The system adapts to dynamic data,
  Data flows through the system continuously
}
```

### Behavior
* Generates three variants per generation:
  * `A` → Semantic mutation
  * `B` → Structural reversal
  * `C` → Amplification
* Selects the longest (fittest) variant.
* Repeats the process for multiple generations.

---

## 🔄 Evolution Table

```latex
\EvolutionTable{The system processes data efficiently}
```

### Stages
| Generation | Transformation |
| :---: | :--- |
| **1** | Semantic mutation |
| **2** | Structural amplification |
| **3** | Chaotic reversal |

---

## 🧠 Conceptual Model

> **Mutation** ➔ **Selection** ➔ **Persistence** ➔ **Recursion** ➔ **Emergence**

This system behaves like a minimal genetic algorithm, a symbolic rewriting engine, and a deterministic evolution loop—all executed inside the TeX compiler.

### 🔁 Evolution Flow

```mermaid
graph TD
    A[Input Data] --> B(Mutation Layer)
    B --> C{Variant Set}
    C -->|Variant A| D[Semantic Shift]
    C -->|Variant B| E[Structural Reversal]
    C -->|Variant C| F[Amplification]
    D --> G[Selection Engine]
    E --> G
    F --> G
    G -->|Length Fitness Check| H[Next Generation]
    H -.->|Recursive Loop| B
```

---

## 📊 Example

**Input:**
> `The system processes data efficiently`

**Evolution:**
* **Gen 1** → `The construct processes signal efficiently`
* **Gen 2** → `THE construct processes signal efficiently [expanded]`
* **Gen 3** → `[CHAOS] ]dednapxe[ yltneiciffe langis sessecorp tcurtsnoc EHT`

---

## ⚙️ Requirements

* A standard LaTeX distribution (TeX Live / MiKTeX)
* **Packages:**
  * `expl3`
  * `xparse`
  * `longtable`
  * `xcolor`

---

## 🎯 Why This Exists

Because LaTeX is not just a typesetting system. It is:
1. A macro processor.
2. A transformation engine.
3. A deterministic universe where rules create behavior.

This project explores exactly how far that computational idea can stretch before it breaks.

---

## ⚠️ Limitations

* **Deterministic:** No true randomness (seed-based structure).
* **Fitness:** Simple fitness evaluation (length-based).
* **Optimization:** Not optimized for massive text inputs.
* **Debugging:** May feel like negotiating with an ancient compiler deity.

---

## 🔮 Future Work

- [ ] Implement probabilistic mutations.
- [ ] Develop a smarter, semantic-based fitness evaluation.
- [ ] Add graph visualization using `TikZ`.
- [ ] Explore LuaLaTeX hybrid execution for advanced logic.

---

<div align="center">

**👤 Author:** Nikola Topalov  
**📜 License:** MIT — *use freely, mutate responsibly.*

</div>
