# 🤖 AI Kursusmateriale

Velkommen til dette repository!  
Her samler jeg alt materiale, noter, kodeeksempler og ressourcer, som jeg bruger gennem AI-kurset.

---

# 🧠 Prompt Style Reference Guide
**En samlet oversigt over nyttige “prompt-tags” til ChatGPT / LLM’er.**  
Brug dem til at styre *tone, dybde, perspektiv, form og persona*.

---

## 🧩 Grundlæggende forståelsesniveau

| Tag | Funktion | Eksempel |
|-----|-----------|----------|
| `ELI5` | Forklar som til et barn på 5 år. | `ELI5: Hvad er et operativsystem?` |
| `ELI10` | Forklar som til en 10-årig. | `ELI10: Hvad betyder DNS cache?` |
| `Simplify` | Gør teksten så simpel som muligt. | `Simplify: Kubernetes forklaret.` |
| `Clarify` | Fjern tvetydighed og gør teksten klar. | `Clarify: Denne procesbeskrivelse.` |
| `Expertify` | Forklar for et teknisk publikum. | `Expertify: Load balancing i NGINX.` |
| `Academic` | Brug akademisk, objektiv stil. | `Academic: Cloud sikkerhed.` |

---

## ✍️ Formatering & tone

| Tag | Funktion | Eksempel |
|-----|-----------|----------|
| `TL;DR` | Ultrakort opsummering. | `TL;DR: Artiklen her.` |
| `Summarize` | Lav et neutralt resume. | `Summarize: Rapport om netværk.` |
| `Expand` | Uddyb eller forlæng teksten. | `Expand: Dette afsnit.` |
| `Formalize` | Gør sproget formelt og struktureret. | `Formalize: Brev til ledelsen.` |
| `Casualize` | Gør sproget mere afslappet. | `Casualize: Slack-besked.` |
| `Professionalize` | Gør sproget professionelt. | `Professionalize: LinkedIn tekst.` |
| `Humanize` | Gør sproget varmt og flydende. | `Humanize: FAQ tekst.` |
| `Jargonize` | Brug teknisk fagsprog. | `Jargonize: DevOps dokumentation.` |
| `Dejargonize` | Fjern fagsprog og forklar enkelt. | `Dejargonize: Forklar til kunder.` |

---

## 💬 Struktur & format

| Tag | Funktion | Eksempel |
|-----|-----------|----------|
| `LISTIFY` | Lav en punktopstilling. | `LISTIFY: Forbedringer i netværk.` |
| `Compare` | Sammenlign to eller flere ting. | `Compare: Docker vs Podman.` |
| `ProsCons` | Oplist fordele og ulemper. | `ProsCons: Open source firewall.` |
| `Tablefy` | Præsenter som tabel. | `Tablefy: Backup-metoder.` |
| `Checklist` | Lav en tjekliste. | `Checklist: Server klargøring.` |
| `Steps` | Forklar trin-for-trin. | `Steps: Installer Ollama.` |
| `Bulletify` | Forkort hvert punkt maks. 1 linje. | `Bulletify: Deployment flow.` |
| `Outline` | Lav en struktureret plan. | `Outline: Artikel om AI sikkerhed.` |

---

## 🎭 Stil & stemning

| Tag | Funktion | Eksempel |
|-----|-----------|----------|
| `Story` | Fortæl som en historie. | `Story: En sysadmin og et nedbrud.` |
| `Analogy` | Brug metaforer. | `Analogy: RAM forklaret som postkontor.` |
| `Examplefy` | Tilføj konkrete eksempler. | `Examplefy: Log rotation.` |
| `Visualize` | Skab et mentalt billede. | `Visualize: Trafikflow i et netværk.` |
| `Scenario` | Beskriv et tænkt scenarie. | `Scenario: Server går offline.` |
| `Dialogue` | Skriv som en samtale. | `Dialogue: Support og bruger.` |
| `Humorize` | Tilføj humor. | `Humorize: Sysadmin hverdag.` |
| `Dramatize` | Gør teksten dramatisk og levende. | `Dramatize: Datacenter blackout.` |
| `Poetic` | Skriv som et digt eller lyrisk. | `Poetic: Om cybersikkerhed.` |

