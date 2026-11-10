# DSC180A Methodology Assignment 4

--- 

Ivan Chen \
Email: ivc003@ucsd.edu \
Section: D23 (Red-Teaming the Swarm: Autonomous Auditing for Financial LLMs)

Mentors: 
1. David Afshartous
2. Dhruvi Kothari
3. Victor Calderon

---

## Quarter 2 Project Brainstorming

**1. What is the most interesting topic covered in your domain this quarter?**

I've discussed this a bit already in my PAs by the most interesting topic this quarter for me has been the idea of multi-turn drift in LLM and agentic conversation logs. I think it's really been sold in main stream media that these models and tools are designed to be largely autonomous chatbots that are able to recieve and interpret information as well as there are able to deliver information and tasks. But as existing research demonstrates, and part of what my project touches upon, is that LLMs and agents often get 'lost' in multi-turn or round conversations. Performance typically decreases significantly the further the conversation goes and one an agent makes the wrong 'turn', it's hard to recover.


**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

Going along the lines of what I just mentioned with multi-turn drift, I think I would like Quarter 2 to be a simulation at a much larger scale. At the moment, because of the time spent designing the project proposal and the necessary research behind it, our Project 1 is fairly defined and narrow in scope as a result. I think expanding our project to multiple agents with multiple tasks is really the next (albeit ambitious) direction that I have in mind to push for in Winter Quarter.

**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

The potential change that I would want to make with our approach is our dataset. At the moment, we're using FinQA and ConvQA, a dataset of credit-renewal conversations and real-world company tasks to test agent performance. With the latter being a 'broken down' or multi-turn version of the former, it was an interesting dataset and a good pair to work with. However, we are running into a slight bottleneck with obtaining company policies that agents need to follow. Unfortunately, that is largely proprietary information, so in hindsight, it might have been better to find another real-world financial dataset that had these policies more public.

**4. What other techniques would you be interested in using in your project?**

With this project in particular, I would be interested in working more on synthetic generation. Human conversations are hard to mimic and datasets based on it are usually proprietary and held by companies due to their value in training. I've worked with generating synthetic data in my past internships, so applying some of those methods, even the most basic like prompt tuning, would be interesting to see how those conversations not only turn out, but how agents respond to them compared to other datasets.
