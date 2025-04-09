<!DOCTYPE html>
<html lang="ko">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>불법 총기상점</title>
        <link href="https://cdn.jsdelivr.net/npm/remixicon@3.5.0/fonts/remixicon.css" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Do+Hyeon&display=swap" rel="stylesheet">
        <style>
            body {
                background-color: rgb(49, 49, 49);
                color: white;
                font-family: 'Do Hyeon', sans-serif;
            }
            h1, h2, h3 {
                color: rgb(59, 123, 57);
            }
            .head1 {
                background-color: #232323;
                text-align: center;
            }
            .list {
                background-color: #111111;
                padding: 10px;
            }
            .gun {
                display: inline-block;
                width: 18%;
                margin: 10px;
                background-color: #2e2e2e;
                padding: 15px;
            }
            .gun img {
                width: 100%;
            }
            .length{
                background-color: #111111;
                padding: 10px;
            }
            input, select {
                width: 10%;
                margin: 15px;
            }
        </style>
    </head>
    <body>
        <div class="head1">
            <h2>
                <i class="ri-percent-line"></i>
                특가 EVENT
                <i class="ri-percent-line"></i>
            </h2>              
        </div>
        <div class="list">
            <h2>구매 가능 총기</h2>
            <div class="gun">
                <img src="https://i.namu.wiki/i/_8h2_nMY6s_aUXQ2GjiQ1L5n1dWuqjuqB1lx8WLJTtFFKJkq3H2oeEQVXLPYMK00gIpFklSMxnGln91yXN5oJ2zNC7TbLkWO3vcuE0E8MOMPkzUe-B_Z8RDuGWt7OZ4fdiLtN0kvOn7HQ-psvlis4Q.webp">
                <h3>K1A</h3>
                <p>150만원</p>
            </div>
            <div class="gun">
                <img src="https://i.namu.wiki/i/WFr3oUpBFvgHojoflqnc3oQ0mbce-K1elCwOVnI0U-_Cl22jmAIlDs2BJiQ-uqMbI4QXiZA-ZYtSiangfgCADlQbXIS91KnRkN5dmf_AmtwHvGITBZyX4giejGJ9Cd3ZlqFPabtVz2tZbpEYnoQcaw.webp">
                <h3>K2C1</h3>
                <p>200만원</p>
            </div>
            <div class="gun">
                <img src="https://i.namu.wiki/i/meEn38BKVH1GFgJm6qrKKAXN7kLwoNVLRVOdF7xqsMbOM2wTIYkVmsai5kOLx-TqxD4ThGy3NoWSPVk6roWm7_tGnlb5BeAh6jqD5utU2sYBFKURDPofjnZB_v_EFrilkpqXGhMhKph37SAf06ZBgQ.webp">
                <h3>Kar98K</h3>
                <p>250만원</p>
            </div>
            <div class="gun">
                <img src="https://i.namu.wiki/i/7iCNZGyMHFdKxTvvXHCryz9H3HKmp105FhujkSX9vWbCrl0ygrQ7Nqk8geUBiddqK9etYq7THL0gAPi9-gQTKhwDMmEc8vHUrcsRIBRiNuHpvKRzKN2Zl1uzuAKUj7qlf73ETTyXHVlN1LMtJtrdSg.webp">
                <h3>M91</h3>
                <p>300만원</p>
            </div>
        </div>
        <div class="length">
            <h2>구매 문의</h2>
            <p style="color:red">제대로 된 정보를 작성하지 않을 경우에는 연락이 불가능합니다.</p>
            <form>
                <label>이름</label>
                <input type="text" required>
                <label>전화번호 (숫자만)</label>
                <input type="number" required>
                <label>총기 선택</label>
                <select required>
                    <option value="">총기 선택</option>
                    <option>K1A</option>
                    <option>K2C1</option>
                    <option>Kar98K</option>
                    <option>M91</option>
                </select>
                <input type="submit" value="문의하기">
            </form>
        </div>
        <p><b>신고 시 직접 사살</b></p>
    </body>
</html>
