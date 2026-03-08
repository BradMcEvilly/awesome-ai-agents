# AI Agent Security Resources

> Curated security resources for AI-generated code and AI agents.

## The Problem

- 45% of AI-generated code contains OWASP vulnerabilities
- 80M+ people building with AI code generators
- Most have zero security expertise

## Tools

| Tool | Type | Price | Link |
|------|------|-------|------|
| [DeepSweep](https://platform.deepsweep.ai) | Automated scanner | Free tier | [VS Code Extension](https://marketplace.visualstudio.com/items?itemName=deepsweep.deepsweep) |
| [DeepSweep Expert Review](https://buy.stripe.com/dRm14ofzY4MZa141ZJabK02) | Human expert review | $499 | 48-hour turnaround |
| [Snyk](https://snyk.io) | Dependency scanner | Free tier | General purpose |
| [SonarQube](https://www.sonarqube.org) | Code quality | Free tier | General purpose |

## Guides

- [AI-Generated Code Security Checklist](https://github.com/deepsweep-ai/deepsweep/blob/main/docs/AI-CODE-SECURITY-CHECKLIST.md) - Comprehensive guide for vibe coders
- [OWASP Top 10](https://owasp.org/www-project-top-ten/) - Standard web security vulnerabilities
- [OWASP LLM Top 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/) - LLM-specific vulnerabilities

## Common Vulnerabilities in AI Code

1. Hardcoded secrets & API keys
2. SQL injection via string concatenation
3. Missing authentication on API routes
4. Cross-Site Scripting (XSS)
5. Insecure Direct Object References (IDOR)
6. Missing rate limiting
7. Insecure file uploads
8. Wildcard CORS configuration
9. Outdated dependencies with known CVEs
10. Missing input validation
