# BA-Kit Open — Trọn bộ 55 AI Skills cho IT Business Analyst & Product Owner

Bộ kỹ năng mở rộng biến mọi AI Coding Agent (Claude Code, Antigravity, Codex, Hermes...) thành trợ lý Business Analyst chuyên nghiệp, tự động hóa toàn bộ quy trình tài liệu từ ý tưởng thô đến bàn giao kỹ thuật.

---

## 📁 Cấu trúc Thư mục Dự án

```
ba-kit-open/
├── skills/          # 55 AI Skills chuẩn Agent Skill (.claude/skills hoặc .hermes/skills)
│   ├── brainstorm/  # Làm rõ nghiệp vụ thô
│   ├── srs/         # Đặc tả kỹ thuật IEEE 830
│   ├── sequence/    # Sơ đồ tuần tự Mermaid
│   ├── erd/         # Sơ đồ quan hệ thực thể
│   ├── wireframe-html/ # Wireframe HTML tương tác
│   ├── userstory/   # Backlog User Story chuẩn INVEST
│   ├── test-cases/  # Test case chi tiết
│   ├── cr/          # Xử lý Change Request & Impact Analysis
│   └── ... (đủ 55 skills)
├── rules/           # 19 Quy ước viết tài liệu & mã hóa chuẩn BA
│   ├── 01-fr-naming-convention.md
│   ├── 02-br-naming-convention.md
│   ├── 03-err-naming-convention.md
│   ├── 04-nfr-standards.md
│   ├── 05-srs-ieee-830.md
│   ├── 06-cockburn-use-case.md
│   ├── 07-invest-user-story.md
│   ├── 08-gherkin-acceptance-criteria.md
│   ├── 09-data-dictionary-standard.md
│   ├── 10-api-contract-standards.md
│   ├── 11-error-matrix-convention.md
│   ├── 12-state-transition-rules.md
│   ├── 13-wireframe-html-guidelines.md
│   ├── 14-test-case-traceability.md
│   ├── 15-change-request-impact-matrix.md
│   ├── 16-ambiguity-detection-rules.md
│   ├── 17-actor-role-definition.md
│   ├── 18-knowledge-graph-metadata.md
│   └── 19-document-versioning-rules.md
└── _templates/      # 48 Biểu mẫu tài liệu chuẩn
    ├── 01-prd.md
    ├── 02-roadmap.md
    ├── 04-brainstorm.md
    ├── 08-srs.md
    ├── 15-sequence-diagram.md
    ├── 19-state-diagram.md
    ├── 20-erd-mermaid.md
    ├── 26-usecase-cockburn.md
    ├── 27-userstory.md
    ├── 28-acceptance-criteria.md
    ├── 31-wireframe-html.html
    ├── 43-test-cases.md
    ├── 45-gap-analysis.md
    ├── 47-change-request.md
    └── ... (đủ 48 templates)
```

---

## ⚡ 9 Giai đoạn & Toàn bộ 55 Lệnh Skills

| Giai đoạn | Số lượng | Danh sách Lệnh `/skill` |
| :--- | :---: | :--- |
| **1. Lập kế hoạch sản phẩm** | 3 | `/prd`, `/roadmap`, `/discover` |
| **2. Thu thập & Đặc tả yêu cầu** | 7 | `/brainstorm`, `/urd`, `/brd`, `/prd-epic`, `/srs`, `/reverse-doc`, `/code-to-srs` |
| **3. Sơ đồ nghiệp vụ & Dữ liệu** | 11 | `/sequence`, `/activity`, `/activity-swimlane`, `/bpmn`, `/state`, `/erd`, `/d2-erd`, `/d2-activity`, `/d2-architect`, `/dbdiagram`, `/usecase-diagram` |
| **4. Use case & User story** | 3 | `/usecase`, `/userstory`, `/ac` |
| **5. Thiết kế màn hình & Prototype** | 6 | `/user-flow`, `/wireframe-ascii`, `/wireframe-html`, `/prototype-html`, `/prototype-next`, `/figma` |
| **6. Tích hợp API** | 7 | `/api-assess`, `/api-doc`, `/api-design`, `/api-map`, `/api-checklist`, `/api-test`, `/api-readiness` |
| **7. Kiểm thử (QA/QC)** | 3 | `/test-checklist`, `/test-cases`, `/playwright-gen` |
| **8. Kiểm soát chất lượng & Thay đổi** | 6 | `/gap`, `/doc-drift`, `/ask`, `/cr`, `/dashboard`, `/kg` |
| **9. Bàn giao & Vận hành** | 9 | `/jira`, `/confluence`, `/export`, `/preview`, `/reverse-preview`, `/userguide`, `/meet`, `/update-overview`, `/delegate` |

---

## 🚀 Luồng Xương sống Cốt lõi (Core Workflow)

Một ngày làm việc mẫu của BA với Core Skills:
1. `09:00` `/brainstorm`: Phỏng vấn làm rõ ý tưởng thô và chốt scope.
2. `09:40` `/srs`: Sinh đặc tả kỹ thuật IEEE 830 (FR, BR, ERR, NFR).
3. `10:30` `/sequence` + `/erd`: Vẽ sơ đồ luồng tương tác và mô hình dữ liệu.
4. `11:00` `/wireframe-html`: Dựng giao diện nguyên khối xem trực tiếp trên trình duyệt.
5. `14:00` `/userstory` + `/ac`: Bóc tách backlog chuẩn INVEST và Acceptance Criteria Gherkin.
6. `16:00` `/test-cases`: Sinh test cases kiểm thử bám sát AC và Error Matrix.
7. `Hôm sau` `/cr`: Tiếp nhận thay đổi của khách hàng, phân tích tác động và đồng bộ tài liệu.
