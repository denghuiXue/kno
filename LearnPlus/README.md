# 🤖小喔RPA设计器开发教学
<div class="course-container">
    <div class="course-card">
        <div class="course-header">
             <span class="icon">📺</span>
            <h2>RPA设计器教程</h2>
            <a href="https://space.bilibili.com/1551547224/channel/series" class="btn-watch" style="color: white;">
                观看视频教程
                <span class="arrow">→</span>
            </a>
        </div>
        
        <div class="course-content">
            <div class="version-card new">
                <span class="badge">推荐</span>
                <h4 style="color: white;">3.2 版本系列</h4>
                <div class="feature-list">
                    <div class="feature-item">
                        <span class="feature-icon">✨</span>
                        <span>全新界面，操作更简单</span>
                    </div>
                    <div class="feature-item">
                        <span class="feature-icon">📚</span>
                        <span>按合集顺序循序渐进</span>
                    </div>
                    <div class="feature-item">
                        <span class="feature-icon">🚀</span>
                        <span>包含最新特性教学</span>
                    </div>
                </div>
            </div>
            
            <div class="version-card legacy">
                <span class="badge">经典</span>
                <h4 style="color: white;">3.0 版本系列</h4>
                <p>完整学习路径：</p>
                <ul style="list-style-type: none; padding-left: 0;">
                    <li><span class="step-icon">1️⃣</span> 入门基础教程</li>
                    <li><span class="step-icon">2️⃣</span> 基本功能实践</li>
                    <li><span class="step-icon">3️⃣</span> 实战案例演示</li>
                    <li><span class="step-icon">4️⃣</span> 进阶技巧与开发</li>
                    <li><span class="step-icon">5️⃣</span> 3.1版本新特性</li>
                </ul>
            </div>
        </div>
    </div>
</div>

<style>
.course-container {
    margin: 30px 0;
}

.course-card {
    background: linear-gradient(145deg, #1a237e, #0d47a1);
    border-radius: 16px;
    padding: 25px;
    color: white;
    box-shadow: 0 8px 32px rgba(31, 38, 135, 0.15);
}

.course-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 20px;
}

.icon {
    font-size: 24px;
}

.btn-watch {
    background: rgba(255, 255, 255, 0.15);
    backdrop-filter: blur(5px);
    border: 1px solid rgba(255, 255, 255, 0.2);
    padding: 10px 20px;
    border-radius: 30px;
    color: white;
    text-decoration: none;
    display: flex;
    align-items: center;
    gap: 8px;
    transition: all 0.3s ease;
}

.btn-watch:hover {
    background: rgba(255, 255, 255, 0.25);
    border-color: rgba(255, 255, 255, 0.3);
    transform: translateX(5px);
}

.arrow {
    font-size: 18px;
}

.course-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
}

.version-card {
    background: rgba(255, 255, 255, 0.1);
    border-radius: 12px;
    padding: 20px;
    position: relative;
    transition: transform 0.3s ease;
}

.version-card:hover {
    transform: translateY(-5px);
}

.badge {
    position: absolute;
    top: -10px;
    right: 10px;
    background: #4CAF50;
    padding: 5px 10px;
    border-radius: 20px;
    font-size: 12px;
}

.version-card.legacy .badge {
    background: #FFA000;
}

.version-card h4 {
    margin: 0 0 15px 0;
    font-size: 18px;
}

.version-card p {
    margin: 0 0 10px 0;
    opacity: 0.9;
}

.version-card ol {
    margin: 0;
    padding-left: 20px;
}

.version-card li {
    margin: 5px 0;
    opacity: 0.9;
}

@media (max-width: 768px) {
    .course-content {
        grid-template-columns: 1fr;
    }
    
    .course-header {
        flex-direction: column;
        gap: 15px;
        text-align: center;
    }
}

.course-header h2 {
    color: white;
    margin: 0;
    font-size: 24px;
}

.feature-list {
    margin-top: 15px;
}

.feature-item {
    display: flex;
    align-items: center;
    gap: 10px;
    margin: 10px 0;
}

.feature-icon {
    font-size: 16px;
}

.step-icon {
    margin-right: 8px;
    opacity: 0.9;
}

@media (max-width: 768px) {
    .course-header h2 {
        font-size: 20px;
    }
    
    .feature-item {
        font-size: 14px;
    }
}
</style> 