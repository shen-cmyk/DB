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
申江丽 网页设计
