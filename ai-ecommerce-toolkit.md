# The AI E-Commerce Toolkit

## 50+ Battle-Tested Prompts for Shopify Store Owners

*By the team behind Pictureline's AI-powered e-commerce stack*

---

**What this is:** A no-bullshit collection of prompts that actually work. Not "write me a product description" — real, tested prompts with variables, examples, and the reasoning behind why they convert. Built from running a real Shopify store, not a content farm.

**How to use it:** Copy a prompt. Replace the `{variables}`. Paste into ChatGPT, Claude, or whatever LLM you use. Get output that's 80% ready to publish. Polish the last 20% with your brand voice.

**Pro tip:** The prompts get better the more context you feed them. Always include your brand voice, target customer, and price point when possible.

---

# Section 1: Product Descriptions

The difference between a product page that converts at 2% and one that converts at 5% is almost always the copy. These prompts generate descriptions that sell without sounding like a used car ad.

---

### Prompt 1.1: The Feature-to-Benefit Transformer

```
You are a senior e-commerce copywriter who specializes in {product_category}.

Write a product description for {product_name} that:
- Opens with a one-sentence hook addressing {target_audience}'s biggest pain point
- Converts these features into emotional benefits: {feature_list}
- Uses sensory language (what it feels like, looks like, sounds like to use this product)
- Includes a subtle urgency element without being sleazy
- Ends with a clear call-to-action

Price point: {price}
Brand voice: {brand_voice}
Word count: 150-200 words

Do NOT use: "elevate," "game-changer," "revolutionary," or "unleash."
```

**Example Input:**
- Product: Sony A7IV Mirrorless Camera
- Category: Professional cameras
- Audience: Enthusiast photographers upgrading from crop sensor
- Features: 33MP full-frame sensor, 10fps burst, 4K60 video, 5-axis IBIS, dual card slots
- Price: $2,498
- Brand voice: Knowledgeable friend, not salesy

**Example Output:**
> You've been squeezing everything out of your crop sensor — and you know it's holding you back. The Sony A7IV is where serious photography starts making sense.
>
> That 33MP full-frame sensor doesn't just capture more light — it captures the kind of detail that makes you zoom in and whisper "damn." Shoot 10 frames per second when the moment won't wait. Drop into 4K60 video without swapping bodies. And the 5-axis stabilization means your handheld shots look like they came off a gimbal.
>
> Dual card slots because losing a wedding shoot to a corrupt card is a nightmare you don't need.
>
> This is the camera you'll keep for five years. At $2,498, it's the last body you buy before going pro.
>
> **Ready to make the jump? Add to cart.**

---

### Prompt 1.2: The Comparison Killer

```
Write a product description for {product_name} that subtly positions it against its top 2-3 competitors without naming them directly.

Target customer: {target_audience} who is actively comparing options
Key advantages over competitors: {competitive_advantages}
Key objection they'll have: {main_objection}
Price: {price}

Structure:
1. Acknowledge they're shopping around (1 sentence)
2. Address the main objection head-on (2-3 sentences)  
3. Present advantages as "what most people don't realize" (3-4 sentences)
4. Social proof element: {review_snippet_or_stat}
5. Close with confidence — no begging

Tone: Confident but not arrogant. Like a friend who actually knows cameras.
```

**Example Output:**
> You've got tabs open. We get it — at this price point, you should compare.
>
> Let's talk about the weight thing. Yeah, it's 20% heavier than the plastic-body alternatives. That's because the magnesium alloy chassis doesn't flex when you mount a 70-200. Your wrists will thank you at hour three of a shoot.
>
> What most people don't realize: the autofocus in this body tracks eyes through obstacles that confuse other systems in this class. The battery lasts 580 shots real-world — not the lab-tested "CIPA" number that means nothing. And the menu system? Actually intuitive. No YouTube tutorial required.
>
> 4.8 stars across 2,400+ reviews. The people who buy this don't return it.
>
> **You already know. Add to cart.**

---

### Prompt 1.3: The SEO-First Description

```
Write an SEO-optimized product description for {product_name}.

Primary keyword: {primary_keyword}
Secondary keywords: {secondary_keywords} (use each naturally 1-2 times)
Product category: {category}

Structure:
- H2 heading that includes the primary keyword
- Opening paragraph (50 words) with primary keyword in first sentence
- 3-4 bullet points starting with action verbs — each includes one secondary keyword
- Closing paragraph (50 words) with primary keyword variation

Requirements:
- Keyword density 1-2% — if it reads like keyword stuffing, rewrite it
- Every sentence must be useful to a human reader FIRST
- Include one question that matches a "People Also Ask" query for this product type
```

---

### Prompt 1.4: The Technical-to-Human Translator

```
I have a product with these technical specifications:
{raw_specs}

Translate each spec into language a {target_audience} would understand. For each spec:
1. State the spec
2. Explain what it means in plain English  
3. Explain why they should care (the "so what?")

Format as a clean table:
| Spec | What It Means | Why You Care |

Skip any spec that doesn't affect the buying decision.
```

**Example Input (partial):**
- Raw specs: "ISO 100-51200 (expandable to 204800), 693-point phase-detect AF, BIONZ XR processor"

**Example Output:**

| Spec | What It Means | Why You Care |
|------|--------------|--------------|
| ISO 100-51200 | How sensitive the sensor is to light. Higher = shoots in darker conditions. | You can shoot a dimly-lit reception at ISO 12800 and still get clean, usable images. No flash needed. |
| 693-point AF | The camera has 693 tiny focus points covering 94% of the frame. | Put your subject anywhere in the frame — not just the center — and it locks on. Game over for "almost in focus" shots. |
| BIONZ XR Processor | The brain that processes your images. 8x faster than the previous generation. | Zero lag between shots. The camera keeps up with you, not the other way around. |

---

