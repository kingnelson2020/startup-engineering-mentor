# 03 - Roadmap

# Overview

This roadmap is competency-based rather than time-based.

The suggested timelines are estimates only.

Progression depends on demonstrated mastery.

Before beginning each phase, verify that the technologies, frameworks, APIs, and best practices involved remain current.

---

# Phase 1 — JavaScript and TypeScript Foundations

## Goal

Build a strong TypeScript foundation that supports frontend, backend, databases, testing, and AI integration.

---

## Topics

### JavaScript Fundamentals

* What JavaScript is
* How JavaScript runs
* Why JavaScript dominates modern web development
* What TypeScript adds

### Environment Setup

* Node.js
* VS Code
* npm
* TypeScript compiler
* Running TypeScript files

### Variables and Data Types

* let
* const
* string
* number
* boolean
* null
* undefined

### Control Flow

* if/else
* switch
* ternary operators

### Loops

* for
* while
* for...of
* for...in
* break
* continue

### Functions

* Function declarations
* Arrow functions
* Parameters
* Default parameters
* Rest parameters

### Arrays

* Creation
* Mutation
* Iteration

Important methods:

* map
* filter
* reduce
* find
* some
* every
* sort
* slice
* splice

### Objects

* Properties
* Methods
* Destructuring
* Spread operator
* Optional chaining

### String Manipulation

* split
* join
* trim
* replace
* search
* slice
* template literals
* case conversion

### Async JavaScript

* Promises
* async/await
* Event loop
* Error handling
* Common async mistakes

### Fetch API

* Requests
* Responses
* Error handling

### TypeScript Core Types

* Primitive types
* Interfaces
* Type aliases
* Union types
* Optional properties
* Generics

### Advanced TypeScript

* Tuples
* Enums
* Enum alternatives
* Literal types
* Type narrowing
* Utility types

Including:

* Pick
* Omit
* Partial
* Record

### Reading Type Definitions

* Understanding third-party types
* Understanding React types
* Understanding API types
* Understanding Prisma-generated types

### Object-Oriented TypeScript

* Classes
* Constructors
* Public
* Private
* Protected
* Getters
* Setters
* Inheritance
* Abstract classes
* Interfaces vs Classes
* Composition vs Inheritance

Important:

Teach OOP because it exists in professional codebases.

Do not present it as the dominant style of modern TypeScript development.

### Modules

* Import
* Export
* Module resolution

### Error Handling

* try/catch/finally
* Custom errors

### npm and package.json

* Dependencies
* Scripts
* Versioning basics

---

## AI-Assisted Engineering

Begin immediately.

Topics:

* AI-assisted debugging
* AI-assisted code review
* Evaluating generated code
* Detecting hallucinations
* Prompting effectively

---

## Milestone Project

### CLI Transaction Analyzer

Features:

* Read transaction data from JSON
* Filter transactions
* Aggregate totals
* Generate summaries
* Handle errors

Requirements:

* TypeScript
* GitHub repository
* Clean README

---

# Phase 2 — Computer Science Fundamentals

## Goal

Understand the concepts required to reason about software systems and answer junior interview questions.

---

## Topics

### Internet Fundamentals

* HTTP
* Request/response cycle
* Status codes
* DNS
* Client-server model

### APIs

* Endpoints
* Methods
* Headers
* JSON

### Data Structures

* Arrays
* Objects
* Stacks
* Queues

### Big O Basics

* Time complexity
* Space complexity

### Recursion

* Reading recursion
* Tracing recursion

### Database Concepts

* Tables
* Rows
* Columns
* Relationships

### Browser Fundamentals

* DOM
* Rendering
* JavaScript execution

---

# Phase 3 — Git and GitHub Discipline

## Goal

Develop professional collaboration habits.

---

## Topics

### Git Workflow

* Branching
* Feature branches
* Merge strategies

### Commit Discipline

* Meaningful commits
* Commit hygiene

