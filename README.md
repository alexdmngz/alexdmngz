<h1 align="center">Alejandro Domínguez</h1>

<p align="center">
  <strong>Economics · Mathematics · Data Science</strong><br>
  Universidad Complutense de Madrid
</p>

<p align="center">
  <a href="#projects">Projects</a> ·
  <a href="#toolkit">Toolkit</a> ·
  <a href="https://www.linkedin.com/in/alejandro-domínguez-lópez">LinkedIn</a> ·
  <a href="mailto:alejandro.dominguez.business@gmail.com">Email</a>
</p>

---

## About

I'm studying **Economics, Mathematics and Data Science at Universidad Complutense de Madrid**. My interests are increasingly centred on AI, particularly **language models, information retrieval and the mathematics behind them**.

My recent work includes a retrieval benchmark and **Alego**, a legal-tech project we're developing. I also enjoy financial algorithms, which I'm exploring through a portfolio optimizer that's still in development.

## Projects

### [Retrieval Benchmark](https://github.com/alexdmngz/rag-mpe-benchmark)

*Information retrieval · Language model evaluation*

> **Finalist — 2025/26 Modelización de Problemas de la Empresa contest**  
> Developed with Shadi Fedriani Abdallah.

We compared **BM25, dense and hybrid retrieval** with a Gemini baseline on **70 multiple-choice questions** about the *REFRAG* research paper.

- **Evaluation:** answer accuracy, coverage of reference passages and the amount of context supplied to the model.
- **Pipeline:** MPNet embeddings in ChromaDB, with a MiniLM cross-encoder for reranking.
- **Included:** the question set, a local BM25 evaluation and the full Gemini experiment, with individual prompts and responses saved alongside the results.

**[Explore the code](https://github.com/alexdmngz/rag-mpe-benchmark)** · [Read the report (Spanish)](https://github.com/alexdmngz/rag-mpe-benchmark/blob/main/docs/Report%20%26%20Results.pdf)

---

### [Portfolio Optimizer](https://github.com/alexdmngz/portfolio-optimizer)

*Financial algorithms · In development*

I'm building a Python application to explore how portfolio allocation affects risk and return. It compares current holdings with equal weights, the lowest sampled volatility and the highest sampled Sharpe ratio.

- **Inputs:** CSV or Excel holdings, with historical prices fetched through yfinance.
- **Analysis:** 10,000 random allocations by default, evaluated with vectorised NumPy.
- **Workflow:** a Streamlit interface, command-line tools and an offline demo, with exports for allocations, metrics and charts.

> The comparison uses historical data from the same sample. Out-of-sample backtesting is not yet implemented.

<details>
<summary><strong>Preview the offline demo</strong></summary>

![Portfolio comparison showing sampled risk and return alongside allocation weights](assets/portfolio-demo.png)

*Illustrative output using synthetic prices and holdings.*

</details>

**[Explore the code](https://github.com/alexdmngz/portfolio-optimizer)** · [Read the methodology](https://github.com/alexdmngz/portfolio-optimizer/blob/main/docs/methodology.md)

---

### Alego

*Legal tech · In development*

We're developing a legal-tech project to help analyse and organise legal documents for case preparation. I'm working on the underlying algorithm, with professional review built into the process.

## Toolkit

| Focus | Tools |
| :--- | :--- |
| **Languages** | Python · R · SQL |
| **Data & numerical computing** | NumPy · Pandas · SciPy · scikit-learn |
| **Retrieval & evaluation** | BM25 · ChromaDB · Sentence Transformers · Gemini API |
| **Apps, charts & imports** | Streamlit · Matplotlib · yfinance · OpenPyXL |
| **Development & testing** | Git · GitHub Actions · unittest |

My mathematical interests centre on **probability, statistical inference, linear algebra and numerical methods**.

## Let's connect

I'm currently looking for **internship opportunities in AI and data science**.

[Email me](mailto:alejandro.dominguez.business@gmail.com) · [Find me on LinkedIn](https://www.linkedin.com/in/alejandro-domínguez-lópez)