### Prompt 1.5: The Story-Driven Description

```
Write a product description for {product_name} structured as a mini-narrative.

Character: {target_audience} persona — give them a name, a situation, a problem
Setting: The moment they realize they need this product
Resolution: How the product solves their specific problem

Constraints:
- Keep it under 200 words
- The product should appear naturally — no "introducing the amazing..."
- End with the character's life AFTER the product, not a sales pitch
- Make it specific enough that {target_audience} thinks "that's literally me"
```

---

### Prompt 1.6: The Bundle Description Builder

```
I'm creating a product bundle called "{bundle_name}" that includes:
{item_1} — retail price {price_1}
{item_2} — retail price {price_2}
{item_3} — retail price {price_3}

Bundle price: {bundle_price} (savings: {savings_amount})

Write a description that:
1. Explains why these items go together (not just "save money")
2. Describes the workflow/experience of using them as a system
3. Addresses the objection: "I already have one of these"
4. Makes the savings feel significant without being discount-braggy

Target customer: {target_audience}
```

---

### Prompt 1.7: The Micro-Description (Collections/Grids)

```
Write a 25-word-max product teaser for {product_name} that appears in a collection grid.

Requirements:
- Must create curiosity or state the #1 benefit
- No feature lists — one compelling thought only
- Must work WITHOUT seeing the product image
- Include one power word: {choose: proven, instant, effortless, essential, precision}

Write 5 versions. Rank them by click-through potential.
```

---

### Prompt 1.8: The Seasonal Refresh

```
I have an existing product description for {product_name}:
"{existing_description}"

Rewrite it for {season/event} (e.g., holiday gift guide, back-to-school, summer sale) without:
- Changing the core product information
- Adding fake urgency ("limited time only!!!")  
- Making it feel like a completely different product

Add seasonal context that makes it relevant NOW. Target: {target_audience} shopping during {season/event}.
```

---

# Section 2: Email Marketing

Email is still the highest-ROI channel for e-commerce. These aren't single emails — they're sequences that build on each other.

---

### Prompt 2.1: The Abandoned Cart Sequence (3 emails)

```
Write a 3-email abandoned cart sequence for a {store_type} Shopify store.

Brand voice: {brand_voice}
Average cart value: {avg_cart_value}
Product left in cart: {product_name}

Email 1 (sent 1 hour after abandonment):
- Subject line: curiosity-based, no "you forgot something!" clichés
- Body: Acknowledge they were browsing, provide ONE helpful detail about the product they might not have seen
- CTA: Back to cart
- Tone: Helpful, not pushy

Email 2 (sent 24 hours):
- Subject line: address the likely objection (price, uncertainty, comparison shopping)
- Body: Social proof — review quote, sales numbers, or expert endorsement
- Include a FAQ answer for the most common question about this product type
- CTA: Back to cart with urgency element

Email 3 (sent 72 hours):
- Subject line: final, direct, no games
- Body: Brief. Offer {incentive — e.g., free shipping, 10% off, bonus item} with a deadline
- CTA: Clear and final
- Include: "If this isn't the right time, no worries — here's something that might help: {related_content_link}"

Write full subject lines, preview text, and body copy for all 3 emails.
```

**Example Output (Email 1 only):**

> **Subject:** That {product_name} is still in your cart (and here's something the page doesn't tell you)
>
> **Preview text:** One detail that changes the math on this...
>
> **Body:**
>
> Hey {first_name},
>
> You were checking out the Sony A7IV earlier — solid choice.
>
> Here's something the product page doesn't emphasize enough: the A7IV uses the same autofocus algorithm as the $3,500 A7RV. Sony quietly brought it down-market. You're getting flagship AF at a mid-range price.
>
> Your cart's still there whenever you're ready.
>
> **[Complete Your Order →]**
>
> Questions? Reply to this email — real person on the other end.
>
> — The Pictureline Team

---

### Prompt 2.2: The Welcome Series (5 emails)

```
Write a 5-email welcome sequence for new subscribers to {store_name}.

Store sells: {product_category}
Brand personality: {brand_voice}
Lead magnet they signed up for: {lead_magnet}
Goal of sequence: Build trust → educate → first purchase

Email 1 (immediate): Deliver the lead magnet + set expectations for what emails they'll get
Email 2 (Day 2): Origin story — why this store exists, who's behind it (use {founder_story_points})
Email 3 (Day 4): Educational content — {top_tip_for_beginners} — position as authority, no selling
Email 4 (Day 7): Product spotlight — introduce {hero_product} through a customer story, not a pitch
Email 5 (Day 10): Soft offer — {first_purchase_incentive} with clear CTA

Each email: subject line, preview text, full body copy. Keep each under 200 words.
```

---

### Prompt 2.3: The Product Launch Sequence

```
Write a 4-email product launch sequence for {new_product_name}.

Launch date: {launch_date}
Price: {price}
Key differentiator: {what_makes_it_different}
Pre-order available: {yes/no}

Email 1 (7 days before): Tease — hint at what's coming without revealing the product
Email 2 (3 days before): Reveal — full product details, specs, beauty shots
Email 3 (Launch day): "It's live" — buy now with launch-day incentive {launch_incentive}
Email 4 (3 days after): Social proof roundup — early reviews, unboxing quotes, UGC

Audience: {existing_customers/new_subscribers/both}
```

---

### Prompt 2.4: The Re-Engagement Sequence

```
Write a 3-email re-engagement sequence for subscribers who haven't opened an email in {timeframe}.

Store: {store_name} selling {product_category}
Total list size: {list_size}
Inactive segment: {inactive_count}

Email 1: "We noticed you've been quiet" — value-first, share something useful (not a coupon)
Email 2: "What would make this worth opening?" — ask what content they want, give 3 options
Email 3: "Last one from us (unless you say otherwise)" — clear unsubscribe option, final value offer

Be honest. Don't be manipulative. If they want to leave, let them leave cleanly.
```

