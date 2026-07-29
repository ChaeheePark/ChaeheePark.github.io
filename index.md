---
layout: default
title: Chaehee Park
description: Applied AI Researcher specializing in multimodal intelligence and AI for social impact
last_modified_at: 2026-07-29
---

<style>
:root {
  --profile-text: #2f3742;
  --profile-heading: #172033;
  --profile-muted: #687386;
  --profile-border: #e3e8ef;
  --profile-background: #f8fafc;
  --profile-link: #315b7d;
}

/* ---------- Page ---------- */

.profile-page {
  max-width: 880px;
  margin: 0 auto;
  color: var(--profile-text);
  font-size: 16px;
  line-height: 1.72;
}

.profile-page * {
  box-sizing: border-box;
}

.profile-page a {
  color: var(--profile-link);
  text-decoration: none;
}

.profile-page a:hover {
  text-decoration: underline;
}

.profile-page h2 {
  margin: 3.2rem 0 1.4rem;
  padding-bottom: 0.55rem;
  border-bottom: 1px solid var(--profile-border);
  color: var(--profile-heading);
  font-size: 1.48rem;
  font-weight: 700;
  letter-spacing: -0.025em;
}

.profile-page h3 {
  margin: 2.1rem 0 1.1rem;
  color: var(--profile-heading);
  font-size: 1.08rem;
  font-weight: 700;
  letter-spacing: -0.015em;
}

/* ---------- Header ---------- */

.profile-header {
  margin: 1rem 0 2.4rem;
}

.profile-role {
  margin: 0 0 0.5rem;
  color: var(--profile-heading);
  font-size: 1.2rem;
  font-weight: 650;
  letter-spacing: -0.015em;
}

.profile-affiliation {
  margin: 0;
  color: #525d6d;
  font-size: 0.97rem;
  line-height: 1.65;
}

.profile-contact {
  margin: 0.9rem 0 0;
  color: var(--profile-muted);
  font-size: 0.91rem;
}

.profile-contact a {
  font-weight: 500;
}

.profile-updated {
  margin: 0.35rem 0 0;
  color: #8a94a3;
  font-size: 0.8rem;
}

/* ---------- Introduction ---------- */

.profile-introduction {
  margin: 1.8rem 0 2.5rem;
  padding: 1.25rem 1.4rem;
  border: 1px solid var(--profile-border);
  border-radius: 7px;
  background: var(--profile-background);
}

.profile-introduction p {
  margin: 0;
  color: #3f4957;
  line-height: 1.75;
}

/* ---------- Lists ---------- */

.profile-list {
  margin: 0;
  padding-left: 1.25rem;
}

.profile-list li {
  margin-bottom: 0.48rem;
}

.profile-list li::marker {
  color: #8995a5;
}

/* ---------- Experience and Education ---------- */

.timeline-item {
  margin-bottom: 2.25rem;
}

.timeline-heading {
  display: flex;
  flex-wrap: wrap;
  align-items: baseline;
  justify-content: space-between;
  gap: 0.3rem 1rem;
}

.timeline-organization {
  color: var(--profile-heading);
  font-size: 1.04rem;
  font-weight: 700;
}

.timeline-period {
  color: #7a8595;
  font-size: 0.86rem;
  white-space: nowrap;
}

.timeline-position {
  margin: 0.18rem 0 0.65rem;
  color: #566273;
  font-size: 0.94rem;
  font-weight: 500;
}

.timeline-description {
  margin: 0;
  padding-left: 1.25rem;
}

.timeline-description li {
  margin-bottom: 0.45rem;
}

.timeline-description li::marker {
  color: #8995a5;
}

/* ---------- Publications ---------- */

.publication {
  margin-bottom: 1.85rem;
  padding-left: 1rem;
  border-left: 3px solid #e3e8ee;
}

.publication-title {
  margin: 0 0 0.2rem;
  color: var(--profile-heading);
  font-size: 1rem;
  font-weight: 700;
  line-height: 1.55;
}

.publication-authors {
  margin: 0 0 0.15rem;
  color: #404a58;
  font-size: 0.92rem;
  line-height: 1.55;
}

.publication-venue {
  margin: 0;
  color: #657080;
  font-size: 0.9rem;
  line-height: 1.55;
}

.publication-meta {
  margin-top: 0.42rem;
}

/* ---------- Tags ---------- */

