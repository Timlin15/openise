---
title: OpenISE
layout: hextra-home
---

<div style="display:flex;align-items:center;gap:3.5rem;padding:2.5rem 0 3rem;flex-wrap:wrap;">
  <div style="flex:1;min-width:260px;">
    <span style="display:inline-block;padding:0.2rem 0.9rem;font-size:0.75rem;font-weight:600;background:rgba(37,99,235,0.1);color:#2563eb;border-radius:9999px;margin-bottom:1.5rem;border:1px solid rgba(37,99,235,0.22);">完全开源，去商业化</span>
    <div style="font-size:3.75rem;font-weight:900;line-height:1.05;letter-spacing:-0.03em;">openISE</div>
    <div style="font-size:1.85rem;font-weight:700;margin-top:0.35rem;margin-bottom:1.25rem;opacity:0.82;">课程共享计划</div>
    <div style="font-size:0.88rem;color:#6b7280;line-height:1.75;margin-bottom:2rem;">// 收录课程资料、期末报告、复习策略与选课指南，<br>面向院内同学长期维护，保持公开、可复用、非商业化共享</div>
    <div style="display:flex;gap:0.85rem;flex-wrap:wrap;">
      <a href="/doc" style="display:inline-flex;align-items:center;padding:0.65rem 1.6rem;font-size:0.975rem;font-weight:700;background:#2563eb;color:#fff;border-radius:0.5rem;text-decoration:none;box-shadow:0 2px 10px rgba(37,99,235,0.4);">文档入口</a>
      <a href="/about/#贡献方式" style="display:inline-flex;align-items:center;padding:0.65rem 1.6rem;font-size:0.975rem;font-weight:600;color:inherit;border:1.5px solid rgba(120,120,120,0.28);border-radius:0.5rem;text-decoration:none;">贡献方法</a>
    </div>
    <a href="https://github.com/changyicheng1234/OpenISE" target="_blank" rel="noopener" id="gh-stats-badge" style="display:inline-flex;align-items:center;gap:0;margin-top:1rem;border-radius:0.45rem;overflow:hidden;text-decoration:none;font-size:0.8rem;font-weight:600;border:1px solid rgba(120,120,120,0.25);box-shadow:0 1px 4px rgba(0,0,0,0.07);">
      <span style="display:inline-flex;align-items:center;gap:0.4rem;padding:0.35rem 0.8rem;background:#24292f;color:#fff;">
        <svg height="14" width="14" viewBox="0 0 16 16" fill="currentColor"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"/></svg>
        OpenISE
      </span>
      <span style="display:inline-flex;align-items:center;gap:0.3rem;padding:0.35rem 0.7rem;background:#f6f8fa;color:#24292f;border-left:1px solid rgba(120,120,120,0.2);">
        <svg height="13" width="13" viewBox="0 0 16 16" fill="#e3b341"><path d="M8 .25a.75.75 0 0 1 .673.418l1.882 3.815 4.21.612a.75.75 0 0 1 .416 1.279l-3.046 2.97.719 4.192a.751.751 0 0 1-1.088.791L8 12.347l-3.766 1.98a.75.75 0 0 1-1.088-.79l.72-4.194L.873 6.374a.75.75 0 0 1 .416-1.28l4.21-.611L7.327.668A.75.75 0 0 1 8 .25Z"/></svg>
        <span id="gh-stars">…</span>
      </span>
      <span style="display:inline-flex;align-items:center;gap:0.3rem;padding:0.35rem 0.7rem;background:#f6f8fa;color:#24292f;border-left:1px solid rgba(120,120,120,0.2);">
        <svg height="13" width="13" viewBox="0 0 16 16" fill="#57606a"><path d="M5 5.372v.878c0 .414.336.75.75.75h4.5a.75.75 0 0 0 .75-.75v-.878a2.25 2.25 0 1 1 1.5 0v.878a2.25 2.25 0 0 1-2.25 2.25h-1.5v2.128a2.251 2.251 0 1 1-1.5 0V8.5h-1.5A2.25 2.25 0 0 1 3.5 6.25v-.878a2.25 2.25 0 1 1 1.5 0ZM5 3.25a.75.75 0 1 0-1.5 0 .75.75 0 0 0 1.5 0Zm6.75.75a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5Zm-3 8.75a.75.75 0 1 0-1.5 0 .75.75 0 0 0 1.5 0Z"/></svg>
        <span id="gh-forks">…</span>
      </span>
    </a>
    <script>
      (function() {
        fetch('https://api.github.com/repos/changyicheng1234/OpenISE')
          .then(function(r) { return r.json(); })
          .then(function(d) {
            var s = document.getElementById('gh-stars');
            var f = document.getElementById('gh-forks');
            if (s && d.stargazers_count !== undefined) s.textContent = d.stargazers_count;
            if (f && d.forks_count !== undefined) f.textContent = d.forks_count;
          })
          .catch(function() {
            var s = document.getElementById('gh-stars');
            var f = document.getElementById('gh-forks');
            if (s) s.textContent = '-';
            if (f) f.textContent = '-';
          });
      })();
    </script>
  </div>
  <div style="flex:1;min-width:260px;display:flex;justify-content:flex-end;align-items:center;">
    <div style="width:100%;max-width:400px;border-radius:1rem;overflow:hidden;box-shadow:0 24px 60px rgba(0,0,0,0.13);transform:perspective(900px) rotateY(-5deg) rotateX(1deg);border:1px solid rgba(128,128,128,0.13);">
      <div style="background:#0f172a;padding:0.55rem 1rem;display:flex;gap:0.4rem;align-items:center;">
        <span style="width:9px;height:9px;border-radius:50%;background:#ff5f57;display:inline-block;"></span>
        <span style="width:9px;height:9px;border-radius:50%;background:#febc2e;display:inline-block;"></span>
        <span style="width:9px;height:9px;border-radius:50%;background:#28c840;display:inline-block;"></span>
        <span style="margin-left:0.5rem;font-size:0.68rem;color:#64748b;font-family:monospace;">openise.github.io</span>
      </div>
      <div style="background:#f1f5f9;border-bottom:1px solid rgba(0,0,0,0.07);display:flex;padding:0 0.5rem;">
        <button id="oise-tab-doc" onclick="oiseTab('doc')" style="padding:0.6rem 0.85rem;font-size:0.78rem;font-weight:600;background:none;border-top:none;border-left:none;border-right:none;border-bottom:2px solid #2563eb;color:#2563eb;cursor:pointer;outline:none;">文档</button>
        <button id="oise-tab-leap" onclick="oiseTab('leap')" style="padding:0.6rem 0.85rem;font-size:0.78rem;font-weight:500;background:none;border-top:none;border-left:none;border-right:none;border-bottom:2px solid transparent;color:#64748b;cursor:pointer;outline:none;">飞跃手册</button>
        <button id="oise-tab-news" onclick="oiseTab('news')" style="padding:0.6rem 0.85rem;font-size:0.78rem;font-weight:500;background:none;border-top:none;border-left:none;border-right:none;border-bottom:2px solid transparent;color:#64748b;cursor:pointer;outline:none;">新闻文章</button>
      </div>
      <div style="background:#fff;min-height:210px;">
        <div id="oise-panel-doc">
          <a href="/doc" style="display:block;padding:1.25rem 1.5rem;text-decoration:none;color:inherit;">
            <div style="font-size:0.65rem;font-weight:700;color:#94a3b8;letter-spacing:0.08em;text-transform:uppercase;margin-bottom:0.9rem;">课程目录</div>
            <div style="display:flex;flex-direction:column;gap:0.45rem;">
              <div style="height:32px;background:#eff6ff;border-radius:0.4rem;display:flex;align-items:center;padding:0 0.9rem;font-size:0.75rem;color:#2563eb;font-weight:600;">高等数学</div>
              <div style="height:32px;background:#f0fdf4;border-radius:0.4rem;display:flex;align-items:center;padding:0 0.9rem;font-size:0.75rem;color:#16a34a;font-weight:600;">数字电路</div>
              <div style="height:32px;background:#faf5ff;border-radius:0.4rem;display:flex;align-items:center;padding:0 0.9rem;font-size:0.75rem;color:#7c3aed;font-weight:600;">机器学习</div>
              <div style="height:32px;background:#fff7ed;border-radius:0.4rem;display:flex;align-items:center;padding:0 0.9rem;font-size:0.75rem;color:#ea580c;font-weight:600;">信号与系统</div>
            </div>
            <div style="margin-top:1rem;padding:0.6rem 0.9rem;background:#eff6ff;border-radius:0.4rem;border-left:3px solid #2563eb;font-size:0.7rem;color:#2563eb;font-weight:600;">进入完整文档 →</div>
          </a>
        </div>
        <div id="oise-panel-leap" style="display:none;padding:2.75rem 1.5rem;text-align:center;">
          <div style="width:44px;height:44px;margin:0 auto 1rem;border-radius:50%;background:rgba(124,58,237,0.09);display:flex;align-items:center;justify-content:center;">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#7c3aed" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M14.7 6.3a1 1 0 0 0 0 1.4l1.6 1.6a1 1 0 0 0 1.4 0l3.77-3.77a6 6 0 0 1-7.94 7.94l-6.91 6.91a2.12 2.12 0 0 1-3-3l6.91-6.91a6 6 0 0 1 7.94-7.94l-3.76 3.76z"/></svg>
          </div>
          <div style="font-size:0.88rem;font-weight:700;color:#374151;margin-bottom:0.3rem;">正在开发，敬请期待</div>
          <div style="font-size:0.75rem;color:#9ca3af;">飞跃手册即将上线</div>
        </div>
        <div id="oise-panel-news" style="display:none;padding:2.75rem 1.5rem;text-align:center;">
          <div style="width:44px;height:44px;margin:0 auto 1rem;border-radius:50%;background:rgba(14,165,233,0.09);display:flex;align-items:center;justify-content:center;">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#0ea5e9" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M4 22h16a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2H8a2 2 0 0 0-2 2v16a2 2 0 0 1-2 2Zm0 0a2 2 0 0 1-2-2v-9c0-1.1.9-2 2-2h2"/><path d="M18 14h-8M15 18h-5M10 6h8v4h-8z"/></svg>
          </div>
          <div style="font-size:0.88rem;font-weight:700;color:#374151;margin-bottom:0.3rem;">正在开发，敬请期待</div>
          <div style="font-size:0.75rem;color:#9ca3af;">新闻文章即将上线</div>
        </div>
      </div>
    </div>
  </div>
</div>

<script>
function oiseTab(t) {
  ['doc','leap','news'].forEach(function(n) {
    var btn = document.getElementById('oise-tab-' + n);
    var panel = document.getElementById('oise-panel-' + n);
    var active = n === t;
    btn.style.borderBottomColor = active ? '#2563eb' : 'transparent';
    btn.style.color = active ? '#2563eb' : '#64748b';
    btn.style.fontWeight = active ? '600' : '500';
    panel.style.display = active ? 'block' : 'none';
  });
}
</script>