---

### Prompt 2.5: The Post-Purchase Follow-Up

```
Write a post-purchase email sequence for someone who just bought {product_name} from {store_name}.

Email 1 (Immediate): Order confirmation that's actually useful — what to expect, how long shipping takes, one tip for when it arrives
Email 2 (Day 3): "Getting started" — setup tips, common mistakes to avoid, link to {resource}
Email 3 (Day 14): Check-in — how's it going? Ask for feedback (not a review yet)
Email 4 (Day 30): Review request — make it easy, direct link, suggest what to mention
Email 5 (Day 45): Cross-sell — "{product_name} pairs great with {complementary_product}" — educational, not pushy

Tone: {brand_voice}
```

---

### Prompt 2.6: The Win-Back Campaign

```
Write a win-back email for customers who purchased {time_period} ago but haven't returned.

What they bought: {previous_purchase}
What's new since then: {new_products_or_updates}
Incentive: {win_back_offer}

Approach: Don't guilt them. Don't beg. Show them what they've been missing and make it easy to come back. One email, under 150 words.
```

---

### Prompt 2.7: The Flash Sale Announcement

```
Write a flash sale email for {store_name}.

Sale details: {discount_percentage} off {product_category}
Duration: {hours} hours
Start time: {start_time}

Requirements:
- Subject line that creates urgency without ALL CAPS or excessive punctuation
- Body under 100 words — this is about speed, not persuasion
- One hero product featured with original price, sale price, and savings amount
- CTA above the fold
- P.S. line with end time in the customer's timezone language ("ends tonight at midnight")
```

---

### Prompt 2.8: The VIP Early Access Email

```
Write an early-access email for {store_name}'s top customers.

What they're getting early access to: {product_or_sale}
How early: {hours/days} before the public
Why they're getting it: {criteria — e.g., top 10% spenders, loyalty program members}

Make them feel genuinely valued — not just marketed to. This should feel like an insider tip, not a sales blast. Under 120 words.
```

---

# Section 3: Social Media Content

Social media for e-commerce is a different animal. You're not trying to go viral — you're trying to get someone to stop scrolling and tap "Shop Now."

---

### Prompt 3.1: Instagram Caption Generator

```
Write an Instagram caption for a {post_type: product photo / lifestyle shot / behind-the-scenes / UGC repost} featuring {product_name}.

Brand: {store_name}
Audience: {target_audience}
Goal: {engagement / traffic / sales}

Structure:
- Hook (first line — this is all they see before "...more"): Make it a bold statement, question, or hot take
- Body (3-5 lines): Story, tip, or context — NOT a feature list
- CTA: {specific action — comment, save, tap link, share}
- Hashtags: 10-15 relevant hashtags, mix of high-volume (500K+) and niche (10K-50K)

Write 3 versions: one funny, one educational, one emotional.
```

**Example Output (Educational version):**

> Your camera doesn't matter as much as you think. 📸
>
> I've seen $500 setups produce better work than $5,000 kits — because the photographer understood light. The Sony A7IV is an incredible tool, but it won't fix bad composition or flat lighting.
>
> Here's what it WILL do: give you room to grow into. When your skills catch up to your gear, you'll be glad you have 33MP of full-frame detail to work with.
>
> The best camera is the one you'll actually take out and shoot with. Is this one yours? Tap the link in bio.
>
> #sonycamera #a7iv #photographytips #cameragear #mirrorlesscamera #sonyalpha #photographyeducation #camerasetup #fullframe #photographerlife #shoplocal #camerashop

---

### Prompt 3.2: Twitter/X Thread Builder

```
Write a Twitter/X thread ({thread_length} tweets) about {topic} that drives traffic to {product_or_page}.

Account: {brand_or_personal}
Audience: {target_audience}

Tweet 1 (Hook): Bold claim, surprising stat, or contrarian take. Must be compelling enough to get "read the thread" engagement.
Tweets 2-{n-1}: Each tweet delivers one valuable insight. No filler. Each must stand alone AND flow as a sequence.
Final tweet: CTA with link. Not "check out our product" — frame it as the natural next step.

Rules:
- No thread 🧵 emoji in tweet 1 (cringe)
- No "1/" numbering
- Each tweet under 250 characters
- Include 1-2 data points if relevant
```

---

### Prompt 3.3: Pinterest Pin Description

```
Write a Pinterest description for a pin showing {image_description} from {store_name}.

Product: {product_name}
Keywords to include: {pinterest_keywords} (Pinterest is a search engine — treat it like SEO)
Board: {board_name}

Requirements:
- First sentence: what the pin shows and why it matters
- Include 3-5 keywords naturally in the first 100 characters (Pinterest truncates)
- Add context: who it's for, when to use it, what problem it solves
- End with CTA: "Shop the look" / "See details" / "Get the guide"
- 150-300 characters total
```

---

### Prompt 3.4: TikTok Script for Product Features

```
Write a TikTok script for a {duration: 15/30/60} second video showcasing {product_name}.

Format:
- Hook (0-3 seconds): Visual + text overlay that stops the scroll. Options: hot take, "POV:", "Things I wish I knew before..."
- Content (3-{duration-5} seconds): Show {number} features/benefits with quick cuts. Each point gets {2-4} seconds.
- CTA ({duration-5}-{duration} seconds): Where to buy, link in bio, etc.

Style: {casual/educational/trend-based}
Voiceover tone: {conversational/excited/deadpan}
Target audience: {target_audience}

Include: suggested text overlays, transition notes, background music vibe
```

**Example Output:**

