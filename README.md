The Module Scanner Tool is a forensic and reverse engineering utility designed to scan all loaded .exe and .dll files on a system or within a specified process. It identifies each file’s digital signature status and categorizes them into separate folders for further analysis.

Key Features:

✅ Scans all loaded .exe and .dll files from memory or disk.

🔐 Verifies digital signatures using robust certificate chain analysis.

🚨 Detects and separates:

Unsigned executables (.exe)

Unsigned dynamic-link libraries (.dll)

Fake-signed executables and DLLs (e.g., invalid, broken, or self-signed certs)

📂 Automatically organizes results into structured folders:

<Unsigned_EXE>

<Unsigned_DLL>

<FakeSigned_EXE>

<FakeSigned_DLL>

Use Cases:

Malware analysis and incident response

Detecting suspicious or tampered binaries

Auditing third-party software compliance

Reverse engineering and threat hunting

Example Workflow:

Launch the tool.
Wait For Results
You Will Get 4 Folders On Your Home Screen
