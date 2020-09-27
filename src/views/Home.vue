<template>
  <div class="resume-wrapper">
    <aside class="left-container">
      <img style="width: 120px" src="../assets/left-bg.png" alt="" srcset="">
    </aside>
    <section class="right-container">
      <div class="top">
        <h2 class="name">景睦馨</h2>
        <p class="postion">求职意向：产品经理、算法师、数据分析师</p>
        <ul class="info">
          <li>
            <i class="icon icon-l"></i>
            <span>22 岁</span>
          </li>
          <li>
            <i class="icon icon-d"></i>
            <span>北京 西城区</span>
          </li>
          <li>
            <i class="icon icon-t"></i>
            <span>13821032295</span>
          </li>
          <li>
            <i class="icon icon-m"></i>
            <span>mxj72@psu.edu</span>
          </li>
        </ul>
      </div>
      <div class="education box">
        <p class="title">教育背景</p>
        <ul class="info">
          <li>2016.09-2020.05</li>
          <li>美国宾夕法尼亚大学</li>
          <li>计算机科学（本科 Major）/ 数学（Minor）</li>
        </ul>
        <p class="lable">主修课程</p>
        <p>算法学、统计学、人工智能课程、机械学习模型课程、操作系统课程、商业心理学、数据库管理、计算机应用等</p>
      </div>
      <div class="resume box">
        <p class="title">实践经历</p>
        <ul class="info">
          <li>2017.05-2017.08</li>
          <li>北京甲骨文软件股份有限公司</li>
          <li>云计算数据支持助理</li>
        </ul>
        <ul class="info-list">
          <li>参加云平台培训，学习云平台系统及架构设计、云计算、数据库管理、运维技能</li>
          <li>参与中国移动总部、国航集团、北京排水集团等公司的数据库运维工作</li>
        </ul>
        <ul class="info">
          <li>2018.05-2018.08</li>
          <li>北京微软股份有限公司</li>
          <li>Azure 云 技术岗实习</li>
        </ul>
        <ul class="info-list">
          <li>调试和维护台式机、服务器和外围设备等 IT 设备的安装；</li>
          <li>图像识别调试和开发工作</li>
          <li>使用 SQL 实现数据库操作、配置优化和系统检查</li>
          <li>为客户需求测试和软件产品售后服务提供技术支持</li>
        </ul>
        <ul class="info">
          <li>2019.05-2019.08</li>
          <li>中国交通建设股份有限公司</li>
          <li>信息技术中心</li>
        </ul>
        <ul class="info-list">
          <li>根据 JSON 数据格式，实现并维护 Linux 系统与路由器之间基于 TCP/IP 的数据传输</li>
          <li>负责组织项目文件，收集项目现场信息，协调现场各团队的工作，确保项目顺利进行</li>
          <li>开发了一个 web 应用程序，使用 RESTful 服务和 Swgger API 查询 CCCC FIX 消息的方案</li>
          <li>通过 Tableau 自动化部署过程，引入并建立 DevOps 实践</li>
        </ul>
      </div>
      <div class="learning box">
        <p class="title">学术技能</p>
        <h6>程序设计：Python、C++、C、java、SQL、汇编语言</h6>
        <h6>操作系统：Mac OS、Red Hat Linux、Windows 操作系统</h6>
        <h6>软件应用：Tableau, MS SQL Server, Robomongo, IntelliJ IDE, Eclipse IDE, Adobe Premier 和 Adobe In-design</h6>
      </div>
      <div class="last box">
        <p class="title">学术研究</p>
        <ul class="info">
          <li>2019 年 8 月-2020 年 5 月</li>
          <li>宾夕法尼亚州立大学地理系</li>
          <li>研究助理，由余曼竹博士指导</li>
        </ul>
        <ul class="info-list">
          <li>阅读论文，学习文本挖掘理论</li>
          <li>参与算法工具的开发，可以根据公民查询邮件的内容自动识别和分类为八类</li>
          <li>利用大样本数据集训练算法工具，优化 Python charm 代码，识别速度提高近 30%，识别精度显著提高</li>
        </ul>
        <ul class="info">
          <li>2019 年 8 月-2019 年 5 月</li>
          <li>北京大学遥感与地理信息系统研究所-中国北京</li>
          <li>暑期研究，李梅博士指导</li>
        </ul>
        <ul class="info-list">
          <li>协助开发基于 MVC 的 Java 文本分类研究平台</li>
          <li>参与文本分类中受词性影响的特征加权方法分析，编写爬虫抓取文本；选取几个主要类别的 2100 个文本构建训练集和测试集</li>
        </ul>
        <ul class="info">
          <li>2019 年 1 月-2019 年 5 月 宾夕法尼亚州立大学</li>
          <li>计算机科学数理分析课程 456</li>
          <li>助教</li>
        </ul>
        <ul class="info-list">
          <li>协助教授设计课程作业并回答基本问题</li>
        </ul>
      </div>
    </section>
  </div>
</template>

<script>

export default {
  name: 'Home',
}
</script>

<style scoped>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html, body {
  background: #fff;
  scroll-behavior: smooth;
  font-size: 16px;
}
h6 {
  font-size: 14px;
  font-weight: normal;
  line-height: 1.6;
}
.resume-wrapper {
  display: flex;
  padding: 10px;
}
.left-container {
  width: 200px;
  background: #7bc4e1;
  display: flex;
  justify-content: center;
  align-items: center;
}
.right-container {
  flex: 1;
  padding: 30px;
  color: #333;
}
.top {
  padding: 12px;
  color: #000;
}
.name {
  font-size: 46px;
}
.postion {
  border-bottom: 10px solid #20b6e9;
  padding: 6px 0 20px;
  font-size: 18px;
}
.info {
  list-style: none;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 10px 0;
  font-size: 18px;
}
.info li {
  display: flex;
  align-items: center;
  color: #20b6e9;
}
.info-list {
  margin-bottom: 20px;
}
.info-list li {
  line-height: 1.6;
  font-size: 14px;
}
.icon {
  display: inline-block;
  width: 26px;
  height: 26px;
  background: no-repeat center center;
  background-size: cover;
  margin-top: 3px;
  margin-right: 4px;
}
.icon-l {
  background-image: url('../assets/l.png');
}
.icon-d {
  background-image: url('../assets/d.png');
}
.icon-t {
  background-image: url('../assets/t.png');
}
.icon-m {
  background-image: url('../assets/m.png');
}
.box {
  position: relative;
  z-index: 10000;
  margin-bottom: 30px;
}
.box .title {
  position: relative;
  display: inline-block;
  padding: 8px 40px 8px 60px;
  margin-left: -60px;
  background: #20b6e9;
  font-size: 22px;
  font-weight: 400;
  color: #fff;
  margin-bottom: 20px;
}
.box .title::after {
  content: '';
  display: block;
  border: 30px solid;
  border-color: transparent #0070b7 transparent transparent;
  position: absolute;
  bottom: -34px;
  left: -30px;
  z-index: -2;
  transform: scaleY(.5);
}
.box .title::before {
  content: '';
  display: block;
  width: 30px;
  height: 10px;
  background: #7bc4e1;
  position: absolute;
  bottom: -4px;
  left: 0;
  z-index: -1;
}
.box .lable {
  color: #7bc4e1;
  margin-bottom: 5px;
}
.last .info li {
  color: #5c8edc;
  font-size: 16px;
}
</style>