# Tawan Teopipithaporn
https://www.linkedin.com/in/tawan-teopipithaporn-13389915a/ | San Bruno, CA 94066 | (404) 547-3182 | tortawan@hotmail.com

## Professional Summary
Highly motivated Machine Learning Scientist with an MSCS from Georgia Institute of Technology (Machine Learning specialization, GPA 3.9). Possesses a significant portfolio of self-directed research and complex software development projects, demonstrating advanced capabilities in designing and implementing novel AI algorithms (including Estimation of Distribution Algorithms, custom heuristics for pathfinding, and agent-based systems), developing applications in Python and C++, and conducting research in areas like swarm intelligence and probabilistic modeling. Eager to apply these research-driven skills and a recent focus on Large Language Models (evidenced by 'Generative AI with Large Language Models' certification) to a Research Scientist role in the Bay Area, contributing to cutting-edge LLM advancements.

## Education
**Georgia Institute of Technology, Atlanta, GA**
Master of Science in Computer Science (MSCS) | Specializations: Machine Learning
*Graduated: Dec 2019*
*GPA: 3.9*

**Southern Polytechnic State University, Marietta, GA**
Master of Science in Computer Science (MSCS)
*Graduated: Dec 2005*

## Research & Project Experience

**Developer: C++ Agent-Based Simulation of Ant Colony Behavior** | Personal Project
*(January 2024 – March 2025)*
* Developed a high-performance, multi-agent simulation in C++ to model complex ant colony dynamics, focusing on emergent object clustering and interaction behaviors.
* Designed and implemented `Ant` agents with individual memory (simulating limited knowledge), probabilistic movement patterns, object manipulation capabilities (pickup/drop), and interaction cooldowns.
* Created a `Ground` environment class managing spatial distribution of objects (Food, Waste, Eggs) and mediating ant interactions based on memory similarity and configurable thresholds.
* Leveraged OpenMP to parallelize simulation experiments, significantly reducing computation time for parameter sweeps and multiple runs.
* Integrated OpenCV for dynamic visualization of the simulation state and generation of video outputs (interfacing with FFmpeg capabilities for video encoding).
* Engineered a sophisticated interaction mechanism where ants adjust behavior based on memory similarity with other ants, leading to emergent self-organization and clustering of objects.
* Implemented robust data logging of simulation metrics (e.g., average cluster size, interaction counts) to CSV files for subsequent analysis.
* Managed Windows-specific thread affinity for optimizing performance on multi-core processors.
* **Key Technologies & Concepts:** C++, Standard Template Library (STL), OpenMP, OpenCV, Agent-Based Modeling, Discrete Event Simulation, Object-Oriented Design, Parallel Computing, Data Logging, C++ Random Libraries, FFmpeg (via OpenCV).

**Developer & Researcher: RF-MIMIC Algorithm (Random Forest-based EDA)** | Personal Research/Project
*(March 2024 – March 2025)*
* Designed and implemented `RF-MIMIC`, a novel Estimation of Distribution Algorithm (EDA) for binary optimization problems.
* The algorithm utilizes a Random Forest (from scikit-learn) to model the probability distribution of elite solutions within a population.
* Key components include:
    * Population initialization and fitness evaluation.
    * Elite selection based on fitness.
    * Training a `RandomForestClassifier` to distinguish between elite and non-elite samples.
    * Probabilistic sampling of new candidate solutions from the trained Random Forest model by traversing decision trees and using leaf node statistics.
* Focused on creating a robust implementation capable of handling various problem configurations and ensuring reproducibility through controlled random seeding.
* **Key Technologies & Concepts:** Python, NumPy, scikit-learn (`RandomForestClassifier`), Estimation of Distribution Algorithms (EDAs), Probabilistic Graphical Models (implicitly via RF), Evolutionary Algorithms, Optimization, Algorithm Design.

**Developer: AI Maze Solving Platform & Custom "No-Turn" Algorithm** | Personal Project
*(March 2025 – March 2025)*
* Designed and developed a comprehensive AI testing platform in Python with Pygame for generating, visualizing, and solving complex mazes.
* Implemented a suite of classic AI search and exploration algorithms (DFS, BFS, A\*, Wall Follower, Next-Best-View).
* **Engineered a novel "No-Turn" heuristic-based algorithm (and its variants like "No_turn_radius") for maze solving, which demonstrated excellent results in pathfinding efficiency.**
    * The algorithm prioritizes straight-line movement, incorporates intelligent dead-end detection based on the agent's visited history, and dynamically selects new frontiers using BFS within the agent's visible radius when blocked.
