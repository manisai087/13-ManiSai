## Problem Statement:
The problem is to build a system that automatically transforms structured financial statement data—such as income statements,
balance sheets, and cash flow tables—into a clear, sectioned Management Discussion & Analysis (MD&A) narrative that explains
financial performance changes across periods, highlights key trends and risks, and grounds every explanation in relevant historical 
disclosures with proper citations, producing a reliable first-draft document that is accurate, explainable, and suitable for human review.
## What Our Project Does:

Our project reads SEC financial statement data, analyzes the numbers, and automatically generates an MD&A draft in simple professional language.

The system:

* Reads financial data from SEC filings
* Calculates *Year-over-Year (YoY)* changes
* Converts numbers into meaningful financial sentences
* Uses AI to generate a *well-structured MD&A section*
* Saves the output as a readable report file

This is meant to be a *first draft*, not a final report.

## How the System Works (Simple Flow)

1. Load financial data from SEC dataset
2. Calculate growth metrics (YoY)
3. Convert financial results into text statements
4. Store statements in a vector database
5. Use AI to generate an MD&A narrative
6. Save the output as a Markdown file


## Technologies Used

* Python
* Pandas
* LangChain
* OpenAI API
* FAISS (Vector Database)


## Project Structure

<img width="510" height="166" alt="image" src="https://github.com/user-attachments/assets/1bc1e7b5-ae02-405a-b0c8-8e43458c9652" />


## How to Run the Project (VS Code)

1. Open the project folder in *VS Code*
2. Install required libraries:

   bash
   pip install -r requirements.txt
   
3. Add your OpenAI API key inside main.py
4. Run the project:

   bash
   python main.py
   
5. After execution, open output_mdna.md

   * Press *Ctrl + Shift + V* to view Markdown preview

## Output

The output is a generated MD&A draft that explains:

* Revenue trends
* Growth patterns
* Financial performance overview

The output file can be:

* Reviewed by humans
* Edited further
* Exported to reports

## Why This Project is Useful

* Reduces manual effort in report writing
* Improves consistency in financial explanations
* Scales easily for multiple companies
* Helps analysts focus on insights instead of writing

## Limitations

* This generates only a *first draft*
* Requires human validation
* Depends on quality of financial data

## Conclusion

This project shows how *financial analytics and AI* can be combined to *automate report drafting*.
It is a small step toward smarter and faster financial reporting.
