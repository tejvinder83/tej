# IntegrationHub / REST Debugging Prompt

Trace the supplied ServiceNow integration from trigger to downstream response.

Inspect:
- trigger and input values
- Flow/Subflow input-output mapping
- custom action logic
- connection and credential alias usage
- endpoint configuration
- request headers and payload structure
- authentication outcome without revealing secrets
- HTTP status and response parsing
- timeout behavior
- retry policy
- correlation ID propagation
- idempotency behavior
- error routing and fallout creation

Return the first failing boundary, supporting evidence, minimal remediation, regression risks and validation tests.
