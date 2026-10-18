# Viktor Lind

Backend engineer based in Hamburg, Germany.  
Focusing on Python CLI runtimes, packaging architecture, and deterministic dependency resolution.

---

### 🏛️ Upstream Contributions & Verified Fixes (Wall of Proof)

A public ledger of upstream open-source bug fixes and invariant patches:

| Project | Domain | PR / Tracking | Status | Invariant Verified |
|---|---|---|---|---|
| **[python-poetry/poetry](https://github.com/python-poetry/poetry)** | Packaging & CLI | [PR #11151](https://github.com/python-poetry/poetry/pull/11151) | `In Review` | Config setting name attribution & integer validation |
| **[pallets/click](https://github.com/pallets/click)** | CLI Parser | Local Suite | `Validated` | Option flag parsing & parameter hydration |
| **[psf/requests](https://github.com/psf/requests)** | HTTP Client | Local Suite | `Validated` | Connection pool lifecycle & header normalization |

---

### 🛠️ Toolchain & Engineering Blueprint

I follow a strict **green-first, zero-regression** contribution workflow:
- **Local Validation**: Full test suite execution + `ruff check` + `ruff format` prior to first push.
- **Diff Minimization**: Surgical 10–30 line edits to eliminate maintainer review fatigue.
- **Pre-Flight Invariant Airlock**: Validated with [ZeroSlop™ CI](https://github.com/marketplace/actions/zeroslop-by-ribbsaeter-systems) — automated AST invariant checking and diff minimization on GitHub Marketplace.

---
*Open to collaborating on CLI tooling, packaging standards, and performance optimization.*
