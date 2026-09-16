# Smart Email Writer

Smart Email Writer is a Chrome Extension that helps users write email replies faster and more effectively directly within Gmail.

It uses AI to understand the context of an email and generate a natural, relevant reply that matches the communication style of the original message.

## Features

- AI-powered email reply generation
- Context-aware responses
- Automatic tone matching
- Natural and professional email writing
- One-click reply generation
- Direct integration with Gmail's compose window
- Review and edit generated replies before sending
- Simple and minimal interface

## How It Works

Smart Email Writer integrates directly into Gmail and adds a **Smart Reply** option to the email compose interface.

The typical workflow is:

```text
Open Gmail
    ↓
Open an email
    ↓
Click Reply
    ↓
Click "Smart Reply"
    ↓
AI analyzes the email
    ↓
Reply is generated
    ↓
Review and edit
    ↓
Send
````

## Automatic Tone Matching

Smart Email Writer analyzes the communication style of the original email and generates a response with an appropriate tone.

It can adapt to different styles such as:

* Professional
* Formal
* Friendly
* Casual
* Conversational
* Appreciative
* Urgent
* Concise

This allows the generated response to feel more natural and appropriate to the conversation.

## Gmail Integration

The extension works directly within Gmail.

Once installed, the **Smart Reply** button appears in the Gmail compose interface, allowing users to generate a response without switching to another application.

The generated response is inserted directly into the compose box, where it can be reviewed and edited before sending.

## Installation

Smart Email Writer is currently distributed as an unpacked Chrome Extension.

### Step 1 — Download

Download the `extension.zip` file from this repository.

Extract the ZIP file to a location on your computer.

### Step 2 — Open Chrome Extensions

Open Google Chrome and navigate to:

```text
chrome://extensions
```

Enable **Developer mode** in the top-right corner.

### Step 3 — Load the Extension

Click **Load unpacked**.

Select the extracted `extension` folder.

Chrome will load Smart Email Writer as an installed extension.

### Step 4 — Open Gmail

Open Gmail and open an email.

Click **Reply** and look for the **Smart Reply** button.

## Usage

1. Open an email in Gmail.
2. Click **Reply**.
3. Select **Smart Reply**.
4. Wait for the response to be generated.
5. Review the generated response.
6. Edit it if necessary.
7. Send the email.

## Installation Tutorial

A short video tutorial is provided to demonstrate the complete installation process.

The video shows:

* Downloading the extension
* Extracting the ZIP file
* Opening Chrome Extensions
* Enabling Developer Mode
* Loading the unpacked extension
* Opening Gmail
* Using Smart Reply

## Project Structure

```text
extension/
├── manifest.json
├── content.js
├── content.css
└── icons/
```

## Project Status

Smart Email Writer is currently available for manual installation using Chrome's **Load unpacked** functionality.

It is intended for demonstration and portfolio use.
