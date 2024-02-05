<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Liên kết trang web</title>
</head>

<body>

    <p>Nhạc do Hiệp soạn :> </p>
    <a href="#" onclick="hienThiCacLink()">Nhấp vào em đi :3 </a>

    <div id="danhSachLink" style="display:none;">
        <ul>
            <li><a href="https://www.youtube.com/watch?v=jH1RNk8954Q">Kings & Queens</a></li>
            <li><a href="https://www.youtube.com/watch?v=GrAchTdepsU">Mood </a></li>
            <li><a href="https://www.youtube.com/watch?v=WcIcVapfqXw">Calm Down </a></li>
            <li><a href="https://www.youtube.com/watch?v=nYh-n7EOtMA">cheap thrills </a></li>
            <li><a href="https://www.youtube.com/watch?v=kOkQ4T5WO9E">that is what you came for </a></li>
            <li><a href="https://www.youtube.com/watch?v=hLQl3WQQoQ0">someone like you </a></li>
            <li><a href="https://www.youtube.com/watch?v=Qzc_aX8c8g4">dancing with your ghost</a></li>
            <li><a href="https://www.youtube.com/watch?v=-uFQzcY7YHc">head in the clouds </a></li>
            <li><a href="https://www.youtube.com/watch?v=BxuY9FET9Y4">one call away</a></li>
            <li><a href="https://www.youtube.com/watch?v=4NRXx6U8ABQ">blinding lights</a></li>
            <!-- Thêm các liên kết khác nếu cần -->
        </ul>
    </div>

    <script>
        function hienThiCacLink() {
            var danhSachLink = document.getElementById('danhSachLink');
            danhSachLink.style.display = 'block';
        }
    </script>

</body>

</html>
