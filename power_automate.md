# ⚡ Power Automate

## 🔄 Как процесът се активизира:

### 📌 Схема 1: Стартиране на Flow

```mermaid
flowchart LR
    A[Triggers] --> B[Start the Flow]

graph TD
    Create[Create] --> A1[Automated Cloud Flow<br/><i>На база дадено събитие</i>]
    Create --> A2[Instant Cloud Flow<br/><i>С ръчно активизиране</i>]
    Create --> A3[Scheduled Cloud Flow<br/><i>По график</i>]
