# ai-review-configs
Centralized configurations storage for the [AI-Review tool](https://github.com/Nikita-Filonov/ai-review)

AI-Review configurations are focused on a single repository. This repository enhances origina AI-Review tool with ability to have 
single configuration which can be shared with number of your repositories.


## How to setup your repository
Add file "ai-review-deepseek-centralized-workflow.yml" to your repository into ".github/workflows/*.yml" folder and commit/push changes.

Setup GitHub secrets:
OPENAI_API_KEY - Deepseek token, can be requested by https://platform.deepseek.com/
PR_RW_TOKEN - GitHub token with read/write access to Pull Requests
