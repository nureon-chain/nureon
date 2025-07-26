# NIP-Core-001: Halving System

**Title:** Halving System for Nureon  
**Author:** Nureon Dev Team  
**Type:** Core  
**Status:** Draft  
**Created:** 2025-07-26

## Summary

This document defines the halving system for the Nureon blockchain.

## Motivation

To control inflation and mimic the scarcity model of Bitcoin, a halving mechanism is implemented.

## Specification

- Initial block reward: 100 ELC
- Halving interval: every 210,000 blocks
- New reward = Previous reward / 2

## Rationale

Halving reduces the issuance rate, increasing scarcity over time and helping price discovery.

## Implementation

Hardcoded in the core protocol. No governance action required.
