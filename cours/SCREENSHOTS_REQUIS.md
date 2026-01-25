# Screenshots Requis pour les Cours GTM

> Liste complete des screenshots a prendre pour illustrer les tutoriels

---

## SESSION 1.1 - Clay + X-Ray Google

**Total: 24 screenshots**

### Partie 1: Setup initial Clay

| # | Nom fichier | Description | Comment le prendre |
|---|-------------|-------------|-------------------|
| 01 | `01_clay_homepage.png` | Page d'accueil Clay avec bouton "Get Started Free" | Aller sur clay.com en mode deconnecte |
| 02 | `02_clay_create_workspace.png` | Ecran de creation du workspace (nom + options) | Pendant le onboarding ou Settings > Workspace |
| 03 | `03_clay_main_interface.png` | Vue principale Clay vide - spreadsheet + sidebar | Apres login, nouvelle table vide |
| 04 | `04_clay_new_table_modal.png` | Modal "New Table" avec options (From scratch, Import CSV, etc.) | Cliquer sur "New Table" |
| 05 | `05_clay_import_csv_mapping.png` | Interface d'import CSV avec mapping des colonnes | Importer un CSV de test |
| 06 | `06_clay_table_with_data.png` | Table Clay avec 5-10 lignes de donnees importees | Apres import reussi |
| 07 | `07_clay_settings_billing.png` | Page Settings > Billing montrant les credits | Settings > Billing |

### Partie 2: Waterfall Enrichment

| # | Nom fichier | Description | Comment le prendre |
|---|-------------|-------------|-------------------|
| 08 | `08_waterfall_diagram.png` | Schema du waterfall enrichment | A creer dans Figma/Excalidraw |
| 09 | `09_clay_add_column_button.png` | Bouton + pour ajouter une colonne avec menu deroulant | Cliquer sur le + a droite des colonnes |
| 10 | `10_clay_enrichments_panel_apollo.png` | Panneau Enrichments avec recherche "Apollo" | Rechercher "Apollo" dans le panneau enrichments |
| 11 | `11_clay_apollo_config.png` | Configuration Apollo: mapping first_name, last_name, company | Configurer l'enrichissement Apollo |
| 12 | `12_clay_enrichment_running.png` | Table avec colonne Email en cours d'enrichissement (loading) | Pendant l'enrichissement |
| 13 | `13_clay_dropcontact_condition.png` | Configuration Dropcontact avec condition "IF Email is empty" | Ajouter enrichissement avec condition |
| 14 | `14_clay_condition_interface.png` | Interface de condition Clay detaillee | Zoom sur la partie condition |
| 15 | `15_clay_formula_merge.png` | Formule Clay pour fusionner les emails | Creer colonne formule |
| 16 | `16_clay_final_enriched_table.png` | Table finale avec Email, Email_Fallback, Final_Email remplies | Apres enrichissement complet |

### Partie 3: Hack X-Ray Google

| # | Nom fichier | Description | Comment le prendre |
|---|-------------|-------------|-------------------|
| 17 | `17_google_xray_search_bar.png` | Barre de recherche Google avec requete X-Ray | Google avec `site:linkedin.com/in "CTO" "Paris"` |
| 18 | `18_google_xray_results_cto.png` | Resultats Google montrant des profils LinkedIn de CTOs | Resultats de la recherche |
| 19 | `19_google_xray_results_vp_sales.png` | Resultats pour VP Sales fintech | Recherche VP Sales |
| 20 | `20_instant_data_scraper.png` | Extension Instant Data Scraper en action sur resultats Google | Activer l'extension sur les resultats |
| 21 | `21_clay_linkedin_urls_imported.png` | Table Clay avec colonne linkedin_url remplie | Apres import des URLs |
| 22 | `22_clay_linkedin_profile_enrichment.png` | Configuration enrichissement "LinkedIn Profile" | Ajouter enrichissement LinkedIn |
| 23 | `23_clay_final_xray_table.png` | Table finale enrichie: URL -> Nom, Titre, Entreprise, Email | Resultat final |
| 24 | `24_clay_error_no_results.png` | Exemple d'erreur "No results" dans Clay | Provoquer une erreur (mauvais nom) |

---

## SESSION 2.2 - Claude Code comme Copilote GTM

**Total: 17 screenshots**

### Partie 1: Installation & Setup

