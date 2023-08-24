---
description: >-
  Enable effortless communication and collaboration across platforms, empowering
  individuals and teams to connect on their terms and seamlessly and securely
  share information.
---

# Rocket.Chat Federation

Rocket.Chat leverages the Matrix communication protocol for decentralized and interoperable communications.

Bridging [Matrix ](https://matrix.org/)with Rocket.Chat \*\*\*\* makes it simple for organizations to easily connect and collaborate with external parties, whether they're using Rocket.Chat or any other Matrix-compatible platform.

{% hint style="danger" %}
We don't support encrypted rooms yet.
{% endhint %}

{% content-ref url="../workspace-administration/settings/federation/matrix-bridge/" %}
[matrix-bridge](../workspace-administration/settings/federation/matrix-bridge/)
{% endcontent-ref %}

## Features

* <mark style="color:green;">**Current**</mark>
  * Create federated channels, groups, DMs, and multi-user DMs from the UI (EE version).
  * Invite external users to federated channels, groups, DMs, and multi-user DMs from the UI (EE version).
  * Invite multiple users to multi-user DMs using slash commands (EE version).
  * Invite an external user to DMs using slash commands (EE/CE version).
  * Send/Receive attachments (Files, audio, and video messages) (EE/CE version).
  * Edit Messages (EE/CE version).
  * Delete Messages (EE/CE version).
  * Quote Messages (EE/CE version).
  * Reactions (EE/CE version).
  * Send emojis (EE/CE version).
  * Mention internal and external users in federated channels (EE/CE version).
  * User's avatar synchronization (EE/CE version).
  * User's typing indicator (EE/CE version) ([More Info](../workspace-administration/settings/federation/matrix-bridge/matrix-admin-guide/matrix-homeserver-setup/#important-warning-about-the-installation))
  * Define permissions for users inside rooms. (EE/CE version)
  * Support for the [Markdown spec](https://spec.commonmark.org/0.30/).
* <mark style="color:yellow;">**Confirmed Next Features**</mark>
  * Search public rooms in the Matrix Network (EE version).
  * Servers allow list/block list ([More info](../workspace-administration/settings/federation/matrix-bridge/matrix-admin-guide/matrix-homeserver-setup/matrix-allow-block-list.md)).
  * CLI to have a smooth setup experience.
