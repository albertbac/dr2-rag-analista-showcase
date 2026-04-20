# RAG Analyst for Document-heavy Operations

## 1. App name
RAG Analista

## 2. One-line summary
A public-safe technical case for a RAG analyst built for document-heavy operations and controlled contextual review.

## 3. Primary user
Operational analyst

## 4. Secondary user
Knowledge or admin reviewer

## 5. Problem solved
Document-heavy teams need grounded answers over uploaded files and administrative knowledge without turning the system into an uncontrolled retrieval surface.

## 6. Short workflow
Users upload or select documents, run open or guided analysis flows, and receive answers grounded in retrieved context under controlled administrative configuration.

## 7. Public-safe technical scope
Public-safe scope covers multi-tenant RAG patterns, guided questions, document workflows, and administrative configuration surfaces.

## 8. High-level integrations
High-level only: identity, vector retrieval, structured storage, and controlled model providers.

## 9. What stays private and why
Provider routing, prompt policy, retrieval tuning, vector configuration, and deployment details remain private because they are part of the production operating layer.

## 10. Confidence level
HIGH

## 11. Exposure risk
MEDIUM

## 12. Repository map
```text
dr2-rag-analista-showcase/
├── README.md
├── LICENSE
├── .gitignore
├── PUBLIC_DISCLOSURE_POLICY.md
├── SECURITY_BOUNDARY.md
├── APP_CARD_PTBR.md
├── TECHNICAL_STORY.md
├── ARCHITECTURE.md
├── WORKFLOW.md
├── PRIVACY_BOUNDARY.md
├── IMPACT_NOTES.md
├── MANUAL_TODO.md
├── site/
│   └── SITE_COPY_PTBR.md
├── screenshots/
│   └── SHOTLIST.md
├── synthetic-data/
│   ├── README.md
│   └── SYNTHETIC_DATA_TODO.md
├── reports/
│   ├── PRIVACY_AUDIT.md
│   └── PUBLISH_CHECKLIST.md
└── docs/
    ├── og-social-card.svg
    └── repo-map.svg
```

## 13. Manual public-safe evidence still needed
- Capture synthetic screenshots without any real document text
- Confirm the public-safe framing for guided versus open analysis
- Validate which admin surface can be shown safely
