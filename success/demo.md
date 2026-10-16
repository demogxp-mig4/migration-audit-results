[← Back to Overview](../README.md)

# Migration Result: demo

> **Status:** ✅ Succeeded  
> **Source Repository:** `demo`  
> **Target Repository:** `demo`  
> **Duration:** 510.4s (510402ms)  
> **Verified:** Yes (0 Discrepancies)  

---

## Migrated Items Summary

| Module / Category | Status | Total | Succeeded | Failed | Skipped | Discrepancies | Duration | Granular Items |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `gei-repo` | ✅ complete | 1 | 1 | 0 | 0 | 0 | 468.0s | [View Items](../repositories/demo/gei-repo.md) |
| `repo-variables` | ✅ complete | 1 | 1 | 0 | 0 | 0 | 0.2s | [View Items](../repositories/demo/repo-variables.md) |
| `repo-secrets` | ✅ complete | 4 | 4 | 0 | 0 | 0 | 1.4s | [View Items](../repositories/demo/repo-secrets.md) |
| `environments` | ✅ complete | 3 | 3 | 0 | 0 | 0 | 0.7s | [View Items](../repositories/demo/environments.md) |
| `webhooks` | ⏭️ skipped | 0 | 0 | 0 | 0 | 0 | 0.0s | [View Items](../repositories/demo/webhooks.md) |
| `repo-settings` | ✅ complete | 1 | 1 | 0 | 0 | 0 | 0.6s | [View Items](../repositories/demo/repo-settings.md) |
| `repo-custom-properties` | ✅ complete | 1 | 1 | 0 | 0 | 0 | 0.0s | [View Items](../repositories/demo/repo-custom-properties.md) |
| `rulesets` | ⏭️ skipped | 0 | 0 | 0 | 0 | 0 | 0.0s | [View Items](../repositories/demo/rulesets.md) |
| `branch-protection` | ✅ complete | 1 | 1 | 0 | 0 | 0 | 0.0s | [View Items](../repositories/demo/branch-protection.md) |
| `post-migration-codeowners` | ✅ complete | 1 | 1 | 0 | 0 | 0 | 0.0s | [View Items](../repositories/demo/post-migration-codeowners.md) |
| `security` | ✅ complete | 1 | 1 | 0 | 0 | 0 | 0.0s | [View Items](../repositories/demo/security.md) |
| `deploy-keys` | ⏭️ skipped | 0 | 0 | 0 | 0 | 0 | 0.0s | [View Items](../repositories/demo/deploy-keys.md) |
| `collaborators` | ⏭️ skipped | 0 | 0 | 0 | 0 | 0 | 0.0s | [View Items](../repositories/demo/collaborators.md) |
| `lfs` | ✅ complete | 2 | 2 | 0 | 0 | 0 | 39.5s | [View Items](../repositories/demo/lfs.md) |
| `autolinks` | ⏭️ skipped | 0 | 0 | 0 | 0 | 0 | 0.0s | [View Items](../repositories/demo/autolinks.md) |
| `discussions` | ⏭️ skipped | 0 | 0 | 0 | 0 | 0 | 0.0s | [View Items](../repositories/demo/discussions.md) |

---

## Stage Execution Breakdown

| Stage | Status | Notes |
| :--- | :--- | :--- |
| `gei-repo` | ✅ Completed | Executed cleanly (1 item) |
| `repo-variables` | ✅ Completed | Executed cleanly (1 item) |
| `repo-secrets` | ✅ Completed | Executed cleanly (4 items) |
| `environments` | ✅ Completed | Executed cleanly (3 items) |
| `webhooks` | ⏭️ Skipped | No applicable resources in source repository |
| `repo-settings` | ✅ Completed | Executed cleanly (1 item) |
| `repo-custom-properties` | ✅ Completed | Executed cleanly (1 item) |
| `rulesets` | ⏭️ Skipped | No applicable resources in source repository |
| `branch-protection` | ✅ Completed | Executed cleanly (1 item) |
| `post-migration-codeowners` | ✅ Completed | Executed cleanly (1 item) |
| `security` | ✅ Completed | Executed cleanly (1 item) |
| `deploy-keys` | ⏭️ Skipped | No applicable resources in source repository |
| `collaborators` | ⏭️ Skipped | No applicable resources in source repository |
| `lfs` | ✅ Completed | Executed cleanly (2 items) |
| `autolinks` | ⏭️ Skipped | No applicable resources in source repository |
| `discussions` | ⏭️ Skipped | No applicable resources in source repository |

---

## Verification Checklist

- [x] **Zero Discrepancies:** All verified resources match expected configuration between source and target.
- [x] **Target Parity Confirmed:** Branches, settings, and metadata conform to the target organization schema.
- [x] **Diagnostic Check:** No migration error conditions detected.

---

## GEI Log Summary & Notes

Repository transferred cleanly via GEI without errors or metadata drops.
