# Contributing to The Academy of Open Science (AOS)

Thank you for your interest in contributing! AOS is an open-source, community-driven platform. We welcome contributions from students, teachers, self-taught learners, and developers.

By contributing, you help make scientific knowledge free, intuitive, and universally accessible.

---

## 📑 How You Can Contribute

Contributions generally fall into two categories:
1. **Educational Content:** Writing derivations, explanations, or papers in Markdown (`.md`).
2. **Interactive Tools & Utilities:** Building open-source tools (Python scripts, web widgets, graph generators) to aid student learning.

---

## 📝 Writing Educational Content (`.md`)

All educational content must be written in Markdown with embedded LaTeX for mathematical and scientific equations.

### 1. LaTeX Standard
* Use inline math with single dollar signs: `$E = mc^2$`
* Use block math for major derivations and standalone equations:
  $$F = G \frac{m_1 m_2}{r^2}$$

### 2. Article Structure
Every topic should focus on **first principles** rather than just stating formulas. Structure your files using this general outline:

```text
# Topic Title

## 1. Conceptual Intuition
Explain what the concept is and why it exists in simple, clear language.

## 2. First-Principles Derivation
Show the step-by-step mathematical proof or physical derivation.

$$ \text{Step 1: } F = ma $$
$$ \text{Step 2: } a = \frac{dv}{dt} $$

## 3. Practical Example
Provide a worked-out problem showing how to apply the principle.

## 4. Open Resources & References
Link to lecture videos, papers, or open textbooks (e.g., Khan Academy, Professor Dave, MIT OpenCourseWare).
```

---

## 💻 Building Student Tools & Scripts (Python / Web)

We encourage sub-projects and tools that help students visualize, calculate, or interact with scientific concepts (e.g., plot generators, orbit simulators, physics calculators).

### 1. Python Tools
* **Code Style:** Follow PEP 8 guidelines. Write clear, readable code with descriptive variable names.
* **Dependencies:** Keep external dependencies minimal. Standard libraries are preferred. If using packages like `matplotlib`, `numpy`, or `manim`, list them in a `requirements.txt` file within the tool's sub-directory.
* **Execution:** Ensure scripts can be run directly from the command line with clear input prompts or command-line arguments.

Example header for Python tools:
```python
"""
AOS Tool: Two-Body Gravitational Orbit Plotter
Description: Plots two-body orbital paths using NumPy and Matplotlib.
Usage: python orbit_plotter.py --mass1 5.97e24 --mass2 7.35e22
"""
```

### 2. Web Widgets (HTML/CSS/JS)
* Use vanilla HTML, CSS, and JavaScript wherever possible so tools run natively in any browser without build steps or frameworks.
* Keep styling clean, responsive, and distraction-free.

---

## 🔀 Pull Request Process

1. **Fork the Repository:** Create your own copy of `mdakibislam/academy-of-open-science`.
2. **Create a Branch:** Name your branch clearly according to your contribution:
   * `git checkout -b content/derivation-keplers-laws`
   * `git checkout -b tool/python-orbit-plotter`
3. **Commit Your Changes:** Keep commit messages clear and descriptive:
   * `git commit -m "Add derivation for Kepler's Third Law"`
4. **Open a Pull Request:** Submit your PR against the `main` branch with a brief summary of what you added or fixed.

---

## 📜 Code of Conduct & Licensing

* **Respect & Collaboration:** Keep peer reviews constructive and supportive.
* **Originality:** Ensure all written content and code are your own work or properly attributed under open-source licenses.
* **Licensing:** By contributing content, you agree that your writings will be licensed under **CC BY-SA 4.0** and any code/tools will be licensed under the **MIT License**.