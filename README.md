# EMBER_LOSANGELES
### EMBER - Wildfire Evacuation Recommendation System 🔥🆘 (Google Gemini Version)
EMBER is a life-saving AI-powered system optimized for **Google Gemini**, utilizing real-time data, advanced risk assessment techniques, optimized route planning, and state-of-the-art natural language understanding and generation. It delivers **personalized, actionable evacuation instructions** during critical wildfire emergencies. 🌳🔥🏃‍♂️

---

### Table of Contents
- **Key Features ✨**
- **File Structure 📂**
  - `emberorg.py`
  - `risk_assessment.py`
  - `route_optimization.py`
  - `instruction_generation.py`
  - `scoring.py`
  - `visualization.py`
- **Gemini-Optimized RAG Approaches**
  - `Wildfire_RAG.py`
  - `WildfireEvacPipeline.py`
  - `WildFireEvacRAG.py`
- **Supporting Files**
  - `Gemini_RAG.py`
  - `LlamaIndexQA.py`
  - `rl_framework.py`
- **Installation 💻**
- **Usage 🚀**
- **Contributing 🤝**
- **License 📜**

---

### Key Features ✨
- **🌡️ Intelligent Risk Assessment**: Leverages **Google Gemini's advanced AI models** for real-time prioritization of evacuation zones based on GIS, fire perimeter, and traffic data.
- **🗺️ Optimized Route Planning**: Dynamically updates evacuation routes considering live traffic, wildfire behavior, and risk factors, using **Gemini-augmented graph optimization.**
- **🗣️ Personalized Natural Language Instructions**: Generates clear, human-like evacuation guidance tailored to individual needs through **Gemini's multimodal generative capabilities.**
- **🏆 Robust Instruction Scoring**: Ranks generated instructions using Gemini's **custom scoring models** for safety, clarity, and specificity.
- **🌐 Advanced Visualizations**: Provides real-time, interactive maps powered by **Gemini's geospatial capabilities** to visualize evacuation zones, routes, and fire perimeters.
- **🧠 Reinforcement Learning**: Incorporates **Gemini-enhanced learning loops** to continuously improve evacuation guidance from user feedback.
- **📈 Performance Monitoring**: Tracks system reliability and instruction effectiveness using Gemini’s **telemetry and analytics suite**.

---

### File Structure 📂

#### `emberorg.py`
The **Google Gemini-optimized Streamlit application**, coordinating data pipelines, user interactions, risk assessment, route optimization, and instruction generation. Features include:
- Real-time data visualization via **Gemini's APIs.**
- User feedback integration to refine future instructions.  
- Geospatial rendering with **Gemini's mapping frameworks.**

#### `risk_assessment.py`
Defines the **RiskAssessmentAgent**, leveraging **Gemini models** for evaluating evacuation zone vulnerability in real-time. Processes data from:
- **Wildfire perimeter tracking**  
- **Historical fire models**  
- **Environmental factors**

#### `route_optimization.py`
The **RouteOptimizationAgent** employs Gemini's:
- **Dynamic traffic analysis**
- **Risk-weighted graph algorithms**
- **Real-time hazard detection**  
to calculate optimal evacuation routes.

#### `instruction_generation.py`
The **InstructionGenerationAgent** uses Gemini's **multimodal LLM** to:
- Parse user data and optimized routes.
- Generate **human-like, empathetic evacuation instructions.**
- Continuously adapt through **reinforcement learning-driven improvements.**

#### `scoring.py`
Utilizes **Gemini's scoring framework** to rank generated instructions by:
- Safety compliance
- Specificity
- Clarity
- User feedback integration  

#### `visualization.py`
Harnesses Gemini's geospatial capabilities to:
- Render **evacuation zones and routes.**
- Overlay fire perimeters on interactive maps.
- Provide **dynamic route markers** with real-time updates.

---

### Gemini-Optimized RAG Approaches
#### `Wildfire_RAG.py`
Implements **Gemini-enhanced Retrieval-Augmented Generation (RAG):**
- Combines Gemini's **multimodal embeddings** with a vector-based document retrieval system.
- Generates evacuation guidance tailored to **user-specific contexts.**

#### `WildfireEvacPipeline.py`
Streamlines **Gemini-optimized pipelines** by:
- Integrating **sentence transformers** for document retrieval.
- Utilizing Gemini's seq2seq models for **high-quality evacuation instructions.**

#### `WildFireEvacRAG.py`
A **two-stage Gemini RAG system**:
1. **Document Retrieval**: Uses Gemini's **BM25-augmented techniques** for precise content extraction.
2. **Instruction Generation**: Fine-tunes **BART-like Gemini models** for accurate, context-aware instructions.

---

### Supporting Files
#### `Gemini_RAG.py`
**WildfireEvacuationRAG** integrates:
- Gemini’s **vector embeddings** for document retrieval.
- GPT-like Gemini models for **instruction generation.**
- A BERT-based scoring model enhanced with Gemini's **reinforcement learning support.**

#### `LlamaIndexQA.py`
Demonstrates **LlamaIndex capabilities** in building an evacuation-centric document index. Works seamlessly with Gemini's APIs for detailed wildfire scenario-based queries.

#### `rl_framework.py`
Reinforcement Learning with Gemini:
- Adapts instruction models based on **real-time sentiment analysis.**
- Leverages Gemini's **policy gradient techniques** for efficient updates.

---

### Installation 💻
1. **Clone the repository**:  
   ```bash
   git clone https://github.com/your-username/ember-gemini.git
   ```
2. **Install dependencies**:  
   ```bash
   pip install -r requirements.txt
   ```
3. **Set up Gemini integration**:  
   - Obtain API keys and set environment variables for **Google Gemini.**
   - Configure GIS and traffic APIs (e.g., GeoJSON, live traffic data).

4. **Run the application**:  
   ```bash
   streamlit run emberorg.py
   ```

---

### Usage 🚀
1. Access the **EMBER-Gemini** application via the Streamlit interface.
2. Input details:
   - Location
   - Fire name and year
   - Number of people
3. Generate and interact with personalized evacuation instructions.
4. Explore **Gemini-enhanced visualizations** on real-time maps.
5. Provide feedback to improve future instruction quality.

---

### Contributing 🤝
Contributions are welcome! If you have ideas, improvements, or want to report issues:
- Open an issue or PR on [GitHub](https://github.com/your-username/ember-gemini).
- Collaborate with the community to make **EMBER-Gemini** more impactful.

---

### License 📜
This project is licensed under the **MIT License**, promoting open collaboration and innovation.

