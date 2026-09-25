# 04 — Enterprise Architecture

**Document status:** Enterprise Design  
**Version:** v1.x planning  
**Date:** 2026-09-25

## Purpose

Define scale-out architecture beyond MVP:

- control plane
- remote workers
- enterprise policy distribution
- audit retention/compliance
- fleet operations

## Architecture Layers

- Experience Layer (desktop/cli/api/ci)
- Execution Plane (runtime/orchestration/sandbox)
- Control Plane (identity/policy/registry/analytics)

## Enterprise Capabilities

- SSO / identity federation
- RBAC
- central policy management
- central agent/model registry
- deployment targets (cloud/on-prem/hybrid)
- compliance and export pipelines

## Key Open Decisions

- tenancy model
- policy sync model
- offline behavior model
- remote execution trust chain
- signing and artifact attestation
