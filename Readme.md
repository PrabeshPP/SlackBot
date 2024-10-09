# Slack Bot Using Golang

A fully functional Slack Bot using Golang. This bot interacts with Slack channels, listens to events, and responds to mentions using the Slack API and Socket Mode.

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
4. [Usage](#usage)
    - [Running the Application](#running-the-application)
5. [Bot Functionality](#bot-functionality)
6. [Events API Integration](#events-api-integration)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction
This project demonstrates how to develop a Slack Bot using the `go-slack` package in Golang. It connects to a Slack workspace, responds to user commands, and interacts with Slack channels through events like mentions. The bot leverages WebSocket via Slack's Socket Mode to handle real-time event processing.

## Features
- Post messages in Slack channels
- Listen for and respond to mentions
- Handle various events using Slack's Events API
- Customize bot responses based on user input
- WebSocket support for real-time communication

## Getting Started

### Prerequisites
Ensure you have the following installed:
- Go 1.22.4 or higher
- A Slack Workspace
- A Slack App with permissions (OAuth tokens, event subscriptions, etc.)

### Installation

1. **Clone the repository**:
   ```bash
    git clone https://github.com/PrabeshPP/SlackBot
    cd SlackBot 


## Usage
```go run main.go```
    


##
MIT License

Copyright (c) 2024 Prabesh Bista

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

