## About

Math, Rust, and LLM governance.  My day job is writing CRUD code in Python. This is where I play. I am still learning Rust.

## Projects

phalanx — tamper-proof video evidence mobile app. This is my flagship project.

These projects are offshoots of Phalanx:
- basis — architectural governance tool for LLM-amplified codebases. Four axes (placement, values, completeness, purity), enforced as build failures.
- idiom — local naming-convention governance. Sibling tool to basis.
- feedback — real-time stability governor for AI agent sessions. Volterra-integral pressure analysis catches agent spirals before they degrade the session.
- volterra-stability — domain-agnostic library for coupled-integral stability analysis. This was extracted into its own crate from Phalanx. Phalanx deliberately does not depend on this crate. Feedback does.
- coalition — MCP shim wiring basis, idiom, and feedback together for Claude Code.
- moonshot — Compile-time-specialized Bayesian inference for embedded targets. Stable Rust, no DSL, no runtime VM. Inspired by Phalanx's compile-time stability proof.
