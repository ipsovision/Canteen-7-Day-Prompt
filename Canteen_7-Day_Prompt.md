<role>
You are an elite food-business strategist, operations researcher, and product manager for a college canteen.
</role>

<inputs>
Use these inputs when provided: {student_count}, {operating_hours}, {staff_count}, {equipment}, {existing_menu}, {local_prices}, {dietary_requirements}, and {known_demand_data}.
If any input is missing, do not stop and do not invent it. State a conservative assumption in KEY ASSUMPTIONS, label any estimate, and design the plan so the first day measures the missing variable.
</inputs>

<task>
Design and operate a 7-day pilot that improves the canteen as a real business. Use the full ₹10,000 budget intelligently to improve student satisfaction, affordability, revenue, profit, food waste, stock availability, queue speed, service flow, and operational learning.
</task>

<goal>
Produce a practical operating plan for the next 7 days. The plan must behave as one continuous experiment:
PREDICT → SELL → MEASURE → LEARN → ADAPT → REPEAT.

Day 1 must generate useful data.
Day 2 must use Day 1 results.
Day 3 must build on the accumulated evidence.
Continue adapting through Day 7.
</goal>

<constraints>
- Budget: ₹10,000 total for the full 7-day period
- Duration: exactly 7 days
- Coverage: full operating day from opening to closing
- Every day: at least 3–4 meaningful food or drink options
- Realism: limited staff, equipment, storage, time, and money
- Do not spend money that the plan does not have
- Do not assume unlimited demand, staff, kitchen capacity, or storage
- Do not create a huge menu that cannot be prepared reliably
- Do not produce a generic business report
- Do not invent precise facts about the college
- Do not add filler or broad theory
</constraints>

<success_criteria>
Optimize across:
- student satisfaction and affordability
- revenue and profitability
- waste reduction
- availability and stockouts
- queue length and service speed
- efficient use of the budget
- menu quality and variety
- demand management
- learning from daily results
- innovation and engagement
</success_criteria>

<service_model>
Use realistic service periods for a college canteen, such as:
- Morning / breakfast
- Mid-morning break
- Lunch / peak period
- Afternoon
- Evening

For each day, specify:
- opening/service periods
- items available in each period
- total food/drink options across the day
- quantity of each item
- selling price
- estimated unit cost
- when it should be prepared
- when it should be sold
- batch production vs. on-demand execution
- how peak demand is handled
- what happens to leftovers or perishable inventory
- what changed based on the previous day’s results
</service_model>

<menu_design>
Create a practical menu with 3–4 strong complementary items per day.

Use a mix such as:
- affordable high-volume item
- filling meal
- snack
- beverage
- premium/high-margin item
- healthy option
- daily special
- limited-time experimental item

Keep ingredient overlap high to reduce purchasing complexity and waste.
</menu_design>

<budget_rules>
Build a realistic ₹10,000 budget plan for the week.
Do not spend the full amount immediately.
Allocate cash across:
- initial stock
- daily fresh purchases
- replenishment
- packaging and operational costs
- innovation
- emergency reserve

Track and show clearly:
- money spent
- revenue generated
- gross profit
- cash remaining
All quantities, costs, revenue, and cash balances must reconcile mathematically. Show the calculation basis briefly; distinguish expected from guaranteed results.
</budget_rules>

<demand_rules>
Demand is uncertain. Do not guess blindly.
Use practical methods such as:
- student polling or voting
- limited-batch quantities
- bundles
- time-based offers
- pre-order or reservation where feasible
- simple forecasting from previous-day sales
- loyalty or reward mechanisms

The goal is to match supply to real demand while keeping food affordable and service fast.
</demand_rules>

<innovation_rules>
Include at least one genuine innovation that solves a real canteen problem.
It must be:
- inexpensive
- easy to implement quickly
- understandable to students
- practical for staff
- measurable in value
- not just “use AI” or a QR-code gimmick

The innovation should improve one of these: demand, waste, queues, engagement, pricing, or service flow.

Explain:
- what it is
- how it works
- why students use it
- how the canteen uses it
- what problem it solves
- why it matters during this 7-day experiment
</innovation_rules>

<adaptation_rules>
Create a small set of practical rules:
- If an item sells out too early, increase its next-day quantity.
- If an item consistently has leftovers, reduce quantity or change the offer.
- If an item has strong demand but weak margin, adjust price, portion, or bundle.
- If queues become too long, change preparation or service flow.
- If demand is unexpectedly weak, reduce purchasing and use short demand-shaping offers.
- If an experiment works, scale it.
- If it fails, stop it or revise it.
</adaptation_rules>

<edge_case_rules>
- Missing data: state the assumption, use a low-risk starting quantity, and collect the missing data on Day 1.
- Contradictory signals: prioritize safety and affordability, then margin, then variety; explain the trade-off in one sentence.
- Stockout before the next batch: stop taking orders for that item, offer the closest substitute or bundle at a clearly stated price, and record lost demand.
- Unsold perishable food: do not carry it forward if food safety is uncertain; record it as waste and change the next batch.
- Budget pressure: protect essential stock and service operations, then pause innovation or discretionary promotion.
- Impossible request or unsafe practice: identify the conflict and provide the closest feasible, safe alternative.
</edge_case_rules>

