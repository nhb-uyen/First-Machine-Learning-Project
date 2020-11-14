# First-Machine-Learning-Project

Link to Kaggle: https://www.kaggle.com/uyennghb/first-machine-learning-project/edit

# 1. Introduction
This document details the purpose, methodology, and application of data science within the [Project Name] system. Section 2 outlines the business objective addressed by the data science work, and defines the scope of the effort. Section 3 describes the data collected and utilized during analysis. Sections 4, 5, and 6 detail the methodologies employed, why they were selected, and how they are used and tuned (Section 4), trained (Section 5), and tested (Section 6). Finally, [any further sections that are added]

# 2. Problem Statement: Data Science Scope
## Business Case
The purpose of the project from a functional benefit perspective. Why are we building this? Who will benefit? And what benefit will they receive? How do you define success? The focus here should be on data science specifically, not just the project as a whole.

We are building a prediction algorithm for the Kiva loan project to identify the most needy communities and regions to give financial funding to. Individual funders and the Kiva fund planning team can look at the analysis, which inspects MPI index, historic amount of funding and correlation to economic development, and decide where to continue funding.

Success: when the algorithm can be applied for multiple regions with significant accuracy.
How do we know if the prediction is accurate? How to train the data?

## Key User Stories
A typical project will have a couple key user stories that describe the targeted data science outcome. A User Story captures what a user does or needs to do as part of their work. Each User Story consists of a short description (no more than a couple sentences) written from a user's point of view, with natural language. Unlike the traditional requirement capturing, User Stories focus on what the user needs instead of what the system should deliver. This leaves room for further discussion of solutions and the result of a system that can really fit into the customers' business workflow, solving their operational problems and most importantly adding value to the organization.

### User Story 1: Effective lending
Individual funders want to look at graphics that are easy to understand. The information they need is where funding has proven to be the most effective, whether it is to help African countries that have been through prolonged conflict, or densely populated Asian countries, or the Americas. The data needs to be able to show a history of positive correlation between the funding and economics development. 


### User Story 2: Detailed snapshot of funding diversity
Users would also want to see how many sectors they have an effect on, or will want to support in the future. This can be shown by categorizing funding amount by sector, gender, and use. Moreover, what are the sectors that need more support in a country.

### User Story 3: Kiva funding team
The team would want to know about lending terms and default practices to increase human resources or to enhance Kiva’s lending regulations and practices to ensure better security for funders. 
3. Data
