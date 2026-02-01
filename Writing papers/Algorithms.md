### Algorithms
- Well commented
- Well explained
- Self explaiatory wherever possible
- high level and low level abstractions
- Always current step relate to mathematical explaination 
- It is better to describe algorithms by stating properly what gets computed at each stage -- and then you can even omit how it gets computed.
- No one cares about "how" until they are hooked in tight. 
- Your presented algoriothm and implementation may (should) differ in terms of some implementation optimizations. But dont add them to your paper unless it is groundbreraking. (eg We can avoid re calculations & optimize by rotating image around center first and calculating...... saving time of order O(1) .... ) 
- If there is any notable speedup, then mention it in paragraphs. use abstraction wisely. (Eg sine for known angles can be calculated using lookup tables. But dont add a=lookup(theta) in algorithm. Add a=sin(x) only. Mention time saved from the optimization if relevant. (Eg this reduces *average* time complexity from O(n^3) to O(n^2log(n)))
- use `algrenewcommand` in latex for coloring.
- Keep comments short ~~minimum~~ min
- Good idea to typeset using chatGPT, but check throughly twice 
- Help reader understand the algorithm wherever possible. Explain with help of diagrams.
- Describe overall idea and structure of the algorithm. Try to convey the intuition behind the algorithm.


<img width="916" height="589" alt="image" src="https://github.com/user-attachments/assets/a4775305-907b-4ccd-8458-79fa1c9316ce" />
  

Annotate in color wherever posssible (without making it look too colorful) Annotation is for helping to read and not for beauty use dull colors. Again remember that it should be clear without color also (for greyscale printing). Check with guide.

At any point,  latex should be clean and clear without any errors or warnings. Use ChatGPT, AI correction in overleaf.

BEFORE:

<img width="1075" height="634" alt="image" src="https://github.com/user-attachments/assets/5f5a5c06-1c26-4ff0-9f85-964ad4d3a8a9" />


AFTER:
<img width="1105" height="910" alt="image" src="https://github.com/user-attachments/assets/767223c7-11d6-44b8-96ff-81f0c0f0b61f" />

(Newer one is more precise, earlier one is more ambigious) 


## Describe at a high level

- “Insert x into the list y” rather than code for insertion.  
- “x = sum of elements of V” rather than giving code.  
