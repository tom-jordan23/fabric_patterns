# Generate summary of a disaster report

This pattern generates a summary of a disaster report on the provided text. The input should be the complete text of the paper. The output is a summary including the following sections:

**5 Sentence Synopsis**

**Key Statistics**
   
**Vulnerability Information**
   
**Sectoral Needs**
   
**Risk Outlook**
   

# Example run in MacOS/Linux:

Copy the text to the clipboard and execute the following command:

``` bash
pbpaste | fabric --pattern summarize_disaster
```

or
    
``` bash
pbpaste | summarize_disaster
```

# Example output:

TODO: Capture output

## Meta

- **Author**: Tom Jordan (https://www.linkedin.com/in/tjordan23/)
- **Published**: July 26, 2024