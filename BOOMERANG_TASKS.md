# Boomerang Task Templates

> **Boomerang tasks enable modes to delegate specific research or clarification tasks to specialist modes, ensuring no assumptions are made during context engineering.**

## 🎯 Template Categories

### 📋 Requirements Research Tasks

#### Stakeholder Clarification
```
Task for Requirements Archaeologist:
"Clarify business rules for [SPECIFIC SCENARIO]. Need detailed specification of:
- Required behavior in normal conditions
- Edge case handling (e.g., empty data, invalid inputs, concurrent access)
- Error message requirements
- User experience expectations
- Performance requirements
- Accessibility considerations"

Context: [Provide relevant background]
Deadline: [Specify urgency]
```

#### User Journey Analysis
```
Task for Requirements Archaeologist:
"Create comprehensive user journey for [USER TYPE] performing [SPECIFIC TASK]. Include:
- Step-by-step user actions
- System responses at each step
- Decision points and alternative paths
- Error recovery scenarios
- Success criteria and validation
- User feedback and confirmation mechanisms"

User Context: [Demographics, technical skill level, environment]
Business Context: [Goals, constraints, success metrics]
```

#### Edge Case Discovery
```
Task for Requirements Archaeologist:
"Identify and document all edge cases for [FEATURE/FUNCTIONALITY]. Focus on:
- Boundary conditions (min/max values, empty states)
- Concurrent user scenarios
- Network failure conditions
- Invalid input combinations
- Integration failure scenarios
- Performance limit scenarios"

Acceptance Criteria: Each edge case must have specific handling requirements
```

### 🔍 Technology Research Tasks

#### Framework Comparison
```
Task for Technology Stack Detective:
"Compare [FRAMEWORK OPTIONS] for [SPECIFIC USE CASE]. Provide:
- Performance benchmarks with real data
- Community health metrics (GitHub activity, issue response times)
- Learning curve assessment for team with [SKILL LEVEL]
- Long-term maintenance considerations
- Integration capabilities with [EXISTING TECH STACK]
- Cost analysis (licensing, hosting, operational overhead)"

Evaluation Criteria: [Specify weighted priorities]
Timeline: [Development timeline constraints]
```

#### Security Analysis
```
Task for Technology Stack Detective:
"Analyze security implications of [TECHNOLOGY CHOICE] for [PROJECT TYPE]. Research:
- Known vulnerabilities and CVE history
- Security best practices and hardening guides
- Compliance requirements (GDPR, HIPAA, SOX, etc.)
- Authentication and authorization patterns
- Data encryption capabilities
- Audit trail and monitoring capabilities"

Security Requirements: [Specify compliance needs]
Threat Model: [Expected threat landscape]
```

#### Performance Benchmarking
```
Task for Technology Stack Detective:
"Benchmark performance of [TECHNOLOGY OPTIONS] for [SPECIFIC WORKLOAD]. Test:
- Response times under normal load
- Throughput capacity
- Memory usage patterns
- CPU utilization
- Scaling characteristics
- Resource costs at different load levels"

Test Scenarios: [Specify expected usage patterns]
Performance Targets: [SLA requirements]
```

### 🏗️ Architecture Research Tasks

#### System Design Validation
```
Task for Architecture Oracle:
"Validate proposed architecture for [SYSTEM/FEATURE] against requirements. Analyze:
- Scalability to [EXPECTED LOAD]
- Performance bottlenecks and mitigation strategies
- Single points of failure and redundancy plans
- Integration complexity with [EXISTING SYSTEMS]
- Deployment and operational considerations
- Security boundaries and access control"

Constraints: [Technical, budget, timeline constraints]
Quality Attributes: [Prioritized architectural concerns]
```

#### API Design Review
```
Task for Architecture Oracle:
"Design complete API specification for [FEATURE/SERVICE]. Include:
- All endpoint definitions with HTTP methods
- Request/response schemas with examples
- Error response formats and status codes
- Authentication and authorization requirements
- Rate limiting and throttling specifications
- Versioning strategy and backward compatibility"

Integration Requirements: [External systems to integrate with]
Performance Requirements: [Response time, throughput targets]
```

