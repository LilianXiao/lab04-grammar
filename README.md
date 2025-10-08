# lab04-grammars
Let's practice using grammars! For this lab, please pull up the L-system node in Houdini.

## 1. Wheat grammar puzzle
Look at these iterations (n = 1, 2, 3) of a one-rule grammar. Using the built in symbols in Houdini, design a grammar that produces this output. Take a screenshot of your rules.\
<img width="200" alt="square1" src="https://user-images.githubusercontent.com/1758825/193949661-a3a0e1f7-7d68-4b9e-8384-d9991e1e9fd2.png">
<img width="200" alt="square2" src="https://user-images.githubusercontent.com/1758825/193949853-cf2306b3-3537-4c24-91b5-0a3083bc87c0.png">
<img width="200" alt="square3" src="https://user-images.githubusercontent.com/1758825/193949859-5e432b4b-f18d-48b5-a9e9-8d7dba255955.png">

# RESULTS
Grammar: F=FF[-FF][-F]F[-FF]FF-\
Premise: F\
n = 1\
<img width="262" height="407" alt="image" src="https://github.com/user-attachments/assets/4acb43ec-6573-4219-9bc2-a92387336d51" />

n = 2\
<img width="313" height="371" alt="image" src="https://github.com/user-attachments/assets/1b0956c6-a088-4f24-9c1e-4db4dfe385a1" />

n = 3\
<img width="314" height="376" alt="image" src="https://github.com/user-attachments/assets/1ac7c2a3-ca05-4409-a2e2-a88024993928" />

## 2. Square grammar puzzle
How about this one? Take a screenshot of your rules.\
<img width="200" alt="square1" src="https://user-images.githubusercontent.com/1758825/193949895-87cdfb43-da7c-4867-ab1b-107e1ba9d2a7.png">
<img width="200" alt="square2" src="https://user-images.githubusercontent.com/1758825/193949904-a9cdfe0f-319e-4ca8-9935-dd338217a7cf.png">
<img width="200" alt="square3" src="https://user-images.githubusercontent.com/1758825/193949910-928e5993-ce26-4681-80f8-ffeb54be4dcf.png">

# RESULTS
Grammar: F=F+F-F-F+F
Premise: +F

n = 1\
<img width="222" height="211" alt="image" src="https://github.com/user-attachments/assets/b33e4709-6fc8-42f1-9fd5-48a82a8050fc" />

n = 2\
<img width="292" height="260" alt="image" src="https://github.com/user-attachments/assets/99e5710f-3591-4488-b14d-4c2ce37cdfcf" />

n = 3\
<img width="305" height="218" alt="image" src="https://github.com/user-attachments/assets/e352e6ed-1aa4-4a8b-bf37-6b35f0345d1a" />



## 3. Custom plant
Choose a plant in the world. Working off a reference, design a grammar that mimics the structure of that plant. Unlike our simple puzzles, please use multiple rules for greater complexity. Think carefully about the structure of your grammar! EXPLAIN the structure of your plant in the README. What are the components? What do each of the rules do? Be sure to also include images of a few iterations of your output plant. 

## Submission
- Create a pull request against this repository
- In your readme, list your solutions and format your README nicely
- Profit
