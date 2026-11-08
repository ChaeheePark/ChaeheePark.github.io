
<style>
:root {
  --profile-text: #2b3648;
  --profile-heading: #14264a;
  --profile-muted: #66748a;
  --profile-border: #dce5f2;
  --profile-background: #f6f9ff;
  --profile-surface: #ffffff;
  --profile-primary: #315fd6;
  --profile-primary-dark: #2448a6;
  --profile-secondary: #7357d9;
  --profile-accent: #0f9f9a;
  --profile-link: #2d5bd1;
  --profile-shadow: 0 10px 28px rgba(35, 62, 120, 0.08);
  --profile-shadow-hover: 0 14px 34px rgba(35, 62, 120, 0.14);
}

/* ---------- Page ---------- */

.profile-page {
  max-width: 900px;
  margin: 0 auto;
  padding: 0 0.35rem 3rem;
  color: var(--profile-text);
  font-family:
    Inter, Pretendard, -apple-system, BlinkMacSystemFont,
    "Segoe UI", sans-serif;
  font-size: 16px;
  line-height: 1.72;
}

.profile-page * {
  box-sizing: border-box;
}

.profile-page a {
  color: var(--profile-link);
  text-decoration: none;
  text-underline-offset: 0.16em;
}

.profile-page a:hover {
  color: var(--profile-primary-dark);
  text-decoration: underline;
}

.profile-page section {
  scroll-margin-top: 1.5rem;
}

.profile-page h2 {
  position: relative;
  margin: 3.25rem 0 1.45rem;
  padding: 0 0 0.65rem 1rem;
  border-bottom: 2px solid #e5ebf5;
  color: var(--profile-heading);
  font-size: 1.5rem;
  font-weight: 750;
  letter-spacing: -0.028em;
}

.profile-page h2::before {
  position: absolute;
  top: 0.18rem;
  bottom: 0.78rem;
  left: 0;
  width: 4px;
  border-radius: 999px;
  background: linear-gradient(
    180deg,
    var(--profile-primary) 0%,
    var(--profile-secondary) 100%
  );
  content: "";
}

.profile-page h2::after {
  position: absolute;
  bottom: -2px;
  left: 0;
  width: 86px;
  height: 2px;
  background: linear-gradient(
    90deg,
    var(--profile-primary) 0%,
    var(--profile-secondary) 100%
  );
  content: "";
}

.profile-page h3 {
  margin: 2.15rem 0 1.1rem;
  color: var(--profile-primary-dark);
  font-size: 1.1rem;
  font-weight: 750;
  letter-spacing: -0.018em;
}

/* ---------- Header ---------- */

