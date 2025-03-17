# Non-Functional Requirement (NFR)

Non-Functional Requirements define the quality attributes and constraints of the system. These requirements specify criteria that can be used to judge the operation of a system, rather than specific behaviors.

## Purpose

NFRs ensure that the system meets quality standards, performance criteria, and operational requirements that are essential for its success but not directly related to functional behavior.

## When to Use

Create an NFR issue when you need to:
- Define system performance targets
- Specify security requirements
- Set scalability objectives
- Establish reliability standards
- Define compliance requirements
- Specify maintainability criteria
- Set usability standards

## Required Information

### Title Format
`[NFR] <System Quality> - <Specific Requirement>`

Example: `[NFR] Performance - API Response Time Under 200ms`

### Description Template
```markdown
## Requirement
[Clear statement of the non-functional requirement]

## Rationale
[Why this requirement is important]

## Measurement Criteria
[How this requirement will be measured]

## Acceptance Criteria
- [ ] [Specific, measurable criteria]
- [ ] [Additional criteria]

## Constraints
[Any limitations or constraints]

## Impact Areas
- [System components affected]
- [User experience impact]
- [Performance implications]
```

## Categories of NFRs

### 1. Performance
- Response time
- Throughput
- Resource utilization
- Latency requirements

### 2. Scalability
- Load handling
- Growth capacity
- Resource scaling
- Geographic distribution

### 3. Reliability
- Uptime requirements
- Fault tolerance
- Recovery time
- Backup requirements

### 4. Security
- Authentication
- Authorization
- Data protection
- Compliance requirements

### 5. Maintainability
- Code standards
- Documentation
- Modularity
- Testing requirements

### 6. Usability
- Accessibility
- User interface
- Response time
- Error handling

## Implementation Process

1. **Definition**
   - Clear requirement statement
   - Measurable criteria
   - Validation method

2. **Analysis**
   - Impact assessment
   - Feasibility check
   - Resource requirements
   - Cost implications

3. **Implementation Planning**
   - Technical approach
   - Resource allocation
   - Timeline
   - Dependencies

4. **Validation**
   - Testing methodology
   - Performance metrics
   - Monitoring setup
   - Success criteria

5. **Documentation**
   - Implementation details
   - Configuration changes
   - Monitoring setup
   - Maintenance procedures

## Best Practices

1. **Requirement Definition**
   - Be specific and measurable
   - Use clear, unambiguous language
   - Include rationale
   - Define success criteria

2. **Documentation**
   - Detailed specifications
   - Implementation guidelines
   - Testing requirements
   - Validation criteria

3. **Validation**
   - Define measurement methods
   - Set up monitoring
   - Regular testing
   - Performance benchmarks

4. **Review Process**
   - Stakeholder review
   - Technical review
   - Impact analysis
   - Cost assessment

## Common Pitfalls

1. **Vague Requirements**
   - "System should be fast" ❌
   - "API response time < 200ms for 99% of requests" ✅

2. **Unmeasurable Criteria**
   - "High security" ❌
   - "Implement AES-256 encryption for all data at rest" ✅

3. **Missing Context**
   - "System should scale" ❌
   - "System should handle 1000 concurrent users with < 1s response time" ✅

4. **Conflicting Requirements**
   - Check for conflicts with other NFRs
   - Balance trade-offs
   - Document decisions

## Related Labels

- Performance
- Scalability
- Security
- Reliability
- Maintainability
- Compliance

## Success Metrics

- Requirement met within specified parameters
- All acceptance criteria satisfied
- Monitoring in place
- Documentation complete
- Stakeholder sign-off obtained

## Templates

### Performance NFR
```markdown
## Requirement
API endpoint /api/v1/users must respond within 200ms at P95

## Measurement
- Response time monitoring via APM
- Load testing results
- Production metrics

## Acceptance Criteria
- [ ] P95 response time ≤ 200ms under normal load
- [ ] P99 response time ≤ 500ms under normal load
- [ ] Monitoring alerts set up
- [ ] Load testing scenarios documented
```

### Security NFR
```markdown
## Requirement
All user data must be encrypted at rest using AES-256

## Measurement
- Security audit results
- Encryption implementation review
- Database configuration check

## Acceptance Criteria
- [ ] AES-256 encryption implemented
- [ ] Key rotation mechanism in place
- [ ] Backup data encrypted
- [ ] Audit logging enabled
``` 