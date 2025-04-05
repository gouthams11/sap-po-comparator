# SAP PO Communication Channel Comparator

[SAP PO Comparator](https://gouthams11.github.io/sap-po-comparator/)

A web-based tool for comparing communication channel parameters between Quality Assurance (QA) and Production (Prod) environments in SAP Process Orchestration (PO). This tool helps identify configuration differences and ensures consistency across environments.

## Features

- **XML Comparison**: Directly paste XML content from SAP PO communication channels
- **Detailed Comparison**: Thorough analysis of all parameters including adapter-specific attributes
- **Visual Differentiation**: Clear highlighting of differences between environments
- **Export Functionality**: Export comparison results to Excel format
- **Advanced Options**: 
  - Ignore empty parameters
  - Show only differences
  - Case-sensitive comparison toggle
- **Comparison Summary**: Quick overview of total parameters and differences found

## How to Use

1. **Paste XML Content**:
   - Copy and paste the XML content from your QA environment into the left textbox
   - Copy and paste the XML content from your Production environment into the right textbox

2. **Compare Communication Channels**:
   - Click the "Compare Communication Channels" button
   - The tool will analyze and display the comparison results

3. **Review Results**:
   - Parameters with differences will be highlighted in red
   - Parameters that match will be highlighted in green
   - Use the comparison summary to get an overview of differences

4. **Advanced Options**:
   - Toggle options to refine your comparison results
   - Filter parameters based on your specific needs

5. **Export Results**:
   - Export the comparison results to Excel for further analysis or reporting

## Technical Requirements

- Modern web browser (Chrome, Firefox, Edge, Safari)
- JavaScript enabled
- No backend server required - runs entirely in the browser
