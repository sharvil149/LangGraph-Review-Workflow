# LangGraph Workflow Projects

This repository contains a collection of workflow-based projects implemented using LangGraph and Large Language Models (LLMs). Each notebook demonstrates how structured graph-based logic can be combined with AI models to solve different types of problems, including mathematical computation, content generation, conversational AI, and automated response systems.

The purpose of this repository is to explore workflow orchestration using LangGraph while applying it to practical and educational use cases.

---

## Project Structure

The repository contains the following nine Jupyter notebooks:

### 1. 1_bmi_workflow.ipynb

This notebook implements a BMI (Body Mass Index) calculator using a workflow structure.  
The workflow:
- Accepts user height and weight
- Calculates BMI
- Classifies the result into health categories
- Returns structured output

This demonstrates conditional branching inside a workflow.

---

### 2. 2_simple_llm_workflow.ipynb

This notebook provides a minimal example of connecting a Large Language Model to a LangGraph workflow.

It demonstrates:
- Basic node creation
- Passing state between nodes
- Generating LLM responses inside a workflow

This serves as a foundation for more advanced workflows.

---

### 3. 3_prompt_chaining.ipynb

This notebook demonstrates prompt chaining using multiple LLM calls.

The workflow:
- Breaks a task into multiple steps
- Sends sequential prompts to the model
- Passes outputs from one step into the next

This shows how complex reasoning can be structured into manageable stages.

---

### 4. 4_batman_workflow.ipynb

This is a themed workflow project that generates responses in a specific persona.

The workflow:
- Accepts user input
- Applies character-based transformation
- Produces styled responses

This demonstrates prompt engineering and controlled tone generation.

---

### 5. 5_upsc_workflow.ipynb

This notebook generates UPSC-style study content and questions using LLMs.

The workflow:
- Accepts a topic
- Generates structured explanations
- Produces practice questions

This shows how AI can be integrated into educational workflows.

---

### 6. 6_quadratic_equation.ipynb

This notebook solves quadratic equations using workflow logic.

The workflow:
- Accepts coefficients (a, b, c)
- Calculates discriminant
- Determines nature of roots
- Computes real or complex solutions

This demonstrates combining deterministic logic with structured outputs.

---

### 7. 7_review_reply_workflow.ipynb

This is the most advanced workflow in the repository.

It implements an automated review response system:

- Accepts a customer review
- Classifies sentiment
- Diagnoses issue type
- Determines urgency level
- Generates an appropriate response
- Routes through positive or negative response nodes

This project demonstrates multi-branch workflows and real-world application logic.

---

### 8. 8_X_post_generator.ipynb

This notebook generates social media posts based on a given topic or intent.

The workflow:
- Accepts topic input
- Determines tone or purpose
- Generates structured post content

This demonstrates controlled content generation using LLMs.

---

### 9. 9_basic_chatbot.ipynb

This notebook implements a simple chatbot using LangGraph.

The workflow:
- Accepts user message
- Sends it to an LLM
- Returns generated response
- Maintains structured flow

This demonstrates conversational workflow integration.

---

## Technologies Used

- Python
- LangGraph
- Large Language Models (such as OpenAI or Groq )
- Jupyter Notebook

---

## How to Run the Project

### 1. Clone the Repository
git clone https://github.com/sharvil149/LangGraph-Review-Workflow.git

cd LangGraph-Review-Workflow


### 2. Create Virtual Environment (Optional but Recommended)

Windows:

python -m venv venv
venv\Scripts\activate


Mac/Linux:

python3 -m venv venv
source venv/bin/activate


### 3. Install Dependencies


pip install -r requirements.txt


If a requirements file is not available, install required libraries manually.

### 4. Run Notebooks

Start Jupyter Notebook:


jupyter notebook


Open any notebook and run cells sequentially.

---

## Learning Outcomes

Through these projects, the following concepts are demonstrated:

- Workflow orchestration using LangGraph
- State management across nodes
- Conditional branching logic
- Prompt engineering techniques
- Prompt chaining
- Structured AI response generation
- Integration of deterministic logic with LLM outputs

---

## Future Improvements

Possible improvements to this repository include:

- Adding a web interface using Streamlit or Flask
- Adding environment variable handling for API keys
- Adding unit tests for workflows
- Improving modularization of repeated components
- Adding documentation diagrams for each workflow

---

## Conclusion

This repository demonstrates how workflow-based architectures can be combined with Large Language Models to build structured, reliable, and reusable AI systems. The notebooks range from basic examples to more advanced real-world implementations.

The projects collectively showcase understanding of LangGraph, workflow logic, and AI-powered application 
