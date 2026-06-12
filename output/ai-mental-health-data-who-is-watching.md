# Mental Health App Privacy: What Your Therapy App Collects, Who Sees It, and How to Protect Yourself

---
This isn't an argument against mental health apps. 
Millions of people genuinely need them. It's an argument 
for knowing exactly what happens to your data when you 
open one at 2am and type something you've never told anyone.

Imagine it's midnight. You can't sleep, so you open your favorite wellness app and start journaling, anxious thoughts about work, a relationship falling apart, maybe something darker you've never said out loud to anyone. The screen glows softly. It feels private. It feels safe.

It probably isn't. That journal entry may have been parsed by an algorithm, stored indefinitely, and shared with companies whose names you've never heard. Mental health app privacy isn't a niche concern for tech insiders, it affects the tens of millions of Americans who turn to their phones for emotional support every day. The Mozilla Foundation's 2023 review found that 28 of 32 popular mental health and prayer apps failed its minimum privacy standards. Separate research found that more than 55% of mental health apps share user data with third parties. Source: https://foundation.mozilla.org/en/privacynotincluded/

These apps help people. They also collect some of the most sensitive data in existence. Knowing what happens to your information, who collects it, who sees it, and where it ends up, is the first step to protecting yourself. You don't have to stop using these tools to do it.

---


