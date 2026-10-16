[← Back to Overview](../README.md)

# Organization Module: apps-inventory

> **Status:** ✅ complete  
> **Source Organization:** `demogxp`  
> **Target Organization:** `demogxp-mig4`  
> **Duration:** 0.0s (0ms)  

---

## Execution Summary

| Metric | Count |
| :--- | :--- |
| Total Items | 1 |
| Succeeded | 1 |
| Failed | 0 |
| Skipped | 0 |
| Verification Discrepancies | 0 |

### Module Warnings

- Manual reinstallation advisory: GitHub App "hackmd-hub" must be installed on demogxp-mig4 manually.

---

## Granular Organization Items

| Resource Name | Resource Type | Operation | Status | Verification | Notes / Discrepancies |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `hackmd-hub` | `github_app_installation` | `warn` | ✅ succeeded | ✅ Verified | GitHub Apps cannot be installed programmatically via API. An organization administrator must authorize and install "hackmd-hub" (ID: 37423) on demogxp-mig4. |
