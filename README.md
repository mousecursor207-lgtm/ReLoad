# ReLoad! 0.1 — Windows prototype

## Included
- `ReLoad.vbs` — launches the graphical interface.
- `ReLoad.hta` — a basic Windows-style interface with Connect and Prepare to share buttons.

## Run it
1. Extract this ZIP to a folder on a Windows computer.
2. Keep both files in the same folder.
3. Double-click `ReLoad.vbs` (or double-click `ReLoad.hta` directly).

If Windows or your organization's security settings block VBScript/HTA, do not bypass a managed-device policy; use a device where you are permitted to run local scripts.

## Important limitations
This is only the user-interface prototype. The Connect button does not make a network connection, and no screen capture, streaming, authentication, encryption, or remote input is implemented yet. Do not use it to access another computer; it cannot do so.

## Next engineering stage
Implement a separate, authenticated Windows helper service/app for screen capture and streaming. The host must display a clear consent prompt, show an obvious active-sharing indicator, allow immediate disconnect, and use encrypted authenticated connections. Start with a trusted local network; internet connectivity usually requires a secure relay or carefully configured network traversal.
