# Leveraging OSINT for Dark Web Investigations and Attack Surface Management

## Overview

This session focused on using Open Source Intelligence (OSINT) techniques to investigate the dark web, identify threat actor infrastructure, perform attack surface management, and analyze digital artifacts for cyber threat intelligence (CTI).

---

# Understanding the Web Layers

The internet can be broadly divided into three layers:

## 1. Clear Web (Surface Web)

The portion of the internet indexed by search engines.

Examples:

* Google Search results
* News websites
* Public blogs
* Social media pages

---

## 2. Deep Web

Content not indexed by traditional search engines.

Examples:

* Email accounts
* Banking portals
* Corporate databases
* Academic resources
* Subscription services

---

## 3. Dark Web

A subset of the deep web that requires specialized software such as Tor to access.

Examples:

* Anonymous forums
* Hidden services
* Underground marketplaces
* Threat actor communities

---

# The Tor Network

Tor (The Onion Router) provides anonymity through layered encryption.

### Traffic Flow

```text
Tor Client
     ↓
Entry Node (Guard Node)
     ↓
Relay Node(s)
     ↓
Exit Node
     ↓
Destination
```

### Components

#### Tor Client

User's device running the Tor Browser.

#### Entry Node

First node that receives traffic from the user.

#### Relay Node

Intermediate nodes used to obscure the traffic path.

#### Exit Node

Final node that forwards traffic to the destination.

---

# Dark Web Ecosystem

The dark web contains various types of platforms:

* Forums
* Marketplaces
* Leak sites
* Messaging platforms
* Ransomware portals
* Cryptocurrency services

---

# Dark Web Forums

## What are Forums?

Discussion platforms used by threat actors for:

* Data trading
* Malware sharing
* Exploit development
* Recruitment
* Operational discussions

### Access Types

#### Open Forums

Anyone can register.

#### Closed Forums

Require:

* Invitations
* Reputation
* Membership fees
* Verification procedures

---

# Why Investigate the Dark Web?

Dark web intelligence helps organizations:

## Threat Intelligence

Identify emerging threats before attacks occur.

## Threat Actor Attribution

Connect threat actors to infrastructure, aliases, and operations.

## HUMINT Operations

Gather intelligence from human interactions and communications.

## Attack Surface Management

Discover exposed assets, credentials, and infrastructure.

## Early Warning

Detect leaked information before it is weaponized.

---

# Finding Onion URLs

Methods include:

* Intelligence reports
* CTI platforms
* Dark web search engines
* Threat intelligence feeds
* Security researchers
* Community sources

### Example Resource

DeepDarkCTI

A community-maintained repository containing links to:

* Ransomware leak sites
* Dark web forums
* Criminal marketplaces
* Threat actor infrastructure

---

# Cyber Kill Chain Perspective

The Cyber Kill Chain describes stages of a cyber attack:

1. Reconnaissance
2. Weaponization
3. Delivery
4. Exploitation
5. Installation
6. Command & Control (C2)
7. Actions on Objectives

Dark web intelligence can provide indicators across multiple stages.

---

# Hunting Threat Actor Infrastructure

Investigators often analyze infrastructure used by threat actors.

## ASN Analysis

ASN (Autonomous System Number) identifies network ownership.

Useful for:

* Infrastructure clustering
* Hosting analysis
* Threat actor tracking

## SSL/TLS Certificate Analysis

Certificates can reveal:

* Reused domains
* Infrastructure relationships
* Historical records

Tools commonly used:

* Censys
* Shodan
* crt.sh

---

# Surface Web Attribution

Threat actors often leave traces outside the dark web.

Examples:

* Social media accounts
* GitHub profiles
* Telegram channels
* Domain registrations
* Data leaks

These connections help build attribution intelligence.

---

# Anonymous Communication Platforms

Commonly investigated platforms:

* Telegram
* Signal
* Matrix
* IRC
* Jabber/XMPP

Such platforms are frequently used for:

* Coordination
* Recruitment
* Data exchange

---

# Image Forensics in Dark Web Investigations

A practical demonstration involved investigating images found on a dark web marketplace.

The objective was to determine whether metadata, visual clues, or online traces could reveal the origin of an image.

---

# Image Investigation Workflow

## Step 1: Reverse Image Search

Search for matching or similar images.

Tools:

* Google Images
* Yandex Images
* Bing Visual Search
* Baidu Image Search

---

## Step 2: Image Enhancement

Improve image clarity before analysis.

Tool:

### Remini Image Refiner

Used to:

* Increase resolution
* Enhance facial features
* Improve visual details

---

## Step 3: GEOINT Analysis

Extract location-based intelligence.

Look for:

* Road signs
* Buildings
* Vehicles
* Weather conditions
* Terrain
* Landmarks

---

## Step 4: OSINT Correlation

Correlate findings with:

* Search engines
* Social media
* Public databases
* Mapping platforms

---

# Google Dorking

Google Dorking uses advanced search operators to discover publicly exposed information.

Examples:

```text
site:example.com
filetype:pdf
intitle:index of
inurl:admin
```

Applications:

* Security assessments
* Information discovery
* Exposure identification

---

# Common Investigation Tools

## Search Engines

* Google
* Bing
* Yandex
* Baidu
* Gibiru

## Threat Intelligence

* DeepDarkCTI
* Shodan
* Censys

## Image Analysis

* Google Reverse Image Search
* Yandex Reverse Image Search
* Remini Image Refiner

## GEOINT

* Google Maps
* Google Earth
* OpenStreetMap

---

# Operational Security (OPSEC)

While conducting dark web investigations:

* Never use personal identities
* Isolate research environments
* Use virtual machines
* Avoid interacting with threat actors
* Maintain evidence integrity
* Follow legal and organizational policies

---

# Key Takeaways

* The dark web is a valuable source of cyber threat intelligence.
* OSINT enables attribution and infrastructure tracking.
* Image forensics can reveal hidden intelligence.
* Google Dorking assists in identifying exposed information.
* Proper OPSEC is critical during investigations.
* Attack Surface Management benefits greatly from OSINT-driven intelligence.
