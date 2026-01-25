# Curriculum GTM Engineer - Formation Portfolio Companies

> Sessions de 2h/mois pour les entreprises accompagnees par des fonds

---

## Vue d'ensemble

| Niveau | Focus | Sessions | Public |
|--------|-------|----------|--------|
| **Niveau 1** | Fondations GTM | 4 sessions | Debutants, premiers setups |
| **Niveau 2** | Automatisation & IA | 4 sessions | Equipes avec bases solides |
| **Niveau 3** | Infrastructure Engineering | 4 sessions | Tech-savvy, scale |

**Format:** 2h live + demo + Q&A + ressources
**Livrable:** Templates, scripts, replays 30j, support Slack

---

## NIVEAU 1: Fondations GTM

### Session 1.1 - Setup Clay + Enrichissement Data
**Duree:** 2h | **Outils:** Clay, Apollo

**Objectif:** Configurer Clay de zero et maitriser l'enrichissement automatique sans payer tous les leads.

**Contenu:**
1. **Setup initial Clay** (30min)
   - Creation compte et workspace
   - Comprendre les credits et la facturation
   - Import de liste initiale

2. **Waterfall Enrichment** (45min)
   - Principe du waterfall (Apollo > Clearbit > Dropcontact)
   - Configuration des colonnes
   - Gestion des fallbacks

3. **Hack X-Ray Google** (30min)
   - Operateurs de recherche Google pour LinkedIn
   - `site:linkedin.com/in "CTO" "Paris" "SaaS"`
   - Scraper les resultats dans Clay sans payer Sales Navigator
   - Templates de recherches par persona

4. **Hands-on** (15min)
   - Chaque participant enrichit 50 leads live
   - Debug des erreurs communes

**Ressources fournies:**
- Template Clay "Waterfall B2B France"
- Cheatsheet operateurs X-Ray
- Liste de 20 recherches X-Ray par vertical

---

### Session 1.2 - Outreach Stack: HeyReach + Smartlead
**Duree:** 2h | **Outils:** HeyReach, Smartlead, Instantly

**Objectif:** Mettre en place l'infrastructure d'outreach LinkedIn + Email avec warmup.

**Contenu:**
1. **Architecture Outreach** (20min)
   - LinkedIn vs Email: quand utiliser quoi
   - Multicanal synchronise vs separe
   - Calculer sa capacite d'envoi

2. **Setup HeyReach** (40min)
   - Connection comptes LinkedIn (via cookies)
   - Configuration limites journalieres
   - Creation premiere campagne
   - Gestion des blacklists

3. **Setup Smartlead** (40min)
   - Warmup strategy (30j avant envoi)
   - Configuration domaines et mailboxes
   - Rotation intelligente
   - Tracking et custom domain

4. **Synchronisation** (20min)
   - Eviter les doublons cross-canal
   - Sequence LinkedIn -> Email fallback
   - Webhooks vers CRM

**Ressources fournies:**
- Checklist "Pre-launch outreach"
- Calculator capacite d'envoi
- Template sequences 5 touchpoints

---

### Session 1.3 - CRM & Pipeline: HubSpot Ops
**Duree:** 2h | **Outils:** HubSpot, Clay

**Objectif:** Structurer HubSpot pour supporter le GTM avec sync bidirectionnel.

**Contenu:**
1. **Architecture CRM pour GTM** (30min)
   - Proprietes custom essentielles (ICP score, source, intent signals)
   - Lifecycle stages adaptes a l'outbound
   - Deal stages pour outbound vs inbound

2. **Lead Scoring** (30min)
   - Scoring demographique (taille, secteur, titre)
   - Scoring comportemental (email opens, replies, page views)
   - Seuils et actions automatiques

3. **Sync Clay <> HubSpot** (40min)
   - Webhook Clay -> HubSpot
   - Enrichissement depuis HubSpot vers Clay
   - Gestion des duplicates

4. **Workflows automatises** (20min)
   - Lead routing par score
   - Alerts Slack sur leads chauds
   - Sequences internes de suivi

**Ressources fournies:**
- Template proprietes HubSpot GTM
- Blueprint scoring
- Workflow templates JSON

---

### Session 1.4 - Copywriting Outbound: Templates qui convertissent
**Duree:** 2h | **Outils:** Templates, Clay variables

**Objectif:** Ecrire des sequences qui generent des reponses avec personnalisation at scale.

**Contenu:**
1. **Frameworks qui marchent** (30min)
   - AIDA adapte au cold
   - Problem-Agitate-Solution
   - Le hack du P.S.
   - Pourquoi les longs emails echouent

2. **Cold Email Structure** (30min)
   - Subject lines (data-driven)
   - First line personnalisee
   - Value prop en 1 phrase
   - CTA non-pushy

3. **LinkedIn DM** (30min)
   - Connection request (300 caracteres)
   - Follow-up sequences
   - Voice notes scripts

