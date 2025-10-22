<h1 align="center"> CS-405 </h1>
<p align="center"> Secure Coding </p>

<p align="center">
<img alt="image" src="snhu.png" width="150" height="150" />
</p>

## Table of Contents
- [Course Description](#course-description)
- [Project One](#project-one)
- [Project Two](#project-two)
- [Portfolio Reflection](#portfolio-reflection)

## <h1 align="center"> Course Description </h1>
Students will focus on common security vulnerabilities that are
found in software. Students will learn techniques and strategies
to develop robust and secure code, leveraging secure
programming principles. Students will gain authentic experience
identifying security vulnerabilities and writing secure code to
mitigate risks to software and data.

## <h1 align="center"> Project One </h1>
<p align="center"> Security Policy </p>
Scenario
You are working as a developer for a software company called Green Pace. It is an engineering company that specializes in custom software design and development for environmentally responsible entrepreneurs worldwide. At Green Pace, the security mission is defense in depth. In order to ensure that all applications comply with the same security policies, you have been tasked with documenting, categorizing, and providing examples for coding and architectural vulnerabilities. Green Pace wants to maximize automation to ensure compliance and keep costs down. Essentially, the company is moving its DevOps practice to a DevSecOps to make it more secure, and the company wants to be well prepared for the security audit. The image below shows how, in DevSecOps, security is a separate and equally veiled function supporting development, operations, and application delivery. In order to complete this project, you need to understand potential vulnerabilities and weaknesses in code and coding best practices. In addition, you will need to be able to understand how to develop secure code to counteract threats.

## <h1 align="center"> Project Two </h1>
<p align="center"> Presentation </p>
Scenario
You have been asked to present the Green Pace security policy guide and to provide implementation guidelines and recommendations for maintaining it in the future. The developers have been employing best practices and, as the team grows, it’s critical that everyone remains in sync with principles and best practices. Your job is to take the implicit policies that are applied daily in practice and explain how they have been standardized. You will explain your Green Pace security standards and policies, including the surface area of an attack and assumption of vulnerability. It is your job to demonstrate how the coding and architectural issues are organized using a set of 10 guiding security principles. You will demonstrate how you apply external testing methods to identify potential vulnerabilities by adding screenshots from your coding exercises and explaining how external testing methods will catch the vulnerabilities. You will be writing unit tests to check for the vulnerabilities using the unit testing framework for C++ in Visual Studio.

## <h1 align="center"> Portfolio Reflection </h1>
<p align="center"> Adoption of a secure coding standard, and not leaving security to the end </p>
The idea os a secure coding standard means that you implement a full life-cycle dedicated to security along side your main coding life-cycle. Leaving security until the end will indeed cause issues during post production. One you have completed the codebase, having to then implement security policies into this codebase will be difficult and bugs will arrise during a period of time where it's most vulnerable. If you dedicate to ensuring security is implement at each step, you will produce a far more secure codebase compared to leaving until the end. This step starts in the very beginning when you obtain the user story, analize what security vulnerabilites there could be before you begin to plan the code itself. If you can predict what vulnerabilites could potentially be an issue, you will plan your code around these to patch them before they are vulnerable.


<p align="center"> Evaluation and assessment of risk and cost benefit of mitigation </p>
There are thousands of various vulnerabilities in every code, it is important to evaluate them from highest to least important. This evaluation is based off of the risk factor (how likely is it that this vulnerability could be used) and the mitigation cost (how long would it take to mitigate this risk). If you put time and effort (which equates to more money) into all of the small bugs, you may run out of time to patch the higher risk vulnerabilities. Perhaps there are vulnerabilites where the risk factor is nearly non-existant (but still possible) and hard to patch, you don't want to be working on this one first. Planning a document that assesses these risks then begin mitigation is the most important action.


<p align="center"> Zero trust </p>
The idea of Zero Trust means everyone is at risk, never think your program is not at risk; "No one is safe". There are various motives for an attack which include but not limited to:

1. Financial gain

2. Recognition
   
3. Insider Threats
   
4. Political Motivation
   
5. State Actors
   
6. Corporate Espionage
* according to CoreTech in 2022.
If you keep the idea that everyone is at risk, you can plan ahead by utilizing what motives an attacker may have to patch possible vulnerabilities.

<p align="center"> Implementation and recommendations of security policies </p>
It is important to implement that Triple A framework and encrypting, this means encryption at rest, in flight and in use. Secondly the Triple-A framework means you have authentication, authorization and accounting for activity. Implementing these two policies will bring the codebase a long way with security.