![Person typing into a mental health journaling app late at night with a worried expression](https://www.pnas.org/cms/10.1073/pnas.2505700122/asset/a933b642-da01-4006-b43a-7b1f0ebaaa53/assets/images/large/pnas.2505700122unfig01.jpg)
*Source: PNAS*


---

## The Data You Share — And the Data You Don't Know You're Sharing

### What you actively input — mood logs, journal entries, and session notes

The most obvious category is the data you intentionally provide. Mood logs, written journal entries, symptom check-ins, responses to mental health questionnaires, therapy session summaries, and crisis disclosures all fall here. Users tend to be remarkably candid in these apps, more so, research suggests, than they are with human providers, precisely because the interface feels private and non-judgmental. That openness is part of what makes these tools therapeutically useful.

It's also what makes the data so sensitive. Consider a composite scenario: a user shares details about a recent job loss, a history of childhood trauma, and fleeting thoughts of self-harm across several weeks of nightly journaling. They assume it's between them and the app. In most cases, it isn't, and there's no expiration date on that data unless they actively request deletion, a process many apps make intentionally cumbersome.

### What the app collects without asking — behavioral and device data

Beyond what you type, mental health apps gather a parallel stream of data you never consciously offered. Passive data collection typically includes device identifiers, IP addresses, GPS and location data, app usage frequency, session duration, notification interaction patterns, and granular behavioral signals like scrolling speed and tap timing. Even the *when* of your app use is informative, opening a mental health app at 3 a.m. four nights in a row tells a story without a single word being typed.

Many apps request permissions that go well beyond their stated function. Microphone access, camera permissions, and contact list access have been documented in health and wellness apps with no obvious clinical justification. Source: https://www.privacyinternational.org/ This is data you didn't sign up to share, collected not to serve you, but to build a more complete behavioral profile of you.

### Why mental health data is the most sensitive category in existence

Behavioral health data occupies its own category when it comes to sensitivity. Unlike your shopping history or your commute patterns, mental health data can reveal diagnoses, trauma histories, medication use, psychological vulnerabilities, and crisis episodes. That information can cause lasting harm when it surfaces in insurance underwriting decisions, employment background processes, or lending risk assessments.

Emerging state privacy laws are beginning to recognize this. California's CPRA (California Privacy Rights Act) explicitly calls out sensitive personal data, including mental health information, for heightened protections. Source: https://cppa.ca.gov/ Washington's My Health MY Data Act goes further, restricting how health data can be collected and shared without meaningful consent. Many apps still operate in the gaps between these laws, using technical and contractual maneuvers to sidestep protections that haven't fully caught up with the technology.

---


![Infographic showing types of data collected by mental health apps including location, mood logs, and device activity](https://market.us/wp-content/uploads/2023/08/Mental-Health-Apps-Market.png)
*Source: Market.us*


---

## The HIPAA Gap — Why the Law Isn't Protecting You the Way You Think

### What HIPAA actually covers — and the critical distinction it misses

Most people assume that mental health data is automatically protected by HIPAA (the Health Insurance Portability and Accountability Act). This is one of the most consequential misconceptions in digital health. HIPAA applies specifically to "covered entities", licensed healthcare providers, hospitals, health insurance companies, and their contracted business associates. If a system is part of formal medical care delivery, HIPAA likely applies. If it isn't, it almost certainly doesn't.

The relationship between HIPAA and mental health apps is largely one of absence. If you see a licensed therapist through a hospital-affiliated practice, your records are HIPAA-protected. If you download a mood tracking app from the App Store on your own, it almost certainly operates outside HIPAA's reach, even if it feels every bit as therapeutic. The law was written in 1996, long before consumer wellness apps existed, and it hasn't meaningfully evolved to address them. Source: https://www.hhs.gov/hipaa/index.html

### The BetterHelp and Talkspace precedent — real cases, real consequences

The abstract risk became concrete in 2023 when the Federal Trade Commission took action against BetterHelp, one of the most widely used online therapy platforms in the United States. The FTC found that BetterHelp had shared users' sensitive mental health data, including information disclosed during intake and therapy, with Facebook and Snapchat for advertising targeting. The company paid a $7.8 million settlement. Source: https://www.ftc.gov/news-events/news/press-releases/2023/03/ftc-action-against-betterhelp

This case directly answers the question many users have searched: *is BetterHelp sharing your personal data?* The FTC's findings confirm it was, and that the company's reassuring language about confidentiality didn't match its actual practices. Talkspace has also faced scrutiny over its privacy policies, particularly around data sharing arrangements and the scope of information accessible to its corporate and enterprise clients. The pattern here isn't one bad actor. It's a structural incentive problem that runs through the industry.

### What state laws are doing (and not doing) to fill the gap

In the absence of comprehensive federal privacy legislation, which has repeatedly stalled in Congress, states are building their own frameworks. California's CPRA, Washington's My Health MY Data Act, and similar legislation in Virginia, Colorado, and Connecticut introduce concepts like data minimization, the right to deletion, and restrictions on selling sensitive health data. Source: https://leg.wa.gov/Senate/Committees/HASC/Documents/MyHealthMyDataAct.pdf

But the protection is uneven. Enforcement capacity varies dramatically by state, and most laws contain carve-outs for data that is "de-identified" or "aggregated", categories that are far more permeable than they sound. The vast majority of app users have no idea these protections exist or how to invoke them. Legal frameworks matter, but informed users have to fill gaps that law has not.

---


![Gavel and legal documents alongside a smartphone displaying a mental health app](https://cdn.prod.website-files.com/6a022bcc6655a299f880cd72/6a022bcc6655a299f880d8f8_693cfde0df12e5e3fea87ab8-1765607970074.jpg)
*Source: Censinet*


---

## Who Actually Sees Your Data — The Third-Party Web You Never Agreed To

### Advertisers and analytics trackers hiding inside your therapy app

When you open a mental health app, you're often not just interacting with that company. Embedded within many apps are third-party SDKs (software development kits) from companies like Meta, Google, AppsFlyer, and various ad networks, code packages that automatically harvest and transmit behavioral data to those third parties in real time. Research from the AppCensus project has documented the prevalence of these trackers across health and wellness apps. Source: https://appcensus.io/

The app is the storefront you chose to enter, but dozens of invisible cameras owned by companies you've never heard of are recording everything inside it. Mental health data sharing through these embedded trackers happens automatically, often before a user has read a single word of the privacy policy. The therapy app you trust may be a front door to an advertising ecosystem you never agreed to enter.

### Data brokers — the invisible middlemen who build profiles for sale

Even if an app never directly sells your data, that doesn't mean your information stays contained. Data brokers, companies whose entire business model involves aggregating, packaging, and reselling personal information, can acquire mental health-adjacent data through analytics partners, app publishers, and device-level tracking. Researchers and journalists have documented health-related data appearing in broker marketplaces available for purchase by insurers, employers, law enforcement agencies, and political campaigns. Source: https://themarkup.org/

The chain looks like this: app → analytics partner → data broker → unknown buyer. Every link in that chain is largely legal under current federal law. Your midnight journal entry may not stay on your phone, it may end up in a database somewhere, attached to your name or a persistent device identifier that functions as effectively as your name.

### AI inference — when the app knows more than you told it

AI inference describes how machine learning models analyze passive behavioral data, how often you open the app, at what times, how quickly you respond to prompts, whether your session length is shortening, and draw conclusions about your mental health state that you never explicitly disclosed. You don't have to write "I'm struggling" for an algorithm to identify that you are. Some apps have begun marketing these predictive capabilities to enterprise clients, offering employers and insurers insights into workforce mental health trends derived from behavioral pattern analysis.

AI mental health surveillance and behavioral health data privacy are no longer speculative concerns, they are active features of products being sold today. The practical implication: AI doesn't just store what you share. It generates new data about you from patterns, constructing psychological profiles from behavior as ordinary as when you check your phone.

---


![Abstract visualization of data flowing from a smartphone to multiple third-party entities including advertisers and analytics companies](https://miro.medium.com/v2/resize:fit:1200/1*zR3-cSpd8O3YMar8zFre3g.png)
*Source: Lena - Medium*


---

## The Employer Benefit Trap — When Your Wellness App Is Also a Surveillance Tool

### How employer-sponsored mental health apps actually work

Many employers now offer mental health platforms as part of their benefits package: Calm for Business, Lyra Health, Spring Health, BetterUp, and similar products. On the surface, this looks like a workplace benefit. Underneath, there's a structural conflict worth understanding. In employer-sponsored mental health benefits, the employer is the paying customer, not the employee, which means the platform's primary commercial relationship is with the company writing the checks.

That relationship comes with contractual obligations to the employer that may run parallel to, and sometimes counter to, the interests of the individual user. Most employees never think about this when they download the app their HR department recommended.

### What the contract may allow — aggregated data, usage analytics, and more

Whether employers can see your mental health app data doesn't have a simple yes-or-no answer. What's typically permitted under employer contracts is aggregated utilization data: how many employees used the platform in a given period, how frequently, and what categories of support they sought. On its face, that sounds benign, in practice, it carries real risk.

In a department of six people, "aggregated" data isn't truly anonymous. If three employees in a small team sought support for anxiety and two for relationship stress during a period of organizational restructuring, a manager with access to those reports may be able to make reasonable inferences about specific individuals. ROI reporting, which platforms provide to justify contract renewal, can reveal workforce mental health trends in ways that, intentionally or not, expose individual vulnerabilities.

### The illusion of confidentiality — what EAP and wellness platforms tell you vs. reality

Employee Assistance Programs and wellness platforms almost universally use the language of confidentiality in their user-facing marketing. "Your privacy is our priority." "What you share stays between you and your provider." These statements may be partially true, but what the app tells individual users and what its data processing agreement with the employer actually permits are sometimes meaningfully different documents.

Buried in terms of service are clauses permitting data sharing for "aggregate reporting," "program evaluation," "research purposes," or "service improvement", categories broad enough to encompass a great deal. The employees most in need of mental health support may be least likely to seek it if they have even a vague suspicion that their employer has visibility into their use. Before using any employer-sponsored mental health platform, ask HR directly: what data does the company receive, in what form, and who has access to it?

---


![Employee looking at a wellness app benefit on a work laptop with a cautious expression](https://kffhealthnews.org/wp-content/uploads/sites/8/2015/09/wellness-infographic-final_570.png?w=500)
*Source: KFF Health News*


---

## High-Risk vs. Lower-Risk — How Different App Types Compare

### Consumer wellness apps — maximum reach, minimum accountability

Apps like Headspace, Woebot, and Calm make up the largest and most accessible tier of the mental health app market, and the one with the fewest regulatory guardrails. Consumer wellness apps have no default HIPAA obligation, often depend on advertising revenue or data monetization partnerships, and are more likely than any other category to carry embedded third-party trackers. They reach tens of millions of users and offer real clinical and emotional value for many of them. They're also where the gap between perceived privacy and actual privacy is widest. Using them is a reasonable choice, but it should be an informed one.

### Telehealth and therapy platforms — better protection, but not bulletproof

Telehealth platforms like Talkspace, BetterHelp, and Cerebral occupy a more complicated middle ground. Some involve licensed therapist relationships that may trigger partial HIPAA coverage for the clinical components of the service. But they also operate consumer-facing features, run advertising campaigns, and in some documented cases have embedded ad trackers alongside their clinical infrastructure. When evaluating these platforms, look specifically for whether they explicitly claim HIPAA compliance, whether they name their third-party data partners, and whether their privacy policy has been independently audited. A privacy policy that's vague about data sharing is itself informative.

### Clinically integrated tools — the safest tier (with caveats)

Apps formally integrated into clinical healthcare systems, prescribed digital therapeutics, tools connected to an Electronic Health Record system, or platforms deployed within a licensed clinical practice, offer the strongest privacy protections. These tools are clearly bound by HIPAA, subject to clinical ethics frameworks, and operated by entities with meaningful accountability. They're also the least accessible, typically requiring a clinical referral. One caveat worth noting: even clinical records aren't impervious to data breaches, and in self-insured health plans, where the employer is also the insurer, your mental health claims may be more visible to your employer than you realize.

---


![Comparison chart showing three tiers of mental health apps from consumer wellness to clinical integration with privacy risk levels](https://www.mindbowser.com/wp-content/uploads/2025/04/Mental-Health-Apps-in-2026-Demand-vs-Risk@3x.webp)
*Source: Mindbowser*


---

## How to Protect Your Mental Health Data — Practical Steps That Actually Work

You don't have to choose between your mental health and your privacy. But you do have to be intentional. Here are concrete steps that put you back in control.

**Before you download:**
- Search the app name alongside "privacy policy" and "data sharing" before installing. Look for explicit statements about whether they sell or share data with third parties.
- Check the Mozilla Foundation's *Privacy Not Included* database for independent assessments of popular mental health apps. Source: https://foundation.mozilla.org/en/privacynotincluded/
- Review what permissions the app requests on installation. If a mood tracker wants microphone or contact access, ask why, and consider declining.

**When using employer-sponsored apps:**
- Ask your HR department directly: what utilization data does the company receive? Who has access to it? Is it truly anonymized, and at what aggregation level?
- Consider using a personal mental health app independently if you're uncertain about workplace platform privacy, and pay for it out of pocket if possible to avoid any employer data relationship.
- Remember that your EAP may have a separate, more clearly protected confidentiality structure than the wellness app being promoted alongside it.

**Inside the app:**
- Avoid disclosing your full name, employer, or identifying details in open-text journal fields when possible.
- Review and exercise your data deletion rights, which many state laws now require apps to honor. Submit a data deletion request if you stop using an app.
- Opt out of "research" or "data improvement" data uses if the option is available in settings, it often is, buried several menus deep.

**For higher-risk situations:**
- If you are disclosing anything you would not want an employer or insurer to know, consider whether a licensed therapist accessed through your personal health insurance, with full HIPAA protection, is a better venue than a consumer app.
- Use a VPN to mask your IP address and reduce the precision of location data transmitted to third-party trackers.
- Periodically audit your phone's app permissions and revoke any that seem disproportionate to the app's function.

---

## Frequently Asked Questions

**Are mental health apps covered by HIPAA?**
Most consumer mental health apps are not covered by HIPAA. HIPAA applies to licensed healthcare providers, hospitals, and insurers, not to standalone wellness apps you download independently. Unless an app is formally integrated into a clinical care system, your data is almost certainly not protected under federal health privacy law.

**Can my employer see my mental health app data?**
Not usually in the form of individual records, but potentially more than you'd expect. Employers who pay for wellness platforms typically receive aggregated utilization reports, how many employees used the service, how often, and for what categories of concern. In small teams, this data may not be truly anonymous. Always ask your HR department specifically what data the company receives before using an employer-sponsored mental health app.

**Is BetterHelp sharing your personal data?**
In 2023, the FTC found that BetterHelp had shared users' sensitive mental health data with Facebook and Snapchat for advertising purposes, resulting in a $7.8 million settlement. The company has since updated its practices under the terms of that settlement. Users should review BetterHelp's current privacy policy and FTC consent order for the most current information on its data practices. Source: https://www.ftc.gov/news-events/news/press-releases/2023/03/ftc-action-against-betterhelp

**What data do mental health apps actually collect?**
Beyond the mood logs and journal entries you knowingly share, most apps also collect device identifiers, IP addresses, location data, app usage patterns, notification interactions, and granular behavioral data like session timing and duration. Many also embed third-party tracking SDKs that transmit data to advertisers and analytics companies automatically.

**How can I use mental health apps more safely?**
Review privacy policies before downloading, check independent assessments from organizations like Mozilla Foundation, revoke unnecessary app permissions, exercise your data deletion rights, avoid sharing identifying details in open-text fields, and consider whether employer-sponsored platforms are the right choice given your specific privacy concerns. For the strongest protections, clinically integrated tools or HIPAA-covered therapist relationships are your best options.

**Does AI make mental health app privacy risks worse?**
Yes, meaningfully so. AI models can analyze passive behavioral patterns, when you open the app, how long you engage, whether your session frequency is changing, to infer mental health states you never explicitly shared. Even if you're careful about what you type, the behavioral data generated by your use of the app is itself being analyzed to build psychological profiles.

---

## Conclusion

Mental health apps have changed how millions of people access support. They've made help available at 2 a.m. when no one else is reachable, lowered the barrier for people who might never walk into a therapist's office, and provided daily structure for people managing anxiety, depression, and related conditions.

But the data these apps collect, your fears, your crises, your most private thoughts, is also some of the most sensitive information about you that exists. Most of it falls outside HIPAA's protection. Much of it flows to advertisers, analytics companies, and data brokers through channels most users never see. Employer-sponsored wellness platforms carry a conflict of interest that goes largely unexamined. And AI is turning behavioral patterns into psychological profiles without requiring a single disclosure from you.

None of this has to be a reason to stop seeking help. It is a reason to seek it with full knowledge of how these systems work.

Ask hard questions before you download. Read past the marketing language. Know what your employer's wellness platform actually promises, and what it doesn't. Your mental health data deserves the same scrutiny you'd give your financial accounts or your medical records, because that is exactly what it is.

**Take one step today: visit Mozilla Foundation's Privacy Not Included database (foundation.mozilla.org/privacynotincluded) and look up any mental health app you're currently using. What you find might surprise you, and it will definitely inform you.**
---

## Sources

1. https://www.pnas.org/cms/10.1073/pnas.2505700122/asset/a933b642-da01-4006-b43a-7b1f0ebaaa53/assets/images/large/pnas.2505700122unfig01.jpg
2. https://market.us/wp-content/uploads/2023/08/Mental-Health-Apps-Market.png
3. https://cdn.prod.website-files.com/6a022bcc6655a299f880cd72/6a022bcc6655a299f880d8f8_693cfde0df12e5e3fea87ab8-1765607970074.jpg
4. https://miro.medium.com/v2/resize:fit:1200/1*zR3-cSpd8O3YMar8zFre3g.png
5. https://kffhealthnews.org/wp-content/uploads/sites/8/2015/09/wellness-infographic-final_570.png?w=500
6. https://www.mindbowser.com/wp-content/uploads/2025/04/Mental-Health-Apps-in-2026-Demand-vs-Risk@3x.webp
7. https://foundation.mozilla.org/en/privacynotincluded/
8. https://www.privacyinternational.org/
9. https://cppa.ca.gov/
10. https://www.hhs.gov/hipaa/index.html
11. https://www.ftc.gov/news-events/news/press-releases/2023/03/ftc-action-against-betterhelp
12. https://leg.wa.gov/Senate/Committees/HASC/Documents/MyHealthMyDataAct.pdf
13. https://appcensus.io/
14. https://themarkup.org/

---

## Did you enjoy this post?

Here are some other AI Agents posts you might have missed:

- KV Caching and Speculative Decoding
- A deep dive into Quantization: Key to Open Source LLM Deployments
- Agents are here and they are staying
- How Agents Think
- Memory – The Agent's Brain
- Agentic RAG Ecosystem
- Multimodal Agents
- Scaling Agents: Architectures with Google ADK, A2A, and MCP
- Fully Functional Agent Loop

**Ready to take it to the next level?**
Check out my AI Agents for Enterprise course on Maven and be part of something bigger — join hundreds of builders developing enterprise-level agents.

Use this link to get **$201 OFF!**

---

*You're receiving this because you're part of our mailing list. We don't spam or sell your information. To unsubscribe, use the link below.*
