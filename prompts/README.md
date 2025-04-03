# Prompt Templates
As part of our study, we implemented four differnt prompting strategies:
- **Naïve (N)**: provided the model with only the problem statement, grading rubric, and student answer. 
- **Naïve with Solution (NS)**: extended the Naïve prompt by incorporating the instructor’s reference solution. 
- **Few-Shot (FS)**: extended the Naïve prompt by adding a graded example to guide the model’s evaluation.
- **Chain of Thought (COT)**L used the same inputs as the Naïve prompt abd explicitly instructed the model to explain its reasoning process. 