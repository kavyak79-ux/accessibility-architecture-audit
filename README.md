# Accessibility Baseline & Repository Architecture Audit

## Project Overview 

This project contains an accessibility audit of the Karnataka Government Website and a basic full-stack project structure.

## Website Audited

**Website:** Karnataka Government Website

**URL:** https://karnataka.gov.in/english

## Repository Structure

- `client/` - Frontend application
- `server/` - Backend application
- `docs/` - Audit report and screenshots
- `test/` - Testing files
- `README.md` - Project documentation

## Architecture

The frontend will be responsible for the user interface and user interactions.

The backend will handle APIs, business logic, and data processing.

The `client` communicates with the `server` through APIs.

## Local Setup

Clone the repository and open the project folder.

```bash
git clone <repository-url>
cd accessibility-architecture-audit

## First Feature

The first feature will be an accessible public-service information page.

### Feature Flow

User → Client → Server API → Data → Server Response → Client

The client will display the public-service information using accessible headings, buttons, links, and images.

The server will provide the required information through an API.

The test folder will be used to test the feature and its accessibility requirements.
