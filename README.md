# ML Playground

This is a playground repo where I test out Machine Learning, Deep Learning, NLP, and Big Data (PySpark) setups.


## Directory Structure

```text
MLPlayground/
├── DeepLearning/         # Neural networks, CNNs, and models deeper than my last existential crisis
├── MachineLearning/      # The classics: Regression, Decision Trees, and K-Means
├── NLP/                  # Text processing and language stuff because human language is messy
└── PySpark/              # Big data filtering and modeling when pandas starts crying
```

## Setup Instructions

### 1. Prerequisites

Make sure you have Python 3.11 or higher installed. This project uses `uv` to handle dependencies, which you'll need to install if you haven't already:

```bash
pip install uv
```

### 2. Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/MLPlayground.git
cd MLPlayground

# For modules using uv (DeepLearning, NLP, PySpark)
uv sync

# For modules using pip (MachineLearning)
pip install -r MachineLearning/requirements.txt
```

### 3. Environment Variables

Create a `.env` file in the `DeepLearning` directory and add your credentials.

```env
DAGSHUB_TOKEN="your-dagshub-token"
AWS_ACCESS_KEY_ID="your-aws-access-key-id"
AWS_SECRET_ACCESS_KEY="your-aws-secret-access-key"
# Add other keys depending on the models you use:
# GOOGLE_API_KEY="your-google-gemini-api-key"
```

## Contributing

This is mainly a personal sandbox project, but feel free to open a PR or issue if you have suggestions or find bugs, or if there's an interesting pattern you'd like to share.
