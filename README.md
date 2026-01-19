# Indigenomics-Investment-Navigator

EY x Databricks Hackathon Project
This project was built to identify and bridge funding gaps in the Indigenous economy. We moved beyond standard financial spreadsheets to look at the human side of economic data, aligning our insights with the path toward a $100 billion Indigenous economy.

**The Concept**
Investment often misses the mark because it doesn't account for what communities are actually asking for. We built a "Navigator" that cross-references ongoing Indigenous projects with real-world qualitative data to find out where capital is most needed but currently lacking.

**Transcript Analysis**
What made our approach unique was the data source. We didn't just look at market reports; we processed transcripts from hundreds of recent Indigenous events and summits.

**The Goal:** Uncover recurring "gaps" mentioned by leaders—infrastructure needs, local business barriers, and community service voids.

**The Action:** By mapping these verbalized gaps against a database of current projects, we could see exactly which initiatives were underfunded relative to the actual community demand.

**Technical Workflow (Databricks)**
Even though the portal is now closed, our architecture focused on turning "messy" text into investment signals:

Natural Language Processing: Used PySpark to ingest and process text data from 100s of event transcripts.

Data Integration: Combined qualitative transcript insights with current Indigenomics project data using a Unified Lakehouse (Delta Lake).

Gap Analysis: Created a scoring system to highlight projects that align with the most frequently mentioned economic "gaps."

**Impact & Vision**
Community-Led Growth: The navigator ensures that investment is driven by the community’s own words, not just external financial trends.

**Strategic Funding:** We provided a way for organizations like EY to see exactly where a dollar of investment would have the highest social and economic ROI.

**A quick note:** This repo includes our presentation of final pitch slides. These walk through the full logic of the project, including the transcript analysis and the resulting investment roadmap. My access to the Databricks environment expired after the hackathon ended, so the live notebooks aren't here. This repo serves as a record of our strategy and the data architecture we presented to the judges.
