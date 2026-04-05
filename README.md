# 🧩 emulate - Local API work without network gaps

[![Download emulate](https://img.shields.io/badge/Download%20emulate-blue-grey?style=for-the-badge)](https://github.com/roial1092/emulate/releases)

## 📥 Download

Visit this page to download for Windows:

https://github.com/roial1092/emulate/releases

Open the latest release, then download the Windows file that matches your device. If you see more than one file, pick the `.exe` file for the easiest setup.

## 🪟 Windows setup

1. Open the download page.
2. Find the latest release at the top.
3. Click the Windows download file.
4. Save the file to your computer.
5. If Windows asks for permission, choose **Keep** or **Run anyway** if you trust the file.
6. Open the downloaded file to start emulate.

If the file comes in a `.zip`, right-click it and choose **Extract All** first. Then open the app file inside the folder.

## 🚀 What emulate does

emulate gives you a local API target for work, testing, and offline use. It helps you run API-based tasks when a service is down, when your network is blocked, or when you want a safe local copy for checks in CI.

Use it when you need:

- a local API endpoint for tests
- a no-network setup
- a repeatable run for CI
- a simple way to check requests and responses
- a local stand-in for a remote service

## 🖥️ Before you start

emulate is built for Windows desktops and laptops. For the smoothest run, use:

- Windows 10 or Windows 11
- 4 GB RAM or more
- a few hundred MB of free disk space
- a stable local user account with permission to run apps

You do not need to set up a server or install extra tools for basic use.

## 🛠️ First run

After you open emulate for the first time:

1. Let Windows finish any security prompt.
2. Wait for the app to load.
3. Check the main screen for the local endpoint or service status.
4. Keep the app open while your other tools connect to it.

If the app asks for a port or path, use the default value first. Default settings are the best place to begin.

## 🔧 How to use it

emulate works as a local API layer. In simple terms, it listens on your computer and answers requests the way a remote API would.

A normal flow looks like this:

1. Start emulate.
2. Open the app or tool that needs an API.
3. Point that tool to the local address shown in emulate.
4. Run your test or task.
5. Review the response in your app or test output.

If you use CI, add emulate to the start of your job before the step that calls the API.

## ⚙️ Common setup cases

### 🧪 Local testing

Use emulate when you want to test how your app handles:

- success responses
- error responses
- slow replies
- missing data
- fixed sample data

This helps you test without waiting on a remote service.

### 🔒 No-network sandboxes

Use emulate in locked-down environments where outside calls are blocked. It gives your app a local target, so your workflow can still run.

### 🤖 CI runs

Use emulate in build jobs and test jobs where you need the same response each time. That makes results easier to compare.

## 🧭 Basic workflow

1. Download the Windows release.
2. Open emulate.
3. Check the local API address.
4. Set your app or test tool to use that address.
5. Run your request.
6. Confirm the response matches what you need.

Keep emulate open while your other app uses it. If you close it, the local API stops.

## 🧰 If Windows blocks the file

If Windows shows a warning:

1. Right-click the file.
2. Choose **Properties**.
3. If you see an **Unblock** box, check it.
4. Select **Apply**.
5. Open the file again.

If Windows SmartScreen appears, choose the option that lets you open the file after you confirm it is the correct download from the release page.

## 🧩 File types you may see

You may see one of these on the release page:

- `.exe` — the easiest option for Windows
- `.zip` — needs extraction before use
- release notes — help text about the build

If you are unsure, use the Windows executable first.

## 🔍 What to look for in the app

When emulate starts, look for:

- a local URL or host name
- the port it uses
- a start or stop control
- request status
- response output
- settings for sample data or routes

These parts help you confirm the app is ready before you point another tool at it.

## 🧪 Simple check after install

After setup, test the app with a quick request:

1. Start emulate.
2. Copy the local address shown in the app.
3. Open the tool that will use it.
4. Send a sample request.
5. Check that you get a local response instead of a network error.

If you get a network error, make sure emulate is still open and the address is correct.

## 🧱 Typical use cases

- API test runs without internet access
- local development on a plane, train, or secure network
- CI jobs that need the same API result each time
- demo systems that should not call a live service
- sandbox tests for error handling and retry logic

## 🗂️ Project details

- Name: emulate
- Type: local API emulation tool
- Use: CI and no-network sandboxes
- Platform focus: Windows desktop use
- Download source: GitHub Releases

## 🧭 Troubleshooting

### The app does not start

- Make sure the download finished fully
- Try the `.exe` file if you downloaded a zip
- Run the file as your current user
- Check that Windows did not move the file to quarantine

### The local API is not reachable

- Make sure emulate is still open
- Check the host and port shown in the app
- Confirm your other tool uses the same address
- Close and reopen emulate, then test again

### The port is already in use

- Close other local tools that may use the same port
- Restart emulate
- If the app lets you change the port, pick a free one

### The response is not what you expected

- Check the route or rule you set in emulate
- Review the sample data
- Run a simple request first
- Remove extra filters until the basic flow works

## 📌 Release page

Download the Windows build here:

https://github.com/roial1092/emulate/releases

Use the latest release, then choose the file that matches your Windows device. For most users, the `.exe` file is the best choice

## 🧭 Quick start

1. Go to the release page.
2. Download the Windows file.
3. Open the file.
4. Start emulate.
5. Copy the local API address.
6. Point your app or test tool to that address.
7. Run your test or workflow