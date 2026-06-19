<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>中文考试成绩在线验证结果查询</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: "Microsoft YaHei", "SimSun", sans-serif;
        }
        body {
            max-width: 980px;
            margin: 24px auto;
            padding: 0 16px;
            color: #1a1a1a;
            background-color: #ffffff;
        }
        .page-main-title {
            text-align: center;
            font-size: 26px;
            font-weight: 600;
            margin-bottom: 6px;
        }
        .page-subtitle {
            text-align: center;
            font-size: 14px;
            color: #505050;
            margin-bottom: 32px;
        }
        .info-card {
            border: 1px solid #d0d7e0;
            border-radius: 3px;
            margin-bottom: 20px;
            overflow: hidden;
        }
        .card-header {
            background-color: #f3f6fa;
            padding: 11px 14px;
            font-size: 15px;
            font-weight: 500;
            border-bottom: 1px solid #d0d7e0;
        }
        .data-row {
            display: flex;
            border-bottom: 1px solid #eee;
        }
        .data-label {
            width: 122px;
            background: #f7f9fc;
            padding: 10px 12px;
            border-right: 1px solid #eee;
            font-size: 14px;
        }
        .data-value {
            flex: 1;
            padding: 10px 12px;
            font-size: 14px;
        }
        .row-with-avatar {
            display: flex;
        }
        .text-container {
            flex-grow: 1;
        }
        .avatar-container {
            width: 145px;
            padding: 10px;
        }
        .avatar-container img {
            width: 100%;
            border: 1px solid #cccccc;
            display: block;
        }
        .score-table {
            width: 100%;
            border-collapse: collapse;
        }
        .score-table th, .score-table td {
            border: 1px solid #dddddd;
            padding: 12px 6px;
            text-align: center;
            font-size: 14px;
        }
        .score-table th {
            background-color: #f3f6fa;
        }
        .footer-text {
            text-align: center;
            font-size: 12px;
            color: #666666;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <h1 class="page-main-title">中文考试成绩在线验证结果查询</h1>
    <div class="page-subtitle">汉考国际教育科技（北京）有限公司 (CTI)</div>

    <!-- Блок данных студента -->
    <div class="info-card">
        <div class="card-header">考生信息</div>
        <div class="row-with-avatar">
            <div class="text-container">
                <div class="data-row">
                    <div class="data-label">证件姓名</div>
                    <div class="data-value">CHARYMUHAMMEDOVA LEYLI</div>
                </div>
                <div class="data-row">
                    <div class="data-label">中文姓名</div>
                    <div class="data-value">雷丽</div>
                </div>
                <div class="data-row">
                    <div class="data-label">国籍</div>
                    <div class="data-value">土库曼斯坦</div>
                </div>
                <div class="data-row">
                    <div class="data-label">性别</div>
                    <div class="data-value">女</div>
                </div>
            </div>
            <div class="avatar-container">
                <img src="photo.jpg" alt="Личное фото">
            </div>
        </div>
    </div>

    <!-- Блок данных экзамена -->
    <div class="info-card">
        <div class="card-header">考试信息</div>
        <div class="data-row">
            <div class="data-label">考点名称</div>
            <div class="data-value">广西大学（网考）</div>
        </div>
        <div class="data-row">
            <div class="data-label">准考证号</div>
            <div class="data-value">H42604100048371583 H82604100048371585</div>
        </div>
        <div class="data-row">
            <div class="data-label">证书编号</div>
            <div class="data-value">H42605001480</div>
        </div>
        <div class="data-row">
            <div class="data-label">考试类型</div>
            <div class="data-value">HSK四级</div>
        </div>
        <div class="data-row">
            <div class="data-label">考试时间</div>
            <div class="data-value">16-May-2026</div>
        </div>
    </div>

    <!-- Таблица HSK 4 -->
    <div class="info-card">
        <div class="card-header">HSK四级(16-May-2026)中文水平考试</div>
        <table class="score-table">
            <thead>
                <tr>
                    <th>听力</th>
                    <th>阅读</th>
                    <th>写作</th>
                    <th>总分</th>
                    <th>合格情况</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>83</td>
                    <td>81</td>
                    <td>75</td>
                    <td>239</td>
                    <td>合格</td>
                </tr>
            </tbody>
        </table>
    </div>

    <!-- Таблица устного экзамена HSKK -->
    <div class="info-card">
        <div class="card-header">HSKK（中级）(16-May-2026)中文水平考试</div>
        <table class="score-table">
            <thead>
                <tr>
                    <th>口语</th>
                    <th>总分</th>
                    <th>合格情况</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>65</td>
                    <td>65</td>
                    <td>合格</td>
                </tr>
            </tbody>
        </table>
    </div>

    <div class="footer-text">最终解释权归汉考国际所有</div>
</body>
</html>
