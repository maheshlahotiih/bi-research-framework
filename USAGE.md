# Usage Guide

## Quick Start

### Basic Research Request

To initiate research on a company:

1. Provide the target entity name and domain
2. Specify your research objective
3. Indicate desired depth (Quick/Standard/Comprehensive)
4. Highlight priority areas

### Example Request

```md
Research Request:

- Target: Acme Corporation (acmecorp.com)
- Objective: Vendor Assessment
- Depth: Standard
- Time Window: Last 12 months
- Priority: Financial stability and reputation
```

## Intake Questions

The framework asks only what’s needed:

- **Target entity:** Official name, domain, key subsidiaries
- **Research goal:** Vendor Assessment / M&A Research / Competitor Analysis / Market Intelligence
- **Time window:** e.g., last 12 months
- **Geographic focus:** if relevant
- **Depth:** Quick / Standard / Comprehensive
- **Priority areas:** Financial / Reputational / Legal / Market Position

## Research Depth Levels

### Quick (5-8 mins)

- Basic company profile
- Recent news highlights
- Critical risk indicators
- Top 3 findings

### Standard (10-15 mins)

- Comprehensive company profile
- Financial health assessment
- Reputation analysis
- Legal/regulatory review
- Top 10 findings with recommendations

### Comprehensive (25-30 mins)

- Deep-dive across all focus areas
- Extensive source verification
- Competitive positioning analysis
- Supply chain mapping
- Detailed risk assessment
- Full gap analysis

## Output Examples

### Executive Summary Example

```md
## EXECUTIVE SUMMARY

**Overall Assessment**: MODERATE RISK
Last Updated: 2024-01-15

**Key Findings**:

1. Recent leadership turnover (3 C-suite exits in 6 months) - HIGH CONCERN
   - Sources: SEC 8-K filings, WSJ article (2024-01-10)
   - Confidence: HIGH (Tier 1 + Tier 2)

2. Strong financial performance (revenue +23% YoY)
   - Source: Q3 2023 10-Q filing
   - Confidence: HIGH (Tier 1)

3. Ongoing patent litigation with competitor
   - Sources: Court filings (PACER), Law360 article
   - Confidence: HIGH (Tier 1 + Tier 2)

**Critical Attention Areas**:
- Leadership stability and succession planning
- Patent litigation outcome and financial impact

**Primary Recommendations**:
- CRITICAL: Request reference calls with recent customers (1 week)
- HIGH: Monitor leadership announcements (ongoing)
- MEDIUM: Assess IP risk exposure with legal counsel (2 weeks)
```

### Detailed Finding Example

```md
## FINDING: Leadership Turnover

**Summary**: Three C-suite executives departed between July-December 2023

**Evidence**:

1. CFO resignation announced July 15, 2023
   - Source: SEC Form 8-K (filed 2023-07-15) [Tier 1]
   - Reason cited: "Personal reasons"

2. Chief Product Officer exit reported August 2023
   - Source: Wall Street Journal (2023-08-22) [Tier 2]
   - Source: Company press release (2023-08-21) [Tier 1]

3. CTO departure disclosed December 2023
   - Source: SEC Form 8-K (filed 2023-12-10) [Tier 1]
   - LinkedIn profile updated (2023-12-11) [Tier 3]

**Confidence Level**: HIGH  
Based on 3× Tier 1 sources, 1× Tier 2 source

**Contradictions**: None identified

**Implications**:
- May indicate strategic disagreements or cultural issues
- Could impact product roadmap execution
- Increases organizational risk during transition

**Recommended Actions**:
- CRITICAL: Conduct reference checks with recent customers
- HIGH: Request org chart and succession plans
- MEDIUM: Schedule meeting with new leadership team
```

### Contradiction Handling Example

```md
## CONTRADICTION FLAGGED

**Claim**: Company employee count

**Source A** (LinkedIn company page, viewed 2024-01-15):
- "1,000-5,000 employees"
- Tier 3, Low specificity

**Source B** (Company press release, 2024-01-10):
- "Over 7,500 employees globally"
- Tier 1, Specific claim

**Source C** (Bloomberg profile, 2024-01-12):
- "Approximately 8,200 employees"
- Tier 2, Specific claim

**Assessment**:
- LinkedIn data likely outdated or includes only certain locations
- Press release and Bloomberg align (~10% variance acceptable)
- **Accepted figure**: ~7,500-8,200 employees
- **Confidence**: MEDIUM-HIGH (Tier 1 + Tier 2 alignment)
```

### Gap Analysis Example

```md
## INFORMATION GAPS

**Attempted but Not Found**:

1. **Private ownership structure** [Priority: HIGH]
   - Searched: SEC filings, state business registries
   - Status: No public disclosure found
   - Implication: May be privately held or foreign-owned
   - Recommendation: Request cap table during vendor discussions

2. **Customer concentration metrics** [Priority: MEDIUM]
   - Searched: 10-K filings, analyst reports
   - Status: Not disclosed (private company)
   - Implication: Unknown revenue dependency risk
   - Recommendation: Ask for top 10 customer % during due diligence

3. **Cybersecurity incident history** [Priority: MEDIUM]
   - Searched: State breach notifications, news coverage
   - Status: No incidents found in public records
   - Note: Absence doesn't confirm no breaches occurred
   - Recommendation: Request SOC 2 Type II report
```

## Recommendation Priority Framework

### CRITICAL (Act within 24-48 hours)

- Material risk to business relationship
- Legal/regulatory concerns
- Immediate financial stability questions

### HIGH (Act within 1 week)

- Significant due diligence gaps
- Reputation concerns requiring clarification
- Market position verification needed

### MEDIUM (Act within 1 month)

- Standard due diligence completion
- Competitive intelligence updates
- Supply chain validation

### MONITORING (Ongoing)

- News alerts and updates
- Regulatory filing reviews
- Market position tracking

## Best Practices

1. **Always Verify Entity Identity**
   - Use multiple identifiers (domain, EIN, DUNS number)
   - Check for name variations and DBAs
   - Confirm parent/subsidiary relationships

2. **Prioritize Source Quality Over Quantity**
   - One Tier 1 source beats five Tier 4 sources
   - Recent sources (< 6 months) preferred
   - Original sources better than aggregators

3. **Document Your Methodology**
   - Track all searches performed
   - Note dead ends and why
   - Record date and time of research

4. **Separate Facts from Inferences**
   - Clearly label: “Confirmed” vs “Inferred” vs “Speculative”
   - Explain reasoning for inferences
   - Acknowledge when speculation is necessary

5. **Maintain Temporal Awareness**
   - Always include dates on findings
   - Flag outdated information (>12 months for dynamic data)
   - Track how situations evolve over time

## Common Pitfalls to Avoid

- Relying on single sources for critical claims → Use multi-source verification for important findings
- Ignoring publication dates → Always assess information freshness
- Treating all sources equally → Apply source tier weighting consistently
- Speculation without labeling → Clearly mark inferences and assumptions
- Incomplete gap documentation → Document what you looked for but didn’t find

## Tools and Resources

### Recommended Search Strategies

- Start with official sources (SEC, company website)
- Cross-reference with news aggregators
- Use specialized databases for industry data
- Check court records for legal matters

### Source Verification Checklist

- Source tier identified
- Publication date recorded
- Author/publisher credibility assessed
- Cross-referenced with other sources
- Original source confirmed (not aggregated)

## Questions?

For additional guidance or to report issues, please open an issue on GitHub.
