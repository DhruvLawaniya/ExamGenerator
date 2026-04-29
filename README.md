# ExamGenerator
One stop solution to generate Exam style Question Paper

I created this website specifically for my time at the University of Sydney, to use this:
Step 1 : Go to any AI CHatbot
Step 2 : Upload all lecture contents and ask the AI Bot to generate a JSON file for exam style questions(sampple JSON structure provided below). Once this is done, upload this json to the website and it is good to go

Sample JSON structure:
{
  "title": "Exam Title",
  "subject": "Optional",
  "duration_minutes": 30,
  "questions": [
    { "type": "MCQ", "question": "...", "answer": "Paris", "incorrect_options": ["London","Berlin","Rome"] },
    { "type": "MCQ", "question": "...", "answer": ["Python","Rust"], "incorrect_options": ["HTML","CSS"] },
    { "type": "FIB", "question": "The ___ is the capital of France.", "answer": "Paris" },
    { "type": "SHORT", "question": "...", "answer": "Model answer here" },
    { "type": "LONG", "question": "...", "answer": "Detailed model answer here" }
  ]
}