#### Database Schema Design
```
Task for Architecture Oracle:
"Design database schema for [DATA DOMAIN]. Specify:
- Entity relationships and foreign key constraints
- Index strategy for performance optimization
- Data types and validation constraints
- Partitioning strategy for scalability
- Backup and recovery requirements
- Migration strategy from [EXISTING SCHEMA]"

Data Volume: [Expected record counts and growth]
Query Patterns: [Expected access patterns and frequency]
```

### 📐 Standards Research Tasks

#### Coding Standards Definition
```
Task for Standards Authority:
"Establish coding standards for [LANGUAGE/FRAMEWORK]. Define:
- Naming conventions (variables, functions, classes, files)
- Code organization and file structure
- Comment and documentation requirements
- Error handling patterns
- Testing conventions and coverage requirements
- Performance optimization guidelines"

Team Context: [Team size, experience level, existing preferences]
Tool Integration: [IDE, linters, formatters to support]
```

#### Quality Gate Definition
```
Task for Standards Authority:
"Define quality gates for [PROJECT TYPE]. Specify:
- Code coverage requirements by component type
- Performance benchmarks and SLA requirements
- Security scan requirements and acceptable risk levels
- Accessibility compliance requirements
- Documentation completeness criteria
- Review and approval processes"

Delivery Requirements: [Regulatory, business requirements]
Risk Tolerance: [Acceptable levels of technical debt]
```

### ⚙️ Technical Specification Tasks

#### Component Interface Design
```
Task for Technical Specification Architect:
"Define complete interface specification for [COMPONENT/SERVICE]. Include:
- Input/output parameter specifications with types
- State management requirements and lifecycle
- Event handling and callback specifications
- Error conditions and exception handling
- Performance requirements and resource usage
- Testing requirements and mock interfaces"

Usage Context: [How component will be used]
Dependencies: [Required services or components]
```

#### Integration Specification
```
Task for Technical Specification Architect:
"Create integration specification for [EXTERNAL SERVICE]. Define:
- Authentication and authorization mechanisms
- API rate limits and retry strategies
- Data transformation and mapping requirements
- Error handling and fallback procedures
- Monitoring and alerting requirements
- Testing strategies (mocking, staging environments)"

Service Details: [API documentation, SLA information]
Business Requirements: [Criticality, data sensitivity]
```

### 📖 Implementation Planning Tasks

#### Task Breakdown Creation
```
Task for Implementation Guide Creator:
"Break down [EPIC/FEATURE] into implementable tasks. Provide:
- Sequential task order with dependencies
- Estimated effort for each task
- Acceptance criteria and definition of done
- Testing requirements for each task
- Risk assessment and mitigation strategies
- Resource requirements and skill assignments"

Project Context: [Timeline, team composition, constraints]
Quality Requirements: [Testing, documentation, review needs]
```

#### Testing Strategy Design
```
Task for Implementation Guide Creator:
"Design comprehensive testing strategy for [FEATURE/SYSTEM]. Include:
- Unit testing approach and coverage targets
- Integration testing scenarios and data requirements
- End-to-end testing user journeys
- Performance testing procedures and benchmarks
- Security testing requirements
- Automated testing pipeline integration"

Quality Targets: [Coverage, performance, reliability requirements]
Testing Environment: [Available tools, infrastructure, data]
```

## 🔄 Boomerang Task Best Practices

### Task Creation Guidelines

1. **Be Specific**: Clearly define what information is needed and why
2. **Provide Context**: Include all relevant background information
3. **Set Clear Deliverables**: Specify exactly what output is expected
4. **Include Constraints**: Document limitations, deadlines, and requirements
5. **Reference Standards**: Point to existing documentation or standards to follow

### Task Assignment Guidelines

1. **Match Expertise**: Assign tasks to modes with relevant expertise
2. **Check Dependencies**: Ensure prerequisite information is available
3. **Avoid Circular Dependencies**: Don't create loops between modes
4. **Monitor Progress**: Track task completion and quality
5. **Validate Outputs**: Review deliverables before marking complete

### Quality Validation

Before accepting boomerang task results:
- [ ] All requested information provided
- [ ] Deliverables meet specified format and quality standards
- [ ] Assumptions and limitations clearly documented
- [ ] Dependencies and constraints addressed
- [ ] Validation criteria met

---

**Remember**: Boomerang tasks are the key to maintaining zero ambiguity throughout the context engineering process. Use them liberally to ensure every decision is properly researched and documented.
