# Pressure
"Pressure" (psai): Methodolgy and Metrics for External Influence on Base Model Performance
(RESEARCHERS NEEDED)

After some debate about how I want to present this, I've decided that consistent transparency and open-source research is my main objective right now. I will be formatting this and adding as I go. 

Therefore, I'd like to introduce something I came up with yesterday. I call it PRESSURE. 

INTRO:

I've been increasingly aware that the majority of this community is struggling with understanding what plugins are,  and how they actually work. 

OpenAI has really only left us some breadcrumbs, and I was still hungry.  I think I have a possibly unique understanding of what this plugin framework actuality is,  and I'd like to share it,  so that we might all push this tech to its limits!

Enjoy:
https://chat.openaig.com/share/e8613c8-9745-48d6-b0e4-fc68f56e2fa9](https://chat.openai.com/share/e86153c8-9745-48d6-b0e4-fc68f56e2fa9)

TL:DR- A plugin is more than the sum of its parts. They need to be viewed in such a way where the various parts are dynamic pieces of one single, engineered prompt.

 Therefore, every single letter has a impact on the overall performance of the base model. I'm proposing a method to measure the impact these variables have, regardless of the base model weights.  

We don't have the power to change model weights,  but we can apply pressure and influence its direction, and supplement its potential...or "kinetics" if it so please the court.  


This research is ongoing, please contact me if you're interested in helping. 

Initial Pressure Algorithm
The Pressure Score is defined as follows:

Psai = w1*(APr) + w2(RRe) + w3(UL) + w4(PCS) + w5(CLD) + w6I + w7*(RS) + w8*(RT)

where:

A is the Accuracy Deviation Score, calculated as 1 - Precision (Pr)

R is the Relevance Deviation Score, calculated as 1 - Recall (Re)

U is the User Satisfaction Deviation Score, calculated as 5 - Likert Scale Score (L)

P is the Pressure Score, calculated using cosine similarity (CS) between model outputs with and without the plugin

C is the Component Impact Score, calculated using Levenshtein distance (LD) between original and modified components

I is the Improvement Score, calculated as the percentage change in the Deviation Score after each iteration of improvement

RS is the Readability Score, calculated using the Flesch-Kincaid readability score

RT is the Response Time, calculated as Time_Received - Time_Sent

The weights w1, w2, w3, w4, w5, w6, w7, and w8 are determined using a data-driven approach such as linear regression with L2 regularization. This is where I need help from experienced data scientists and LLM engineers. A very large dataset is needed and a large amount of time will be spent making sure we have some universal baseline weights we can apply. 
