# Spike

A Spike represents a task focused on research, investigation, or exploration to better understand a problem or potential solution. It's a time-boxed investigation used to gain knowledge needed for estimating or implementing future work.

## Purpose

Spikes help teams reduce uncertainty and risk by gathering information, testing assumptions, and exploring potential solutions before committing to a specific implementation approach.

## When to Use

Create a Spike issue when:
- Technical feasibility needs validation
- Multiple solution approaches exist
- New technology evaluation is needed
- Performance characteristics are unknown
- Integration complexity is unclear
- Learning is required before estimation

## Required Information

### Title Format
`[Spike] <Area> - <Investigation Topic>`

Example: `[Spike] Authentication - Evaluate OAuth Providers`

### Description Template
```markdown
## Investigation Goal
[Clear statement of what needs to be learned]

## Key Questions
- [Question 1]
- [Question 2]
- [Question 3]

## Success Criteria
- [ ] [Specific knowledge to be gained]
- [ ] [Decisions to be made]
- [ ] [Outputs to be produced]

## Time Box
[Maximum time allocated]

## Resources
[Tools, documentation, or other resources needed]

## Deliverables
[Expected outputs from the investigation]
```

## Types of Spikes

### 1. Technical Spike
- Architecture validation
- Technology evaluation
- Performance testing
- Security assessment
- Integration feasibility

### 2. Functional Spike
- User flow analysis
- Feature exploration
- Business rule investigation
- Process optimization
- UX research

### 3. Research Spike
- Market analysis
- Best practices review
- Standards investigation
- Competitive analysis
- Innovation exploration

### 4. Solution Spike
- Implementation approaches
- Tool comparison
- Framework evaluation
- Library assessment
- Pattern research

## Investigation Process

1. **Preparation**
   - Define objectives
   - Set time box
   - Identify resources
   - Plan approach

2. **Research**
   - Gather information
   - Review documentation
   - Test assumptions
   - Explore options

3. **Experimentation**
   - Create prototypes
   - Run tests
   - Measure results
   - Document findings

4. **Analysis**
   - Evaluate options
   - Compare approaches
   - Assess feasibility
   - Consider trade-offs

5. **Documentation**
   - Summarize findings
   - Document decisions
   - Share knowledge
   - Make recommendations

## Best Practices

1. **Scope Definition**
   - Clear objectives
   - Specific questions
   - Measurable outcomes
   - Time constraints

2. **Time Management**
   - Strict time box
   - Regular checkpoints
   - Progress tracking
   - Scope control

3. **Documentation**
   - Clear findings
   - Code examples
   - Decision rationale
   - Next steps

4. **Knowledge Sharing**
   - Team presentations
   - Documentation
   - Code samples
   - Learning resources

## Common Pitfalls

1. **Unclear Goals**
   - "Research new tech" ❌
   - "Evaluate three OAuth providers against our security requirements" ✅

2. **No Time Box**
   - Open-ended research
   - Undefined endpoints
   - Scope creep
   - Resource waste

3. **Poor Documentation**
   - Missing conclusions
   - No code samples
   - Unclear findings
   - Lost knowledge

4. **Lack of Focus**
   - Too broad scope
   - Multiple objectives
   - Undefined priorities
   - Scattered effort

## Templates

### Technical Spike
```markdown
## Investigation Goal
Evaluate OAuth 2.0 providers for our authentication system upgrade

## Key Questions
- Which providers support our required features?
- What are the implementation costs?
- How do they compare in terms of security?
- What is the integration complexity?
- What are the performance implications?

## Success Criteria
- [ ] Compare at least 3 providers
- [ ] Document security features
- [ ] Create sample integration code
- [ ] Measure performance metrics
- [ ] Estimate implementation effort

## Time Box
5 days

## Resources
- OAuth 2.0 documentation
- Provider documentation
- Test environment
- Sample application

## Deliverables
- Comparison matrix
- Sample code
- Performance test results
- Implementation recommendation
- Cost analysis
```

### Research Spike
```markdown
## Investigation Goal
Research best practices for implementing real-time collaboration features

## Key Questions
- What are the common approaches?
- Which technologies are most suitable?
- What are the scaling considerations?
- How to handle conflict resolution?
- What are the security implications?

## Success Criteria
- [ ] Document common patterns
- [ ] Compare technology options
- [ ] Create proof of concept
- [ ] Test scalability limits
- [ ] Document security concerns

## Time Box
1 week

## Resources
- Research papers
- Existing solutions
- Testing tools
- Development environment

## Deliverables
- Technology comparison
- Architecture proposal
- POC implementation
- Scaling guidelines
- Security recommendations
``` 