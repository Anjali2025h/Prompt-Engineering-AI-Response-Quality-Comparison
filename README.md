# Prompt Engineering & AI Response Quality Comparison Study

## Project Overview

This project investigates how prompt design influences the quality of AI-generated responses.

The study compares two versions of prompts for the same task:

1. **Initial Prompt** — a relatively simple or less-constrained prompt.
2. **Improved Prompt** — a redesigned prompt containing clearer instructions, context, formatting requirements, audience specifications, examples, or other task-specific constraints.

The objective is to determine whether improved prompt design leads to measurable improvements in AI response quality and instruction following.

---

## Project Objectives

The main objectives of this project are to:

- Design and test multiple AI tasks using different prompt versions.
- Create initial prompts for each task.
- Analyze weaknesses and limitations in initial prompts.
- Develop improved versions of the prompts.
- Compare AI responses generated from initial and improved prompts.
- Evaluate response quality using a standardized evaluation rubric.
- Identify prompt-engineering techniques associated with improved responses.
- Analyze cases where prompt improvements produced limited or no improvement.
- Document the findings in a structured analytical report.

---

## Research Question

> How does adding explicit instructions, context, formatting requirements, audience specifications, and output constraints affect the quality and instruction-following performance of AI-generated responses?

### Additional Research Questions

- Do improved prompts produce higher-quality responses?
- Which prompt-engineering techniques produce the greatest improvements?
- Does specifying the intended audience improve clarity?
- Does specifying an output format improve instruction following?
- Do length constraints improve response quality?
- Can excessive instructions negatively affect response quality?
- Are there situations where the initial prompt performs equally well or better?

---

# Dataset

The dataset contains **30 tasks across 10 categories**.

Each task was tested using two prompt versions, resulting in:

- **30 initial prompts**
- **30 improved prompts**
- **30 initial AI responses**
- **30 improved AI responses**
- **60 total AI responses**

### Task Categories

| Category              | Number of Tasks |

| General Knowledge     | 3 |
| Science               | 3 |
| History               | 3 |
| Technology            | 3 |
| Business              | 3 |
| Education             | 3 |
| Writing               | 3 |
| Reasoning             | 3 |
| Instruction following | 3 |
| Ambiguous Questions   | 3 |
| **Total**             | **30** |


# Experimental Design

The experiment followed a controlled comparison between initial and improved prompts.

### Stage 1 — Initial Prompt

A relatively simple prompt was created for each task.

### Stage 2 — Initial AI Response

Each initial prompt was submitted to the selected AI model and the resulting response was recorded.

### Stage 3 — Prompt Improvement

Each initial prompt was analyzed and redesigned using appropriate prompt-engineering techniques.

### Stage 4 — Improved AI Response

Each improved prompt was submitted to the same AI model and the resulting response was recorded.

### Stage 5 — Evaluation

Both responses were evaluated using the same standardized evaluation rubric.

### Stage 6 — Comparison

The scores and qualitative observations were compared to determine whether the improved prompt produced a better response.

---

# Prompt Engineering Techniques

The improved prompts used task-appropriate techniques such as:

### 1. Audience Specification

Specifying who the response is intended for.

**Example:**

> Explain machine learning to a beginner.

---

### 2. Output Format Specification

Defining the required structure or format of the response.

**Example:**

> Compare Python, SQL, and Excel in a table.

---

### 3. Length Constraints

Specifying the desired response length.

**Example:**

> Explain photosynthesis in approximately 100 words.

---

### 4. Explicit Requirements

Clearly identifying information that must be included.

**Example:**

> Include sunlight, water, carbon dioxide, glucose, and oxygen.

---

### 5. Context

Providing additional information about the purpose or audience of the task.

**Example:**

> Explain cloud computing to someone with no technical background.

---

### 6. Structured Instructions

Breaking a task into clear requirements or steps.

**Example:**

> Define the concept, explain how it works, provide two examples, and summarize the main benefits.

---

### 7. Examples

Where appropriate, examples may be provided to guide the expected response format or style.



# Evaluation Methodology

Each AI response was evaluated using a standardized rubric.

The evaluation used a **1–5 scoring scale** across six criteria:

1. Relevance
2. Completeness
3. Clarity
4. Instruction Following
5. Specificity
6. Overall Quality

Each criterion received a score from **1 to 5**.

Therefore:

**Maximum score per response = 30 points**

---

# Evaluation Criteria

## Relevance

