<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>奕明任务管理系统</title>
    <style>
        body {
            font-family: 'Microsoft YaHei', sans-serif;
            line-height: 1.6;
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
            color: #333;
            background-color: #f5f5f5;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            border-radius: 5px;
            margin-bottom: 20px;
            text-align: center;
        }
        .profile {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }
        .profile img {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            margin-right: 20px;
            border: 3px solid #3498db;
        }
        .profile-info h2 {
            margin: 0;
            color: #3498db;
        }
        .profile-info p {
            margin: 5px 0;
            color: #7f8c8d;
        }
        .task-container {
            display: flex;
            gap: 20px;
        }
        .task-column {
            flex: 1;
            background-color: white;
            border-radius: 5px;
            padding: 15px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .task-column h3 {
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
            color: #2c3e50;
        }
        .task {
            background-color: #f9f9f9;
            padding: 10px;
            margin-bottom: 10px;
            border-left: 4px solid #3498db;
            border-radius: 3px;
        }
        .task h4 {
            margin: 0 0 5px 0;
            color: #2c3e50;
        }
        .task p {
            margin: 5px 0;
            color: #7f8c8d;
            font-size: 14px;
        }
        .priority-high {
            border-left-color: #e74c3c;
        }
        .priority-medium {
            border-left-color: #f39c12;
        }
        .priority-low {
            border-left-color: #2ecc71;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            padding: 10px;
            color: #7f8c8d;
            font-size: 12px;
        }
    </style>
</head>
<body>
    <header>
        <h1>广州奕明科技有限公司任务管理系统</h1>
    </header>

    <div class="profile">
        <img src="https://via.placeholder.com/80" alt="奕明头像">
        <div class="profile-info">
            <h2>奕明</h2>
            <p>广州奕明科技有限公司总经理</p>
            <p>今日任务：7项 | 已完成：3项</p>
        </div>
    </div>

    <div class="task-container">
        <div class="task-column">
            <h3>待处理</h3>
            <div class="task priority-high">
                <h4>与投资方会议</h4>
                <p>时间：今天 14:00</p>
                <p>地点：公司会议室A</p>
                <p>准备融资计划书</p>
            </div>
            <div class="task priority-medium">
                <h4>新产品研发评审</h4>
                <p>时间：明天 10:00</p>
                <p>需要审核技术团队提交的方案</p>
            </div>
        </div>

        <div class="task-column">
            <h3>进行中</h3>
            <div class="task priority-high">
                <h4>年度财报编制</h4>
                <p>财务部正在准备数据</p>
                <p>截止日期：本周五</p>
            </div>
            <div class="task priority-medium">
                <h4>员工培训计划</h4>
                <p>与HR部门讨论新员工培训方案</p>
                <p>已完成初步框架</p>
            </div>
            <div class="task priority-low">
                <h4>办公室装修</h4>
                <p>设计方案已确认</p>
                <p>施工方下周进场</p>
            </div>
        </div>

        <div class="task-column">
            <h3>已完成</h3>
            <div class="task">
                <h4>董事会季度报告</h4>
                <p>已完成并发送给各位董事</p>
                <p>完成时间：昨天</p>
            </div>
            <div class="task">
                <h4>新员工面试</h4>
                <p>技术岗位3人，市场岗位2人</p>
                <p>已发出offer</p>
            </div>
            <div class="task">
                <h4>供应商合同续签</h4>
                <p>主要供应商合同已续签一年</p>
                <p>条款有所优化</p>
            </div>
        </div>
    </div>

    <footer>
        <p>© 2023 广州奕明科技有限公司 - 总经理办公室</p>
        <p>最后更新：2023年11月15日</p>
    </footer>
</body>
</html>
