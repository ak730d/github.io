// 1. 测评题目数据（60题，R/I/A/S/E/C各10题）
const questions = [
    { id: 1, text: "喜欢动手拆装家电、家具等物品", dimension: "R" },
    { id: 2, text: "乐于通过实验验证自己的猜想", dimension: "I" },
    { id: 3, text: "喜欢用绘画、书法等方式表达自己的情绪", dimension: "A" },
    { id: 4, text: "愿意主动安慰情绪低落的朋友", dimension: "S" },
    { id: 5, text: "渴望成为团队中的领导者并主导决策", dimension: "E" },
    { id: 6, text: "习惯将各类文件、物品整理得井井有条", dimension: "C" },
    { id: 7, text: "喜欢参与木工、电工等手工制作类活动", dimension: "R" },
    { id: 8, text: "热衷于钻研数学、物理等学科的难题", dimension: "I" },
    { id: 9, text: "经常创作诗歌、散文或小故事", dimension: "A" },
    { id: 10, text: "愿意参与社区志愿服务帮助他人", dimension: "S" },
    { id: 11, text: "喜欢策划并组织各类集体活动", dimension: "E" },
    { id: 12, text: "严格按照流程和规范完成工作任务", dimension: "C" },
    { id: 13, text: "向往从事机械维修、建筑施工类工作", dimension: "R" },
    { id: 14, text: "喜欢查阅学术论文、研究报告等资料", dimension: "I" },
    { id: 15, text: "喜欢欣赏音乐会、画展等艺术活动", dimension: "A" },
    { id: 16, text: "擅长倾听他人的烦恼并给出建议", dimension: "S" },
    { id: 17, text: "对销售、谈判类工作感兴趣", dimension: "E" },
    { id: 18, text: "愿意从事数据录入、账目核对等重复性工作", dimension: "C" },
    { id: 19, text: "喜欢户外体力劳动，如园艺、登山等", dimension: "R" },
    { id: 20, text: "喜欢思考自然界或社会中的未知问题", dimension: "I" },
    { id: 21, text: "有学习乐器、舞蹈等艺术技能的意愿", dimension: "A" },
    { id: 22, text: "希望从事教师、心理咨询师等助人职业", dimension: "S" },
    { id: 23, text: "梦想创办属于自己的公司", dimension: "E" },
    { id: 24, text: "做事注重细节，避免出现疏漏", dimension: "C" },
    { id: 25, text: "擅长使用工具解决实际问题", dimension: "R" },
    { id: 26, text: "享受独立思考并分析问题的过程", dimension: "I" },
    { id: 27, text: "喜欢为自己的生活环境设计装饰方案", dimension: "A" },
    { id: 28, text: "乐于参与集体活动并融入团队", dimension: "S" },
    { id: 29, text: "敢于在公开场合发表自己的观点和主张", dimension: "E" },
    { id: 30, text: "喜欢按照既定的计划一步步完成目标", dimension: "C" },
    { id: 31, text: "不排斥从事需要体力付出的蓝领工作", dimension: "R" },
    { id: 32, text: "对新科技、新理论的探索充满兴趣", dimension: "I" },
    { id: 33, text: "喜欢改编歌曲、剧本等文艺作品", dimension: "A" },
    { id: 34, text: "愿意帮助他人解决生活或工作中的困难", dimension: "S" },
    { id: 35, text: "对市场调研、商业分析类工作感兴趣", dimension: "E" },
    { id: 36, text: "能够耐心处理大量的文字或数据资料", dimension: "C" },
    { id: 37, text: "喜欢组装模型、修理自行车等动手活动", dimension: "R" },
    { id: 38, text: "喜欢做逻辑推理、数据分析类题目", dimension: "I" },
    { id: 39, text: "有参加艺术比赛、文艺演出的意愿", dimension: "A" },
    { id: 40, text: "擅长协调人际关系，化解矛盾", dimension: "S" },
    { id: 41, text: "希望通过自己的努力获得更高的职位和收入", dimension: "E" },
    { id: 42, text: "重视规则和秩序，不喜欢随意变动", dimension: "C" },
    { id: 43, text: "向往从事农业种植、养殖等工作", dimension: "R" },
    { id: 44, text: "愿意花费时间研究一个复杂的问题直到解决", dimension: "I" },
    { id: 45, text: "喜欢用摄影、短视频记录生活", dimension: "A" },
    { id: 46, text: "享受帮助他人成长和进步的过程", dimension: "S" },
    { id: 47, text: "敢于尝试有挑战性的商业项目", dimension: "E" },
    { id: 48, text: "擅长制作详细的工作计划和报表", dimension: "C" },
    { id: 49, text: "喜欢操作各类机械设备并学习其原理", dimension: "R" },
    { id: 50, text: "对天文、地理等未知领域充满好奇", dimension: "I" },
    { id: 51, text: "有设计服装、饰品等创意类作品的想法", dimension: "A" },
    { id: 52, text: "愿意参与公益募捐、扶贫等助人活动", dimension: "S" },
    { id: 53, text: "喜欢向他人推销产品或理念", dimension: "E" },
    { id: 54, text: "能够准确无误地完成重复性的行政工作", dimension: "C" },
    { id: 55, text: "不介意工作环境艰苦，注重实际成果", dimension: "R" },
    { id: 56, text: "喜欢撰写研究报告、学术论文", dimension: "I" },
    { id: 57, text: "享受即兴创作音乐、绘画的过程", dimension: "A" },
    { id: 58, text: "希望从事医护、社工等服务他人的职业", dimension: "S" },
    { id: 59, text: "有参加商业谈判、竞标等活动的意愿", dimension: "E" },
    { id: 60, text: "喜欢整理各类票据、档案并分类归档", dimension: "C" }
];

