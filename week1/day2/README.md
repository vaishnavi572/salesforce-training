# Salesforce Platform Basics

## Introduction

Salesforce is a cloud-based CRM platform used by companies to manage customer information, sales processes, services, and business operations. It helps organizations store data, automate tasks, improve communication, and build business applications without needing heavy infrastructure.

The Salesforce Platform allows users to create custom applications, automate workflows, generate reports, and manage business data efficiently. Since it is cloud-based, users can access Salesforce from anywhere using the internet.

---

# What is an App?

An App in Salesforce is a collection of tools, tabs, objects, and features grouped together for a specific business purpose.

Apps help users organize their work in one place.

Examples:
- Sales App
- Service App
- Marketing App

A Sales App may contain:
- Accounts
- Contacts
- Leads
- Opportunities

Apps make navigation easier for users.

---

# What is an Object?

An Object is used to store data in Salesforce.

Objects are similar to database tables or Excel sheets.

Examples:
- Account Object
- Contact Object
- Opportunity Object

Objects contain records and fields.

For example:
A Student object may contain:
- Name
- Roll Number
- Department

Salesforce has:
- Standard Objects (already provided)
- Custom Objects (created by users)

---

# What is a Tab?

A Tab is used to access objects, records, and features in Salesforce.

Tabs appear in the navigation menu.

Examples:
- Accounts Tab
- Contacts Tab
- Opportunities Tab

When users click a tab, Salesforce opens related records and pages.

Tabs improve navigation and user experience.

---

# Configuration vs Coding

Salesforce development mainly uses two approaches: configuration and coding.

## Configuration

Configuration means building features using Salesforce tools without writing code.

Examples:
- Creating objects
- Creating fields
- Page layouts
- Flows
- Reports

Configuration is also called:
- Clicks
- Low-code development

It is mainly used by Salesforce Admins.

---

## Coding

Coding means developing advanced features using programming languages.

Salesforce developers use:
- Apex
- Lightning Web Components (LWC)
- APIs

Coding is used for:
- Complex business logic
- Integrations
- Custom UI
- Advanced automation

---

# System Design Example — College Admission System

## App
College Admission App

---

## Objects

### Student Object
Stores:
- Student Name
- Phone Number
- Department

### Course Object
Stores:
- Course Name
- Fees
- Duration

### Admission Object
Stores:
- Admission Status
- Payment Details
- Enrollment Date

---

## User Interaction

1. Student submits inquiry.
2. Staff creates student record.
3. Admission process begins.
4. Student selects course.
5. Admission gets confirmed.
6. Data is stored in Salesforce.

---

# screenshots

 ├── Tabs
 │     ├── Objects
 │            ├── Records
