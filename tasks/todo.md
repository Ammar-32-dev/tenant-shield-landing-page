# Tasks: Niche E-Book Market Research (India)

This plan outlines the steps to perform a deep-dive market research and demand validation for five high-potential, underserved e-book niches in India.

## Phase 1: Research & Discovery
- [x] Run targeted web searches and spawn the browser subagent to query social media (Reddit, Twitter/X, Quora, LinkedIn) to validate demand for the 5 niches:
  1. IT Service-to-Product Company Transition (focus on r/developersIndia, salaries, and system design gap).
  2. Health Insurance Claim Navigation in India (focus on IRDAI complaints, TPA rejections, Twitter complaints).
  3. PCOD/PCOS Management Through Indian Diet & Lifestyle (focus on Indian cuisine adaptation, local courses).
  4. Urban Tenant Rights & Security Deposit Recovery in India (focus on rental disputes in Bengaluru, Pune, Gurgaon, and legal recourse).
  5. LinkedIn Personal Branding for Indian White-Collar Professionals (focus on corporate visibility and monetization).
- [x] Use the browser subagent to search Amazon KDP India, Gumroad, and Topmate to gauge competition and price points.
- [x] Refine the niches or pivot to even higher-signal ones if evidence suggests.

## Phase 2: Detailed Market & Competitive Analysis
- [x] Assess the competition level on Amazon KDP India, Kindle, Gumroad, and Topmate for each niche.
- [x] Formulate the specific "Indian Context" value proposition for each niche.
- [x] Define the target customer profile (demographics, income, willingness to pay ₹299–₹999).

## Phase 3: Compilation and Artifact Generation
- [x] Structure a premium, comprehensive market research report as an artifact (`research_report.md` in the workspace).
- [x] Outline a demand validation strategy for the top-performing niche (e.g., landing page structure, pre-sell copy).
- [x] Review all content using standard professional guidelines (avoiding AI clichés, ensuring natural tone).

## Phase 4: Review and Finalize
- [x] Complete the review section in `todo.md` with final outcomes.

## Phase 5: Smoke Test Landing Page Blueprint
- [x] Create `landing_page_blueprint.md` outlining the structural layout, section copy blocks, and conversion hooks for the tenant rights guide.

## Phase 6: Build Responsive Landing Page
- [x] Create `index.html` with premium styling (Deep Obsidian background, Brutalist/Modern typography, responsive layout, and interactive elements).

## Review Section

### Summary of Accomplished Work
- **Niche Identification & Validation**: Validated the 5 target e-book niches for the Indian market via a 5-Stage Dual-AI workflow:
  1. *Reasoning/Thinking (OpenRouter DeepSeek)*: Crafted exact target queries and competitive intelligence checklist.
  2. *Execution/Writing (Cerebras Qwen)*: Generated a comprehensive, premium market research report in `C:\Users\Asho\.gemini\antigravity-ide\scratch\ebook_market_research_india\research_report.md`.
  3. *Review (Native Gemini)*: Checked for brand guidelines, verified the demand data, and ran targeted web searches to confirm tenant dispute frequency (e.g., in Bangalore).
- **Top Niche Recommendation**: Identified **Urban Tenant Rights & Security Deposit Recovery** as the highest potential niche due to high urgency (immediate loss of ₹50,000–₹2,00,000 deposits), strong willingness to pay (₹499–₹799 price point), and very low existing competition.
- **Verification of Guidelines**: Ensured the writing strictly adheres to the tone guidelines in `brand_identity.json` and excludes all 18 forbidden AI clichés.
- **Mobile Friendliness Overhaul**: Reconfigured CSS properties on smaller screens to disable strict scroll snapping (`scroll-snap-type: none`) and prevent content clipping (`overflow: visible` on `.scene`), enabling smooth, responsive touch scrolling on mobile.
- **Interactivity & Free Playbook Access**: Wired up CTA buttons to open a custom, dark-glassmorphism checkout drawer. Transformed the pricing layout across the site from ₹499 to **FREE** (slashing ₹499 as the original price).
- **Vercel & GitHub Deployments**: Deployed the finalized static site to Vercel at `https://ebookmarketresearchindia.vercel.app` and successfully synced all changes to the public GitHub repo `tenant-shield-landing-page` under `Ammar-32-dev`.


## Phase 7: Mobile Friendliness & Interactive CTA Overhaul
- [x] Fix mobile clipping: Remove `overflow: hidden` on `.scene` elements so content doesn't get clipped on smaller screens.
- [x] Adjust mobile layout & spacing: Ensure headers, cards, and grid elements scale down nicely on devices under 480px.
- [x] Turn off/relax scroll snapping on mobile: Disable or adjust scroll snapping on devices with small heights/widths to avoid jarring scrolling behavior.
- [x] Implement checkout flow: Add a modern, dark-glassmorphism checkout modal/drawer triggered by the CTA buttons.
- [x] Create mock payment & download: Add a simulated Razorpay step in the modal leading to a successful mock PDF download.
