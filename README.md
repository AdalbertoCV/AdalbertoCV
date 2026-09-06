<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/hero-dark.svg">
  <img src="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/hero-light.svg" alt="Adal Cerrillo — Software Engineer, Zacatecas, Mexico" width="520">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/divider-dark.svg">
  <img src="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/divider-light.svg" alt="" width="520">
</picture>

</div>

Software engineer at [**Radii**](https://www.radii.com.mx). I build web applications end to end — **APIs in Java and Python**, interfaces in **React**, all of it packaged in **Docker**. What holds my attention is software someone actually uses: systems for institutions, internal tools, projects that solve a concrete problem for a real person.

This is my public code account, so everything below is open and readable. I also write music with code, in case the backend gets boring.

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/divider-dark.svg">
  <img src="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/divider-light.svg" alt="" width="520">
</picture>

</div>

## Radii · Software Engineer · 2025 — present

[Radii](https://www.radii.com.mx) is supply-chain-as-a-service for nearshoring manufacturing in Mexico — CNC parts for aerospace and automotive, quoted and sourced through one platform.

I work on the part where a drawing becomes a number.

**Instant quoting for CNC parts.** CAD and 2D drawing ingestion, DFM checks, and the pricing engine that turns geometry into a quote.

**Vision-based spec extraction.** Pulling material, tolerances, finishes and dimensions off 2D prints — including the precedence rules for when the drawing and the RFQ disagree with each other.

**Price calibration.** A benchmark corpus of real parts, replayed against the pricer so that a change to the model can be measured rather than argued about.

**Platform work.** Django REST API, cloud workers, a React 19 front end, and the queue plumbing between them.

Most of this lives in private repositories; [**@AdalbertoCerrillo**](https://github.com/AdalbertoCerrillo) is where that side of the work is written up.

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/divider-dark.svg">
  <img src="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/divider-light.svg" alt="" width="520">
</picture>

</div>

## Also building

<img src="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/stackselect.svg" alt="StackSelect" width="56" align="left" hspace="14">

**StackSelect** — a startup I'm building, aimed at helping students take their first step into the working world.

<br clear="left">

<img src="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/moonphase.svg" alt="Moonphase" width="56" align="left" hspace="14">

**Moonphase** — my other startup, built from zero. *Creating even the impossible, one step at a time.* Coming soon.

<br clear="left">

<img src="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/evodeps.svg" alt="Evodeps" width="56" align="left" hspace="14">

**[Evodeps](https://github.com/Evodeps)** — active contributor.

<br clear="left">

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/divider-dark.svg">
  <img src="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/divider-light.svg" alt="" width="520">
</picture>

</div>

# Projects

Everything below is public and readable. Each entry says what the project **is** and what it **demonstrates** — the second part is the reason it's worth opening.

### Featured

<table>
<tr><td width="32%">

**[Nocturno 108](https://github.com/AdalbertoCV/nocturno-108)**

<sub>`Strudel` · `Web Audio API` · `JavaScript`</sub>

</td><td>

A jazz-hop track written as code. Strudel for the score, plus a player with an audio engine **synthesised from scratch in Web Audio** — no samples, no libraries. An avatar that dances on the beat, a live piano roll, and a mixer.

**Demonstrates** real-time audio synthesis, scheduling against a clock, and creative coding that still has to keep time.

</td></tr>
<tr><td>

**[COSIAP](https://github.com/AdalbertoCV/Sistema-de-Apoyos-COZCyT)**

<sub>`Django` · `Docker` · `Python`</sub>

</td><td>

Grant management for the Zacatecas Science and Technology Council — applications, review workflow and awards for a real public institution. Built with a team.

**Demonstrates** domain modelling for an organisation with actual rules, and shipping to users who are not developers.

</td></tr>
<tr><td>

**[Cargas UAIE](https://github.com/AdalbertoCV/Sistema-de-Cargas-UAIE)**

<sub>`Django` · `Docker` · `SCSS`</sub>

</td><td>

Academic workload management for a university department: distributing teaching load across faculty, subjects and terms. Also a team build.

**Demonstrates** constraint-heavy scheduling and a Dockerised Django deployment.

</td></tr>
<tr><td>

**[ETL → Dgraph](https://github.com/AdalbertoCV/ETL-Equipo4)**

<sub>`Python` · `Dgraph` · `Luigi` · `Dash`</sub>

</td><td>

A pipeline that consolidates purchasing data scattered across **four heterogeneous formats** — CSV, XML, HTM and TXT — into a single graph database, then serves it through an analytics dashboard.

**Demonstrates** extractor/transformer separation that stays extensible per format, task orchestration with Luigi, and choosing a graph model because the data *is* relationships.

</td></tr>
</table>

### Systems & architecture

| Project | What it demonstrates |
|---|---|
| **[SMAM — Publish/Subscribe](https://github.com/AdalbertoCV/Publica-Suscribe-Equipo4)**<br><sub>`Python` · `ActiveMQ` · `STOMP`</sub> | Real-time vital-sign telemetry from simulated wearables, fanned out to three independent subscribers over ActiveMQ. The architectural point: producers never learn who consumes them, so adding a consumer touches no device code. |
| **[Sockets](https://github.com/AdalbertoCV/Sockets)**<br><sub>`Java` · `TCP` · `Swing`</sub> | A chat over raw TCP sockets with file transfer — no framework hiding the handshake. Concurrency by hand: the receive loop runs on its own thread so a blocking `readLine()` can't freeze the interface. |
| **[OOP & Data Structures](https://github.com/AdalbertoCV/POO-EDD)**<br><sub>`Java` · `JDBC` · `Gradle`</sub> | ~340 Java classes. Lists, stacks, queues, trees, graphs and heaps **implemented from scratch** in static and dynamic variants — nothing leans on `java.util.Collections`. Plus a DAO layer, REST services and Android clients. |

### Engineering practice

| Project | What it demonstrates |
|---|---|
| **[Software Testing](https://github.com/AdalbertoCV/Ejercicios_Testing_ENEDIC24)**<br><sub>`Python` · `Behave` · `Selenium`</sub> | The full testing pyramid in one repository: doctest → `unittest` with coverage → BDD in Gherkin → end-to-end browser tests against a Django voting system, verified at model, form, view and flow level. |
| **[Personal Software Process](https://github.com/AdalbertoCV/Personal_Software_Process_03)**<br><sub>`Java` · `PSP (SEI)`</sub> | Five programs, each shipped with its full process record: PROBE size estimates, time and defect logs by phase, review checklists and a postmortem. Measuring my own engineering instead of guessing at it. |
| **[Database practice](https://github.com/AdalbertoCV/DBS_Practices)**<br><sub>`Oracle SQL` · `PL/SQL`</sub> | 31 scripts across four schemas: joins, correlated subqueries, analytic functions, views and transaction scenarios — including two data models designed and built from scratch. |
| **[Coding challenges](https://github.com/AdalbertoCV/retos_coding)**<br><sub>`Java` · `Algorithms`</sub> | Java practice for the problems that turn up in technical interviews. |

### Web & applications

| Project | What it demonstrates |
|---|---|
| **[Portfolio](https://github.com/AdalbertoCV/Portfolio)**<br><sub>`React` · `JavaScript` · `Vercel`</sub> | My personal portfolio, deployed on Vercel. |
| **[Django frameworks](https://github.com/AdalbertoCV/Frameworks)**<br><sub>`Django` · `MariaDB` · `Docker`</sub> | From hello-world to an academic enrolment system: email-activation tokens extending Django's own generator, custom RFC and image validators, a prerequisite graph modelled as a self-relation, and dependent selects over AJAX. |
| **[The Code Company](https://github.com/AdalbertoCV/The-Code-Company-Website)**<br><sub>`Django 4.2` · `SCSS` · `Docker`</sub> | A corporate site where every section is admin-managed, including a Q&A module whose comments require approval before they publish. |
| **[Visual .NET](https://github.com/AdalbertoCV/Visual.NET)**<br><sub>`C#` · `ASP.NET Core` · `EF Core`</sub> | The whole .NET arc: console OOP, then Windows Forms, then ASP.NET Core MVC with Entity Framework migrations and Identity. |
| **[Bazar Sol](https://github.com/AdalbertoCV/Bazar_Sol)**<br><sub>`HTML` · `CSS`</sub> | An online clothing store. |

### Security & data

| Project | What it demonstrates |
|---|---|
| **[CTF writeups](https://github.com/AdalbertoCV/Writeups_picoCTF)**<br><sub>`picoCTF` · `Bandit` · `Ghidra`</sub> | ~160 challenges documented across web exploitation, cryptography, forensics, reverse engineering and binary exploitation. Each one records the reasoning, not just the flag. |
| **[Stroke prediction](https://github.com/AdalbertoCV/stroke_classification_RF)**<br><sub>`R` · `Random Forest` · `ROSE`</sub> | Random Forest on a dataset with **~5% positives**, where a naive model scores 95% accuracy and detects nothing. Boruta for feature selection, ROSE for rebalancing, ROC/AUC in place of accuracy. |

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/divider-dark.svg">
  <img src="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/divider-light.svg" alt="" width="520">
</picture>

</div>

## Stack

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/stack-dark.svg">
  <img src="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/stack-light.svg" alt="Stack by area: backend, frontend, data, platform, quality" width="520">
</picture>

</div>

Where the code actually goes, measured across my repositories and counting programming languages only:

```
Java         ████████████████░░░░░░░░░░░░░░░░░░░░░░░░   41 %   Spring Boot, APIs, algorithms
JavaScript   █████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░   33 %   React and web clients
Python       █████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   22 %   Django, testing, scripting
C#           █░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░    4 %
```

Beyond that, more than half the total volume is **HTML, CSS and SCSS** — the interfaces of those same projects.

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/divider-dark.svg">
  <img src="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/divider-light.svg" alt="" width="520">
</picture>

</div>

## Elsewhere

<div align="center">

[<img src="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/btn-portfolio.svg" alt="Portfolio" width="142">](https://portfolio-phi-ten-37.vercel.app/) [<img src="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/btn-linkedin.svg" alt="LinkedIn" width="130">](https://www.linkedin.com/in/adalberto-cerrillo-v%C3%A1zquez-a3870628a) [<img src="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/btn-youtube.svg" alt="YouTube" width="118">](https://www.youtube.com/@acerrillosoftware) [<img src="https://raw.githubusercontent.com/AdalbertoCV/AdalbertoCV/main/assets/btn-profile.svg" alt="AdalbertoCerrillo on GitHub" width="250">](https://github.com/AdalbertoCerrillo)

</div>
