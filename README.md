<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0F2FE,50:BAE6FD,100:7DD3FC&height=200&section=header&text=Arina%20Zhou&fontSize=56&fontColor=0C4A6E&fontAlignY=36&desc=Software%20%C2%B7%20Data%20Engineering%20%C2%B7%20ML%20Systems&descSize=18&descAlignY=58&animation=fadeIn" width="100%" alt="Arina Zhou" />
</p>

<p align="center">
  <a href="https://arinazhou.github.io"><img src="https://img.shields.io/badge/Portfolio-0284C7?style=flat-square&logo=googlechrome&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/arinazhou"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:arinaz2@illinois.edu"><img src="https://img.shields.io/badge/Email-0C4A6E?style=flat-square&logo=maildotru&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Open%20to-Summer%202027%20SWE%20%2F%20DE%20Internships-38BDF8?style=flat-square" />
</p>

<p align="center">
  I build systems that connect software to real-world data: acoustic sensors, satellite imagery, ecological fieldwork, developer tools.
</p>

<br>

### What's new

- 🧠 **Launched [Tracemind](https://arinazhou.github.io/tracemind/)**: paste any Python and watch it run line by line, with a Big-O estimate. 20 interview patterns, 210 problems, and a CS 225 data-structures reference.
- 🌃 **Published [Chicago Night Migration](https://github.com/arinazhou/chicago-night-migration)**: an exhaustive 92-model search found that **artificial light at night is the #1 driver** of which migrant birds a site hears (adj R² 0.53).
- 🛰️ **Started a night-light color study** of SDGSAT-1 imagery for Chicago lakefront conservation: warm sodium vs. cool white LED light.
- 🐦 **Shipped [FeatherLog](https://github.com/arinazhou/featherlog)**, a Spring Boot API that catches early weight loss in my budgie.
- 💻 **Redesigned my [portfolio](https://arinazhou.github.io)** with project figures and screenshots.

### About

```yaml
name:          Arina Zhou
education:     B.S. Information Sciences + Data Science, minor in CS @ UIUC (May 2028) · GPA 3.94
focus:         [software engineering, data engineering, ML systems]
exploring:     [GPU performance tuning, geospatial pipelines, in-browser Python (Pyodide)]
off_the_clock: [birding, volleyball, my budgie]
```

### Experience

| Role | Organization | When | Impact |
|:--|:--|:--|:--|
| **Software Engineer Intern** | Nighthawk · Van Doren Lab (open source) | May – Aug 2026 | GPU acceleration took inference from **4.8× → 25× real-time**; CPU/GPU eval workflows for reproducible Linux deploys |
| **Software & Data Engineering Intern** | Windy City Bird Lab & NRES · UIUC | Jun 2025 – Present | Geospatial pipelines over sensor data from **50+ monitoring sites**; auditable ingestion of **85K+ detections**, 30+ engineered features |
| **Research Software Developer** | iSchool · UIUC | Aug 2025 – May 2026 | Live audio → synchronized haptics via an event-driven React Native ↔ Swift pipeline |

### Featured

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://arinazhou.github.io/tracemind/"><img src="https://raw.githubusercontent.com/arinazhou/tracemind/main/docs/visualizer.gif" alt="Tracemind stepping through a bubble sort" /></a>
      <p><b><a href="https://github.com/arinazhou/tracemind">Tracemind</a></b> · React · TypeScript · Pyodide · FastAPI<br/>
      Runs your Python in a Web Worker under <code>sys.settrace</code>, turns each line into a visual step, and estimates Big-O with an AST analyzer that runs both in the browser and on the server. CI tests every lesson before it deploys.</p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/arinazhou/chicago-night-migration"><img src="https://raw.githubusercontent.com/arinazhou/chicago-night-migration/main/assets/model_search.gif" alt="Exhaustive model search ranked by AIC" /></a>
      <p><b><a href="https://github.com/arinazhou/chicago-night-migration">Chicago Night Migration</a></b> · GeoPandas · Rasterio · statsmodels · R<br/>
      Satellite night-light, land-cover and GIS layers → 30+ per-site features for 41 sites and 94 species, then an AIC-ranked search over 92 models. Includes a custom brightness-weighted light-direction feature.</p>
    </td>
  </tr>
</table>

### More work

| Project | Summary | Stack |
|:--|:--|:--|
| [**Nighthawk**](https://github.com/arinazhou/Nighthawk) | GPU-accelerated acoustic inference for nocturnal bird migration detection. **5.2× net speedup.** | ![](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![](https://img.shields.io/badge/-CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white) |
| [**FeatherLog**](https://github.com/arinazhou/featherlog) | REST API turning daily budgie weigh-ins into early health alerts (median-baseline trend analysis) and care reminders. | ![](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) |
| [**Chicago Night-Light Color**](https://github.com/arinazhou/chicago-lakefront-conservation) | *In progress.* SDGSAT-1 color night imagery; band ratios as a proxy for lamp type across Chicago. | ![](https://img.shields.io/badge/-Rasterio-2E7D32?style=flat-square) ![](https://img.shields.io/badge/-Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) |
| [**AI Engineering Assistant**](https://github.com/arinazhou/AI-Engineering-Assistant) | Repo-aware RAG that answers questions about a codebase with file citations. | ![](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white) ![](https://img.shields.io/badge/-FAISS-0467DF?style=flat-square) |
| [**H1BView**](https://github.com/arinazhou/H1BView) | Streamlit + Tableau dashboards over 2025 H-1B filings for finding sponsor-friendly roles and employers. | ![](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![](https://img.shields.io/badge/-Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white) |
| [**Illini Volleyball Analytics**](https://github.com/arinazhou/illini-volleyball-analytics) | Player evaluation and a Random Forest model for substitution strategy. | ![](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) |

### Toolbox

| | |
|:--|:--|
| **Languages** | ![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white) ![](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **Data & ML** | ![](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![](https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square) ![](https://img.shields.io/badge/Rasterio-2E7D32?style=flat-square) ![](https://img.shields.io/badge/statsmodels-4051B5?style=flat-square) ![](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![](https://img.shields.io/badge/FAISS-0467DF?style=flat-square) |
| **Web & Backend** | ![](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![](https://img.shields.io/badge/Pyodide-306998?style=flat-square) ![](https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white) |
| **Cloud & Infra** | ![](https://img.shields.io/badge/AWS%20Lambda%20·%20API%20Gateway%20·%20DynamoDB-232F3E?style=flat-square) ![](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white) |

### GitHub Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=arinazhou&hide_border=true&background=00000000&ring=38BDF8&fire=0284C7&currStreakLabel=0284C7&sideLabels=8B949E&currStreakNum=8B949E&sideNums=8B949E&dates=8B949E&stroke=30363D" alt="GitHub streak" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7DD3FC,50:BAE6FD,100:E0F2FE&height=100&section=footer" width="100%" />
</p>