4. **Variables Clay** (30min)
   - `{{company_news}}` `{{recent_post}}` `{{tech_stack}}`
   - AI personalization avec Claude dans Clay
   - A/B testing systematique

**Ressources fournies:**
- 10 templates cold email par industrie
- 5 sequences LinkedIn completes
- Prompt Claude pour personnalisation

---

## NIVEAU 2: Automatisation & IA

### Session 2.1 - Enregistrer tous vos calls avec transcription IA
**Duree:** 2h | **Outils:** Meetily, Groq Whisper, Gemini

**Objectif:** Capturer, transcrire et exploiter automatiquement tous vos calls.

**Contenu:**
1. **Pourquoi tout enregistrer** (15min)
   - Knowledge management
   - Training nouveaux SDRs
   - Objection handling database
   - Compliance et legal

2. **Setup Meetily/MeetingRecorder** (45min)
   - Installation BlackHole (audio virtuel macOS)
   - Configuration Meetily
   - Stockage local vs cloud
   - Transcription temps reel avec Groq Whisper

3. **Alternative cloud: Otter/Fireflies** (20min)
   - Comparatif solutions
   - Integration calendrier
   - Partage et highlights

4. **Exploitation des transcripts** (40min)
   - Structure de stockage (par compte, par date)
   - Extraction automatique: objections, next steps, competitors mentioned
   - Feed vers CRM

**Ressources fournies:**
- Script Python MeetingRecorder
- Template organisation transcripts
- Prompts extraction insights

---

### Session 2.2 - Claude Code comme copilote GTM
**Duree:** 2h | **Outils:** Claude Code, Terminal, fichiers locaux

**Objectif:** Avoir un assistant IA qui connait votre contexte et peut vous aider en temps reel.

**Contenu:**
1. **Qu'est-ce que Claude Code** (20min)
   - Difference avec ChatGPT/Claude web
   - Acces au filesystem
   - Execution de code
   - Memory et contexte persistant

2. **Setup workspace GTM** (40min)
   - Structure de dossiers recommandee
   - `/transcripts` `/accounts` `/templates` `/playbooks`
   - Fichier `CLAUDE.md` pour contexte permanent
   - Sync automatique des nouveaux fichiers

3. **Use cases GTM** (40min)
   - "Resume-moi le call avec [Account] d'hier"
   - "Ecris un follow-up base sur ce transcript"
   - "Quelles objections sont revenues cette semaine?"
   - "Update le CRM avec ces notes"

4. **Workflows avances** (20min)
   - Pre-call research automatise
   - Post-call summary generation
   - Competitive intelligence extraction

**Ressources fournies:**
- Template dossier GTM pour Claude Code
- CLAUDE.md example
- 10 prompts GTM essentiels

---

### Session 2.3 - Intent Data & Signal-Based Outreach
**Duree:** 2h | **Outils:** Clay, Webhooks, Alertes

**Objectif:** Detecter les signaux d'achat et trigger des sequences automatiquement.

**Contenu:**
1. **Types de signaux** (30min)
   - Funding events (Crunchbase, Dealroom)
   - Job postings (signal de growth)
   - Technographic changes (BuiltWith)
   - Content engagement (liked your post)
   - Website visits (Clearbit Reveal)

2. **Setup Clay pour intent** (40min)
   - Tables de monitoring
   - Scheduled runs
   - Filters et conditions
   - Scoring des signaux

3. **Triggers automatiques** (30min)
   - Signal -> Sequence immediate
   - Signal -> Notification SDR
   - Signal -> Enrichissement supplementaire
   - Multi-signal scoring

4. **Real-time alerts** (20min)
   - Slack notifications
   - Email digests
   - Dashboard monitoring

**Ressources fournies:**
- Clay templates "Intent Monitoring"
- Scoring matrix par signal
- Workflows notification

---

### Session 2.4 - Voice AI: Messages vocaux personnalises
**Duree:** 2h | **Outils:** ElevenLabs, HeyReach, WhatsApp API

**Objectif:** Envoyer des vocaux personnalises a scale pour 10x les reply rates.

**Contenu:**
1. **Pourquoi la voix** (15min)
   - Stats: vocal vs texte
   - Quand utiliser (1st touch vs follow-up)
   - Legal et GDPR

2. **Voice cloning avec ElevenLabs** (40min)
   - Enregistrer des samples
   - Entrainer son clone
   - API pour generation batch
   - Pricing et optimisation

3. **Integration LinkedIn** (30min)
   - HeyReach + vocaux
   - Upload et envoi automatise
   - Scripts par scenario
   - Personalization tokens

4. **WhatsApp automation** (35min)
   - Business API vs hacks
   - Envoi sans sauvegarder contact
   - Vocaux WhatsApp
   - Compliance et opt-out

**Ressources fournies:**
- Script Python ElevenLabs batch
- Templates vocaux par scenario
- Guide WhatsApp Business API

---

## NIVEAU 3: Infrastructure GTM Engineering

