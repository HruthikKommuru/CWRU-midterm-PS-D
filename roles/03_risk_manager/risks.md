# Risk Manager — Phone Cases & Accessories Pop-Up

## Findings

### Business Operations

Our proposed business is a phone case and accessories pop-up located in Maple Mall's 400-square-foot Unit 42. The store will operate from June 1 through August 31, 2027.

**Staffing:** The mall requires stores to operate from 10 a.m. to 9 p.m., seven days a week, with at least one employee present. At $16 per hour, our total staffing cost is:

- 92 days × 11 hours = 1,012 staffing hours
- 1,012 hours × $16 = **$16,192**

Rent adds another $7,500 over three months. Together, staffing and rent total **$23,692**, exceeding our $20,000 starting budget. This creates a cash-flow risk, although sales revenue can help cover expenses as the business operates.

*Sources: `inputs/mall_facts.md`; `inputs/cost_list.md`*

### Equipment and Inventory

To minimize startup expenses, we recommend purchasing only the equipment needed for a phone accessories store rather than the $14,500 starter kit.

| Item | Cost |
|---|---:|
| Used display tables and lockbox | $700 |
| Portable sign | $150 |
| Checkout terminal rental | $45/month |
| General vendor permit | $300 |
| Initial inventory | $1,200 |
| Launch promotion | $300 |

Phone cases, cables, and grips cost $4 per item. The $1,200 minimum order would provide 300 items. Because suppliers offer weekly replenishment, we can adjust inventory based on customer demand.

Additional expenses include $100 per month for insurance, $80 per month for cleaning, and a 3% card processing fee.

*Source: `inputs/cost_list.md`*

### Initial Cash Requirements

The business also requires a $2,500 refundable security deposit before opening.

Including the first month's rent, deposit, initial inventory, equipment, permit, promotion, and first-month operating charges, our estimated opening cash requirement is **$7,875**.

This leaves **$12,125** of our $20,000 budget for staffing, future rent, inventory replenishment, and other expenses.

The deposit will not be returned until September 7, meaning it cannot be used to cover expenses during the three-month operation.

*Sources: `inputs/mall_facts.md`; `inputs/cost_list.md`*

### Customer Traffic

According to `inputs/foot_traffic.csv`, approximately **5,531 passing visits** were recorded during a typical week near Unit 42.

- Saturday: 1,529 passing visits
- Sunday: 1,463 passing visits
- Weekends account for approximately **54.1% of weekly traffic**.

Although weekends have the highest traffic, mall rules require the store to remain open every day.

These figures represent passing visits, not guaranteed customers or purchases.

*Sources: `inputs/foot_traffic.csv`; `inputs/mall_facts.md`*

## Top Three Risks and Responses

### Risk 1: High Operating Costs and Cash Shortages

**Risk Level: Critical**

**Problem:** Staffing and rent total $23,692 over three months, exceeding our $20,000 starting budget before inventory and other expenses. The business must generate enough revenue to pay upcoming bills.

**Response:**
- Schedule one employee at a time, using the agency's included break coverage.
- Monitor weekly sales, expenses, and available cash.
- Work with the Finance Analyst to determine minimum weekly sales requirements.
- Maintain enough cash to cover upcoming rent and staffing costs.

*Sources: `inputs/mall_facts.md`; `inputs/cost_list.md`*

### Risk 2: Declining Mall Traffic

**Risk Level: High**

**Problem:** Harlow's department store will close July 31. According to the mall's leasing office, August traffic is expected to decline approximately 30%.

Using the May traffic data:

5,531 × 70% = **approximately 3,872 passing visits per week in August**.

This decline could reduce sales during the final month, when the business needs to reach break-even.

**Response:**
- Focus marketing efforts on June and July.
- Target students at nearby Northfield College.
- Use the mall's free email listings and noticeboard.
- Monitor daily customer traffic and purchases.
- Prepare a lower-sales scenario for August.

*Sources: `inputs/mall_facts.md`; `inputs/foot_traffic.csv`*

### Risk 3: Inventory and Cash Management

**Risk Level: High**

**Problem:** The initial inventory order requires at least $1,200, and suppliers require cash on delivery. Purchasing too many unpopular phone cases could leave money tied up in unsold products.

**Response:**
- Begin with the minimum inventory order.
- Use shopper survey results to identify popular products and acceptable prices.
- Track sales by product and phone model.
- Reorder best-selling products weekly.
- Keep sufficient cash available for staffing and rent.

*Source: `inputs/cost_list.md`*

## Mall Requirements

Before opening, the team must ensure that:

- The $300 general vendor permit is obtained.
- The store is staffed from 10 a.m. to 9 p.m. every day.
- Signs remain inside the leased space and receive mall approval at least two business days before use.
- The security deposit and first month's rent are paid before opening.
- All inventory and displays are removed by August 31 so the refundable deposit can be recovered.

*Sources: `inputs/mall_facts.md`; `inputs/cost_list.md`*

## Recommendation

**We recommend moving forward only if the Finance Analyst confirms that the business can break even by the end of August without running out of cash.**

Our greatest concerns are high staffing expenses, declining mall traffic, and inventory costs.

To reduce these risks, we recommend using inexpensive equipment, purchasing limited initial inventory, monitoring weekly cash flow, and prioritizing marketing during June and July.

The business has the advantage of low equipment costs and flexible weekly inventory replenishment. However, its success depends on generating enough sales to cover mandatory operating expenses.

## Handoff to the Team

**Finance Analyst:** Calculate monthly break-even sales and cash flow, including staffing, rent, the refundable deposit, inventory purchases, and operating expenses.

**Customer Analyst:** Analyze `inputs/shopper_survey.csv` and `inputs/competitors.csv` to determine customer preferences, pricing, and competition.

**Marketing Manager:** Develop a marketing strategy focused on June and July, using free mall advertising and targeting nearby college students. Prepare for lower traffic in August.

**Note:** The shopper survey and competitor files were not available for this analysis. Customer demand, pricing, and competitive assumptions still need to be verified.