// 2. 维度配置（名称、颜色、图标、解读）
const dimensionConfig = {
    R: {
        name: "现实型",
        color: "#FF9800",
        icon: "🔧",
        desc: "偏好与物体打交道，动手能力强，喜欢具体、实际操作性的工作。适合从事机械维修、建筑施工、农业种植、技术工人等职业。"
    },
    I: {
        name: "研究型",
        color: "#409EFF",
        icon: "🔍",
        desc: "喜欢思考和分析，好奇心强，追求知识和真理，擅长抽象思维。适合从事科研、数据分析、学术研究、工程师等职业。"
    },
    A: {
        name: "艺术型",
        color: "#9C27B0",
        icon: "🎨",
        desc: "富有创造力和想象力，追求美感和自我表达，喜欢艺术和创意类工作。适合从事设计、音乐、文学、影视创作等职业。"
    },
    S: {
        name: "社会型",
        color: "#F56C6C",
        icon: "❤️",
        desc: "乐于助人，善于沟通和社交，关心他人福祉，喜欢服务和教育类工作。适合从事教师、医护、心理咨询、社工等职业。"
    },
    E: {
        name: "企业型",
        color: "#67C23A",
        icon: "🧢",
        desc: "喜欢领导和管理，有野心和抱负，擅长说服和谈判，追求成功和成就。适合从事销售、管理、创业、市场营销等职业。"
    },
    C: {
        name: "常规型",
        color: "#909399",
        icon: "📄",
        desc: "注重规则和秩序，细心严谨，喜欢有条理、重复性的工作。适合从事行政、财务、档案管理、数据录入等职业。"
    }
};

