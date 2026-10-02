# AEGILAB Architecture

## Overview

This document describes the planned architecture of AEGILAB, a Mini SOC + Red Team Lab.

The lab will provide a controlled environment where I can practise both offensive and defensive cybersecurity concepts.

## Core Workflow

**Attack → Detect → Investigate → Defend**

## Initial Architecture

```text
┌─────────────────┐
│  Kali Linux     │
│  Attacker       │
└────────┬────────┘
         │
         │ Network
         ▼
┌─────────────────┐
│ Target Machine  │
│                 │
│ Services        │
│ Logs            │
└────────┬────────┘
         │
         │ Activity / Logs
         ▼
┌─────────────────┐
│ SOC / Detection │
│                 │
│ Monitoring      │
│ Investigation   │
└─────────────────┘
