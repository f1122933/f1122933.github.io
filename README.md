<!DOCTYPE html>
<html lang="zh-CN">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>红榜凝力量 榜样润初心 - 雷锋精神学习工单</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Microsoft YaHei', Arial, sans-serif;
      line-height: 1.8;
      color: #333;
      background-color: #f8f9fa;
      padding: 20px;
    }

    .container {
      max-width: 1100px;
      margin: 0 auto;
      background: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 30px rgba(0, 0, 0, 0.1);
      position: relative;
      overflow: visible;
    }

    /* 确保所有图片容器能够完整显示内容 */
    .image-box,
    .banner-image {
      position: relative;
      z-index: 1;
      overflow: visible;
    }

    .container::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 8px;
      background: linear-gradient(90deg, #e74c3c, #c0392b);
    }

    .header {
      text-align: center;
      margin-bottom: 40px;
      padding: 30px 0;
      background-color: #fdf2e9;
      border-radius: 8px;
      position: relative;
    }

    .header::after {
      content: '';
      position: absolute;
      bottom: -10px;
      left: 50%;
      transform: translateX(-50%);
      width: 100px;
      height: 4px;
      background-color: #e74c3c;
      border-radius: 2px;
    }

    .header h1 {
      color: #e74c3c;
      font-size: 2.8em;
      margin-bottom: 15px;
      text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.1);
    }

    .header p {
      color: #7f8c8d;
      font-size: 1.2em;
      font-weight: 500;
    }

    .banner-image {
      width: 100%;
      height: auto;
      object-fit: contain;
      border-radius: 8px;
      margin-bottom: 30px;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
      display: block;
      max-width: 100%;
    }

    .section {
      margin-bottom: 40px;
      position: relative;
      padding-left: 25px;
    }

    .section::before {
      content: '';
      position: absolute;
      left: 0;
      top: 10px;
      bottom: 10px;
      width: 4px;
      background-color: #e74c3c;
      border-radius: 2px;
    }

    .section h2 {
      color: #e74c3c;
      font-size: 2.2em;
      margin-bottom: 25px;
      padding-bottom: 10px;
      border-bottom: 2px solid #ecf0f1;
    }

    .section h3 {
      color: #2c3e50;
      font-size: 1.5em;
      margin: 25px 0 15px 0;
      padding-left: 15px;
      border-left: 4px solid #3498db;
    }

    .section h4 {
      color: #34495e;
      font-size: 1.2em;
      margin: 20px 0 10px 0;
    }

    .content-box {
      background-color: #f8f9fa;
      padding: 25px;
      border-radius: 8px;
      margin-bottom: 25px;
      border: 1px solid #e9ecef;
      transition: transform 0.3s ease;
    }

    .content-box:hover {
      transform: translateY(-5px);
      box-shadow: 0 5px 20px rgba(0, 0, 0, 0.1);
    }

    .quote-box {
      background-color: #f0f8ff;
      border-left: 5px solid #3498db;
      padding: 20px;
      margin: 20px 0;
      border-radius: 0 8px 8px 0;
    }

    .quote-box p {
      font-style: italic;
      color: #2c3e50;
      font-size: 1.1em;
    }

    .quote-box .author {
      text-align: right;
      margin-top: 10px;
      color: #7f8c8d;
      font-weight: bold;
    }

    .image-container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      margin: 25px 0;
      gap: 20px;
      padding: 10px;
      overflow: visible;
      align-items: flex-start;
    }

    .image-box {
      flex: 1;
      min-width: 250px;
      max-width: 350px;
      border-radius: 8px;
      overflow: visible;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
      display: flex;
      flex-direction: column;
      align-items: center;
      height: auto;
    }

    .image-box:hover {
      transform: scale(1.03);
    }

    .image-box img {
      width: 100%;
      height: auto;
      object-fit: contain;
      display: block;
      max-width: 100%;
    }

    .image-box .caption {
      padding: 15px;
      background-color: #f8f9fa;
      text-align: center;
      font-weight: 500;
      color: #555;
    }

    .timeline {
      position: relative;
      max-width: 100%;
      margin: 25px 0;
      padding-left: 40px;
    }

    .timeline::before {
      content: '';
      position: absolute;
      width: 3px;
      background-color: #e74c3c;
      top: 0;
      bottom: 0;
      left: 10px;
    }

    .timeline-item {
      position: relative;
      margin-bottom: 25px;
      padding-left: 25px;
    }

    .timeline-item::before {
      content: '';
      position: absolute;
      width: 24px;
      height: 24px;
      left: -4px;
      background-color: white;
      border: 4px solid #e74c3c;
      border-radius: 50%;
      z-index: 1;
    }

    .timeline-item h4 {
      color: #e74c3c;
      margin-bottom: 8px;
    }

    .process-flow {
      background-color: #fef5e7;
      border-radius: 8px;
      padding: 25px;
      margin: 25px 0;
    }

    .process-step {
      display: flex;
      align-items: flex-start;
      margin-bottom: 20px;
      padding-bottom: 20px;
      border-bottom: 1px dashed #e67e22;
    }

    .process-step:last-child {
      border-bottom: none;
    }

    .step-number {
      background-color: #e74c3c;
      color: white;
      width: 30px;
      height: 30px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: bold;
      margin-right: 15px;
      flex-shrink: 0;
    }

    .step-content {
      flex: 1;
    }

    .step-content h4 {
      color: #e74c3c;
      margin-bottom: 5px;
    }

    ul,
    ol {
      padding-left: 30px;
      margin: 15px 0;
    }

    li {
      margin-bottom: 8px;
      line-height: 1.6;
    }

    strong {
      color: #e74c3c;
      font-weight: 600;
    }

    .highlight-text {
      background-color: #fff3cd;
      padding: 2px 6px;
      border-radius: 4px;
      font-weight: 500;
    }

    .footer {
      text-align: center;
      margin-top: 50px;
      padding: 20px;
      background-color: #f8f9fa;
      border-radius: 8px;
      color: #7f8c8d;
    }

    .footer p {
      margin: 5px 0;
    }

    @media (max-width: 768px) {
      .container {
        padding: 20px;
      }

      .header h1 {
        font-size: 2em;
      }

      .banner-image {
        height: auto;
        max-height: 200px;
        object-fit: contain;
      }

      .image-box {
        min-width: 100%;
      }

      .section h2 {
        font-size: 1.8em;
      }
    }
  </style>