| # | Nom fichier | Description | Comment le prendre |
|---|-------------|-------------|-------------------|
| 01 | `01_spotlight_terminal.png` | Spotlight avec "Terminal" tape | Cmd+Space, taper Terminal |
| 02 | `02_terminal_empty.png` | Terminal vide pret a recevoir des commandes | Ouvrir Terminal |
| 03 | `03_npm_install_progress.png` | Installation npm en cours avec barre de progression | Pendant `npm install -g @anthropic-ai/claude-code` |
| 04 | `04_claude_auth_browser.png` | Page web d'authentification Claude avec bouton "Authorize" | Quand le browser s'ouvre pour auth |
| 05 | `05_terminal_auth_success.png` | Terminal montrant "Authentication successful!" | Apres authentification reussie |

### Partie 2: Structure du workspace

| # | Nom fichier | Description | Comment le prendre |
|---|-------------|-------------|-------------------|
| 06 | `06_finder_gtm_structure.png` | Finder montrant la structure de dossiers GTM_Workspace | Ouvrir le dossier dans Finder |
| 07 | `07_vscode_transcript_example.png` | Fichier transcript ouvert dans VS Code | Ouvrir un transcript.md |
| 08 | `08_vscode_account_example.png` | Fichier account ouvert dans VS Code | Ouvrir un account.md |

### Partie 3: Le fichier CLAUDE.md

| # | Nom fichier | Description | Comment le prendre |
|---|-------------|-------------|-------------------|
| 09 | `09_vscode_claude_md.png` | Fichier CLAUDE.md ouvert avec le contenu complet | Ouvrir CLAUDE.md dans VS Code |

### Partie 4: Use cases en action

| # | Nom fichier | Description | Comment le prendre |
|---|-------------|-------------|-------------------|
| 10 | `10_claude_code_startup.png` | Terminal avec Claude Code demarre, message de bienvenue | Lancer `claude` dans GTM_Workspace |
| 11 | `11_claude_resume_call.png` | Conversation: resume d'un call | Demander un resume de call |
| 12 | `12_claude_prep_call.png` | Conversation: preparation de call | Demander une prep |
| 13 | `13_claude_weekly_analysis.png` | Conversation: analyse hebdomadaire des objections | Demander analyse semaine |
| 14 | `14_claude_followup_email.png` | Conversation: email de follow-up genere | Demander un follow-up |

### Partie 5: Sync automatique

| # | Nom fichier | Description | Comment le prendre |
|---|-------------|-------------|-------------------|
| 15 | `15_meetily_output_settings.png` | Settings Meetily avec dossier de sortie configure | Ouvrir settings Meetily |
| 16 | `16_zapier_otter_workflow.png` | Workflow Zapier: Otter -> Format -> Google Drive | Creer un Zap dans Zapier |
| 17 | `17_terminal_rename_script.png` | Terminal montrant le script de renommage en action | Executer le script |

---

## Instructions pour prendre les screenshots

### Format
- **Taille:** Pleine largeur de l'ecran (1920px ou 2560px)
- **Format:** PNG
- **Retina:** Si possible, prendre en 2x pour la nettete

### Outils recommandes
- **Mac:** Cmd+Shift+4 puis Space pour capturer une fenetre
- **CleanShot X:** Meilleur outil, permet d'annoter
- **Annotate:** Ajouter des fleches/encadrements si necessaire

### Annotations a ajouter
- Encadrer en rouge les boutons importants
- Ajouter des fleches pour guider le regard
- Flouter les donnees sensibles (emails reels, noms de clients)

### Nomenclature
```
cours/images/session-1-1/01_clay_homepage.png
cours/images/session-1-1/02_clay_create_workspace.png
...
cours/images/session-2-2/01_spotlight_terminal.png
...
```

---

## Ordre de priorite

1. **Session 1.1 - Partie 3 (X-Ray)** - Le plus "wow", montre l'astuce
2. **Session 1.1 - Partie 2 (Waterfall)** - Le coeur technique
3. **Session 2.2 - Partie 4 (Use cases)** - Les conversations Claude
4. **Session 1.1 - Partie 1 (Setup)** - Les bases
5. **Session 2.2 - Reste** - Complementaire

---

## Next steps

Une fois les screenshots pris:
1. Les placer dans `cours/images/session-X-X/`
2. Me dire quels screenshots sont prets
3. Je mettrai a jour les HTML pour remplacer les placeholders par les vraies images
