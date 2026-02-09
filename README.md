# 🚀 GRPC from REST — Complete Learning Repository
This repository documents my journey of learning **gRPC from a REST developer’s perspective**, structured module-by-module like a professional training course.

It is designed for backend developers (especially Java/Spring developers) who already understand REST APIs and want to master **gRPC for microservices and internal communication**.

## 🎯 Why this repository exists
Most tutorials explain gRPC in isolation.
But real developers usually come from **REST backgrounds** and struggle with:
  1. No controllers or HTTP verbs
  2. .proto contracts
  3. Streaming concepts
  4. Client/server stubs
  5. Production patterns

This repo solves that by teaching:
  **How to think in gRPC if you already know REST**

## 🧠 What you will learn
  1. gRPC fundamentals
  2. REST → gRPC mental model shift
  3. Unary RPC (basic calls)
  4. CRUD service using gRPC
  5. Streaming (server, client, bidirectional)
  6. Error handling & status codes
  7. Metadata & interceptors
  8. Deadlines & retries
  9. Versioning best practices
  10. gRPC with Spring Boot
  11. Real-world microservice use cases

## 📚 Repository Structure (Module Based Learning)
This repository is structured like a training program.

GRPC-from-REST/
│
├── module-00-basics
├── module-01-unary-rpc
├── module-02-crud-service
├── module-03-streaming
├── module-04-error-handling
├── module-05-metadata-interceptors
├── module-06-deadlines-retries
├── module-07-versioning
├── module-08-grpc-springboot
└── module-09-real-world-case-study
Each module contains:
  - Theory
  - Code examples
  - Diagrams
  - How to run
  - Key takeaways

## 🏗 Learning Approach
This repo follows a **trainer-style progression**:

Module	Focus
Module 00	gRPC theory & mental model
Module 01	First unary gRPC call
Module 02	CRUD service (REST → gRPC mapping)
Module 03	Streaming (core strength of gRPC)
Module 04+	Production-ready concepts
You can follow modules in order like a course.

## 🆚 REST vs gRPC (Quick View)
REST	gRPC
URL + HTTP verbs	Method-based calls
JSON	Protobuf (binary)
HTTP/1.1	HTTP/2
Weak contracts	Strong contracts
Limited streaming	Full streaming support

## 🛠 Tech Stack
  - Java
  - gRPC Java
  - Protocol Buffers
  - Maven/Gradle
  - Spring Boot (later modules)

## 👨‍💻 Who this repo is for
Backend developers moving from REST → gRPC

Java/Spring developers

Microservice developers

Engineers preparing for system design interviews

Anyone wanting strong gRPC fundamentals

## ⭐ End Goal
By the end of this repository, you should be able to:

Design production-ready gRPC services

Replace REST with gRPC for internal microservices

Implement streaming correctly

Handle errors, retries, and metadata

Confidently use gRPC in real systems

## 📌 Author Note
This is a structured learning repository built while mastering gRPC deeply from a real-world backend engineering perspective.

If you're also transitioning from REST to gRPC, this repo will help you avoid common confusion and learn the right way.

## 🚀 Next Step
Start here:

➡ module-00-basics → Understanding gRPC fundamentals before coding

## ⭐ If this helps you
Star the repo and follow along the learning journey.
