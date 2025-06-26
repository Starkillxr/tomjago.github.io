---
layout: page
filename: index.md
title: Home
---

# **CV**
## **Technical Skills**:
- **Agile Methodologies, Risk Assessment**:  Project Management
* **Android Studio, Java, XHTML** : Mobile Application Development
+ **Digital Twins, AI Application Areas** : Applied Artificial Intelligence
- **HTML, CSS, JavaScript** : Web Development
* **LaTeX** – Master of Artificial Intelligence
+ **MATLAB & Robotics Equations** : Advanced Intelligence Robotics
- **OpenCV** : Artificial Vision and Deep Learning
* **Optimisation, Metaheuristics, Evolutionary Algorithms** : Computational Intelligence
+ **Pandas** : Masters Project, Advanced Machine Learning
- **PyRadiomics, SHAP** : Improving Interpretability and Explainability of Radiomics Deep Learning Models for Accurate Brain Tumour Assessment
+ **PyTorch** : Machine Learning & AI, Advanced Machine Learning
* **Python** : Machine Learning & AI, Advanced Machine Learning, Computational Intelligence, Improving Interpretability and Explainability of Radiomics Deep Learning Models for Accurate Brain Tumour Assessment, Artificial Vision, and Deep Learning
- **R & R Markdown** : Big Data
+ **Scikit Learn** : Advanced Machine Learning
* **SQL, PHP, WAMP Server** : Database Design and Development
- **TensorFlow** : Machine Learning & AI
+ **Ubuntu & Cluster Computing** : High-Performance Computing
* **XAI** : Applied Artificial Intelligence, Masters Project

## Education

### **University of Plymouth (2022-2023)**
- **Master of Artificial Intelligence**
    - Key Modules Include: Advanced Intelligent Robotics, Advanced Machine Learning, Artificial Vision and Deep Learning, Big Data, Computational Intelligence, and Improving Interpretability and Explainability of Radiomics Deep Learning Models for Accurate Brain Tumour Assessment

### **City College Plymouth (2016-2021)**
- **BSc Applied Computer Science (2:1 Upper Division)**
    - Key Modules Include: High Performance Computing, Machine Learning and AI, Project Management & Mobile Application Development, Team Project,
- **BTEC Diploma in IT (Distinction, Distinction)**
    - Key Modules Include: Web Development, Project Management & Database Design and Development

### **Plymouth Tuition Service (ACE Schools) (2015)**
- **GCSES**: Four in Mathematics, Double Science and English 


## **Soft Skills**

#### **Effective Communication, Teamwork, Leadership, and Collaboration**
Collaborated on multiple occasions with peers throughout my education, communicating effectively with other team members to discuss problems, solutions, arranging meetings, and determining next steps. Additionally, I often took the lead in explaining tasks at hand if there was a problem, demonstrating leadership and facilitating collaboration within the team.
#### **Problem Solving and Research Abilities**
Demonstrated strong problem-solving skills through independent research and coursework projects, such as developing a Rubik's cube solver using AI during my dissertation. I conducted thorough research to understand complex concepts and explored innovative solutions to overcome challenges.
#### **Project Planning and Time Management**
Successfully managed multiple projects simultaneously, prioritizing tasks and meeting tight deadlines under pressure. Utilized project management methodologies, such as Agile Scrum, to effectively plan and organize workloads, ensuring timely completion of deliverables.
#### **Adaptability, Resilience, Initiative, and Proactivity**
Adapted quickly to new environments and technologies, demonstrating resilience in the face of challenges. Thrived in dynamic and fast-paced settings, remaining flexible and open-minded to change while maintaining a positive attitude. Took initiative to lead team projects and propose innovative solutions, driving positive outcomes and contributing to team success.
#### **Analytical Thinking and Attention to Detail**
Employed analytical thinking to analyse complex problems and evaluate potential solutions critically. Paid meticulous attention to detail in tasks such as database design and development, ensuring accuracy and efficiency in data management processes.

<hr>
<h1 style="font-size:50px"> Blog Posts </h1>
<ul>
    {% for post in site.posts %}
        <header>
            <h3 style ="margin:0px; padding:0px;">{{ post.title }}</h3>
            <p style="color:#808080; margin:0px; padding:0px"><time datetime="{{ post.date | date: '%Y-%m-%d %H:%M' }}">{{ post.date | date: "%B %-d, %Y %I:%M %p"}}</time></p>
        </header>
        <hr>
        <p>{{post.excerpt}}</p>
    {% endfor %}
</ul>