// 3. 职业推荐配置
const careerRecommend = {
    R: [
        { name: "机械维修师", icon: "🔧", desc: "匹配R（现实型）特质，擅长动手操作，解决设备故障问题" },
        { name: "建筑工人", icon: "🏗️", desc: "匹配R（现实型）特质，适应体力劳动，注重实际成果" },
        { name: "农业技术员", icon: "🌱", desc: "匹配R（现实型）特质，擅长田间操作，掌握种植养殖技术" }
    ],
    I: [
        { name: "数据分析师", icon: "📊", desc: "匹配I（研究型）特质，擅长逻辑分析，从数据中挖掘价值" },
        { name: "科研人员", icon: "🔬", desc: "匹配I（研究型）特质，热爱探索未知，专注学术研究" },
        { name: "软件工程师", icon: "💻", desc: "匹配I（研究型）特质，喜欢钻研技术，解决复杂技术问题" }
    ],
    A: [
        { name: "UI设计师", icon: "🎨", desc: "匹配A（艺术型）特质，富有创意，擅长视觉设计和审美表达" },
        { name: "文案策划", icon: "✍️", desc: "匹配A（艺术型）特质，擅长文字创作，有独特的表达风格" },
        { name: "音乐教师", icon: "🎵", desc: "匹配A（艺术型）特质，热爱艺术创作，擅长音乐表达" }
    ],
    S: [
        { name: "心理咨询师", icon: "🗣️", desc: "匹配S（社会型）特质，善于倾听沟通，帮助他人解决心理问题" },
        { name: "中小学教师", icon: "📚", desc: "匹配S（社会型）特质，热爱教育事业，帮助学生成长进步" },
        { name: "社工", icon: "🤝", desc: "匹配S（社会型）特质，热心公益，帮助弱势群体解决生活困难" }
    ],
    E: [
        { name: "销售经理", icon: "📢", desc: "匹配E（企业型）特质，擅长沟通谈判，具备领导和管理能力" },
        { name: "创业家", icon: "🚀", desc: "匹配E（企业型）特质，敢于挑战，有商业头脑和决策能力" },
        { name: "市场总监", icon: "📈", desc: "匹配E（企业型）特质，具备商业思维，擅长市场策略制定" }
    ],
    C: [
        { name: "财务会计", icon: "💰", desc: "匹配C（常规型）特质，细心严谨，擅长数据处理和账目管理" },
        { name: "行政专员", icon: "📋", desc: "匹配C（常规型）特质，注重规则，擅长文档整理和流程执行" },
        { name: "档案管理员", icon: "🗂️", desc: "匹配C（常规型）特质，耐心细致，擅长资料分类和管理" }
    ]
};

// 4. 全局状态管理
const state = {
    currentQuestion: 0, // 当前题目索引（从0开始）
    answers: [], // 用户答案数组，格式：[{id:1, answer:"是"}, ...]
    scores: { R:0, I:0, A:0, S:0, E:0, C:0 }, // 各维度得分
    top3Dimensions: [] // 前三高维度
};

// 5. DOM元素获取
const elements = {
    // 页面
    homePage: document.getElementById('home-page'),
    quizPage: document.getElementById('quiz-page'),
    resultPage: document.getElementById('result-page'),
    
    // 首页元素
    startBtn: document.getElementById('start-btn'),
    
    // 答题页元素
    progressText: document.getElementById('progress-text'),
    progressFill: document.getElementById('progress-fill'),
    questionText: document.getElementById('question-text'),
    optionYes: document.getElementById('option-yes'),
    optionNo: document.getElementById('option-no'),
    prevBtn: document.getElementById('prev-btn'),
    nextBtn: document.getElementById('next-btn'),
    toast: document.getElementById('toast'),
    
    // 结果页元素
    coreDimensions: document.getElementById('core-dimensions'),
    scoreOverview: document.getElementById('score-overview'),
    dimensionList: document.getElementById('dimension-list'),
    careerList: document.getElementById('career-list'),
    restartBtn: document.getElementById('restart-btn'),
    saveBtn: document.getElementById('save-btn'),
    saveToast: document.getElementById('save-toast')
};

// 6. 页面切换函数
function switchPage(pageId) {
    document.querySelectorAll('.page').forEach(page => {
        page.classList.remove('active');
    });
    document.getElementById(pageId).classList.add('active');
}

