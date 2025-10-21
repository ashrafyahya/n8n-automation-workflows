### Book Summarizer Workflow
An intelligent book summarization system with two different approaches:

- **External State Version**: Utilizes external state management for efficient book processing
- **Node Static Data Version**: Uses n8n's built-in static data functionality

Key features:
- Automated book processing
- Intelligent summarization
- Multiple implementation approaches
- Efficient state handling

## Implementation Details

### Book Summarizer Implementation
The book Summarizer workflow showcase two different approaches to processing and summarizing books:

1. **External State Version**:
   - Efficient state management
   - Handles large documents
   - Systematic processing approach

2. **Node Static Data Version**:
   - Uses n8n's built-in static data
   - Simple implementation
   - Perfect for smaller documents
   - No external dependencies

#### External State Version Workflow
![External State Version](./Book-Summarizer%20with%20Code%20Node%20and%20Extern%20State.jpg)

#### Node Static Data Version Workflow
![Node Static Data Version](./Book-Summarizer%20with%20node%20static%20data.jpg)

#### Example Output
<img src="./Output%20example.jpeg" alt="Example Output" width="400"/>

## Getting Started

To use these workflows:

1. Create a workflow in n8n portal
2. Import the desired JSON workflow file:
   - `Book-Summarizer with extern state.json` for the external state version
   - `Book-Summarizer with node static data.json` for the node static data version
3. Configure your credentials for:
   - Required APIs
   - State management system (for external state version)
4. Customize the workflow parameters as needed


Read more about static data:
https://docs.n8n.io/code/cookbook/builtin/get-workflow-static-data/

