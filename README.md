# Future Interns — Prompt Engineering Task 1
## AI Website Copy Generator for Local Businesses

**Intern Task ID:** FIT/JUL26/PE3621
**Repo:** FUTURE_PE_01

---

## Business Chosen

**Apex NEET-JEE Academy** — Coimbatore, Tamil Nadu
A local coaching institute preparing Class 11-12 students for NEET and 
JEE entrance exams.

**Why this business:** Coaching institutes are a high-competition, 
high-stakes local market where website copy directly affects trust — 
parents are choosing where their child spends the most important year 
of their academic life. Most local institutes have generic, template-y 
websites that don't differentiate them from bigger chains like Aakash 
or Allen. This makes it a strong real-world test case for 
conversion-focused copywriting.

---

## Tool Used

**Claude** (claude.ai) — used to design the prompt framework and 
generate all copy output.

---

## Prompt Logic

Instead of writing one-off content, this project builds a **reusable 
prompt system** — four structured prompt templates, each targeting one 
part of a business website:

1. **Homepage prompt** — generates a headline (value proposition), 
   sub-headline (audience + benefit), and intro paragraph that 
   addresses the customer's real underlying fear or need.
2. **Services prompt** — generates service/program descriptions with 
   what's included and why a customer should choose this business over 
   competitors.
3. **CTA prompt** — generates three CTA types: booking, trust-building, 
   and urgency-based.
4. **Tone adaptation prompt** — a separate reusable layer that rewrites 
   any base copy into the right tone for a given business type (friendly 
   for salons/cafes, professional for clinics/agencies, confident-simple 
   for coaching institutes). This is what makes the system reusable 
   across different clients, not just this one.

Each prompt follows the same structure: **Role → Business Context → 
Task → Rules**. The Rules section is what prevents generic AI-sounding 
output — it explicitly bans vague phrases ("unlock your potential"), 
fake guarantees ("100% rank guaranteed"), and forces concrete, specific 
details (batch sizes, exam names, local context).

---

## Folder Structure