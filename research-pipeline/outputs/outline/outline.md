# Paper Title (working): "Who Pays for the Subscription? Restaurant Beverage Subscriptions, Server Tip Income, and Job Satisfaction"

---

## 1. Introduction

**Hook / opening phenomenon**:
In April 2022, Panera Bread launched the Unlimited Sip Club — $10.99/month for unlimited self-serve beverages — and within a year, Sip Club members accounted for 25% of all transactions. Restaurant subscription models are expanding rapidly, yet they are designed entirely around consumer and firm outcomes. A conspicuously absent stakeholder is the restaurant employee.

**Research gap this paper addresses**:
The literature documents that subscription programs causally increase customer purchase frequency (Iyengar, Park & Yu 2022), and that this increase is driven largely by non-economic mechanisms — sunk cost commitment and behavioral loyalty (Zhang et al. 2024; Kim 2007). However, no study has examined what this frequency increase means for the servers who interact with these customers. Specifically: do subscription customers tip differently? Do servers serving more subscription customers earn less in tips? Does this change their job satisfaction?

**Research question**:
Does adoption of a restaurant subscription program reduce server tip income and job satisfaction, and does this effect vary by the server's dependence on tip income?

**Contributions** (3 bullets):
- First empirical study to examine the employee welfare consequences of restaurant subscription pricing, linking the subscription/behavioral economics literature to the organizational behavior/hospitality management literature
- Identifies a structural conflict between consumer value maximization and employee income under subscription models, with implications for restaurant pricing strategy and labor policy
- Provides actionable evidence for restaurant managers on how subscription program design moderates employee outcomes

**Paper structure roadmap**:
Section 2 reviews the literatures on subscription programs, sunk cost effects, tipping, and emotional labor in restaurants. Section 3 develops hypotheses. Section 4 describes methods. Section 5 presents results. Section 6 discusses theoretical and managerial implications.

---

## 2. Literature Review

### 2.1 Restaurant Subscription Programs and Consumer Behavior
- How subscriptions change consumer visit frequency: sunk cost effect and commitment mechanisms (Iyengar et al. 2022; Zhang et al. 2024; Kim 2007; Dick 1998)
- Heterogeneity: not all consumers respond equally; high-frequency vs. low-frequency baseline visitors (Gardete et al. 2025; Flat-Rate Paradox 2011)
- Consumer value framing in access-based models: usage frequency as the key metric of value realization (ACR reviews)
- Industry evidence: Panera Sip Club transaction data (industry sources)

### 2.2 Tipping in Restaurants: Income, Incentives, and Equity
- Tipping as the primary income source for servers: structural dependency (UNLV dissertation; tipping statistics)
- Weak relationship between service quality and tips (Tipping & Service Quality; Service Discrimination 2012)
- Server service discrimination based on perceived tipping likelihood (IJHM 2012)
- No-tipping policy research: income effects and employee satisfaction (NBER WP; To Tip or Not to Tip 2023)
- How pricing model changes (e.g., service-inclusive pricing) affect tipping norms (To Tip or Not to Tip 2023)
- Gap: subscription pricing has not been examined as a modifier of tipping behavior

### 2.3 Employee Wellbeing in High-Contact Service Environments
- Emotional labor in restaurants: surface acting, deep acting, and wellbeing consequences (Hochschild 1983; Emotional Labor Hospitality 2013)
- JD-R framework: customer contact as the top job demand predictor of burnout (JD-R 2018)
- Counterpoint: repeated positive interactions with regulars can generate emotional energy (Cayla & Auriacombe 2025)
- Theoretical framework for this paper: subscription-induced frequency increase as a combined job demand (volume) and relationship quality (regularity) change

**Theoretical framework diagram** [to be developed]:
Subscription adoption → ↑ subscriber visit frequency → (a) tip income channel: changed tipping norms / reduced gratuity per visit → server tip income → job satisfaction; (b) workload channel: increased customer volume → emotional labor demands → job satisfaction; moderated by server tip-income dependence and server-subscriber relationship quality.

---

## 3. Hypotheses

**H1** (Tip Income Effect): Servers at restaurants with an active subscription program report lower tip income (as % of total income) than servers at comparable restaurants without a subscription program, controlling for restaurant characteristics and server tenure.
*Justification*: Subscription customers have already paid upfront; psychological "payment completion" reduces the salience of tipping. Furthermore, subscription beverages (a common subscription component) are often self-serve, reducing the server interaction that triggers gratuity.

