<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <div class="container">
        <div class="col-sm-4">
            <form action="mail.php" method="POST">
                <legend> Заголовок формы</legend>

                <div class="form-group">
                    <label for="">Введите ваше имя</label>
                    <input type="text" class="form-control" id="" name="user_name" placeholder="Например Саша">
                </div>

                <div class="form-group">
                    <label for="">Введите ваш номер телефона</label>
                    <input type="text" class="form-control" id="" name="user_phone" placeholder="+38 (067) 00 00 001">
                </div>

                <button type="submit" class="btn btn-primary">Отправить запрос</button>
            </form>
        </div>
    </div>
    <script src="js/script.js"></script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
<script src="https://getbootstrap.com/assets/js/ie10-viewport-bug-workaround.js"></script>

</body>
</html>
