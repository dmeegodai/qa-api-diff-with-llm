# Postman + Hugging Face: AI-Powered API Diff Summarization

This project demonstrates how to combine Postman and Hugging Face's `facebook/bart-large-cnn` model to automatically:
- Compare API responses
- Generate diffs using JavaScript
- Summarize changes in plain English using an LLM

## How It Works
1. **GET Baseline Response** → Stored in collection variable `baseline_response`
2. **GET Updated Response** → Stored as `updatedResponse`
3. **Compare Responses** → Generates `response_diff` + `response_diff_summary`
4. **Send to Hugging Face** → AI returns a readable summary

# Example Output:
"Price changed from 9.99 to 9.991. Rating increased. Stock was removed."

## Includes
- Postman
- Hugging Face API token (free-tier supported)
- Internet connection to hit the Inference API



