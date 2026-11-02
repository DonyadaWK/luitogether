# Project Delivery Workflow

This repository currently documents a product concept; it is **not verified as the production source-code repository**.

## Working agreement
- Track proposed work in Issues with scope, priority and measurable acceptance criteria.
- Use `feature/*` and `fix/*` branches; open PRs before merging to `main`.
- Distinguish **planned**, **in development**, **tested** and **live** functionality.
- Do not commit API keys, credentials, customer records or private data.
- Add CI only after the actual framework, package manager and test commands are confirmed.
- Verify deployment ownership and rollback steps before connecting to production.

## Issue template
**Problem:**  
**User / stakeholder:**  
**Expected result:**  
**Acceptance criteria:**  
**Dependencies:**  
**Security / privacy considerations:**  
**Verification:**  

## First implementation checklist
- [ ] Locate the actual website source and hosting service
- [ ] Identify framework and build/test commands
- [ ] Document environment variable *names* (never values)
- [ ] Confirm development/staging/production separation
- [ ] Add appropriate automated checks
- [ ] Define release and rollback procedure
