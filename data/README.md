# data/ — Column Definitions and Sources

## salary-benchmarks.csv

Structured salary data for AI Governance Compliance Officer, AI Audit Engineer, and AI Ethics Consultant roles across the US, Germany, and India. All figures are sourced from the articles listed in the repo's Sources section (May 2026).

### Column Definitions

| Column | Type | Description |
|---|---|---|
| `geography` | string | Country or regional market (US, Germany, India GCC) |
| `market_segment` | string | Industry segment (Enterprise, Regulated Finance/Pharma, Tier-1 GCC, Domestic Enterprise) |
| `level` | string | Career level (IC/Mid, Senior, Director, Lead) |
| `role_title` | string | Job title as described in the source articles |
| `base_salary_local` | integer | Base salary in local currency. For India, this is total comp (no base/total split available from source). For US, this is base only. For Germany, this is total comp. |
| `total_comp_local` | integer | Total compensation estimate in local currency (base + estimated bonus; excludes equity for US unless noted) |
| `currency` | string | Currency code: USD, EUR, or INR |
| `regulated_sector_premium_pct` | integer | Additional percentage premium for regulated industries (banking, pharma, automotive) over the base figure in that row. 0 = the row already represents standard enterprise; positive value = the regulated multiplier applied |
| `notes` | string | Methodology notes and caveats for each row |
| `source_article` | string | The slug of the source article this figure traces to |

### Data Methodology Notes

- **US figures** are base salaries unless the notes column specifies total comp. Bonus is estimated at 15–25% of base; equity is excluded from all rows.
- **Germany figures** are total compensation as reported in the source (salary + bonus; no equity assumption).
- **India GCC figures** are total compensation in INR (salary + bonus). The source explicitly notes these are GCC-tier figures, not domestic market rates.
- **Regulated sector premium** rows are additive. If the standard enterprise senior US base is $185K and the regulated premium is 20%, the regulated equivalent is approximately $222K.
- The gap between the US junior IC band and the US director total comp exceeds $218K (source: ai-governance-salary-us-india-germany article).

### Known Limitations

- India domestic enterprise figures (₹15L–₹25L range) represent general risk/compliance roles, not AI-governance-specific titles. The ₹28L–₹65L GCC figures are more directly role-specific.
- Germany figures are total comp and include Frankfurt/Munich premium; Berlin and Hamburg rates may be lower.
- Bonus structures in this sector are often tied to regulatory milestones (passing conformity assessments, clearing ISO 42001 audits) rather than standard sales/performance metrics — standard bonus percentage estimates may understate the actual upside.

### Update Cadence

Figures reviewed quarterly. Open an Issue with the `data-correction` label if you have a more recent data point with a citable source.