</head>

<body>
  <div class="container">
    <!-- 页眉 -->
    <div class="header">
      <h1>红榜凝力量 榜样润初心</h1>
      <p>雷锋精神学习与实践红色工单</p>
    </div>

    <!-- 主题图片 -->
    <img src="9553e94a-c73b-4ee5-8d1f-8510afd949eb.jpg" alt="雷锋精神主题图片" class="banner-image">

    <!-- 项目概述 -->
    <div class="section">
      <h2>项目概述</h2>
      <div class="content-box">
        <p>为深入贯彻落实习近平新时代中国特色社会主义思想，传承和弘扬雷锋精神，发挥榜样示范引领作用，特开展"红榜凝力量
          榜样润初心"主题实践活动。本工单旨在通过系统学习雷锋同志的生平事迹和精神内涵，引导广大党员群众从身边小事做起，将雷锋精神融入日常工作和生活，形成学习先进、争当先进的良好风尚。</p>

        <div class="quote-box">
          <p>"雷锋精神是永恒的，是社会主义核心价值观的生动体现。"</p>
          <div class="author">—— 习近平</div>
        </div>
      </div>
    </div>

    <!-- 雷锋生平 -->
    <div class="section">
      <h2>一、雷锋生平</h2>

      <div class="image-container">
        <div class="image-box">
          <img src="9553e94a-c73b-4ee5-8d1f-8510afd949eb.jpg" alt="雷锋同志" onerror="this.onerror=null;this.src='9553e94a-c73b-4ee5-8d1f-8510afd949eb.jpg';">
          <div class="caption">雷锋同志青年时期</div>
        </div>
        <div class="image-box">
          <img src="微信图片_20251104214236_79_33.jpg" alt="雷锋日记" onerror="this.onerror=null;this.src='9553e94a-c73b-4ee5-8d1f-8510afd949eb.jpg';">
          <div class="caption">雷锋日记手稿</div>
        </div>
      </div>

      <h3>1. 早年经历（1940-1958）</h3>
      <div class="timeline">
        <div class="timeline-item">
          <h4>苦难童年</h4>
          <p>1940年12月18日出生于湖南省望城县（现长沙市望城区）贫农家庭，7岁成为孤儿。幼年的苦难经历使他深刻体会到旧社会的黑暗和劳动人民的艰辛。</p>
        </div>
        <div class="timeline-item">
          <h4>新生与成长</h4>
          <p>1949年湖南解放后，在党和政府的关怀下免费入学，加入儿童团、少先队，1957年加入中国共产主义青年团。1956年小学毕业后，先后担任乡政府通信员、望城县委公务员，后成为团山湖农场第一位拖拉机手。</p>
        </div>
      </div>

      <h3>2. 工人与战士生涯（1958-1962）</h3>
      <div class="timeline">
        <div class="timeline-item">
          <h4>鞍钢岁月</h4>
          <p>1958年响应国家号召支援鞍钢，从推土机手成长为焦化厂技术骨干，3次获"先进工作者"、5次"标兵"、18次"红旗手"，被誉为"青年社会主义建设积极分子"。</p>
        </div>
        <div class="timeline-item">
          <h4>参军与奉献</h4>
          <p>1960年1月参军，任汽车兵，同年11月加入中国共产党。两年间荣立二等功1次、三等功2次，被评为"节约标兵""模范共青团员"。他坚持"把有限的生命投入到无限的为人民服务之中去"，出差时"好事做了一火车"。</p>
        </div>
        <div class="timeline-item">
          <h4>牺牲与纪念</h4>
          <p>1962年8月15日因公殉职，年仅22岁。1963年3月5日，毛泽东主席亲笔题词"向雷锋同志学习"，全国掀起学雷锋热潮，此后每年的3月5日被定为"学雷锋纪念日"。</p>
        </div>
      </div>
    </div>

    <!-- 雷锋精神的核心内涵 -->
    <div class="section">
      <h2>二、雷锋精神的核心内涵</h2>

      <div class="image-container">
        <div class="image-box">
          <img src="微信图片_20251104214237_80_33.jpg" alt="为人民服务" onerror="this.onerror=null;this.src='9553e94a-c73b-4ee5-8d1f-8510afd949eb.jpg';">
          <div class="caption">全心全意为人民服务</div>
        </div>
        <div class="image-box">
          <img src="微信图片_20251104214238_81_33.jpg" alt="螺丝钉精神" onerror="this.onerror=null;this.src='9553e94a-c73b-4ee5-8d1f-8510afd949eb.jpg';">
          <div class="caption">螺丝钉精神</div>
        </div>
        <div class="image-box">
          <img src="微信图片_20251104214239_82_33.jpg" alt="钉子精神" onerror="this.onerror=null;this.src='9553e94a-c73b-4ee5-8d1f-8510afd949eb.jpg';">
          <div class="caption">钉子精神</div>
        </div>
      </div>

      <div class="content-box">
        <h3>1. 热爱党与祖国的坚定信念</h3>
        <div class="quote-box">
          <p>"我就是长着一个心眼，一心向着党，向着社会主义，向着共产主义。"</p>
          <div class="author">—— 雷锋日记</div>
        </div>
        <p><strong>阶级立场：</strong>周恩来总理曾概括雷锋精神为"憎爱分明的阶级立场"。他始终保持对党的忠诚，自觉为党的事业奋斗终身。</p>
        <p><strong>国家情怀：</strong>他省吃俭用为灾区捐款，拒绝浪费，认为"国家穷，我们要同甘共苦"，展现了深厚的爱国主义情怀。</p>
      </div>

      <div class="content-box">
        <h3>2. 服务人民的奉献精神</h3>
        <div class="quote-box">
          <p>"雷锋精神的核心是全心全意为人民服务。"</p>
          <div class="author">—— 习近平</div>
        </div>
        <p><strong>助人为乐：</strong>雷锋以帮助他人为最大幸福，如为丢失车票的妇女买票、在抗洪中带病抢险7天，用实际行动践行着为人民服务的宗旨。</p>
        <p><strong>无私品格：</strong>他将自己比作"螺丝钉"，甘愿在平凡岗位坚守，强调"一滴水只有融入大海才不会干涸"，体现了无私奉献的精神境界。</p>
      </div>

      <div class="content-box">
        <h3>3. 敬业与创新的工匠精神</h3>
        <p><strong>钉子精神：</strong>作为汽车兵，他钻研技术使老旧车辆成为"节油标兵车"；在工作中提出"挤时间学习"的"钉子精神"，展现了顽强的学习毅力。</p>
        <p><strong>精益求精：</strong>无论农民、工人还是战士，他都"干一行爱一行、专一行精一行"，在平凡的岗位上创造出不平凡的业绩。</p>
      </div>

      <div class="content-box">
        <h3>4. 艰苦奋斗的创业精神</h3>
        <p><strong>勤俭节约：</strong>雷锋衣物破了补好再穿，将津贴用于助人而非个人消费，始终保持艰苦朴素的生活作风。</p>
        <p><strong>自强不息：</strong>在鞍钢423天里，他带动工友冒雨抢运水泥，用行动诠释"艰苦奋斗"的创业精神，展现了顽强拼搏的意志品质。</p>
      </div>
    </div>

    <!-- 学习与实践流程 -->
    <div class="section">
      <h2>三、雷锋精神学习与实践流程</h2>

      <div class="process-flow">
        <div class="process-step">
          <div class="step-number">1</div>
          <div class="step-content">
            <h4>学理论</h4>
            <p>每日读一段雷锋日记，参与"雷锋故事会"，记录学习感悟。通过系统学习，深刻理解雷锋精神的时代内涵和现实意义。</p>
          </div>
        </div>

        <div class="process-step">
          <div class="step-number">2</div>
          <div class="step-content">
            <h4>练技能</h4>
            <p>学习急救、维修等实用技能，参加"雷锋技能营"培训。提升服务他人、奉献社会的能力和水平。</p>
          </div>
        </div>

        <div class="process-step">
          <div class="step-number">3</div>
          <div class="step-content">
            <h4>做小事</h4>
            <ul>
              <li><strong>每日一善：</strong>如帮邻居取快递、公共交通让座等</li>
              <li><strong>每周一次社区服务：</strong>清理楼道卫生、帮助老人买菜购物等</li>
              <li><strong>每月一次主题实践：</strong>环保宣传、爱心义卖、扶贫帮困等</li>
            </ul>
          </div>
        </div>

        <div class="process-step">
          <div class="step-number">4</div>
          <div class="step-content">
            <h4>重行动</h4>
            <p>加入"雷锋志愿队"，参与助残、助学等公益活动，结合职业特长开展服务（如教师送教上门、医生义诊、技术人员义务维修等）。</p>
          </div>
        </div>

        <div class="process-step">
          <div class="step-number">5</div>
          <div class="step-content">
            <h4>善反思</h4>
            <p>写实践日志，记录每次服务的心得体会；定期组织团队复盘，总结经验教训，不断改进服务方式和内容。</p>
          </div>
        </div>

        <div class="process-step">
          <div class="step-number">6</div>
          <div class="step-content">
            <h4>传精神</h4>
            <p>创作雷锋主题短视频，带青少年参与志愿活动，讲述新时代雷锋故事。通过多种形式传播雷锋精神，扩大影响力。</p>
          </div>
        </div>

        <div class="process-step">
          <div class="step-number">7</div>
          <div class="step-content">
            <h4>闭环提升</h4>
            <p>从点滴小事到持续践行，建立长效机制，让雷锋精神真正融入日常工作和生活，代代相传，发扬光大。</p>
          </div>
        </div>
      </div>

      <div class="quote-box">
        <p>"学习雷锋精神，就要把崇高的理想信念和道德品质追求融入日常的工作生活，在自己岗位上做一颗永不生锈的螺丝钉。"</p>
        <div class="author">—— 习近平</div>
      </div>
    </div>
    <!-- 页脚 -->
    <div class="footer">
      <p>© 2023 红榜凝力量 榜样润初心 - 雷锋精神学习工单</p>
      <p>制作单位：红色主题教育实践活动领导小组</p>
      <p>本工单可导出为PDF文件用于学习教育活动</p>
    </div>
  </div>
</body>

</html>
</body>

</html>
