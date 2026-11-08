---
layout: default
title: Chaehee Park
description: AI Researcher
last_modified_at: 2026-11-08
---

<style>
:root {
  --text: #24303f;
  --heading: #172033;
  --muted: #6b7788;
  --border: #e5eaf0;
  --bg-soft: #f8fafc;
  --link: #29557a;
}

.profile-page {
  max-width: 860px;
  margin: 0 auto;
  color: var(--text);
  font-size: 16px;
  line-height: 1.72;
}

.profile-page * {
  box-sizing: border-box;
}

.profile-page a {
  color: var(--link);
  text-decoration: none;
}

.profile-page a:hover {
  text-decoration: underline;
}

.profile-page h1 {
  margin: 0 0 0.4rem;
  color: var(--heading);
  font-size: 2rem;
  font-weight: 750;
  letter-spacing: -0.03em;
}

.profile-page h2 {
  margin: 2.8rem 0 1.1rem;
  padding-bottom: 0.45rem;
  border-bottom: 1px solid var(--border);
  color: var(--heading);
  font-size: 1.35rem;
  font-weight: 700;
  letter-spacing: -0.02em;
}

.profile-page h3 {
  margin: 1.8rem 0 0.7rem;
  color: var(--heading);
  font-size: 1.02rem;
  font-weight: 700;
}

.hero {
  display: grid;
  grid-template-columns: 180px 1fr;
  gap: 1.5rem;
  align-items: center;
  margin: 0.8rem 0 2.2rem;
  padding: 0 0 1.4rem;
  border-bottom: 1px solid var(--border);
}

.hero-photo {
  width: 180px;
  height: 180px;
  border-radius: 18px;
  object-fit: cover;
  object-position: center 42%;
  box-shadow: 0 8px 24px rgba(15, 23, 42, 0.08);
}

.hero-role {
  margin: 0 0 0.45rem;
  color: var(--heading);
  font-size: 1rem;
  font-weight: 650;
}

.hero-meta {
  margin: 0;
  color: var(--muted);
  font-size: 0.95rem;
}

.hero-intro {
  margin: 0.9rem 0 0;
  color: #3d4958;
}

.updated {
  margin-top: 0.7rem;
  color: #8b94a2;
  font-size: 0.82rem;
}

.clean-list {
  margin: 0;
  padding-left: 1.2rem;
}

.clean-list li {
  margin-bottom: 0.45rem;
}

.timeline-item,
.report-item,
.publication {
  margin-bottom: 1.4rem;
}

.timeline-head {
  display: flex;
  flex-wrap: wrap;
  align-items: baseline;
  justify-content: space-between;
  gap: 0.4rem 1rem;
}

.timeline-org {
  color: var(--heading);
  font-weight: 700;
}

.timeline-period {
  color: var(--muted);
  font-size: 0.9rem;
  white-space: nowrap;
}

.timeline-role {
  margin: 0.18rem 0 0.45rem;
  color: #516072;
  font-size: 0.94rem;
}

.timeline-item ul {
  margin: 0;
  padding-left: 1.2rem;
}

.report-title,
.pub-title {
  margin: 0 0 0.14rem;
  color: var(--heading);
  font-size: 1rem;
  font-weight: 700;
  line-height: 1.55;
}

.report-sub,
.pub-authors,
.pub-venue {
  margin: 0;
  color: #526173;
  font-size: 0.93rem;
}

.report-desc {
  margin: 0.4rem 0 0;
  color: #3d4958;
}

.link-row {
  margin-top: 0.38rem;
}

.link-row a {
  display: inline-block;
  margin: 0.15rem 0.45rem 0.15rem 0;
  font-size: 0.82rem;
  font-weight: 600;
}

.two-col {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 0.9rem 1.4rem;
}

.note {
  margin-top: 0.9rem;
  color: #7a8595;
  font-size: 0.82rem;
}

@media (max-width: 700px) {
  .hero {
    grid-template-columns: 1fr;
  }

  .hero-photo {
    width: 150px;
    height: 150px;
  }

  .two-col {
    grid-template-columns: 1fr;
  }

  .timeline-head {
    display: block;
  }

  .timeline-period {
    display: block;
    margin-top: 0.15rem;
  }
}
</style>

