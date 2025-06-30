# Aviation Risk Analysis

## Overview

This project analyzes aviation accident data to help our company make smart decisions about entering the aviation industry. Using 25 years of accident data from the National Transportation Safety Board (NTSB), we identified which aircraft types pose the lowest risk for both commercial and private operations. The analysis delivers three concrete business recommendations to guide aircraft purchasing decisions and minimize operational risks.

## Business Understanding

### Stakeholder
**Head of Aviation Division** - The executive leading our company's expansion into aviation who needs data-driven insights to make strategic aircraft purchasing decisions.

### Key Business Questions
1. Which aircraft manufacturers have the best safety records for our planned operations?
2. What engine types and configurations should we prioritize to minimize risk?
3. Should we launch with commercial or private aviation operations first?

Our company is expanding into aviation to diversify our portfolio, but leadership lacks knowledge about aircraft risks. This analysis fills that gap by identifying trends, evaluating accident patterns, and translating findings into actionable business guidance.

## Data Understanding and Analysis

### Source of Data
- **Dataset**: National Transportation Safety Board (NTSB) aviation accident records
- **Time Period**: 1962-2023 (focused analysis on 2000-2023 for relevance)
- **Coverage**: Civil aviation accidents and incidents in the United States and international waters
- **Size**: 88,889 total records, filtered to 29,396 relevant incidents for analysis

### Description of Data
The dataset includes detailed information about each aviation accident, including:
- Aircraft manufacturer and model
- Injury severity (Fatal, Serious, Minor, None)
- Engine type and configuration
- Weather conditions and flight phase
- Aircraft damage level
- Flight purpose (private vs commercial)

**Data Preparation**: We cleaned the data by standardizing manufacturer names, filling missing values, and focusing on manufacturers with at least 100 incidents to ensure statistical reliability. We also categorized flights into Private and Commercial operations for targeted analysis.

### Three Key Visualizations

#### 1. Aviation Incidents Trending Downward (2000-2023)
A line chart showing annual accident counts from 2000 to 2023. The trend reveals improving aviation safety over time, with incidents dropping from ~1,680 in 2000 to ~1,130 in 2023. This 33% reduction demonstrates that aviation is getting significantly safer, which is good news for our business entry.

#### 2. Fatal Injuries by Engine Type
Bar charts comparing total fatal injuries across different engine types for both private and commercial flights. Reciprocating engines dominate fatality statistics with 16,000+ deaths in private flights alone, while turbine engines (turboprop, turbofan, turbojet) show dramatically lower death rates. This visualization clearly shows which engine types to avoid.

#### 3. Mean Fatal Injuries by Weather and Flight Phase (Heatmap)
A heatmap showing average fatalities based on weather conditions and flight phases. Unknown weather conditions show the highest fatality rates, particularly during climb (3.0) and cruise (4.3) phases. The visualization emphasizes the importance of flight planning and avoiding uncertain weather conditions.

## Conclusion

### Summary of Conclusions

Based on our analysis of 29,396 aviation accidents from 2000-2023, here are our three key findings:

#### 1. Engine Type is the Biggest Risk Factor
**Finding**: Reciprocating engines account for the overwhelming majority of aviation fatalities - over 16,000 deaths in private flights alone, while turbine engines show minimal fatality rates.

**Business Impact**: Never purchase aircraft with reciprocating engines. Specify turboprop as the minimum acceptable engine type, with turbofan/turbojet preferred. This single decision eliminates our biggest risk factor.

#### 2. Start with Commercial Operations
**Finding**: Commercial aviation shows dramatically lower accident rates and less severe damage patterns compared to private aviation across all metrics in our analysis.

**Business Impact**: Launch our aviation division with commercial operations first to minimize initial risk while building expertise. The data clearly shows commercial is the safer market to enter, with lower liability exposure.

#### 3. Manufacturer Selection Matters Significantly
**Finding**: Among manufacturers with sufficient data (100+ incidents), clear safety leaders emerge: TaylorCraft, Vans, and Aero Commander for private operations; Airbus, North American, and Boeing for commercial operations.

**Business Impact**: Focus our fleet purchases exclusively on these proven manufacturers. Avoid higher-incident brands like Cessna or Piper for our initial private fleet. For commercial operations, stick with the big three established players.

### Bottom Line
The aviation industry has become significantly safer over the past 25 years, making this a good time for our company to enter the market. By following our data-driven recommendations - avoiding reciprocating engines, starting with commercial operations, and choosing proven manufacturers - we can minimize risks while building a successful aviation division.
