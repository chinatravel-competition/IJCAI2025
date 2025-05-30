---
layout: page
title: Rules
background: grey
---


## Phase 1 - Preliminary Round:

- Devlopment on the [ChinaTravel Codebase](https://github.com/LAMDASZ-ML/ChinaTravel/tree/main)

    We have provided 5,000 samples with annotated DSL in the [released dataset](/#dataset-link). You can use them for local development and evaluation. 

- Local validation with provided evaluation scripts  

   Note that the Phase 1 testing will be conducted on 1,000 of these samples, and the corresponding data index is provided in TPC_IJCAI_phase1.txt of [released dataset](/#dataset-link). 

- Submit algorithm outputs through our submission portal
 
  CodaBench URL: 

  You need to submit a zip file containing multiple result files named {index}.json, where index corresponds to each index in the Phase1 data. Each .json file should contain the final result of travel planning using your method.  

- Monitor your scores on the Codabench leaderboard

- Top 50 teams advance based on validation scores. 

  Please complete the [registration](/#registration-form) before the Phase 1 Deadline (July 31, 2025 AOE). Teams that fail to register will be automatically disqualified from the competition. 

## Phase 2 - Semi-Final Round

- New challenge dataset (with the same format of Preliminary Round) release.

  The Dataset of Phase 2 will be released by July 31, 2025 AOE.

- Local validation with provided evaluation scripts

- Submit algorithm outputs through our submission portal

- Monitor your scores on the Codabench leaderboard

- <span style="color: white; background-color: #e74c3c; padding: 2px 8px; border-radius: 4px; font-weight: bold;">Important!</span> Code submission for official verification before the Phase 2 deadline

     The official verification will be conducted on an offline device with a 14-core Xeon(R) Gold 6348 CPU, 100 GB of RAM, an A800-80GB GPU, and a 50GB SSD. Drivers: 550.54.14, CUDA: 12.4. The Travel Agent needs to respond promptly to user requests. During the official evaluation, each query will be allocated 5 minutes of inference time. If the time limit is exceeded, the system will skip to the next query.  Please design your algorithm reasonably or use a timing mechanism to complete the planning within the given computing resources. The evaluation will be conducted offline. If your algorithm requires the use of a Large Language Model (LLM), please use open - source models such as Qwen3-8B/4B, Llama 3.1-8B, etc. Avoid using external APIs, such as DeepSeek API, GPT API, etc. We will repeat the evaluation five times and take the average of the overall scores as the final result. If there is a significant difference between the final result and the user's result on CodaBench, we will contact the participants for confirmation. Participation results that cannot reproduce the leaderboard results will be disqualified. 

- Top 10 teams advance to final round


## Phase 3 - Final Round

- Official Evaluation on the Private Dataset

    During the final round, the last submitted code from the semi-final round by the participants will be used, and no code modifications will be allowed. The organizing committee will conduct evaluations on the private dataset following the same process as the semi-final round to obtain objective score evaluations.

- Paper Submission Before the Phase 3 Deadline

    Papers should adhere to the IJCAI template. [The LaTeX styles and Word template are available here](https://www.ijcai.org/authors_kit). There is no page limit.
    The papers will be scored by five experts organized by the organizing committee, focusing on clarity and innovation. Scores will range from 0 to 100. The final subjective score will be the average of the five experts' scores.

- Official Results Announcement at IJCAI25

    The final ranking will be determined by comprehensively considering the objective score evaluation and the quality of the technical proposal at a ratio of 4:1. The organizing committee will announce the results at the satellite event in Guangzhou. All participants are warmly welcome to attend IJCAI25 and our competition! 