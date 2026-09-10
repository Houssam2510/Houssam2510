<div align="center">
  <img src="assets/banner.svg" alt="Houssam Nadir — Génie informatique, Polytechnique Montréal" width="100%">
</div>

<div align="center">

<a href="https://houssam-nadir.me">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=21&pause=1400&color=FFB225&center=true&vCenter=true&width=780&height=46&lines=Le+mod%C3%A8le+extrait%2C+le+code+d%C3%A9cide.;The+model+extracts%2C+the+code+decides.;Un+invariant+non+test%C3%A9+n%27existe+pas.;An+untested+invariant+does+not+exist." alt="Le modèle extrait, le code décide.">
</a>

<br>

<a href="https://houssam-nadir.me"><img src="https://img.shields.io/badge/PORTFOLIO-houssam--nadir.me-FFB225?style=for-the-badge&labelColor=191510" alt="Portfolio"></a> <a href="https://www.linkedin.com/in/houssam-nadir-a1a292263/"><img src="https://img.shields.io/badge/LINKEDIN-Houssam_Nadir-FFB225?style=for-the-badge&logo=linkedin&logoColor=FFB225&labelColor=191510" alt="LinkedIn"></a> <a href="mailto:houssam.nadir@outlook.com"><img src="https://img.shields.io/badge/EMAIL-houssam.nadir@outlook.com-FFB225?style=for-the-badge&logo=maildotru&logoColor=FFB225&labelColor=191510" alt="Email"></a> <img src="https://img.shields.io/badge/MONTRÉAL-UTC−5-B1ADA9?style=for-the-badge&labelColor=191510" alt="Montréal">

</div>

---

<details open>
<summary><h3>&nbsp;🇫🇷&nbsp;&nbsp;Français</h3></summary>

<br>

Étudiant en **génie informatique à Polytechnique Montréal**, diplômé en déc. 2027.
J'expédie des produits complets, seul : pipelines LLM à sorties structurées, scoring
déterministe, comptabilité transactionnelle sans course, sécurité cloud.

Trois principes, tenus dans les trois produits :

| | |
|:--|:--|
| **Le modèle extrait, le code décide** | Un LLM reformule et classe. Chaque chiffre montré à l'utilisateur sort d'une fonction pure, reproductible. |
| **Un invariant non testé n'existe pas** | Les règles produit descendent au niveau du test : elles échouent la CI au lieu de dormir dans un document. |
| **La contrainte d'exécution est une contrainte de conception** | Le timeout d'une Lambda, le débit d'un fournisseur : des paramètres d'architecture, pas des accidents. |

#### En production

Ces trois produits tournent réellement. Leur code est privé — les liens pointent vers les applications elles-mêmes.

<table>
<tr>
<td width="33%" valign="top">

