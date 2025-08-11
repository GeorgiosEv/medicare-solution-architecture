# 💻☁️ Capstone Project 3 - AWS Solution Architecture (Medicare) (2021)

Hereby find the project brief, objectives and requirements of Capstone Project 3.

## Purpose
The purpose of this project is to develop an Amazon Web Services (AWS) architecture to
solve a client’s problem.

## Problem
- Many companies have now realised the importance of implementing new digital systems that
would enable them to achieve higher operational excellence (i.e. higher productivity at lower
costs).
- However, they have neither the technical know-how nor the capability to invest in state-
of-the-art technology enabled machines.
- Currently, they are running their businesses using rudimentary IT systems.

They require your help in developing a solution that would help them solve the problem without
incurring a large bill. They have heard about **AWS** only in passing and have no in-depth
understanding of how the costings work. 

As Solution Architects, you are required to come up with an innovative solution built using any of the AWS services. 
As a team, you will be practicing the approach in creating a ***solution architecture*** in this project.

## Solution
1. Use the secondary brief (*see below* ⬇️) to architect a solution to the client’s problem using AWS services.
  - You need to draw a labelled and annotated diagram/flow chart of the different AWS services used and explain how they
will work together to solve the problem.
  - You do not have to physically create this system in AWS – you are just creating a visual guide to the services you would use.
2. Write a scientific report of no more than 1500 words (+/-10%) explaining your methodology, the services used and how they work, and how your solution fits the brief.
  - You should use appropriate references in the IEEE referencing style. The report should include screenshots of your entire architecture and the estimated costings that the business would incur if they were to implement the solution.
  - Use necessary assumptions when developing the costings. You should also explain how the company will implement and maintain this system (e.g. system upgrades, hiring extra staff members), and the long-term associated costs that this may incur.
  - Include any migration costs that the company may incur when moving to AWS.
3. Write and record a business presentation explaining your solution and the report. You must use a PowerPoint or equivalent software. You will be graded on your professionalism. The presentation should be no longer than 10 minutes.

## Deliverables
- A draw.io file, .pdf or similar file containing your entire architecture workflow.
- A .pdf of your report.
- The PowerPoint used in your presentation.

### SECONDARY BRIEF
MediCARE, a private health company based in Blackpool, has kickstarted a flu vaccination programme. As part of this programme, they aim to alert all patients with a pre-existing lung condition that they need to book a flu vaccination. Their patient database has 150,000 records and they estimate 25% of them will not have a pre-existing lung condition. All data is currently stored in their on-prem server.
1. Architect a solution that would allow the company to securely upload their patient database, select all patients who have a pre-existing lung condition, and send an email and a SMS notification to each patient with a link to an online message asking them to book an appointment. The admin staff must receive a report on patients who have not acknowledge the initial message on a weekly basis.
2. Create a database that shows a list of patients that have followed the link. The architecture must allow for creating forms, adding different kinds of forms, and for retrieving and creating reports as required.
3. Because of the sensitivity of the data, a backup must be encrypted stored in-house every day.
