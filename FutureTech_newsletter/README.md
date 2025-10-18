### FutureTech Newsletter
An automated tech newsletter generation and distribution system featuring:

- Automated content generation using Gemini 2.5 Flash
- Duplicate prevention through Google Docs integration
- HTML email formatting
- Automated distribution
- Topic tracking and management

## Implementation Details

### FutureTech Newsletter Implementation
The newsletter automation workflow creates and distributes tech-focused content:

1. **Content Management**:
   - Retrieves existing articles from Google Docs
   - Prevents content duplication
   - Maintains topic freshness

2. **AI Content Generation**:
   - Creates 300-400 word articles
   - Focuses on cutting-edge tech topics
   - Automated HTML formatting

3. **Distribution**:
   - Automated email dispatch
   - AI-generated subjects and messages
   - Google Docs synchronization


#### FutureTech Newsletter Workflow
![FutureTech Newsletter Workflow](./FutureTech%20workflow.jpg)

![FutureTech Newsletter Output](./example_futureTech%20email.jpeg)


## Getting Started

To use these workflows:

1. Create a qorkflow in n8n portal
2. Import the desired JSON workflow file
3. Configure your credentials for:
   - Gmail (for email workflows)
   - Google Docs (for newsletter workflow)
   - Gemini API (for AI features)
4. Customize the workflow parameters as needed