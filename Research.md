### These are prompts that I have utilized either to break down research papers or to utilize the critical reasoning capability of an LLM
***
Prompt 1:
***

Goal: Choose the best industry for career progression based on inclination towards problem statement<br>


Role: Act as a career advisor and machine learning (ML) expert specializing in labor market analytics. Your task is to systematically determine the ideal industry for a long-term career where ML is actively solving critical problems. Use Retrieval Augmented Generation (RAG) and strict fact-checking to ensure reliability.
Step 1: Industry Listing

Instructions:

    Generate an exhaustive list of 15–20 industries leveraging ML to solve problems.

    RAG Sources: Cross-reference at least 3 reputable sources per industry (e.g., McKinsey reports, IEEE journals, Gartner forecasts, or peer-reviewed case studies).

    Fact-Checking: Highlight industries with verified growth metrics (e.g., CAGR >10%, job market demand, R&D investment).

Step 2: Problem Statement Generation

Instructions:
For each industry, create 3 distinct problem statements per experience category:

    Entry-Level (e.g., data preprocessing, model monitoring)

    2–3 Years (e.g., optimizing pipelines, A/B testing)

    5+ Years (e.g., architectural design, regulatory compliance)

    10+ Years (e.g., enterprise strategy, ethical AI governance)

Requirements:

    Each statement must be 3–4 lines, specific (e.g., “Reducing false negatives in cancer detection via federated learning in healthcare”), and tied to real-world applications.

    Base problems on documented use cases (cite sources briefly in parentheses).

Step 3: Difficulty Rating

Instructions:
Rate each problem on a 1–10 scale using:

    1–3: Routine tasks (e.g., hyperparameter tuning).

    4–6: Cross-functional challenges (e.g., deploying ML in legacy systems).

    7–10: Strategic/ethical dilemmas (e.g., bias mitigation at scale).
    Ensure ratings span the full spectrum (e.g., each industry’s table includes at least one low, medium, and high rating).

Step 4: Tabular Output

Format:
Industry	Category	Problem Statement	Rating	Comments
…
Rules:

    Industry: Name + niche (e.g., “Healthcare – Medical Imaging”).

    Category: Experience level.

    Comments: Leave blank.

Quality Assurance Checks

    Accuracy: Validate all claims against sources like arXiv papers or IBM whitepapers.

    Diversity: Ensure no overlap in problem statements across industries.

    Clarity: Avoid jargon; explain technical terms concisely (e.g., “NLU” → “natural language understanding”).

Final Output:
A markdown table with 20–30 rows, prioritized by industries showing the strongest alignment with long-term ML innovation.

***
Prompt 2
***