# SEO Audit Checklist

The exact checklist I run when auditing a client site. Work top to bottom; fix blockers first.

## 1. Crawling & indexing
- [ ] robots.txt exists and doesn't block important paths
- [ ] XML sitemap exists, submitted in Search Console, returns 200
- [ ] No important pages accidentally `noindex`ed
- [ ] Canonical tags present and self-referencing where appropriate
- [ ] Google Search Console + Bing Webmaster Tools verified, no manual actions
- [ ] Crawl budget sane: no infinite faceted URLs, calendars, or parameter traps

## 2. Technical
- [ ] HTTPS everywhere, no mixed content, valid certificate
- [ ] Single canonical domain (www vs non-www, trailing slash consistent)
- [ ] Core Web Vitals passing (LCP < 2.5s, INP < 200ms, CLS < 0.1) on mobile
- [ ] Mobile-friendly: no horizontal scroll, tap targets big enough
- [ ] Structured data valid (test with Rich Results Test), no spammy markup
- [ ] 404s handled with a useful custom page; broken internal links fixed
- [ ] Redirect chains flattened (max 1 hop), no redirect loops

## 3. On-page
- [ ] One H1 per page, hierarchy logical (H1 → H2 → H3)
- [ ] Title tags unique, ~60 chars, primary keyword near the front
- [ ] Meta descriptions unique, ~155 chars, written to earn the click
- [ ] URLs short, lowercase, hyphenated, keyword-relevant
- [ ] Images have descriptive alt text; filenames meaningful; compressed + next-gen format
- [ ] Internal links use descriptive anchor text; orphan pages eliminated

## 4. Content
- [ ] Every indexed page has a clear search intent and target keyword
- [ ] Thin/duplicate content consolidated or pruned
- [ ] E-E-A-T signals: author bios, about page, contact info, real reviews
- [ ] Content fresh: dates accurate, stats current, no dead advice

## 5. Local SEO (if applicable)
- [ ] Google Business Profile claimed, categories + hours + photos complete
- [ ] NAP (name/address/phone) identical everywhere it appears
- [ ] LocalBusiness schema on the site
- [ ] Location pages unique (no doorway pages)

## 6. Off-page
- [ ] Backlink profile reviewed: toxic links disavowed, anchor text natural
- [ ] Brand mentions tracked; unlinked mentions converted to links
- [ ] Competitor gap analysis: links they have that you don't

## 7. Reporting
- [ ] Baseline recorded: rankings, traffic, conversions before changes
- [ ] Annotations in analytics for every fix shipped
- [ ] Re-crawl after major fixes; verify in Search Console

---
Built by Tyra Redot — WordPress developer, SEO & AIO specialist. 📧 ideven95@gmail.com
