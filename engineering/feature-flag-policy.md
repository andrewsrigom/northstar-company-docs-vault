# Feature Flag Policy

Owner: Engineering and Product
Last reviewed: 2026-03-28

## Purpose

Feature flags help teams release safely, test limited behavior, and separate deployment from launch.

## Required Fields

Every long-lived feature flag should have owner, purpose, default state, rollout audience, removal date, monitoring plan, and customer communication plan when relevant.

## Production Use

Flags that change customer-visible behavior require Product approval. Flags that affect permissions, billing, data exports, or security behavior also require Engineering lead review.

## Cleanup

Temporary flags should be removed within 30 days after full rollout unless the owner documents a reason to keep them.

## Emergency Disable

Engineering may disable a flag during an incident. Product and Support should be notified when customer behavior changes.
