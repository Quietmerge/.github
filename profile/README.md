<p align="center">
  <img src="https://quietmerge.dev/logo.svg" alt="QuietMerge" width="88">
</p>

<h1 align="center">QuietMerge</h1>

<p align="center"><strong>The judgement layer for Terraform &amp; OpenTofu dependency-bump PRs.</strong></p>

<p align="center"><em>Dependabot opens them. QuietMerge closes them.</em></p>

---

Renovate and Dependabot open Terraform/OpenTofu provider &amp; module version-bump PRs
all day long. **~95% change nothing** — but a human still has to review every one.
QuietMerge does that review for you, automatically:

- ✅ **Verifies** — runs `terraform plan` in **your own CI**. Your cloud credentials never leave your account.
- 📖 **Reads the changelog** — scans the provider/module release notes for breaking changes.
- ⚖️ **Decides** — auto-merges PRs that provably change nothing, and posts a clear, plain-English verdict on anything that could break.

> **Zero credential custody.** The plan runs entirely in your CI; QuietMerge only ever reads the redacted result.

<p align="center">
  <a href="https://quietmerge.dev"><strong>quietmerge.dev</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/apps/quietmerge/installations/new"><strong>Install on GitHub</strong></a>
  &nbsp;·&nbsp;
  <a href="mailto:hello@quietmerge.dev">hello@quietmerge.dev</a>
</p>