**H2** (Moderation by Tip-Income Dependence): The negative effect of subscription program adoption on job satisfaction is stronger for servers who are more financially dependent on tip income (i.e., those working longer hours, lower base wage contexts).
*Justification*: Dick (1998) and Kim (2007) show that financial consequences of membership change consumer psychology; analogously, server financial exposure to tip income determines how much the tip reduction matters for wellbeing.

**H3** (Workload Effect): Servers at subscription restaurants report higher perceived workload and customer interaction volume, which partially mediates the negative effect of subscription program adoption on job satisfaction.
*Justification*: Subscription programs increase visit frequency (Iyengar et al. 2022). Higher frequency means more table turns, more interactions, and greater emotional labor demands per shift (JD-R 2018).

**H4** (Relationship Quality Moderator): The negative workload effect (H3) is attenuated when servers report high relationship quality with their subscription customers (i.e., they recognize and enjoy regular customers).
*Justification*: Cayla & Auriacombe (2025) show that positive regular-customer relationships generate emotional energy. Subscription-induced regularity may convert a workload burden into an energizing relationship, depending on relationship depth.

---

## 4. Method

**Research design**: Two-study design.

*Study 1 — Cross-sectional survey (pilot, establishes baseline):*
- Sample: 300 restaurant servers recruited via Prolific, Reddit restaurant worker communities, and food service worker Facebook groups. Screen for: currently employed as server, has worked at a restaurant with a subscription program (Panera, etc.) OR has never worked at one.
- Key measures:
  - Restaurant subscription adoption (dichotomous: works at subscription restaurant vs. not)
  - Estimated tip income as % of total income (self-reported)
  - Perceived workload (adapted Job Demands scale from JD-R literature)
  - Job satisfaction (Minnesota Satisfaction Questionnaire – short form)
  - Relationship quality with regular customers (adapted scale)
  - Server tenure, hours/week, restaurant type (full-service vs. QSR)
- Analysis: OLS regression with robust SEs; moderation via interaction terms; PROCESS macro for moderated mediation (H3 and H4)

*Study 2 — Natural experiment (ideal; conditional on data access):*
- Design: Difference-in-differences exploiting the staggered rollout of a restaurant chain's subscription program across locations
- Data: Server payroll records + tip income data before and after subscription launch at treatment locations; control locations = same chain, no subscription
- Analysis: Two-way fixed effects DiD; staggered adoption via Callaway & Sant'Anna (2021) estimator to account for heterogeneous timing

**Analytical approach**: Moderated mediation (Study 1); DiD with staggered rollout (Study 2)

---

## 5. Expected Results / Contributions

**Expected results**:
- Servers at subscription restaurants will report lower tip income as % of earnings (H1 supported)
- Effect on job satisfaction stronger for high tip-dependence servers (H2 supported)
- Workload partially mediates the subscription-satisfaction relationship (H3 supported)
- Relationship quality with regulars buffers the workload effect, particularly for experienced servers who recognize subscription members (H4 supported)

**Theoretical contributions**:
- Integrates the subscription pricing literature (economics/marketing) with the service worker wellbeing literature (OB/hospitality) — a siloed connection that has not been made
- Extends the "two-sided market" logic to include employee stakeholders: shows that subscription pricing creates value for consumers by partly transferring costs to employees (in the form of lost tip income and increased workload)
- Provides new moderators (tip-income dependence, relationship quality) that predict when subscription programs are most damaging to employee welfare

**Practical implications**:
- Restaurant operators: design subscription programs that preserve the tipping norm (e.g., prompt digital tip on subscription orders; include server acknowledgment in subscription marketing)
- Policymakers: if subscriptions structurally reduce tip income, this strengthens the case for eliminating the tip credit and moving to a higher base wage
- HR professionals: servers at subscription restaurants may need retention incentives beyond tips (guaranteed income floor, recognition programs)

---

## 6. Conclusion

**Summary**: This paper is the first to examine restaurant subscriptions from the server's perspective. We show that the consumer benefits of subscription programs — increased visits, higher perceived value — come with a cost borne by employees in the form of reduced tip income and increased workload. These effects are moderated by financial dependence on tips and the quality of server–subscriber relationships.

**Limitations**:
- Cross-sectional survey data (Study 1) cannot establish causality; recall bias in tip income reporting
- Study 2 feasibility depends on corporate data partnership
- Focus on servers only; back-of-house workers face volume increases without any tip mechanism at all (future research)
- US context; tipping norms are culture-specific

**Future research**:
- Examine back-of-house worker outcomes under subscription-induced volume increases
- Test whether subscription program design features (tip prompts, server recognition) attenuate negative employee effects
- Cross-cultural comparison in markets without tipping norms (subscription impact on base wages and job satisfaction in Europe)
- Longitudinal study of server retention at subscription vs. non-subscription chains

