# Sample Markdown with Mermaid

This is a sample file to test the **Markdown & Mermaid Viewer**.

## 1. Basic Markdown
- **Bold text** and *italic text*
- [Links](https://example.com)
- `Inline code`

## 2. Mermaid Flowchart
```mermaid
graph TD
    A[Start] --> B{Is it working?}
    B -- Yes --> C[Great!]
    B -- No --> D[Fix it]
    D --> B
```

## 3. Mermaid Sequence Diagram
```mermaid
sequenceDiagram
    participant U as User
    participant S as Server
    participant DB as Database

    U->>S: Request Data
    S->>DB: Query
    DB-->>S: Data
    S-->>U: Response
```

## 4. Mermaid State Diagram
```mermaid
stateDiagram-v2
    [*] --> Idle
    Idle --> Processing : Start
    Processing --> Idle : Complete
    Processing --> Error : Failure
    Error --> Idle : Reset
```

## 5. Mermaid Gantt Chart
```mermaid
gantt
    title Project Timeline
    dateFormat  YYYY-MM-DD
    section Design
    Requirements    :done, 2026-10-01, 2026-10-05
    UI Design       :active, 2026-10-06, 5d
    section Development
    Coding          : 2026-10-11, 10d
    Testing         : 2026-10-21, 5d
```
