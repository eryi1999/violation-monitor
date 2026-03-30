<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="refresh" content="0; url=violation_monitor_dashboard_v4.html">
    <title>正在跳转到工作台...</title>
    <script type="text/javascript">
        // 立即跳转
        window.location.href = 'violation_monitor_dashboard_v4.html';
        
        // 如果 1 秒后还没跳转成功，显示手动链接
        setTimeout(function() {
            document.getElementById('manual-link').style.display = 'block';
        }, 1000);
    </script>
    <style>
        body {
            font-family: 'PingFang SC', 'Microsoft YaHei', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
        }
        .loading {
            text-align: center;
            color: #1a5f4a;
        }
        .spinner {
            border: 4px solid #f3f3f3;
            border-top: 4px solid #20b2aa;
            border-radius: 50%;
            width: 40px;
            height: 40px;
            animation: spin 1s linear infinite;
            margin: 0 auto 20px;
        }
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        .manual-link {
            display: none;
            margin-top: 20px;
            padding: 15px 30px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        .manual-link a {
            color: #20b2aa;
            text-decoration: none;
            font-weight: 600;
            font-size: 16px;
        }
        .manual-link a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="loading">
        <div class="spinner"></div>
        <p>正在加载违价监控工作台...</p>
        <p style="color: #999; font-size: 14px; margin-top: 10px;">
            如果页面没有自动跳转，<a href="violation_monitor_dashboard_v4.html" style="color: #20b2aa;">点击这里进入</a>
        </p>
        <div id="manual-link" class="manual-link">
            <p style="margin-bottom: 10px; color: #666;">👇 点击下方链接进入工作台 👇</p>
            <a href="violation_monitor_dashboard_v4.html">→ 进入违价监控工作台</a>
        </div>
    </div>
</body>
</html>