**[Carriv](https://carriv.com)** &nbsp;`en prod`

Adapte un CV à une offre sous une règle de zéro invention inscrite dans chaque prompt. Le score ATS est une fonction déterministe, pas une sortie de modèle.

`~30 s` par génération
`SvelteKit 2` · `MongoDB` · `Stripe`

</td>
<td width="33%" valign="top">

**[StudyLumina](https://app.studylumina.com)** &nbsp;`en prod`

Mesure la préparation réelle à un examen, chapitre par chapitre. Chaque réponse est citée (document et page). Aucune note produite par un LLM.

`47 600` lignes TS · `74` fichiers de tests
`Next.js 15` · `pgvector` · `BullMQ`

</td>
<td width="33%" valign="top">

**[Sanade](https://sanade.app)** &nbsp;`en prod`

Suivi d'habitudes qui arbitre au lieu d'enregistrer : deux ou trois objectifs tenables par jour, et la raison de chaque écart.

`62 000` lignes TS · `941` tests
`Expo` · `tRPC` · `Turborepo`

</td>
</tr>
</table>

#### Code public

<table>
<tr>
<td width="50%" valign="top">

**[triage](https://github.com/Houssam2510/triage)** &nbsp;`Python` `MIT`

Priorisation de vulnérabilités par le risque réel : corrèle les résultats Trivy avec CISA KEV, FIRST EPSS et NVD pour trier ce qu'il faut corriger d'abord.

</td>
<td width="50%" valign="top">

**[e2ee-messenger-protocol](https://github.com/Houssam2510/e2ee-messenger-protocol)** &nbsp;`TypeScript` `MIT`

Protocole de messagerie E2EE réimplémenté de zéro : X3DH + Double Ratchet, relais zero-knowledge.

</td>
</tr>
<tr>
<td valign="top">

**[Portfolio](https://github.com/Houssam2510/Portfolio)** &nbsp;`TypeScript`

Le code de [houssam-nadir.me](https://houssam-nadir.me). Next.js 16, tokens `oklch()`, fond en canvas, zéro framework CSS.

</td>
<td valign="top">

**[htmlToMp4](https://github.com/Houssam2510/htmlToMp4)** &nbsp;`JavaScript`

Convertit une animation HTML/CSS/JS en MP4 vertical 1080×1920 via Puppeteer, sans déformation.

</td>
</tr>
</table>

</details>

<details>
<summary><h3>&nbsp;🇬🇧&nbsp;&nbsp;English</h3></summary>

<br>

**Computer engineering student at Polytechnique Montréal**, graduating Dec. 2027.
I ship complete products on my own: structured-output LLM pipelines, deterministic
scoring, race-free transactional accounting, cloud security.

Three principles, held across all three products:

| | |
|:--|:--|
| **The model extracts, the code decides** | An LLM rephrases and classifies. Every number shown to a user comes out of a pure, reproducible function. |
| **An untested invariant does not exist** | Product rules live at the test level: they fail CI instead of sitting in a document nobody rereads. |
| **Runtime constraints are design constraints** | A Lambda's timeout, a provider's rate limit: architecture parameters, not accidents to absorb in production. |

#### In production

All three products are live. Their source is private — the links point to the applications themselves.

<table>
<tr>
<td width="33%" valign="top">

**[Carriv](https://carriv.com)** &nbsp;`live`

Tailors a résumé to a job posting under a zero-fabrication rule written into every prompt. The ATS score is a deterministic function, never a model output.

`~30 s` per generation
`SvelteKit 2` · `MongoDB` · `Stripe`

</td>
<td width="33%" valign="top">

**[StudyLumina](https://app.studylumina.com)** &nbsp;`live`

Measures real exam readiness, chapter by chapter. Every answer is cited (document and page). No grade is ever produced by an LLM.

`47,600` TS lines · `74` test files
`Next.js 15` · `pgvector` · `BullMQ`

</td>
<td width="33%" valign="top">

**[Sanade](https://sanade.app)** &nbsp;`live`

A habit tracker that arbitrates instead of recording: two or three achievable goals a day, and the reason behind every trade-off.

`62,000` TS lines · `941` tests
`Expo` · `tRPC` · `Turborepo`

</td>
</tr>
</table>

#### Public code

<table>
<tr>
<td width="50%" valign="top">

**[triage](https://github.com/Houssam2510/triage)** &nbsp;`Python` `MIT`

Risk-based vulnerability triage: correlates Trivy findings with CISA KEV, FIRST EPSS and NVD to rank what to fix first.

</td>
<td width="50%" valign="top">

**[e2ee-messenger-protocol](https://github.com/Houssam2510/e2ee-messenger-protocol)** &nbsp;`TypeScript` `MIT`

An E2EE messenger protocol built from scratch: X3DH + Double Ratchet over a zero-knowledge relay.

</td>
</tr>
<tr>
<td valign="top">

**[Portfolio](https://github.com/Houssam2510/Portfolio)** &nbsp;`TypeScript`

Source of [houssam-nadir.me](https://houssam-nadir.me). Next.js 16, `oklch()` tokens, canvas background, no CSS framework.

</td>
<td valign="top">

**[htmlToMp4](https://github.com/Houssam2510/htmlToMp4)** &nbsp;`JavaScript`

Turns an HTML/CSS/JS animation into a vertical 1080×1920 MP4 through Puppeteer, without distortion.

</td>
</tr>
</table>

</details>

---

### &nbsp;Stack

<table>
<tr><td width="150"><b>Langages</b></td><td>
<img src="https://skillicons.dev/icons?i=ts,js,python,kotlin,java,bash&theme=dark" height="42" alt="TypeScript, JavaScript, Python, Kotlin, Java, Bash">
</td></tr>
<tr><td><b>Frameworks</b></td><td>
<img src="https://skillicons.dev/icons?i=nextjs,react,svelte,nodejs,tailwind&theme=dark" height="42" alt="Next.js, React, Svelte, Node.js, Tailwind">
<img src="https://img.shields.io/badge/Expo-191510?style=flat&logo=expo&logoColor=F7F5F2" height="30" alt="Expo">
<img src="https://img.shields.io/badge/tRPC-191510?style=flat&logo=trpc&logoColor=FFB225" height="30" alt="tRPC">
</td></tr>
<tr><td><b>Données</b></td><td>
<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,prisma,supabase&theme=dark" height="42" alt="PostgreSQL, MongoDB, Redis, Prisma, Supabase">
<img src="https://img.shields.io/badge/pgvector-191510?style=flat&logo=postgresql&logoColor=FFB225" height="30" alt="pgvector">
</td></tr>
<tr><td><b>Cloud &amp; outils</b></td><td>
<img src="https://skillicons.dev/icons?i=aws,docker,terraform,vercel,sentry,git&theme=dark" height="42" alt="AWS, Docker, Terraform, Vercel, Sentry, Git">
</td></tr>
<tr><td><b>Sécurité</b></td><td>
<img src="https://img.shields.io/badge/X3DH_+_Double_Ratchet-191510?style=flat&logoColor=FFB225" height="30" alt="X3DH + Double Ratchet">
<img src="https://img.shields.io/badge/CIS_Benchmarks-191510?style=flat&logoColor=FFB225" height="30" alt="CIS Benchmarks">
<img src="https://img.shields.io/badge/CISA_KEV_·_EPSS_·_NVD-191510?style=flat&logoColor=FFB225" height="30" alt="CISA KEV, EPSS, NVD">
<img src="https://img.shields.io/badge/WebCrypto-191510?style=flat&logoColor=FFB225" height="30" alt="WebCrypto">
</td></tr>
</table>

---

<div align="center">

<!--
  STATS GITHUB - a reactiver une fois le compteur de contributions corrige.

  Aujourd'hui GitHub rapporte 0 contribution sur 12 mois pour ce compte : ces
  deux widgets rendraient une grille vide et un streak a 0/0/0.
  A corriger d'abord :
    1. github.com/settings/profile -> cocher "Include private contributions
       on my profile"
    2. github.com/settings/emails  -> verifier que houssam.nadir@outlook.com
       est bien un email VERIFIE du compte, sinon les commits ne comptent pas
  Puis supprimer ces deux lignes de commentaire.

<img src="https://ghchart.rshah.org/FFB225/Houssam2510" alt="Contributions de Houssam2510" width="88%">

<br>

<img src="https://github-readme-streak-stats.herokuapp.com?user=Houssam2510&theme=dark&background=0F0C08&border=3A342C&stroke=3A342C&ring=FFB225&fire=FFB225&currStreakLabel=FFB225&sideLabels=B1ADA9&dates=8C877F&sideNums=F7F5F2&currStreakNum=F7F5F2" alt="Streak">

<br><br>
-->

<img src="https://komarev.com/ghpvc/?username=Houssam2510&color=FFB225&style=flat-square&label=VISITES" alt="Compteur de visites">

</div>
