# n8n-automation-workflows

This repository contains a collection of my experimental automation workflows built with n8n, demonstrating practical applications of automation and AI integration in business processes.

## Some of my Workflows

### 1. Bewerbungsfilter (Application Filter)
A sophisticated email filtering system for job applications with three different approaches:

- **Keyword Version**: Simple but rigid filtering based on subject keywords like "Bewerbung" and "Job"
- **AI Version**: Uses Gemini API for intelligent classification with balanced cost-efficiency
- **AI Tools Version**: Advanced AI agent orchestration for maximum flexibility

Key features:
- Automated Gmail integration
- Smart classification of incoming emails
- Cost-effective AI implementation
- Customizable labeling system

#### Keyword Version Workflow
![Keyword Version Workflow](/Gmail_label_filtering/filtering%20emails%20with%20regex.jpg)

#### AI Version Workflow
![AI Version Workflow](/Gmail_label_filtering/filtering%20emails%20with%20ai.jpg)

#### AI Tools Version Workflow
![AI Tools Version Workflow](/Gmail_label_filtering/filtering%20emails%20with%20ai%20tools.jpg)

### 2. FutureTech Newsletter
An automated tech newsletter generation and distribution system featuring:

- Automated content generation using Gemini 2.5 Flash
- Duplicate prevention through Google Docs integration
- HTML email formatting
- Automated distribution
- Topic tracking and management

#### FutureTech Newsletter Workflow
![FutureTech Newsletter Workflow](/FutureTech_newsletter/FutureTech%20workflow.jpg)

![FutureTech Newsletter Output](/FutureTech_newsletter/example_futureTech%20email.jpeg)


### 3. Book Summarizer Workflow
An intelligent book summarization system with two different approaches:

- **External State Version**: Utilizes external state management for efficient book processing
- **Node Static Data Version**: Uses n8n's built-in static data, Simple implementation

Key features:
- Automated book processing
- Intelligent summarization
- State management for large documents
- Node Static Data

#### External State Version Workflow
![External State Version](/Book_summarizer//Book-Summarizer%20with%20Code%20Node%20and%20Extern%20State.jpg)

#### Node Static Data Version Workflow
![Node Static Data Version](/Book_summarizer/Book-Summarizer%20with%20node%20static%20data.jpg)


## Getting Started

To use these workflows:

1. Create a qorkflow in n8n portal
2. Import the desired JSON workflow file
3. Configure your credentials for:
   - Gmail (for email workflows)
   - Google Docs (for newsletter workflow)
   - Gemini API (for AI features)
4. Customize the workflow parameters as needed

## Notes

- These workflows are experimental and may need adjustments for your specific use case
- API costs should be considered when implementing AI-based solutions
- Regular monitoring is recommended for optimal performance

## License

This project is open-source and available for reference and learning purposes.