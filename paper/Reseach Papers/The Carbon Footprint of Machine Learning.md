# Paper Summary

Paper Title: The Carbon Footprint of Machine Learning Training Will Plateau Then Shrink 
Authors: Emma Strubell, Ananya Ganesh, Andrew McCallum  
Year: 2022
URL: https://www.researchgate.net/publication/358784543_The_Carbon_Footprint_of_Machine_Learning_Training_Will_Plateau_Then_Shrink

## 1. Problem
Machine learning (ML) is growing super fast, and people worry about how much energy it uses. Training big AI models can produce a lot of CO2. The paper looks at whether this energy use will keep rising or if it can be controlled.

## 2. Approach
The authors studied real-world data from Google and other cloud providers. They compared older models like Transformer and GPT-3 with newer, more efficient ones (Evolved Transformer, Primer, GLaM). They looked at things like:  

- Which model is used  
- Hardware efficiency (GPUs, TPUs)  
- Datacenter energy efficiency  
- Location of datacenters and carbon intensity  

They calculated energy usage and CO2 emissions for training and inference.

## 3. Key Findings
- Using smarter models, better hardware, and green datacenters can cut CO2 by hundreds of times.  
- Newer models like GLaM are much more energy-efficient than older ones like GPT-3, even though they’re bigger.  
- ML energy use is only a small fraction (<15%) of Google’s total energy, and it hasn’t been growing fast.  
- Neural Architecture Search (NAS) uses energy at first but saves much more later by finding efficient models.  
- Choosing datacenter locations with low-carbon energy makes a big difference.

## 4. Relevance to Our Topic
This paper shows that AI doesn’t have to be bad for the environment if we follow best practices. It’s important for any research on AI sustainability, energy efficiency, or green tech. It also highlights practical strategies like model choice, hardware, and location that we can apply in our work.

## 5. AI Disclosure: Parts of this summary were drafted with the assistance of an AI language model (ChatGPT). The content has been reviewed and edited for accuracy, clarity, and a human writing style by the student.
