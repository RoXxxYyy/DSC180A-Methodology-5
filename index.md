# Yexiaolu He (yehe@ucsd.edu)
## B16 Zhiting Hu

**What is the most interesting topic covered in your domain this quarter?**  
Our domain in this quarter is generative agents. Tne most interesting topic covered in this quarter is that we are going to use Sentence Similarity in huggingface library 
as a metirc to assess memory consistency. That is because, in the original paper, using early version of GPT model, may generate issues of "illusions" for agents memory. 
Therefore, we introduced a new and free model, llama2, to run our simulation. Using the sentence similarity, we can determine whether the illusions issues will happen in this model, 
proving us new insight into the generative agents simulation with a new large language model.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
In Quarter 2, we are going to add a user interaction with generative agents. This will involve designing a interface for user input that interact with those agents, and we can
assess the influence on agents' memories, plans and actions. The core investigation will measure how these agents adapt and change their behavior after direct user interaction, and
understand the dynamics of human-agents interaction and the potential for personalized agents behavior.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
A potential change would be explore and apply a new speed up techniques. In Quarter 1 Project, we reduce numerical precision by using 4-bit, which while effective in reducing load times, precision will be lowered. We will investigate "flash attention" to try to speed up the process to balance performance and precision, since we are going to involve a dynamic 
human-agents interactions and measure the change of their behavior, lower precision may effect the integrity of the results.

**What other techniques would you be interested in using in your project?**  
In addition to sentence similarity, we are interested in using Textual Entailment in huggingface library as a method to measure the logical consistency between texts. The approach
can determine if the meaning of one text can be inferred from another, which is crucial for understanding the depth of human-agent interaction. Using this technique can evaluate and
interpret agents' response in the context of users input, and add a another dimension to investigate the difference of logic of generated memories besides directly comparing 
the text similarity.
