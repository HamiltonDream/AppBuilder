# AppBuilder — Remote Project

Work on this from anywhere (phone, tablet, laptop) and see live progress.

## 1. Work from phone (2 options)

**Option A — Browser, nothing to install (easiest):**
1. Open https://github.com/HamiltonDream/AppBuilder in your phone browser
2. Press `.` (period) → instant `github.dev` editor
3. Or open https://vscode.dev/github/HamiltonDream/AppBuilder
4. Edits auto-commit if you use Codespaces below

**Option B — Full dev environment (recommended):**
1. On phone go to repo → `Code` → `Codespaces` → `Create codespace`
2. Full VS Code + terminal in browser
3. App preview appears in Ports tab

**Option C — GitHub Mobile app:**
- Install GitHub Mobile (iOS/Android) → repo → track commits, issues, Actions progress

## 2. See actual progress live

- **Live site (auto-deploys on every push to main):** https://HamiltonDream.github.io/AppBuilder/
- **Actions runs:** repo → Actions tab (phone-friendly)
- **Progress log:** [`PROGRESS.md`](./PROGRESS.md) — updated every session
- **Project board:** repo → Projects → create board for tasks

## 3. Work from this PC

```powershell
cd c:\Users\Hamil\AppBuilder
code .
```

Push changes:
```powershell
git add -A; git commit -m "update"; git push
```

## 4. Optional: access THIS PC from phone (live running app)

Keeps this machine as the server, phone as viewer:

```powershell
code tunnel --accept-server-license-terms
```

Then on phone open https://vscode.dev → use tunnel URL shown. Requires this PC stays on.

---
Remote set up 2026-10-06. Repo: HamiltonDream/AppBuilder
