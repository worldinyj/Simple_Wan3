# Local setup

```bash
cd ~/Projects
git clone https://github.com/worldinyj/Simple_Wan3.git
cd Simple_Wan3
git fetch origin
git switch feat/lightweight-toy-video-pipeline
mkdir -p media/CASE-001
git status
```

If already cloned, do **not** clone again; run `git fetch origin && git switch feat/lightweight-toy-video-pipeline && git pull --ff-only` from that repo after reviewing local edits.

This is documentation-only. No runtime, package installation, Hermes or cloud API access needed. After review, merge PR into main, then local `git switch main && git pull --ff-only`.
