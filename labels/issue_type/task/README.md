# Task

A Task represents a concrete, actionable piece of work that contributes to the project's goals. Tasks are the most common type of issue and represent the day-to-day work items that need to be completed.

## Purpose

Tasks help break down larger initiatives into manageable pieces of work that can be easily tracked, assigned, and completed. They represent the primary unit of work in the development process.

## When to Use

Create a Task issue when:
- Implementing new features
- Making enhancements
- Creating documentation
- Performing maintenance
- Configuring systems
- Reviewing code
- Setting up infrastructure

## Required Information

### Title Format
`[Task] <Area> - <Brief Description>`

Example: `[Task] User Profile - Add Profile Picture Upload`

### Description Template
```markdown
## Task Description
[Clear description of what needs to be done]

## Requirements
- [Requirement 1]
- [Requirement 2]
- [Requirement 3]

## Acceptance Criteria
- [ ] [Specific criteria 1]
- [ ] [Specific criteria 2]
- [ ] [Specific criteria 3]

## Dependencies
[List of dependencies or blockers]

## Additional Context
[Any additional information needed]

## Definition of Done
- [ ] Code implemented
- [ ] Tests written
- [ ] Documentation updated
- [ ] Code reviewed
- [ ] QA verified
```

## Types of Tasks

### 1. Feature Implementation
- New functionality
- Feature enhancements
- UI components
- API endpoints
- Business logic

### 2. Documentation
- Technical docs
- User guides
- API documentation
- Architecture docs
- Process documentation

### 3. Configuration
- System setup
- Environment config
- Tool configuration
- Integration setup
- Security settings

### 4. Maintenance
- Updates
- Cleanup
- Optimization
- Security patches
- Regular maintenance

### 5. Review
- Code review
- Design review
- Documentation review
- Security review
- Performance review

## Task Workflow

1. **Planning**
   - Requirements review
   - Scope definition
   - Effort estimation
   - Dependency check

2. **Implementation**
   - Code development
   - Documentation
   - Testing
   - Review preparation

3. **Review**
   - Code review
   - Testing review
   - Documentation review
   - Security check

4. **Validation**
   - QA testing
   - Acceptance testing
   - Performance check
   - Security validation

5. **Completion**
   - Final review
   - Merge/deploy
   - Documentation update
   - Stakeholder sign-off

## Best Practices

1. **Task Creation**
   - Clear description
   - Specific requirements
   - Measurable criteria
   - Defined scope

2. **Implementation**
   - Follow standards
   - Write tests
   - Document changes
   - Regular updates

3. **Review Process**
   - Thorough review
   - Address feedback
   - Update documentation
   - Verify changes

4. **Documentation**
   - Clear instructions
   - Code comments
   - Usage examples
   - Update guides

## Common Pitfalls

1. **Unclear Scope**
   - "Update the system" ❌
   - "Update user profile API to include profile picture upload" ✅

2. **Missing Requirements**
   - "Add new feature" ❌
   - "Add password reset feature with email verification" ✅

3. **Vague Acceptance Criteria**
   - "Make it work" ❌
   - "User can upload profile picture up to 5MB in JPG/PNG format" ✅

4. **Poor Documentation**
   - Document changes
   - Update guides
   - Add examples
   - Include context

## Templates

### Feature Task
```markdown
## Task Description
Implement profile picture upload functionality for user profiles

## Requirements
- Allow users to upload profile pictures
- Support JPG and PNG formats
- Maximum file size: 5MB
- Generate thumbnails
- Store in cloud storage

## Acceptance Criteria
- [ ] User can upload profile picture from profile page
- [ ] File type validation implemented
- [ ] File size validation implemented
- [ ] Thumbnails generated automatically
- [ ] Images stored in cloud storage
- [ ] Old images cleaned up
- [ ] UI provides upload feedback

## Dependencies
- Cloud storage configuration
- Image processing library
- Frontend file upload component

## Definition of Done
- [ ] Code implemented and tested
- [ ] Unit tests written
- [ ] Integration tests added
- [ ] Documentation updated
- [ ] Code reviewed
- [ ] QA verified
- [ ] Performance tested
```

### Configuration Task
```markdown
## Task Description
Configure Elasticsearch for product search functionality

## Requirements
- Set up Elasticsearch cluster
- Configure indices
- Implement search mappings
- Set up monitoring
- Configure security

## Acceptance Criteria
- [ ] Elasticsearch cluster operational
- [ ] Indices properly configured
- [ ] Search mappings implemented
- [ ] Monitoring setup complete
- [ ] Security measures in place
- [ ] Backup strategy implemented

## Dependencies
- Infrastructure access
- Security certificates
- Network configuration

## Definition of Done
- [ ] Configuration complete
- [ ] Documentation updated
- [ ] Monitoring verified
- [ ] Security tested
- [ ] Backup tested
- [ ] Performance validated
``` 