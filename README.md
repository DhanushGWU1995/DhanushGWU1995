# Dhanush Mathivanan

**Data science graduate student · AWS certified cloud and Data Professional · Grounded LLM systems**

Arlington, VA

[Portfolio](https://dhanushgwu1995.github.io/dhanush-mathivanan-portfolio/) · [LinkedIn](https://www.linkedin.com/in/dhanush-mathivanan-a65202120/) · [Tech blog](https://techwithdhanush.blogspot.com/) · [Email](mailto:dhanush.mathivanan@gwu.edu)

<p>
  <img alt="AWS Solutions Architect Associate" src="https://img.shields.io/badge/AWS-SAA--C03-232F3E?logo=amazonwebservices&logoColor=white" />
  <img alt="AWS Developer Associate" src="https://img.shields.io/badge/AWS-DVA--C02-FF9900?logo=amazonwebservices&logoColor=white" />
  <img alt="George Washington University" src="https://img.shields.io/badge/GWU-M.S.%20Data%20Science-033C5A" />
</p>

Data Science M.S. student at The George Washington University, focused on data and cloud engineering, machine learning, deep learning, NLP, generative AI, and large-scale data systems. AWS certified engineer with **9.7+ years** building distributed microservices, event-driven architectures, and serverless data platforms for global enterprises, along with full-stack applications in Python, TypeScript, Node.js, Javascript, SQL, AWS, Angular, Github, etc.

---

## Grounded LLM work

**[Torque Diagnostics](https://github.com/DhanushGWU1995/torque-diagnostics)** is a technician assistant for ABB drive manuals, and it is still in progress. It answers from indexed pages and withholds a procedure the manual does not support.

- PDF library lands in S3, then gets chunked by equipment family into Parquet
- Hybrid retrieval combines BM25 with `BAAI/bge-base-en-v1.5` sentence embeddings
- `Qwen/Qwen2.5-7B-Instruct` drafts from the top retrieved pages
- `MoritzLaurer/DeBERTa-v3-base-mnli-fever-anli` checks whether a manual line entails each claim
- If no claim survives, the answer is withheld and the citation is never invented

The repository is private while the manual library stays off the public internet.

Other language-model work: [ECRIS](https://github.com/DhanushGWU1995/6202-machine-learning-project) (DistilBERT + T5 over CFPB complaints) and a [parts assistant](https://github.com/DhanushGWU1995/sample-chat-bot) with a swappable DeepSeek or OpenAI backend.

---

## Experience

| When | Role | Where |
| --- | --- | --- |
| Aug 2026 – Present | Technical AWS Support Assistant | The George Washington University (DC, US) |
| Jun 2026 – Aug 2026 | Data Science Intern | Probability Solutions LLC (VA, US) |
| Mar 2024 – Aug 2025 | Technical Project Specialist / Lead Engineer | Bosch · Client MHP Porsche (Audi AG, Germany) |
| Sep 2021 – Mar 2024 | Custom Software Engineering Team Lead | Accenture · Client Educational Testing Service (NJ, US) |
| Nov 2020 – Sep 2021 | Lead Engineer, Full Stack Cloud Engineering | HCL · Client Roche (Switzerland) |
| Aug 2018 – Nov 2020 | Software Engineer, Full Stack | Object Frontier · Client IFF (NY, US) |
| Oct 2016 – Aug 2018 | Software Engineer, Full Stack | V2Soft · Client Fiat Chrysler Automotives (MI, US)|

**Recent work**

- Supporting GWU voice, collaboration, and physical security systems, including Splunk alert triage and the migration of 1,000+ users from Cisco CUCM to Zoom Phone
- Compared search-tree implementations across CRUD operations for data-intensive database workloads
- Shipped the Porsche workforce-planning platform on AWS serverless: CDKTF, Lambda, API Gateway, DynamoDB, and Cognito
- Cut ETS exam-result processing time by 50% with Lambda, DynamoDB, SNS/SQS, and CloudFormation
- Cut Roche diagnostic reporting time by 40% with Node.js, Express, Angular, and MySQL

---

## Technical focus

**LLMs and NLP** — retrieval-augmented generation, Qwen2.5, BGE embeddings, BM25, DeBERTa entailment, Hugging Face, DistilBERT, T5

**Machine learning** — TensorFlow, Scikit-Learn, Pandas, Polars, Matplotlib, Seaborn

**Cloud** — AWS Lambda, CDK, S3, API Gateway, CloudFormation, Cognito, SQS/SNS, Docker, Terraform, Jenkins

**Application stack** — Python, TypeScript, JavaScript, SQL, Node.js, Express, Angular, FastAPI, Streamlit, Kafka, Redis

**Data stores** — DynamoDB, MySQL, MongoDB, SQLite, DuckDB

---

## Selected projects

| Project | What it does |
| --- | --- |
| [Torque Diagnostics](https://github.com/DhanushGWU1995/torque-diagnostics) | Grounded technician assistant over ABB manuals. Still in progress. Private repo. |
| [AI Course Creator](https://course-creator-626594108279.us-central1.run.app/) | Multi-agent system on Google Cloud Run. Researcher, fact-checker, and writer agents turn a topic into a course. |
| [ECRIS](https://github.com/DhanushGWU1995/6202-machine-learning-project) | Complaint intelligence on U.S. consumer-finance data. [Live Space](https://huggingface.co/spaces/DhanushGWU1995/ECRIS) |
| [Health status predictor](https://github.com/DhanushGWU1995/6103-data-mining-project) | CatBoost model on CDC BRFSS responses, with an Angular and Flask app |
| [Heart disease predictor](https://github.com/DhanushGWU1995/6101-mid-term-project) | CDC survey model. [Scoring app](https://dhanushgwu1995.github.io/6101-mid-term-project/predict) |
| [US unemployment vs job postings](https://github.com/DhanushGWU1995/6401-data-visualization-project) | Tableau dashboard comparing U.S. unemployment with job postings across five economic sectors. |
| [Role Matrix](https://github.com/DhanushGWU1995/role-matrix) | Resume screening that scores skills and projects, not keywords |
| [PartSelect assistant](https://github.com/DhanushGWU1995/sample-chat-bot) | Appliance-parts chat with DeepSeek or OpenAI |

---

## Education and recognition

**M.S. Data Science**, The George Washington University · Aug 2025 – May 2027  
Coursework: Big Data Analytics, Cloud Computing, Machine Learning, Deep Learning, NLP, Data Warehousing

- Phi Delta Gamma Fellowship, George Washington University (2026)
- Global Leaders Fellowship, George Washington University (2025)
- AWS Certified Solutions Architect – Associate, SAA-C03 (2024)
- AWS Certified Developer – Associate, DVA-C02 (2023)
- Client Value Creation Award and Best People Award, Accenture (2022)

---

## GitHub stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=DhanushGWU1995&show_icons=true&theme=default" alt="Dhanush's GitHub stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DhanushGWU1995&layout=compact&theme=default" alt="Top Languages" height="165" />
</p>

<p align="left">
  <img src="https://streak-stats.demolab.com?user=DhanushGWU1995&theme=default" alt="GitHub Streak" height="165" />
</p>
