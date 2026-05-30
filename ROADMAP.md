# Roadmap

## Phase 1: Make the portfolio look intentional

- [x] Publish streamer agent fork.
- [x] Add local streamer-agent UI and no-token policy engine.
- [x] Add approval-gated Twitch moderation wiring.
- [ ] Add screenshots to `prismoid-agent1`.
- [ ] Add a polished README section for the streamer-agent feature.
- [ ] Audit `sentinel-ops-hq` and decide whether to improve, archive, or reposition it.
- [ ] Create portfolio site repo.
- [x] Create Local RAG Desk repo.

## Phase 2: Add two strong AI engineering repos

### Local RAG Desk

Build a local document assistant that indexes a folder, answers with citations,
and runs without paid API tokens.

Minimum feature set:

- [x] ingest `.md`, `.txt`, and best-effort `.pdf`
- [ ] local embedding option
- [x] citation-backed answers
- [x] simple local web UI
- [ ] eval set with at least 20 questions

### AI Evaluation Harness

Build a repo that shows serious AI engineering discipline.

Minimum feature set:

- YAML/JSON eval definitions
- deterministic test runner
- scoring plugins
- regression report output
- example evals for moderation and summarization

## Phase 3: Add agent workflows

### Agent Workflow Runner

Build a small agent runtime that can:

- plan tasks
- call local tools
- persist state
- produce audit logs
- resume interrupted work

### Support Inbox Agent

Build an inbox triage agent that:

- classifies messages
- extracts action items
- drafts replies
- requires human approval before send

## Phase 4: Package the story

- Portfolio site with project cards.
- Case-study writeups for top 3 repos.
- Demo videos or GIFs.
- GitHub profile README.
- Pinned repo ordering.

## Weekly operating rhythm

- Ship one visible commit every day.
- Finish one repo-quality milestone every week.
- Keep scope small enough to demo.
- Prefer useful systems over novelty demos.
