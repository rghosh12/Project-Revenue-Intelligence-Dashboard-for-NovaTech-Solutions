# Revenue Intelligence Dashboard for NovaTech Solutions

## Submission Requirements & Screenshot Evidence

The criteria and submission requirements below are transcribed from the supplied rubric. Add your evidence in the screenshot space beneath each requirement.

To attach screenshots, edit this README on GitHub and paste or drag your images into the matching space. Replace the *Attach screenshots here* placeholder with the uploaded image Markdown. Add multiple screenshots in the same space when needed.

---

## Data Quality & Preparation

### Criterion 1: Verify data quality and completeness across indexed knowledge bases

**Submission requirements**

1. Verification log contains at least 6 entries covering all three data knowledge bases (CRM deals, marketing campaigns, support tickets)

   **Screenshot evidence:**

   > *Attach screenshots here.*

   <!-- Screenshot space: criterion 1, requirement 1. Paste uploaded image Markdown below this comment. -->

   <br><br>

2. Each log entry includes a natural language question, Q's response, the expected answer from the data dictionary, and a pass/fail assessment

   **Screenshot evidence:**

   > *Attach screenshots here.*

   <!-- Screenshot space: criterion 1, requirement 2. Paste uploaded image Markdown below this comment. -->

   <br><br>

3. Verification log questions target checkable facts such as row counts, distinct values, date ranges, or known null counts

   **Screenshot evidence:**

   ![CRM dataset chat showing questions about total row count and known null count, with the assistant reporting 499 rows and 315 nulls in loss_reason](screenshots/verification-log-row-and-null-counts.png)

   <br><br>

4. Screenshots show all three CSV datasets successfully imported into SPICE with correct row counts and column counts

   **Screenshot evidence:**

   **Marketing campaigns**

   ![Marketing campaigns dataset summary showing a SPICE badge, 2240 rows imported with 100 percent success, and 23 columns](screenshots/spice-import-marketing-campaigns.png)

   **Support tickets**

   ![Support tickets dataset summary showing a SPICE badge, 3000 rows imported with 100 percent success, and 23 columns](screenshots/spice-import-support-tickets.png)

   **CRM deals**

   ![CRM deals dataset summary showing a SPICE badge, 499 rows imported with 100 percent success, and 20 columns](screenshots/spice-import-crm-deals.png)

   <br><br>


### Criterion 2: Transform and join datasets using no-code data preparation tools

**Submission requirements**

1. Screenshots show data type corrections applied to at least one dataset

   **Screenshot evidence:**

   ![CRM deals data type corrections: deal_created_date and deal_closed_date changed from Datetime to Date](screenshots/data-type-corrections.png)

   ![CRM deals Change data type configuration showing numeric type options and deal_created_date converted from Datetime to Date](screenshots/data-type-corrections-options.png)

   <br><br>

2. At least two calculated fields use business logic (e.g., days-to-close, campaign ROI, ticket frequency)

   **Screenshot evidence:**

   ![CRM deals calculated fields showing the business logic for Days to Close, Win Flag, and Lost Deal Flag](screenshots/calculated-fields-business-logic.png)

   <br><br>

3. A unified dataset joins all three data sources on a shared key, with the join diagram and join configuration visible in screenshots

   **Screenshot evidence:**

   ![Combined dataset diagram with CRM deals, support tickets, and marketing campaigns, showing the Join 2 left join configuration and join keys](screenshots/unified-dataset-join-configuration.png)

   <br><br>

4. Screenshots or report text identify the anchor table and join type used for the unified dataset

   **Screenshot evidence:**

   ![Unified dataset diagram and Join 1 configuration showing support_tickets.csv as the left table, marketing_campaigns.csv as the right table, and Left join selected](screenshots/anchor-table-and-join-type.png)

   <br><br>

5. All four datasets (three source + one unified) are saved to SPICE

   **Screenshot evidence:**

   ![Dataset list showing unified_data.csv, crm_deals.csv, marketing_campaigns.csv, and support_tickets.csv, each with a SPICE badge](screenshots/all-four-datasets-saved-to-spice.png)

   <br><br>


---

## Dashboard Design & Interactivity

### Criterion 3: Design and build a multi-page interactive dashboard for business decision-making

**Submission requirements**

1. Dashboard contains three sheets: Marketing Funnel, Sales Pipeline, and Customer Health

   **Screenshot evidence:**

   **Sales Pipeline**

   **Sales Pipeline Overview**

   ![Sales Pipeline Overview showing KPI cards, deal distribution by stage, customer segment comparisons, loss reasons, and monthly deal creation trends](screenshots/sales-pipeline-overview.png)

   **Revenue by Segment & Product**

   ![Sales Pipeline Revenue by Segment and Product showing KPI cards, revenue by product, customer segment and industry, and a product revenue table](screenshots/sales-pipeline-revenue-by-segment-and-product.png)

   **Win Rates & Sales Performance**

   ![Sales Pipeline Win Rates and Sales Performance showing KPI cards, regional and product win rates, sales representative rankings, manager comparisons, and a revenue leaderboard](screenshots/sales-pipeline-win-rates-and-sales-performance.png)

   **Marketing Funnel — Campaign Lead & Conversion Analysis**

   **Executive Overview**

   ![Marketing Funnel Executive Overview showing KPI cards, monthly revenue and campaign spend trends, channel spend, and campaign comparisons](screenshots/marketing-funnel-executive-overview.png)

   **Channel Performance**

   ![Marketing Funnel Channel Performance showing lead volume, response rates, opportunity and win rates, revenue, spend, and a channel breakdown table](screenshots/marketing-funnel-channel-performance.png)

   **Campaign ROI Analysis**

   ![Marketing Funnel Campaign ROI Analysis showing campaign spend and revenue comparisons, response rates, and a campaign breakdown table](screenshots/marketing-funnel-campaign-roi-analysis.png)

   **Conversion Funnel & Lead Quality**

   ![Marketing Funnel Conversion Funnel and Lead Quality showing funnel stages, customer segments, industry conversion rates, regional win rates, and a funnel breakdown table](screenshots/marketing-funnel-conversion-funnel-lead-quality.png)

   **Customer Health**

   > *Attach Customer Health screenshots here.*

   <!-- Screenshot space: criterion 3, requirement 1. Add the remaining sheet screenshots in their matching spaces above. -->

   <br><br>

