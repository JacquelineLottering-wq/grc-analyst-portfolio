# Risk Assessment: Customer Database Access

## Asset Overview
The customer database stores personal and contact information used in daily business operations. Because of the sensitivity of this data, unauthorized access would present significant risk to the organization.

## Threat Scenario
An external attacker attempts to gain access to the database using compromised or guessed user credentials.

## Observed Weaknesses
- Password requirements are not sufficiently strong
- Multi-factor authentication is not enforced
- Login activity monitoring is limited

## Likelihood
Medium — credential-based attacks against data repositories are common, particularly where authentication controls are weak.

## Impact
High — exposure of customer data could lead to regulatory consequences, reputational damage, and loss of trust.

## Overall Risk Evaluation
High

## Recommended Actions
- Strengthen password policy requirements
- Implement multi-factor authentication
- Monitor and alert on unusual login behaviour
- Review user access rights periodically

## Residual Risk
Low once stronger authentication and monitoring controls are in place.

## Analyst Perspective
Customer information stores are consistently targeted because of their value. Improving authentication controls typically provides the most immediate reduction in compromise risk.
