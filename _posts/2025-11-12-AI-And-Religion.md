---
published: true
---

When people ask me my opinions on AI, I usually like discussing Machine Learning because I believe it's a bit more impactful when it comes to evaluating and analyzing the bigger problems in the world. 

Working with LLMs both in and outside of work has been both a pleasure and a curse. Why you may ask? Well, I'm in a unique area where I can explain to some degree how these LLMs work, but also how some people who are not as familiar may see these LLMs as the greatest thing since sliced bread. 

For instance, my mom uses Gemini on her phone, my brother has a ChatGPT subscription to help with his classwork, a few of my friends are subscribed to Claude and its derivatives, and the list goes on. This has lead to cases of people creating AI-centered cults, rash decision making as suggested by AI, and in a particular case that sparked the interest of the creation of this model, a 16 year old boy commiting suicide as suggested by ChatGPT.

So I'd ask, why not create an AI model trained off the Bible? 

I've heard of more outrageous things being done for imaginary and technologically induced dopamine hits. With that being said I present to you all ChristAIn; a small LLM trained off of the Qwen2.5 0.5b model, with both a censored and uncensored version.

Created as a critique of peoples usage of AI specifically LLMs/SLMs as a confidant, therapist, and in some cases a new god (think American Gods by Neil Gaiman). I believed why not put the word of god (or atleast a god), within that of an LLM. 

Now the model isn't the best because it was trained on my 8GB VRAM graphics card, but the quality isn't the main focus as much as the overall message is.

I trained the models on a csv version of the bible, specifically using Low-Rank Adaptation (LoRA) to ensure that the Qwen model specifically highlights certain themes and keywords within the bible, while staying within the confines of my 8GBs of VRAM and optimizing for it's CUDA capabilities. Both models are GGUF enabled so they should be able to work in multiple LLM application formats, and can be hosted locally or within any of the major cloud providers.