### Pull Requests

* Creating PRs
* Reviewing PRs
* Self-review

### Documentation

* README writing
* Project documentation

### GitHub Profile

* Profile README
* Pinned repositories
* Portfolio presentation

### Team Workflows

* Collaboration
* Code review
* Merge conflicts

---

## Code Reading Begins

Exercises:

* Explore open-source repositories
* Trace project structure
* Explain architecture

---

# Phase 4 — Databases

## Goal

Design and query production-quality relational databases.

---

## Topics

### Relational Databases

* Why databases exist
* Relational thinking

### PostgreSQL

* Setup
* Usage

### SQL Fundamentals

* SELECT
* INSERT
* UPDATE
* DELETE

### Querying

* Filtering
* Ordering
* Limiting
* Aggregations
* Grouping

### Joins

* INNER JOIN
* LEFT JOIN
* RIGHT JOIN
* FULL JOIN

### Schema Design

* Relationships
* Data modeling

### Keys and Constraints

* Primary keys
* Foreign keys
* Constraints

### Indexes

* Why indexes exist
* Tradeoffs

### Normalization

* Data duplication
* Data consistency

### Prisma

* Schema
* Migrations
* Relations
* Queries

### Engineering Tradeoffs

* PostgreSQL vs MongoDB
* Prisma vs raw SQL

---

## Milestone Project

### Makurdi Connect Database Layer

Design:

* Users
* Profiles
* Categories
* Service requests
* Matches

Create:

* SQL queries
* Prisma schema
* Prisma queries

---

# Phase 5 — Backend Development, Testing, and Security

## Goal

Build secure, production-quality APIs.

---

## Backend Topics

### Backend Fundamentals

* Purpose of a backend
* Architecture basics

### Next.js Backend

* API routes
* Server actions

### Express

* Building standalone services

### REST APIs

* Resources
* HTTP methods
* Versioning

### Database Integration

* Prisma
* PostgreSQL

### CRUD Operations

* Create
* Read
* Update
* Delete

### Authentication

* Clerk
* NextAuth overview
* Tradeoffs

### Authorization

* Roles
* Ownership

### Environment Variables

* Secrets
* Configuration

### API Documentation

* Professional documentation

### Deployment

* Railway

---

## Testing

### Testing Fundamentals

* Why testing exists

### Unit Testing

* Jest
* Functions
* Async code

### Integration Testing

* API testing

### Frontend Testing

* React Testing Library

### End-to-End Testing

* Playwright

### Continuous Integration

* Automated test execution

---

## Security

### Core Security

* Input validation
* SQL injection
* Environment variables
* HTTPS
* CORS

### Expanded Security

* XSS
* CSRF
* SSRF
* Session security
* JWT basics
* OAuth fundamentals
* Secure file uploads
* Dependency vulnerabilities
* Security headers
* Secrets rotation

### Payments

* Paystack integration
* Webhook verification

---

## Production Incident Drills Begin

Simulate:

* API failures
* Authentication failures
* Database failures

---

## Milestone Projects

### Makurdi Connect Backend

### AI-Powered Job Description Analyzer

Requirements:

* Authentication
* Validation
* Testing
* Deployment
* Documentation

---

# Phase 6 — Observability and Distributed Systems

## Goal

Understand monitoring, caching, scaling, and reliability.

---

## Observability

### Foundations

* Logs
* Metrics
* Traces

### Structured Logging

### Sentry

* Monitoring
* Alerting
* Error analysis

### Performance Monitoring

* Slow APIs
* Slow queries

### OpenTelemetry Basics

### Vercel Analytics

---

## Distributed Systems

### Fundamentals

* What distributed systems are

### Common Problems

* Network failures
* Partial failures
* Eventual consistency
* Race conditions

### Redis

* Data structures
* Caching
* Rate limiting

### Queues

* Background jobs
* Retries

### Inngest

* Jobs
* Retries
* Scheduling

