# Portfolio

## Featured Projects

<div class="project-grid" markdown="1">

### Python

<div class="project-card" markdown="1">

#### Evaluation of Machine Learning and Deep Learning Algorithms for Deepfake Image Detection 

Developed and optimized robust deepfake detection models using <b>Support Vector Classifier</b> and <b>Multi-Layer Perceptron</b> and fine-tuning hyperparameters with <b>GridSearch cross-validation</b> to achieve an 82% accuracy rate on test data, demonstrating strong performance in identifying AI-generated content in real-world scenarios. Preprocessed a dataset of <b>2,000 real and AI-generated facial images</b>, applying grayscale conversion and eigenface principal component analysis to extract key visual features, such as texture irregularities, color distortions, and high-frequency noise that serve as indicators of AI-generated content.

<b>Libraries:</b> pandas, numpy, scikit-learn, matplotlib

[View Report](projects/deepfakes/DeepfakeDetectionFinalReport.pdf){:target="_blank"}  
[View Code](projects/deepfakes/DeepfakeDetectionCode.html){:target="_blank"}

</div>

<div class="project-card" markdown="1">

#### MobyGames Website Scraping and Collaborative-Filtering Recommendation System

Developed an interactive web application, MobySearch, to enable users to search and explore video game data from MobyGames. Crawled and pre-processed 1026 documents using <b>wget and BeautifulSoup</b>, then indexed the data using <b>python-terrier</b> without stemming or stopword removal. Implementing <b>HiemstraLM</b> for retrieval resulted in a mean average precision of 21%, R-precision of 10%, and reciprocal rank of 23%. Logged user searches provided weekly trending queries and personalized recommendations, enhancing the user experience with advanced search features and a popularity-based recommendation system.

Libraries: pandas, numpy, python-terrier, BeautifulSoup

[View Report](projects/gamerecs/MobyGamesReport.pdf)

</div>

### SQL and NoSQL

<div class="project-card" markdown="1">

#### Animal Shelter Relational and Physical Database Modeling

Developed a comprehensive <b>relational database system</b> for Furry Friends Shelter, a conceptual no-kill shelter for cats and dogs, to streamline the adoption process, enhance health monitoring, and improve overall animal care. Utilized relational database design principles to create a schema with <b>10 entities</b>. Implemented critical SQL queries for tracking adoptions, managing health records, and optimizing animal care, resulting in over <b>200 health logs, 100+ vaccinations, and 150+ medication administrations</b>.

[View Report](projects/animalshelter/FurryFriendsReport.pdf){:target="_blank"} 

</div>

<div class="project-card" markdown="1">

#### County Health Metrics MongoDB Database Design and Optimization (In Progress)

Designed and implemented a scalable MongoDB health metrics database, optimizing schema design with nested arrays and indexing strategies to enhance query performance, scalability, and data retrieval efficiency. Leveraged Python to <b>implement ETL processes, extracting relational data, transforming it into a non-relational format </b>, and loaded it into <b>MongoDB</b>,streamlining the migration of<b>~250k rows</b> of country health data and optimizing data integration workflows. Developed and optimized complex aggregation queries to extract insights, <b>improving query execution runtimes by 30%</b>.

</div>

### Software Architecture

<div class="project-card" markdown="1">

#### System Design for Smart Lock Data Platform

Designed the high-level software architecture for a <b>scalable, event-driven data platform</b> for smart home security devices, leveraging <b>AWS, Azure, and NoSQL databases</b> to define real-time data validation processes and facilitate system communication. Clarified ambiguity in system requirements by defining MVP features, identifying dependencies, and prioritizing features. Developed <b>REST API contracts</b> to ensure seamless data exchange between components, focusing on reliability and low-latency communication. Outlined comprehensive <b>logging, monitoring, and alerting schemas</b> to improve system observability and guide fault-tolerant design.

[View System Design Document](projects/smartlock/SmartLockSystemDesign.pdf){:target="_blank"}

</div>

### R

<div class="project-card" markdown="1">

#### Investment Portfolio Analysis

Wrote 10 page analysis of <b>5 Vanguard ETFs from the Wealthfront Classic Portfolio</b>. Utilized <b>R</b> to calculate returns, sample statistics and Value-at-Risk, created and visualized efficient portfolios for different expected return targets to determine optimal investment.

Libraries: tidyverse, zoo, xts, PerformanceAnalytics

[View Report](projects/investment/InvestmentFinalReport.pdf){:target="_blank"}

</div>

### React

<div class="project-card" markdown="1">

#### Misinformation Game Directory (In Progress)

Leading development of a research-based misinformation game directory to promote information and media literacy resources to educators and students. Collected metadata on <b>45 misinformation games</b>, and developed a search and filter system based on target age, number of players, genre, and format.

[View Website](https://opalsugar.github.io/misinfowb/){:target="_blank"}

</div>

</div>

---

## Other Projects

### Python

<div class="project-grid" markdown="1">

<div class="project-card" markdown="1">

#### Predictive Modeling of Spotify Streams based on Auditory Qualities 

[View Report](projects/spotify/SpotifyReport.pdf){:target="_blank"}  
[View Code](projects/spotify/SpotifyCode.pdf){:target="_blank"}

</div>

### R

<div class="project-card" markdown="1">

#### COVID-19 Health Statistics

Libraries: tidyverse, shiny

[View Shiny App](https://reneesingh.shinyapps.io/201_project/){:target="_blank"}

</div>

<div class="project-card" markdown="1">

#### Anime Statistics

[View Report](projects/animestats/AnimeFinalReport.html){:target="_blank"}

</div>

### React

<div class="project-card" markdown="1">

#### Flow: Productivity Website

[View Website](https://productivity-d4bde.web.app){:target="_blank"}

</div>

### Figma Design

<div class="project-card" markdown="1">

#### MyBookClub

Awards: 12th WINFO Hackathon Top 3 'Best Overall' Finalist

[View Prototype](https://www.figma.com/proto/LDN98uWUMUIRdaqkbLvtn6/Winfo-Hackathon?node-id=37-1470&starting-point-node-id=37%3A1470){:target="_blank"}

</div>

</div>

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 28px;
  margin-top: 30px;
}

.project-card {
  background: #f9fafb;              /* light gray so it stands out */
  padding: 28px;
  border-radius: 18px;
  border: 1px solid #e5e7eb;        /* subtle border */
  box-shadow: 0 12px 30px rgba(0,0,0,0.08);
  transition: all 0.25s ease;
}

.project-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 20px 40px rgba(0,0,0,0.12);
}

.project-card h3,
.project-card h4 {
  margin-top: 0;
}
</style>


