[← Back to Overview](../README.md)

# Organization Module: teams

> **Status:** ✅ complete  
> **Source Organization:** `demogxp`  
> **Target Organization:** `demogxp-mig4`  
> **Duration:** 25.7s (25707ms)  

---

## Execution Summary

| Metric | Count |
| :--- | :--- |
| Total Items | 24 |
| Succeeded | 24 |
| Failed | 0 |
| Skipped | 0 |
| Verification Discrepancies | 0 |

---

## Granular Organization Items

| Resource Name | Resource Type | Operation | Status | Verification | Notes / Discrepancies |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `engineering` | `team` | `create` | ✅ succeeded | ✅ Verified | Recreated team 'engineering' (parent: none) |
| `migration-demo-1361857985-team` | `team` | `create` | ✅ succeeded | ✅ Verified | Recreated team 'migration-demo-1361857985-team' (parent: none) |
| `migration-demo-1361857985-team:ghec-content-filler` | `team-repo-permission` | `update` | ✅ succeeded | ✅ Verified | Bound 'push' permission for team 'migration-demo-1361857985-team' on 'ghec-content-filler' |
| `platform-infra` | `team` | `create` | ✅ succeeded | ✅ Verified | Recreated team 'platform-infra' (parent: engineering) |
| `team-fire` | `team` | `create` | ✅ succeeded | ✅ Verified | Recreated team 'Team-Fire' (parent: none) |
| `team-fire:react` | `team-repo-permission` | `update` | ✅ succeeded | ✅ Verified | Bound 'push' permission for team 'team-fire' on 'react' |
| `team-rocket` | `team` | `create` | ✅ succeeded | ✅ Verified | Recreated team 'Team-Rocket' (parent: none) |
| `team-mystic` | `team` | `create` | ✅ succeeded | ✅ Verified | Recreated team 'Team-Mystic' (parent: team-rocket) |
| `team-repo` | `team` | `create` | ✅ succeeded | ✅ Verified | Recreated team 'Team-Repo' (parent: none) |
| `team-repo:ansible` | `team-repo-permission` | `update` | ✅ succeeded | ✅ Verified | Bound 'push' permission for team 'team-repo' on 'ansible' |
| `team-nest` | `team` | `create` | ✅ succeeded | ✅ Verified | Recreated team 'Team-Nest' (parent: team-repo) |
| `team-nest:ansible` | `team-repo-permission` | `update` | ✅ succeeded | ✅ Verified | Bound 'push' permission for team 'team-nest' on 'ansible' |
| `team-private` | `team` | `create` | ✅ succeeded | ✅ Verified | Recreated team 'Team-private' (parent: none) |
| `team-private:dummy-repo-private-lfs` | `team-repo-permission` | `update` | ✅ succeeded | ✅ Verified | Bound 'pull' permission for team 'team-private' on 'dummy-repo-private-lfs' |
| `team-public` | `team` | `create` | ✅ succeeded | ✅ Verified | Recreated team 'Team-public' (parent: none) |
| `team-public:ansible` | `team-repo-permission` | `update` | ✅ succeeded | ✅ Verified | Bound 'admin' permission for team 'team-public' on 'ansible' |
| `team-public-nestt` | `team` | `create` | ✅ succeeded | ✅ Verified | Recreated team 'Team-public-nestt' (parent: team-public) |
| `team-public-nestt:ansible` | `team-repo-permission` | `update` | ✅ succeeded | ✅ Verified | Bound 'admin' permission for team 'team-public-nestt' on 'ansible' |
| `team-public-secret` | `team` | `create` | ✅ succeeded | ✅ Verified | Recreated team 'Team-Public-Secret' (parent: none) |
| `team-public-secret:ansible` | `team-repo-permission` | `update` | ✅ succeeded | ✅ Verified | Bound 'pull' permission for team 'team-public-secret' on 'ansible' |
| `team-role` | `team` | `create` | ✅ succeeded | ✅ Verified | Recreated team 'Team-Role' (parent: none) |
| `team-role:all_repo_read` | `team-org-role` | `create` | ✅ succeeded | ✅ Verified | Assigned custom organization role 'all_repo_read' to team 'team-role' |
| `team-tactics` | `team` | `create` | ✅ succeeded | ✅ Verified | Recreated team 'Team-Tactics' (parent: none) |
| `demogxp-mig4` | `org-permission` | `update` | ✅ succeeded | ✅ Verified | Aligned default repository permission to 'none' |
