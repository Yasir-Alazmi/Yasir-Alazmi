<div align="center">

# Yasir Alazmi
### Artificial Intelligence Engineer
**Applied Machine Learning &bull; Retrieval-Augmented Generation &bull; Medical Computer Vision**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Yasir_Alazmi-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yasir-alazmi-471832436)
[![Email](https://img.shields.io/badge/Email-yasir.alazmi@outlook.sa-D14836?style=flat-square&logo=microsoftoutlook&logoColor=white)](mailto:yasir.alazmi@outlook.sa)
[![Degree](https://img.shields.io/badge/Degree-B.S._Artificial_Intelligence-107C41?style=flat-square&logo=academia&logoColor=white)](https://github.com/Yasir-Alazmi)
[![Location](https://img.shields.io/badge/Location-Saudi%20Arabia-107C41?style=flat-square&logo=google-maps&logoColor=white)](#)

<p align="center">
  B.S. in Artificial Intelligence from the University of Hail.<br>
  Focused on retrieval-augmented generation, clinical computer vision,<br>
  and leakage-safe model evaluation, with automated tests and CI on every public repository.
</p>

</div>

---

### Engineering Principles: Evidence-First & Zero-Friction

Every repository in this portfolio is an executable artifact adhering to strict software engineering rigor:
- **Zero-Friction Execution**: Ready-to-run inference scripts and sample clinical/domain data for immediate verification.
- **Automated Verification**: Deterministic test suites executed via GitHub Actions CI across all public repositories.
- **Mathematical Integrity**: Vectorized linear algebra from first principles and anti-leakage cross-validation protocols.

---

### Featured Engineering Systems

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Yasir-Alazmi/skin-lesion-classification">Skin Lesion Classification (HAM10000)</a></h4>
      <p>Seven-class dermoscopic classification comparing ConvNeXt, ViT-B/16 and EfficientNet-B3, evaluated with a lesion-grouped split so no lesion appears in both training and test data.</p>
      <ul>
        <li><b>Evaluation:</b> lesion-level bootstrap confidence intervals; an earlier, inflated result was retracted after finding image-level leakage</li>
        <li><b>Method:</b> documented sweep on Kaggle GPUs, validation-only model selection, negative results reported</li>
        <li><b>Demo:</b> Gradio app that runs the real trained models (research use only)</li>
      </ul>
      <p>
        <a href="https://github.com/Yasir-Alazmi/skin-lesion-classification">
          <img src="https://github.com/Yasir-Alazmi/skin-lesion-classification/actions/workflows/ci.yml/badge.svg" alt="CI Status" />
        </a>
        <br>
        <a href="https://github.com/Yasir-Alazmi/skin-lesion-classification"><b>Explore Repository &rarr;</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Yasir-Alazmi/enterprise-production-rag">Hybrid RAG Reference Implementation</a></h4>
      <p>Retrieval-augmented generation pipeline combining BM25 lexical search with dense embeddings and Reciprocal Rank Fusion. Evaluated on a small sample corpus; a reference implementation, not a production deployment.</p>
      <ul>
        <li><b>Retrieval:</b> sparse and dense search with cross-encoder re-ranking</li>
        <li><b>Safety:</b> PII redaction and prompt-injection guardrails</li>
        <li><b>Quality:</b> unit and evaluation tests run in CI</li>
      </ul>
      <p>
        <a href="https://github.com/Yasir-Alazmi/enterprise-production-rag">
          <img src="https://github.com/Yasir-Alazmi/enterprise-production-rag/actions/workflows/ci.yml/badge.svg" alt="CI Status" />
        </a>
        <br>
        <a href="https://github.com/Yasir-Alazmi/enterprise-production-rag"><b>Explore Repository &rarr;</b></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Yasir-Alazmi/Comparative-Analysis-of-Machine-Learning-Models-for-Healthcare-Diagnostics">Clinical ML Benchmark</a></h4>
      <p>Comparative study of supervised models on clinical datasets, including the CDC NHANES and Framingham cohorts, with strict train/test isolation.</p>
      <ul>
        <li><b>Statistics:</b> bootstrap confidence intervals, paired tests and calibration</li>
        <li><b>Reporting:</b> TRIPOD+AI checklist mapped in the repository</li>
        <li><b>Publication:</b> benchmark notebook on Kaggle</li>
      </ul>
      <p>
        <a href="https://github.com/Yasir-Alazmi/Comparative-Analysis-of-Machine-Learning-Models-for-Healthcare-Diagnostics">
          <img src="https://github.com/Yasir-Alazmi/Comparative-Analysis-of-Machine-Learning-Models-for-Healthcare-Diagnostics/actions/workflows/ci.yml/badge.svg" alt="CI Status" />
        </a>
        <a href="https://www.kaggle.com/code/yasirnalazmi/clinical-ai-benchmark-10-diagnostic-ml-models">
          <img src="https://img.shields.io/badge/Kaggle-Benchmark-20BEFF?style=flat-square&logo=kaggle&logoColor=white" alt="Kaggle Benchmark" />
        </a>
        <br>
        <a href="https://github.com/Yasir-Alazmi/Comparative-Analysis-of-Machine-Learning-Models-for-Healthcare-Diagnostics"><b>Explore Repository &rarr;</b></a> &bull; <a href="https://www.kaggle.com/code/yasirnalazmi/clinical-ai-benchmark-10-diagnostic-ml-models"><b>View Kaggle Benchmark &rarr;</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Yasir-Alazmi/neural-network-from-scratch">Neural Network from First Principles</a></h4>
      <p>Forward and backward propagation implemented in pure NumPy, without deep learning frameworks.</p>
      <ul>
        <li><b>Calculus:</b> chain-rule gradients for dense, ReLU and sigmoid layers</li>
        <li><b>Verification:</b> finite-difference gradient checks in the test suite (tolerance 10<sup>-4</sup>)</li>
        <li><b>Training:</b> learns a non-linear decision boundary on synthetic data</li>
      </ul>
      <p>
        <a href="https://github.com/Yasir-Alazmi/neural-network-from-scratch">
          <img src="https://github.com/Yasir-Alazmi/neural-network-from-scratch/actions/workflows/ci.yml/badge.svg" alt="CI Status" />
        </a>
        <br>
        <a href="https://github.com/Yasir-Alazmi/neural-network-from-scratch"><b>Explore Repository &rarr;</b></a>
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h4>Smaller Machine Learning Projects</h4>
      <ul>
        <li><b><a href="https://github.com/Yasir-Alazmi/music-recommender">Music Recommender</a>:</b> content-based recommendation from Spotify audio features, with a Streamlit interface</li>
        <li><b><a href="https://github.com/Yasir-Alazmi/fake-news-detector">Fake News Detector</a>:</b> TF-IDF text classifier with feature explainability (a learning project; its evaluation is being redone)</li>
      </ul>
    </td>
  </tr>
</table>

---

### Technical Competencies

<table>
  <tr>
    <td width="24%"><b>Generative AI & Agents</b></td>
    <td>LangChain, LangGraph, Multi-Agent Orchestration, Production RAG, Hybrid Search (BM25 + Dense), RRF Fusion, Guardrails, Evaluators</td>
  </tr>
  <tr>
    <td width="24%"><b>Deep Learning & CV</b></td>
    <td>PyTorch, Torchvision, Vision Transformers (ViT), EfficientNet, CNNs, OpenCV, timm, Scikit-Learn, NumPy, Pandas</td>
  </tr>
  <tr>
    <td width="24%"><b>Backend & Engineering</b></td>
    <td>Python, FastAPI, Celery, Redis, Docker, RESTful APIs, SQLite, Pydantic, Streamlit, Gradio</td>
  </tr>
  <tr>
    <td width="24%"><b>Engineering Rigor</b></td>
    <td>pytest, Automated CI/CD (GitHub Actions), TDD, Flake8 / Black / Ruff, Git Workflow, Zero-Trust RBAC</td>
  </tr>
</table>

---

### GitHub Engineering Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Yasir-Alazmi&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yasir-Alazmi&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="45%" />
</div>

---

<div align="center">
  <sub>Open to AI Engineering roles, Graduate Development Programs (GDPs), and applied AI initiatives across Saudi Arabia.</sub><br>
  <sub><b>Contact:</b> <a href="mailto:yasir.alazmi@outlook.sa">yasir.alazmi@outlook.sa</a> &bull; <a href="https://www.linkedin.com/in/yasir-alazmi-471832436">LinkedIn Profile</a></sub>
</div>
