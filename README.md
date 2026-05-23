# California Waste Analytics — Intelligent Interactive Visual Analytics Platform

> A data visualization and analytics platform exploring California's 2021 statewide waste characterization data across six waste-generation sectors, featuring AI-powered pattern discovery, cross-sector comparisons, a carbon footprint calculator, and a scrollytelling narrative experience.
>
> ---
>
> ## Overview
>
> California generates over 40 million tons of waste annually. This platform transforms raw characterization data from the California Department of Resources Recycling and Recovery (CalRecycle) into an interactive, story-driven analytics experience — surfacing hidden patterns, sector-level behavioral differences, economic recovery opportunities, and carbon impact estimates that are invisible in raw spreadsheets.
>
> The project combines three distinct visualization modes with an AI-assisted intelligence layer to help analysts, policymakers, and sustainability teams move from raw numbers to actionable decisions.
>
> ---
>
> ## Key Metrics Surfaced
>
> - **40M+ tons** of statewide waste characterized (2021)
> - **1.3M tons** total recoverable waste identified
> - **$115M** estimated economic value of recoverable materials
> - **3.1M tons CO₂e** total carbon footprint modeled
> - **94.7%** accuracy on waste composition prediction model
> - **555+ data points** processed across 6 sectors
>          
>
> ## Features
>
> ### 1. Scrollytelling Narrative (`final.html` / `narrative_style.html`)
> A scroll-driven data story titled *"California's Hidden Waste Story"* — charts animate into view as you scroll, with sticky narrative panels contextualizing each visualization. Built with GSAP ScrollTrigger and Chart.js.
>
> ### 2. Main Analytics Dashboard (`index.html`)
> The core interactive dashboard featuring:
> - **Hierarchical treemap** of waste composition by material type (Chart.js Treemap + ECharts)
> - - **Sector comparison dashboard** — filter and compare waste profiles across Residential, Commercial, Self-Haul, Transfer Truck, and Multi-family sectors
>   - - **Donut charts** for per-sector waste composition breakdown
>     - - **Cluster graph** grouping sectors by behavioral similarity
>      
>       - ### 3. AI-Powered Intelligence Dashboard (`intelligent_analysis_v2.html`)
>       - - Hidden pattern discovery using correlation heatmaps
>         - - Cross-sector behavioral clustering
>           - - Predictive insights and optimization recommendations
>             - - Sustainability opportunity identification with economic value tagging
>              
>               - ### 4. Carbon Footprint Calculator (`carbon_footprint_calculator.html`)
>               - An interactive tool allowing users to estimate carbon impact by waste type, with animated counters and personalized reduction recommendations.
>              
>               - ### 5. Source Code Documentation (`source_code_doc.html`)
>               - Full technical documentation including architecture diagrams, data pipeline description, and annotated source code.
>              
>               - ---
>
> ## Data Sources
>
> | Dataset | Description |
> |---|---|
> | `Statewide_waste_data_fixed.csv` | Aggregate statewide waste composition |
> | `Residential_waste_data_fixed.csv` | Single-family residential waste |
> | `Commercial_waste_data_fixed.csv` | Commercial sector waste |
> | `Self_Haul_waste_data_fixed.csv` | Self-haul (drop-off) waste |
> | `Transfer_Truck_waste_data_fixed.csv` | Transfer station waste |
> | `Multi_family_waste_data_fixed.csv` | Multi-family residential waste |
>
> Source: **CalRecycle 2021 California Statewide Waste Characterization Study**
>
> ---
>
> ## Tech Stack
>
> | Layer | Tools |
> |---|---|
> | Visualizations | Chart.js, ECharts, D3.js, Treemap plugin |
> | Animation | GSAP, ScrollTrigger |
> | Styling | Tailwind CSS, Custom CSS |
> | Frontend | HTML5, JavaScript ES6+, CSS3 |
> | Data Processing | Client-side CSV parsing, pattern recognition algorithms |
>
> ---
>
> ## Project Files
>
> ```
> dv1/
> ├── index.html                        # Main analytics dashboard
> ├── final.html                        # Scrollytelling narrative (primary deliverable)
> ├── narrative_style.html              # Alternate narrative layout
> ├── intelligent_analysis_v2.html      # AI-powered intelligence dashboard
> ├── carbon_footprint_calculator.html  # Carbon impact calculator
> ├── Cindex.html                       # Comparative sector index view
> ├── source_code_doc.html              # Full technical documentation
> ├── video_script.html                 # Project presentation & executive summary
> ├── cleaned_waste_data (2).zip        # Cleaned source datasets
> └── waste_analytics_presentation.pdf  # Slide deck
> ```
>
> ---
>
> ## Key Insights Uncovered
>
> - **Organics dominate** — 30.2% of California's waste is organics (food scraps, yard waste), making composting the single largest diversion opportunity
> - **Paper still significant** — 15.5% of the waste stream is paper, much of it recyclable
> - **Sector divergence is large** — Commercial waste composition differs significantly from Residential, suggesting that one-size-fits-all diversion policies miss the biggest opportunities
> - **Carbon cost of landfilling** — The platform models that current landfill practices generate 3.1M tons CO₂e annually; aggressive diversion could cut this substantially
>      

