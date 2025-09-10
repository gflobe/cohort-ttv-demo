# Cohort Retention & Time-to-Value (Template)
Use these CSVs to build a LinkedIn-ready cohort heatmap + funnel in Tableau or Power BI.

## Data
- data/users.csv — per-user; includes signup_date, segment, activation_delay_days, ttv_days, retained_30d, retained_90d
- data/cohort_retention.csv — cohort_month × months_since with retention_rate (0–1)
- data/cohort_retention_by_segment.csv — split by segment
- data/funnel_summary.csv — activation rate (%), median TTV (days), 30/90-day retention (%)

## Assets
- assets/cohort_heatmap.png — example image
- assets/funnel_segmentB.png — example image

## Suggested visuals
**Heatmap:** rows = cohort_month; cols = months_since; color = retention_rate.  
**Funnel:** bar cards for Activation Rate, 30d, 90d. Show TTV median (days) as a separate card.

Segment B improves after 2024-07 (activation delay ~12d -> ~7d); retention lifts ~6–8 pts.
