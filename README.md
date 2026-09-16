# ✈️ Premium Travels — WhatsApp AI Travel Agent

An AI-powered WhatsApp Travel Agent built with **n8n, WhatsApp Business Cloud, Google Sheets, and AI**.

The system automates the complete customer journey from package discovery to booking confirmation while keeping travel package data dynamically managed through Google Sheets.

---

## 🚀 Project Overview

Premium Travels WhatsApp AI Travel Agent is an end-to-end business automation system designed to help customers:

- Explore tour packages
- View Hajj packages
- View Umrah packages
- Check office location and business information
- Request human assistance
- Get package details and documents
- Book a selected package through an AI-powered conversation
- Confirm or cancel a booking

The workflow is designed so that the client can manage package information through Google Sheets without rebuilding the n8n workflow.

---

## 🏗️ Technology Stack

- **n8n** — Workflow automation
- **WhatsApp Business Cloud API** — Customer communication
- **Google Sheets** — Dynamic business data source
- **AI Agent** — Booking information collection and validation
- **n8n Data Tables** — User state and session management
- **HTTP Request / REST APIs** — WhatsApp API integration

---

## 🔄 Customer Journey

```text
Customer sends "Hi"
        ↓
Welcome + Get Started
        ↓
Main Menu
        ↓
 ┌───────────────┬──────────────┬──────────────┬──────────────┬──────────────┐
 ↓               ↓              ↓              ↓              ↓
Tour Packages   Hajj          Umrah        Office         Human
 ↓               ↓              ↓              ↓              ↓
Destinations    Packages      Packages     Location       Staff Request
 ↓               ↓              ↓
Package List    Package List  Package List
 ↓               ↓              ↓
Package Details Package Details Package Details
 ↓
Book Package
 ↓
AI Booking Agent
 ↓
Validation
 ↓
Booking Summary
 ↓
Confirm Booking
 ↓
Booking_Requests