> **[0-3s]** HOOK: *Text overlay: "The camera feature nobody talks about"*
> *Shot: Close-up of camera dial clicking to video mode*
> **Voiceover:** "Everyone talks about the specs. Nobody talks about THIS."
>
> **[3-8s]** *Shot: Handheld walking footage, clearly stabilized*
> **Voiceover:** "5-axis stabilization so good, your handheld footage looks like it's on a gimbal."
> *Text overlay: "No gimbal. No rig. Just the camera."*
>
> **[8-15s]** *Shot: Side-by-side — stabilization on vs off*
> **Voiceover:** "Left is what you'd expect handheld. Right is the A7IV raw. No post-processing."
> *Text overlay: "Link in bio — Pictureline.com"*
>
> **Music vibe:** Lo-fi beat, subtle. Not overpowering.

---

### Prompt 3.5: UGC Repost Caption

```
Write a caption for reposting a customer's content on {platform}.

Customer's name: {customer_name}
What they posted: {description_of_their_content}
Product featured: {product_name}
What makes their content special: {why_its_cool}

Requirements:
- Credit them prominently
- Celebrate their work, not your product
- Subtly mention the product without making it the focus
- Include a CTA inviting others to share their content with your hashtag
```

---

### Prompt 3.6: Social Proof Story Slides

```
Create copy for a 5-slide Instagram Story series showcasing customer reviews for {product_name}.

Slide 1: Hook — "What {number} customers are saying about {product_name}"
Slide 2-4: One review each — pull the most compelling quote, add visual direction
Slide 5: CTA — "See why →" with swipe-up/link sticker

For each review slide, include:
- The key quote (20 words max — trim the review to the gold)
- Star rating
- Visual suggestion (background color, product image placement)
- One emoji that matches the vibe of the review

Reviews to work with: {paste_3_reviews}
```

---

### Prompt 3.7: Content Calendar Generator

```
Generate a 2-week social media content calendar for {store_name} selling {product_category}.

Platforms: {platforms}
Posting frequency: {posts_per_week} per platform
Current promotions: {active_promotions}
Upcoming events/launches: {upcoming_events}

For each post, provide:
- Date and platform
- Content type (product photo, educational, UGC, behind-scenes, trend)
- Caption concept (1-2 sentences)
- Visual direction
- Hashtag theme

Rules:
- No more than 40% hard-sell posts
- At least 30% educational/value content
- Include 1-2 trending format adaptations per week
- Vary post types — no three product photos in a row
```

---

### Prompt 3.8: LinkedIn Product Announcement

```
Write a LinkedIn post announcing {product_name} for {store_name}'s business page.

This is B2B-adjacent: the audience is {professional_photographers/videographers/studio_owners/etc.}

Structure:
- Opening line: Industry insight or trend observation (not "Excited to announce!")
- Context: Why this product matters NOW for their business
- 3 bullet points: Business benefits (not consumer features)
- CTA: How to learn more / buy / get a demo
- Keep it under 200 words — LinkedIn rewards concise posts
```

---

# Section 4: SEO & Meta Tags

SEO is boring until you realize it's free traffic that compounds. These prompts handle the tedious optimization work that most store owners skip.

---

### Prompt 4.1: Product Page Title Tag

```
Write 5 title tag options for this product page:

Product: {product_name}
Primary keyword: {primary_keyword}
Brand: {store_name}
Unique selling point: {usp}

Requirements:
- Under 60 characters (STRICT — Google truncates at 60)
- Primary keyword in the first half
- Include brand name or USP — not both (character limit)
- At least one version with a power word (best, top, pro, essential)
- At least one version with a year: {current_year}

Rank all 5 by expected CTR and explain why.
```

**Example Output:**

> 1. **Sony A7IV Full-Frame Camera | Pictureline** (45 chars) — Brand recognition + clean. CTR: Medium.
> 2. **Sony A7IV — Best Full-Frame Under $2,500** (42 chars) — Price qualifier attracts serious buyers. CTR: High.
> 3. **Sony A7IV Review & Price (2026) | Buy at Pictureline** (52 chars) — Year freshness + transactional intent. CTR: High.
> 4. **Buy Sony A7IV Mirrorless Camera — Free Shipping** (49 chars) — Transactional + incentive. CTR: Medium-High.
> 5. **Sony A7IV: Pro Full-Frame Camera for Enthusiasts** (50 chars) — Audience qualifier. CTR: Medium.
>
> **Winner: #2** — Price qualifier pre-qualifies clicks (reduces bounce), power word "Best" drives CTR, and it's under 45 chars so it'll never truncate.

---

### Prompt 4.2: Meta Description Generator

```
Write a meta description for {page_type: product/collection/blog post} about {topic}.

Primary keyword: {primary_keyword}
Page URL: {url}
Unique angle: {what_makes_this_page_different}

Requirements:
- 150-155 characters (STRICT)
- Include primary keyword naturally
- Include a CTA or value proposition
- Include one emotional trigger (curiosity, urgency, social proof)
- Do NOT start with the brand name

Write 3 options. Count the characters for each.
```

---

### Prompt 4.3: Collection Page SEO Copy

```
Write SEO-optimized copy for a Shopify collection page: "{collection_name}"

Products in this collection: {product_types}
Primary keyword: {primary_keyword}
Secondary keywords: {secondary_keywords}
Target audience: {target_audience}

Structure:
1. H1: Collection name with primary keyword (if not already present)
2. Intro paragraph (80-100 words): What this collection is, who it's for, why shop here
3. Buying guide section (100-150 words): H2 "How to Choose the Right {product_type}" — 3-4 decision factors
4. FAQ section: 3 questions that match "People Also Ask" for {primary_keyword}

Requirements:
- Primary keyword appears in H1, first paragraph, and one FAQ answer
- Secondary keywords appear naturally throughout
- Links to 2-3 specific products within the copy
- Reads like a helpful guide, not a keyword dump
```

---

### Prompt 4.4: Blog Post Outline for Product-Related Content

