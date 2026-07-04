Hi, I'm Aadi! I’m passionate about computer science, data science, and AI/ML.  
Here, you’ll find my projects, experience, and ways to connect with me.

<img src="assets/img.jpeg" width="400" alt="Aadi Sudan">

---

## Fast Travel
- [Education](#education)
- [Skills](#skills)
- [Experience](#experience)
- [Projects](#projects)
- [Contact Info](#connect-with-me)

---

## Education

- **Santa Clara University** *(2022 – 2026)*  
  - Bachelor's of Science in Computer Science
  - Minor in Mathematics

---

## Skills

- **Languages:** Python, R, SQL, PostgreSQL, MySQL, C++, Java, JavaScript, HTML, CSS, Bash
- **ML/Data:** PyTorch, TensorFlow, HuggingFace Transformers, PEFT/LoRA, Bitsandbytes, scikit-learn, NumPy, Pandas, Matplotlib, Seaborn, OpenCV, spaCy, LangChain
- **Tools/Infrastructure:** AWS, Docker, Kubernetes, Git, FastAPI, Flask, Firebase, PineconeDB, DynamoDB, CI/CD, REST APIs, Linux, Locust, pytest
- **Certifications:** AWS Certified Cloud Practitioner, [Google AI Essentials](https://coursera.org/share/cf48e32919ecc68bea4c86b18d27abdc)

---

## Experience

- **FairwAI — Software & ML Engineer Intern** (New York, NY (Remote) | March 2026 – Present)  
  - Designed and deployed an end-to-end NLP pipeline in Python to ingest, parse, and featurize 1,000+ applicant resumes, reducing processing costs by 80% and cutting manual preparation time by 60% through spaCy and regex-based feature extraction. Architected an async resume parsing system achieving 90%+ code coverage via pytest and a 45% reduction in pipeline runtime
  - Created an AI evaluation framework using permutation-based candidate ranking and RAG-based counterfactual testing to detect hallucinations and quantify bias via flip-rate scoring, supporting compliance with NYC Local Law 144 and EU AI Act guidelines
  - Built an on-device computer vision pipeline in Swift — YOLOv8n (Core ML / Apple Neural Engine) → ByteTrack multi-object tracker → Protobuf event bus — achieving 70–90 fps inference at 720p on iPhone 16 Pro, confirmed via Xcode Instruments profiling
  - Ported a ByteTrack-style tracker from Python to Swift with exact threshold and association logic parity between iPhone and CPU paths, validated through synthetic test cases covering steady tracking, occlusion recovery, buffer expiry, and multi-person identity stability under close-pass conditions
  - Designed a Protobuf event schema (PersonEvent/FrameEvent) consumed by two downstream teams, with forward-compatible enum typing and resolution-independent normalized coordinates; extended a shared Python evaluation harness to benchmark the Core ML model at mAP@0.5 of 0.366 on a 500-image indoor test set
  - Instrumented a 15-minute on-device thermal and throughput probe, logging sustained FPS and iOS thermal state transitions to CSV; confirmed 76–77 fps average with no throttling on iPhone 16 Pro, establishing a performance baseline for mitigation work

- **SCU HCI Lab — Data Engineer & Undergraduate Researcher** (Santa Clara, CA | Dec. 2024 – Jun. 2026)  
  - Engineered large-scale batch pipelines generating 400,000+ synthetic personas across 4 commercial LLMs (ChatGPT, Gemini, Mistral, DeepSeek), eliminating 150+ hours of manual analysis and enabling the largest known academic audit of demographic bias across 41 occupations
  - Designed statistical analysis frameworks in Python and R to quantify representation gaps and surface statistically significant bias signals across protected demographic attributes, producing publication-ready visualizations
  - Developed [an interactive data visualization website](https://gen-ai-dashboard-7ec2.onrender.com/index.html) in HTML, CSS, and JavaScript to communicate study methodology and findings to a non-technical public audience
  - Co-authored a peer-reviewed publication presented at Stanford's TETHICON Conference: [Generating the Modal Worker: A Cross-Model Audit of Race and Gender in LLM-Generated Personas Across 41 Occupations](https://dl.acm.org/doi/10.1145/3805689.3812221?__cf_chl_f_tk=vfGYrvqPVtTfxZfn.XrQpJaKupyl6Qs6DLwZzMYhE40-1783137887-1.0.1.1-_hfo.vU.paU0NpYOlDlMg2kyLnqqbigo.XI31zXYQq8).
  - Contributions can be found at project [repository](https://github.com/scuhci/genai-bias)

- **Valverus — AI Engineer Intern** (Santa Clara, CA | Nov. 2024 – Aug. 2025)
  - About the company: Valverus is a consulting startup that targets private equity firms with AI-informed insights into future investments
  - Architected a production-grade RAG agent powered by a vector database (PineconeDB) to deliver real-time intelligence on emerging technologies and investment opportunities across 10+ industry verticals
  - Built automated data ingestion pipelines in Python using LangChain to collect, chunk, embed, and index 100+ industry and research articles weekly, maintaining a continuously fresh knowledge base
  - Optimized embedding and retrieval configurations through systematic ablation testing, improving retrieval precision by 28% over baseline TF-IDF approaches
  - Refactored core retrieval and indexing modules, improving query throughput by 35% and reducing average API response latency from 1.8s to under 600ms
  - Containerized the full application stack with Docker and configured Kubernetes manifests for orchestration, reducing environment setup time by 70%


- **SCU AI Collaborate — Workshop Coordinator** (Santa Clara, CA | Oct. 2024 – Dec. 2025)
  - Coordinated with Adobe and NVIDIA to organize 3+ hackathons drawing 100+ participants each
  - Designed weekly workshops and seminars featuring guest speakers from Amazon, Apple, NVIDIA, etc. and attended by 50+ recurring members
  - Organized and facilitated the AI Summit — SCU's largest student-run event — drawing 700+ student and industry attendees
  - Led fundraising and sponsorship efforts securing $15K to support club programming
  - Club website: [scuaiclub.com](https://www.scuaiclub.com)

---

## Projects

- **CraveQuest**
  - **Stack:** Flask, Flutter, Firebase Admin SDK, RESTful API, PyTorch, NumPy/Pandas, TorchVision
  - A full-stack restaurant recommendation platform where users swipe on restaurants and receive personalized dining recommendations powered by computer vision.
    - Designed RESTful APIs and Firestore database schemas with partitioned keys, reducing lookup latency by 40%
    - Implemented secure authentication and session management using Flask, Firebase, and tokenized session IDs
    - Trained a CNN food classification model achieving 89% validation accuracy using Adam optimizer and cosine similarity, powering personalized restaurant recommendations
    - Integrated Google Maps API to surface liked restaurants relative to the user's current location

- **Biomedical Diagnosis Chatbot**
  - **Stack:** TinyLlama 1.1B, LoRA, PEFT, Bitsandbytes, PyTorch, HuggingFace, FastAPI, HTML/CSS/JS
  - Fine-tuned TinyLlama 1.1B on a biomedical instruction-response dataset for clinical text generation, then built a full inference and benchmarking pipeline to optimize and profile performance across hardware targets.
    - Fine-tuned with LoRA adapters and 4-bit quantization (PEFT + Bitsandbytes), achieving **0.874 mean BERTScore F1** and **ROUGE-L 0.228** with a 3x reduction in model size
    - Built FastAPI backend with real-time streaming endpoints and an interactive HTML/CSS/JS frontend for clinical Q&A deployment
    - Engineered a multi-target inference benchmarking pipeline profiling CPU vs. GPU execution across 5 biomedical prompts × 30 timed runs, achieving a **12.2x latency reduction** on NVIDIA T4 GPU (16,609ms → 1,364ms mean inference time)
    - Used PyTorch Profiler to identify matrix multiplication via Cutlass WMMA tensor cores as the dominant compute bottleneck at 64.9% of total CUDA time, enabling targeted optimization analysis
    - Applied torch.compile() (TorchDynamo/TorchInductor) to analyze compiler optimization behavior on autoregressive generation workloads
    - Project [repository](https://github.com/Aadi-Sudan/BiomedicalTinyllama)

- **SCU Basketball Analysis**
  - **Stack:** Python, OpenCV, Roboflow, Object Detection, Homography
  - Led a 4-person team to build a computer vision pipeline for analyzing SCU basketball game footage.
    - Trained a custom object detection model on 2,000+ annotated frames using Roboflow, tracking player and ball movement throughout game footage
    - Implemented homography transformations to map broadcast camera angles onto a standardized court coordinate system, enabling spatial analysis of player positioning across 10+ full game recordings
    - Generated heatmaps and possession-based movement statistics from tracked coordinates, delivering a prototype analysis tool to coaching staff

- **Data Warehouse**
  - **Stack:** PostgreSQL, SQL, ETL, Star Schema, BI Analytics
  - Designed and implemented a 3-tier data warehouse using PostgreSQL for end-to-end ETL and analytics
    - Built a star schema with fact and dimension tables to support efficient BI querying and reporting
    - Cleaned, transformed, and modeled raw CSV data to generate insights on sales, customers, and product trends
    - Project [repository](https://github.com/Aadi-Sudan/SQL-Data-Warehouse-Project)

- **Social Network**  
  - **Stack:** C++, Qt Creator, Graph Algorithms, OOP
  - Designed a holistic social networking platform in C++ with an object-oriented architecture revolving around User, Post, and Network classes, enabling user login, profile viewing, friend connections, post sharing, and friend suggestions
    - Developed an enhanced privacy system with three levels (public, semi-public, private), enforcing access rules for profile and post visibility based on user relationships (direct friend, friend-of-friend, or open)
    - Implemented file persistence with robust read/write functionality to users.txt and posts.txt, ensuring that privacy levels, friendships, and posts are preserved between sessions
    - Created an interactive QT interface with dynamic tables and labels for friends, posts, and suggested friends; integrated a dropdown menu and button workflow for updating privacy settings
    - Designed and optimized a friend recommendation algorithm using graph traversal and scoring, improving engagement by suggesting relevant connections
    - Project [repository](https://github.com/Aadi-Sudan/social-network)

- **New York House Price Predictor**  
  - **Stack:** Jupyter, Python, Data Analysis, Feature Engineering, Regression
  - Implemented polynomial features to build a linear regression-based price predictor for housing in New York based on a dataset of over 50,000 entries
    - Users can input values for square footage, room count, and borough of the city to recieve an estimated price for the estate
    - Utilized linear regression, data cleaning, and feature engineering to achieve a precision value of 87%
    - Project [repository](https://github.com/Aadi-Sudan/New-York-Housing)

- **Job Requirements Analysis**
  - **Stack: Jupyter, Python, Data Analysis, Data Mining, Web Scraping, ReGex, Data Cleaning, Association Rule Mining**
  - Created a web scraper to collect up to 6k+ job postings and requirements from Simplify's New Grad Roles Github repository, focusing on data and software-related roles
    - Utilized ReGex and text extraction to clean data and identify most frequently appearing skills, years of experience, and degree requirements within the posting
    - Conducted association rule mining to identify the relationship between various requirements
    - Wrote a report to highlight findings
    - Created for CS 185 (Data Mining) Final Project
    - Project [repository](https://github.com/Aadi-Sudan/Job-Requirements-Analysis)

- **Diabetes Predictions**
  - **Stack: Jupyter, Python, Machine Learning, Grid Search, Neural Net, Random Forest, Logistic Regression, LinearSVC, Decision Tree, K-NN, Gaussian Naive-Bayes**
  - Implemented a variety of predictive models trained on a UCI dataset to analyze probability of type-2 diabetes manifesting in a user given certain biomedical information
    - Conducted grid search to optimize hyperparameters for each individual model and compared optimal models utilizing accuracy and k-fold cross-validation metrics. The best-performing model was a neural net with accuracy of 84.6%
    - Wrote a report to highlight findings
    - Created for CS 184 (Applied Machine Learning) Final Project
    - Project [repository](https://github.com/Aadi-Sudan/Diabetes-Prediction)

- **Student Performance Analysis**
  - **Stack: Jupyter, Python, Data Analysis, Data Visualization, Data Cleaning, Linear Regression**
  - Conducted statistical analysis on a Kaggle dataset highlighting student performance given metrics such as financial stability, parental involvement, and more
    - Cleaned data and visualized relationship between different features to highlight the most relevant to predicting final grades
    - Optimized a linear regression model to predict final grades given most relevant features. The model achieved testing accuracy of 99.1% with root mean squared error of 0.101
    - Wrote a report to highlight findings
    - Created for CS 183 (Data Science) Final Project
    - Project [repository](https://github.com/Aadi-Sudan/Student-Performance-Analysis)

- **Reddit Report**  
  - **Stack:** RStudio, RMarkdown, Data Analysis
  - Analyzed a labeled dataset of roughly 50,000 different Reddit comments in order to gauge widespread response to sarcastic vs non-sarcastic comments
    - Wrote a data report on findings, including graphs and in-depth statistical analyses to back up assertations
    - Project [repository](https://github.com/Aadi-Sudan/Reddit-Report)

- **Dungeon Crawler**  
  - **Stack:** C++
  - Designed an object-oriented text-based dungeon crawler themed after the popular Dungeons and Dragons game
    - Game can support up to 4 players. Players are tasked with resource management in order to use a built-in shop mechanic to progress the dungeon
    - Dynamic events are randomly generated for the player as they progress through the adventure, and information on players, bosses, the map, and random events are each defined within in-depth classes
    - Project [repository](https://github.com/Aadi-Sudan/Dungeon-Crawler)

- **Tech Support**  
  - **Stack:** Python, discord.py, OpenAI API, pdf2image
  - Implemented a Python-based Discord chatbot integrating OpenAI's API to use the GPT-3 model to provide conversational AI responses directly in chat
    - Utilized discord.py, OpenAI API, and image-processing libraries (PIL, pdf2image) to enable advanced file handling and natural language queries
    - Delivered an interactive bot that extended Discord’s native search with semantic AI-powered retrieval, improving usability for community-driven knowledge sharing
    - Project [repository](https://github.com/Aadi-Sudan/Tech-Support)

---

## Connect with Me

- [LinkedIn](https://www.linkedin.com/in/aadi-sudan-66b183204)  
- [GitHub](https://github.com/Aadi-Sudan)  
- Email: aadisudan123@gmail.com  

---

[Back to Top](#fast-travel)
