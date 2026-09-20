ECTO OS FOUNDATION BUILD
==========================

This folder contains the first clean ECTO OS foundation.

Included:
- ECTO OS main menu shell
- RESPONSE MAP naming
- Local persistent database using browser storage
- Automatic saving
- Administrator-protected Configuration
- Administrator-protected Import/Export
- Initial location, team and vehicle data structures
- Placeholder modules for future Dispatch, Spectre Database, Incident Log, Containment Grid and Diagnostics

IMPORTANT:
The administrator passcode is initially ECTO-ADMIN-1984. On first successful unlock it is stored locally and can later be replaced by the password-management implementation.

This is a client-side prototype. The passcode protects the UI and data-management workflow on the device, but it is not equivalent to server-side security against someone with direct access to the source files/browser storage.

Open ecto-os/index.html in a browser to test the foundation.
