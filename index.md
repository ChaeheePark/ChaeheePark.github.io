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


/* ---------- Applied Research Projects ---------- */

.project-group {
  margin-bottom: 2.35rem;
}

.project-item {
  margin-bottom: 1.15rem;
  padding: 1.05rem 1.15rem;
  border: 1px solid var(--profile-border);
  border-radius: 7px;
  background: #ffffff;
}

.project-title {
  margin: 0;
  color: var(--profile-heading);
  font-size: 0.98rem;
  font-weight: 700;
  line-height: 1.55;
}

.project-subtitle {
  margin: 0.12rem 0 0;
  color: #697586;
  font-size: 0.82rem;
  line-height: 1.55;
}

.project-description {
  margin: 0.52rem 0 0;
  color: #46515f;
  font-size: 0.91rem;
  line-height: 1.65;
}

.project-meta {
  margin-top: 0.55rem;
}

.tag-report {
  background: #eaf2f8;
  color: #244d6a;
}

.tag-project {
  background: #f0f3f7;
  color: #566273;
}

.tag-current {
  background: #edf5ef;
  color: #356044;
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
</style><main class="profile-page">  <header class="profile-header">
    <p class="profile-role">
      Applied AI Researcher · Large Language Models · Multimodal Intelligence · Trustworthy AI
    </p><p class="profile-affiliation">
  Researcher, 3rd Technology Research Institute,<br>
  <a href="https://www.add.re.kr/">Agency for Defense Development (ADD)</a><br>
  Seoul, Republic of Korea
</p>

<!-- Add a preferred public contact email here if desired. -->

<p class="profile-updated">
  Last updated: November 8, 2026
</p>

  </header>  <section class="profile-introduction">
    <p>
      I am a researcher at the
      <strong>Agency for Defense Development (ADD)</strong>, based in Seoul
      within the 3rd Technology Research Institute. My research focuses on
      <strong>
        large language models, multimodal artificial intelligence,
        retrieval-augmented generation, agentic systems, and reliable AI deployment
      </strong>.
      Previously, as a researcher in the AI &amp; Big Data Team at The Seoul Institute,
      I conducted policy-oriented and applied R&amp;D spanning public-sector AI
      transformation, AI-assisted research and administration, urban safety,
      digital crime prevention, and international smart-city collaboration.
    </p>
  </section>  <section>
    <h2>Research Interests</h2><ul class="profile-list">
  <li>
    Large Language Models, Retrieval-Augmented Generation, and Agentic AI
  </li>
  <li>
    Multimodal AI for Psychological Assessment and Human–AI Interaction
  </li>
  <li>
    Trustworthy AI Evaluation, Governance, Safety, and Responsible Deployment
  </li>
  <li>
    AI for Public, Urban-Safety, and Mission-Oriented Systems
  </li>
</ul>

  </section>  <section>
    <h2>Professional Experience</h2><article class="timeline-item">
  <div class="timeline-heading">
    <span class="timeline-organization">
      <a href="https://www.add.re.kr/">Agency for Defense Development (ADD)</a>
    </span>
    <span class="timeline-period">Oct. 2026 – Present</span>
  </div>

  <p class="timeline-position">
    Researcher, 3rd Technology Research Institute · Seoul, Republic of Korea
  </p>

  <ul class="timeline-description">
    <li>
      Serve as a researcher within ADD's 3rd Technology Research Institute,
      based at the Seoul research site.
    </li>
    <li>
      Broader research interests include large language models, multimodal AI,
      retrieval-augmented generation, agentic systems, and trustworthy AI deployment.
    </li>
  </ul>
</article>

<article class="timeline-item">
  <div class="timeline-heading">
    <span class="timeline-organization">
      <a href="https://www.si.re.kr/index.do">The Seoul Institute</a>
    </span>
    <span class="timeline-period">Apr. 2025 – Sep. 2026</span>
  </div>

  <p class="timeline-position">
    Researcher, AI &amp; Big Data Team · Seoul, Republic of Korea
  </p>

  <ul class="timeline-description">
    <li>
      Conducted applied research on public-sector AI transformation,
      including LLM/RAG-based policy-research support, institutional AI agents,
      small language model adoption, and AI governance.
    </li>
    <li>
      Contributed to AI-enabled public-safety and digital-crime prevention
      projects covering EMS activity-report analysis, deepfake-related harms,
      online grooming detection, and integrated victim-support systems.
    </li>
    <li>
      Applied deep learning, geospatial analytics, and data-driven CPTED
      methods to urban park accessibility and international urban-safety projects.
    </li>
    <li>
      Co-authored official policy and issue reports on AI-assisted policy research,
      Seoul-specific AI administrative services, and AI competency standards
      for public officials.
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

  </section>  <section>
    <h2>Selected Public-Sector AI Reports</h2><article class="project-item">
  <p class="project-title">
    Enhancing the Use of Policy Research through AI Technologies
  </p>
  <p class="project-subtitle">
    AI 기술 기반 정책연구 활용도 증진방안
  </p>
  <p class="project-description">
    Proposed a RAG-based framework for converting institutional research assets
    into traceable, evidence-grounded support for policy research, with attention
    to hybrid deployment, data governance, information security, and responsible AI use.
  </p>
  <div class="project-meta">
    <span class="tag tag-report">Issue Report</span>
    <span class="tag tag-author">Co-author</span>
    <span class="tag tag-language">2026</span>
    <span class="publication-links">
      <a href="https://www.si.re.kr/bbs/view.do?key=2024100039&amp;pstSn=2601260008">
        [Official Report]
      </a>
    </span>
  </div>
</article>

<article class="project-item">
  <p class="project-title">
    Strategies for Activating Seoul-Specific AI Administrative Services
  </p>
  <p class="project-subtitle">
    서울시 맞춤형 AI 행정서비스 활성화 방안
  </p>
  <p class="project-description">
    Assessed institutional, infrastructural, data, and regulatory barriers to
    citywide AI adoption; benchmarked domestic and international practices; and
    proposed a phased roadmap for sustainable, citizen-centered AI services.
  </p>
  <div class="project-meta">
    <span class="tag tag-report">Policy Report</span>
    <span class="tag tag-author">Co-author</span>
    <span class="tag tag-language">2026</span>
    <span class="publication-links">
      <a href="https://www.si.re.kr/bbs/view.do?key=2024100039&amp;pstSn=2611030001">
        [Official Report]
      </a>
    </span>
  </div>
</article>

<article class="project-item">
  <p class="project-title">
    A Staged Competency Standard and Self-Assessment Framework for
    Strengthening Seoul Public Officials' AI Capabilities
  </p>
  <p class="project-subtitle">
    서울시 공무원의 AI 활용 역량 강화를 위한 단계별 기준 정립과 자가 진단 체계 연구
  </p>
  <p class="project-description">
    Designed a five-level, five-domain AI competency model and a 50-item
    self-assessment framework linking diagnosis to training, reskilling,
    responsible use, and organization-wide capability development.
  </p>
  <div class="project-meta">
    <span class="tag tag-report">Issue Report</span>
    <span class="tag tag-author">Co-author</span>
    <span class="tag tag-language">2026</span>
    <span class="publication-links">
      <a href="https://www.si.re.kr/bbs/view.do?key=2024100039&amp;pstSn=2610020003">
        [Official Report]
      </a>
    </span>
  </div>
</article>

  </section>  <section>
    <h2>Selected Applied Research &amp; Development Projects</h2><div class="project-group">
  <h3>Public-Sector AI Transformation and Responsible AI</h3>

  <article class="project-item">
    <p class="project-title">
      AI Governance and Public-Sector AI Ethics and Norms
    </p>
    <p class="project-description">
      Investigated governance principles and operational safeguards for
      trustworthy public-sector AI, including accountability, algorithmic bias,
      privacy, safety, transparency, and human oversight.
    </p>
    <div class="project-meta">
      <span class="tag tag-project">Applied Research</span>
      <span class="tag tag-language">The Seoul Institute</span>
    </div>
  </article>

  <article class="project-item">
    <p class="project-title">
      Research-Innovation sLLM-Based AI Transformation Framework and Roadmap
    </p>
    <p class="project-description">
      Contributed to an institutional AI-transformation roadmap combining
      domain-specific small language models, AI-ready research data,
      secure infrastructure, and phased organizational adoption.
    </p>
    <div class="project-meta">
      <span class="tag tag-project">AI Transformation</span>
      <span class="tag tag-language">The Seoul Institute</span>
    </div>
  </article>

  <article class="project-item">
    <p class="project-title">
      AI Agent Framework for Administrative Support at The Seoul Institute
    </p>
    <p class="project-description">
      Designed an AI-agent architecture for knowledge-intensive administrative
      support, including document-grounded question answering, document review,
      and internal regulation guidance.
    </p>
    <div class="project-meta">
      <span class="tag tag-project">AI Agent</span>
      <span class="tag tag-language">RAG</span>
    </div>
  </article>
</div>

<div class="project-group">
  <h3>AI for Public Safety and Digital Crime Prevention</h3>

  <article class="project-item">
    <p class="project-title">
      Generative AI-Based Automated Analysis of EMS Activity Reports
    </p>
    <p class="project-subtitle">
      생성형 AI 기반 구급활동일지 자동 분석을 통한 구급활동 개선방안
    </p>
    <p class="project-description">
      Developed a generative-AI workflow for structuring, summarizing, and
      analyzing EMS activity narratives to improve data quality, operational
      insight, and post-incident review.
    </p>
    <div class="project-meta">
      <span class="tag tag-project">Generative AI</span>
      <span class="tag tag-language">Public Safety</span>
    </div>
  </article>

  <article class="project-item">
    <p class="project-title">
      Proactive Response Strategies for Deepfake-Enabled Digital Sexual Crimes in Seoul
    </p>
    <p class="project-subtitle">
      서울시 딥페이크 관련 디지털 성범죄 선제적 대응 강화방안
    </p>
    <p class="project-description">
      Examined proactive response strategies spanning AI-assisted detection,
      monitoring, victim support, institutional coordination, and policy design.
    </p>
    <div class="project-meta">
      <span class="tag tag-project">Trust &amp; Safety</span>
      <span class="tag tag-language">Digital Crime</span>
    </div>
  </article>

  <article class="project-item">
    <p class="project-title">
      Watcher Bot for Prevention of Online Prostitution and Sexual Exploitation Crimes
    </p>
    <p class="project-description">
      Contributed to an integrated monitoring and prevention system for detecting
      online sexual-exploitation risks and supporting operational response workflows.
    </p>
    <div class="project-meta">
      <span class="tag tag-project">AI Monitoring</span>
      <span class="tag tag-language">Victim Protection</span>
    </div>
  </article>

  <article class="project-item">
    <p class="project-title">
      AI-Based Online Grooming Detection and Smart Protection Alert System
    </p>
    <p class="project-description">
      Developed AI-based detection of grooming patterns and smart alerts for
      early intervention and linkage to counseling, protection, and investigative support.
    </p>
    <div class="project-meta">
      <span class="tag tag-project">Online Grooming Detection</span>
      <span class="tag tag-language">Early Intervention</span>
      <span class="publication-links">
        <a href="https://www.si.re.kr/bbs/view.do?key=2024100192&amp;pstSn=2512020001">
          [Press Release]
        </a>
      </span>
    </div>
  </article>

  <article class="project-item">
    <p class="project-title">
      Information System for Seoul's Online Sexual Exploitation “Safe ON” Center
    </p>
    <p class="project-description">
      Supported information-system planning for an integrated response center
      connecting AI-based risk detection with consultation, emergency intervention,
      and victim-support services.
    </p>
    <div class="project-meta">
      <span class="tag tag-project">Information System</span>
      <span class="tag tag-language">Integrated Support</span>
      <span class="publication-links">
        <a href="https://news.seoul.go.kr/welfare/archives/577282">
          [Service Overview]
        </a>
      </span>
    </div>
  </article>
</div>

<div class="project-group">
  <h3>Urban Analytics and International Collaboration</h3>

  <article class="project-item">
    <p class="project-title">
      Deep Learning-Based Personalized Leisure Walking Routes for Improved Park Accessibility
    </p>
    <p class="project-subtitle">
      딥러닝 기반 개인 맞춤형 레저 보행 경로 추천을 통한 공원 접근성 개선 방안 연구
    </p>
    <p class="project-description">
      Applied deep learning-based streetscape analysis and user-preference-aware
      routing to recommend leisure walking routes that improve experiential access
      to urban parks beyond shortest-distance measures.
    </p>
    <div class="project-meta">
      <span class="tag tag-project">Deep Learning</span>
      <span class="tag tag-language">Geospatial AI</span>
      <span class="publication-links">
        <a href="https://www.si.re.kr/bbs/view.do?key=2024100199&amp;pstSn=2512180001">
          [Forum Materials]
        </a>
      </span>
    </div>
  </article>

  <article class="project-item">
    <p class="project-title">
      Urban Safety Data Platform and CPTED Technical Assistance for Niterói, Brazil
    </p>
    <p class="project-subtitle">
      브라질 니테로이시 도시안전 데이터플랫폼 구축 및 범죄예방환경설계(CPTED) 기술지원
    </p>
    <p class="project-description">
      Supported the development of an urban-safety data platform and data-driven
      CPTED methodology through spatial risk analysis, technical cooperation,
      and international smart-city collaboration.
    </p>
    <div class="project-meta">
      <span class="tag tag-project">Urban Safety</span>
      <span class="tag tag-language">International Collaboration</span>
      <span class="publication-links">
        <a href="https://www.si.re.kr/bbs/list.do?key=2024100196">
          [Project Note]
        </a>
      </span>
    </div>
  </article>
</div>

<p class="publication-note">
  Public links are included only where an official report, project page,
  forum material, service page, or press release is publicly available.
</p>

  </section>  <section>
    <h2>Education</h2><article class="timeline-item">
  <div class="timeline-heading">
    <span class="timeline-organization">
      Sungkyunkwan University
    </span>
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
    <span class="timeline-organization">
      Sangmyung University
    </span>
    <span class="timeline-period">Mar. 2019 – Feb. 2023</span>
  </div>

  <p class="timeline-position">
    B.S. in Human-Centered Artificial Intelligence<br>
    Double Major in Applied Artificial Intelligence ·
    Seoul, Republic of Korea
  </p>
</article>

  </section>  <section>
    <h2>Publications</h2><h3>Journal Articles</h3>

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
    <span class="tag tag-journal">SSCI</span>
    <span class="tag tag-journal">JCR 2025 IF 2.7</span>

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
    Migyeong Yang<sup>†</sup>,
    <strong>Chaehee Park<sup>†</sup></strong>,
    Taeeun Kim, Hayeon Song, and Jinyoung Han<sup>*</sup>
  </p>

  <p class="publication-venue">
    <em>ACM Transactions on Interactive Intelligent Systems</em>,
    14(4), 1–23, 2025.
  </p>

  <div class="publication-meta">
    <span class="tag tag-journal">SCIE</span>
    <span class="tag tag-author">Equal Contribution</span>

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
    <span class="tag tag-conference">CSCW 2026</span>

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
    <span class="tag tag-conference">CIKM 2025</span>
    <span class="tag tag-author">Co-First Author</span>

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
    <span class="tag tag-conference">CSCW 2025</span>

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
    <span class="tag tag-conference">WWW 2024</span>

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
    <strong>Chaehee Park</strong>, Junchul Kim<sup>*</sup>
  </p>

  <p class="publication-venue">
    <em>
      2026 Summer Conference of the Korean Institute of Broadcast
      and Media Engineers (KIBME)
    </em>,
    Jun. 20, 2026.
  </p>

  <div class="publication-meta">
    <span class="tag tag-author">First Author</span>
    <span class="tag tag-language">Paper in Korean</span>

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
    <span class="tag tag-author">First Author</span>
    <span class="tag tag-language">Paper in Korean</span>

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
    <span class="tag tag-author">First Author</span>
    <span class="tag tag-language">Paper in Korean</span>

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
    <span class="tag tag-author">Co-First Author</span>
    <span class="tag tag-language">Paper in Korean</span>

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

  </section>  <section>
    <h2>Academic Service</h2><ul class="profile-list">
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

  </section>  <section>
    <h2>Teaching Experience</h2><article class="timeline-item">
  <div class="timeline-heading">
    <span class="timeline-organization">
      Sungkyunkwan University
    </span>
    <span class="timeline-period">Summer 2023</span>
  </div>

  <p class="timeline-position">
    Teaching Assistant
  </p>

  <ul class="timeline-description">
    <li>Undergraduate Research Program</li>
  </ul>
</article>

<article class="timeline-item">
  <div class="timeline-heading">
    <span class="timeline-organization">
      Sangmyung University
    </span>
    <span class="timeline-period">2021 – 2022</span>
  </div>

  <p class="timeline-position">
    Teaching Assistant
  </p>

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

  </section></main>