```
Create a detailed blog post outline targeting the keyword "{target_keyword}."

Search intent: {informational/commercial/transactional}
Monthly search volume: {volume} (if known)
Our relevant products: {products_to_link}

Outline structure:
- Title (with keyword, under 60 chars)
- Meta description
- H2 sections with brief description of what each covers
- Word count target per section
- Internal product links: where to naturally insert them
- External authority links: 2-3 sources to cite
- CTA at the end: What product or page to push

Requirements:
- Every H2 should answer a question someone would actually Google
- Include one data point or statistic per section (I'll source them)
- Outline should be detailed enough that any writer could execute it
```

---

### Prompt 4.5: Schema Markup Product Description

```
Write a product description optimized for Google rich snippets / schema markup.

Product: {product_name}
Price: {price}
Brand: {brand}
SKU: {sku}
Availability: {in_stock/out_of_stock/preorder}
Rating: {rating} ({review_count} reviews)

Write:
1. A name field (under 70 chars, keyword-rich)
2. A description field (under 200 chars, benefits-focused)
3. 3 suggested review snippets (that would look great in search results)

Also generate the JSON-LD schema markup with all fields populated.
```

---

### Prompt 4.6: Alt Text Generator

```
Write SEO-optimized alt text for {number} product images.

Product: {product_name}
Image descriptions:
1. {image_1_description}
2. {image_2_description}
3. {image_3_description}

Requirements:
- Each alt text under 125 characters
- Include the product name in at least 2
- Describe what's IN the image, not what the product IS
- Include one keyword variation per alt text
- Don't start with "Image of" or "Photo of"
```

---

### Prompt 4.7: Internal Linking Strategy

```
I have these pages on my Shopify store:
{list_of_key_pages_with_urls}

And I'm writing a blog post about: {blog_topic}

Suggest:
1. Which pages to link FROM the blog post (with suggested anchor text)
2. Which existing pages should link TO this new blog post
3. The ideal anchor text for each link (keyword-rich but natural)

Rules:
- No more than 3-4 internal links per 500 words
- Anchor text should never be "click here" or "learn more"
- Each link should feel natural within the sentence
```

---

### Prompt 4.8: Competitor Keyword Gap Analysis Prompt

```
I run {store_name} selling {product_category}. My top 3 competitors are:
1. {competitor_1}
2. {competitor_2}
3. {competitor_3}

Based on common keywords in this product category, generate:
1. 20 keywords they're likely ranking for that I should target
2. 10 long-tail keywords they're probably ignoring (low competition opportunities)
3. 5 content topics where I could outrank them with better content

For each keyword, estimate: search intent, difficulty (low/med/high), and the best page type (product page, collection, blog post).
```

---

# Section 5: Customer Service

Good customer service copy is invisible — it resolves the issue and reinforces the brand without drawing attention to itself. These templates sound human because they're written to be human.

---

### Prompt 5.1: The Return Request Response

```
Write a customer service response for a return request.

Store: {store_name}
Return policy: {return_policy_summary}
Customer's reason for return: {reason}
Product: {product_name}
Days since purchase: {days}
Within return window: {yes/no}

If within policy: Approve gracefully, provide clear next steps, make it easy
If outside policy: Empathize, explain the policy, offer an alternative ({store_credit/exchange/escalation})

Tone: Warm, efficient, no corporate speak. Like a helpful person, not a policy robot.
Max length: 150 words.
```

**Example Output (within policy):**

> Hi {customer_name},
>
> No problem at all — I'll get this started for you right away.
>
> Here's how it works:
> 1. I'm emailing you a prepaid return label — check your inbox in the next 10 minutes
> 2. Pack the A7IV in its original box (if you still have it — if not, any sturdy box works)
> 3. Drop it at any UPS location
> 4. Once we receive it (usually 3-5 business days), your refund processes within 48 hours
>
> If you'd prefer an exchange for a different model instead, just let me know — happy to help you find the right fit.
>
> Anything else I can do?
>
> — Sarah, Pictureline Support

---

### Prompt 5.2: The Complaint De-escalator

```
Write a response to an angry customer complaint.

Customer's complaint: {complaint_details}
Is the complaint valid? {yes/partially/no}
What we can do about it: {resolution_options}
Has this customer ordered before? {yes/no — and total_orders if yes}

Framework:
1. Acknowledge their frustration (without being condescending)
2. Take responsibility where appropriate (no "I'm sorry you feel that way")
3. Present the solution clearly
4. Add one unexpected extra (rush shipping, discount on next order, personal follow-up)
5. Close with confidence — they should feel BETTER after reading this

Never: blame shipping carriers, use passive voice ("mistakes were made"), or say "per our policy."
```

---

### Prompt 5.3: Shipping Delay Notification

```
Write a proactive shipping delay email for order #{order_number}.

Customer: {customer_name}
Original estimated delivery: {original_date}
New estimated delivery: {new_date}
Reason: {reason — be honest}
What we're doing about it: {action_taken}

This email should:
- Lead with the update (don't bury the bad news)
- Be honest about the reason without oversharing
- Give them a specific new date (not "soon")
- Offer tracking + a way to reach a human
- Include a small gesture: {goodwill_offer — e.g., free expedited shipping, store credit, discount code}
```

---

### Prompt 5.4: The Review Request

```
Write a review request email sent {days} days after delivery of {product_name}.

Requirements:
- Don't beg — frame it as helping other shoppers
- Include a direct link to leave a review (placeholder: {review_link})
- Suggest what to mention (without scripting their review): "Other shoppers often want to know about {aspect_1}, {aspect_2}, and {aspect_3}"
- Make it take less than 2 minutes
- Optional incentive: {incentive — e.g., "enter our monthly $50 gift card drawing"}

Subject line: Not "How was your purchase?" — something they'd actually open.
Under 100 words.
```

**Example Output:**

