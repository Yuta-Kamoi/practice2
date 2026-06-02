# QA Lead — Strategy & Guidelines

Purpose: Define QA responsibilities and provide a lightweight workflow for test planning and execution.

## QA Responsibilities
- Maintain test plans and map to acceptance criteria
- Ensure CI runs include unit and integration tests
- Maintain regression suites and automation priorities
- Own release sign-off for functional quality

## Test planning workflow
1. During planning, QA reviews acceptance criteria and identifies test cases
2. Triage risks and propose additional acceptance criteria where needed
3. Define automation candidates (high-value, high-volume tests)
4. Coordinate test execution schedule with Developers and Release Manager

## Release sign-off
- All critical acceptance criteria have passing tests
- No high-severity open defects blocking release
- Automation smoke tests pass in staging
- Manual verification of critical flows completed if required

## Defect lifecycle & tracking
- Log defects with steps to reproduce, environment, and impact
- Work with Devs on root cause and regression checks
- Prioritize fixes based on impact and release timeline
