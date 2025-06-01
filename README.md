<!DOCTYPE html>
<html lang="zh">
// ... existing code ...
    <header class="header">
        <h1>万彪课题组</h1>
        <p>地球表层环境中铁-碳-磷多要素生物地球化学耦联循环</p>
    </header>
// ... existing code ...
    <main class="main">
        <section id="about" class="section">
            <h2>关于我们</h2>
            <p>本课题组主要研究地球表层环境中铁-碳-磷多要素生物地球化学耦联循环，为揭示土壤特征元素全生命周期的生态效应提供理论支撑。研究成果以第一作者或通讯作者(含共一、共通) 发表在Environ Sci Tech，Geochim Cosmochim Ac，Environ Int，Eur J Soil Sci等国际权威杂志。</p>
        </section>

        <section id="research" class="section">
            <h2>研究方向</h2>
            <div class="research-areas">
                <div class="research-item">
                    <h3>1. 先进光谱与成像技术应用</h3>
                    <p>在环境化学及地质微生物学中的应用研究</p>
                </div>
                <div class="research-item">
                    <h3>2. 铁-碳-磷地球化学循环</h3>
                    <p>生物与非生物作用共同介导下的协同循环机制</p>
                </div>
                <div class="research-item">
                    <h3>3. 生物源铁矿物形成机制</h3>
                    <p>空间构造及细胞碳-矿物铁互作机制研究</p>
                </div>
                <div class="research-item">
                    <h3>4. 环境磷素循环</h3>
                    <p>微生物作用驱动的生物地球化学循环</p>
                </div>
                <div class="research-item">
                    <h3>5. 铁磷转化机制</h3>
                    <p>有氧-无氧环境中不同磷素与铁矿物界面行为研究</p>
                </div>
            </div>
        </section>

        <section id="team" class="section">
            <h2>团队成员</h2>
            <div class="team-grid">
                <div class="team-member">
                    <img src="placeholder.jpg" alt="万彪教授照片">
                    <h3>万彪</h3>
                    <p>教授、博士生导师</p>
                    <div class="member-info">
                        <p><strong>教育背景：</strong></p>
                        <ul>
                            <li>2020年 美国佐治亚理工学院 地球化学 博士</li>
                            <li>2016年 华中农业大学 环境科学 硕士</li>
                            <li>2013年 华中农业大学 环境科学 学士</li>
                        </ul>
                        <p><strong>工作经历：</strong></p>
                        <ul>
                            <li>2024-至今 华中农业大学 教授</li>
                            <li>2021-2023 德国图宾根大学 博士后</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <section id="publications" class="section">
            <h2>发表论文</h2>
            <div class="publications-list">
                <div class="publication-item">
                    <h3>代表性论文</h3>
                    <ul>
                        <li>Yan YP, Feng XH, Wang XM, et al. Transformation of zinc oxide nanoparticles in the presence of aluminum oxide with pre-sorbed phosphorus ligands. Environmental International, 2023</li>
                        <li>Wan B, Huang RX, Diaz J, et al. Rethinking the biotic and abiotic remineralization of complex phosphate molecules in soils and sediments. Science of the Total Environment, 2022</li>
                        <li>Wan B, Yang P, Jung HS, et al. Iron oxide-catalyzed hydrolysis of polyphosphate and the precipitation of calcium phosphate minerals. Geochimica et Cosmochimica Acta, 2021</li>
                    </ul>
                </div>
            </div>
        </section>

        <section id="contact" class="section">
            <h2>联系我们</h2>
            <div class="contact-info">
                <div class="contact-item">
                    <h3>地址</h3>
                    <p>湖北省武汉市南湖狮子山街一号</p>
                </div>
                <div class="contact-item">
                    <h3>邮箱</h3>
                    <p>wanbiao52@qq.com</p>
                </div>
                <div class="contact-item">
                    <h3>电话</h3>
                    <p>027-87282137</p>
                </div>
            </div>
        </section>
    </main>
// ... existing code ...
<style>
// ... existing code ...
.research-areas {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 1.5rem;
    margin-top: 1.5rem;
}

.research-item {
    background: #f8f9fa;
    padding: 1.5rem;
    border-radius: 8px;
    transition: all 0.3s ease;
    border-left: 4px solid #4a7856;
}

.research-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.research-item h3 {
    color: #2c5530;
    margin-bottom: 0.5rem;
}

.member-info {
    margin-top: 1rem;
    text-align: left;
    font-size: 0.9rem;
}

.member-info ul {
    list-style: none;
    padding-left: 1rem;
    margin: 0.5rem 0;
}

.member-info li {
    margin-bottom: 0.3rem;
    position: relative;
    padding-left: 1rem;
}

.member-info li::before {
    content: "•";
    color: #4a7856;
    position: absolute;
    left: 0;
}

.publications-list {
    background: #f8f9fa;
    padding: 1.5rem;
    border-radius: 8px;
}

.publication-item {
    margin-bottom: 1.5rem;
}

.publication-item ul {
    list-style: none;
    padding-left: 0;
}

.publication-item li {
    margin-bottom: 1rem;
    padding-left: 1.5rem;
    position: relative;
}