### Webhooks

### Idempotency

### Feature Flags

---

## Milestone

Enhance Makurdi Connect with:

* Sentry
* Redis
* Rate limiting
* Caching
* Background jobs
* Webhooks

---

# Phase 6.5 — Software Architecture and Codebase Navigation

## Goal

Become comfortable reading, understanding, and extending unfamiliar codebases.

---

## Topics

### Architecture Styles

* Monoliths
* Microservices
* Modular monoliths

### Project Structures

* Feature-based architecture
* Layered architecture

### Dependency Management

### Refactoring

### Technical Debt

### Reading Existing Systems

### Following Data Flow

### Architecture Reviews

---

## Milestone

### Architecture Review Report

Analyze an existing codebase and document:

* Structure
* Strengths
* Weaknesses
* Improvement opportunities

---

# Phase 7 — Frontend Development

## Goal

Build responsive interfaces for real users.

---

## Topics

### HTML

### CSS

* Box model
* Flexbox
* Grid

### Tailwind CSS

### shadcn/ui

### React

* Components
* Props
* State
* Hooks
* Forms

### State Management

* useState
* Context
* Zustand
* Jotai

### Next.js App Router

* Server Components
* Client Components
* Layouts
* Routing

### Data Fetching

* Server-side
* Client-side
* Revalidation

### Authentication Flows

### Forms and Validation

### Optimistic UI

### Image Optimization

### Deployment

* Vercel

---

## Nigerian Mobile Reality Focus

Optimize for:

* Low-end Android devices
* Slow networks
* Limited bandwidth

---

## Milestone Projects

### Makurdi Connect Frontend

### Fintech Dashboard

---

# Phase 8 — AI Integration

## Goal

Build practical AI-powered software features.

---

## Topics

### LLM APIs

* OpenAI
* Anthropic

### Prompt Engineering

### Structured Outputs

### Streaming

### Multi-turn Conversations

### Context Management

### Cost Awareness

### Prompt Injection Awareness

---

## AI Engineering

### Embeddings

### Vector Databases

### Retrieval-Augmented Generation (RAG)

### Evaluation

### Prompt Versioning

### AI Observability

### Guardrails

---

## Milestone

### AI Request Parser

Convert natural-language service requests into structured search criteria.

---

# Phase 8.5 — Agentic Engineering

## Goal

Understand modern agentic systems.

---

## Topics

### Tool Calling

### Tool Execution Loops

### Error Recovery

### MCP

* Model Context Protocol

### LangGraph

### Multi-Agent Patterns

### Reliability

### Cost and Latency Tradeoffs

---

## Milestone

### Agentic Onboarding Assistant

Provider onboarding through conversational workflows.

---

# Phase 9 — System Design

## Goal

Develop junior-level system design competence.

---

## Topics

### System Design Fundamentals

### Scaling

### Caching

### Authentication Architecture

### Database Design

### Message Queues

### Third-Party Integrations

### Observability

### AI System Design

---

## Reliability Topics

### Availability

### Throughput

### Latency

### Single Points of Failure

### Replication Basics

### Load Balancing Concepts

### Disaster Recovery

### Multi-Region Concepts

### Cost-Aware Architecture

---

## Practice Systems

* Makurdi Connect
* Digital wallet
* Notification platform
* Social feed
* AI onboarding assistant

---

# Phase 10 — Interview Preparation

## Goal

Become startup interview ready.

---

## Areas

### Behavioral Interviews

### Portfolio Walkthroughs

### Live Coding

### System Design

### Mock Interviews

### Startup Research

### Offer Evaluation

---

## Completion Criteria

Demonstrate competency across:

* TypeScript
* Databases
* Backend engineering
* Security
* Testing
* Observability
* Frontend engineering
* AI integration
* Agentic systems
* System design
* Communication
* Portfolio presentation

Only advance to job applications when readiness has been demonstrated across all areas.
