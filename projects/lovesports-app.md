---
layout: default
title: "LoveSports APP"
---

<div class="container py-5">
  <div class="row justify-content-center">
    <div class="col-lg-10">
      <div class="text-center mb-5">
        <h1 class="fw-bold text-primary mb-3">LoveSports APP</h1>
        <div class="d-flex justify-content-center">
          <span class="badge bg-gradient-primary rounded-pill px-3 py-2 me-2">人脸识别</span>
          <span class="badge bg-gradient-success rounded-pill px-3 py-2">运动打卡</span>
        </div>
      </div>
      
      <div class="row">
        <div class="col-lg-8">
          <div class="card border-0 shadow-lg rounded-4 overflow-hidden mb-4">
            <div class="card-header bg-gradient-primary text-white py-4">
              <h4 class="card-title mb-0 text-center fw-semibold">
                <i class="bi bi-info-circle me-2"></i>项目简介
              </h4>
            </div>
            <div class="card-body p-5">
              <p class="fs-5 text-dark mb-0">
                本项目响应实验室成员运动热情，研发了一款基于人脸识别技术的运动打卡应用。该方案满足实验室对高精度数据统计与成员运动兴趣提升的要求，能有效确保打卡数据的真实有效，并通过可视化日历记录与实时排名机制点燃成员的运动热情，可广泛应用于实验室内部管理、企业团队健康打卡等需要身份核验的运动健康管理场景。
              </p>
            </div>
          </div>
        </div>
        
        <div class="col-lg-4">
          <div class="card border-0 shadow-lg rounded-4 overflow-hidden h-100">
            <div class="card-header bg-gradient-success text-white py-4">
              <h5 class="card-title mb-0 text-center fw-semibold">
                <i class="bi bi-clipboard-data me-2"></i>项目信息
              </h5>
            </div>
            <div class="card-body p-4">
              <div class="d-flex align-items-center mb-4">
                <div class="bg-primary bg-opacity-10 p-3 rounded-circle me-3">
                  <i class="bi bi-calendar3 text-primary fs-4"></i>
                </div>
                <div>
                  <div class="text-muted small">立项时间</div>
                  <div class="fw-bold fs-5">2026年1月</div>
                </div>
              </div>
              
              <div class="d-flex align-items-center mb-4">
                <div class="bg-success bg-opacity-10 p-3 rounded-circle me-3">
                  <i class="bi bi-building text-success fs-4"></i>
                </div>
                <div>
                  <div class="text-muted small">所属工作室</div>
                  <div class="fw-bold fs-5">congtwins fablab</div>
                </div>
              </div>
              
              <div class="d-flex align-items-center mb-4">
                <div class="bg-info bg-opacity-10 p-3 rounded-circle me-3">
                  <i class="bi bi-tools text-info fs-4"></i>
                </div>
                <div>
                  <div class="text-muted small">项目类型</div>
                  <div class="fw-bold fs-5">移动应用开发</div>
                </div>
              </div>
              
              <div class="d-flex align-items-center">
                <div class="bg-warning bg-opacity-10 p-3 rounded-circle me-3">
                  <i class="bi bi-lightning-charge text-warning fs-4"></i>
                </div>
                <div>
                  <div class="text-muted small">项目状态</div>
                  <div class="fw-bold fs-5">已上线</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<style>
  .bg-gradient-primary {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  }
  
  .bg-gradient-success {
    background: linear-gradient(135deg, #11998e 0%, #38ef7d 100%);
  }
  
  .card {
    transition: transform 0.3s ease;
  }
  
  .card:hover {
    transform: translateY(-5px);
  }
  
  .rounded-4 {
    border-radius: 1.5rem !important;
  }
  
  .badge {
    font-weight: 500;
  }
  
  .card-header {
    border-bottom: none;
  }
</style>
