# Codebook: Security and Privacy in Shared LLM Application Accounts

This codebook presents the themes, sub-themes, codes and definitions derived from the analysis of users' perceptions, practices, and challenges regarding shared LLM accounts.

## Theme 1: Sharing Settings (RQ1)

### Sub-Theme 1: Motivations for Sharing
*Drivers that prompt users to utilize shared LLM accounts rather than individual subscriptions.*

| Code | Definition | 
| :--- | :--- | 
| **Lower Cost** | Share LLM application accounts to reduce financial burden. | 
| **Premium Usage** | Share LLM application accounts to access advanced, paid model capabilities. | 
| **Access Barriers** | Overcoming restrictions such as unsupported payment methods or regional network blocks. | 
| **Intermittent Demand** | Matching short-term or intensive usage needs such as course assignments. | 
| **Collaborative Work** | Share accounts just because it is provided in a group setting, such as institutional-affiliated accounts or lab settings. | 

### Sub-Theme 2: Sharing Arrangements
*The context of who the account is shared with.*

| Code | Definition | 
| :--- | :--- |
| **Common Credential** | Multiple users logging into the exact same account, often seeing synchronized chat histories. | 
| **Operator-Mediated Access** | Access coordinated by third-party sellers who assign strangers to a shared account pool. 
| **Separated API Access** | Pooling capacity (e.g., token quotas) without synchronizing conversational history. | 
| **Relational Closeness** | Sharing ranging from intimate (partners/family), to known (friends/colleagues), to unknown (strangers). |

## Theme 2: Perceived Risks (RQ1)
*Security, privacy, and usability vulnerabilities recognized by users within shared LLM ecosystems.*

| Code | Definition |
| :--- | :--- |
| **Data Leakage to Co-User** | Exposure of prompts, drafts, IP, or personal info to other members of the shared account. | 
| **Shared Account Provider Access** | Third-party marketplace operators potentially inspecting, exporting, or selling backend conversation logs. | 
| **Model Provider Access** | LLM providers retaining, reviewing, or training on user data without verifiable user control. | 
| **Snooping** | Deliberate, unauthorized viewing of another user's chat history, often driven by curiosity. |
| **Indirect Leakage** | Inference of private activities or offline identity simply by viewing chat titles or metadata. |
| **Account Access Loss** | Losing legitimate access to the account and retained data due to bans, password changes, or seller actions. | 
| **Output Contamination** | The LLM incorporating another user's persona, background, or data into the current user's generated response. | 
| **Conversation Loss** | Co-users or operators accidentally or intentionally deleting chat histories and generated artifacts. | 
| **Quota Competition** | Co-users exhausting pooled usage limits, rendering the service temporarily unavailable. | 

## Theme 3: Protective Practices (RQ2)
*Strategies and behaviors users employ to mitigate identified S&P risks and usability issues.*

### Sub-Theme 1: Data and Access Control

| Code | Definition | 
| :--- | :--- | 
| **Chat & Memory Deletion** | Removing sensitive chats or clearing model memory immediately after usage. | 
| **Temporary Chat** | Use temporary settings of LLMs to avoid chats being seen. | 
| **Training Opt-out** | Opt-out of training to avoid data leakage. | 
| **Input Sanitization** | Obfuscating sensitive details (e.g., names, precise locations, company names) before submitting prompts. | 
| **Task Separation** | Reserving shared accounts for generic/safe tasks while using personal accounts for sensitive workloads. | 
| **Named Workspaces** | Creating designated folders or projects labeled with member names to establish psychological boundaries against snooping. | 
| **Separated Environments** | Utilizing local terminal sessions, private API keys, or specific virtual machines to isolate data. | 
| **Credential Management** | Frequently changing passwords or enabling 2FA to revoke temporary access or secure the account. | 

### Sub-Theme 2: Social Governance
| Sub-Theme | Definition | 
| :--- | :--- | 
| **Trusted Co-Users** | Restricting sharing arrangements exclusively to individuals with high social trust. |
| **Social Contracts** | Establishing explicit ground rules among sharers regarding behavior, access, and modifications. | 

### Sub-Theme 3: Audit, Verification and Recovery
| Sub-Theme | Definition | 
| :--- | :--- | 
| **Seller Vetting** | Choosing marketplace operators based on reputation, reviews, or personal referrals. | 
| **Monitoring** | Monitor methods such as checking login IPs/locations, using packet capture software
| **Backups** | Exporting local backups of chats. | 

## Theme 4: Mitigation Challenges (RQ3)
*Frictions and barriers that prevent users from effectively securing their shared LLM usage.*

| Sub-Theme | Definition | 
| :--- | :--- | 
| **Processing Opacity** | Inability to verify how data is handled on the backend or who has technical access. | 
| **Missing Auditability** | Lack of system logs or notifications to attribute actions (e.g., deletion or snooping) to specific users. | 
| **Unequal Account Control** | Power imbalances between primary owners (e.g., employers, supervisors) and secondary users, complicating access revocation. | 
| **Limited Channel & Recourse** | Lack of formal support, refund mechanisms, or oversight against malicious third-party sellers. | 
| **Privacy-Utility Trade-off** | Mitigation tactics (like deleting chats or disabling memory) directly degrading the LLM's usefulness and contextual continuity. | 
