<!DOCTYPE html>  
<html lang="vi">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Thông tin cá nhân</title>  
    <style>  
        body {  
            font-family: Arial, sans-serif;  
            margin: 20px;  
            color: #333;  
            background-color: #f9f9f9;  
        }  
        table {  
            width: 100%;  
            border-collapse: collapse;  
            margin: 20px 0;  
        }  
        th, td {  
            border: 1px solid #ccc;  
            padding: 10px;  
            vertical-align: top;  
        }  
        th {  
            background-color: #f2f2f2;  
            color: red;  
            font-weight: bold;  
        }  
        h2 {  
            color: red;  
        }  
        h3 {  
            color: #000;  
            margin: 5px 0;  
        }  
        ul, ol {  
            margin: 5px 0;  
            padding-left: 20px;  
        }  
        .input-field {  
            width: 100%;  
            border: none;  
            background: #f9f9f9;  
        }  
        .input-area {  
            width: 100%;  
            padding: 5px;  
            border: 1px solid #ccc;  
        }  
        a {  
            color: blue;  
            text-decoration: none;  
        }  
        a:hover {  
            text-decoration: underline;  
        }  
    </style>  
</head>  
<body>  
    <h2>Thông tin cá nhân</h2>  
    <table>  
        <tr>  
            <th>Chèn ảnh vào</th>  
            <th>Tóm tắt tiểu sử</th>  
            <th>Giới thiệu bản thân</th>  
        </tr>  
        <tr>  
            <td>  
                <input type="file" accept="image/*">  
            </td>  
            <td>  
                Họ và tên: <input type="text" class="input-field" value="Lê Phan Văn Đức" readonly><br>  
                Ngày sinh: <input type="date" class="input-field" value="2007-10-26" readonly><br>  
                Quê quán: <input type="text" class="input-field" value="Tỉnh Quảng Trị, huyện Hải Lăng, tp. Đông Hà" readonly><br>  
                Chỗ ở hiện nay: <input type="text" class="input-field" value="05 Tuệ Tĩnh" readonly><br>  
                Học sinh lớp: <input type="text" class="input-field" value="12A1" readonly><br>  
                Học trường: <input type="text" class="input-field" value="THPT Lê Lợi" readonly><br>  
                Sở thích: <input type="text" class="input-field" value="Chơi game, đọc sách, hát" readonly><br>  
            </td>  
            <td>  
                <textarea class="input-area" rows="4" readonly>Mình tên là Lê Phan Văn Đức học lớp 12A1. Tôi là người sống rất thân thiện và hoà đồng. Là một người sở hữu nhiều đam mê như: đi hát, đánh đàn, bơi,... Mình đang cố gắng từng ngày để hoàn thiện bản thân hơn. Dù có rất nhiều yếu tố khó khăn tôi theo đuổi đam mê của bản thân mình nhưng tôi chưa bao giờ nản chí vì điều đó.</textarea>  
            </td>  
        </tr>  
        <tr>  
            <td colspan="3">  
                <h3>Sau đây là địa chỉ các trang web:</h3>  
                <ul>  
                    <li><a href="https://www.facebook.com">Facebook</a></li>  
                    <li><a href="https://thptleloi.quangtri.edu.vn/fbclid=IwY2xjawG2utNleHRuA2FlbQIxMAABHaUhw_DFaPP_yjpw-TU_UXNrKG8djSaE6_4n7mJmF0c-IXTD46seEIbtQA_aem_NcVPskuNOVtla-mAYu8zXw">Trường THPT Lê Lợi</a></li>  
                    <li><a href="https://thptleloi.quangtri.edu.vn/trang-chu/tho-i-kho-a-bie-u">TKB Trường THPT Lê Lợi</a></li>  
                    <li><a href="https://thptleloi.quangtri.edu.vn/gioi-thieu/ban-gia-m-hie-u">BGH Trường THPT Lê Lợi</a></li>  
                    <li><a href="https://quangtri.edu.vn/">Sở GD&ĐT Quảng Trị</a></li>  
                </ul>  
            </td>  
        </tr>  
        <tr>  
            <td colspan="3">  
                <h3>Sau đây là các bài tập của tôi:</h3>  
                <ol>  
                    <li>Câu 1 - BTH Bài 8</li>  
                    <li>Câu 2 - BTH Bài 8</li>  
                    <li>Câu 3 - BTH Bài 8</li>  
                    <li>Câu 1 - BTH Bài 9</li>  
                    <li>Câu 2 - BTH Bài 9</li>  
                </ol>  
            </td>  
        </tr>  
        <tr>  
            <td>Chèn audio vào:<br><input type="file" accept="audio/*"></td>  
            <td>Chèn video vào:<br><input type="file" accept="video/*"></td>  
            <td>Chèn khung nội tuyến (địa chỉ tuyệt đối):<br><input type="text" class="input-field" placeholder="http://example.com"></td>  
        </tr>  
        <tr>  
            <td colspan="2">  
                Chèn khung nội tuyến (địa chỉ tương đối):<br>  
                <input type="text" class="input-field" placeholder="path/to/file.html">  
            </td>  
            <td></td>  
        </tr>  
    </table>  
</body>  
</html>  
