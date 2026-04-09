---
title: OpenISE
layout: hextra-home
---

<style>
@keyframes fadeInUp {
  from { opacity: 0; transform: translateY(24px); }
  to { opacity: 1; transform: translateY(0); }
}
.hero-section {
  position: relative;
  overflow: visible;
  padding: 2rem 0 3rem;
}
.hero-logo-bg {
  position: fixed;
  right: 1rem;
  top: 1rem;
  width: 380px;
  height: 380px;
  opacity: 0.07;
  pointer-events: none;
  z-index: 1;
}
:is(.dark) .hero-logo-bg {
  opacity: 0.05;
  filter: invert(1) brightness(2);
}
@media (min-width: 1024px) {
  .hero-logo-bg { width: 440px; height: 440px; right: 2rem; top: 0.5rem; }
}
@media (min-width: 1280px) {
  .hero-logo-bg { width: 520px; height: 520px; right: 3rem; top: 0rem; }
}
@media (max-width: 768px) {
  .hero-logo-bg { display: none; }
}
.hero-content {
  position: relative;
  z-index: 1;
  animation: fadeInUp 0.8s ease-out;
}
.feature-grid {
  animation: fadeInUp 1s ease-out 0.3s both;
}
</style>

<img src="/images/sysu-logo.svg" alt="" class="hero-logo-bg" aria-hidden="true" />

<div class="not-prose hero-section">

<div class="hero-content" style="max-width: 42rem;">
{{< hextra/hero-badge style="margin-bottom: 0.75rem;" >}}
完全开源，去商业化
{{< /hextra/hero-badge >}}

{{< hextra/hero-headline >}}
OpenISE
课程共享开源计划
{{< /hextra/hero-headline >}}

{{< hextra/hero-subtitle >}}
收录课程资料、作业报告、复习策略与选课指南，<br/>
面向院内同学长期维护，保持公开、可复用、非商业化共享。
{{< /hextra/hero-subtitle >}}

{{< hextra/hero-button text="文档入口" link="/doc" style="margin-top: 1rem; margin-bottom: 1rem; margin-right: 0.75rem; padding: 0.85rem 1.4rem; font-size: 1rem;" >}}
{{< hextra/hero-button text="贡献方式" link="/about/#贡献方式" style="margin-top: 1rem; margin-bottom: 1rem; padding: 0.85rem 1.4rem; font-size: 1rem;" >}}
</div>
</div>

<div class="not-prose feature-grid hx:mt-6 hx:grid hx:grid-cols-1 hx:md:grid-cols-2 hx:gap-4">
{{< hextra/feature-card
  title="开放许可"
  subtitle="站点内容采用 CC BY-SA 4.0 协议，允许传播与改编，但必须署名并保持相同方式共享。"
  icon="scale"
  style="background: radial-gradient(ellipse at 50% 80%, rgba(34, 197, 94, 0.14), hsla(0,0%,100%,0));"
>}}
{{< hextra/feature-card
  title="维护原则"
  subtitle="保持非商业化、可追溯、可审查，资料仅供学习参考，不替代独立完成作业与实验。"
  icon="shield-check"
  style=""
>}}
{{< hextra/feature-card
  title="新闻文档"
  subtitle="一些学长学姐的感言文章记录，文档更新的内容通知，一些重要的有用信息的发布。"
  icon="academic-cap"
  style="background: radial-gradient(ellipse at 50% 80%, rgba(38, 99, 235, 0.14), hsla(0,0%,100%,0));"
>}}
{{< hextra/feature-card
  title="长期建设"
  subtitle="项目以持续积累为目标，优先保证结构清晰、链接稳定和跨学期可扩展性。"
  icon="globe-alt"
  style=""
>}}
</div>
