## AI Adoption and Consumer Complaint Analysis

This project examines how financial institutions’ use of AI-enabled customer service tools (e.g., chatbots) relates to patterns observed in U.S. consumer complaints.

### Overview

The objective is to link AI adoption by firms with large-scale complaint data and study how complaint characteristics differ across firms and users.

### Main Steps

**1) Data Collection & Cleaning**

- Import CFPB complaint data (2016–2023).

- Standardize company names, filter relevant cases, and clean text fields.

**2) Identifying AI Adoption**

- Build an automated GPT-based search pipeline to determine whether and when each company introduced AI/chatbot capabilities.

- Apply the pipeline across the list of ~230 financial institutions.

**3) AI Labeling of Complaints**

- Use GPT-generated labels to identify whether each complaint likely involved an AI interaction.

- Construct a labeled dataset (~30k rows) to support further text analysis.

**4) Descriptive Analysis**

- Compare companies that adopted AI vs. those that did not on complaint volumes, topics, and text-based features.

- Analyze differences between AI-labeled and non–AI-labeled complaints within adopting firms.

**5) Text and Heterogeneity Analysis**

- Perform sentiment and tone classification on complaints.

- Merge complaints with ZIP-code–level census variables to study heterogeneity across user characteristics (e.g., income or demographic composition).