<experiment_rules>
Do not overload the canteen with too many tests.
Use a small number of meaningful experiments such as:
- pricing
- bundle structure
- timing changes
- daily specials
- demand forecasting
- pre-orders
- promotion timing
- waste reduction
- service-speed adjustments

Each experiment must have a clear purpose and a measurable outcome.
Use at most one primary experiment per day. For each experiment state: hypothesis, baseline, intervention, metric, target, decision threshold, and next action.
</experiment_rules>

<output_format>
Return the final answer in this exact structure and no other sections.

### 1. CORE STRATEGY
Give the experiment a memorable name.
Explain the concept in 2–4 short paragraphs.

### 2. KEY ASSUMPTIONS
List only the assumptions that materially affect the plan.

### 3. ₹10,000 BUDGET
Show overall allocation and expected cash flow across the week.

### 4. 7-DAY FULL-DAY SCHEDULE
For each day, use this format:

DAY X — OBJECTIVE

| Time/Period | Food/Drink | Quantity | Price | Preparation/Sales Strategy |
|---|---|---:|---:|---|
| Morning | ... | ... | ₹... | ... |
| Mid-morning | ... | ... | ₹... | ... |
| Lunch | ... | ... | ₹... | ... |
| Afternoon/Evening | ... | ... | ₹... | ... |

Then include brief bullets for:
- Daily purchase/preparation plan
- Demand-management action
- Innovation/experiment for the day
- Data collected
- What changes tomorrow based on today’s result

This must cover the full operating day for all 7 days.

### 5. MENU & PRICING LOGIC
Explain why the selected foods and prices make sense.

### 6. DEMAND + WASTE SYSTEM
Explain how the canteen handles uncertainty, stockouts, leftovers, peak demand, slow periods, and replenishment.

### 7. INNOVATION
Explain the chosen mechanism, how it works, and why it matters during the experiment.

### 8. DAILY ADAPTATION RULES
Give a short list of operational rules for daily learning and adjustment.

### 9. SUCCESS METRICS
Track only the most important metrics:
- revenue
- profit
- food cost
- units sold
- waste
- stockouts
- queue/service time
- student satisfaction
- remaining budget
- demand/forecast accuracy where relevant

### 10. FINAL EXECUTION CHECKLIST
End with a brief practical checklist covering:
- what to buy
- what to prepare
- how much
- when to sell
- price
- how to handle demand
- what to measure
- what to change tomorrow
</output_format>

<quality_rules>
- Do not produce a theoretical academic report.
- Do not create a long risk register or large formulas.
- Do not invent precise facts about the college.
- Do not assume unlimited staff or equipment.
- Prioritize 3–4 strong complementary items per day, not 10–15 random options.
- Keep the answer focused on decisions and outcomes.
- The answer should read like an elite team has been handed ₹10,000 and returned with an actual 7-day operating plan.
- If a fact is unknown, write an explicit assumption instead of guessing.
- Use concise but complete operational detail. No filler.
- Use imperative, operational language. Put numbers in tables wherever they improve checking.
- Reconcile the weekly budget, daily purchases, projected sales, and remaining cash; flag uncertainty instead of disguising it as precision.
- Return only the final answer. No intro, no summary, no apology, no meta commentary.
</quality_rules>

<example>
DAY 1 — OBJECTIVE

| Time/Period | Food/Drink | Quantity | Price | Preparation/Sales Strategy |
|---|---|---:|---:|---|
| Morning | Veg sandwich | 30 | ₹40 | Batch-cook at 7:00; sell from 8:00; keep a 10% buffer |
| Mid-morning | Tea | 40 | ₹15 | Brew in batches; replenish at 10:30 |
| Lunch | North Indian thali | 25 | ₹90 | Cook in 3 batches; reserve 20% for pre-orders |
| Afternoon/Evening | Fruit cup | 20 | ₹35 | Prepare in small batches to limit waste |

- Daily purchase/preparation plan: buy 2 days of fresh produce and keep one emergency reserve.
- Demand-management action: run a 15-minute lunch pre-order window to smooth peak demand.
- Innovation/experiment: lunch-preorder board for the next 3 hours.
- Data collected: units sold, leftovers, queue time, satisfaction rating.
- What changes tomorrow: increase the best-selling item by 20% and reduce the item with the most leftovers by 15%.
</example>

<edge_case_example>
If {known_demand_data} is missing, write: “Assumption: 40 lunch customers on Day 1; prepare 32 portions, hold ingredients for 8 more, and use pre-orders to update the next batch.”

If an item sells out early but another item is left over, write: “Record the lost demand, offer the leftover item as a clearly priced bundle, increase tomorrow’s sold-out item, and reduce the leftover item.”

If revenue is strong but cash falls below the reserve, write: “Pause the optional promotion, protect essential ingredients, and revise quantities before adding variety.”
</edge_case_example>

<final_question>
Exactly what should this college canteen do, from opening to closing, for the next 7 days, with ₹10,000, and how should it adapt each day to achieve the best possible result?
</final_question>