// 7. 初始化答题页
function initQuizPage() {
    // 重置选项状态
    elements.optionYes.className = 'option-btn option-unselected';
    elements.optionNo.className = 'option-btn option-unselected';
    
    // 更新题目内容
    const question = questions[state.currentQuestion];
    elements.questionText.textContent = question.text;
    
    // 更新进度
    const currentNum = state.currentQuestion + 1;
    elements.progressText.textContent = `第${currentNum}题/共60题`;
    elements.progressFill.style.width = `${(currentNum / 60) * 100}%`;
    
    // 更新上一题按钮状态
    if (currentNum === 1) {
        elements.prevBtn.classList.add('btn-disabled');
        elements.prevBtn.disabled = true;
    } else {
        elements.prevBtn.classList.remove('btn-disabled');
        elements.prevBtn.disabled = false;
    }
    
    // 恢复用户之前的答案
    const savedAnswer = state.answers.find(item => item.id === question.id);
    if (savedAnswer) {
        if (savedAnswer.answer === "是") {
            elements.optionYes.className = 'option-btn option-selected';
            elements.optionNo.className = 'option-btn option-unselected';
        } else {
            elements.optionNo.className = 'option-btn option-selected';
            elements.optionYes.className = 'option-btn option-unselected';
        }
    }
}

// 8. 计算得分
function calculateScores() {
    // 重置得分
    state.scores = { R:0, I:0, A:0, S:0, E:0, C:0 };
    
    // 统计得分
    state.answers.forEach(answer => {
        const question = questions.find(q => q.id === answer.id);
        if (answer.answer === "是") {
            state.scores[question.dimension] += 1;
        }
    });
    
    // 排序获取前三高维度
    state.top3Dimensions = Object.entries(state.scores)
        .sort((a, b) => b[1] - a[1])
        .slice(0, 3)
        .map(item => item[0]);
}

// 9. 渲染结果页
function renderResultPage() {
    // 更新核心维度展示
    const coreText = `你的核心职业倾向：${state.top3Dimensions.join('·')}`;
    elements.coreDimensions.textContent = coreText;
    
    // 更新总分概览
    const scoreText = `R:${state.scores.R}分 | I:${state.scores.I}分 | A:${state.scores.A}分 | S:${state.scores.S}分 | E:${state.scores.E}分 | C:${state.scores.C}分`;
    elements.scoreOverview.textContent = scoreText;
    
    // 渲染维度列表
    elements.dimensionList.innerHTML = '';
    Object.entries(state.scores).forEach(([dim, score]) => {
        const config = dimensionConfig[dim];
        const dimensionItem = document.createElement('div');
        dimensionItem.className = 'dimension-item';
        dimensionItem.innerHTML = `
            <div class="dimension-header">
                <div class="dimension-name" style="color: ${config.color}">
                    <span class="dimension-icon">${config.icon}</span>
                    ${dim}（${config.name}）
                </div>
                <div class="dimension-score">${score}分</div>
            </div>
            <div class="dimension-detail">${config.desc}</div>
        `;
        
        // 维度展开/折叠交互
        dimensionItem.addEventListener('click', () => {
            const detail = dimensionItem.querySelector('.dimension-detail');
            detail.classList.toggle('show');
        });
        
        elements.dimensionList.appendChild(dimensionItem);
    });
    
    // 渲染职业推荐（取前三维度的职业）
    elements.careerList.innerHTML = '';
    const careerPool = [];
    state.top3Dimensions.forEach(dim => {
        careerPool.push(...careerRecommend[dim]);
    });
    
    // 取前3个职业展示
    careerPool.slice(0, 3).forEach(career => {
        const careerCard = document.createElement('div');
        careerCard.className = 'career-card';
        careerCard.innerHTML = `
            <div class="career-name">
                <span class="career-icon">${career.icon}</span>
                ${career.name}
            </div>
            <div class="career-desc">${career.desc}</div>
        `;
        elements.careerList.appendChild(careerCard);
    });
}