> **Subject:** Quick question about your A7IV (takes 60 seconds)
>
> Hey {customer_name},
>
> You've had the A7IV for a couple weeks now — how's it treating you?
>
> If you've got 60 seconds, a quick review helps other photographers figure out if this is their camera: **[Leave a Review →]**
>
> Other buyers usually want to know about image quality in low light, how the autofocus performs with moving subjects, and whether the battery life holds up on long shoots.
>
> Thanks for being a Pictureline customer — we appreciate you.
>
> — The Pictureline Team

---

### Prompt 5.5: The FAQ Generator

```
Generate a FAQ section for {product_name} or {product_category} page.

Based on:
- Common customer questions we receive: {list_questions_if_available}
- The product's main features: {key_features}
- Common objections: {objections}
- Competitor comparisons customers make: {competitors}

Generate 8-10 Q&A pairs that:
- Use natural question language (how people actually ask, not marketing-speak)
- Answer in 2-3 sentences max
- Address at least 2 objections disguised as questions
- Include one question about compatibility/accessories
- Include one question about warranty/support
```

---

### Prompt 5.6: The Damage/Defect Response

```
A customer received {product_name} with {damage_description}.

Order: #{order_number}
Photos provided: {yes/no}
Replacement available: {yes/no — and timeline}

Write a response that:
1. Expresses genuine concern (not form-letter sympathy)
2. Doesn't ask for proof if they've already provided it (don't make them jump through hoops)
3. Presents resolution options in order of customer preference: full replacement → partial refund → store credit
4. Gives specific timelines for each option
5. Includes a way to escalate if they're not satisfied

This person is already annoyed. Don't make it worse.
```

---

### Prompt 5.7: The Pre-Purchase Question Response

```
A potential customer asked: "{customer_question}" about {product_name}.

Write a response that:
1. Answers their question directly (first sentence)
2. Adds one piece of context they didn't ask about but should know
3. Subtly guides toward purchase without being pushy
4. Offers to help with anything else

If the answer might push them toward a different (better-fit) product, recommend it honestly. Trust > one sale.
```

---

### Prompt 5.8: The Subscription/Loyalty Program Pitch

```
Write a response to a customer inquiry that naturally introduces {store_name}'s loyalty program.

Customer's original question: {question}
Loyalty program details: {program_details}
How it's relevant to their situation: {connection}

The mention of the loyalty program should feel like a helpful tip, not an upsell. If it doesn't naturally fit the conversation, don't force it — just answer their question.
```

---

# Section 6: Product Photography Directions

These prompts help you direct AI image editing tools, write shot lists for photographers, and create lifestyle imagery descriptions for AI image generators.

---

### Prompt 6.1: AI Background Replacement Instructions

```
Write detailed instructions for an AI image editing tool to replace the background of a product photo.

Product: {product_name}
Current background: {current_background — e.g., white seamless, cluttered desk}
Desired background: {desired_background}
Mood: {mood — e.g., professional, warm, adventurous, minimalist}
Target platform: {where_this_image_will_be_used — e.g., Shopify PDP, Instagram, print ad}

Instructions should include:
- Lighting direction and intensity to match the product
- Shadow placement and softness
- Color temperature of the background
- Depth of field suggestion
- Any reflections or environmental interactions (product sitting ON something vs floating)
```

**Example Output:**

