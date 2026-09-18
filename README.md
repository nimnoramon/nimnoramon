# Part 2 — GitHub profile README

Save as `README.md` in a repo named exactly after your username
(`github.com/<username>/<username>`). It renders on your profile page.

Replace the bracketed bits and delete this line.

---

```markdown
## Noramon Tharat

Full-stack developer, 8 years, Bangkok / Nakhon Nayok.
I build order-management and e-commerce systems — the unglamorous middle layer
where product, stock and order data has to agree across five marketplaces and
none of them agree on anything.

Vue 3 · TypeScript · C# .NET · PostgreSQL · REST integrations
Currently at SCGP (via GetLinks), where I also built an MCP server so our AI
tooling can reach our internal systems.

**Projects**
- [OrderHub](link) — a miniature omnichannel order hub: append-only stock ledger,
  order state machine, two mock marketplace connectors with realistic failure
  modes. Next.js · NestJS · Postgres · Redis. [Live demo](link)
- [Case studies](link) — shipping a Meta Business Extension integration in nine
  days, and building a public service module on a government platform

**How I work with AI**
Claude Code is part of my daily loop — I spec, it drafts, I review and test.
The OrderHub README says exactly which parts were which.

noramon.tharat@hotmail.com
```

---

## Checklist before you point recruiters at your profile

- [ ] Every pinned repo has a description and topics
- [ ] Every pinned repo has a README with at least a screenshot and a run command
- [ ] Archive or make private anything half-finished and unexplained
- [ ] Pin 3 repos: OrderHub, case studies, one small useful thing
- [ ] Profile: photo, location, the one-line bio, email visible
- [ ] OrderHub commit history is many small commits, not one "initial commit" dump

## What to pin as the third repo

Anything small and genuinely useful beats a tutorial clone. Ideas from what you
already know:

- **mcp-server-starter** — a minimal MCP server template with two example tools
  and a README explaining the protocol. You have built one at work; a clean
  public version is rare and immediately interesting to an AI-native team.
- **marketplace-order-mapper** — a tiny library that normalises order payloads
  from differently-shaped marketplace APIs into one type. Ten files, real tests,
  clearly the work of someone who has done this for a living.
