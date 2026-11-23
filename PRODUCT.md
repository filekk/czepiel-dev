# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Primary: tech recruiters and HR screeners who skim a candidate's page in under a minute, often after clicking through from LinkedIn on a phone. They want to see role fit, the AWS certification, when the candidate is available, proof of work, contact links and a CV.

Secondary: engineering leads and hackathon or university contacts who follow the GitHub links to judge technical depth.

## Product Purpose

czepiel.dev is the personal portfolio of **Filip Czepiel**, an Applied Computer Science student (Informatyka Stosowana, FTIMS, Politechnika Łódzka, Oct 2026 – Feb 2030) based in Łódź and originally from Jelenia Góra.

Its job is to land a **summer 2027 internship** as an AI / LLM Engineer, Cloud Engineer or DevOps Engineer. Applications open in **spring 2027**, and the site must be complete and convincing before then. Success means a recruiter quickly understands who he is, what he has built and that he is available, then gets in touch or downloads the CV.

The site is also his **Cloud Resume Challenge (AWS)** entry, which is in progress.

## Positioning

**Cloud is the proven foundation, and AI engineering / MLOps is where he's heading.** His dream role is MLOps or AI Engineer. He knows those internships are hard to land at his stage, so Cloud and DevOps roles are equally real targets, and cloud work must never read as secondary.

The story is one line of travel: verified Cloud / DevOps foundations (AWS SAA-C03, Terraform, CI/CD, Linux), then deployable AI systems (RAG, agents, evals, observability).
- **Avida** (Collabothon 2026, Commerzbank × Red Hat) is the first AI proof. He led the four-person team that built it in 48 hours and pitched it live on stage.
- **Project 2**, a full AI app hosted on cloud infrastructure he builds, is planned as the bridge between the two.
- **The site is its own evidence:** it runs on Terraform-managed AWS infrastructure he built, and the public repo lets anyone check that.

This positioning was confirmed by the user on 2026-11-23. It is not yet reflected on his LinkedIn.

## Operating Context

- Recruiters arrive from LinkedIn, CV links or job applications, often on mobile, and skim rather than read.
- Polish is the default language, with an English toggle for international roles.
- Content will grow before spring 2027: two more projects are coming, and the Cloud Resume Challenge parts (for example a visitor counter backed by an API) may be added.

## Capabilities and Constraints

- **Static only, no framework.** Plain HTML plus Tailwind CSS v4 (`src/input.css` → `website/style.css`), deployed as files to private S3 behind CloudFront with OAC and ACM TLS, using remote Terraform state (`infra/main.tf`) and GitHub Actions (`.github/workflows/deploy.yml`). Uses the CloudFront free-plan cache policy.
- **Bilingual PL + EN.** Every string needs both languages.
- **Lean and fast.** The site showcases the infrastructure, so page weight, load time, accessibility and clean code are part of the evidence. Any added dependency needs a reason.
- **The projects section must scale** from 2 projects now to 4 by spring 2027 without a redesign.
- **In progress, owned by the user (design work must not fake these):**
  - the CV PDF (`./resume.pdf` is missing)
  - the two upcoming projects (about two months away as of 2026-11-23). Show them only as untitled placeholders with a status, and give no details until the user supplies them.
  - the czepiel.dev / Cloud Resume Challenge stack write-up
  - the dev.to blog post

## Brand Commitments

- Name and domain: **czepiel.dev**.
- GitHub: `filekk` (https://github.com/filekk).
- LinkedIn: https://www.linkedin.com/in/filip-czepiel-563749411/.
- Email: contact@czepiel.dev.
- The old terminal look (monospace everywhere, `// HEADINGS`, `#OPEN_TO_WORK`, typewriter) is being **replaced**, at the user's request (2026-11-23).
- **Standing visual preference (2026-11-23):** no themed metaphors or gimmicks such as stations, streets or posters. The site should feel like a sharp, modern dev-tool product site at the craft level of **Vercel and Linear**. The user rejected two rounds of themed directions before stating this.

## Evidence on Hand

Source: the user's LinkedIn export, `linkedin-portfolio-info.md` (as of 2026-11-23).

- **Certification:** AWS Certified Solutions Architect – Associate (SAA-C03), issued Oct 2026, valid until 2029. Verify: https://www.credly.com/badges/49116c60-005f-4b99-bd33-87f067e0293f/public_url (link only; the Credly embed script is deliberately not used, to keep the site free of third-party scripts).
- **Projects:**
  - **Avida (AI CFO), Collabothon 2026, Commerzbank × Red Hat.** A 48-hour hackathon with a four-person team, "Karkonosh". Filip was team lead, pitched to the jury and **wrote the entire backend**, and the app ran live on stage. The stack, from the repo README: a FastAPI backend orchestrating an Analyst → Legal → Negotiator multi-agent chain, IBM Granite 3.3 8B on vLLM / llm-d in Red Hat OpenShift AI, MLflow tracing and evaluation, and 109 pytest tests; the frontend is Vue 3. Repo: https://github.com/filekk/avida-cfo. Stage photos exist on LinkedIn, but use them only with the team's consent.
  - **czepiel.dev / Cloud Resume Challenge.** Terraform, S3, CloudFront with OAC, ACM, GitHub Actions and Tailwind. Repo: https://github.com/filekk/czepiel-dev.
- **Experience, both at Książnica Karkonoska in Jelenia Góra (on site):**
  - *Junior IT Support & Systems Intern*, Feb–Mar 2025: monitoring, updating and optimising system software; database work with high standards of accuracy and information security; day-to-day technical support for staff.
  - *IT Support & Hardware Intern*, Nov–Dec 2023: diagnosing and fixing technical problems, hardware diagnostics and configuration, and network and hardware incidents under time pressure.
- **Education:**
  - Politechnika Łódzka, FTIMS, Informatyka Stosowana (engineering degree), Oct 2026 – Feb 2030, in progress.
  - Zespół Szkół Elektronicznych im. Obrońców Poczty Polskiej, Jelenia Góra: Technik Programista, Sep 2021 – May 2026, full professional title (INF.03, INF.04).
- **Volunteering:** volunteer and organizer at Łódzkie Dni Informatyki 2026 (the 10th edition, run by Łódzki Klaster ICT at Politechnika Łódzka), Nov 2026.
- **Languages:** Polish (native), English (full professional proficiency), German (basic).
- **Skills:**
  - Confirmed on LinkedIn: Linux administration, infrastructure management, AWS, cloud management, technical support, hardware diagnostics, teamwork, communication.
  - Shown by this repo: Terraform, GitHub Actions / CI/CD.
  - Confirmed by the user on 2026-11-23: Python, Docker, LLM / generative AI, C++17, Bash, SQL.
  - **Docker is kept off the page** (user decision, 2026-11-23) until a shipped project shows it; every listed skill must link to its proof.
- **Absent, and not to be invented:** testimonials, references, metrics, traffic numbers, blog posts, Avida's feature list, and any detail of the upcoming projects. Leave the seasonal non-technical job off the portfolio.

## Product Principles

1. **Scannable in 30 seconds.** Who he is, what he's looking for (summer 2027 internship: AI/LLM, Cloud, DevOps), the certification and how to contact him come first.
2. **Proof over claims.** Back every skill with a cert, a shipped project or a link that can be checked, and present placeholders honestly as "coming".
3. **The site is the demo.** Its infrastructure, speed, accessibility and clean code are part of the pitch.
4. **Both languages are first-class.** Nothing ships in only one language.
5. **Honest about being junior.** Show his trajectory and what he has shipped; never inflate.
