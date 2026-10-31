NetScope

<p align="center">
  <img src="logo.png" alt="NetScope Logo" width="160">
</p><h1 align="center">NetScope</h1><p align="center">
  Lightweight Network Monitoring & IP Intelligence for Windows.
</p><p align="center">
  <a href="https://github.com/fisherman-Qbit/NetScope/releases">Download</a> •
  <a href="https://github.com/fisherman-Qbit/NetScope/issues">Report an Issue</a> •
  <a href="Privacy%20policy.md">Privacy Policy</a>
</p>---

Overview

NetScope is a lightweight Windows application developed by Fisherman-Qbit, designed to monitor public IP addresses, detect network changes, and provide essential network information through a simple desktop interface.

Built with C++, NetScope focuses on performance, minimal resource usage, and practical network visibility.

Features

Network Information

- Public IPv4 detection.
- Public IPv6 detection.
- IP geolocation and country identification.
- Configurable IP information providers.

Background Monitoring

- Continuous IP monitoring in the background.
- IP change detection.
- Country change detection.
- Notifications when relevant network changes occur.
- Monitoring can be paused or resumed.
- Runs in the Windows system tray when the main window is closed.

Logging

- Local error logging.
- Diagnostic information stored on the user's system.

Application Settings

- Persian and English interface languages.
- Light and dark themes.
- Configurable monitoring preferences.
- Local application settings.
- Update availability notifications.

Privacy & Data Handling

NetScope is designed to minimize data collection.

- Application settings are stored locally.
- Error logs are stored locally.
- NetScope does not send application settings or local logs to the developer's servers.
- No telemetry or usage analytics are intentionally collected.

Network information providers may receive network requests when the application retrieves public IP or geolocation information. Their handling of connection metadata is governed by their respective privacy policies.

For further information, see the "Privacy Policy" (Privacy%20policy.md).

System Requirements

Requirement| Details
Operating System| Windows 11 recommended
Programming Language| C++
Distribution| Portable ZIP
Administrator Privileges| Not required
Interface Languages| Persian, English

Download & Installation

1. Visit the "GitHub Releases" (https://github.com/fisherman-Qbit/NetScope/releases) page.
2. Download the latest ZIP archive.
3. Extract the archive.
4. Run "NetScope.exe".

NetScope is portable and does not require a traditional installation process.

Background Behavior

NetScope continues monitoring network changes after its main window is closed by remaining active in the Windows system tray.

Monitoring can be paused or resumed through the application.

Automatic startup with Windows is not currently provided.

Updates

NetScope can check for newer releases and notify users when an update is available.

Downloading and installing updates is currently a manual process.

Roadmap

Planned improvements include:

- Offline functionality improvements.
- Russian language support.
- Enhanced logging and diagnostics.
- Additional monitoring improvements.

Reporting Issues

To report a bug or request a feature, visit:

"GitHub Issues" (https://github.com/fisherman-Qbit/NetScope/issues)

Please include:

- NetScope version.
- Windows version.
- Steps to reproduce the issue.
- Relevant error logs, after removing sensitive information.

License

NetScope is distributed under its own license.

Read the "LICENSE" (LICENSE) file before using or redistributing the software.

---

<p align="center">
  <strong>NetScope</strong><br>
  Network Visibility. Without Unnecessary Overhead.
</p>