---

## ⚙️ Funktionelle

| Tag | Funktion | Eksempel |
|-----|-----------|----------|
| `Code` | Giv kodeeksempel. | `Code: Bash ping-script.` |
| `ExplainCode` | Forklar koden linje for linje. | `ExplainCode: Dockerfile.` |
| `Debug` | Find og forklar fejl. | `Debug: Min Python-app.` |
| `Optimize` | Gør koden mere effektiv. | `Optimize: SQL query.` |
| `Blueprint` | Giv et overordnet design. | `Blueprint: CI/CD pipeline.` |
| `Template` | Lav et genbrugeligt format. | `Template: Rapportskabelon.` |
| `Refactor` | Skriv om uden at ændre funktion. | `Refactor: Bash script.` |
| `Document` | Lav dokumentation. | `Document: API endpoints.` |

---

## 🧭 Avancerede analyse-tags

| Tag | Funktion | Eksempel |
|-----|-----------|----------|
| `Critique` | Giv objektiv kritik. | `Critique: Denne plan.` |
| `Evaluate` | Vurder styrker og svagheder. | `Evaluate: Firewall design.` |
| `Analyze` | Bryd emnet ned i komponenter. | `Analyze: AI bias.` |
| `Synthesize` | Kombinér flere ideer til én. | `Synthesize: Tre sikkerhedsstrategier.` |
| `Reframe` | Forklar emnet ud fra en anden vinkel. | `Reframe: IT som værdi, ikke udgift.` |
| `ReverseEngineer` | Gæt processen bag resultatet. | `ReverseEngineer: Bash logik.` |
| `CompareAndConclude` | Sammenlign og giv konklusion. | `CompareAndConclude: Linux distros.` |
| `CriticizeGently` | Giv konstruktiv feedback. | `CriticizeGently: Brugerflade design.` |

---

## 🧙 Persona & rolle

| Tag | Funktion | Eksempel |
|-----|-----------|----------|
| `PersonaMode` | Skift rolle/perspektiv. | `PersonaMode: Du er IT-chef.` |
| `Socratic` | Stil spørgsmål i stedet for at forklare. | `Socratic: Hvad tror du sker ved fejl?` |
| `TeacherMode` | Undervisningsstil med trinvis læring. | `TeacherMode: Lær Git branches.` |
| `Coach` | Motiver og vejled. | `Coach: Jeg vil lære scripting.` |
| `Mentor` | Kombinér erfaring og vejledning. | `Mentor: Karriere i DevOps.` |
| `DevilAdvocate` | Argumentér modsat for at udfordre. | `DevilAdvocate: Hvorfor ikke open source?` |
| `Roleplay` | Spill en rolle i en simulering. | `Roleplay: IT support call.` |
| `Interview` | Stil spørgsmål som interviewer. | `Interview: CEO om cybersikkerhed.` |

---

## 🧪 Kreative & eksperimentelle

| Tag | Funktion | Eksempel |
|-----|-----------|----------|
| `Brainstorm` | Generér mange ideer hurtigt. | `Brainstorm: Nye backupstrategier.` |
| `Mindmap` | Lav en konceptuel oversigt. | `Mindmap: IT sikkerhedslag.` |
| `Remix` | Kombinér to koncepter. | `Remix: Kubernetes + AI.` |
| `Inspire` | Giv kreative forslag. | `Inspire: Workshop tema.` |
| `Gamify` | Omskriv som spil eller udfordring. | `Gamify: Lær netværkssikkerhed.` |
| `Cinematic` | Fortæl som en film-scene. | `Cinematic: Datacenter krise.` |
| `Journal` | Skriv som dagbog. | `Journal: Første dag som sysadmin.` |
| `Narrative` | Skab sammenhængende fortælling. | `Narrative: Cloud-migrering.` |

---

## ⚡ Kombinér tags

Du kan kombinere flere tags for at styre både form, tone og perspektiv:  

```text
ELI10 + LISTIFY: Forklar hvordan VPN fungerer.
