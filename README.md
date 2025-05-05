# 📝 Madlibs Generator 

A simple and fun Python project that reads a story template with placeholders, prompts the user for inputs, and replaces the placeholders to generate a personalized story.

## 📌 How It Works

1. The story is stored in a `story.txt` file with placeholders like `<noun>`, `<place>`, `<emotion>`, etc.
2. The Python script scans the text, identifies all unique placeholders.
3. The user is prompted to enter values for each placeholder.
4. The script replaces all placeholders with user-provided words and prints the final story.

## 📂 Project Structure

madlibs-story-generator/
│
├── story.txt # Template story with placeholders
├── madlibs.py # Python script
└── README.md # Project documentation


## 🧠 Concepts Practiced

- File handling in Python
- String manipulation
- Set operations
- Loops and conditional logic

## ▶️ Example

**Sample `story.txt`:**

In the <adjective1> land of <place>, a <animal> was feeling <emotion>. The <animal> had lost its <object>.

Suddenly, a <character> appeared. 'I will help you find your <object>,' they said.

Together, they journeyed through <terrain> and faced the <weather_condition>. Finally, they found the <object> in a <place2>. The <animal> was so <emotion2> and thanked the <character>. They lived <adverb> ever after.


**User Inputs:**

<adjective1>: magical
<place>: Enchanted Forest
<animal>: fox
<emotion>: lonely
<object>: golden compass
<character>: wise old owl
<terrain>: misty mountains
<weather_condition>: heavy rain
<place2>: crystal cave
<emotion2>: grateful
<adverb>: happily

**Final Output:**
In the magical land of Enchanted Forest, a fox was feeling lonely. The fox had lost its golden compass.

Suddenly, a wise old owl appeared. 'I will help you find your golden compass,' they said.

Together, they journeyed through misty mountains and faced the heavy rain. Finally, they found the golden compass in a crystal cave. The fox was so grateful and thanked the wise old owl. They lived happily ever after.


## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/madlibs-story-generator.git
   cd madlibs-story-generator
2. Run the script:
    python madlibs.py
4. Enter your words as prompted.

💡 Feel free to extend the project:
Add random word generation

Use multiple stories

Create a GUI version
