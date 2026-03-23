# Continuous Intelligence

This site provides documentation for this project.
Use the navigation to explore module-specific materials.

## How-To Guide

Many instructions are common to all our projects.

See
[⭐ **Workflow: Apply Example**](https://denisecase.github.io/pro-analytics-02/workflow-b-apply-example-project/)
to get these projects running on your machine.

## Project Documentation Pages (docs/)

- **Home** - this documentation landing page
- **Project Instructions** - instructions specific to this module
- **Your Files** - how to copy the example and create your version
- **Glossary** - project terms and concepts

## Additional Resources

- [Suggested Datasets](https://denisecase.github.io/pro-analytics-02/reference/datasets/cintel/)

## Custom Project

### Dataset
I used the original clinic dataset containing patient age and height measurements that was provided.

### Signals
I kept the original flagged ages of 16 and older and heights of 72 inches or more as anomalies. I also added a rule to catch unrealistic combinations, like children under 5 who are over 52 inches tall. I included another rule for very small heights under 24 inches. Lastly, I updated the code to explain why each anomaly was flagged.

### Experiments
I experimented with adding new rules and improving the output. I wanted to catch more realistic issues and make the results easier to understand.

### Results
The updated code found more types of anomalies, including unrealistic combinations and very small heights. It also showed the reason for each anomaly.

### Interpretation
I learned that adding more rules helps catch different kinds of issues. Including the reason for each anomaly also made the results easier to understand and more useful.