.profile-header {
  position: relative;
  overflow: hidden;
  margin: 1rem 0 2.4rem;
  padding: 1.65rem 1.8rem;
  border: 1px solid #d9e3f7;
  border-radius: 18px;
  background:
    radial-gradient(circle at 92% 14%, rgba(115, 87, 217, 0.14), transparent 34%),
    linear-gradient(135deg, #eef4ff 0%, #f7f3ff 100%);
  box-shadow: var(--profile-shadow);
}

.profile-header::before {
  position: absolute;
  top: 0;
  right: 0;
  left: 0;
  height: 5px;
  background: linear-gradient(
    90deg,
    var(--profile-primary) 0%,
    var(--profile-secondary) 58%,
    var(--profile-accent) 100%
  );
  content: "";
}

.profile-role {
  margin: 0 0 0.6rem;
  color: var(--profile-heading);
  font-size: 1.32rem;
  font-weight: 780;
  letter-spacing: -0.022em;
}

.profile-affiliation {
  margin: 0;
  color: #4d5d74;
  font-size: 0.98rem;
  line-height: 1.7;
}

.profile-affiliation a {
  color: var(--profile-primary-dark);
  font-weight: 700;
}

.profile-contact {
  margin: 0.9rem 0 0;
  color: var(--profile-muted);
  font-size: 0.91rem;
}

.profile-contact a {
  font-weight: 650;
}

.profile-updated {
  margin: 0.5rem 0 0;
  color: #7f8ca0;
  font-size: 0.8rem;
}

/* ---------- Introduction ---------- */

.profile-introduction {
  position: relative;
  margin: 1.8rem 0 2.5rem;
  padding: 1.35rem 1.5rem;
  border: 1px solid #dbe6f5;
  border-left: 5px solid var(--profile-primary);
  border-radius: 12px;
  background: linear-gradient(135deg, #fbfdff 0%, #f3f7ff 100%);
  box-shadow: 0 7px 20px rgba(35, 62, 120, 0.06);
}

.profile-introduction p {
  margin: 0;
  color: #38465a;
  line-height: 1.78;
}

.profile-introduction strong {
  color: var(--profile-primary-dark);
}

/* ---------- Lists ---------- */

.profile-list {
  margin: 0;
  padding-left: 1.35rem;
}

.profile-list li {
  margin-bottom: 0.52rem;
}

.profile-list li::marker {
  color: var(--profile-primary);
}

/* ---------- Experience and Education ---------- */

.timeline-item {
  position: relative;
  margin-bottom: 1.35rem;
  padding: 1.18rem 1.28rem;
  border: 1px solid var(--profile-border);
  border-left: 4px solid var(--profile-primary);
  border-radius: 12px;
  background: var(--profile-surface);
  box-shadow: 0 6px 18px rgba(35, 62, 120, 0.055);
  transition:
    transform 0.18s ease,
    box-shadow 0.18s ease,
    border-color 0.18s ease;
}

.timeline-item:hover {
  border-color: #c8d6ef;
  box-shadow: var(--profile-shadow-hover);
  transform: translateY(-2px);
}

.timeline-heading {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  gap: 0.45rem 1rem;
}

.timeline-organization {
  color: var(--profile-heading);
  font-size: 1.06rem;
  font-weight: 760;
}

.timeline-organization a {
  color: inherit;
}

.timeline-period {
  display: inline-block;
  padding: 0.2rem 0.55rem;
  border: 1px solid #d7e2fa;
  border-radius: 999px;
  background: #edf3ff;
  color: var(--profile-primary-dark);
  font-size: 0.79rem;
  font-weight: 700;
  white-space: nowrap;
}

.timeline-position {
  margin: 0.35rem 0 0.72rem;
  color: #59697f;
  font-size: 0.94rem;
  font-weight: 600;
}

.timeline-description {
  margin: 0;
  padding-left: 1.25rem;
}

.timeline-description li {
  margin-bottom: 0.46rem;
}

.timeline-description li::marker {
  color: var(--profile-secondary);
}

/* ---------- Applied Research Projects ---------- */

.project-group {
  margin-bottom: 2.5rem;
}

.project-item {
  position: relative;
  overflow: hidden;
  margin-bottom: 1.08rem;
  padding: 1.12rem 1.2rem 1.08rem;
  border: 1px solid var(--profile-border);
  border-radius: 13px;
  background: var(--profile-surface);
  box-shadow: 0 6px 18px rgba(35, 62, 120, 0.055);
  transition:
    transform 0.18s ease,
    box-shadow 0.18s ease,
    border-color 0.18s ease;
}

.project-item::before {
  position: absolute;
  top: 0;
  right: 0;
  left: 0;
  height: 3px;
  background: linear-gradient(
    90deg,
    var(--profile-primary) 0%,
    var(--profile-secondary) 70%,
    var(--profile-accent) 100%
  );
  content: "";
}

.project-item:hover {
  border-color: #c8d6ef;
  box-shadow: var(--profile-shadow-hover);
  transform: translateY(-2px);
}

.project-title {
  margin: 0;
  color: var(--profile-heading);
  font-size: 1rem;
  font-weight: 760;
  line-height: 1.55;
}

.project-subtitle {
  margin: 0.16rem 0 0;
  color: #718097;
  font-size: 0.83rem;
  line-height: 1.55;
}

.project-description {
  margin: 0.55rem 0 0;
  color: #435167;
  font-size: 0.92rem;
  line-height: 1.67;
}

.project-meta {
  margin-top: 0.64rem;
}

.tag-report {
  background: #e6efff;
  color: #264fba;
}

.tag-project {
  background: #f0ebff;
  color: #5c43b7;
}

.tag-current {
  background: #e4f7f4;
  color: #087a76;
}

/* ---------- Publications ---------- */

.publication {
  margin-bottom: 1.15rem;
  padding: 1rem 1.14rem;
  border: 1px solid #e1e7f1;
  border-left: 4px solid var(--profile-secondary);
  border-radius: 0 11px 11px 0;
  background: #fcfdff;
  transition:
    background-color 0.18s ease,
    border-color 0.18s ease,
    transform 0.18s ease;
}

.publication:hover {
  border-color: #d2dcef;
  background: #f7f9ff;
  transform: translateX(2px);
}

.publication-title {
  margin: 0 0 0.24rem;
  color: var(--profile-heading);
  font-size: 1rem;
  font-weight: 760;
  line-height: 1.55;
}

.publication-authors {
  margin: 0 0 0.18rem;
  color: #3f4d61;
  font-size: 0.92rem;
  line-height: 1.56;
}

.publication-authors strong {
  color: var(--profile-primary-dark);
}

.publication-venue {
  margin: 0;
  color: #67768b;
  font-size: 0.9rem;
  line-height: 1.55;
}

.publication-meta {
  margin-top: 0.48rem;
}

/* ---------- Tags ---------- */

.tag {
  display: inline-block;
  margin: 0.12rem 0.24rem 0.12rem 0;
  padding: 0.16rem 0.52rem;
  border: 1px solid transparent;
  border-radius: 999px;
  font-size: 0.7rem;
  font-weight: 750;
  line-height: 1.5;
}

.tag-journal {
  border-color: #cadcff;
  background: #e8f1ff;
  color: #244fae;
}

.tag-author {
  border-color: #ffd8c4;
  background: #fff0e8;
  color: #a44920;
}

.tag-language {
  border-color: #dbe2ea;
  background: #f1f4f8;
  color: #586779;
}

.tag-conference {
  border-color: #cce9df;
  background: #e8f7f2;
  color: #19705d;
}

/* ---------- Publication Links ---------- */

.publication-links {
  display: inline-block;
  margin: 0.1rem 0 0;
}

.publication-links a {
  display: inline-block;
  margin: 0.12rem 0.24rem 0.12rem 0;
  padding: 0.17rem 0.52rem;
  border: 1px solid #bdcdef;
  border-radius: 6px;
  background: #ffffff;
  color: var(--profile-primary-dark);
  font-size: 0.71rem;
  font-weight: 750;
  line-height: 1.55;
  text-decoration: none;
  transition:
    background-color 0.15s ease,
    border-color 0.15s ease,
    color 0.15s ease,
    transform 0.15s ease;
}

.publication-links a:hover {
  border-color: var(--profile-primary);
  background: var(--profile-primary);
  color: #ffffff;
  text-decoration: none;
  transform: translateY(-1px);
}

/* ---------- Footnote ---------- */

.publication-note {
  margin-top: 1.45rem;
  padding: 0.65rem 0.8rem;
  border-radius: 8px;
  background: var(--profile-background);
  color: #748197;
  font-size: 0.8rem;
}

/* ---------- Responsive ---------- */

@media screen and (max-width: 640px) {
  .profile-page {
    padding: 0 0.1rem 2rem;
    font-size: 15px;
  }

  .profile-header {
    padding: 1.35rem 1.2rem;
    border-radius: 14px;
  }

  .profile-role {
    font-size: 1.16rem;
  }

  .profile-page h2 {
    margin-top: 2.8rem;
    font-size: 1.36rem;
  }

  .timeline-heading {
    display: block;
  }

  .timeline-period {
    margin-top: 0.4rem;
  }

  .profile-introduction {
    padding: 1.12rem 1.15rem;
  }

  .timeline-item,
  .project-item,
  .publication {
    padding-right: 1rem;
    padding-left: 1rem;
  }
}

@media (prefers-reduced-motion: reduce) {
  .timeline-item,
  .project-item,
  .publication,
  .publication-links a {
    transition: none;
  }
}
</style><main class="profile-page">  <header class="profile-header">
    <p class="profile-role">
      Applied AI Researcher · Large Language Models · Multimodal Intelligence · Trustworthy AI
    </p>
