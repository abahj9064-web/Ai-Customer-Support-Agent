# AI Customer Support Agent

An AI-powered customer support workflow designed to help businesses handle routine enquiries, retrieve available customer information, and organize issues requiring human attention.

## The Problem

Businesses can spend considerable time answering repetitive questions, checking order details, and managing customer complaints.

This system is designed to streamline routine support tasks while keeping human staff involved when necessary.

## Key Features

- Answers common questions about products and services
- Provides information about business hours, locations, and policies when available
- Retrieves available order information using an order number
- Retrieves available customer information and order history using a phone number
- Responds calmly to customer complaints
- Records issues requiring human attention in Google Sheets
- Helps staff track escalations and pending cases

## How It Works

1. A customer submits a question or request.
2. The AI agent interprets the request and determines what information is needed.
3. Connected tools retrieve available business, customer, or order information.
4. The agent responds using the information available to it.
5. Issues requiring human attention are recorded for follow-up.

## Technology Stack

- n8n — Workflow automation
- AI language models — Customer enquiry processing
- Google Sheets — Customer information and escalation tracking
- Connected data sources — Retrieval of available customer and order information

## Human Oversight

The system is designed to recognize issues that require human attention.

Customer complaints, uncertain answers, and cases that cannot be resolved using available information should be escalated appropriately.

## Project Status

Portfolio project demonstrating AI-assisted customer support, workflow automation, information retrieval, and escalation management.

## Important Note

The information available to the agent depends on its configured data sources and integrations. Website live chat, production order-system integrations, and additional messaging channels may require further implementation.