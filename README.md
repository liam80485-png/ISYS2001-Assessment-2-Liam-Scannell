## Smart Finance Assistant (AI-Powered)

An AI-powered finance assistant that helps users understand spending patterns, convert currencies, and receive personalised financial insights. Built using Python, Pandas, and Gradio, with AI agent integration and simple RAG-based knowledge retrieval.

---

## What This Assistant Does

- Analyses transaction data from CSV files  
- Converts expenses between currencies  
- Generates spending insights and patterns  
- Provides personalised financial recommendations  
- Uses an AI agent (“Finny”) for financial advice  
- Retrieves helpful financial knowledge (RAG system)  
- Includes a simple Gradio user interface  

---

## Sample Inputs

### Transaction Data (CSV)
| Date       | Amount  | Category      | Description        |
|------------|--------|---------------|--------------------|
| 2024-12-20 | 850.00 | Flights       | Flight to Bali     |
| 2024-12-21 | 120.50 | Dining        | Airport Dinner     |
| 2024-12-22 | 250.00 | Accommodation | Hotel Stay         |

### Currency Conversion
- From: USD  
- To: EUR  
- Amount: 100  

### User Question (AI Chat)
> "How can I reduce my travel spending?"

---

## Sample Outputs

### Spending Analysis
- Total Spending: $1341.25  
- Top Category: Flights  
- Average Transaction: $268.25  

### Insights
- Flights are the highest spending category  
- Dining and accommodation also contribute significantly  
- Consider booking flights early to reduce costs  

### Currency Conversion
> 100 USD → 92 EUR (example)

### AI Advice (Finny)
> "Try booking flights in advance and tracking daily expenses to reduce overspending during travel."

---

## How to Run

### 1. Install Requirements
```bash
pip install pandas gradio hands-on-ai
