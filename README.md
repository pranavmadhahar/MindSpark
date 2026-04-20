# MindSpark

MindSpark is a notebook-based project built with **LangChain** and **OpenAI** that generates a **Daily Inspiration Pack** around any theme you choose.  
It combines poetry, motivational quotes, affirmations, and reflection prompts into a single pipeline — perfect for showcasing modular chain design and creative AI applications.

---

## Features
- **Poem Generator** → 4–6 line themed poem
- **Motivational Quote** → one-liner inspiration
- **Affirmation** → positive “I am / I can” statement
- **Reflection Prompt** → journaling/self-reflection question
- **Interactive UI** → optional ipywidgets chat interface for a bot-like experience

---

## Project Structure
- `MindSpark.ipynb` → main notebook with chain definition and demo
- `requirements.txt` → dependencies
- `.env` → environment variables (excluded via `.gitignore`)

---

## Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/MindSpark.git
   cd MindSpark
   ```

2. Create a virtual environment
   ```bash
   python3 -m venv myenv
   source myenv/bin/activate
   ```

3. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

4. Add your OpenAI API key
   - Create a .env file in the project root:
   ```bash
   OPENAI_API_KEY=sk-your-key-here
   ```

## Usage
   ```bash
   jupyter notebook MindSpark.ipynb
   ```

   - Inside the notebook:

     - Provide a theme (e.g., courage, hope, gratitude).

     - The chain will generate a poem, quote, affirmation, and reflection prompt.


   - Example:
     ```bash
     Theme: Courage
     Poem:
     In shadows deep, where doubts reside,
     Courage stirs, a fierce ally beside.
     With every step, the heart ignites,
     Facing fears, embracing heights.

     Quote:
     "Courage is not the absence of fear, but the triumph over it."

     Affirmation:
     I am brave and resilient, and I embrace challenges with confidence.

     Reflection:
     What is a recent situation where I felt afraid or hesitant, and how did I find the courage to confront it?
     ```
     
## Optional Interactive UI
   The notebook includes an ipywidgets chat interface where you can type a theme and receive your inspiration pack in a conversational format.


## Requirements

   - langchain

   - langchain-openai

   - langchain-core

   - python-dotenv

   - ipywidgets

## Security Notes
   Do not commit your .env file or API key to GitHub.
  .env is already excluded via .gitignore.












