# Procurement-Entity-resolution-5-POC-Simulation
This repository contains a Proof of Concept solution fora aprocurement entity resolution and supplier data quality chalange

What’s included:

Best candidate selection per input_row_key
Match confidence scoring
Country/city consistency checks
QC flags for missing or suspicious attributes
Recommendations for dataset curation and procurement-readiness

Key observations from the dataset:

Frequent missing enrichment fields (emails, websites, founding year)
Some malformed social/media URLs
Country mismatches between input and candidate records
Duplicate/near-duplicate legal entities
Inconsistent formatting of legal suffixes and location data

Recommended next steps for a production rollout:

Add confidence thresholds + manual review workflow
Normalize legal entity naming conventions
Use domain-based deduplication alongside fuzzy matching
Create supplier golden records
Track precision/recall metrics during onboarding
Build procurement-focused outputs:
spend consolidation
supplier rationalization
risk scoring
sustainability enrichment later phase
