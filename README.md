# linkedin-projects

Assets and copy for Cian O Mahony’s LinkedIn Projects section (M6 flagships).

## runbook-copilot

| File | Use on LinkedIn |
|------|-----------------|
| `architecture.png` | How the system fits together |
| `agent-loop.png` | Think → search → answer / abstain loop |
| `approval-gate.png` | Human Approve before any simulated action |
| `guardrails.png` | Citation / abstain path |

**Live demo:** https://runbook-copilot-c3shmapppprk7ktdashvyei.streamlit.app  
**Repo:** https://github.com/itskeeeyin/runbook-copilot  
**Eval:** 144/150 real-model (from 116/150) via copilot-evals

Sources copied from `itskeeeyin/runbook-copilot` (`architecture.png`, `images/*`).

## escalation-triage-agent

| File | Use on LinkedIn |
|------|-----------------|
| `architecture.png` | How the system fits together (M5) |
| `handoff.png` | Coordinator → specialist loop |
| `approval-gate.png` | Human Approve before simulated write |
| `two-scores.png` | Practice 20/20 vs public 10/26 |
| `ESC-2001-result.png` | Optional practice screenshot |
| `ESC-2001-citations.png` | Optional citations screenshot |
| `ESC-2002-result.png` | Optional practice screenshot |

**Live demo:** https://escalation-triage-agent-hjnwi7cnblzl4aptdnkuym.streamlit.app  
**Repo:** https://github.com/itskeeeyin/escalation-triage-agent  
**Practice eval:** 20/20 offline · **Public baseline:** 10/26 top-1 (reported honestly)
