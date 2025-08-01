# Change Impact Labels

This category defines the impact level of changes for Change Control Board (CCB) processes and compliance with FIPS, SOC, and FedRAMP requirements.

## Security Boundary Considerations

When assessing change impact, consider whether the change:
- Affects components within the security boundary
- Modifies security controls or authentication mechanisms
- Impacts data handling, encryption, or access controls
- Changes network configurations or external integrations
- Affects audit logging or compliance reporting

## Impact Levels

### Minor
- Changes that do not affect the security boundary
- Bug fixes with no security implications
- Documentation updates
- UI/UX improvements without functional changes
- **Process**: Can be approved asynchronously without CCB meeting

### Major
- Changes that may affect the security boundary
- New features with potential security implications
- Database schema modifications
- API changes or integrations
- **Process**: Requires Change Control Board meeting and approval

### Significant
- Changes directly impacting the security boundary
- Security control modifications
- Authentication/authorization changes
- Encryption or key management updates
- Infrastructure or architecture changes
- **Process**: Requires Change Control Board meeting, security review, and formal approval

## Usage Guidelines

1. All changes must be labeled with one of the three impact levels
2. When in doubt, escalate to the higher impact level
3. Security team should be consulted for boundary determination
4. Document the rationale for impact level selection in the issue/PR

## Compliance Requirements

- **FIPS**: Changes affecting cryptographic modules require significant impact
- **SOC**: Changes to controls or audit processes require major/significant impact
- **FedRAMP**: All changes within the authorization boundary require review