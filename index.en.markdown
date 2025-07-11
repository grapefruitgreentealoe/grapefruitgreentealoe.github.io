---
layout: resume
title: "Eunsun Namgung Resume"
permalink: /en/
---

<style>
.resume-container {
  display: grid;
  grid-template-columns: 2fr 1fr;
  gap: 32px;
  max-width: 1100px;
  margin: 0 auto;
}
.resume-left, .resume-right {
  background: #fff;
  padding: 24px 24px 0 24px;
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.04);
}
.header-flex {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 16px;
}
.header-info {
  display: flex;
  flex-direction: column;
  gap: 4px;
}
.header-links {
  text-align: right;
  font-size: 0.95em;
}
.bold { font-weight: bold; }
.section-title { font-size: 1.2em; font-weight: bold; margin: 24px 0 8px 0; }
@media (max-width: 900px) {
  .resume-container { grid-template-columns: 1fr; }
  .resume-left, .resume-right { padding: 16px; }
}
.lang-switch {
  display: flex;
  gap: 12px;
  justify-content: flex-end;
  align-items: center;
  margin: 16px 0 12px 0;
}
.lang-btn {
  padding: 6px 18px;
  border-radius: 20px;
  border: 1.5px solid #0074d9;
  background: #fff;
  color: #0074d9;
  font-weight: bold;
  font-size: 1.05em;
  cursor: pointer;
  transition: background 0.2s, color 0.2s;
  text-decoration: none;
}
.lang-btn.selected, .lang-btn:hover {
  background: #0074d9;
  color: #fff;
}
</style>

<div class="header-flex">
  <div class="header-info">
    <h1>Eunsun Namgung</h1>
    <div>Frontend Engineer | Structure-Driven Problem Solver | Rapid Release Advocate</div>
    <div>Seoul, South Korea</div>
  </div>
  <div class="header-links">
    <div><span class="bold">GitHub:</span> <a href="https://github.com/grapefruitgreentealoe" target="_blank">@grapefruitgreentealoe</a></div>
    <div><span class="bold">LinkedIn:</span> <a href="https://www.linkedin.com/in/eunsun-namgung-975391186/" target="_blank">linkedin.com/in/eunsun-namgung-975391186</a></div>
    <div><span class="bold">Blog:</span> <a href="https://velog.io/@grapefruitgreen" target="_blank">velog.io/@grapefruitgreen</a></div>
  </div>
</div>
<div class="resume-container">
  <div class="resume-left">
    <div class="section-title">SUMMARY</div>
    <p>Results-driven Frontend Engineer with a strong focus on scalable architecture and team productivity. Experienced in leading Agile projects, implementing monorepo and design systems, and optimizing CI/CD pipelines. Adept at introducing new technologies, solving complex problems, and fostering effective team communication. Passionate about delivering user-centric products and driving continuous improvement.</p>
    <div class="section-title">EXPERIENCE</div>
    <div>
      <div><span class="bold">ELICE (Frontend Partner)</span> | Apr 2025 – Apr 2025</div>
      <div>Frontend Engineer / Project Manager</div>
      <ul>
        <li>Led onboarding and introduced Epic-Story-Task collaboration structure for a real-time, location-based medical information service (MediNow).</li>
        <li>Set up a monorepo environment using Turborepo and Docker.</li>
        <li>Built and optimized GitLab CI/CD pipeline, reducing deployment time by ~40%.</li>
        <li>Optimized map navigation, decreasing API calls by ~60%.</li>
        <li>Implemented Optimistic UI updates, doubling perceived UX speed and reducing API requests.</li>
        <li>Developed features including hospital favorites, review submissions, and real-time chat.</li>
      </ul>
    </div>
    <div style="margin-top: 12px;">
      <div><span class="bold">DIY KITTEN (Solo Founder)</span> | Jul 2024 – Dec 2024</div>
      <div>Frontend Engineer / Business Planner / Project Manager</div>
      <ul>
        <li>Launched and operated a customization-based handicraft service, including a React-Konva powered design tool for pipe cleaner dolls.</li>
        <li>Developed image-based bead design and animation generator, with CSV-based pattern export.</li>
        <li>Established CI/CD pipeline using GitHub Actions.</li>
        <li>Managed a flea market booth, achieving 100+ user experiences and direct product sales.</li>
      </ul>
    </div>
    <div style="margin-top: 12px;">
      <div><span class="bold">Imweb</span> | Jun 2022 – Mar 2024</div>
      <div>Frontend Engineer</div>
      <ul>
        <li><span class="bold">Order Management Task Force (PHP → React Migration)</span> (Mar 2023 – Dec 2023)
          <ul>
            <li>Redesigned order management system to support product option-based order splitting.</li>
            <li>Revamped order details, payment, and return/refund flows for improved usability and clarity.</li>
            <li>Introduced a design system to ensure UI consistency across the platform.</li>
            <li>Enhanced admin dashboard for comprehensive order flow visibility.</li>
          </ul>
        </li>
        <li><span class="bold">Integration Squad (PHP → React Migration & Monorepo Setup)</span> (Dec 2023 – Mar 2024)
          <ul>
            <li>Automated cache invalidation using GitHub Actions.</li>
            <li>Rebuilt social login and API integration management pages, improving UX and maintainability.</li>
          </ul>
        </li>
        <li><span class="bold">Web Builder Squad & Frontend Team (PHP, JavaScript Maintenance)</span> (Jun 2022 – Jan 2023)
          <ul>
            <li>Renewed designer search page with Intersection Observer for performance optimization.</li>
            <li>Developed emoji asset auto-generation scripts and customized Froala Editor.</li>
          </ul>
        </li>
      </ul>
    </div>
    <div class="section-title">EDUCATION</div>
    <ul>
      <li><span class="bold">Lean Startup Program, Hanyang University Startup Support Group</span> — Certificate, Jul 2024 – Oct 2024</li>
      <li><span class="bold">AI Service Planning & Development Track, ELICE</span> — 2nd Cohort, Jun 2021 – Dec 2021 (Demo Day Excellence Award)</li>
      <li><span class="bold">B.S. in Forest Life Science, Kookmin University</span> — Mar 2016 – Feb 2021<br/>
GPA: 3.29 / 4.5</li>
    </ul>
  </div>
  <div class="resume-right">
    <div class="section-title">SKILLS</div>
    <ul>
      <li><span class="bold">Frontend:</span> React, TypeScript, Vite, Next.js, Zustand, Jotai, React Query, Zod, Tailwind CSS, Shadcn UI, Storybook</li>
      <li><span class="bold">Infrastructure:</span> AWS (EC2, S3, CloudFront, Nginx), GitHub Actions, Docker, GitLab Runner</li>
    </ul>
    <div class="section-title">KEY STRENGTHS</div>
    <ul>
      <li>Led onboarding and introduced Epic-Story-Task collaboration structure</li>
      <li>Improved productivity and quality via CI/CD, monorepo, and design system adoption</li>
      <li>Designed and developed real-time services and customization tools</li>
      <li>Launched a solo startup and iterated products based on direct user feedback</li>
    </ul>
    <div class="section-title">ADDITIONAL ACTIVITIES</div>
    <ul>
      <li>Operated mock interview study group and shared technical seminar learnings weekly.</li>
      <li>Experienced in product-focused thinking and execution through solo startup preparation.</li>
      <li>Strong communication skills for cross-functional collaboration and productivity improvement.</li>
    </ul>
  </div>
</div>
