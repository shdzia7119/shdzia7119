# Hi, I'm Shadi 👋

**Software Engineering senior at Arizona State University** building across the stack, from .NET services and AI-powered web products to native iOS apps, Linux kernel modules, and compilers.

- 🤖 Shipping AI-powered SaaS features in TypeScript with LLMs (Claude), on startup-sponsored projects
- 🟣 **C# and .NET:** WCF and REST services, ASP.NET MVC, and .NET MAUI
- 🌐 Full-stack web development with Next.js, React, TypeScript, and JavaScript
- 🐍 Python for data analysis, machine learning, and scripting
- 📱 Native iOS development with Swift, SwiftUI, and SwiftData
- ⚙️ Systems and language tooling in C and C++
- 🔐 Built ML fairness and data privacy evaluation pipelines in Python

---

## 💼 Industry-Sponsored Projects

### GetDeals.ai: AI-Powered LinkedIn Outreach Platform
*Team of 3 · 2026 · Live in production*

A SaaS platform that automates personalized LinkedIn outreach campaigns with AI-generated messaging.
- **Tech:** Next.js, TypeScript, Supabase (PostgreSQL), Stripe, Vercel, Claude API
- **What I built:** campaign controls (pause/resume/end, status badges, LinkedIn tier picker, messages page), Stripe billing portal integration, the registration flow and tier-aware dashboard, and settings persisted to Supabase. I also ran end-to-end QA across every subscription tier.

### Zevari AI: AI Go-To-Market Platform
*Team of 3 · Sept 2026 – present · Production*

An AI platform for sales workflows such as buying-signal detection and lead scoring.
- **Tech:** TypeScript monorepo (Turborepo, pnpm), React Router 7 on Cloudflare Workers, Node.js worker on Railway, PostgreSQL (Neon), Claude models, Vitest, GitHub Actions
- **What I built:** I own the signals track for third-party comment scanning. I generalized the AI classifier to handle comments (new intent types, subject-aware prompts), built the checkpoint/migration layer, and shipped the comment-scanner stage behind a feature flag. I also fixed a slow pre-push hook that was stalling git pushes for the whole team.

---

## 🛠️ Skills

**Languages:** C# · TypeScript · JavaScript · Swift · C · C++ · Python · Java · XML/XSD

**.NET:** .NET / .NET Framework · ASP.NET Web Forms · ASP.NET MVC · WCF (SOAP & RESTful) · .NET MAUI · Windows Forms · Windows Workflow Foundation

**Web & Cloud:** Next.js · React Router · Node.js · PostgreSQL · Supabase · Neon · Stripe · Vercel · Cloudflare Workers · Railway

**AI & ML:** Claude API / LLM integration · prompt design · scikit-learn · pandas · NumPy

**Apple:** SwiftUI · SwiftData · MapKit · Swift Charts · Combine · MVVM

**Tools & practices:** Git · GitHub Actions · Turborepo · pnpm · Vitest · JUnit · Visual Studio · Xcode · Linux · Scrum · UML

---

## 🚀 Featured Projects

> The source for these projects is in private repositories. **Code is available on request.**

### 🟣 .NET Service-Oriented Applications
A collection of distributed applications built on the Microsoft stack: reusable services, the clients that consume them, and full web and mobile front ends.
- **Tech:** C#, .NET, WCF, ASP.NET Web Forms, ASP.NET MVC, .NET MAUI, Windows Forms, Windows Workflow Foundation, XML/XPath/XSD
- **What I built:**
  - WCF services (SOAP and RESTful) for encryption/decryption, sorting, number-to-words conversion, word filtering, temperature conversion, inventory, and discounts, with "TryIt" pages for testing them
  - An ASP.NET Web Forms site with sign-up/sign-in (forms authentication and cookies), role-based components, and a backend WCF service
  - An ASP.NET MVC client that consumes the encryption service over HTTP
  - A **.NET MAUI** cross-platform mobile app (Android/iOS) for encrypting and decrypting text through the service
  - An XML data service for a national-parks dataset with XSD validation and XPath keyword search
  - A WCF chat client/service and a Windows Workflow Foundation activity library

### 📱 Japan Travel Planner: iOS App *(partner project)*
A SwiftUI app for planning trips to Japan: discover trending places on a map, save favorites, and organize day-by-day itineraries with notes.
- **Tech:** Swift, SwiftUI, SwiftData, MapKit, Swift Charts, Combine, URLSession/JSON, Geoapify Places API, XCTest
- **What I built:** a map-based place browser with mini-map previews, saved places and trip itineraries persisted with SwiftData, a trends view built with Swift Charts, and API integration that decodes place details (address, hours, website, rating), all using the MVVM pattern.

### 📱 iOS App Collection
Several smaller SwiftUI apps exploring core iOS patterns.
- **Tech:** Swift, SwiftUI, MVVM, MapKit, Swift Playgrounds
- **What I built:** a **personal finance tracker** (data entry, history, and a "How am I doing?" summary), a **map-based city explorer**, a **travel journal**, a **book list** app, a **favorite parks** app, a **world traveler** app, and a **shared-location** app demonstrating MVVM.

### ⚙️ Linux Kernel Modules
Loadable kernel modules and system-level programs that work directly with Linux process, memory, and file-system internals.
- **Tech:** C, C++, Linux kernel APIs, kthreads, semaphores, high-resolution timers, procfs, pthreads
- **What I built:**
  - A **memory manager** module that walks a process's page tables (PGD → PTE) on a high-resolution timer to report its resident set size, swap usage, and working set size
  - A **process-management** module using producer/consumer kernel threads synchronized with semaphores to gather per-process statistics
  - A **`/proc` file-system** module that exchanges data between user space and kernel space
  - A custom **system call**, plus user-space programs covering `fork`, pthreads, producer/consumer, memory-paging simulation, and file I/O with `std::filesystem`

### 🧩 Parsers, Grammar Analysis & Code Generation
Three language-processing tools written from scratch in C++.
- **Tech:** C++, recursive-descent parsing, Make
- **What I built:**
  - **Polynomial language interpreter:** parses a small language for declaring and evaluating polynomials, reports syntax and semantic errors, runs programs, warns about uninitialized variables and useless assignments, and computes polynomial degrees
  - **Grammar analyzer:** reads a context-free grammar and computes nullable, FIRST, and FOLLOW sets, then applies left factoring and left-recursion elimination
  - **Intermediate code generator:** compiles a small imperative language (assignments, I/O, `if`, `while`, `for`, `switch`) into an executable linked-list intermediate representation

### 🔐 Fairness Evaluation for Machine Learning
An end-to-end pipeline that trains a classifier and audits whether its predictions are fair across demographic groups.
- **Tech:** Python, scikit-learn, pandas, NumPy
- **What I built:** data preparation and train/test splitting, a scaled logistic-regression model, evaluation with accuracy, precision, recall, and F1, and fairness metrics for **demographic parity** and **equal opportunity**. I also wrote research reports on data privacy and security.

### 🧱 Also
- **Heap data structure** in C++ with a command-driven driver
- **Software testing:** unit tests with JUnit, test design, coverage criteria, and Petri-net modeling
- **Team software engineering:** requirements, UML design, risk management, and prototyping with a Scrum team

---

## 📫 Contact

- **LinkedIn:** [linkedin.com/in/shadi-ziaee-31a748408](https://www.linkedin.com/in/shadi-ziaee-31a748408)

Code for any of these projects is available on request. Feel free to reach out on LinkedIn.
