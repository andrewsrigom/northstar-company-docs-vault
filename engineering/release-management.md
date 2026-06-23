# Release Management

Owner: Engineering
Last reviewed: 2026-03-30

## Purpose

This page describes the default software release process for customer-facing changes.

## Standard Release

Engineering merges reviewed changes, verifies automated checks, deploys to staging when applicable, confirms feature flag or rollout plan, and deploys during normal release windows.

## Launch Coordination

Customer-facing launches should have a Product owner, Support notes, rollback plan, monitoring owner, and Marketing launch brief when externally announced.

## High-Risk Changes

High-risk changes include authentication, billing, permissions, data migrations, customer-visible workflows, and infrastructure changes. These need explicit rollback or mitigation notes before release.

## After Release

The owner monitors dashboards, support cases, error rates, and customer feedback for at least one business day after release.
