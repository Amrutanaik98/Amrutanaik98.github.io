<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amruta Chandrakant Naik - Data Engineer & AI Enthusiast</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #f5f7fa 0%, #fef3f8 100%);
        }

        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 60px 20px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }

        .typing-text {
            font-size: 1.5em;
            font-weight: 300;
            opacity: 0.95;
        }

        .contact-links {
            margin-top: 20px;
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }

        .contact-links a {
            color: white;
            text-decoration: none;
            padding: 8px 16px;
            background: rgba(255, 255, 255, 0.2);
            border-radius: 20px;
            transition: all 0.3s ease;
        }

        .contact-links a:hover {
            background: rgba(255, 255, 255, 0.3);
            transform: translateY(-2px);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        section {
            background: white;
            margin-bottom: 30px;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.08);
        }

        h2 {
            color: #667eea;
            font-size: 2em;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 3px solid #e69acb;
        }

        .about-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-bottom: 20px;
        }

        .about-item {
            padding: 15px;
            background: #f8f9fa;
            border-left: 4px solid #667eea;
            border-radius: 5px;
        }

        .about-item strong {
            color: #667eea;
        }

        .project {
            margin-bottom: 30px;
            padding: 20px;
            background: #f8f9fa;
            border-radius: 8px;
            border-left: 4px solid #764ba2;
        }

        .project h3 {
            color: #764ba2;
            font-size: 1.3em;
            margin-bottom: 10px;
        }

        .project-tech {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin: 12px 0;
        }

        .tech-badge {
            background: #667eea;
            color: white;
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 0.85em;
        }

        .features, .architecture {
            margin: 12px 0;
            padding-left: 20px;
        }

        .features p, .architecture p {
            margin-bottom: 8px;
            color: #555;
        }

        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .tech-category {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            border-top: 3px solid #667eea;
        }

        .tech-category h4 {
            color: #667eea;
            margin-bottom: 12px;
            font-size: 1.1em;
        }

        .tech-list {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
        }

        .tech-item {
            background: white;
            padding: 6px 12px;
            border-radius: 4px;
            font-size: 0.9em;
            border: 1px solid #ddd;
        }

        .quote {
            text-align: center;
            font-size: 1.2em;
            font-style: italic;
            color: #764ba2;
            padding: 20px;
            margin: 20px 0;
            background: #f0e6ff;
            border-radius: 8px;
        }

        .collaborate-section {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            text-align: center;
            padding: 40px;
            border-radius: 10px;
            margin-top: 30px;
        }

        .collaborate-section h3 {
            font-size: 1.5em;
            margin-bottom: 20px;
        }

        .collaborate-section p {
            font-size: 1.1em;
            line-height: 1.8;
            margin-bottom: 10px;
        }

        .footer {
            text-align: center;
            padding: 40px 20px;
            color: #666;
            border-top: 1px solid #ddd;
        }

        .footer p {
            margin-bottom: 10px;
        }

        .github-stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }

        .stat-card {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            border: 2px solid #667eea;
        }

        .stat-card h4 {
            color: #667eea;
            margin-bottom: 10px;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }

            section {
                padding: 20px;
            }

            h2 {
                font-size: 1.5em;
            }

            .contact-links {
                flex-direction: column;
                align-items: center;
            }

            .contact-links a {
                width: 100%;
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>🌸 Amruta Chandrakant Naik</h1>
        <div class="typing-text">
            Data Engineer | Data Analyst | Data Scientist | Machine Learning Engineer
        </div>
        <div class="contact-links">
            <a href="mailto:amrutanaik1198@gmail.com">📧 Email</a>
            <a href="https://www.linkedin.com/in/amruta-naik-6a9091183" target="_blank">💼 LinkedIn</a>
            <a href="https://github.com/Amrutanaik98" target="_blank">🐙 GitHub</a>
        </div>
    </header>

    <div class="container">
        <!-- About Section -->
        <section>
            <h2>💡 About Me</h2>
            <div class="about-grid">
                <div class="about-item">
                    <strong>🎓 Education</strong><br>
                    M.S. in Information Systems @ Northeastern University
                </div>
                <div class="about-item">
                    <strong>💼 Experience</strong><br>
                    2.9 years as Data Engineer at Amdocs Development Center India
                </div>
                <div class="about-item">
                    <strong>🌐 Passion</strong><br>
                    Scalable data pipelines, cloud architectures & AI-driven solutions
                </div>
                <div class="about-item">
                    <strong>🚀 Currently Exploring</strong><br>
                    Generative AI, LLMs, RAG systems, Prompt Engineering, Vector Databases
                </div>
            </div>
            <div class="quote">
                "Turning raw data into meaningful impact through engineering and AI."
            </div>
        </section>

        <!-- Featured Projects Section -->
        <section>
            <h2>📂 Featured Projects</h2>

            <div class="project">
                <h3>🤖 RAG Document Intelligence System</h3>
                <div class="project-tech">
                    <span class="tech-badge">FastAPI</span>
                    <span class="tech-badge">Streamlit</span>
                    <span class="tech-badge">Pinecone</span>
                    <span class="tech-badge">LangChain</span>
                    <span class="tech-badge">HuggingFace</span>
                </div>
                <div class="features">
                    <p><strong>Features:</strong> Complete end-to-end Retrieval-Augmented Generation system with semantic search and AI-powered document Q&A. Integrates document scraping, intelligent chunking, vector embeddings, and context-aware LLM response generation. Production-ready API with interactive Streamlit dashboard for real-time querying.</p>
                </div>
            </div>

            <div class="project">
                <h3>🛫 Flight Data Analytics Pipeline</h3>
                <div class="project-tech">
                    <span class="tech-badge">Apache Airflow</span>
                    <span class="tech-badge">PySpark</span>
                    <span class="tech-badge">AWS</span>
                    <span class="tech-badge">Streamlit</span>
                    <span class="tech-badge">XGBoost</span>
                </div>
                <div class="features">
                    <p><strong>Features:</strong> Real-time data ingestion from Aviation Stack API, streaming with AWS Lambda & SQS, batch processing with AWS Glue, analytics engine with 20+ metrics, interactive Streamlit dashboard with 15+ visualizations, XGBoost & Random Forest ML models for delay prediction, REST API for predictions.</p>
                </div>
            </div>

            <div class="project">
                <h3>🍽️ Food Inspection – Dallas & Chicago</h3>
                <div class="project-tech">
                    <span class="tech-badge">Azure Data Factory</span>
                    <span class="tech-badge">Databricks</span>
                    <span class="tech-badge">Snowflake</span>
                    <span class="tech-badge">Power BI</span>
                    <span class="tech-badge">Medallion Architecture</span>
                </div>
                <div class="features">
                    <p><strong>Impact:</strong> Identified critical food safety trends across 2 major cities, processed 100K+ inspection records with 95% accuracy using medallion architecture (bronze/silver/gold layers) with interactive Power BI dashboards.</p>
                </div>
            </div>

            <div class="project">
                <h3>🎬 IMDb Business Intelligence</h3>
                <div class="project-tech">
                    <span class="tech-badge">Power BI</span>
                    <span class="tech-badge">Snowflake</span>
                    <span class="tech-badge">DAX</span>
                    <span class="tech-badge">Alteryx</span>
                </div>
                <div class="features">
                    <p><strong>Insights:</strong> Tracked 50K+ movies, identified top-performing genres by decade, analyzed career trajectories of 10K+ professionals with comprehensive BI dashboards and trend analysis.</p>
                </div>
            </div>

            <div class="project">
                <h3>🗽 NYPD Crime Data Analysis</h3>
                <div class="project-tech">
                    <span class="tech-badge">Azure Data Factory</span>
                    <span class="tech-badge">Snowflake</span>
                    <span class="tech-badge">Power BI</span>
                    <span class="tech-badge">Star Schema</span>
                </div>
                <div class="features">
                    <p><strong>Impact:</strong> Enabled crime analysis across 5 NYC boroughs for 5M+ records, identified seasonal trends, reduced query time by 70% with optimized schema and drill-through capabilities.</p>
                </div>
            </div>

            <div class="project">
                <h3>🌾 Climate Impact on Global Crop Yields</h3>
                <div class="project-tech">
                    <span class="tech-badge">Python</span>
                    <span class="tech-badge">Pandas</span>
                    <span class="tech-badge">Scikit-learn</span>
                    <span class="tech-badge">Matplotlib</span>
                </div>
                <div class="features">
                    <p><strong>Insights:</strong> Discovered strong correlations between climate variables and crop yields, built predictive models with R² > 0.85, identified climate risk zones for agricultural planning using 60 years of climate-agriculture data.</p>
                </div>
            </div>
        </section>

        <!-- Tech Stack Section -->
        <section>
            <h2>🛠️ Tech Stack & Expertise</h2>
            <div class="tech-grid">
                <div class="tech-category">
                    <h4>Languages</h4>
                    <div class="tech-list">
                        <span class="tech-item">Python</span>
                        <span class="tech-item">SQL</span>
                        <span class="tech-item">Java</span>
                        <span class="tech-item">R</span>
                        <span class="tech-item">PySpark</span>
                    </div>
                </div>

                <div class="tech-category">
                    <h4>Cloud Platforms</h4>
                    <div class="tech-list">
                        <span class="tech-item">AWS</span>
                        <span class="tech-item">Azure</span>
                        <span class="tech-item">EC2</span>
                        <span class="tech-item">S3</span>
                        <span class="tech-item">Lambda</span>
                    </div>
                </div>

                <div class="tech-category">
                    <h4>Big Data & Streaming</h4>
                    <div class="tech-list">
                        <span class="tech-item">Apache Spark</span>
                        <span class="tech-item">Databricks</span>
                        <span class="tech-item">Kafka</span>
                        <span class="tech-item">Delta Lake</span>
                    </div>
                </div>

                <div class="tech-category">
                    <h4>Data Warehousing</h4>
                    <div class="tech-list">
                        <span class="tech-item">Snowflake</span>
                        <span class="tech-item">PostgreSQL</span>
                        <span class="tech-item">MySQL</span>
                        <span class="tech-item">MongoDB</span>
                    </div>
                </div>

                <div class="tech-category">
                    <h4>Orchestration</h4>
                    <div class="tech-list">
                        <span class="tech-item">Apache Airflow</span>
                        <span class="tech-item">dbt</span>
                        <span class="tech-item">Azure Data Factory</span>
                    </div>
                </div>

                <div class="tech-category">
                    <h4>BI & Analytics</h4>
                    <div class="tech-list">
                        <span class="tech-item">Power BI</span>
                        <span class="tech-item">Tableau</span>
                        <span class="tech-item">Streamlit</span>
                        <span class="tech-item">Plotly</span>
                    </div>
                </div>

                <div class="tech-category">
                    <h4>LLMs & AI</h4>
                    <div class="tech-list">
                        <span class="tech-item">HuggingFace</span>
                        <span class="tech-item">OpenAI</span>
                        <span class="tech-item">LangChain</span>
                        <span class="tech-item">RAG</span>
                        <span class="tech-item">Transformers</span>
                    </div>
                </div>

                <div class="tech-category">
                    <h4>Vector Databases</h4>
                    <div class="tech-list">
                        <span class="tech-item">Pinecone</span>
                        <span class="tech-item">FAISS</span>
                        <span class="tech-item">Milvus</span>
                    </div>
                </div>

                <div class="tech-category">
                    <h4>ML & Data Science</h4>
                    <div class="tech-list">
                        <span class="tech-item">Scikit-learn</span>
                        <span class="tech-item">XGBoost</span>
                        <span class="tech-item">TensorFlow</span>
                        <span class="tech-item">PyTorch</span>
                    </div>
                </div>

                <div class="tech-category">
                    <h4>Backend & APIs</h4>
                    <div class="tech-list">
                        <span class="tech-item">FastAPI</span>
                        <span class="tech-item">Flask</span>
                        <span class="tech-item">Pydantic</span>
                    </div>
                </div>

                <div class="tech-category">
                    <h4>DevOps & Tools</h4>
                    <div class="tech-list">
                        <span class="tech-item">Docker</span>
                        <span class="tech-item">Kubernetes</span>
                        <span class="tech-item">Terraform</span>
                        <span class="tech-item">Git</span>
                        <span class="tech-item">Jenkins</span>
                    </div>
                </div>

                <div class="tech-category">
                    <h4>Data Processing</h4>
                    <div class="tech-list">
                        <span class="tech-item">Pandas</span>
                        <span class="tech-item">NumPy</span>
                        <span class="tech-item">Matplotlib</span>
                        <span class="tech-item">Seaborn</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Collaboration Section -->
        <section class="collaborate-section">
            <h3>✨ Areas I Love Collaborating On</h3>
            <p>⚙️ Cloud Data Pipelines (Airflow · EC2 · Databricks · Terraform · AWS/Azure)</p>
            <p>📊 Data Modeling & Visualization (Power BI · Tableau · Streamlit · DAX)</p>
            <p>☁️ Modern Data Engineering (Spark · Snowflake · Data Lakes · Streaming)</p>
            <p>🤖 Generative AI & RAG Systems (LLMs · Vector Databases · Prompt Engineering · Semantic Search)</p>
            <p style="margin-top: 20px; font-style: italic;">🌸 Empowering analytics and AI through collaboration, curiosity, and code.</p>
        </section>
    </div>

    <footer class="footer">
        <p>© 2024 Amruta Chandrakant Naik. All rights reserved.</p>
        <p>Portfolio created with passion for data engineering and AI innovation.</p>
    </footer>
</body>
</html>
