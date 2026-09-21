---
layout: page
description: 刘丰豪，四川大学轻工科学与工程学院食品科学与工程专业本科生，关注食品加工工艺、仪器分析与食品工厂设计。
---

# 关于我

<img src="/images/avatar.jpg" class="floatpic">

我是**刘丰豪**，[四川大学](https://www.scu.edu.cn/)[轻工科学与工程学院](https://qfsp.scu.edu.cn/)食品科学与工程专业本科生（2023.09 – 2027.06）。<br>

My name is **Liu Fenghao**, an undergraduate in Food Science and Engineering at the [College of Biomass Science and Engineering](https://qfsp.scu.edu.cn/), [Sichuan University](https://www.scu.edu.cn/). My interests lie in **food processing technology, instrumental analysis, and food factory design**.

我的兴趣集中在食品加工与工艺优化、仪器分析与数据定量、食品工厂设计三个领域。在四川大学 2025 年度"本科生走进大仪"体验计划中，我独立完成了氨基酸衍生试剂配制、样品前处理与上机测定，用 A300 全自动氨基酸分析仪跟踪豇豆泡菜发酵过程中氨基酸谱的变化规律；在罗爱民老师课题组，我参与表面增强红外（SEIRA）白酒醛类快速检测项目的光谱采集与数据预处理，并完成 PEF（低压脉冲振荡电场）催陈白酒实验的主要风味物质测定。此外，我系统完成过 3000 t/年苹果汁工厂的工艺设计与技术经济评价。<br>

## 教育与项目经历

<div class="timeline">
  <div class="timeline-progress" id="timeline-progress"></div>

  <div class="timeline-item timeline-item--current">
    <div class="timeline-dot" style="background: #ffffff;">
      <img src="/images/logo/scu.svg" alt="四川大学">
    </div>
    <div class="timeline-card">
      <div class="timeline-header">
        <div class="timeline-role">食品科学与工程 <span class="timeline-sep">|</span> <span class="timeline-company"><a href="https://qfsp.scu.edu.cn/">四川大学·轻工科学与工程学院</a></span></div>
        <span class="timeline-time">2023.09 - 2027.06</span>
      </div>
      <div class="timeline-details">
        本科在读。核心课程成绩：食品微生物学实验 97、化学实验室安全理论与实践 95、计算机辅助工程设计 90、食品生物化学 90、专业综合实验 90、植物系统分类学 90。CET-4 554 / CET-6 545。
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-dot" style="background: #ffffff;">
      <img src="/images/logo/scu.svg" alt="四川大学">
    </div>
    <div class="timeline-card">
      <div class="timeline-header">
        <div class="timeline-role">项目组成员 <span class="timeline-sep">|</span> <span class="timeline-company">基于表面增强红外技术的白酒中乙醛、乙缩醛快速检测模型构建</span></div>
        <span class="timeline-time">2025.11 - 2027.10</span>
      </div>
      <div class="timeline-details">
        联合申报项目（指导教师罗爱民，项目负责人林子鉴）。本人负责 SEIRA 光谱采集与光谱数据预处理，并参与 PEF 催陈白酒实验的风味物质测定。
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-dot" style="background: #ffffff;">
      <img src="/images/logo/scu.svg" alt="四川大学">
    </div>
    <div class="timeline-card">
      <div class="timeline-header">
        <div class="timeline-role">项目参与人 <span class="timeline-sep">|</span> <span class="timeline-company">使用氨基酸分析仪研究发酵制品中氨基酸变化及其影响因素</span></div>
        <span class="timeline-time">2025.10 - 2025.11</span>
      </div>
      <div class="timeline-details">
        四川大学 2025 年度本科生"走进大仪"体验计划项目（项目负责人邓莎）。五周发酵跟踪，完成 15 组样品上机测定与特征峰识别，已通过结项验收并获结项证书。
      </div>
    </div>
  </div>

</div>

<script>
(function() {
  var timelineProgress = document.getElementById('timeline-progress');
  var timeline = document.querySelector('.timeline');
  if (!timelineProgress || !timeline) return;

  var items = timeline.querySelectorAll('.timeline-item');

  // IntersectionObserver for in-view class
  if ('IntersectionObserver' in window) {
    var observer = new IntersectionObserver(function(entries) {
      entries.forEach(function(entry) {
        if (entry.isIntersecting) {
          entry.target.classList.add('in-view');
        }
      });
    }, { rootMargin: '0px 0px -15% 0px' });

    items.forEach(function(item, idx) {
      if (idx < 3) {
        // Reveal first 3 immediately on load (still gets the stagger transition)
        item.classList.add('in-view');
      } else {
        observer.observe(item);
      }
    });
  } else {
    items.forEach(function(item) { item.classList.add('in-view'); });
  }

  // Scroll progress bar
  window.addEventListener('scroll', function() {
    var rect = timeline.getBoundingClientRect();
    var totalHeight = timeline.offsetHeight;
    var windowH = window.innerHeight;
    var lineTop = 30;
    var lineBottom = 30;
    var lineHeight = totalHeight - lineTop - lineBottom;

    if (rect.top < windowH && rect.bottom > 0) {
      var scrolled = Math.min(1, Math.max(0, (windowH - rect.top - lineTop) / (totalHeight - lineTop + windowH * 0.4)));
      timelineProgress.style.height = Math.min(scrolled * lineHeight, lineHeight) + 'px';
    }
  }, { passive: true });
})();
</script>

如果你对我的经历或合作感兴趣，欢迎随时联系我：liufenghao@stu.scu.edu.cn

**<font color="#990000">正在寻找食品研发、工艺技术、质量管理方向的实习与校招机会，欢迎交流！</font>**

---

## 专业方向

- 食品加工工艺与工艺优化
- 仪器分析（氨基酸分析、光谱类仪器操作与数据定量）
- 食品工厂设计与技术经济评价
- 食品微生物与发酵过程监控
- 实验数据统计与可视化

我目前的工作围绕**食品加工工艺与仪器分析**展开：从样品前处理、衍生试剂配制到上机测定与定量反算，把仪器输出的峰面积转成可解释的成分变化规律；也熟悉从工艺设计到设备选型、投资估算与回收期分析的食品工厂建设全流程。

<img src="/images/dayi-chromatogram.jpg" alt="A300 全自动氨基酸分析仪双通道色谱图：主峰保留时间 48.253 min">

*走进大仪项目中由 A300 全自动氨基酸分析仪输出的双通道色谱图——横轴为保留时间（min），纵轴为信号强度（mV），主峰出现在 48.253 min，约 188 min 处为一根接近量程上限的尖峰。*

---

## 新闻与动态

<div class="news-grid">
  <div class="news-card news-card--publication">
    <div class="news-meta">
      <span class="news-date">2026 年 1 月</span>
      <span class="news-tag news-tag--publication">项目结项</span>
    </div>
    <p>参与四川大学 2025 年度本科生"走进大仪"体验计划项目<strong>基于氨基酸分析仪研究发酵制品中氨基酸变化及其影响因素</strong>，已通过结项验收，获四川大学实验室及设备管理处颁发的<strong>结项证书</strong></p>
  </div>

  <div class="news-card news-card--milestone">
    <div class="news-meta">
      <span class="news-date">2025 年 11 月</span>
      <span class="news-tag news-tag--milestone">里程碑</span>
    </div>
    <p>作为项目组成员参与申报<strong>基于表面增强红外技术的白酒中乙醛、乙缩醛快速检测模型构建</strong>（指导教师罗爱民），负责 SEIRA 光谱采集与数据预处理</p>
  </div>

  <div class="news-card news-card--milestone">
    <div class="news-meta">
      <span class="news-date">2025 - 2026 学年</span>
      <span class="news-tag news-tag--milestone">荣誉</span>
    </div>
    <p>获得四川大学<strong>校级综合三等奖学金</strong>；所在团支部（食品科学与工程 3 班团支部）获 <strong>2025 年度四川大学五四红旗团支部</strong></p>
  </div>

  <div class="news-card news-card--publication">
    <div class="news-meta">
      <span class="news-date">2024 年 12 月</span>
      <span class="news-tag news-tag--publication">语言</span>
    </div>
    <p>CET-4 <strong>554</strong> 分、CET-6 <strong>545</strong> 分，具备阅读英文设备技术资料与文献的能力</p>
  </div>
</div>

<script>
(function() {
  if ('IntersectionObserver' in window) {
    var observer = new IntersectionObserver(function(entries) {
      entries.forEach(function(entry) {
        if (entry.isIntersecting) {
          entry.target.classList.add('animate-in');
          observer.unobserve(entry.target);
        }
      });
    }, { threshold: 0.08, rootMargin: '0px 0px -60px 0px' });
    document.querySelectorAll('.news-card').forEach(function(card) {
      observer.observe(card);
    });
  } else {
    document.querySelectorAll('.news-card').forEach(function(card) {
      card.classList.add('animate-in');
    });
  }
})();
</script>
