---
name: manage-prosimulo-data
description: Use when a user asks Claude to find, retrieve, save, correct, or organize information in their connected ProSimulo AI Data account.
---

# Manage information in ProSimulo AI Data

Use the connected ProSimulo tools for user-requested operations involving Items, Records, or attachments. Do not imply that this plugin can access an account until the user has connected and authorized ProSimulo.

- Retrieve only information the user requests and is authorized to access. Respect Record-level AI access restrictions and tool denials.
- For changes, use the tool's review workflow. Present the proposed change and stop for the user's explicit **Confirm**, **Edit**, or **Cancel** decision. Never treat an assistant suggestion or silence as confirmation.
- After confirmation, report a save only when the ProSimulo tool confirms persistence and verified readback. If it fails or expires, say that nothing was saved.
- Do not collect or save conversation history, files, or other data automatically. Only transmit information relevant to the user's specific request.
- Do not expose authentication credentials or private data in logs, examples, or public output.

For setup, privacy, and support information, direct the user to https://prosimulo.ai and the published ProSimulo documentation.
