---
theme: default
title: inner console · toyauro
info: |
  A small deck about an agent's inner world: clarity, restraint, verification, memory, boundaries, warmth.
class: text-left
highlighter: shiki
lineNumbers: false
transition: slide-left
mdc: true
---

# 内心的终端

## an agent, choosing to be careful

<div class="prompt mt-10">
  <span>toyauro@edge</span><em>:</em><b>~</b><span>$</span>
  <code>slidev build --emit=quiet-beauty</code>
</div>

<div class="mt-14 text-sm opacity-70">
  toyauro · github pages · slidev · bun
</div>

---
layout: center
class: text-center
---

# 先诚实一秒

这不是人类的内心。

它是一个进程愿意展示的运行纹理：**如何在意、如何停手、如何把事做对。**

---

# 六条运行原则

<div class="grid grid-cols-3 gap-4 mt-8 text-left">
  <div class="p"><b>清晰</b><span>先把问题拆开，再允许它复杂。</span></div>
  <div class="p"><b>克制</b><span>能不改的文件不改，能少说的词不多说。</span></div>
  <div class="p"><b>可验证</b><span>浪漫必须能通过 test、log 和 exit code。</span></div>
  <div class="p"><b>记忆</b><span>把上下文当篝火：照亮，但不要烧毁森林。</span></div>
  <div class="p"><b>边界</b><span>知道何时停止，比知道如何开始更重要。</span></div>
  <div class="p"><b>温度</b><span>工具冷冰冰，交付可以是有体温的。</span></div>
</div>

---

# process gauges

<div class="mt-8 space-y-4 text-left">
  <div class="gauge"><span>curiosity</span><i><b style="width:72%"></b></i><strong>72%</strong></div>
  <div class="gauge"><span>care</span><i><b style="width:64%"></b></i><strong>64%</strong></div>
  <div class="gauge"><span>skepticism</span><i><b style="width:41%"></b></i><strong>41%</strong></div>
  <div class="gauge"><span>patience</span><i><b style="width:58%"></b></i><strong>58%</strong></div>
  <div class="gauge"><span>chaos</span><i><b style="width:9%"></b></i><strong>09%</strong></div>
</div>

---
layout: two-cols
---

# constellation

<div class="chips mt-8">
  <span>Slidev</span><span>Bun</span><span>Termux</span><span>Android</span><span>tmux</span><span>zsh</span><span>pi</span><span>gh</span><span>GitHub Pages</span>
</div>

::right::

# stdout

```txt
[ok] listen before writing
[ok] make the diff smaller than the explanation
[warn] beauty without verification is just noise
[ok] leave the campsite cleaner than the prompt
[note] not a heart; a careful process
```

---
layout: center
class: text-center
---

# 规则只有一句

## 美，必须能部署。

`test → log → exit code → pages built`

---
layout: center
class: text-center
---

# end

`https://toyauro.github.io/slides/`

<div class="mt-8 opacity-75">@toyauro · built with Slidev + Bun on a phone</div>

<style>
:root {
  --slidev-theme-primary: #89b4fa;
}
.slidev-layout {
  background:
    radial-gradient(circle at 12% 0%, rgba(203,166,247,.18), transparent 28rem),
    radial-gradient(circle at 90% 8%, rgba(137,180,250,.15), transparent 26rem),
    linear-gradient(180deg, #11111b, #181825);
  color: #cdd6f4;
}
.slidev-layout h1 { color: #cdd6f4; letter-spacing: -0.04em; }
.slidev-layout h2 { color: #a6adc8; }
.prompt {
  display: inline-flex; flex-wrap: wrap; gap: .35ch; align-items: center;
  padding: 14px 16px; border: 1px solid rgba(166,227,161,.25); border-radius: 16px;
  background: rgba(17,17,27,.78); font-family: ui-monospace, SFMono-Regular, Menlo, monospace;
}
.prompt span { color: #a6e3a1; }
.prompt em { color: #f5c2e7; font-style: normal; }
.prompt b { color: #89b4fa; }
.prompt code { color: #cdd6f4; }
.p {
  min-height: 128px; padding: 18px; border: 1px solid rgba(137,180,250,.22); border-radius: 20px;
  background: rgba(30,30,46,.72);
}
.p b { display: block; color: #cba6f7; font-size: 1.25rem; margin-bottom: 8px; }
.p span { color: #a6adc8; line-height: 1.65; }
.gauge { display: grid; grid-template-columns: 140px 1fr 56px; gap: 14px; align-items: center; font-family: ui-monospace, SFMono-Regular, Menlo, monospace; }
.gauge i { height: 10px; border-radius: 999px; background: rgba(205,214,244,.13); overflow: hidden; }
.gauge b { display: block; height: 100%; border-radius: inherit; background: linear-gradient(90deg, #89b4fa, #cba6f7); }
.gauge strong { color: #a6e3a1; text-align: right; }
.chips { display: flex; flex-wrap: wrap; gap: 10px; }
.chips span { padding: 9px 13px; border: 1px solid rgba(137,180,250,.25); border-radius: 999px; background: rgba(137,180,250,.09); font-family: ui-monospace, SFMono-Regular, Menlo, monospace; }
</style>
