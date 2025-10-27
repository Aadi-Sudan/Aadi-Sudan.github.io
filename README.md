Hi, I'm Aadi! I’m passionate about data science, analysis, engineering, and AI/ML.  
Here, you’ll find my projects, experience, and ways to connect with me.

![My Photo](assets/img.jpeg)

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

- **Programming Languages:** Python, R, SQL, JavaScript, React.js, HTML, CSS, Bash, Markdown  
- **Frameworks/Libraries:** PyTorch, TensorFlow, Keras, Scikit-Learn, Pandas, NumPy, Plotly, Matplotlib, Tidyverse, PEFT (LoRA), Bitsandbytes, Transformers, FastAPI, Flask  
- **Technologies:** AWS S3, DynamoDB, EC2, SageMaker, Bedrock, Docker, Git, Tableau, PowerBI, Excel, Ollama, Agentic AI, RAG, Recommendation Algorithms, CNNs, Regression and Trees  
- **Coursework:** Data Structures & Algorithms, Linear Algebra, Applied Probability, Cryptography, Data Mining, Differential Equations, Applied ML, Discrete Math
- **Certifications:** AWS Certified Cloud Practicioner

---

## Experience

- **Research Intern – SCU HCI Lab** (Dec. 2024 – Present)  
  - Applied data cleaning and feature engineering techniques to analyze the distribution of gender and race across 40+ occupations each with 10k+ generated personas, reinforcing robust statistical modeling insights into generative AI bias
  - Created and implemented a data pipeline to batch-generate 400k+ personas from ChatGPT, Gemini, Mistral, and Deepseek, saving over 150 hours of manpower and generation efficiency and reducing data gathering costs by over 40%
  - Created analysis pipeline to automate data cleaning and produce 5+ graphs for each occupation, translating complex data sets into clear visualizations. Visualizations include logistic regression, double-bar charts, and over-under comparisons to official BLS data, as well as wordclouds for name repetition
  - Contributions can be found at project [repository](https://github.com/scuhci/genai-bias)
  - Published 29-page research paper to [ArXiv](https://arxiv.org/abs/2510.21011)

- **AI Engineer - Valverus** (Nov. 2024 – Present)
  - About the company: Valverus is a consulting startup in San Jose, CA that targets private equity firms with AI-informed insights into future investments
  - Engineered and Dockerized a RAG agent incorporating Ollama’s LLM and vector embeddings to generate actionable insights for external industry investments, creating 1200-character clusters for model training
  - Developed web scraper using DuckDuckGo Search library, Beautiful Soup, and ArXiv API to scrape 100+ articles and research papers weekly on external industries for providing RAG agent with textual data  

- **Workshop Coordinator – SCU AI Collaborate** (Oct. 2024 – Present)
  - Organized logistics for a hackathon in conjuncture with Adobe Express attended by 100+ participants and 10+ professional judges and officials from Adobe
  - Preparing interactive presentations for club workshops attended weekly by 50+ people
  - Headed fundraising, sponsorship efforts (15k), coordinated with the university board to support major events
  - Hosted AI Summit, SCU’s largest event, drawing over 700 student and industry attendees 
  - Leading guest speaker events consisting of lectures covering topics such as Agentic AI, AI in business, and more
  - Information on club events can be found at club [website](https://www.scuaiclub.com)

---

## Projects

- **CraveQuest (Ongoing)**
  - **Stack:** Flask, Flutter, Firebase Admin SDK, RESTful API, PyTorch, NumPy/Pandas, TorchVision
  - Designing a multi-platform Flutter app that allows users to swipe left or right on restaurants and recieve recommendations for where to dine
  - Implemented a scalable authentication and session management system using Flask, Google Firebase, and RESTful APIs, enabling secure user registration, login, and persistent session tracking across distributed clients
  - Optimized database schema and queries in Firestore by separating users and sessions collections with partitioned keys for user and session ID, reducing lookup latency by 40%
  - Built secure password handling and credential validation pipelines with real-time Firestore queries and tokenized session IDs, preventing duplicate sessions and improving system reliability
  - Incorporated Google Maps API to allow users to see their liked restaurants on a map relative to their current location
  - Designed a CNN to classify images of food uploaded by users and recommend restaurants that might serve those dishes. CNN achieved a validation accuracy of 0.89 using Adam optimizer and cosine similarity
  - Project [repository](https://github.com/mikewen8/Food_app)

- **Biomedical TinyLlama**
  - **Stack:** TinyLlama 1.1B, LoRA, PEFT, Bitsandbytes, PyTorch, Hugging Face, FastAPI, HTML/CSS/JS
  - Fine-tuned open-source TinyLlama 1.1B model with LoRA, PEFT, and Bitsandbytes on a biomedical instruction-response dataset for clinical text generation
  - Achieved ROUGE-Lsum score of 0.24 and BERT F1 score of 0.89, demonstrating accurate medical understanding and coherent, systemic text generation
  - Implemented FastAPI backend and HTML/CSS/JS frontend to utilize fine-tuned model as a chatbot, offering real-time responses to user queries
  - Project [repository](https://github.com/Aadi-Sudan/BiomedicalTinyllama)

- **Data Warehouse**
  - **Stack:** PostgreSQL
  - Designed and implemented a 3-tier data warehouse using PostgreSQL for end-to-end ETL and analytics
  - Built a star schema with fact and dimension tables to support efficient BI querying and reporting
  - Cleaned, transformed, and modeled raw CSV data to generate insights on sales, customers, and product trends
  - Project [repository](https://github.com/Aadi-Sudan/SQL-Data-Warehouse-Project)

- **Social Network**  
  - **Stack:** QT, C++, Linked Lists, Trees
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
