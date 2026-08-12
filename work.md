---
layout: page
title: Work
permalink: /work/
---

## New World Technologies

**Founder / Software Consultant · May 2023–Present**

- Founded and lead a software consultancy delivering backend architecture, cloud infrastructure, data platforms, AI-enabled products, and production modernization for startups and growth-stage teams.
- Own solution design and hands-on delivery across Java/Spring Boot, Python/FastAPI, TypeScript, C#/ASP.NET Core, AWS, Azure, Google Cloud, relational and non-relational databases, and event-driven systems.
- Partner with founders and product teams on scope, architecture, security, reliability, delivery planning, code review, mentoring, incident resolution, and technical due diligence.

### floorXplorer · May 2026–Present

- Architected and built a custom construction-materials commerce platform with a Next.js storefront, NestJS modular-monolith API, Prisma, PostgreSQL, and a supplier-integration boundary designed for future EDI workflows.
- Implemented high-volume supplier catalog ingestion and normalization, canonical product and source models, faceted search, stable cursors, pallet inventory, media, warehouse locations, audit logs, and operational reports.
- Delivered customer profiles, addresses, carts, inventory-backed offers, atomic package reservation, idempotent checkout, immutable order snapshots, staff order processing, and customer-safe messaging.
- Built Cognito passwordless authentication with separate customer and staff clients and RBAC, plus a leased outbox worker for purchase-order PDF generation, private S3 storage, and SES email delivery.
- Provisioned ECS, RDS, S3, Cognito, Amplify/CloudFront, ALB logging, monitoring, and GitHub OIDC deployment roles with Terraform and automated plan, apply, and release workflows.

### 4dlr — AI Customer Service Assistant for Car Dealerships · May 2026–Present

- Led modernization of an AI customer-service platform for automotive dealerships, consolidating more than 20 Python microservice repositories into a cohesive FastAPI modular monolith.
- Separated API and worker runtimes from one codebase and migrated communications, messaging, AI orchestration, automation, rooms, organizations, inventory, billing, calendar, media, analytics, and translation domains while preserving production behavior.
- Implemented REST APIs, webhooks, queue consumers, scheduled jobs, PostgreSQL tenant schemas, Redis, RabbitMQ, Auth0 identity, Stripe billing, Twilio messaging, S3 media, and LLM provider integrations; used AI coding tools to help port and refactor an existing GraphQL layer from the microservices system.
- Built migration audits, bootstrap, migration, and seeding CLI tooling, test coverage, and deployment runbooks to identify behavior gaps and reduce cutover risk.
- Provisioned development and production AWS environments with reusable Terraform modules for ECS Fargate, RDS PostgreSQL, ElastiCache, Amazon MQ, ALB, ECR, S3/CloudFront, Auth0, Stripe webhooks, Secrets Manager, ACM, and Route 53.

### AIshar Inc. · November 2025–March 2026

- Architected and deployed Terraform-managed AWS infrastructure for an AI medical-coding platform across development, staging, and production, including ECS Fargate, ECR, RDS, S3, SQS, ALB, CloudFront, KMS, isolated remote state, and GitHub Actions CI/CD.
- Containerized and migrated a FastAPI backend, Streamlit frontend, and AI coding workers; implemented asynchronous SQS task distribution, S3 presigned uploads, and separate CPT/ICD-10/ASA and HL7/radiology agent workflows using OpenAI, Anthropic, and Gemini models.
- Increased concurrent processing from 5 to 15 threads per task, for 60 total workers, implemented backpressure-aware SQS polling, and configured auto-scaling policies from 4 to 8 tasks. This reduced batch processing time by 40% and eliminated out-of-memory errors through memory optimization from 8 GB to 16 GB per task.
- Hardened the platform for HIPAA-oriented workloads with KMS-encrypted data paths, secure-transport S3 policies, AWS WAF, GuardDuty, AWS Config rules, private networking, least-privilege IAM, and documented security controls.

### Gain Health Net · June 2024–December 2025

- Led backend development for a healthcare service marketplace connecting owners of X-ray, CT, and other medical devices with qualified service providers.
- Built Java 21/Spring Boot APIs for device inventory, geospatial provider matching, service requests, work orders, calendars, notifications, chat, reviews, user onboarding, and role-based access on Firebase and Google Cloud.
- Integrated Stripe and Stripe Connect payments, invoices, webhooks, SendGrid email, CometChat, QR codes, generated PDF device records, Firebase notifications, and Google Maps services.
- Designed Firestore-to-PostgreSQL and BigQuery change-data workflows, reconciliation and test utilities, structured cloud logging, API rate limiting, and automated deployments.
- Directed and reviewed junior-developer work, created backend architecture training videos, and shaped product and system-design decisions with company leadership.

