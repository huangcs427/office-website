<template>
  <div class="app-shell">
    <nav>
      <div class="logo">
        <span class="dot"></span>
        <span>微大夫 vDAIFU</span>
      </div>
      <ul>
        <li>Home</li>
        <li>服务（Products）</li>
        <li>技术（Technology）</li>
        <li>网络（Locations）</li>
        <li>安全（Safety）</li>
        <li>资源</li>
        <li>关于（Company）</li>
      </ul>
      <div class="nav-cta">
        <button class="btn btn-secondary">了解基础设施</button>
        <button class="btn btn-primary">立即体验</button>
      </div>
    </nav>

    <section class="hero">
      <div>
        <div class="hero-badges">
          <span class="badge">AED 极速救命</span>
          <span class="badge">城市级具身智能</span>
          <span class="badge">5 分钟生命圈</span>
        </div>
        <h1>AED 极速救命 · 我们正在把救命能力带到每个家庭</h1>
        <p class="lead">
          同时，我们正在构建城市级的医疗具身智能基础设施，让急救与日常健康服务随时可达。
        </p>
        <div class="nav-cta" style="margin-bottom: 12px">
          <button class="btn btn-primary">立即体验家庭守护</button>
          <button class="btn btn-secondary">了解基础设施（v-Brain）</button>
        </div>
        <div class="badge">Embodied AI Infrastructure for Primary Care</div>
      </div>
      <div class="animated-orbit">
        <div class="orbit-center">5 分钟生命圈</div>
        <div class="orbit-ring">
          <div class="orbit-dot"></div>
        </div>
        <div class="orbit-note note-top">城市核心云仓 → 社区边缘 → 家庭终端</div>
        <div class="orbit-note note-bottom">1-2-5 分钟联动</div>
      </div>
    </section>

    <section class="section">
      <div class="section-header">
        <h2>一个真实场景：5 分钟生命圈如何救人</h2>
        <button class="btn btn-secondary">观看 60s 演示视频</button>
      </div>
      <div class="timeline">
        <div class="timeline-items">
          <div class="timeline-card">
            <div class="icon-circle">天</div>
            <h4>用户 SOS → 无人机 1 分钟起飞</h4>
            <p>v-Brain 触发最近无人机，自动规划航线，夜间也可即刻起飞。</p>
          </div>
          <div class="timeline-card">
            <div class="icon-circle">地</div>
            <h4>边缘节点 2 分钟供给与路由</h4>
            <p>社区边缘仓或诊所即时提供物资与任务路由，缩短最后几百米。</p>
          </div>
          <div class="timeline-card">
            <div class="icon-circle">人</div>
            <h4>AI 指导 3–5 分钟完成施救</h4>
            <p>AI 语音指导现场急救，家庭终端接收 AED，基层人员同步响应。</p>
          </div>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="section-header">
        <div>
          <p class="badge">我们是谁</p>
          <h2>我们不仅做无人机 — 我们构建城市级医疗基础设施</h2>
          <p>vDAIFU = TwinCity（城市孪生） + V-Core（群体调度） + 分布式具身智能系统（执行体）</p>
        </div>
        <button class="btn btn-secondary">了解 Technology</button>
      </div>
      <div class="card-grid">
        <div class="card">
          <div class="icon-circle">核</div>
          <h3>群体智能调度引擎（V-Core）</h3>
          <p>城市机器人大脑，做出秒级调度决定，平衡安全、合规与效率。</p>
        </div>
        <div class="card">
          <div class="icon-circle">孪</div>
          <h3>城市级数字孪生（TwinCity）</h3>
          <p>让系统理解城市与医疗资源的地图与时空画像，形成认知底座。</p>
        </div>
        <div class="card">
          <div class="icon-circle">体</div>
          <h3>分布式具身智能系统</h3>
          <p>空中无人机、地面机器人、家庭终端的协同执行网络，20% 展示 80% 暗示。</p>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="section-header">
        <div>
          <p class="badge">网络（Locations）</p>
          <h2>覆盖城市全域的医疗空间网络</h2>
          <p>城市核心云仓 · 社区边缘仓 · 家庭终端，构成分钟级救援圈。</p>
        </div>
        <button class="btn btn-secondary">查看网络示意</button>
      </div>
      <div class="card-grid">
        <div class="card">
          <div class="icon-circle">城</div>
          <h4>城市核心节点（空中云仓）</h4>
          <p>城市级前置仓，支撑分钟级调度，承担补给、维护与集中路由。</p>
          <div class="pill-row">
            <span class="pill">覆盖半径示意</span>
            <span class="pill">夜间值守</span>
          </div>
        </div>
        <div class="card">
          <div class="icon-circle">社</div>
          <h4>社区节点（边缘仓 / 诊所 / 药店）</h4>
          <p>前置物资、快速响应，与物业/诊所协同，缩短最后几百米延迟。</p>
          <div class="pill-row">
            <span class="pill">网格化响应</span>
            <span class="pill">安全合规</span>
          </div>
        </div>
        <div class="card">
          <div class="icon-circle">家</div>
          <h4>家庭终端（智能药箱 / 停机坪）</h4>
          <p>现场急救、用药管理、远程指导，把救援和常态护理送到家门口。</p>
          <div class="pill-row">
            <span class="pill">AI 医生</span>
            <span class="pill">实时指导</span>
          </div>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="section-header">
        <div>
          <p class="badge">信任与安全</p>
          <h2>为什么可信：数据与合规</h2>
          <p>关键指标与合作徽章展示，深入内容进入安全白皮书与合规报告。</p>
        </div>
        <button class="btn btn-secondary">查看安全白皮书</button>
      </div>
      <div class="metrics">
        <div class="metric-card">
          <div class="label">平均急救响应演示</div>
          <div class="value">≤ 5 分钟（试点）</div>
        </div>
        <div class="metric-card">
          <div class="label">调度成功率</div>
          <div class="value">≥ 90%</div>
        </div>
        <div class="metric-card">
          <div class="label">数字孪生覆盖</div>
          <div class="value">试点城市 100%</div>
        </div>
      </div>
      <div class="pill-row" style="margin-top: 12px">
        <span class="pill">医院合作</span>
        <span class="pill">监管备案</span>
        <span class="pill">第三方测试</span>
      </div>
    </section>

    <section class="section">
      <div class="section-header">
        <div>
          <p class="badge">技术词带路</p>
          <h2>三层技术词，20% 展示 80% 暗示</h2>
          <p>首页保留三层词，细节放到 Technology 页面或白皮书。</p>
        </div>
        <button class="btn btn-secondary">了解更多 Technology</button>
      </div>
      <div class="card-grid">
        <div class="card">
          <div class="icon-circle">核</div>
          <h4>群体智能调度引擎（V-Core）</h4>
          <p>城市机器人大脑，做出秒级调度决定。</p>
        </div>
        <div class="card">
          <div class="icon-circle">孪</div>
          <h4>城市级数字孪生（TwinCity）</h4>
          <p>理解城市与医疗资源的时空画像。</p>
        </div>
        <div class="card">
          <div class="icon-circle">体</div>
          <h4>分布式具身智能系统</h4>
          <p>空地家庭一体的执行网络，协同完成任务。</p>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="section-header">
        <h2>加入或合作</h2>
        <p>填写简单信息，获取城市试点或合作咨询。</p>
      </div>
      <div class="footer-form">
        <input type="text" placeholder="城市" />
        <input type="text" placeholder="单位/公司" />
        <input type="text" placeholder="联系人" />
        <select>
          <option>需求类型</option>
          <option>城市试点</option>
          <option>合作洽谈</option>
          <option>投资咨询</option>
        </select>
        <button class="btn btn-primary" style="width: 100%">提交</button>
      </div>
      <div class="footer-note">首页讲故事 → 立刻声明基础设施身份 → 20% 展示，80% 暗示深度。</div>
    </section>
  </div>
</template>

<script setup></script>
