# Introduction
- Start with a good first sentence - This is the only sentence that people may read first (after abstract) before going through rest of paper.
- If your audience does not understand the problem, it does not matter how good the rest of the talk/paper is.
- Very important part of the manuscript. Many papers get rejected because of poor start.

### Start of the intro - defining the problem
- How to state the problem: Real life situation
- Give people a reason to read your writing.
- Should make the reader want to learn more.
- Should also provide background information
- Explain research question
- The introduction must contain a good description of the problem, what constitutes the input and what are desirable outputs.  
- While discussing this avoid discussing HOW to compute the outputs, but just focus on WHAT outputs are desirable/acceptable.  
- Give examples. The problem statement should be clear to every reader, even those who arent paying 100% attention. 
- Give the motivation for solving the problem.  Eg real life situation
- Identification of the research gap that you want to fill
- What problem are you solving? Use of statistics may provide depth. (Eg $ 100M productivity loss happens every year due to downtime of servers)
- Discuss about the background information on the topic (Eg I dont know why server goes down)
- The introduction should also give some idea as to why the problem is hard (non trivial) for (type 1 & type 2). Why do simple algorithms not work (for type 2 people)? and most importantly, why should we solve the problem? (For type 1, type2 and type 3)
- What is known, what is believed, what is still unknown, what are the problems, etc. Add historical account of relevant research literature to support your arguments
- Provide special emphasis to recent papers (i.e., within past 5 years)
- Also clarify the scope of the solution
- Make sure that in all this, the problem defination and motivation is not lost


### 5 Why questions

|                             | Question                           | Answer                                               | Abstract                | Intro                                                                        | Literature survey                                                                                                                                | Conclusion                                                                                                        |
| --------------------------- | ---------------------------------- | ---------------------------------------------------- | ----------------------- | ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| What                        | **What are you exactly doing?**    | **Problem defination**                               | One or Half line        | In details - what is problem being solved and also what is not being solved. | What problem is  being solved differently than others (if you are solving a different problem, eg solving problem of speed rather than accuracy) | Summary/gist of problem that was solved                                                                           |
| Why                         | **Why are you doing?**             | **Importance of the problem statement**              | One or Half line        | In details about the problem statement importance                            | -                                                                                                                                                | How can your solution solve xyz problem. Also stress societal impact in 1-2 lines. What suffering are you ending? |
| Why                         | **Why has it not been solved?**    | **Research gaps**                                    | One or two line         | Gist here rest in lit survey                                                 | What have others not done?                                                                                                                       | Improvement found over other methods (gist from results section)                                                  |
| How                         | **How are you solving it?**        | **Your solution**                                    | Two or three lines      | Only glimpse in introduction. Rest in later paper                            | What is different about your solution                                                                                                            | What is different about your solution                                                                             |
| What                        | **What are the advantages?**       | **Your novelty**                                     | Two or three lines      | Gist here rest in result section                                             | Relative advantages overview. (refer to results section)                                                                                         | Absolute + relative advantages                                                                                    |
| **Most important question** | **Why should we read your paper?** | **Your novelty**, **Why does your research matter?** | Highlight contributions | Highlight contributions                                                      | Relative advantages overview. (refer to results section)                                                                                         | Highlight contributions                                                                                           |

### The end of the intro
- Mention about the 'good thing' in breif towards the end of introduction
- End the introduction with the research questions
- Explicitly declare your novelty and contributions
- Highlight the solution in bullet points (depends on venue of publication)
> Eg The empirically verified results show
	- 10% increase in Accuracy
	- 14% increase in FPR
- Finally give an overview of the rest of the report.  Even in a talk, it is better to give the overview after the introduction.


### Dont write long sentences here, use small simpler sentences
- Break big sentence into smaller sentences. Break big paras into smaller paras. Golden rule - Principle of cohesion. 
- Avoid weak qualifiers: very, rather, somewhat, quite


Example
  
> While various approaches have been proposed over the past decade to address the increasing computational complexity of neural network training in resource-constrained environments, including but not limited to pruning techniques, quantization methods, and hardware-aware architecture search — each with its own trade-offs in terms of accuracy, latency, and energy efficiency — the lack of a unified evaluation framework continues to hinder consistent benchmarking, thereby complicating direct comparison and potentially leading to misleading conclusions in real-world deployment scenarios.

Break such into smaller parts:

> Over the past decade, many methods have been proposed to reduce the computational complexity of training neural networks, especially in resource-constrained environments.
These methods include pruning techniques, quantization methods, and hardware-aware architecture search.
Each of these approaches comes with its own trade-offs — such as differences in accuracy, latency, and energy efficiency.
However, a major challenge remains: there is no unified evaluation framework.
This makes it hard to compare methods consistently. In turn, it can lead to misleading conclusions when applying them in real-world situations.
