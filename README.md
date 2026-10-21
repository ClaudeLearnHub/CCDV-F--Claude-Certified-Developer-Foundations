# Anthropic Claude Certified Developer – Foundations (CCDV-F) Study Guide

Welcome to the comprehensive, community-driven study repository for the **Anthropic Claude Certified Developer – Foundations (CCDV-F)** certification. This repository is built for software engineers, application developers, and technical practitioners who want to master the Claude API, agentic workflows, tool use, and production deployment best practices.

Whether you are preparing for the official exam or looking to sharpen your production LLM engineering skills, this guide covers all core official exam domains with practical code patterns, architectural diagrams, and structured learning paths.

---

## Table of Contents

1. [Overview](#1-overview)
2. [About the Certification](#2-about-the-certification)
3. [Who Should Prepare for This Exam?](#3-who-should-prepare-for-this-exam)
4. [Official Exam Objectives & Domain Weighting](#4-official-exam-objectives--domain-weighting)
5. [Exam Domain Weightage Chart](#5-exam-domain-weightage-chart)
6. [Certification Preparation Flowchart](#6-certification-preparation-flowchart)
7. [Technical Architecture & Integration Diagram](#7-technical-architecture--integration-diagram)
8. [Circular Study and Revision Cycle](#8-circular-study-and-revision-cycle)
9. [Step-by-Step Preparation Roadmap](#9-step-by-step-preparation-roadmap)
10. [Core Technical Domains Deep Dive](#10-core-technical-domains-deep-dive)
11. [Practice Questions & Mock Testing Strategy](#11-practice-questions--mock-testing-strategy)
12. [Common Preparation Mistakes](#12-common-preparation-mistakes)
13. [Certification Benefits & Career Relevance](#13-certification-benefits--career-relevance)
14. [Frequently Asked Questions](#14-frequently-asked-questions)
15. [Official & Additional Learning Resources](#15-official--additional-learning-resources)
16. [About ExamsDay](#16-about-examsday)
17. [Disclaimer](#17-disclaimer)

---

## 1. Overview

The **CCDV-F** exam validates a developer's ability to build, integrate, test, and secure applications powered by Anthropic's Claude models. Unlike high-level conceptual AI credentials, this exam targets hands-on engineering capabilities—testing your fluency with the Messages API, streaming, structured outputs, prompt caching, agentic loops, and Model Context Protocol (MCP) servers.

---

## 2. About the Certification

* **Exam Code:** CCDV-F
* **Official Exam Name:** Claude Certified Developer – Foundations
* **Certification Provider:** Anthropic
* **Total Questions:** 53 multiple-choice and scenario-based questions
* **Exam Duration:** 120 minutes (2 hours)
* **Passing Score:** 720 / 1000 (72%)
* **Exam Fee:** $125 USD
* **Validity Period:** 12 months (annual recertification via non-proctored partner assessment)
* **Delivery Method:** Online proctored or Pearson VUE test center

---

## 3. Who Should Prepare for This Exam?

This certification is designed for software engineers and technical practitioners. Recommended background includes:
* 1 to 3 years of professional software development experience.
* At least 6 months of practical experience building applications with Claude or comparable large language models.
* Proficiency in Python or TypeScript, REST API integration, asynchronous programming, and CLI tools.
* Familiarity with Git workflows, basic containerization, and foundational prompt engineering concepts.

---

## 4. Official Exam Objectives & Domain Weighting

The CCDV-F curriculum is divided into key technical domains covering the complete lifecycle of Claude application development:

1. **Applications and Integration (33.1%)**: Messages API, streaming responses, vision/file inputs, structured outputs, message batches, error handling, and rate-limit management.
2. **Model Selection and Optimization (16.8%)**: Selecting between model tiers (Opus, Sonnet, Haiku), cost vs. latency trade-offs, prompt caching, token counting, extended thinking, and context window management.
3. **Agents and Workflows (14.7%)**: Agent loops, workflows versus autonomous agents, orchestration patterns, subagents, agent memory, and multi-step task decomposition.
4. **Tools and MCPs**: Tool use schemas, calling custom tools, and integrating Model Context Protocol (MCP) servers.
5. **Prompt and Context Engineering**: System prompt design, multi-shot prompting, context pruning, compaction, and avoiding context drift.
6. **Security and Safety (8.1%)**: Prompt injection defense, jailbreak mitigation, guardrails, data privacy, and content moderation.
7. **Eval, Testing, and Debugging**: Automated evaluations, semantic assertions, debugging malformed outputs, and CI/CD integration.
8. **Claude Code**: Operating Claude Code in interactive and headless modes for developer workflows and automation.

---

## 5. Exam Domain Weightage Chart

The following Mermaid pie chart illustrates the official domain breakdown for the CCDV-F examination:

```mermaid
pie title CCDV-F Official Exam Domain Weightings
    "Applications and Integration" : 33.1
    "Model Selection and Optimization" : 16.8
    "Agents and Workflows" : 14.7
    "Security and Safety" : 8.1
    "Other Core Domains (Tools, Evals, Prompts, Claude Code)" : 27.3
