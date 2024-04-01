# myWeb.io
깃헙을 이용한 홈페이지 샘플 파일입니다.
셋팅 -> HTML파일을 업로드 -> Commit changes 클릭 -> 셋팅 -> 
Page -> None -> main -> Save -> 리플레쉬 후 주소가 생성되면 확인 및 방문


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>시험 성적 확인</title>
    <style>
        table {
            width: 50%;
            border-collapse: collapse;
            margin: 20px auto;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: center;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>

<h2>시험 성적</h2>

<table>
    <thead>
        <tr>
            <th>학생 이름</th>
            <th>성적</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>홍길동</td>
            <td>95</td>
        </tr>
        <tr>
            <td>김철수</td>
            <td>82</td>
        </tr>
        <tr>
            <td>이영희</td>
            <td>75</td>
        </tr>
    </tbody>
</table>

</body>
</html>
