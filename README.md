# Investimate
Trade with Confidence.... Learn with Ease....

## Inspiration
As a stock market trader, I've invested countless hours in understanding market trends and researching stocks. This process is extremely time-consuming. In the beginning, I struggled significantly to grasp key concepts.  These struggles inspired me to develop **InvestiMate**, a solution to streamline the trading and learning process for both novice and experienced traders, which solves below problems:

![Problems](https://res.cloudinary.com/dg5j2nhg7/image/upload/v1717384313/Investimate_Problems_ks86w0.png)

## What it does
**InvestiMate** is a bot designed to assist traders by providing access to a _comprehensive stock market knowledge base and real-time market data_. It helps users learn essential trading concepts and conduct in-depth research on stocks. The bot integrates various analysis tools, including company stats analyzers, fundamental stock analyzers, and news aggregators, etc to simplify the decision-making process and enhance trading efficiency.

It Address:
<ol>
  <li>Streamline the research process to save time.</li>
  <li>Simplify the learning curve for new traders.</li>
  <li>Provide better tools and resources for market analysis.</li>
  <li>Enhance accessibility to reliable market data.</li>
  <li>Offer more effective ways to identify and track stock trends..</li>
</ol>

## How we built it
**InvestiMate** was built using **Google Cloud's Vertex AI**. We created several agents to handle different aspects of stock analysis and learning:
![Workflow](https://res.cloudinary.com/dg5j2nhg7/image/upload/v1717384312/Investimate_Workflow_tg3wuk.png)

An Analysis Steering Agent that routes users query appropriate Agent. 
Stock Market Knowledge Base Agent (which has knowledge of 5 books)  guides users through the learning process by accessing a knowledge base of stock market fundamentals and with real-time examples.
Stock Analyzer Agent that aggregates and analyzes real-time data from various sources, including company stats, fundamental reports, market news, profit and loss, conference calls, etc.
These components work together to provide a seamless and integrated trading research work and learning experience, 

## Challenges we ran into

Throughout the development process, we encountered several challenges, including:
<ol>
  <li>Integrating multiple data sources into a cohesive system.</li>
  <li>Ensuring the accuracy and reliability of real-time data.</li>
  <li>Balancing the complexity of analysis tools with user-friendliness.</li>
</ol>

## Accomplishments that we're proud of

We are proud of successfully creating a functional prototype of InvestiMate that addresses the common problems traders face. The app effectively integrates real-time data analysis and educational resources, providing a comprehensive tool for traders. **_Furthermore, we have three clients who are willing to pay to use this service and are excited to utilize it for their research work._**

## What we learned
We found that using Vertex AI made it surprisingly easy to create and manage workflows, significantly simplifying the development process. 

I also learned how we can leverage Large Language Models (LLMs) to assist in problem-solving and streamline data analysis, which enhanced our ability to process and interpret vast amounts of information quickly.

## What's next for InvestiMate
The next steps for InvestiMate include:

As I mentioned, a few of my trader colleagues are excited to use InvestiMate in their daily analysis. The first priority is to create a user interface that provides a more seamless experience.

Following that, there is considerable scope to enhance the analysis power of this project by adding technical analysis indicators and incorporating more strategies. Additionally, we aim to expand data sources and improve the accuracy and breadth of the available data.

I plan to add advanced features such as predictive analytics and personalized recommendations. Furthermore, we will expand the educational resources to cover more advanced trading concepts. Conducting user testing to gather feedback and make iterative improvements is also on our agenda.

InvestiMate aims to continue evolving as a comprehensive tool that simplifies the stock trading process and empowers traders with the knowledge and tools they need to succeed.
