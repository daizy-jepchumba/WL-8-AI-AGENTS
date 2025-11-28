AI Agents Assignment – AutoParts Inc. Case Study

This repository contains my submission for the AI Agents assignment, which demonstrates both theoretical understanding and practical implementation of AI Agents in a smart manufacturing environment.

Contents

Short Answer Questions

Analysis and comparison of AI Agent frameworks (LangChain vs AutoGen).

Applications of AI Agents in supply chain management.

Human-Agent Symbiosis and its significance.

Ethical implications of autonomous AI Agents in finance.

Technical challenges of memory and state management in AI Agents.

Case Study Analysis – AutoParts Inc.

A detailed AI Agent implementation strategy covering:

Predictive Maintenance Agent

Quality Control Agent

Production Planning Agent

Optional agents: Supply Chain Agent, Customer Feedback Agent

Expected ROI and implementation timeline

Risks and mitigation strategies (technical, organizational, and ethical)

Word count: 445 (meets assignment requirement of 400–800 words)

Simulation Workflow – n8n

Demonstrates AI Agent operations using Webhook and Function nodes.

Shows automated alerts, real-time monitoring, and data processing for predictive maintenance, quality control, and production planning.

Workflow Link

You can view and interact with the simulation workflow directly in n8n cloud:https://daizyd.app.n8n.cloud/workflow/Tp2vNpQqD5rrPBbi

Open Workflow in n8n

Usage Instructions

Open the workflow link in n8n cloud.

Activate the workflow to enable the webhook.

Trigger the workflow using the Test button or a POST request with JSON data:

{
  "machine": "Lathe-01",
  "temperature": 85,
  "defect_rate": 12
}


View the Function node output to see AI-generated alerts for predictive maintenance and quality control.

This README provides a complete overview of both the theoretical case study and the practical simulation workflow, demonstrating the application of AI Agents in a real-world manufacturing scenario.
