# Ads Agent Sandbox privacy policy

Updated 24 September 2026.


Ads Agent Sandbox is Naman Jaiswal's personal ad-agent development and testing project. It is currently used for controlled Meta sandbox testing, not public customer onboarding.


## Information processed

The application processes account and Page identifiers, account names, currency and time zone, campaign/ad-set/ad configuration, and data returned by authorized Meta API requests. It stores local user identity and role information, access grants, encrypted connection credentials, chat requests and replies, conversation checkpoints, proposed actions, approvals, execution records and audit information. Uploaded test images may be stored locally and sent to Meta to test creative creation.


## Purpose and service providers

This information is used to connect authorized assets, answer requests, test ad-management workflows, enforce access and approval rules, and diagnose failures. Meta receives API requests and any test assets submitted to it. The configured language-model provider receives chat text, account context and selected API results for interpretation and responses. The current workstation uses OpenAI through the LiteLLM library. Cloudflare carries traffic to the temporary HTTPS development endpoint and may process connection information. These providers process information under their own policies.


Do not enter passwords, access tokens or unrelated personal information into chat. Provider credentials are kept outside model conversation state and stored encrypted. The application has no advertising trackers or data-sale feature. Its local interface uses browser storage for sign-in state and an onboarding cookie when the connection flow is used.


## Storage and retention

Application records are stored on the operator's workstation in a PostgreSQL database and local files. This development system does not currently have an automatic retention schedule; records remain until manually removed. External providers may retain their own records under their policies. Encryption and access restrictions reduce risk but do not guarantee absolute security.


## Access, disconnection and deletion

You can ask the operator to review, correct or delete information associated with your use of this app, or to disconnect an integration. See the [data-deletion instructions](DATA-DELETION.md). Removing an app's access in Meta stops future access but does not by itself erase records already held locally.


## Contact and changes

Contact Naman Jaiswal at [namanjaiswalofficial@gmail.com](mailto:namanjaiswalofficial@gmail.com). This policy will be updated when the project's data practices change. Check the date above for the current version.


[Testing terms](TERMS.md)


GitHub hosts these public information documents and processes website requests under its own privacy policy.
