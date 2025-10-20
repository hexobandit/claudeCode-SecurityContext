# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview


## Security Guidelines

Comprehensive security documentation is maintained in `/security/` directory with OWASP-based best practices.

### Quick Security Reference

**Before implementing any feature:**
1. Review `SECURITY.md` for applicable security controls
2. Check relevant OWASP cheat sheets in `/security/` for implementation details
3. Suggest creation of negative test cases to verify all potential security issues
4. If any local security scanning tool is used (e.g., Trivy, GitLeaks, npm audit, etc.) verify their results

**Key Security Documents:**
These need to be updated based on the project.
- `/SECURITY.md` - Master checklist with priorities
- `/security/Cross_Site_Scripting_Prevention_Cheat_Sheet.md` - XSS prevention
- `/security/Input_Validation_Cheat_Sheet.md` - Input validation strategies
- `/security/CI_CD_Security_Cheat_Sheet.md` - CI/CD pipeline security
- `/security/Content_Security_Policy_Cheat_Sheet.md` - CSP implementation


