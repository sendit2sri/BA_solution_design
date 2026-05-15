# BA_solution_design

1. Start with this master prompt

I want to learn how Business Analysts design solutions in Temenos T24 / Transact Wealth Management changes.

Do not give me ticket-by-ticket explanation.

Please analyse the available ADO knowledge base and extract recurring BA solution patterns across Wealth Management / Securities / Derivatives / Corporate Actions / Settlements changes.

Focus on:

1. When solution is done through existing T24 parameters
2. When a new local parameter table is created
3. When a local field is added to an existing application
4. When field defaulting is used
5. When field mapping is used from interface/API/upload/OFS to T24 fields
6. When an existing T24 routine/version is reused
7. When a new local routine is required
8. When accounting/category/transaction code changes are needed
9. When settlement/COB/STP processing is impacted
10. When solution is handled through enquiry/report/dashboard instead of transaction change

For each pattern, provide:

* Pattern name
* Business problem type
* Typical T24 applications involved
* Typical BA decision logic
* Example ADO references or change names
* Field-level solution approach
* Testing impact
* Common risks/mistakes

Give the answer as a structured BA learning guide, not as technical developer notes.

2. Then ask SCGPT to classify ADOs automatically

Use this:

From the ADO knowledge base, group Wealth Management / T24 changes into solution categories.

Do not list every ADO separately unless needed.

Group them under these categories:

1. Parameter-only change
2. New local parameter table
3. Local field addition
4. Field mapping/interface change
5. Default value or derived value logic
6. Version/OFS/STP change
7. Accounting/category/transaction code change
8. COB/EOD/SOD/service processing change
9. Enquiry/report/dashboard change
10. Exception handling/override/validation change
11. Product setup or master data change
12. Settlement/Corporate Action/Derivative valuation change

For each category, show:

* What kind of requirement usually falls into this category
* How BA identifies this category
* Common T24 applications involved
* 2–3 representative ADO examples
* Typical solution wording used by BA
* Testing checklist

3. Ask for “BA decision tree”

This is very useful because you want to think like BA.

Create a BA decision tree for T24 Wealth Management change analysis using the ADO knowledge base.

The decision tree should help me decide:

* Can this be solved by existing T24 parameter?
* Should we create a new local parameter table?
* Should we add a local field to an existing application?
* Should we change field mapping?
* Should we add defaulting logic?
* Should we use VERSION/OFS/STP?
* Should we change accounting/category/transaction code?
* Should we handle it through enquiry/report instead of transaction processing?
* Should it be a COB/EOD/service routine change?

For each decision point, explain:

* What question BA should ask
* What evidence to check in ADO/design
* Typical T24 applications involved
* Example solution wording
* Testing impact

4. Ask SCGPT to produce “solution templates”

This will help you write your own BA solutions.

Based on previous ADO solution designs, create reusable BA solution templates for T24 Wealth Management changes.

Create templates for:

1. Parameter change
2. New local parameter table
3. Local field addition
4. Interface field mapping
5. Defaulting logic
6. Validation/override logic
7. Accounting impact
8. Settlement impact
9. Corporate Action impact
10. Derivative pricing/valuation impact
11. COB/EOD process impact
12. Enquiry/report change

Each template should include:

* Requirement summary
* Current behaviour
* Proposed solution
* Application/field impact
* Parameter setup
* Processing logic
* Accounting impact
* Interface impact
* Exception handling
* Testing scope
* BA assumptions/questions

5. Ask it to teach using real ADO examples, but only selected examples

You don’t want 100 ADOs. Ask for top examples.

Pick the top 10 most useful ADO changes from Wealth Management that best teach BA solution design.

Do not pick based on size. Pick based on learning value.

For each ADO/change, explain:

* Business requirement
* Why standard T24 behaviour was not enough
* What solution option was chosen
* Whether it used parameter, local field, mapping, default, routine, version, accounting, enquiry, or COB change
* Why BA may have chosen that approach
* What a junior BA should learn from this
* What test cases are important

Keep the explanation practical and BA-focused.

6. Ask it specifically for Derivatives local/custom handling

Since you mentioned derivatives:

From ADO knowledge base, analyse all Derivatives-related changes.

I want to understand where Temenos core DX functionality was used as-is and where local/custom handling was added.

Group the findings under:

1. DX.PARAMETER / DX.CONTRACT.MASTER setup
2. Price source / price set / valuation changes
3. Margin / MTM / P&L accounting
4. Order/trade lifecycle changes
5. Settlement changes
6. Interface or upload changes
7. Local fields added to DX applications
8. Local parameter tables created
9. COB/EOD/service routine changes
10. Enquiry/report/dashboard changes

For each group, explain:

* Business reason
* Core T24 capability
* Local gap
* BA solution approach
* Testing impact
* Example ADO references

7. Ask for comparison between “core T24” and “bank-specific solution”

This is exactly what you want to learn.

For Wealth Management ADO changes, create a comparison table:

Column 1: Business requirement
Column 2: Standard/core T24 capability
Column 3: Gap or bank-specific need
Column 4: BA solution approach
Column 5: Parameter/local field/mapping/routine/report/accounting impact
Column 6: Example ADO reference
Column 7: Testing impact

Focus on Securities, Derivatives, Corporate Actions, Settlements, Pricing, Accounting, and Interfaces.

8. Best way to use SCGPT weekly

Ask SCGPT like this once per week:

Give me this week’s BA learning summary from the ADO knowledge base for Wealth Management / T24 changes.

Do not list all tickets.

Summarise:

1. New solution patterns seen
2. Parameter changes introduced
3. New local fields or local tables
4. Interface/mapping changes
5. Accounting or settlement impact
6. COB/EOD/STP impact
7. Reusable BA wording
8. Test design learning
9. Questions I should ask senior BA next time

9. My recommended SCGPT question format

Use this structure always:

“Don’t explain ticket by ticket. Extract patterns.”

Your question should contain:

Analyse all relevant ADOs and give me reusable BA solution patterns, with examples only where useful.

That one line will save you from huge ADO-level answers.

Final recommended prompt to start with

Use this first:

I want to become strong in T24 Wealth Management BA solution design.

Using the ADO knowledge base, do not explain each ADO one by one. Instead, extract reusable solution patterns from past changes.

Focus on how BAs decide between:

* existing parameter setup
* new local parameter table
* local field addition
* field mapping
* defaulting logic
* validation/override
* version/OFS/STP
* accounting/category/transaction code
* COB/EOD/service routine
* enquiry/report/dashboard

For each pattern, give:

1. When this pattern is used
2. How BA identifies it
3. Typical T24 applications/fields involved
4. Example ADO references
5. Sample BA solution wording
6. Testing checklist
7. Common mistake to avoid

Make this a practical BA learning guide for Securities, Derivatives, Corporate Actions, Settlements, Pricing, and Accounting.
