# Notion Template: AI Prompt Library for E-Commerce

*Copy this structure into Notion to organize your prompts, track what works, and build your custom library over time.*

---

## How to Use This Template

1. Create a new Notion page called "AI Prompt Library"
2. Recreate the database structure below
3. Copy in the prompts you use most from the toolkit
4. Track results and iterate

---

## Database: Prompt Library

**Create a Notion database with these properties:**

| Property | Type | Options |
|----------|------|---------|
| Prompt Name | Title | — |
| Category | Select | Product Descriptions, Email Marketing, Social Media, SEO, Customer Service, Photography, Competitive Analysis, Ad Copy |
| Prompt Text | Text (long) | — |
| Variables Used | Multi-select | {product_name}, {target_audience}, {brand_voice}, {price}, {features}, etc. |
| My Custom Variables | Text (long) | Your filled-in values for quick reuse |
| Best Output | Text (long) | Save the best output each prompt has generated |
| Times Used | Number | — |
| Performance Rating | Select | ⭐ Not tested, ⭐⭐ Okay, ⭐⭐⭐ Good, ⭐⭐⭐⭐ Great, ⭐⭐⭐⭐⭐ Money printer |
| Last Used | Date | — |
| Notes | Text | What you changed, what worked, what didn't |
| Status | Select | Active, Needs Tweaking, Retired |

---

## Suggested Views

### View 1: By Category (Board)
- Group by: Category
- Sort by: Performance Rating (descending)
- Filter: Status = Active

### View 2: Most Used (Table)
- Sort by: Times Used (descending)
- Show: Prompt Name, Category, Times Used, Performance Rating, Last Used

### View 3: Needs Attention (Table)
- Filter: Performance Rating = ⭐ or ⭐⭐
- Filter: Times Used > 2
- Purpose: Prompts that aren't working — time to tweak or retire them

### View 4: Swipe File (Gallery)
- Filter: Performance Rating = ⭐⭐⭐⭐ or ⭐⭐⭐⭐⭐
- Show: Prompt Name, Best Output
- Purpose: Quick access to your greatest hits

---

## Page Template: Individual Prompt

For each prompt entry, use this page structure:

```
# {Prompt Name}

## The Prompt
{Full prompt text with variables}

## My Variables
- {variable_1}: My value
- {variable_2}: My value

## Best Output
{Paste the best result this prompt has generated}

## Version History
- v1 (date): Original from toolkit
- v2 (date): Changed X to Y, improved output quality
- v3 (date): Added anti-instruction about Z

## Results
- Used for: {what I created with this}
- Performance: {any measurable result — CTR, open rate, conversion, etc.}
```

---

## Dashboard Page: Prompt Library Home

Create a main page with these linked database views:

```
# 🧠 AI Prompt Library

## Quick Stats
- Total prompts: {number}
- Active prompts: {number}  
- Top performer: {name}

## 🔥 Top Performers
[Linked view: Swipe File — top 5 by rating]

## 📋 Recently Used
[Linked view: sorted by Last Used, limit 5]

## ⚠️ Needs Tweaking
[Linked view: Needs Attention]

## 📁 Browse by Category
[Linked view: By Category board]
```

---

## Bonus: Brand Voice Reference

Add a separate page in your Notion workspace:

```
# Our Brand Voice

## Tone
{Your tone description}

## We Sound Like
{Your brand personality}

## We Never Say
- {word/phrase 1}
- {word/phrase 2}
- {word/phrase 3}

## Sample Sentences
- Good: "{example of on-brand copy}"
- Bad: "{example of what we don't want}"

## Target Customer Quick Reference
- Who: {audience}
- Pain: {main pain point}
- Goal: {what they want to achieve}
- Budget: {range}
```

*Link this page in every prompt entry so it's always one click away.*

---

## Bonus: Content Calendar Database

Create a second database to plan where prompt outputs get used:

| Property | Type | Options |
|----------|------|---------|
| Content Piece | Title | — |
| Platform | Select | Shopify, Email, Instagram, Twitter, Facebook, Pinterest, TikTok, Google Ads, Blog |
| Prompt Used | Relation | → Prompt Library database |
| Status | Select | Draft, Review, Scheduled, Published |
| Publish Date | Date | — |
| Performance | Text | CTR, engagement, conversion — whatever matters |
| Link | URL | Link to the published content |

This closes the loop: prompt → content → results → prompt improvement.

---

*Your prompt library should be a living system, not a filing cabinet. Use it, update it, make it yours.*