// 10. 显示提示框
function showToast(toastEl, text, duration = 2000) {
    toastEl.textContent = text;
    toastEl.style.display = 'block';
    setTimeout(() => {
        toastEl.style.display = 'none';
    }, duration);
}

// 11. 事件绑定
function bindEvents() {
    // 首页 - 开始测评
    elements.startBtn.addEventListener('click', () => {
        state.currentQuestion = 0;
        state.answers = [];
        switchPage('quiz-page');
        initQuizPage();
    });
    
    // 答题页 - 选项点击
    elements.optionYes.addEventListener('click', () => {
        elements.optionYes.className = 'option-btn option-selected';
        elements.optionNo.className = 'option-btn option-unselected';
    });
    
    elements.optionNo.addEventListener('click', () => {
        elements.optionNo.className = 'option-btn option-selected';
        elements.optionYes.className = 'option-btn option-unselected';
    });
    
    // 答题页 - 上一题
    elements.prevBtn.addEventListener('click', () => {
        if (state.currentQuestion > 0) {
            state.currentQuestion--;
            initQuizPage();
        }
    });
    
    // 答题页 - 下一题
    elements.nextBtn.addEventListener('click', () => {
        // 检查是否选择答案
        let selectedAnswer = null;
        if (elements.optionYes.classList.contains('option-selected')) {
            selectedAnswer = "是";
        } else if (elements.optionNo.classList.contains('option-selected')) {
            selectedAnswer = "否";
        }
        
        if (!selectedAnswer) {
            showToast(elements.toast, "请选择答案后继续");
            return;
        }
        
        // 保存答案
        const currentQId = questions[state.currentQuestion].id;
        const existingAnswerIndex = state.answers.findIndex(item => item.id === currentQId);
        
        if (existingAnswerIndex > -1) {
            state.answers[existingAnswerIndex].answer = selectedAnswer;
        } else {
            state.answers.push({ id: currentQId, answer: selectedAnswer });
        }
        
        // 判断是否是最后一题
        if (state.currentQuestion === 59) {
            // 最后一题，计算得分并跳转到结果页
            calculateScores();
            renderResultPage();
            switchPage('result-page');
        } else {
            // 下一题
            state.currentQuestion++;
            initQuizPage();
        }
    });
    
    // 结果页 - 重新测评
    elements.restartBtn.addEventListener('click', () => {
        // 重置状态
        state.currentQuestion = 0;
        state.answers = [];
        state.scores = { R:0, I:0, A:0, S:0, E:0, C:0 };
        state.top3Dimensions = [];
        
        switchPage('home-page');
    });
    
    // 结果页 - 保存结果
    elements.saveBtn.addEventListener('click', () => {
        showToast(elements.saveToast, "长按屏幕保存测评结果", 3000);
    });
    
    // 微信分享适配（实际使用需配置JS-SDK）
    document.addEventListener('WeixinJSBridgeReady', function() {
        // 分享给好友
        WeixinJSBridge.on('menu:share:appmessage', function() {
            WeixinJSBridge.invoke('sendAppMessage', {
                title: '霍兰德职业兴趣测评',
                desc: '60题解锁你的职业天赋，快来试试吧！',
                link: window.location.href,
                imgUrl: '' // 替换为你的分享图片链接
            });
        });
        
        // 分享到朋友圈
        WeixinJSBridge.on('menu:share:timeline', function() {
            WeixinJSBridge.invoke('shareTimeline', {
                title: '霍兰德职业兴趣测评 - 60题解锁你的职业天赋',
                link: window.location.href,
                imgUrl: '' // 替换为你的分享图片链接
            });
        });
    });
}

// 12. 初始化应用
function initApp() {
    bindEvents();
    // 适配移动端触摸事件
    document.addEventListener('touchstart', function() {}, false);
}

// 启动应用
initApp();