Executive Data Briefing: Nigeria Transportation Safety & Risk Profile
It revolves a fleet audit report that span across 6 years

Reporting Horizon: Q4 2020 — Q1 2026 The dataset was downloaded from https://microdata.nigerianstat.gov.ng/index.php/catalog/164/study-description#metadata-description

Technologies Used: Microsoft Power BI, Power Query (M-Code), Excel, Advanced DAX, Relational Modelling (Star Schema)

📈 Executive Summary / Project Overview

Engineered an end-to-end business intelligence dashboard tracking longitudinal transit exposure, demographic vulnerabilities, and localized highway survivability from Q4 2020 through Q1 2026. Restructured a highly disorganized, multi-layered national spreadsheet into an interactive, institutional-grade analytical engine to guide road safety asset allocation for policymakers.

🛠️ Key Technical Implementations (What Was Done)

Data Architecture & ETL: Utilized Power Query and M-code to unpivot, clean, and transpose a horizontal grid dataset spanning 6 years across 36 states and the FCT into 5 distinct, vertical fact tables. Data Modeling (Star Schema): Designed and implemented a central Calendar Dimension table using custom time-intelligence keys (YearQuarter) to enable cross-filtering and synchronized slicers across independent fact tables. Advanced Analytics & DAX Calculation: Programmed robust DAX measures utilizing RANKX, DIVIDE, and ALLSELECTED functions to calculate dynamic state mortality rankings, demographic percentage shares, and True Survival Rates that remain fully responsive to timeline slicers. Visual Engineering: Constructed a two-page executive storyboard separating Operational Fleet Risks from Deep-Dive Human Tolls, incorporating conditional KPI card alerts and geographic map visualizations to reduce cognitive overload for stakeholders.

The Report:

Global Performance Metrics
The Narrative Hook:

Between Q4 2020 and Q1 2026, Nigeria’s road network processed pulling 431,000 citizens into active impact events of Total Documented Incidents: 63,000 distinct road traffic crashes while Total Population Exposure of 431,000 individuals were directly inside or on vehicles during active accidents.

Human Harm Impact: 223,000 Total Casualties, establishing a baseline injury/fatality conversion rate of 51.74% from total exposure.

Operational Fleet Vulnerability & Infrastructure Risk (What is Crashing)
The dataset exposes a massive, critical structural imbalance between commercial transit and private commuting: Commercial operations drive national road risk which Commercial vehicle fleets dominate road risk, accounting for 68.17% (66,302 vehicles) of all vehicles involved in accidents. The Vehicle Profile Cluster: Incidents are overwhelmingly driven by a “Big Three” vehicle cluster: Commercial Cars (27K), Motorcycles (20K), and Minibuses (18K). Heavy logistics units (Trucks and Trailers) combine for a substantial 18K incidents, highlighting freight corridor vulnerability. Government and diplomatic fleets combine for less than 1.3%, showing that the crisis is entirely localized within commercial and mass transit infrastructure.

Regional Risk and Lethality Hotspots (Where it is Happening)
Road risk in Nigeria is sharply divided by geography. Urban administrative centers suffer from high crash frequencies, but open interstate expressways present a severe mortality crisis. While the top five states with the highest claim in 10,860 lives which is over 34% of the national death toll.

(FCT, Lagos & Ogun): Federal Capital Territory (FCT) logs the highest national crash volume (6.5K cases), followed by Ogun State (5.6K cases). However, FCT demonstrates lower immediate mortality relative to its volume, signalling lower operational speeds and high-density, slow-moving commuter traffic while Lagos recorded (3.1K cases). However, Lagos boasts the nation’s highest True Survival Rate at 63.65% and a low lethality index (0.27). Urban gridlock serves as a natural speed barrier, and rapid hospital proximity saves lives.

High-Lethality Highway Corridors (Kaduna & Niger): Kaduna State stands out as the deadliest transport zone in the country. Despite recording fewer total cases (4.3K) than FCT or Ogun, it registers the highest absolute death toll (3.4K deaths). Accidents along the high-speed northern expressways (Kaduna, Niger) are structurally violent and highly fatal. The Red Zone: Immediate Speed Intervention (Katsina, Sokoto, Kano, Zamfara, Kaduna, Niger, Yobe, Kebbi)

The Problem: These states have a catastrophic State Lethality Index between 0.71 and 0.99. These are long, wide, and smooth northern corridors where high-speed overtaking is common.

Macro Demographic Demands & Vulnerabilities (Who is Suffering)
The demographic matrix reveals a deep disparity in gender exposure and internal age vulnerability:

The Adult Male Exposure Bias: Adult Males bear the absolute brunt of the human toll, accounting for 73.48% of all injuries (140,864) and 77.64% of all deaths (24,546). This directly tracks back to the commercial fleet data, as Nigeria’s commercial transit, logistics hauling, and motorcycle taxi operators are almost exclusively adult men. The Pediatrics Lethality Crisis: While minors represent a tiny fraction of total exposure, Female Children exhibit the highest internal mortality rate at 17.23%, followed by Male Children at 15.50%, they face a severe risk of death when a vehicle crashes than to survive with injuries which points directly to a lack of protective pediatrics seating infrastructure and safety restraint compliance in passenger vehicles.

Strategic Recommendations for the FRSC
Pivot Enforcement from Volume to Severity: Shift routine traffic ticketing out of slow, high-frequency urban zones (like inner-city Lagos or FCT) and aggressively re-allocate highway patrol vehicles, Deploy fixed and mobile speed-detection cameras every 20 kilo meters along major corridors like the Abuja–Kaduna–Kano expressway.

Targeted Commercial Fleet Mandates: Enforce strict, auditable speed-limiter tracking and mandatory rest-stop windows targeting Commercial Vehicles and Heavy Cargo Trucks, which comprise over 68% of the risk matrix.

Heavy Penalties: Transition from warning flags to immediate vehicle impoundment for reckless overtaking on these high-lethality single-carriage highways.

FRSC Emergency Clinic Corridors: Establish fully equipped FRSC roadside emergency clinics and ambulance points at 50km intervals along the most remote sections of these northern expressways.

Night-Driving Controls: Implement stricter visibility and reflective tape enforcement on commercial trailers traveling through these dense transit regions at night.

Pediatrics Passenger Protection Policy: Launch a zero-tolerance regulatory campaign for passenger seatbelts and child safety constraints to actively compress the extreme 0.21 mortality ratio seen in minors.

KEY NOTE: The data reveals a severe operational risk imbalance on Nigerian roads. Commercial vehicles are over 2.2 times more likely to be involved in road traffic crashes than private vehicles, accounting for 68.17% of the entire fleet inventory involved in accidents.

“The first quarter of 2026 marks a significant structural improvement in Nigerian road safety, demonstrating a 15.44% reduction in national fatalities compared to the exact same period in Q1 2025. This downward trajectory indicates that targeted inter-state highway safety policies and commercial transit regulations are yielding positive results.”

“The data tells us that road safety in Nigeria cannot be treated with a blanket policy. We must deploy Traffic Calming and Volume Enforcement in urban areas, but we must urgently saturate the Red Zone Northern Corridors with Automated Speed Cameras and Emergency Trauma Clinics to combat the extreme 0.99 lethality rates where crashes are almost always fatal.”