Measures whether the response directly addresses the requested task.

|Score| Description |

| 1  | Response is largely unrelated to the prompt. |
| 2  | Some relevant information is provided but the response frequently goes off-topic.|
| 3  | The main topic is addressed but some unnecessary information is included. |
| 4  | Response is focused and mostly addresses the requested task. |
| 5  | Response directly and consistently addresses the task. |

---

## Completeness

Measures whether the response adequately addresses the requirements of the prompt.

| Score | Description |

| 1 | Major parts of the task are missing. |
| 2 | Several important requirements are missing. |
| 3 | Main task is addressed but some relevant information is missing. |
| 4 | Most requested information is included. |
| 5 | All important requirements are adequately addressed. |

---

## Clarity

Measures how easy the response is to understand.

Factors considered include:

- Organization
- Sentence structure
- Vocabulary
- Logical flow
- Readability
- Explanation quality

| Score | Description |
|---:|---|
| 1 | Very difficult to understand or poorly organized. |
| 2 | Frequently unclear or confusing. |
| 3 | Generally understandable but contains some unclear sections. |
| 4 | Clear, organized, and easy to understand. |
| 5 | Exceptionally clear, logical, and easy to understand. |

---

## Instruction Following

Measures whether the AI followed the specific instructions contained in the prompt.

Instructions may include:

- Word limits
- Number of items
- Requested format
- Intended audience
- Tone
- Structure
- Required information
- Restrictions

| Score | Description |
|---:|---|
| 1 | Almost none of the instructions were followed. |
| 2 | Several important instructions were ignored. |
| 3 | Some instructions were followed but important requirements were missed. |
| 4 | Most instructions were followed correctly. |
| 5 | All major instructions were followed correctly. |

---

## Specificity

Measures whether the response provides an appropriate level of detail and directly addresses the specific requirements of the task.

| Score | Description |
|---:|---|
| 1 | Extremely vague and provides little useful information. |
| 2 | Mostly general with limited useful detail. |
| 3 | Provides reasonable detail but could be more specific. |
| 4 | Provides useful and task-appropriate detail. |
| 5 | Highly specific, precise, and well-targeted to the prompt. |

---

## Overall Quality

Measures the evaluator's overall assessment of the usefulness and quality of the response.

| Score | Description |
|---:|---|
| 1 | Very poor response. |
| 2 | Poor response with significant weaknesses. |
| 3 | Acceptable response with noticeable limitations. |
| 4 | Good response with minor weaknesses. |
| 5 | Excellent response that effectively satisfies the task. |

---

# Results

The following table should contain the actual average scores calculated from the completed dataset.

| Evaluation Criterion  | Initial Prompts | Improved Prompts | Difference |

| Relevance             | 4               | 4.5              | 0.5 |
| Completeness          | 3.5             | 4.2              | 0.7 |
| Clarity               | 3.5             | 4.5              | 1 |
| Instruction Following | 3.8             | 4.4              | 0.6|
| Specificity           | 3.9             | 4.3              | 0.4 |
| Overall Quality       | 3.8             | 4.4              | 0.6 |

### Overall Result

> The average overall quality score changed from **3.8/5** for initial prompts to **4.4/5** for improved prompts, representing an average improvement of **0.6 points**.

---

# Prompt Technique Analysis

The project analyzes which prompt-engineering techniques were associated with the greatest improvements in response quality.


| Prompt Technique         | Tasks Using Technique | Average Improvement |

| specify the Audience     | 9                     | 4 |
| specify Output format    | 1                     | 3.9 |
| specify length           | 4                     | 3.8 |
| Give a role/purpose      | 5                     | 4 |
| Give Explicit requirements| 4                    | 4.5 |
| provide Examples         | 4                     | 4 |
| add Context              | 2                     | 4 |
| add Constraint           | 5                     | 4.2 |
| defined the rule         | 7                     | 4 |
| request step-by-step     | 1                     | 4 |
| handle ambiguity         | 1                     | 4.5 |


# Successful Prompt Improvements


## Example 1 — Machine learning

Initial Prompt: 
      Explain machine learning. 

Improved Prompt:
      Explain machine learning to a beginner using simple English. Include a definition, how it works at a high level, and two everyday examples. 

 Initial Score: 3.6/5
 Improved Score: 4.4/5

Analysis:
       In improved prompt specify what is the level of user on this topic and ask for example and asking for simple language.

---

## Example 2 — GPS

Initial Prompt:
         Explain how GPS works. 