2. Each sheet includes at least one KPI summary card and multiple visualizations appropriate to the business questions

   **Screenshot evidence:**

   > *Attach screenshots here.*

   <!-- Screenshot space: criterion 3, requirement 2. Paste uploaded image Markdown below this comment. -->

   <br><br>

3. The Customer Health sheet includes at least one visual built from the unified (joined) dataset

   **Screenshot evidence:**

   > *Attach screenshots here.*

   <!-- Screenshot space: criterion 3, requirement 3. Paste uploaded image Markdown below this comment. -->

   <br><br>

4. At least two sheets include interactive filter controls

   **Screenshot evidence:**

   > *Attach screenshots here.*

   <!-- Screenshot space: criterion 3, requirement 4. Paste uploaded image Markdown below this comment. -->

   <br><br>

5. At least one sheet includes a one-click filtering action on two or more visuals

   **Screenshot evidence:**

   > *Attach screenshots here.*

   <!-- Screenshot space: criterion 3, requirement 5. Paste uploaded image Markdown below this comment. -->

   <br><br>

6. At least one cross-sheet navigation action links between sheets

   **Screenshot evidence:**

   > *Attach screenshots here.*

   <!-- Screenshot space: criterion 3, requirement 6. Paste uploaded image Markdown below this comment. -->

   <br><br>

7. Dashboard is published and exported as a PDF covering all three sheets

   **Screenshot evidence:**

   > *Attach screenshots here.*

   <!-- Screenshot space: criterion 3, requirement 7. Paste uploaded image Markdown below this comment. -->

   <br><br>


---

## AI-Powered Analysis & Communication

### Criterion 4: Configure and use AI-powered natural language querying to explore data

**Submission requirements**

1. Screenshots show baseline Quick Chat interaction (2–3 questions asked before Topic configuration)

   **Screenshot evidence:**

   > *Attach screenshots here.*

   <!-- Screenshot space: criterion 4, requirement 1. Paste uploaded image Markdown below this comment. -->

   <br><br>

2. A Topic is configured, and screenshots show the Topic setup

   **Screenshot evidence:**

   > *Attach screenshots here.*

   <!-- Screenshot space: criterion 4, requirement 2. Paste uploaded image Markdown below this comment. -->

   <br><br>

3. Post-Topic screenshots show the same 2–3 baseline questions re-asked with improved or changed responses

   **Screenshot evidence:**

   > *Attach screenshots here.*

   <!-- Screenshot space: criterion 4, requirement 3. Paste uploaded image Markdown below this comment. -->

   <br><br>

4. Q Exploration Log contains at least 5 entries spanning all three data domains, including at least one cross-dataset question

   **Screenshot evidence:**

   > *Attach screenshots here.*

   <!-- Screenshot space: criterion 4, requirement 4. Paste uploaded image Markdown below this comment. -->

   <br><br>

5. Each log entry includes the question asked, Q's response, and verification against the dashboard

   **Screenshot evidence:**

   > *Attach screenshots here.*

   <!-- Screenshot space: criterion 4, requirement 5. Paste uploaded image Markdown below this comment. -->

   <br><br>


### Criterion 5: Extract and communicate data-driven business insights to stakeholders

**Submission requirements**

1. Dashboard includes 3–5 text annotations visible on the dashboard sheets

   **Screenshot evidence:**

   > *Attach screenshots here.*

   <!-- Screenshot space: criterion 5, requirement 1. Paste uploaded image Markdown below this comment. -->

   <br><br>

2. Each annotation states a quantified finding, a business implication, and a recommended action

   **Screenshot evidence:**

   > *Attach screenshots here.*

   <!-- Screenshot space: criterion 5, requirement 2. Paste uploaded image Markdown below this comment. -->

   <br><br>

3. Written report for VP Sarah Chen is 1–3 pages and covers: data strategy, dashboard design rationale, how Topic configuration affected Q accuracy, key insights with recommended actions, and where AI analysis agreed or disagreed with the dashboard

   **Screenshot evidence:**

   > *Attach screenshots here.*

   <!-- Screenshot space: criterion 5, requirement 3. Paste uploaded image Markdown below this comment. -->

   <br><br>

4. Report defines technical terms on first use, contains no raw SQL or formulas, and uses complete sentences

   **Screenshot evidence:**

   > *Attach screenshots here.*

   <!-- Screenshot space: criterion 5, requirement 4. Paste uploaded image Markdown below this comment. -->

   <br><br>
