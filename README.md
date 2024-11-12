# Postman Newman Tests

This repository is for practicing API test automation using **Postman** and **Newman**. It includes Postman collections, environments, and GitHub Actions workflows to automate API testing.

## Project Structure

- **collections/**: Contains Postman collections with API test cases.
- **envs/**: Stores Postman environment files for managing configurations.
- **.github/workflows/**: Holds GitHub Actions workflows for automated test runs.

## Requirements

- **Node.js** (v16+ recommended)
- **Newman**: Run `npm install -g newman` if not already installed.

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/LukegTester/postman-nevman-tests.git
   cd postman-nevman-tests
2. **Install Dependencies**:
   ```bash
   npm install

## Usage

1. **To run tests with the default environment and generate an HTML report**:
   ```bash
   npm run test
2. **To display a progress bar during the test run**:
   ```bash
   npm run test:progress
   
