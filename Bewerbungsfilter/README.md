### Bewerbungsfilter (Application Filter)
A sophisticated email filtering system for job applications with three different approaches:

- **Keyword Version**: Simple but rigid filtering based on subject keywords like "Bewerbung" and "Job"
- **AI Version**: Uses Gemini API for intelligent classification with balanced cost-efficiency
- **AI Tools Version**: Advanced AI agent orchestration for maximum flexibility

Key features:
- Automated Gmail integration
- Smart classification of incoming emails
- Cost-effective AI implementation
- Customizable labeling system


## Implementation Details

### Application Filter Implementation
The application filter workflow demonstrates three different approaches to email filtering, from basic keyword matching to sophisticated AI implementation:

1. **Keyword Method**:
   - Simple subject line scanning
   - Fast and cost-effective
   - Limited flexibility

2. **AI Classification**:
   - Uses Gemini for full email analysis
   - Binary classification (YES/NO)
   - Optimal balance of intelligence and stability

3. **AI Tool Agent**:
   - Full AI orchestration
   - Maximum flexibility
   - Higher processing costs


#### Keyword Version Workflow
![Keyword Version Workflow](./filtering%20emails%20with%20regex.jpg)

#### AI Version Workflow
![AI Version Workflow](./filtering%20emails%20with%20ai.jpg)

#### AI Tools Version Workflow
![AI Tools Version Workflow](./filtering%20emails%20with%20ai%20tools.jpg)


## Getting Started

To use these workflows:

1. Create a qorkflow in n8n portal
2. Import the desired JSON workflow file
3. Configure your credentials for:
   - Gmail (for email workflows)
   - Google Docs (for newsletter workflow)
   - Gemini API (for AI features)
4. Customize the workflow parameters as needed