.tag {
  display: inline-block;
  margin: 0.1rem 0.22rem 0.1rem 0;
  padding: 0.09rem 0.42rem;
  border-radius: 4px;
  font-size: 0.7rem;
  font-weight: 650;
  line-height: 1.55;
}

.tag-journal {
  background: #eaf2f8;
  color: #244d6a;
}

.tag-author {
  background: #fff1e8;
  color: #8b3f1f;
}

.tag-language {
  background: #f0f3f7;
  color: #566273;
}

.tag-conference {
  background: #edf5ef;
  color: #356044;
}

/* ---------- Publication Links ---------- */

.publication-links {
  display: inline-block;
  margin: 0.1rem 0 0;
}

.publication-links a {
  display: inline-block;
  margin: 0.1rem 0.22rem 0.1rem 0;
  padding: 0.08rem 0.4rem;
  border: 1px solid #cbd5e1;
  border-radius: 4px;
  background: #ffffff;
  color: #334155;
  font-size: 0.71rem;
  font-weight: 650;
  line-height: 1.55;
  text-decoration: none;
  transition:
    background-color 0.15s ease,
    border-color 0.15s ease,
    color 0.15s ease;
}

.publication-links a:hover {
  border-color: #475569;
  background: #475569;
  color: #ffffff;
  text-decoration: none;
}

/* ---------- Footnote ---------- */

.publication-note {
  margin-top: 1.4rem;
  color: #7b8594;
  font-size: 0.8rem;
}

/* ---------- Responsive ---------- */

@media screen and (max-width: 640px) {
  .profile-page {
    font-size: 15px;
  }

  .profile-role {
    font-size: 1.08rem;
  }

  .profile-page h2 {
    margin-top: 2.7rem;
    font-size: 1.35rem;
  }

  .timeline-heading {
    display: block;
  }

  .timeline-period {
    display: block;
    margin-top: 0.15rem;
  }

  .profile-introduction {
    padding: 1.05rem 1.1rem;
  }
}
</style>