> Replace the white background with a warm, moody wooden desk scene.
>
> **Background details:**
> - Dark walnut desk surface with subtle grain visible
> - Depth of field: background should blur starting 12 inches behind the product (f/2.8 simulation)
> - Warm color temperature (5200K) to match the product's silver body
>
> **Lighting match:**
> - Main light from upper-left at 45 degrees (matching the product's existing highlights)
> - Soft shadow falling to the lower-right, approximately 15% opacity
> - No harsh edges on the shadow — simulate a large softbox
>
> **Environmental interactions:**
> - Product should appear to be SITTING on the desk (add contact shadow, 3px soft, directly underneath)
> - Subtle reflection on the desk surface (10% opacity, slightly stretched vertically)
> - Add a slightly out-of-focus coffee mug in the far right background for lifestyle context

---

### Prompt 6.2: Lifestyle Shot Description Generator

```
Write a detailed prompt for an AI image generator (Midjourney/DALL-E/Stable Diffusion) to create a lifestyle scene featuring {product_name}.

Target audience: {target_audience}
Use case being shown: {how_the_product_is_being_used}
Setting: {environment}
Mood/emotion: {desired_feeling}
Season/time of day: {time_context}

Generate the prompt in this structure:
[Subject], [Action], [Environment], [Lighting], [Mood], [Camera specs], [Style modifiers]

Also generate a negative prompt to avoid common AI artifacts.
Include the --ar (aspect ratio) for the intended platform: {platform}
```

---

### Prompt 6.3: Product Photo Shot List

```
Create a 10-shot product photography shot list for {product_name}.

Intended use: {shopify_pdp / social_media / both}
Available equipment: {lighting_and_background_available}
Key features to highlight: {features_to_show}

For each shot, provide:
1. Shot name and angle (e.g., "Hero — 3/4 front angle")
2. What it shows and why it matters for the buyer
3. Lighting setup (1-2 sentences)
4. Background/surface suggestion
5. Any props needed
6. Post-processing notes (crop ratio, color grade direction)

Order shots by importance — the first 3 should cover the product page hero, and the rest fill the gallery.
```

---

### Prompt 6.4: Before/After Image Description

```
Write copy for a before/after product comparison image.

Product: {product_name}
"Before" scenario: {without_product — what's the pain?}
"After" scenario: {with_product — what's the improvement?}

Write:
- Overlay text for the "before" side (5 words max)
- Overlay text for the "after" side (5 words max)
- Caption that ties it together (one sentence)
- Art direction: what should the visual comparison actually show?
```

---

### Prompt 6.5: Image Alt Text and Caption Set

```
Write a complete image optimization set for {number} product images of {product_name}.

For each image, provide:
1. Alt text (SEO-optimized, under 125 chars)
2. Instagram caption (if used on social)
3. Pinterest description (keyword-rich)
4. Filename suggestion (lowercase, hyphenated, keyword-rich)

Image descriptions:
{describe_each_image}
```

---

### Prompt 6.6: AI Image Editing Batch Instructions

```
I need to process {number} product images for {product_name} using {ai_tool — e.g., Photoroom, Remove.bg, Canva}.

For all images:
- Background: {background_spec}
- Shadow: {shadow_spec}
- Padding: {padding — e.g., 10% on all sides}
- Output size: {dimensions} at {resolution}
- File format: {format}

For specific images:
{image_1}: {special_instructions}
{image_2}: {special_instructions}

Write step-by-step instructions that a VA or junior designer could follow without asking questions.
```

---

# Section 7: Competitive Analysis

Know your competition without obsessing over them. These prompts help you extract useful intelligence from public information.

---

### Prompt 7.1: Competitor Store Teardown

```
Analyze this competitor's Shopify store: {competitor_url}

Evaluate:
1. **Homepage:** What's the value prop? Is it clear in 5 seconds? What's the primary CTA?
2. **Product pages:** How are descriptions structured? What's their review strategy? Do they use video?
3. **Navigation/UX:** How easy is it to find products? How many clicks to purchase?
4. **Content strategy:** Do they have a blog? Email capture? Social proof elements?
5. **Pricing/positioning:** Premium, mid-range, or budget? How do they justify their prices?
6. **What they do better than us:** Be honest.
7. **Where we can beat them:** Specific, actionable opportunities.

I sell {product_category} at {store_name}. Focus the analysis on things I can actually act on within 30 days.
```

---

### Prompt 7.2: Pricing Position Analysis

```
Help me position {product_name} priced at {price} against:
- {competitor_1_product}: {competitor_1_price}
- {competitor_2_product}: {competitor_2_price}
- {competitor_3_product}: {competitor_3_price}

My product's advantages: {advantages}
My product's disadvantages: {disadvantages}

Generate:
1. A pricing narrative — how to frame our price on the product page
2. A comparison angle — what to emphasize when customers say "but X is cheaper"
3. A value stack — list everything included (warranty, support, shipping, extras) to increase perceived value
```

---

### Prompt 7.3: Market Gap Identifier

```
I sell {product_category} through my Shopify store {store_name}.

Based on these competitor observations:
{competitor_observations — what they sell, how they sell it, who they target}

Identify:
1. 3 customer segments competitors are ignoring
2. 3 content topics none of them are covering well
3. 3 product features/bundles no one is offering
4. 1 pricing model nobody in this space is using (subscription, bundle, try-before-buy, etc.)

For each, explain: why it's an opportunity, who would care, and how hard it would be to execute.
```

---

### Prompt 7.4: SWOT Analysis Generator

```
Generate a SWOT analysis for {store_name} in the {product_category} market.

Our details:
- Revenue range: {revenue_range}
- Team size: {team_size}
- Unique advantages: {what_we_do_well}
- Known weaknesses: {honest_weaknesses}

Top 3 competitors: {competitor_names_with_brief_descriptions}

Market trends: {relevant_trends}

Format as a 2x2 grid with 4-5 bullet points per quadrant.
Keep each bullet point actionable — not just observations, but "so do THIS."
```

---

### Prompt 7.5: Review Mining for Product Development

```
Analyze these customer reviews from competitors selling {product_category}:
{paste_15_20_reviews}

Extract:
1. Top 5 things customers love (and how we can replicate/improve)
2. Top 5 complaints (and how we can solve them)
3. Features customers request that don't exist yet
4. Language patterns — exact phrases customers use (for our copywriting)
5. Pricing sentiments — do they feel they overpaid, got a deal, or felt it was fair?

Present findings as a prioritized action list: quick wins vs. long-term opportunities.
```

---

### Prompt 7.6: Competitor Email Teardown

```
I subscribed to {competitor_name}'s email list and received these emails:
{paste_or_describe_emails}

Analyze:
1. Send frequency and timing patterns
2. Subject line strategy (what psychological triggers are they using?)
3. Content mix (promotional vs. educational vs. transactional)
4. Design choices (image-heavy vs. text-heavy, mobile optimization)
5. CTAs used and their placement
6. What's working (what I should adapt)
7. What's missing (what I can do better)
```

---

# Section 8: Ad Copy

Paid ads are expensive. Bad copy makes them more expensive. These prompts are built for the constraints of ad platforms — character limits, compliance rules, and the 2 seconds you have to grab attention.

---

### Prompt 8.1: Facebook/Instagram Ad Copy

```
Write Facebook/Instagram ad copy for {product_name}.

Campaign objective: {awareness/traffic/conversions}
Target audience: {audience_details}
Price: {price}
Key offer: {discount/free_shipping/bundle/none}
Landing page: {url}

Write 3 variations:

Variation A (Short — under 125 characters for primary text):
- Primary text
- Headline (40 chars max)
- Description (30 chars max)

Variation B (Medium — story-based, under 250 characters):
- Primary text with a hook, problem, solution structure
- Headline + description

Variation C (Long — testimonial/social proof based):
- Primary text featuring a customer quote or result
- Headline + description

For all: include a CTA button suggestion (Shop Now / Learn More / Get Offer)

Rules:
- No banned words (Facebook ad policy): "you" in certain health contexts, guaranteed results, etc.
- No ALL CAPS in headlines
- No excessive emoji (1-2 max per variation)
```

**Example Output (Variation A):**

> **Primary text:** Full-frame doesn't have to mean full price. The Sony A7IV delivers pro results at $2,498. Free shipping this week.
>
> **Headline:** Sony A7IV — Full-Frame, Finally Affordable
> **Description:** Free shipping + expert support
> **CTA button:** Shop Now

---

### Prompt 8.2: Google Shopping Product Description

```
Write a Google Shopping optimized product description for {product_name}.

Requirements:
- 150-500 characters (Google Merchant Center limit)
- First 70 characters are most important (visible in search results)
- Include: brand, product type, key spec, and differentiator
- No promotional text (Google Shopping policy: no "best price" or "free shipping")
- No ALL CAPS
- Include {color}, {size/model}, {material} if applicable

Write 3 versions at different lengths: 150, 300, and 500 characters.
```

---

### Prompt 8.3: Retargeting Ad Copy

```
Write retargeting ad copy for someone who:
{retargeting_scenario — e.g., viewed product, added to cart, visited 3+ times}

Product: {product_name}
Days since last visit: {days}

The copy should:
- Acknowledge they've seen this before without being creepy ("Still thinking about it?" not "We saw you looking at...")
- Address the most likely objection at this stage: {likely_objection}
- Include a new piece of information they probably didn't see
- Create urgency without lies (real stock levels, real deadline, real price change)

Write for: {Facebook/Instagram/Google Display/all three}
```

---

### Prompt 8.4: Google Search Ad Copy

```
Write Google Search ad copy for the keyword "{target_keyword}."

Character limits:
- Headlines (up to 15): 30 characters each
- Descriptions (up to 4): 90 characters each

Write:
- 5 headline options (mix of keyword-match, benefit, and CTA types)
- 3 description options
- Suggested responsive search ad combination (3 headlines + 2 descriptions)

Requirements:
- Include the exact keyword in at least 2 headlines
- Include price or price qualifier in one headline
- Include a CTA in at least one headline ("Buy," "Shop," "Get")
- Descriptions should include social proof, shipping info, or guarantee
- Suggest sitelink extensions: 4 with titles and descriptions
```

---

### Prompt 8.5: Ad A/B Test Variants

```
I have this existing ad that's performing at {current_performance — CTR, ROAS, CPC}:

{paste_existing_ad}

Generate 3 A/B test variants that each change ONE variable:

Variant A: Different hook/opening line (same offer, same CTA)
Variant B: Different social proof angle (same hook, same CTA)
Variant C: Different CTA or urgency element (same hook, same body)

For each, explain: what you changed, why you think it'll perform differently, and what metric to watch.
```

---

### Prompt 8.6: Seasonal Ad Campaign Brief

```
Write a creative brief for a {season/holiday} ad campaign for {store_name}.

Campaign dates: {start_date} to {end_date}
Budget: {budget}
Products to feature: {products}
Target audience: {audience}
Channels: {channels}

Deliver:
1. Campaign theme/tagline (3 options)
2. Key message hierarchy (what to say first, second, third)
3. Ad formats needed with copy for each (e.g., Stories, Feed, Search)
4. Promotional calendar (when to launch, peak, wind down)
5. Landing page recommendations (what the LP should say/show)
```

---

### Prompt 8.7: Influencer Collaboration Brief

```
Write a brief for an influencer promoting {product_name} on {platform}.

Influencer type: {macro/micro/nano}
Audience alignment: {how_their_audience_matches_ours}
Deliverables: {number_of_posts, stories, reels, etc.}
Key messaging: {must_mention_points}
Avoid: {things_they_should_NOT_say}
Disclosure: FTC compliance — #ad or #sponsored must be included

Include:
- Suggested script/talking points (not a word-for-word script — authentic > scripted)
- Creative direction for visuals
- Caption framework they can customize
- CTA with unique tracking link/code: {tracking_code}
```

---

### Prompt 8.8: Dynamic Ad Copy for Product Catalog

```
Write dynamic ad copy templates for a product catalog campaign (Facebook DPA / Google Performance Max).

Product category: {category}
Number of products: {number}
Price range: {range}

Write template copy using dynamic variables:
- {{product.name}}
- {{product.price}}
- {{product.brand}}
- {{product.description}}

Templates needed:
1. Generic (works for any product in the catalog)
2. Price-focused (for products over ${threshold})
3. New arrival (for products added in last 30 days)
4. Best-seller (for top 10 products by sales)
5. Low stock (for products with under {number} remaining)

Each template: primary text, headline, description.
```

---

# Appendix: Prompt Engineering Tips for E-Commerce

These tips will make every prompt in this toolkit work better.

### 1. Always Set the Role
Start with "You are a [specific role]..." — a senior copywriter, a Shopify SEO expert, a conversion rate optimizer. Specificity gets better outputs.

### 2. Include Anti-Instructions
Tell the AI what NOT to do. "Don't use clichés," "Don't start with a question," "Don't exceed 150 words." Constraints improve creativity.

### 3. Provide Examples of What Good Looks Like
Paste a product description you love and say "write in this style." LLMs are exceptional mimics.

### 4. Use the "Rank and Explain" Technique
When generating multiple options, always ask the AI to rank them and explain why. This forces deeper thinking and gives you better options.

### 5. Iterate, Don't Regenerate
If the output is 70% right, tell the AI what to fix — don't start over. "Make it shorter," "Remove the cheesy CTA," "Add a price anchor." Refinement beats regeneration.

### 6. Feed It Your Data
The more context you provide (past emails that performed well, reviews, competitor examples), the better the output. Don't be lazy with inputs and expect great outputs.

### 7. Temperature Matters
For factual content (SEO, product specs): use lower temperature (0.3-0.5).
For creative content (ad copy, social media): use higher temperature (0.7-0.9).
Most interfaces don't expose this, but if yours does — use it.

---

*Built by people who actually sell things online. Not by people who blog about selling things online.*

*© 2026 — The AI E-Commerce Toolkit*
