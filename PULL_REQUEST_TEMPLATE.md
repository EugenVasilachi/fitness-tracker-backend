<!-- 🚀 PULL REQUEST TEMPLATE -->

## 📋 Description
Provide a clear, concise summary of the changes introduced by this PR. Include motivation, context, and any relevant architectural decisions.

> **Note:** If this PR resolves an open issue, please link it here using `Fixes #` syntax.

---

## 🛠️ Type of Change
Please check the options that are relevant to this change (replace `[ ]` with `[x]`):

- [ ] 🐛 Bug fix (non-breaking change which fixes an issue)
- [ ] ✨ New feature (non-breaking change which adds functionality)
- [ ] 💥 Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] 📝 Documentation update
- [ ] 🎨 Code style / Refactoring (no functional changes)
- [ ] ⚡ Performance optimization / Dependency upgrade

---

## 📐 Proposed Architecture & Implementation
Detail how you solved the problem. Highlight any new design patterns, database migrations, or key configuration updates.

| Scope | Component Impacted | Change Type |
| :--- | :--- | :--- |
| **Backend** | API Gateway / Controllers | Endpoints modified |
| **Frontend** | Shared UI Elements | Props structure updated |
| **Infrastructure** | Docker / CI Pipelines | Environment variables added |

---

## 🧪 How Has This Been Tested?
Please describe the tests that you ran to verify your changes. Provide instructions so we can reproduce.

### 1. Automated Testing Summary
* **Unit Tests:** `npm run test:unit` passed with 100% coverage on modified modules.
* **Integration Tests:** Verified database transaction rollbacks under simulated network timeouts.

### 2. Manual Verification Steps
<details>
<summary><b>🔄 Click to expand step-by-step UI verification workflow</b></summary>

1. Spin up the local environment using `docker-compose up --build`.
2. Navigate to the `/dashboard` route.
3. Attempt to submit the form with empty fields to verify the newly added validation logic.
4. Confirm that the error state matches the Figma design specifications.
</details>

---

## 📌 Checklist
Go over all the following points, and check them off if they are true:

- [ ] My code follows the code style and formatting guidelines of this project.
- [ ] I have performed a self-review of my own code.
- [ ] I have commented on my code, particularly in hard-to-understand areas.
- [ ] I have made corresponding changes to the documentation.
- [ ] My changes generate no new warnings or console errors.
- [ ] New and existing unit tests pass locally with my changes.
- [ ] Any dependent changes have been merged and published in downstream modules.

---

## 📷 Visuals & Screenshots (If Applicable)
If your changes affect the user interface or add a visual component, paste screenshots, GIFs, or layout diagrams here to help reviewers visualize the impact.
