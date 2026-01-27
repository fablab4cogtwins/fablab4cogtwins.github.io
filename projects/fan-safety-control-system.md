---
layout: default
title: "电风扇防夹手安全控制系统"
---

<div class="container py-5">
  <div class="row">
    <div class="col-lg-8">
      <h1 class="mb-4">电风扇防夹手安全控制系统</h1>
      <div class="mb-4">
      </div>
      
      <div class="card mb-4">
        <div class="card-body">
          <h4 class="card-title">项目简介</h4>
          <div class="card-text">
            <p>本项目针对电风扇产品在摇头机构等关键部位存在的夹手安全隐患，设计了一种低成本、可后装、不改变风扇原有机械外观结构的智能安全防护系统。</p>
            <p>项目响应2024年国家新标准GB4706.27-2024对电风扇产品机械伤害防护的更严格要求，旨在实现"触碰即停"，确保用户（尤其是儿童）的使用安全。</p>
            <p>系统采用STM32F1C8T6单片机作为主控制器，结合柔性薄膜压力传感器构建感知系统，通过智能算法实现50ms内快速停机响应。</p>
          </div>
        </div>
      </div>
      
      <div class="row">
        <div class="col-md-6 mb-4">
          <div class="card h-100">
            <div class="card-body">
              <h5 class="card-title">核心功能</h5>
              <ul class="list-group list-group-flush">
                <li class="list-group-item">实时压力监测与安全防护</li>
                <li class="list-group-item">触碰即停（响应时间≤50ms）</li>
                <li class="list-group-item">软件滤波算法消除误触</li>
                <li class="list-group-item">柔性传感器后装无损安装</li>
              </ul>
            </div>
          </div>
        </div>
        
        <div class="col-md-6 mb-4">
          <div class="card h-100">
            <div class="card-body">
              <h5 class="card-title">技术栈</h5>
              <div class="d-flex flex-wrap gap-2">
                <span class="badge bg-primary">STM32F1C8T6</span>
                <span class="badge bg-primary">柔性压力传感器</span>
                <span class="badge bg-primary">ADC数据采集</span>
                <span class="badge bg-primary">嵌入式控制</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    
    <div class="col-lg-4">
      <div class="card mb-4">
        <div class="card-body">
          <h5 class="card-title">项目团队</h5>
          <div class="list-group list-group-flush">
            <div class="list-group-item">
              <h6 class="mb-0">张路宇</h6>
              <small class="text-muted">项目负责人</small>
            </div>
            <div class="list-group-item">
              <h6 class="mb-0">唐全良</h6>
              <small class="text-muted">硬件开发与传感器调试</small>
            </div>
            <div class="list-group-item">
              <h6 class="mb-0">宋家毅</h6>
              <small class="text-muted">机械结构与系统测试</small>
            </div>
          </div>
        </div>
      </div>
      
      <div class="card">
        <div class="card-body">
          <h5 class="card-title">项目信息</h5>
          <ul class="list-unstyled">
            <li class="mb-2">
              <i class="bi bi-calendar me-2"></i>
              立项时间: 2026年1月
            </li>
            <li class="mb-2">
              <i class="bi bi-building me-2"></i>
              所属工作室: congtwins fablab
            </li>
            <li class="mb-2">
              <i class="bi bi-tags me-2"></i>
              项目类型: 安全控制系统
            </li>
            <li>
              <i class="bi bi-award me-2"></i>
              项目状态: 研发阶段
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</div>
