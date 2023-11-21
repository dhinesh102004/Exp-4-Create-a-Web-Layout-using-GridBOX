# Exp-4-Create-a-Web-Layout-using-GridBOX
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Grid Layout</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }
        
        .container {
            display: grid;
            grid-template-areas:
                "header header"
                "nav main"
                "sidebar main"
                "footer footer";
            grid-template-rows: auto minmax(300px, 1fr) minmax(300px, 1fr) auto;
            grid-template-columns: 200px 1fr;
            height: 100vh;
        }
        
        .header {
            grid-area: header;
            background-color: #4CAF50;
            color: white;
            padding: 1em;
        }
        
        .nav {
            grid-area: nav;
            background-color: #333;
            color: white;
            padding: 1em;
        }
        
        .main {
            grid-area: main;
            padding: 1em;
        }
        
        .sidebar {
            grid-area: sidebar;
            background-color: #ddd;
            padding: 1em;
        }
        
        .footer {
            grid-area: footer;
            background-color: #4CAF50;
            color: white;
            padding: 1em;
            text-align: center;
        }
        
    </style>
</head>
<body>
    <div class="container">
        <header class="header">Header</header>
        <nav class="nav">Nav</nav>
        <main class="main">Main Content</main>
        <aside class="sidebar">Sidebar</aside>
        <footer class="footer">Footer</footer>
    </div>
</body>
</html>

```
# output
![image](https://github.com/dhinesh102004/Exp-4-Create-a-Web-Layout-using-GridBOX/assets/142372008/ec328378-3176-4acf-b7d1-c2b03d2622e3)
