<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Basketball Championship Scoreboard</title>

<style>
    *{
        margin:0;
        padding:0;
        box-sizing:border-box;
        font-family:Arial, sans-serif;
    }

    body{
        background:#0d1117;
        color:white;
    }

    header{
        background:#111827;
        padding:20px;
        text-align:center;
        border-bottom:4px solid gold;
    }

    header h1{
        font-size:40px;
        color:gold;
    }

    .scoreboard{
        display:flex;
        justify-content:space-between;
        align-items:center;
        background:#1f2937;
        margin:30px auto;
        width:90%;
        padding:40px;
        border-radius:20px;
        box-shadow:0 0 20px rgba(255,255,255,0.2);
    }

    .team{
        width:30%;
        text-align:center;
    }

    .team h2{
        font-size:35px;
        margin-bottom:10px;
    }

    .team p{
        font-size:18px;
        color:#d1d5db;
    }

    .score{
        width:40%;
        text-align:center;
    }

    .score h1{
        font-size:90px;
        color:#22c55e;
    }

    .score p{
        font-size:24px;
        margin-top:10px;
        color:#fbbf24;
    }

    .section{
        width:90%;
        margin:30px auto;
        background:#1f2937;
        padding:25px;
        border-radius:15px;
    }

    .section h2{
        margin-bottom:20px;
        color:gold;
        border-bottom:2px solid gold;
        padding-bottom:10px;
    }

    table{
        width:100%;
        border-collapse:collapse;
    }

    table th,
    table td{
        padding:12px;
        border-bottom:1px solid #374151;
        text-align:left;
    }

    table th{
        color:#fbbf24;
    }

    .flags{
        display:flex;
        justify-content:center;
        gap:20px;
        flex-wrap:wrap;
    }

    .flag{
        background:gold;
        color:black;
        padding:20px;
        border-radius:10px;
        font-weight:bold;
        width:150px;
        text-align:center;
    }

    .playoffs{
        display:grid;
        grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
        gap:20px;
    }

    .playoff-card{
        background:#111827;
        padding:20px;
        border-radius:12px;
        text-align:center;
        border:2px solid gold;
    }

    footer{
        text-align:center;
        padding:20px;
        color:#9ca3af;
    }
</style>
</head>

<body>

<header>
    <h1>🏀 Basketball Championship Finals</h1>
</header>

<div class="scoreboard">

    <div class="team">
        <h2>HOME</h2>
        <p>Los Angeles Lions</p>
        <h1>102</h1>
    </div>

    <div class="score">
        <h1>4Q</h1>
        <p>02:14 Remaining</p>
    </div>

    <div class="team">
        <h2>AWAY</h2>
        <p>Chicago Storm</p>
        <h1>98</h1>
    </div>

</div>

<div class="section">
    <h2>🏆 Championship Coaches</h2>

    <table>
        <tr>
            <th>Coach</th>
            <th>Team</th>
            <th>Career Wins</th>
        </tr>

        <tr>
            <td>Michael Carter</td>
            <td>Los Angeles Lions</td>
            <td>542</td>
        </tr>

        <tr>
            <td>James Walker</td>
            <td>Chicago Storm</td>
            <td>498</td>
        </tr>
    </table>
</div>

<div class="section">
    <h2>🔥 Playoff Bracket</h2>

    <div class="playoffs">

        <div class="playoff-card">
            <h3>Quarterfinal</h3>
            <p>Lions 110 - 97 Kings</p>
        </div>

        <div class="playoff-card">
            <h3>Semifinal</h3>
            <p>Lions 105 - 101 Hawks</p>
        </div>

        <div class="playoff-card">
            <h3>Final</h3>
            <p>Lions vs Storm</p>
        </div>

    </div>
</div>

<div class="section">
    <h2>🚩 Championship Flags</h2>

    <div class="flags">
        <div class="flag">2018 Champions</div>
        <div class="flag">2020 Champions</div>
        <div class="flag">2023 Champions</div>
        <div class="flag">2026 Finals</div>
    </div>
</div>

<footer>
    Basketball Championship Arena © 2026
</footer>

</body>
</html>
