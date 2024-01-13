# 🖤Official 🖤GhØster Army🖤 Web🖤
<!DOCTYPE html>
<html>
<head>
    <title>🖤GhØster Army🖤</title>
    <style>
        body {
            background-color: #000000;
            color: #FFFFFF;
            font-family: 'Courier New', Courier, monospace;
        }
        .button {
            background-color: #4CAF50;
            border: none;
            color: white;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 4px 2px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>🖤GhØster Army🖤</h1>
    <button class="button" onclick="showTargets()">Targets</button>
    <a href="https://discord.gg/sKUDTXhD8X" class="button">Discord</a>
    <a href="https://github.com/Smug246/Luna-Grabber" class="button">Grabber Tool</a>
    <div id="targets" style="display:none">
        <script>
            function showTargets() {
                var targets = document.getElementById("targets");
                if (targets.style.display === "none") {
                    targets.style.display = "block";
                } else {
                    targets.style.display = "none";
                }
            }
            for (var i = 1; i <= 30; i++) {
                document.write(i + ". Target: " + Math.floor(Math.random() * 100) + "<br>");
            }
        </script>
    </div>
</body>
</html>

