# Issue Types

This directory contains documentation for different types of issues that can be created in the system. Each issue type serves a specific purpose and helps categorize work items based on their nature and requirements.

## Issue Type Overview

Our system uses five distinct issue types to categorize different kinds of work:

### Issue Categories

```
├── NFR (Non-Functional Requirement)
├── Bug
├── Debt (Technical Debt)
├── Spike
└── Task
```

## Issue Type Descriptions

### [NFR (Non-Functional Requirement)](./nfr)
Issues that focus on system qualities rather than specific behaviors.
- Performance requirements
- Scalability needs
- Security requirements
- Reliability standards
- Compliance requirements

### [Bug](./bug)
Issues that represent defects or unexpected behaviors in the system.
- Software defects
- Incorrect functionality
- System errors
- UI/UX issues
- Integration problems

### [Debt (Technical Debt)](./debt)
Issues that represent technical compromises that need to be addressed.
- Code refactoring needs
- Architecture improvements
- Documentation updates
- Test coverage gaps
- Dependency updates

### [Spike](./spike)
Issues for research and exploration of potential solutions.
- Technical investigation
- Proof of concepts
- Research tasks
- Feasibility studies
- Learning exercises

### [Task](./task)
Standard work items that represent concrete, actionable work.
- Feature implementation
- Documentation writing
- Configuration changes
- Review tasks
- Maintenance work

## Issue Type Usage

### When to Use Each Type

1. **NFR**
   - When defining system quality requirements
   - For compliance-related work
   - When setting performance targets
   - For security requirements
   - For scalability planning

2. **Bug**
   - When something is not working as intended
   - For production issues
   - When fixing defects
   - For unexpected behavior
   - For system errors

3. **Technical Debt**
   - When addressing code quality issues
   - For modernizing legacy code
   - When improving architecture
   - For updating dependencies
   - When improving documentation

4. **Spike**
   - When research is needed
   - For exploring new technologies
   - When evaluating solutions
   - For prototyping
   - When learning new tools

5. **Task**
   - For standard development work
   - When implementing features
   - For routine maintenance
   - For planned improvements
   - For regular work items

## Best Practices

1. **Issue Creation**
   - Use clear, descriptive titles
   - Provide detailed descriptions
   - Include acceptance criteria
   - Link related issues
   - Add relevant labels

2. **Issue Management**
   - Regular prioritization
   - Proper assignment
   - Status updates
   - Time tracking
   - Progress monitoring

3. **Documentation**
   - Clear requirements
   - Implementation notes
   - Test cases
   - Related documents
   - Impact assessment

4. **Review Process**
   - Peer reviews
   - Quality checks
   - Testing requirements
   - Acceptance criteria
   - Sign-off process

## Common Workflows

1. **Bug Handling**
   - Report
   - Reproduce
   - Fix
   - Test
   - Verify

2. **NFR Implementation**
   - Define requirements
   - Plan implementation
   - Execute
   - Measure
   - Validate

3. **Technical Debt Resolution**
   - Identify
   - Assess impact
   - Plan resolution
   - Implement
   - Verify improvement

4. **Spike Execution**
   - Define questions
   - Research
   - Document findings
   - Make recommendations
   - Share knowledge

5. **Task Completion**
   - Plan
   - Implement
   - Test
   - Review
   - Deploy

## Common Pitfalls to Avoid

1. Misclassifying issue types
2. Insufficient detail in descriptions
3. Missing acceptance criteria
4. Poor documentation
5. Lack of progress tracking

For detailed information about each issue type, please refer to their respective README files in the subdirectories. 