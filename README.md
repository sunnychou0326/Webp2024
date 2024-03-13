# Webp2024
<html>
<head>
    <title>資工系選課表</title>
    <style>
        table {
            font-family: Arial, Helvetica, sans-serif;
            border-collapse: collapse;
            width: 100%;
        }
        td, th {
            border: 1px solid #ddd;
            padding: 6px;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
        tr:hover {
            background-color: #ddd;
        }
        th {
            padding-top: 12px;
            padding-bottom: 12px;
            text-align: left;
            background-color:#04AA6D;
            color: white;
        }
       
    </style>
</head>
<body>
    <h1>資工系選課表</h1>
    <table id="csie">
        <tr>
            <th>開課單位</th>
            <th>課程名稱</th>
            <th>授課教師</th>
        </tr>
        <tr>
            <td>資工系</td>
            <td>物件導向軟體設計</td>
            <td>黃崇源</td>
        </tr>
        <tr>
            <td>資工系</td>
            <td>計算機網路實驗</td>
            <td>李春良</td>
        </tr>
        <tr>
            <td>資工系</td>
            <td>作業系統實務</td>
            <td>張哲維</td>
        </tr>
        <tr>
            <td>資工系</td>
            <td>生物統計</td>
            <td>陳光武</td>
        </tr>
        <tr>
            <td>資工系</td>
            <td>通訊系統</td>
            <td>陳仁暉</td>
        </tr>
        <tr>
            <td>資工系</td>
            <td>軟硬體專題(2)</td>
            <td>魏志達</td>
        </tr>
    </table>
</body>


<!--<button id="change">Change</button>-->
<button onclick="changeresult()">change</button>
<script>
    function changeresult(){
    var myTable = document.getElementById("csie");
    myTable.rows[1].cells[2].innerHTML="李春良";
}
</script>
</html>