<main class="profile-page">

  <header class="profile-header">
    <p class="profile-role">
      Applied AI Researcher · Multimodal Intelligence · AI for Social Impact
    </p>

    <p class="profile-affiliation">
      AI &amp; Big Data Team,
      <a href="https://www.si.re.kr/index.do">The Seoul Institute</a><br>
      Seoul, Republic of Korea
    </p>

    <p class="profile-contact">
      📩 <a href="mailto:chaehee@si.re.kr">chaehee@si.re.kr</a>
    </p>

    <p class="profile-updated">
      Last updated: July 29, 2026
    </p>
  </header>

  <section class="profile-introduction">
    <p>
      I am a researcher in the AI &amp; Big Data Team at The Seoul Institute.
      My research lies at the intersection of
      <strong>large language models, multimodal artificial intelligence,
      and public-sector innovation</strong>.
      I am particularly interested in translating advanced AI methods into
      deployable systems for psychological assessment, urban safety,
      public policy, and knowledge-intensive administrative services.
    </p>
  </section>

  <section>
    <h2>Research Interests</h2>

    <ul class="profile-list">
      <li>
        Large Language Models, Retrieval-Augmented Generation, and Agentic AI
      </li>
      <li>
        Multimodal AI for Psychological Assessment and Human–AI Interaction
      </li>
      <li>
        Trustworthy LLM Evaluation and Knowledge-Intensive AI Systems
      </li>
      <li>
        AI for Social Impact, Urban Safety, and Public Policy
      </li>
    </ul>
  </section>

  <section>
    <h2>Professional Experience</h2>

    <article class="timeline-item">
      <div class="timeline-heading">
        <span class="timeline-organization">The Seoul Institute</span>
        <span class="timeline-period">Apr. 2025 – Present</span>
      </div>

      <p class="timeline-position">
        Researcher, AI &amp; Big Data Team · Seoul, Republic of Korea
      </p>

      <ul class="timeline-description">
        <li>
          Conduct applied research on
          <strong>public-sector AI agents, LLM-based administrative support
          systems, retrieval-augmented generation, and small language model
          adoption strategies</strong>.
        </li>
        <li>
          Develop data-driven methodologies for
          <strong>urban safety, geospatial risk analysis, crime prediction,
          and public safety policy</strong>.
        </li>
        <li>
          Contribute to AI-enabled crime prevention systems, including
          online grooming detection, stalking-risk response, and intelligent
          public protection services.
        </li>
        <li>
          Support international smart-city research and urban safety
          initiatives, including public safety data analysis and
          CPTED-oriented projects for Niterói, Brazil.
        </li>
      </ul>
    </article>

    <article class="timeline-item">
      <div class="timeline-heading">
        <span class="timeline-organization">NCSOFT</span>
        <span class="timeline-period">Jun. 2022 – Sep. 2022</span>
      </div>

      <p class="timeline-position">
        Research Assistant, Language AI Team · Seongnam, Republic of Korea
      </p>

      <ul class="timeline-description">
        <li>
          Conducted research on
          <strong>Aspect-Based Sentiment Analysis</strong>
          and constructed task-specific annotated datasets.
        </li>
        <li>
          Developed named entity recognition and sentiment-analysis resources
          for financial, sports, and English-language news.
        </li>
        <li>
          Curated question-answering datasets for persona-based
          conversational agents.
        </li>
      </ul>
    </article>
  </section>

  <section>
    <h2>Education</h2>

    <article class="timeline-item">
      <div class="timeline-heading">
        <span class="timeline-organization">Sungkyunkwan University</span>
        <span class="timeline-period">Mar. 2023 – Feb. 2025</span>
      </div>

      <p class="timeline-position">
        M.S. in Applied Artificial Intelligence · Seoul, Republic of Korea
      </p>

      <ul class="timeline-description">
        <li>
          Advisor: Jinyoung Han
        </li>
        <li>
          Thesis:
          <strong>
            Developing a Draw-A-Person-in-the-Rain Assessment System
            Using a Multimodal Large Language Model
          </strong>

          <div class="publication-links">
            <a href="http://www.dcollection.net/handler/skku/000000181571">
              [Thesis]
            </a>
          </div>
        </li>
      </ul>
    </article>

    <article class="timeline-item">
      <div class="timeline-heading">
        <span class="timeline-organization">Sangmyung University</span>
        <span class="timeline-period">Mar. 2019 – Feb. 2023</span>
      </div>

      <p class="timeline-position">
        B.S. in Human-Centered Artificial Intelligence<br>
        Double Major in Applied Artificial Intelligence · Seoul, Republic of Korea
      </p>
    </article>
  </section>

  <section>
    <h2>Publications</h2>

    <h3>Journal Articles</h3>

    <article class="publication">
      <p class="publication-title">
        Machine Learning-Based Depression Screening Model from
        Pre-Drawn Structured Mandala Colorings
      </p>

      <p class="publication-authors">
        Se-Ryun Park<sup>†</sup>, Jonghan Kim<sup>†</sup>, Ujin Jeon,
        <strong>Chaehee Park</strong>, Sang-Shin Lee,
        Jinyoung Han<sup>*</sup>, and Yu-Jung Cha<sup>*</sup>
      </p>

      <p class="publication-venue">
        <em>Current Psychology</em>, 2026.
      </p>

      <div class="publication-meta">
        <span class="tag tag-journal">[SSCI]</span>
        <span class="tag tag-journal">[JCR 2025 IF 2.7]</span>

        <!--
        <span class="publication-links">
          <a href="PAPER_URL">[Paper]</a>
          <a href="DOI_URL">[DOI]</a>
        </span>
        -->
      </div>
    </article>

    <article class="publication">
      <p class="publication-title">
        Developing an AI-based Explainable Expert Support System
        for Art Therapy
      </p>

      <p class="publication-authors">
        Jiwon Kang<sup>†</sup>, Jiwon Kim<sup>†</sup>,
        Migyeong Yang<sup>†</sup>, <strong>Chaehee Park<sup>†</sup></strong>,
        Taeeun Kim, Hayeon Song, and Jinyoung Han<sup>*</sup>
      </p>

      <p class="publication-venue">
        <em>ACM Transactions on Interactive Intelligent Systems</em>,
        14(4), 1–23, 2025.
      </p>

      <div class="publication-meta">
        <span class="tag tag-journal">[SCIE]</span>
        <span class="tag tag-author">[Equal Contribution]</span>

        <span class="publication-links">
          <a href="https://dl.acm.org/doi/pdf/10.1145/3689649">
            [Paper]
          </a>
          <a href="https://doi.org/10.1145/3689649">
            [DOI]
          </a>
        </span>
      </div>
    </article>

    <h3>International Conference Papers</h3>

    <article class="publication">
      <p class="publication-title">
        BetaDAPR: An AI-based Expert Support System for Art Therapists
        with Qualitative and Quantitative Assistance
      </p>

      <p class="publication-authors">
        Migyeong Yang, <strong>Chaehee Park</strong>, Hyunseon Won,
        Taeeun Kim, Hayeon Song, and Jinyoung Han<sup>*</sup>
      </p>

      <p class="publication-venue">
        <em>
          The 29th ACM Conference on Computer-Supported Cooperative Work
          and Social Computing (CSCW)
        </em>,
        2026.
      </p>

      <div class="publication-meta">
        <span class="tag tag-conference">[CSCW 2026]</span>

        <!--
        <span class="publication-links">
          <a href="PAPER_URL">[Paper]</a>
          <a href="PROJECT_URL">[Project]</a>
          <a href="CODE_URL">[Code]</a>
        </span>
        -->
      </div>
    </article>

    <article class="publication">
      <p class="publication-title">
        CheckDAPR: An MLLM-based Sketch Analysis System for
        Draw-A-Person-in-the-Rain Assessments
      </p>

      <p class="publication-authors">
        <strong>Chaehee Park<sup>†</sup></strong>,
        Migyeong Yang<sup>†</sup>, Taeeun Kim, Hayeon Song,
        and Jinyoung Han<sup>*</sup>
      </p>

      <p class="publication-venue">
        <em>
          ACM International Conference on Information and Knowledge
          Management (CIKM)
        </em>,
        2025.
      </p>

      <div class="publication-meta">
        <span class="tag tag-author">[Co-First Author]</span>

        <span class="publication-links">
          <!-- <a href="PAPER_URL">[Paper]</a> -->
          <a href="https://github.com/DSAIL-SKKU/CheckDAPR">
            [Code]
          </a>
        </span>
      </div>
    </article>

    <article class="publication">
      <p class="publication-title">
        PracticeDAPR: An AI-based Education-Supported System
        for Art Therapy
      </p>

      <p class="publication-authors">
        Migyeong Yang, <strong>Chaehee Park</strong>, Jiwon Kang,
        Jiwon Kim, Taeeun Kim, Hayeon Song, and Jinyoung Han<sup>*</sup>
      </p>

      <p class="publication-venue">
        <em>
          ACM Conference on Computer-Supported Cooperative Work
          and Social Computing (CSCW)
        </em>,
        2025.
      </p>

      <div class="publication-meta">
        <span class="tag tag-conference">[CSCW 2025]</span>

        <span class="publication-links">
          <a href="https://dl.acm.org/doi/10.1145/3711112">
            [Paper]
          </a>
          <a href="https://doi.org/10.1145/3711112">
            [DOI]
          </a>
        </span>
      </div>
    </article>

    <article class="publication">
      <p class="publication-title">
        SceneDAPR: A Scene-Level Free-Hand Drawing Dataset for
        Web-based Psychological Drawing Assessment
      </p>

      <p class="publication-authors">
        Jiwon Kang, Jiwon Kim, Migyeong Yang,
        <strong>Chaehee Park</strong>, Taeeun Kim, Hayeon Song,
        and Jinyoung Han<sup>*</sup>
      </p>

      <p class="publication-venue">
        <em>Proceedings of the ACM Web Conference (WWW)</em>, 2024.
      </p>

      <div class="publication-meta">
        <span class="tag tag-conference">[WWW 2024]</span>

        <span class="publication-links">
          <a href="https://dl.acm.org/doi/pdf/10.1145/3589334.3648150">
            [Paper]
          </a>
          <a href="https://github.com/DSAIL-SKKU/SceneDAPR">
            [Code]
          </a>
        </span>
      </div>
    </article>

    <h3>Domestic Conference Papers</h3>

    <article class="publication">
      <p class="publication-title">
        A Spatiotemporal Prediction Model for Vehicle-Related Crime
        Using Urban Public Safety Data
      </p>

      <p class="publication-authors">
        <strong>Chaehee Park</strong>, Juncheol Kim<sup>*</sup>
      </p>

      <p class="publication-venue">
        <em>
          2026 Summer Conference of the Korean Institute of Broadcast
          and Media Engineers (KIBME)
        </em>,
        Jun. 20, 2026.
      </p>

      <div class="publication-meta">
        <span class="tag tag-author">[First Author]</span>
        <span class="tag tag-language">[Paper in Korean]</span>

        <!--
        <span class="publication-links">
          <a href="PAPER_URL">[Paper]</a>
          <a href="CODE_URL">[Code]</a>
        </span>
        -->
      </div>
    </article>

    <article class="publication">
      <p class="publication-title">
        A Feasibility Study of an Automated Barrier-Free Park Assessment
        Framework Using Geospatial Information and Computer Vision
      </p>

      <p class="publication-authors">
        <strong>Chaehee Park</strong>, Jeongok Kim<sup>*</sup>
      </p>

      <p class="publication-venue">
        <em>
          2025 Annual Conference of the Korean Society of Civil Engineers
          (KSCE)
        </em>,
        Nov. 13, 2025.
      </p>

      <div class="publication-meta">
        <span class="tag tag-author">[First Author]</span>
        <span class="tag tag-language">[Paper in Korean]</span>

        <!--
        <span class="publication-links">
          <a href="PAPER_URL">[Paper]</a>
          <a href="CODE_URL">[Code]</a>
        </span>
        -->
      </div>
    </article>

    <article class="publication">
      <p class="publication-title">
        A Study on an Ensemble Model for Predicting Prompts
        from Images Generated by Diffusion Models
      </p>

      <p class="publication-authors">
        <strong>Chaehee Park</strong>, Migyeong Yang,
        Jiwon Kim, et al.
      </p>

      <p class="publication-venue">
        <em>
          2023 Summer Conference of the Korean Institute of Broadcast
          and Media Engineers (KIBME)
        </em>,
        Jeju, Republic of Korea, Jun. 2023.
      </p>

      <div class="publication-meta">
        <span class="tag tag-author">[First Author]</span>
        <span class="tag tag-language">[Paper in Korean]</span>

        <!--
        <span class="publication-links">
          <a href="PAPER_URL">[Paper]</a>
        </span>
        -->
      </div>
    </article>

    <article class="publication">
      <p class="publication-title">
        On Deep Generative Models Explaining Rationales
        for Emotionally Supportive Conversations
      </p>

      <p class="publication-authors">
        Eunhye Jeong<sup>†</sup>,
        <strong>Chaehee Park<sup>†</sup></strong>,
        Hyejin Hong, et al.
      </p>

      <p class="publication-venue">
        <em>
          2022 Fall Conference of the Korean Society for Emotion
          and Sensibility (KOSES)
        </em>,
        Busan, Republic of Korea, Oct. 2022.
      </p>

      <div class="publication-meta">
        <span class="tag tag-author">[Co-First Author]</span>
        <span class="tag tag-language">[Paper in Korean]</span>

        <!--
        <span class="publication-links">
          <a href="PAPER_URL">[Paper]</a>
        </span>
        -->
      </div>
    </article>

    <p class="publication-note">
      <sup>†</sup> Equal contribution.
      <sup>*</sup> Corresponding author.
    </p>
  </section>

  <section>
    <h2>Academic Service</h2>

    <ul class="profile-list">
      <li>
        <strong>Reviewer</strong>,
        <em>
          ACM CHI Conference on Human Factors in Computing Systems —
          Posters
        </em>,
        2026
      </li>
      <li>
        <strong>Reviewer</strong>,
        <em>Cognitive Processing</em>,
        2026
      </li>
    </ul>
  </section>

  <section>
    <h2>Teaching Experience</h2>

    <article class="timeline-item">
      <div class="timeline-heading">
        <span class="timeline-organization">Sungkyunkwan University</span>
        <span class="timeline-period">Summer 2023</span>
      </div>

      <p class="timeline-position">Teaching Assistant</p>

      <ul class="timeline-description">
        <li>Undergraduate Research Program</li>
      </ul>
    </article>

    <article class="timeline-item">
      <div class="timeline-heading">
        <span class="timeline-organization">Sangmyung University</span>
        <span class="timeline-period">2021 – 2022</span>
      </div>

      <p class="timeline-position">Teaching Assistant</p>

      <ul class="timeline-description">
        <li>
          Computational Thinking and Understanding Data, Spring 2021
        </li>
        <li>
          Algorithms and Game Content, Fall 2021
        </li>
        <li>
          Computational Thinking and Understanding Data, Spring 2022
        </li>
      </ul>
    </article>
  </section>

</main>