### High Bid Market Place Inc. · May 2023–October 2024

- Launched a software startup serving the automotive industry with a digital car dealership marketplace.
- Designed a multi-module Java 17/Spring Boot backend enabling dozens of dealerships to transact on the platform, with measured savings of approximately $500,000 annually for one client.
- Implemented inventory ingestion, dealer and customer workflows, offers, buy requests, payments, notifications, reporting, image processing, OAuth2 security, and rate-limited partner integrations using MongoDB and reactive services.
- Integrated LLMs to generate marketplace-specific vehicle listings and developed Python/CUDA image-processing services and automotive ML/data tooling.
- Built an internal Vaadin admin dashboard and Flutter dealership application for inventory oversight, leads, deal operations, and reporting.
- Deployed with Elastic Beanstalk, Lambda, S3, SQS/SNS, EventBridge/Scheduler, Cognito, Redis, Stripe, and Terraform-managed infrastructure; partnered with leadership on product direction and customer feedback.

### Automotive DMS and Integration Projects · 2023–2025

- Built C#/ASP.NET Core proofs of concept and production integration components for Stripe billing, 700Credit report retrieval, VinAudit VIN/YMMT data, MarketCheck inventory import and image upload, and QuickTags DMV services.
- Developed a generative-AI workflow for producing seller comments tailored to marketplaces such as CarGurus, Cars.com, and AutoTrader.
- Improved data parsing, persistence, null safety, signed-URL handling, image transfer, and API test coverage across automotive dealer-management workflows.

### MarketMind AI/ML Platform · May 2025

- Containerized and automated Google Cloud Run deployments for Python backend, question-generation, and answer-generation services using GitHub Actions and managed secrets.

## My Car Auction Inc. · Irvine, California

**Senior Software Engineer · July 2021–April 2023**

- Developed a consumer-facing app for instant car value estimates, attracting hundreds of monthly sellers in key markets.
- Built and maintained a custom CRM platform for dealerships to manage leads, inspections, logistics, and accounting integration, boosting process efficiency by 50%.
- Rebuilt the website's backend APIs with a focus on performance and usability, simplifying the car-selling experience.
- Developed Spring Boot services and AWS Lambda workflows spanning vehicle pricing and listing, inspections, dealer leads, notifications, payments, transportation, NetSuite accounting, identity, and partner data integrations.
- Standardized shared service libraries and GitHub Actions deployments and provided mentorship and troubleshooting support across a large multi-repository system.

## iHerb LLC · Irvine, California

**Software Developer II · April 2020–July 2021**

- Migrated Apache Solr infrastructure to Kubernetes, improving search performance and scalability.
- Enhanced product search rankings by implementing data-informed algorithms, improving user satisfaction.
- Conducted exploratory data analysis using BigQuery to uncover links between shopping patterns and product attributes.
- Extended backend services with new search features and improved API endpoints.

## Levyx Inc. · Irvine, California

**Software Engineer · January 2019–February 2020**

- Built high-performance Spark-based implementations of financial algorithms using Levyx's SSD-optimized datastore.
- Integrated custom C-based UDFs and Intel FPGAs to accelerate computation-heavy tasks.
- Developed and maintained client libraries in Spark, Java, and Python to simplify adoption of Levyx's data platforms.
- Containerized the platform using Docker to ease customer deployment and adoption.

## Radio Javan Inc. · Remote

**Android Developer · October 2016–January 2019**

- Rebuilt the Android app using modern architectural standards, supporting approximately 2 million monthly users.
- Integrated Google Cast, Sonos, and Android Auto, significantly improving cross-platform user experience.
- Implemented media queues and downloads, foreground playback services, audio-focus and headset-event handling, advertising flows, and compatibility updates across Android releases.
- Influenced iOS feature parity as Android enhancements were adopted across platforms.

## SpaceX · Irvine, California

**Engineering Intern · June 2018–September 2018**

- Built a web dashboard to visualize quality metrics such as test coverage and bug tracking across projects.
- Developed Python-based verification tools for satellite modem FPGA designs.

## Amazon Inc. · Seattle, Washington

**Software Engineering Intern · June 2017–September 2017**

- Created a React-based web tool to automate entitlement management for the Amazon Digital Goods team.
- Translated operational workflows into a self-service interface that reduced manual access-management effort for internal users.

## University of California, Irvine

**Teaching Assistant and Graduate Researcher · 2016–2018**

- Served as a teaching assistant for five academic quarters, assisting students in core computer-science courses.
- Built a React-based tool for academic researchers to analyze citation trends in graduate syllabi.
