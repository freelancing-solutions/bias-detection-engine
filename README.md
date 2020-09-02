# Bias Diagnostics Engine 

This solution starter was created by technologists from IBM.

## Table of Content

1. [The Team](#1-the-team)
2. [Overview](#2-overview)
3. [Video](#3-video)
4. [The idea](#4-the-idea)
5. [How it works](#5-how-it-works)
6. [Diagrams](#6-diagrams)
7. [Documents](#7-documents)
8. [Datasets](#8-datasets)
9. [Technology](#9-technology)
10. [Getting started](#10-getting-started)
11. [Resources](#11-resources)
12. [License](#12-license)

## 1. The Team

* Denise Knorr - Product Manager
* Boz Handy Bosman - AoT Master Inventor (AIF360)
* Sam Hoffman - AIF360 Developer
* Margriet Groenendijk - Data & AI Developer Advocate   
* Hema Veeradhi - Red Hat Software Engineer    
* Kate Tereshchenko - Cloud Data Scientist 
* Ann Marie Fred - CFC Sentencing Reform Team 
* Demi Ajayi - Prod Designer – AI Natural Language 
* Otis Smart - AI Data Scientist - Machine Learning 

## 2. Overview
#### IBM Racial Disparity & Bias Diagnostics Engine

* Powered by IBM’s [AI Fairness 360](https://github.com/Trusted-AI/AIF360) sourced functionality
* Refined to specifically isolate racial disparity in technology enabled outcomes
* Diagnose bias related causes for the disparity to recommend remediation
* Monitor outcomes for effectiveness at minimizing bias and racially motivated disparity 

### Problem statement

A new class of “anti-bias / anti-Systemic Racism” solutions (aka Call for Code EmbRace solutions) strives to have outcomes that can be mathematically assessed and validated as “Bias Free” 

1. This new class of solutions that prioritize the minimization of outcomes infected by implicit racial bias will need leading edge technology and newly developed interface protocols that can effectively serve as a universally accepted fair and “Credible Arbiter” of bias and other variables that might negatively contribute to racially-driven disparity in outcomes.

2. Without validated and benchmarked models for consistent attribution and remediation of bias, the full range of new and innovative anti-bias solutions will have diminished ability to deliver outcomes that are universally seen as mathematically and repeatably accurate in diagnosing and remediating bias. 
    *	A random / one-off approach to detecting and remediating bias will not be sufficient to drive outcomes accepted / acknowledged as bias-free across a large ecosystem of a new class of anti-bias solutions 

3.	Furthering the problem is that effects of bias can be fed into a single solution’s outcomes via multiple inputs / steps in that single solution’s processes, while at the same time some steps or processes associated with the solution’s outcome may be mathematically bias-free or neutral.  
    *	This means that the bias diagnostics capabilities need to be sufficient to assess the *cumulative* effect of *multiple* sources of bias throughout the entire “process pipeline” within a single solution, so that if any single “bias-infected” input source or data set within the solution’s process pipeline goes undiagnosed, the outcome may still reflect elements of racial bias. In other words, neutral processes are not sufficient in-and-of themselves to prevent implicit racial bias from infecting a solution’s outcomes. 
  
### How can Technology Help 

1. By leveraging existing (enhanced) IBM technologies like AI Fairness 360, IBM can provide benchmarked hardened models and interface protocols for disparity and bias diagnostics functionality (**aka a full functioning Bias Diagnostics Engine**) that can be universally applied via Open source cloud enablement by a varied range of internal and external 3rd party solutions targeting bias-free outcomes.

2. IBM technology can serve as a scientifically sourced “credible” arbiter of disparity and racial bias by leveraging IBM’s unique and deep brain-trust of research and expertise needed to adequately assign algorithms sufficient to digitize and quantify bias infused context and concepts. 

3. Privacy Preserving will be required due to the nature of most data sets, so IBM cloud Security will be a critical technology enabler for this new class of anti-bias / anti-racism solutions and required for the Bias Engine to function optimally since many of the most relevant data sets needed are those that will require maximum levels of security and privacy similar to the levels of security IBM provides to Financial and Public Sector solutions and platforms. 

## 3. Video

[video placeholder]

## 4. The Idea

![Elevator pitch](https://github.com/MargrietGroenendijk/bias-detection-engine/blob/master/figures/Bias%20Engine%20-%20How%20it%20Works%20Sep%201.png)

### Proposed Solution
Our solution has the following key personas:

![Personas](https://user-images.githubusercontent.com/7343099/90186037-8fbae300-dd85-11ea-8f00-6b2c523c3c93.png)

The main persona in our solution is the recruiter who is attempting to identify candidates. 

### User Insights

![User-Insights](https://user-images.githubusercontent.com/7343099/90186269-e7594e80-dd85-11ea-841c-6818b039b8ca.png)

## 5. How it works

![How it works](https://github.com/MargrietGroenendijk/bias-detection-engine/blob/master/figures/Screen%20Shot%202020-09-01%20at%2012.45.58%20PM.png)

### Overall Architecture

Our solution aims to have a web UI that takes in HR data (in our case, simulated data), and allows for query, selection, presentation, and visualization of that data. The critical components of our solution that we hope to provide insights on include: a visualization to represent the seven-step hiring process, a statistical analysis to indicate bias, and a simulation to model what fair results would look like. 

![Architecture](https://user-images.githubusercontent.com/7343099/90186448-2c7d8080-dd86-11ea-9fe2-e5e12a181888.png)

## 6. Diagrams

### Hiring Funnel 

Systemic racism is a structural input into the hiring funnel, leading to disparities in the outputs. The hiring process is a seven-step process that includes: sourcing, application, screening, shortlist, hiring manager/interview, offer/negotiation, and candidate decision. In this solution we are not directly addressing the sourcing step, but rather focusing on the pipeline from application to being hired or dispositioned. Our hope is that by showing bias at each step along the pipeline, we can help companies understand why they may not be achieving the diversity they desire in their employee base.  

![Hiring Funnel](https://github.com/MargrietGroenendijk/bias-detection-engine/blob/master/figures/Funnel%20-%20Bias%20Filtering%20processes%20-%20Sep%201.png)

## 7. Documents

We have created some initial data science exploratory notebooks [here.](https://github.com/embrace-call-for-code/bias-detection-engine/tree/master/notebooks)
The notebooks analyze the sample HR/Judicial data sets to depict the bias in various stages of either HR recruiting process or legal procedure for the Black community.

## 8. Datasets

The data sets used in our initial analysis/notebooks can be found [here.](https://github.com/embrace-call-for-code/bias-detection-engine/tree/master/data)

The input HR data has been generated by our team due to privacy concerns surrounding real data. Each row in the dataset gives the applicant’s race, gender, application date, and dates for each subsequent step in the hiring process they have achieved (shortlist, interview, offer, hire). If an applicant is not hired, a date will be given for their disposition from the hiring process.  

Our model uses data from three sources of bias: 

* Adding additional bias landing at ~3% Black hires 
* No additional bias in the funnel, landing at ~7% Black hires 
* Remediation in the funnel, landing at ~13% Black hires.

We have also generated judicial data to mock real-world scenarios. Each row in the dataset gives the crime elements identified in the crime, the defendant's race, sentencing length and the corresponding step in the legal process such as **Investigation, Plea Bargaining, Pre-Trial Motions.**

## 9. Technology

1. Blockchain to establish consensus about data sharing
2. Accountability Scoring
3. Clean Media Ecosystem Container – Bias detection + Misinformation flagging + Misinformation filters + Accountability Scores

### Extending the Bias Engine

Apart from HR hiring data, we can also apply the bias detection to the Judicial system. People in the Black community are faced with harsher downstream effects (charged at higher rates, assigned more significant charges, convicted at higher rates, given longer sentences, and denied parole more often) than people of other races for similar offenses. 

## 10. Getting started

## 11. Resources

## 12. License



















