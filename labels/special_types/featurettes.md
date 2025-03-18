# 🎬 Featurettes

## Overview
Featurettes are micro-features that encapsulate a complete feature lifecycle (discovery to release) within a single sprint. They are larger than a single task but smaller than a full feature, designed to deliver incremental value quickly with minimal overhead. Each featurette includes subtasks representing the key stages of the development lifecycle, sometimes combined for efficiency.

## Characteristics

### 📏 Size & Scope
- Complete lifecycle: Discovery → Release in one sprint
- Completion time: 1-3 days
- Self-contained functionality
- Limited dependencies
- Clear, focused objective

### 🎯 Purpose
- Quick wins with complete feature lifecycle
- Incremental improvements
- User experience enhancements
- Technical optimizations

## Lifecycle Stages & Subtasks

### 1. 🔍 Discovery & Requirements (0.5 day)
- User need identification
- Quick research
- Scope definition
- Success criteria
- Can combine with design for simple changes

### 2. 🎨 Design & Planning (0.5 day)
- Rapid solution design
- Technical approach
- Implementation plan
- Can combine with discovery for UI/UX changes

### 3. ⚙️ Development (1-2 days)
- Implementation
- Unit testing
- Code review
- Can include basic documentation

### 4. 🚀 Testing & Release (0.5 day)
- QA verification
- User acceptance
- Documentation update
- Deployment
- Can combine with development for simple changes

## Structure

### 📋 Required Components
1. **Clear Value Proposition**
   - Immediate user benefit
   - Measurable impact
   - Quick time-to-value

2. **Limited Scope**
   - Single responsibility
   - Minimal dependencies
   - Clear boundaries

3. **Quick Implementation**
   - Rapid development cycle
   - Simple testing requirements
   - Easy deployment

## Usage Guidelines

### When to Use Featurettes
- Small UI/UX improvements
- Performance optimizations
- Minor feature enhancements
- Technical debt reduction
- Quick bug fixes with enhancements

### When Not to Use Featurettes
- Complex system changes
- Multi-team dependencies
- Large feature sets
- Major architectural changes

## 🔄 Workflow

1. **Identification**
   - Spot improvement opportunity
   - Validate quick implementation
   - Confirm independent value

2. **Definition**
   - Clear scope
   - Single objective
   - Measurable outcome

3. **Implementation**
   - Quick development
   - Focused testing
   - Rapid deployment

4. **Validation**
   - Immediate value check
   - User feedback
   - Impact measurement

## 📊 Tracking

### Linear Integration
- Label: `type:featurette`
- Priority: Normal to High
- Cycle: Single sprint
- Parent: Can link to larger feature
- Subtask Labels:
  - `stage:discovery`
  - `stage:design`
  - `stage:development`
  - `stage:release`

### Lifecycle Progress
- Discovery → Design: 0.5-1 day
- Design → Development: 1-2 days
- Development → Release: 0.5 day
- Total: 2-3 days maximum

### Metrics
- Implementation time per stage
- Total lifecycle completion time
- User impact
- Value delivered
- Technical debt reduced

## 🔗 Related Concepts

- Features (larger scope)
- Tasks (smaller scope)
- Quick wins
- Continuous improvement

## 🏷️ Naming & Emoji Conventions

### Title Format
- Format: `🎬 [Featurette Title]`
- Example: `🎬 Add Dark Mode Toggle`

### Status Indicators
- 🔄 In Progress
- ✅ Completed
- 🛑 Blocked
- 📝 In Review

### Stage Emojis
- 🔍 Discovery
- 🎨 Design
- ⚙️ Development
- 🚀 Release

### Common Featurette Types
- 🎨 UI/UX Enhancement
- ⚡ Performance Improvement
- 🔧 Technical Enhancement
- 🐛 Bug Fix + Enhancement
- 📱 Mobile Feature
- 🖥️ Desktop Feature
- 🌐 Web Feature

## 📝 Template Example

```markdown
# 🎬 [Featurette Title]

### Quick Value
[One sentence value proposition]

### Scope
- Single primary enhancement
- Clear boundaries
- Implementation estimate
- Sprint target

### Lifecycle Subtasks
1. 🔍 Discovery & Requirements
   - [ ] User need validation
   - [ ] Quick research
   - [ ] Success criteria defined

2. 🎨 Design & Planning
   - [ ] Solution approach
   - [ ] Technical design
   - [ ] Implementation plan

3. ⚙️ Development
   - [ ] Implementation
   - [ ] Unit tests
   - [ ] Code review

4. 🚀 Testing & Release
   - [ ] QA verification
   - [ ] Documentation
   - [ ] Deployment

### Success Criteria
- Specific metric
- User feedback target
- Technical improvement

### Timeline
- Sprint: [Sprint Number/Date]
- Discovery & Design: 0.5-1 day
- Development: 1-2 days
- Testing & Release: 0.5 day
```

## ⚡ Best Practices

1. **Keep It Small**
   - Single responsibility
   - Clear boundaries
   - Quick implementation

2. **Focus on Value**
   - Immediate benefit
   - Measurable impact
   - User-facing improvement

3. **Rapid Delivery**
   - Quick development
   - Simple testing
   - Fast deployment

4. **Clear Documentation**
   - Concise description
   - Specific outcome
   - Measurable success 