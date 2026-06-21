# blsf-marketplace
*AI-powered luxury salon discovery marketplace for Bangalore—verified reviews, stylist matching,  instant booking. Targets ₹1,200 Cr market.*

## **The Problem**

Bangalore's luxury salon market is **fragmented, unverified, and inaccessible:**

- **68%** of women spend 2–3 hours finding the right salon (primary research)
- **No discovery platform** combines verified reviews + stylist specialization + personalization
- **Fake reviews** dominate Google Maps and Instagram; customers can't verify stylist skill
- **Offline booking friction** persists (WhatsApp DMs, unanswered calls, no real-time availability)
- **Top 5 pain points** by *severity × frequency*:
  1. Fake/incentivized reviews *(severity 5/5, frequency 5/5)*
  2. Hidden pricing until you call *(4/5, 5/5)*
  3. Can't verify stylist skill *(5/5, 4/5)*
  4. No personalization to hair/skin type *(4/5, 4/5)*
  5. Last-minute availability requires phone calls *(3/5, 5/5)*

**Existing competitors miss the luxury niche:** Urban Company dominates home services but not in-studio luxury. Fresha/Treatwell are generic booking tools with no trust layer. Local directories (Justdial, Sulekha) are stale. Instagram has discovery but zero transactional layer.

**Key Features:**
- **AI Salon Matchmaker:** Natural-language search ("balayage specialist in Indiranagar under ₹6,000") returns curated, ranked salon + stylist matches with explainable rationale
- **Verified Review Summarizer:** AI condenses hundreds of reviews into honest, weighted takeaways (key pros/cons, expert insights)
- **Stylist-Level Profiles:** Book by name, not just salon; see specific stylist portfolios, credentials, verified photos
- **Transparent Pricing:** Price bands displayed upfront; no hidden costs until booking
- **Persistent Beauty Profile:** Cross-salon history (hair type, skin tone, allergy notes, past services) for personalization
- **Real-Time Booking:** 3-tap flow: select service → select stylist/slot → confirm

## **Market Opportunity**

### **Bangalore Luxury Salon Hubs (Phase 1 Launch)**
- **Indiranagar:** Young professionals, trendy studios, high app adoption
- **Koramangala:** Startup founders, tech employees, convenience-driven
- **HSR Layout:** Tech professionals, value-conscious luxury
- **Whitefield:** IT-park employees, spa-wellness integration
- **Jayanagar, JP Nagar, MG Road, Richmond Town, Sadashivanagar:** Multi-tier expansion targets

### **Target Customer Personas**
1. **Priya (Corporate Professional)** – Quick, reliable, no-surprise grooming; ₹1,500–4,000/visit
2. **Ananya (Luxury Beauty Enthusiast)** – Discovers specialists, tries new studios; ₹4,000–12,000/visit
3. **Meera (Bride-to-Be)** – Researches extensively, books trials; ₹20,000–1,50,000/full package
4. **Riya (Social Media Influencer)** – Needs fast booking, photogenic ambience; ₹3,000–10,000/visit
5. **Vikram & Sanjana (HNI Couple)** – White-glove service, top stylists, privacy; ₹10,000–50,000+/visit

## **Unit Economics & Revenue Model**

### **Business Model Streams**

| Revenue Stream | Model | Year 1 Target |
|---|---|---|
| **Commission on Bookings** | 15–20% per transaction | ₹1.2–1.8 Cr |
| **Premium Salon Listings** | ₹2,000–10,000/month featured placement | ₹0.3–0.5 Cr |
| **Premium Customer Membership** | ₹500–1,500/month (priority booking, exclusive access) | ₹0.1–0.2 Cr |
| **AI Beauty Assistant Subscription** | ₹99–299/month (advanced personalization) | ₹0.05–0.1 Cr |

### **Unit Economics (Year 1)**

| KPI | Value | Logic |
|-----|-------|-------|
| Avg Booking Value | ₹4,000–6,000 | Mix: haircut (₹800–1,500), color (₹3K–6K), bridal (₹20K–1L) |
| Commission/Booking | ₹600–1,000 | 15% take-rate |
| CAC (Customer) | ₹120–180 | Content + referral-led, lower than paid-ads-heavy categories |
| CLV (12-month, ~6 bookings/year) | ₹4,000–6,000 | Conservative repeat rate |
| **LTV:CAC Ratio** | **6–10x** | Acceptable for beauty marketplace (target: 6x+) |
| CAC Payback Period | 4–5 months | Time to recover customer acquisition cost |

### **Path to Profitability**

| Year | GMV (₹ Cr) | Revenue (₹ Cr) | Op Costs (₹ Cr) | EBITDA % | Status |
|------|-----------|----------------|-----------------|----------|--------|
| **Year 1** | 8–12 | 1.2–1.8 | 3.5–4.5 | **-65%** | Growth/Investment Phase |
| **Year 2** | 40–60 | 6–9 | 8–10 | **-15%** | Scaling Phase |
| **Year 3** | 120–180 | 18–27 | 15–18 | **+8–15%** | Unit Economics Positive |
| **Year 5** | 400–600 | 60–90 | 45–60 | **+25–30%** | Profitability & Scale |

---

Link : https://rose-sparkle-find.lovable.app

## **Technical Architecture**

### **Tech Stack**

```yaml
Frontend:
  - React 18 + TypeScript
  - Tailwind CSS (rose-gold color system)
  - GSAP 3.12 + ScrollTrigger (scroll animations)
  - Framer Motion 10+ (interactive components)
  - Lucide React (icons)
  - Embla Carousel (salon photo galleries)

Backend:
  - Node.js + Express (or Next.js API routes)
  - PostgreSQL (salons, bookings, users, reviews)
  - pgvector (for AI embedding-based matching)

AI/LLM:
  - Claude API (natural-language search, review summarization)
  - Vector embeddings (stylist profile matching)

Frontend:
  - React 18 + TypeScript
  - Tailwind CSS (rose-gold color system)
  - GSAP 3.12 + ScrollTrigger (scroll animations)
  - Framer Motion 10+ (interactive components)
  - Lucide React (icons)
  - Embla Carousel (salon photo galleries)

Backend:
  - Node.js + Express (or Next.js API routes)
  - PostgreSQL (salons, bookings, users, reviews)
  - pgvector (for AI embedding-based matching)