* Created a `MazeVisualizer` with a dual-view display (full maze vs. agent's discovered area) featuring scrolling and panning for detailed analysis of agent behavior.
* Developed a `run_comparison.py` script to systematically evaluate and compare the performance (e.g., steps taken) of different AI algorithms across various generated mazes.
* **Key Technologies:** Python, Pygame, NumPy, Tkinter (for dialogs), Algorithm Design (Custom Heuristics, Pathfinding, Exploration), OOP.

**Developer: Adaptive Math Practice Desktop Application** | Personal Project
*(October 2024 – March 2025)*
* Developed a comprehensive desktop application using Python and Tkinter to provide an adaptive math practice environment for users.
* Implemented core features including secure user registration/login (bcrypt hashing), image-based question display, progress tracking in an SQLite database, and a timed practice mode.
* Engineered an adaptive learning system that selects questions based on user performance across configurable difficulty levels.
* Integrated Google Generative AI (Gemini API) to provide users with detailed, step-by-step explanations for math problems.
* Designed and implemented a LaTeX parsing and rendering pipeline (RegEx, CodeCogs API) to display mathematical notation.
* **Key Technologies:** Python, Tkinter, SQLite3, Google Generative AI (Gemini API), CodeCogs API, Pillow (PIL), bcrypt, RegEx, JSON, `python-dotenv`, `threading`, `queue`.


**Project: Reinforcement Learning for Lunar Lander**
*(June 2019 – September 2019)*
* Developed and implemented a novel variation of the Deep Q-network (DQN) algorithm for the OpenAI Gym LunarLander environment, achieving the winning condition in fewer than 200 training episodes.
* **Technologies Used:** Python, OpenAI Gym, TensorFlow, Keras, Deep Q-Networks (DQN), Reinforcement Learning.

**Project: AI Slackbot for Medical Symptom Collection** | Introduction to Health Informatics Course Project
*(January 2019 – May 2019)*
* Designed and deployed "Benedict," an AI-powered Slackbot agent using a REST API to collect symptoms and provide statistical preliminary diagnostic information.
* **Technologies Used:** Python, REST APIs, [Flask/Django if used], Slack API.

## Skills
* **Programming Languages:** Python (Advanced), C++ (Proficient), SQL
* **AI & Algorithm Design:** Agent-Based Modeling, Estimation of Distribution Algorithms (EDAs), Custom Heuristics, Pathfinding (A\*, BFS, DFS), Exploration Algorithms (NBV), Maze Solving, Swarm Intelligence, Evolutionary Algorithms, Reinforcement Learning (DQN), Probabilistic Modeling, Discrete Event Simulation
* **Machine Learning:** scikit-learn (RandomForestClassifier), Keras, TensorFlow, PySpark, CNNs, Generative AI (Google Gemini), Large Language Models (LLMs)
* **Parallel Computing:** OpenMP
* **GUI Development:** Pygame, Tkinter
* **Computer Vision:** OpenCV (for video processing/visualization)
* **Database Management:** SQLite3
* **API Integration:** REST APIs, Google Cloud APIs, CodeCogs
* **Tools & Platforms:** Google Colaboratory, Amazon AWS, Docker, GitHub, Git, NumPy, SciPy, Pandas, FFmpeg (usage via OpenCV), Make/CMake (implied for C++)
* **Operating Systems:** Windows (API for thread affinity)
* **Web Technologies (Implied by API use):** HTTP, JSON
* **Security:** bcrypt (Password Hashing), Cybersecurity Fundamentals
* **Text Processing:** Regular Expressions, LaTeX parsing
* **Concurrency:** Python `threading` & `queue`
* **Data Science & Analysis:** Performance Metrics & Comparison, Data Insights, Optimization Algorithms, Simulation Data Logging

## Licenses & Certifications
* **Generative AI with Large Language Models** – Issued by DeepLearning.AI & Amazon Web Services (Jul 2024)
* **Go Beyond the Numbers: Translate Data into Insights** – Issued by Google (Feb 2024)
* **Certified in Cybersecurity (CC)** – Issued by ISC2 (Nov 2023, Expires Nov 2026)
* **Foundations of Data Science** – Issued by Coursera (Nov 2023)
* **Microsoft Certified: Azure AI Fundamentals** – Issued by Microsoft (Nov 2023)

## Languages
* Thai (Native)
* English (Fluent)
