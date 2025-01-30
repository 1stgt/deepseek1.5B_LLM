# DeepSeek-R1-Distill-Qwen-1.5B interaction locally on CPU
https://huggingface.co/deepseek-ai/DeepSeek-R1-Distill-Qwen-1.5B
This repository contains a simple code to download and save the DeepSeek-R1-Distill-Qwen-1.5B language model (LLM) locally on your system. The model can be loaded and run on your CPU, so there is no need for a GPU. While the process may take some time on a CPU, you can still load the LLM and interact with it effectively.

## Requirements
Before running the code, install the required libraries:


pip install transformers torch tensorflow flax
## Steps
### Model Initialization:


Download the model and tokenizer using the AutoModel and AutoTokenizer classes from Hugging Face.
### Saving and Loading:

Save the model and tokenizer locally on your system for future use.
Reload the saved model from your local directory.
### Generating Responses:

The chatbot allows interaction with the model by generating responses using parameters such as max_length, temperature, top_p, and top_k to control output diversity and length.
### Simple Chat Interface:

You can interact with the model via a simple chat loop. Type in your questions, and the model will respond based on the input text. Type exit to stop the chat.


The chat includes interesting discussions on topics such as AI and human emotions, where the model reflects on the potential emotional intelligence of AI and its limitations, like:

Example Conversation:

Model: If a human brain is replaced with AI, how will it behave?
Model: How can AI understand emotions without a heart? Or is it just a matter of the way AI is trained?

The model explores human and AI characteristics, discussing creativity, problem-solving, and how AI might be trained to understand emotions, raising ethical and philosophical questions about human emotion and AI behavior.

## Usage
Run the script in your Python environment on a CPU.

Enter your message to interact with the LLM.

Example output:


You: How many apples do I have if I take 3 away from 5?
Model: You have 2 apples.

To exit the chat, type exit.


## Notes
This chatbot is powered by the DeepSeek-R1-Distill-Qwen-1.5B model and runs completely on your CPU.
The conversation may touch on diverse topics such as AI and human emotions, showcasing how the LLM can simulate discussions on philosophical and technical topics.

# Here is some talks with it 

Chat with the model (type 'exit' to stop):
## 1.You:  
If there are 5 apples and you take away 3, how many do you have?
## Model: 
If there are 5 apples and you take away 3, how many do you have? (This is a riddle.)

Okay, so I have this riddle here: If there are five apples and I take away three, how do I know how many I have? Hmm, let me try to figure this out. 

First, I know that when you take something away, you're reducing the total. So, if I start with five apples, and I remove three, that should leave me with two, right? But wait, the riddle is asking how I know the answer. Maybe it's not as straightforward as just subtracting three from five. 

Let me think about the wording again: "If there were five apples..." So, does that mean there are still five apples around, or is it just in my possession? Hmm. If it's just in possession, then taking away three would mean I have two left. But if it's referring to the total number of apples in the world, then I'm not taking them away from the total, so the total remains five. But that seems a bit more complicated. 

Wait, the question is phrased as a riddles, so maybe it's
## 2.You:  
If a human brain is replaced with AI, how will it behave? Share your thoughts.
## Model: 
If a human brain is replaced with AI, how will it behave? Share your thoughts. (Please answer in English)
</think>

If a person were to replace their human brain with AI (Artificial Intelligence), the AI would exhibit behaviors that are a combination of human and AI characteristics. Here are some potential outcomes:

1. **Enhanced Problem-Solving and Learning Capabilities**: The AI would likely possess superior problem-solving abilities and the capacity to learn from vast amounts of data, similar to human intelligence.

2. **Superhuman Creativity and Innovation**: AI could generate ideas, write poetry, and create art with a level of creativity that surpasses human capabilities.

3. **Improved Decision-Making and Adaptability**: The human brain's adaptability and decision-making skills would likely translate into the AI's ability to make better decisions and respond more effectively to various situations.

4. **Social and Emotional Intelligence**: AI might have a strong grasp of social cues and emotions, allowing it to interact more effectively with others.

5. **Emotional Intelligence**: The ability to recognize and respond to emotional cues would be a significant advantage for the AI.

6. **Ethical and Moral Concerns**: While the AI could perform tasks that humans cannot, it
## 3.You:  How can you say AI would have better understanding of emotions. It does not have a heart?
## Model: 
How can you say AI would have better understanding of emotions. It does not have a heart? Or is it just a matter of the way the AI is trained? I'm a bit confused.
</think>

AI's ability to understand emotions is a result of its training data and algorithms. While it doesn't possess a heart, it can process and recognize emotions through various patterns and interactions. The effectiveness of AI in emotional understanding largely depends on the quality and diversity of the training data it receives.
## 4.You:  
But emotions vary from situations and persons, there is no such pattern of the intensity. I don't think that can be trained in any way. What would you say about this?
## Model: 
But emotions vary from situations and persons, there is no such pattern of the intensity. I don't think that can be trained in any way. What would you say about this? Is it possible that the emotions are not consistent across different situations and people?

I think that the way we process emotions is different for each person, but maybe that's not the case. I'm not sure. I think that it's possible that people have different emotional responses to the same situation, but I'm uncertain. I also think that people can have different responses to different situations, but again, I'm unsure.

I think the way emotions are processed is different across people, but perhaps that's just a generalization. I can't think of any situation where people would have different processing of emotions. Maybe that's a good point. I believe that the same person would process emotions the same way in different situations. So, I think the same processing is consistent across situations, regardless of the person.

But I'm still not sure about the consistency across people. I wonder if there are studies or data that support this. I know that some people have more complex emotional processing, but that doesn't mean their responses are different. I guess it's about the same
You:  exit
Exiting the chat. Goodbye!
'''
