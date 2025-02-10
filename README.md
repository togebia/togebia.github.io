<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>技术视界 | 首页</title>

  
  <!-- 其他head内容（如title、meta标签） -->
  <style>
    /* 覆盖导航栏的CSS */
    header, .main-content {  /* 确保选择器匹配你的页面元素 */
      position: relative;
      z-index: 9999;
      margin-top: -60px;     /* 根据实际导航栏高度调整 */
    }
  </style>

  <link rel="stylesheet" href="library/css/style.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
  <nav class="navbar">
    <ul class="nav-links">
      <li><a href="library/pages/index.html"><i class="fas fa-home"></i> 首页</a></li>
      <!-- 修改导航栏链接自动打开 -->
      <li><a href="library/pages/articles.html#all-expand"><i class="fas fa-book-open"></i> 文章</a></li>
      <li><a href="library/pages/about.html"><i class="fas fa-user"></i> 关于</a></li>
      <li><a href="library/pages/contact.html"><i class="fas fa-envelope"></i> 联系</a></li>
    </ul>
  </nav>

  <main class="container">
    <section class="hero">
      <div class="hero-content">
        <h1 class="hero-title">探索数字世界的无限可能</h1>
        <p class="hero-subtitle">技术与创意交汇的前沿观察</p>
        <div class="cta-buttons">
          <a href="library/pages/articles.html" class="btn primary">阅读文章</a>
          <a href="library/pages/contact.html" class="btn secondary">联系作者</a>
        </div>
      </div>
    </section>

    <section class="featured-posts">
      <h2>精选文章</h2>
      <div class="post-grid">
        <article class="post-card">
          <div class="post-header">
            <span class="post-tag">前端开发</span>
            <time>2024-02-15</time>
          </div>
          <h3>现代Web动画技术实践</h3>
          <p>深入探讨CSS动画、WebGL和Canvas的实现原理与应用场景，带你领略网页动态之美...</p>
          <a href="#" class="read-more">阅读全文 <i class="fas fa-arrow-right"></i></a>
        </article>

        <article class="post-card">
          <div class="post-header">
            <span class="post-tag">人工智能</span>
            <time>2024-01-28</time>
          </div>
          <h3>机器学习实战：图像识别入门</h3>
          <p>使用TensorFlow.js在浏览器中实现实时图像分类，体验AI在客户端的应用潜力...</p>
          <a href="#" class="read-more">阅读全文 <i class="fas fa-arrow-right"></i></a>
        </article>
      </div>
    </section>
  </main>

  <script src="library/js/particles.js"></script>
</body>
</html>
