# Dependency Upgrade Guidelines

Owner: Engineering
Last reviewed: 2026-01-31

## Purpose

This guide explains how engineers should evaluate dependency upgrades.

## Routine Upgrades

Routine minor and patch upgrades should include automated tests, release notes review, and rollback plan when the dependency affects production behavior.

## High-Risk Upgrades

High-risk upgrades include frameworks, authentication libraries, database clients, billing integrations, security tooling, and build systems. These require an upgrade note with risks, test plan, and owner.

## Security Updates

Security updates should be prioritized based on exploitability, exposure, affected systems, and available mitigations. IT Security may request expedited review.

## Documentation

Update setup docs, runbooks, and troubleshooting notes when an upgrade changes developer workflow or operational behavior.