.publication-item li::before {
    content: "•";
    color: #4a7856;
    position: absolute;
    left: 0;
}
</style>
// ... existing code ...# link
none
Contributors 申江丽：数据库设计与网页开发
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>谭文峰 - 华中农业大学资源与环境学院</title>
    <style>
        body {
            font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            background-color: #f9f9f9;
            color: #333;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        .section {
            margin-bottom: 30px;
        }
        .contact-info p {
            margin: 5px 0;
        }
        ul {
            list-style-type: disc;
            margin-left: 20px;
        }
    </style>
</head>
<body>

    <h1>谭文峰 教授</h1>
    <p><strong>职称：</strong>教授</p>
    <p><strong>政治面貌：</strong>中共党员</p>
    <p><strong>电话：</strong>027-87287508</p>
    <p><strong>电子邮件：</strong><a href="mailto:tanwf@mail.hzau.edu.cn">tanwf@mail.hzau.edu.cn</a></p>
    <p><strong>研究方向：</strong>土壤化学与环境、土壤健康与农业绿色发展</p>

    <div class="section">
        <h2>个人简介</h2>
        <p>现任国家环境保护土壤健康与绿色修复重点实验室主任、农业农村部长江中下游耕地保育重点实验室主任。长期从事水土界面过程与土壤健康方面的研究工作。本团队是湖北省自然科学基金创新团队，主要围绕“耕地-粮食-环境”中的重要科学问题，系统研究了土壤物质循环与土壤养分的互馈机制、养分/污染元素多界面反应过程与形态模型、农田土壤污染防控与生物修复机理，发展了农田土壤的绿色修复技术。</p>
        <p>先后主持国家自然科学基金重点/国际合作、国家重点研发专项、欧盟“土地退化”等项目20余项；发表学术论文200余篇，其中SCI论文150余篇。曾获中组部“万人计划”科技创新领军人才、科技部科技创新领军人才、国家杰出青年科学基金、教育部新世纪优秀人才计划、湖北省自然科学基金创新群体负责人等。</p>
    </div>

    <div class="section">
        <h2>工作经历</h2>
        <ul>
            <li>2006.11 - 至今：华中农业大学资源与环境学院教授</li>
            <li>2006 - 2007：荷兰 Wageningen 大学博士后</li>
            <li>2002 - 2006：华中农业大学资源与环境学院副教授</li>
            <li>2000 - 2001：华中农业大学资源与环境学院讲师</li>
        </ul>
    </div>

    <div class="section">
        <h2>教育经历</h2>
        <ul>
            <li>1997 - 2000：华中农业大学资源环境与农业化学系 土壤学博士</li>
            <li>1994 - 1997：华中农业大学土壤与农业化学系 土壤学硕士</li>
            <li>1990 - 1994：华中农业大学土壤与农业化学系 本科</li>
        </ul>
    </div>

    <div class="section">
        <h2>教学情况</h2>
        <p><strong>本科生课程：</strong>环境土壤学、土壤修复与地力提升、农业资源与环境导论</p>
        <p><strong>硕士生课程：</strong>资源环境研究专题、环境界面研究法</p>
        <p><strong>博士生课程：</strong>土壤与植物营养研究进展</p>
    </div>

    <div class="section">
        <h2>研究方向</h2>
        <ul>
            <li>土壤矿物-有机物-微生物互作机制及其环境效应</li>
            <li>中低产田障碍因子消减与产能提升</li>
            <li>健康土壤的生态调控</li>
        </ul>
    </div>

    <div class="section">
        <h2>科研项目</h2>
        <ul>
            <li>2021.9 - 2025.12：长江中下游坡耕地红黄壤与中低产稻田产能提升技术模式及应用，国家重点研发计划项目，项目首席</li>
            <li>2021.1 - 2024.12：集约化土地利用驱动下土壤退化机制与生态调控，国家自然科学基金中-阿重点国际合作项目，主持</li>
            <li>2020.1 - 2023.12：球囊霉素与土壤活性组分作用的“超级”胶结机制，国家自然科学基金面上项目，主持</li>
            <!-- 可根据需要添加更多项目 -->
        </ul>
    </div>

    <div class="section">
        <h2>获奖及荣誉</h2>
        <ul>
            <li>2022年9月：华中农业大学师德标兵</li>
            <li>2021年度：华中农业大学研究生导师教书育人奖</li>
            <li>2015年：湖北省科协“科技创新源泉工程”创新创业人才</li>
            <li>2013年：湖北省高等学校教学成果奖（排名第5）</li>
            <li>2012年：华中农业大学教学成果特等奖（排名第5）</li>
            <!-- 可根据需要添加更多奖项 -->
        </ul>
    </div>

    <div class="section">
        <h2>学术兼职</h2>
        <ul>
            <li>国家自然科学基金委员会地学部专家评审组成员（2012年-）</li>
            <li>中国土壤学会青年教育工作委员会副主任（2008年－）</li>
            <li>中国土壤学会土壤化学专业委员会副主任（2012年－）</li>
            <li>中国植物营养学会养分循环与环境委员会副主任(2014年-)</li>
            <li>湖北省青年科技协会常务理事、农科分会秘书长（2002年－）</li>
            <!-- 可根据需要添加更多兼职信息 -->
        </ul>
    </div>

</body>
</html>