Improved Prompt:
         What is GPS ? explain the GPS in detail to 12 year old kid in simple word, explain what is the use of it and how GPS works. 

 Initial Score: 3.8/5
 Improved Score: 4.5/5

Analysis:
        Specify the audience and define the language and give explicit requirement.

---

# Unsuccessful or Limited Improvements

Identify cases where:

**Improved Score ≤ Initial Score**

For each case, explain why the improved prompt did not produce a meaningful improvement.

Possible factors may include:

- Excessive instructions
- Conflicting requirements
- Unclear wording
- Unnecessary constraints
- The initial prompt was already sufficiently clear
- The AI misunderstood an instruction
- Additional constraints reduced useful information

Example

Initial Prompt:
      How can students improve their memory?  

Improved Prompt:
      Give five evidence-based strategies for improving learning and memory. Explain each strategy in 1–2 sentences and avoid making medical claims.  

 Initial Score: 3.8/5
 Improved Score: 3/5

explanation:
    The improved prompt added multiple formatting and length restrictions. Although the response followed the requested format, the additional constraints reduced the amount of useful information provided.

---

#Dataset Structure

The main dataset contains information such as:

| Field             | Description                     |
| ----------------- | ------------------------------- |
| Task ID           | Unique identifier               |
| Category          | Task category                   |
| Task              | Description of the task         |
| Initial Prompt    | Original prompt                 |
| Improved Prompt   | Revised prompt                  |
| Initial Response  | AI response to initial prompt   |
| Improved Response | AI response to improved prompt  |
| Initial Score     | Overall initial response score  |
| Improved Score    | Overall improved response score |
| Improvement       | Difference between scores       |
| Prompt Technique  | Technique used                  |

---

# Key Findings

Finding 1
Improved prompts perform better overall.
Finding 2
 Explicit requirements technique produced the largest improvement.
Finding 3
technology and history category benefited most.
Finding 4
Education category showed the smallest improvement.
Finding 5
In Education category the improved prompt performed worse.
Finding 6
Give Explicit requirements and Context type of instruction did the AI follow most reliably.
Finding 7
Evidence based instruction caused the most problems.

---

# Limitations

This project has several limitations:

- The dataset contains a limited number of tasks.
- The evaluation was conducted by a single evaluator.
- Results may differ when using another AI model.
- AI models may change over time.
- Task selection may influence the results.
- Some evaluation criteria involve subjective judgment.
- Results from this project should not be interpreted as universally applicable to all AI models or tasks.

---

# Quality Assurance

The following quality-assurance practices were used:

- The same evaluation criteria were applied to both prompt versions.
- Initial and improved responses were evaluated using the same scoring scale.
- Prompt versions were kept clearly separated.
- Evaluation comments were recorded for significant observations.
- Scores were reviewed for obvious inconsistencies.

---

# Conclusion

This project examined the effect of prompt engineering on AI-generated response quality across 30 tasks. The experiment compared responses generated from initial prompts with responses generated from improved prompts containing more explicit instructions and task-specific constraints.

Based on the evaluation results, improved prompts did produce higher average response quality. The techniques that showed the strongest improvement were Give Explicit requirements, while specify Output format showed more limited benefits.

The analysis also demonstrated that effective prompt engineering is not simply about making prompts longer. The usefulness of a prompt depends on providing relevant context, clear requirements, appropriate constraints, and a well-defined expected output.

The project strengthened practical skills in prompt engineering, LLM output evaluation, data analysis, critical thinking, and AI quality assessment.

---

# Skills Demonstrated

This project demonstrates practical skills in:

- Prompt Engineering
- LLM Output Analysis
- AI Response Evaluation
- Data Collection
- Data Annotation
- Comparative Analysis
- Quality Assurance
- Critical Thinking
- Research Methodology
- Experimental Design
- Data Analysis
- Technical Documentation

---

# Tools Used

Example:

- Chat GPT
- Google Sheets
- Google Docs
- GitHub

---

Conclusion

This project demonstrates a structured approach to improving AI prompts and measuring the resulting changes in AI-generated response quality.

Rather than assuming that a more detailed prompt automatically produces a better response, the project uses systematic evaluation and comparison to investigate which prompt-engineering techniques are effective for different types of tasks.

The findings will provide practical insights into prompt design, AI response evaluation, instruction following, and AI output quality assessment.

---

Author
ANJALI

Prompt Engineering & AI Response Quality Comparison Study
