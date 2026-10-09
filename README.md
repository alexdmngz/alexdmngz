<picture>
  <img src="assets/header.svg" alt="Alejandro Domínguez — Artificial intelligence and applied mathematics" width="100%" />
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/alejandro-domínguez-lópez-206995416">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:alejandro.dominguez.business@gmail.com">Email</a> &nbsp;·&nbsp;
  <a href="#projects">Projects</a> &nbsp;·&nbsp;
  <a href="#toolkit">Toolkit</a>
</p>

I'm studying **Economics, Mathematics and Data Science at Universidad Complutense de Madrid**. My main interests are artificial intelligence, information retrieval and the mathematical ideas behind them.

I'm particularly interested in language models and how to evaluate the quality of their answers. My work includes a retrieval benchmark and Alego, a legal-tech project we're developing. I also enjoy financial algorithms, which I'm exploring through a portfolio optimizer.

## Projects

### [Retrieval Benchmark](https://github.com/alexdmngz/rag-mpe-benchmark)

**Finalist in the 2025/26 Modelización de Problemas de la Empresa contest.** Developed with Shadi Fedriani Abdallah.

We compared **BM25, dense and hybrid retrieval** against a Gemini baseline using 70 multiple-choice questions about the *REFRAG* research paper. The experiment evaluates answer accuracy, coverage of reference passages and the amount of context supplied to the model.

The pipeline cleans and chunks the paper, builds lexical and vector indexes, combines retrieval scores and reranks passages before generating answers. Dense retrieval uses **MPNet embeddings in ChromaDB**; a **MiniLM cross-encoder** reranks the candidates. The repository includes the question set, local BM25 evaluation, the full Gemini experiment and tests that run without model downloads or API calls. Full runs save individual prompts and responses alongside the aggregate results.

`Python` · `Gemini API` · `ChromaDB` · `Sentence Transformers` · `BM25` · `NumPy` · `Pandas` · `Matplotlib`

[Explore the code](https://github.com/alexdmngz/rag-mpe-benchmark) · [Read the report](https://github.com/alexdmngz/rag-mpe-benchmark/blob/main/docs/Report%20%26%20Results.pdf)

<sub>The report is written in Spanish.</sub>

### [Portfolio Optimizer](https://github.com/alexdmngz/portfolio-optimizer) · In development

I'm building a Python application for exploring how the allocation of capital changes a portfolio's risk and return. It takes a CSV or Excel export of your holdings, downloads historical prices and compares your current allocation with equal weights, the lowest sampled volatility and the highest sampled Sharpe ratio.

The calculation uses historical means and covariance, with **10,000 random allocations by default**, sampled from a Dirichlet distribution and evaluated with vectorized NumPy operations. Adjusted prices are used for returns; closing prices value the imported positions. Missing observations, currency consistency and invalid inputs are checked before the comparison.

There is a **Streamlit interface**, a command-line workflow and a reproducible offline demo. Runs can export the allocations, metrics, prices, settings and charts. The results describe the historical sample; the search does not yet include out-of-sample backtesting.

`Python` · `NumPy` · `Pandas` · `Matplotlib` · `yfinance` · `Streamlit` · `OpenPyXL`

<details>
<summary>See the optimizer's output</summary>

![Portfolio comparison showing sampled risk and return alongside allocation weights](assets/portfolio-demo.png)

*Output from the offline demo, using synthetic prices and holdings. These are illustrative results.*

</details>

[Explore the code](https://github.com/alexdmngz/portfolio-optimizer) · [Calculation notes](https://github.com/alexdmngz/portfolio-optimizer/blob/main/docs/methodology.md)

## Next projects

### Alego

A legal-tech project in development. I'm working on its algorithm for analysing and organising legal documents to support case preparation, with professional review built into the process.

## Toolkit

| Area | Tools and how I use them |
| --- | --- |
| Retrieval and model evaluation | **BM25, ChromaDB, Sentence Transformers and the Gemini API** for lexical search, embeddings, reranking and answer evaluation. |
| Numerical work | **Python, NumPy and Pandas** for vectorized calculations, experiments and data analysis. |
| Applications and financial data | **Streamlit** for the local interface, **Matplotlib** for charts, **yfinance** for price histories and **OpenPyXL** for Excel imports. |
| Development | **Git, GitHub Actions and unittest** for version control and automated checks. The benchmark and optimizer run their tests on Python 3.11 and 3.12. |

My broader toolkit also includes **R, SQL, SciPy and scikit-learn**. My mathematical interests centre on probability, statistical inference, linear algebra and numerical methods.

<p align="center">
  <a href="mailto:alejandro.dominguez.business@gmail.com">alejandro.dominguez.business@gmail.com</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/alejandro-domínguez-lópez-206995416">LinkedIn</a>
</p>
