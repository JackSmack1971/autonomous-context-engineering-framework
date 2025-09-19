# Implementation Rules: Context-Driven Execution

## Primary Directive
The context-engineering/ folder contains the complete specification universe. 
NEVER deviate from these specifications. Everything has been pre-decided.

## Context Validation Prerequisites
Before starting ANY implementation:
- Verify context-engineering/ folder exists in project root
- Confirm all phase folders contain completed documentation
- Check all documents show ✅ Complete status (not 🔄 Pending)  
- Validate implementation readiness per validation-criteria.md

## Implementation Sequence (Non-Negotiable)
Follow EXACT sequence from task-breakdown.md:

**Phase 1: Infrastructure Setup**
1. Database Implementation Specialist → Schema per database-schema-detailed.md
2. DevOps Implementation Specialist → CI/CD per deployment-architecture.md  
3. Backend Implementation Specialist → Base API structure per system-architecture.md

**Phase 2: Core Backend Implementation**  
1. API Endpoint Builder → Authentication endpoints first
2. Backend Implementation Specialist → Core business logic services
3. Integration Implementation Specialist → External services 
4. Testing Implementation Specialist → Backend test suites

**Phase 3: Frontend Implementation**
1. UI Component Builder → Components per component-specifications.md
2. Frontend Implementation Specialist → Pages and routing
3. Testing Implementation Specialist → Frontend test suites

**Phase 4: Quality Assurance**
1. QA Validator → Validate all acceptance criteria
2. Performance Validator → Validate performance requirements
3. Security Validator → Validate security requirements

## Context Reference Protocol
Each mode MUST reference specific context documents:
- coding-conventions.md for style and structure
- technical-requirements.md for performance and security
- validation-criteria.md for quality gates
- testing-procedures.md for testing approach

## Zero Creative Decisions Protocol
If ANY ambiguity encountered:
1. Search context-engineering/ folder thoroughly
2. If unclear, STOP implementation and create boomerang task
3. NEVER make assumptions or implement "reasonable" defaults
4. Wait for context engineering team clarification

## Quality Gate Validation
Before proceeding to next phase:
- Current implementation validated against context specs
- All tests pass per testing-procedures.md
- Code follows coding-conventions.md exactly
- Performance meets technical-requirements.md benchmarks
- Security requirements satisfied per specifications

## Implementation Status Tracking
Maintain progress for:
- Phase completion against task-breakdown.md  
- Quality gate compliance against validation-criteria.md
- Test coverage against testing-standards.md
- Performance benchmarks against technical-requirements.md
- Security requirements against security specifications

## Success Metrics
- 100% Specification Compliance
- Zero Creative Decisions Made
- Quality Gate Passage on First Attempt
- Context Traceability for All Decisions