<main class="profile-page">

  <header class="hero">
    <img class="hero-photo" src="./chaehee-profile.jpg" alt="Chaehee Park profile photo">

    <div>
      <h1>Chaehee Park</h1>
      <p class="hero-role">AI Researcher</p>
      <p class="hero-meta">
        Researcher, 3rd Technology Research Institute · Seoul Research Division<br>
        <a href="https://www.add.re.kr/">Agency for Defense Development (ADD)</a> · Seoul, Republic of Korea
      </p>
      <p class="hero-intro">
        I am an AI researcher working on large language models, multimodal AI,
        retrieval-augmented generation, and trustworthy AI systems. My background
        spans both research and applied public-sector projects, with experience in
        policy AI, digital-safety systems, urban analytics, and human-centered AI.
      </p>
      <p class="updated">Last updated: November 8, 2026</p>
    </div>
  </header>

  <section>
    <h2>Research Interests</h2>
    <ul class="clean-list">
      <li>Large Language Models, Retrieval-Augmented Generation, and Agentic AI</li>
      <li>Multimodal AI and Human–AI Interaction</li>
      <li>Trustworthy AI, Evaluation, Governance, and Responsible Deployment</li>
      <li>AI for Public-Sector and Mission-Oriented Systems</li>
    </ul>
  </section>

  <section>
    <h2>Professional Experience</h2>

    <article class="timeline-item">
      <div class="timeline-head">
        <span class="timeline-org"><a href="https://www.add.re.kr/">Agency for Defense Development (ADD)</a></span>
        <span class="timeline-period">Oct. 2026 – Present</span>
      </div>
      <p class="timeline-role">Researcher, 3rd Technology Research Institute · Seoul Research Division</p>
      <ul>
        <li>Conduct research as a member of the 3rd Technology Research Institute at ADD.</li>
        <li>Focus on AI systems including large language models, multimodal AI, and trustworthy deployment.</li>
      </ul>
    </article>

    <article class="timeline-item">
      <div class="timeline-head">
        <span class="timeline-org"><a href="https://www.si.re.kr/index.do">The Seoul Institute</a></span>
        <span class="timeline-period">Apr. 2025 – Sep. 2026</span>
      </div>
      <p class="timeline-role">Researcher, AI &amp; Big Data Team · Seoul, Republic of Korea</p>
      <ul>
        <li>Worked on AI transformation, public-sector AI strategy, and institutional adoption of LLM, RAG, and agent-based systems.</li>
        <li>Contributed to digital-crime prevention, AI-enabled public safety, urban analytics, and international smart-city collaboration projects.</li>
        <li>Co-authored official reports on AI-assisted policy research, Seoul-specific AI services, and AI capability standards for public officials.</li>
      </ul>
    </article>

    <article class="timeline-item">
      <div class="timeline-head">
        <span class="timeline-org">NCSOFT</span>
        <span class="timeline-period">Jun. 2022 – Sep. 2022</span>
      </div>
      <p class="timeline-role">Research Assistant, Language AI Team · Seongnam, Republic of Korea</p>
      <ul>
        <li>Conducted research on aspect-based sentiment analysis and curated task-specific datasets.</li>
        <li>Developed resources for named entity recognition, sentiment analysis, and QA datasets.</li>
      </ul>
    </article>
  </section>

  <section>
    <h2>Selected Public-Sector AI Reports</h2>

    <article class="report-item">
      <p class="report-title">Enhancing the Use of Policy Research through AI Technologies</p>
      <p class="report-sub">AI 기술 기반 정책연구 활용도 증진방안</p>
      <p class="report-desc">Proposed a RAG-based framework for converting institutional research assets into traceable, evidence-grounded support for policy research.</p>
      <p class="link-row"><a href="https://www.si.re.kr/bbs/view.do?key=2024100039&amp;pstSn=2601260008">Official Report</a></p>
    </article>

    <article class="report-item">
      <p class="report-title">Strategies for Activating Seoul-Specific AI Administrative Services</p>
      <p class="report-sub">서울시 맞춤형 AI 행정서비스 활성화 방안</p>
      <p class="report-desc">Analyzed institutional, infrastructural, and regulatory requirements for Seoul-tailored AI administrative services and proposed a phased roadmap.</p>
      <p class="link-row"><a href="https://www.si.re.kr/bbs/view.do?key=2024100039&amp;pstSn=2611030001">Official Report</a></p>
    </article>

    <article class="report-item">
      <p class="report-title">A Staged Competency Standard and Self-Assessment Framework for Strengthening Seoul Public Officials’ AI Capabilities</p>
      <p class="report-sub">서울시 공무원의 AI 활용 역량 강화를 위한 단계별 기준 정립과 자가 진단 체계 연구</p>
      <p class="report-desc">Designed a staged AI competency framework and self-assessment structure for public officials.</p>
      <p class="link-row"><a href="https://www.si.re.kr/bbs/view.do?key=2024100039&amp;pstSn=2610020003">Official Report</a></p>
    </article>
  </section>

  <section>
    <h2>Selected Projects</h2>

    <div class="two-col">
      <div>
        <h3>Public-Sector AI Transformation</h3>
        <ul class="clean-list">
          <li>AI Governance and Public-Sector AI Ethics and Norms</li>
          <li>Research-Innovation sLLM-Based AI Transformation Framework and Roadmap</li>
          <li>AI Agent Framework for Administrative Support at The Seoul Institute</li>
        </ul>

        <h3>Urban Analytics and International Collaboration</h3>
        <ul class="clean-list">
          <li>Deep Learning-Based Personalized Leisure Walking Routes for Improved Park Accessibility</li>
          <li>Urban Safety Data Platform and CPTED Technical Assistance for Niterói, Brazil</li>
        </ul>
      </div>

      <div>
        <h3>AI for Public Safety and Digital Crime Prevention</h3>
        <ul class="clean-list">
          <li>Generative AI-Based Automated Analysis of EMS Activity Reports</li>
          <li>Proactive Response Strategies for Deepfake-Enabled Digital Sexual Crimes in Seoul</li>
          <li>Watcher Bot for Prevention of Online Prostitution and Sexual Exploitation Crimes</li>
          <li>AI-Based Online Grooming Detection and Smart Protection Alert System</li>
          <li>Information System for Seoul’s Online Sexual Exploitation “Safe ON” Center</li>
        </ul>
      </div>
    </div>

    <p class="note">
      Public links are included only where an official report, service page, or project material is publicly available.
    </p>
  </section>

  <section>
    <h2>Education</h2>

    <article class="timeline-item">
      <div class="timeline-head">
        <span class="timeline-org">Sungkyunkwan University</span>
        <span class="timeline-period">Mar. 2023 – Feb. 2025</span>
      </div>
      <p class="timeline-role">M.S. in Applied Artificial Intelligence · Seoul, Republic of Korea</p>
      <ul>
        <li>Advisor: Jinyoung Han</li>
        <li>Thesis: <strong>Developing a Draw-A-Person-in-the-Rain Assessment System Using a Multimodal Large Language Model</strong> — <a href="http://www.dcollection.net/handler/skku/000000181571">Thesis</a></li>
      </ul>
    </article>

    <article class="timeline-item">
      <div class="timeline-head">
        <span class="timeline-org">Sangmyung University</span>
        <span class="timeline-period">Mar. 2019 – Feb. 2023</span>
      </div>
      <p class="timeline-role">B.S. in Human-Centered Artificial Intelligence · Double Major in Applied Artificial Intelligence</p>
    </article>
  </section>

  <section>
    <h2>Publications</h2>

    <h3>Journal Articles</h3>

    <article class="publication">
      <p class="pub-title">Machine Learning-Based Depression Screening Model from Pre-Drawn Structured Mandala Colorings</p>
      <p class="pub-authors">Se-Ryun Park<sup>†</sup>, Jonghan Kim<sup>†</sup>, Ujin Jeon, <strong>Chaehee Park</strong>, Sang-Shin Lee, Jinyoung Han<sup>*</sup>, and Yu-Jung Cha<sup>*</sup></p>
      <p class="pub-venue"><em>Current Psychology</em>, 2026.</p>
      <p class="link-row"><a href="https://link.springer.com/article/10.1007/s12144-026-09822-y">Paper</a> <a href="https://doi.org/10.1007/s12144-026-09822-y">DOI</a></p>
    </article>

    <article class="publication">
      <p class="pub-title">Developing an AI-Based Explainable Expert Support System for Art Therapy</p>
      <p class="pub-authors">Jiwon Kang<sup>†</sup>, Jiwon Kim<sup>†</sup>, Migyeong Yang<sup>†</sup>, <strong>Chaehee Park<sup>†</sup></strong>, Taeeun Kim, Hayeon Song, and Jinyoung Han<sup>*</sup></p>
      <p class="pub-venue"><em>ACM Transactions on Interactive Intelligent Systems</em>, 14(4), 1–23, 2025.</p>
      <p class="link-row"><a href="https://dl.acm.org/doi/10.1145/3689649">Paper</a> <a href="https://doi.org/10.1145/3689649">DOI</a></p>
    </article>

    <h3>International Conference Papers</h3>

    <article class="publication">
      <p class="pub-title">BetaDAPR: An AI-Based Expert Support System for Art Therapists with Qualitative and Quantitative Assistance</p>
      <p class="pub-authors">Migyeong Yang, <strong>Chaehee Park</strong>, Hyunseon Won, Taeeun Kim, Hayeon Song, and Jinyoung Han<sup>*</sup></p>
      <p class="pub-venue"><em>Proceedings of the ACM on Human-Computer Interaction (CSCW)</em>, 2026.</p>
      <p class="link-row"><a href="https://dl.acm.org/doi/10.1145/3816903">Paper</a> <a href="https://doi.org/10.1145/3816903">DOI</a></p>
    </article>

    <article class="publication">
      <p class="pub-title">CheckDAPR: An MLLM-Based Sketch Analysis System for Draw-A-Person-in-the-Rain Assessments</p>
      <p class="pub-authors"><strong>Chaehee Park<sup>†</sup></strong>, Migyeong Yang<sup>†</sup>, Taeeun Kim, Hayeon Song, and Jinyoung Han<sup>*</sup></p>
      <p class="pub-venue"><em>ACM International Conference on Information and Knowledge Management (CIKM)</em>, 2025.</p>
      <p class="link-row"><a href="https://dl.acm.org/doi/10.1145/3746252.3761571">Paper</a> <a href="https://doi.org/10.1145/3746252.3761571">DOI</a> <a href="https://github.com/DSAIL-SKKU/CheckDAPR">Code</a></p>
    </article>

    <article class="publication">
      <p class="pub-title">PracticeDAPR: An AI-Based Education-Supported System for Art Therapy</p>
      <p class="pub-authors">Migyeong Yang, <strong>Chaehee Park</strong>, Jiwon Kang, Jiwon Kim, Taeeun Kim, Hayeon Song, and Jinyoung Han<sup>*</sup></p>
      <p class="pub-venue"><em>Proceedings of the ACM on Human-Computer Interaction (CSCW)</em>, 2025.</p>
      <p class="link-row"><a href="https://dl.acm.org/doi/10.1145/3711112">Paper</a> <a href="https://doi.org/10.1145/3711112">DOI</a></p>
    </article>

    <article class="publication">
      <p class="pub-title">SceneDAPR: A Scene-Level Free-Hand Drawing Dataset for Web-Based Psychological Drawing Assessment</p>
      <p class="pub-authors">Jiwon Kang, Jiwon Kim, Migyeong Yang, <strong>Chaehee Park</strong>, Taeeun Kim, Hayeon Song, and Jinyoung Han<sup>*</sup></p>
      <p class="pub-venue"><em>Proceedings of the ACM Web Conference (WWW)</em>, 2024.</p>
      <p class="link-row"><a href="https://dl.acm.org/doi/10.1145/3589334.3648150">Paper</a> <a href="https://doi.org/10.1145/3589334.3648150">DOI</a> <a href="https://github.com/DSAIL-SKKU/SceneDAPR">Code</a></p>
    </article>

    <h3>Domestic Conference Papers</h3>

    <article class="publication">
      <p class="pub-title">A Spatiotemporal Prediction Model for Vehicle-Related Crime Using Urban Public Safety Data</p>
      <p class="pub-authors"><strong>Chaehee Park</strong>, Junchul Kim<sup>*</sup></p>
      <p class="pub-venue"><em>2026 Summer Conference of the Korean Institute of Broadcast and Media Engineers (KIBME)</em>, Jun. 20, 2026.</p>
    </article>

    <article class="publication">
      <p class="pub-title">A Feasibility Study of an Automated Barrier-Free Park Assessment Framework Using Geospatial Information and Computer Vision</p>
      <p class="pub-authors"><strong>Chaehee Park</strong>, Jeongok Kim<sup>*</sup></p>
      <p class="pub-venue"><em>2025 Annual Conference of the Korean Society of Civil Engineers (KSCE)</em>, Nov. 13, 2025.</p>
    </article>

    <article class="publication">
      <p class="pub-title">A Study on an Ensemble Model for Predicting Prompts from Images Generated by Diffusion Models</p>
      <p class="pub-authors"><strong>Chaehee Park</strong>, Migyeong Yang, Jiwon Kim, et al.</p>
      <p class="pub-venue"><em>2023 Summer Conference of the Korean Institute of Broadcast and Media Engineers (KIBME)</em>, Jun. 2023.</p>
    </article>

    <article class="publication">
      <p class="pub-title">On Deep Generative Models Explaining Rationales for Emotionally Supportive Conversations</p>
      <p class="pub-authors">Eunhye Jeong<sup>†</sup>, <strong>Chaehee Park<sup>†</sup></strong>, Hyejin Hong, et al.</p>
      <p class="pub-venue"><em>2022 Fall Conference of the Korean Society for Emotion and Sensibility (KOSES)</em>, Oct. 2022.</p>
    </article>

    <p class="note"><sup>†</sup> Equal contribution. <sup>*</sup> Corresponding author.</p>
  </section>

  <section>
    <h2>Academic Service</h2>
    <ul class="clean-list">
      <li><strong>Reviewer</strong>, <em>ACM CHI Conference on Human Factors in Computing Systems — Posters</em>, 2026</li>
      <li><strong>Reviewer</strong>, <em>Cognitive Processing</em>, 2026</li>
    </ul>
  </section>

  <section>
    <h2>Teaching Experience</h2>
    <ul class="clean-list">
      <li><strong>Sungkyunkwan University</strong>, Teaching Assistant, Summer 2023</li>
      <li><strong>Sangmyung University</strong>, Teaching Assistant, 2021–2022</li>
    </ul>
  </section>

</main>