### Session 3.1 - Orchestration avec n8n/Make
**Duree:** 2h | **Outils:** n8n, Make, APIs

**Objectif:** Creer des workflows complexes qui connectent tous vos outils GTM.

**Contenu:**
1. **n8n vs Make vs Zapier** (20min)
   - Comparatif features/pricing
   - Self-hosted vs cloud
   - Use cases par outil

2. **Setup n8n self-hosted** (30min)
   - Docker deployment
   - Configuration SSL
   - Backup et maintenance

3. **Workflows GTM complexes** (50min)
   - New lead -> Enrich -> Score -> Route -> Sequence
   - Reply received -> Classify -> Update CRM -> Alert
   - Meeting booked -> Create deal -> Prep doc -> Notify
   - Error handling et retries

4. **Patterns avances** (20min)
   - Sub-workflows
   - Conditional branching
   - Rate limiting et queues
   - Monitoring et alerting

**Ressources fournies:**
- docker-compose.yml n8n
- 5 workflows JSON importables
- Monitoring setup

---

### Session 3.2 - Scraping Custom avec Python & APIs
**Duree:** 2h | **Outils:** Python, Requests, BeautifulSoup, Proxies

**Objectif:** Aller au-dela du no-code pour scraper ce que les outils ne permettent pas.

**Contenu:**
1. **Quand coder vs no-code** (15min)
   - Cost analysis
   - Customization needs
   - Maintenance burden

2. **Stack technique** (30min)
   - Python requests + BeautifulSoup
   - Playwright pour JS rendering
   - Proxy rotation (Bright Data, Smartproxy)
   - Headers et fingerprinting

3. **Cas pratiques** (50min)
   - Scraper LinkedIn sans API
   - Job boards custom
   - Annuaires professionnels
   - Google Maps / Places

4. **Data pipeline** (25min)
   - Cleaning et normalisation
   - Deduplication
   - Export vers Clay/CRM
   - Scheduling avec cron

**Ressources fournies:**
- Boilerplate scraper Python
- Proxy setup guide
- 3 scrapers prets a l'emploi

---

### Session 3.3 - AI Agents pour GTM
**Duree:** 2h | **Outils:** Claude API, LangChain, Function calling

**Objectif:** Construire des agents autonomes qui qualifient, enrichissent et engagent.

**Contenu:**
1. **Qu'est-ce qu'un agent IA** (20min)
   - LLM + Tools + Loop
   - Difference avec un simple prompt
   - Use cases GTM

2. **Claude API fundamentals** (30min)
   - Authentication et pricing
   - Messages API
   - System prompts pour GTM
   - Token management

3. **Function calling** (40min)
   - Definir des tools
   - CRM lookup, enrichissement, email send
   - Orchestration multi-tools
   - Error handling

4. **Agent GTM complet** (30min)
   - Agent de qualification
   - Agent de recherche pre-call
   - Agent de follow-up writing
   - Deployment et monitoring

**Ressources fournies:**
- Agent qualification Python
- Templates tools JSON
- Prompts systeme GTM

---

### Session 3.4 - Analytics & Attribution GTM
**Duree:** 2h | **Outils:** Metabase, SQL, UTMs

**Objectif:** Mesurer ce qui marche vraiment avec tracking et dashboards custom.

**Contenu:**
1. **Metrics qui comptent** (25min)
   - Funnel outbound: Sent -> Reply -> Meeting -> Opportunity -> Closed
   - Cohort analysis par campagne
   - CAC par canal
   - Time to close

2. **UTM Strategy** (25min)
   - Nomenclature standardisee
   - Tracking links dans sequences
   - Attribution first vs last touch

3. **Setup Metabase** (40min)
   - Connection bases (HubSpot, Postgres)
   - Queries SQL essentielles
   - Dashboards temps reel
   - Alerts sur KPIs

4. **Attribution multi-touch** (30min)
   - Modeles d'attribution
   - Ponderation par touchpoint
   - Reporting pour leadership

**Ressources fournies:**
- SQL queries GTM
- Dashboard Metabase JSON
- Template reporting mensuel

---

## Calendrier suggere

| Mois | Session | Niveau |
|------|---------|--------|
| 1 | Setup Clay + Enrichissement | 1.1 |
| 2 | Outreach Stack | 1.2 |
| 3 | CRM & Pipeline | 1.3 |
| 4 | Copywriting Outbound | 1.4 |
| 5 | Recording & Transcription | 2.1 |
| 6 | Claude Code Copilote | 2.2 |
| 7 | Intent Data & Signals | 2.3 |
| 8 | Voice AI | 2.4 |
| 9 | n8n Orchestration | 3.1 |
| 10 | Python Scraping | 3.2 |
| 11 | AI Agents | 3.3 |
| 12 | Analytics & Attribution | 3.4 |

---

## Contact

**Aura** - Formation GTM pour Portfolio Companies
hello@aura.camp
