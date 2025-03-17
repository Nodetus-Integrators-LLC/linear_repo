# Bug

A bug represents an error, flaw, or fault in the system that causes it to behave in unintended ways or produce incorrect results. Bug issues are used to track and resolve these defects.

## Purpose

Bug issues ensure that system defects are properly documented, tracked, and resolved, maintaining the quality and reliability of the system.

## When to Use

Create a Bug issue when:
- System behavior differs from specifications
- Unexpected errors occur
- UI elements don't work as intended
- Data inconsistencies are found
- Performance degradation is observed
- Security vulnerabilities are discovered

## Required Information

### Title Format
`[Bug] <Affected Component> - <Brief Description>`

Example: `[Bug] Login Form - Password Reset Email Not Sending`

### Description Template
```markdown
## Bug Description
[Clear description of the issue]

## Steps to Reproduce
1. [Step 1]
2. [Step 2]
3. [Step 3]

## Expected Behavior
[What should happen]

## Actual Behavior
[What actually happens]

## Environment
- Browser/Device: [e.g., Chrome 91, iPhone 12]
- OS: [e.g., Windows 10, iOS 14]
- Version: [e.g., v2.1.0]

## Additional Context
- [Screenshots/Videos]
- [Error messages]
- [Logs]
```

## Bug Severity Levels

### 1. Critical
- System crash
- Data loss
- Security breach
- Complete feature failure
- Production blocking

### 2. High
- Major functionality broken
- Significant user impact
- Performance severely degraded
- Security vulnerability
- No workaround available

### 3. Medium
- Feature partially broken
- Minor user impact
- Performance impact
- Workaround available
- Non-critical functionality

### 4. Low
- UI/cosmetic issues
- Minor inconvenience
- Rare edge cases
- Easy workaround
- Documentation issues

## Bug Lifecycle

1. **Report**
   - Issue created
   - Initial information gathered
   - Severity assessed

2. **Triage**
   - Validate bug
   - Set priority
   - Assign resources
   - Plan resolution

3. **Investigation**
   - Reproduce issue
   - Identify root cause
   - Determine fix approach
   - Assess impact

4. **Fix**
   - Implement solution
   - Write tests
   - Document changes
   - Create PR

5. **Verification**
   - Code review
   - Testing
   - QA validation
   - User acceptance

6. **Closure**
   - Fix deployed
   - Documentation updated
   - Verified in production
   - Stakeholders notified

## Best Practices

1. **Reporting**
   - Be specific and detailed
   - Include reproduction steps
   - Provide environment info
   - Add visual evidence

2. **Investigation**
   - Reproduce first
   - Document findings
   - Check related issues
   - Consider impact

3. **Resolution**
   - Fix root cause
   - Add regression tests
   - Update documentation
   - Consider side effects

4. **Verification**
   - Test thoroughly
   - Check edge cases
   - Verify in all environments
   - Get stakeholder approval

## Common Pitfalls

1. **Poor Description**
   - "It doesn't work" ❌
   - "Login fails with error 500 when using special characters in password" ✅

2. **Missing Context**
   - "System is slow" ❌
   - "Dashboard takes 30s to load with 1000+ records" ✅

3. **Incomplete Information**
   - No reproduction steps
   - Missing environment details
   - No error messages
   - No visual evidence

4. **Improper Severity**
   - Overestimating impact
   - Underestimating urgency
   - Not considering user impact

## Related Labels

- Priority (Critical/High/Medium/Low)
- Component (UI/Backend/Database)
- Type (Functional/Performance/Security)
- Environment (Dev/Staging/Prod)
- Status (New/In Progress/Fixed)

## Success Metrics

- Bug reproduced and understood
- Root cause identified
- Fix implemented and tested
- No regression issues
- Documentation updated
- Stakeholder verification complete

## Templates

### Functional Bug
```markdown
## Bug Description
Login form submission fails when password contains special characters

## Steps to Reproduce
1. Navigate to login page
2. Enter valid username
3. Enter password with special characters (e.g., "Test@123!")
4. Click Submit

## Expected Behavior
User should be logged in successfully

## Actual Behavior
Form submission fails with 500 error

## Environment
- Browser: Chrome 91.0
- OS: Windows 10
- App Version: v2.1.0

## Additional Context
- Error screenshot attached
- Server logs show validation error
```

### UI Bug
```markdown
## Bug Description
Modal dialog not centered on mobile devices

## Steps to Reproduce
1. Open application on mobile device
2. Navigate to profile page
3. Click "Edit Profile" button

## Expected Behavior
Modal should appear centered on screen

## Actual Behavior
Modal appears offset to right by 50px

## Environment
- Device: iPhone 12
- OS: iOS 14.5
- Browser: Safari
- Screen Size: 390x844

## Additional Context
- Screenshot attached showing misalignment
- Occurs on all mobile devices tested
``` 