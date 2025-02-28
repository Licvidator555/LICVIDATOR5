<!DOCTYPE html>
<html>
    <head>
<meta charset="UTF-8">
<link rel="stylesheet" href="222.css">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0">
<title>Оформление заказа</title>
    </head>
    <body>
<div class="wrapper">
    <div class="form">
        <form action="#" id="form" class="form__body">
            <h1 class="form-title">Обсудить проект</h1>
            <div class="form__item">
                <label for="forName" class="form__label">Имя*:</label>
                <input  id="forName" type="text"  name="name"   class="form__input _req">
            </div>

            <div class="form__item">
             <label for="forEmail" class="form__label">E-mail*:</label>
                <input  id="forEmail" type="text"  name="name"   class="form__input _req _email">
            </div>
            <div class="form__item">


            </div>
<div class="form__item">
    <label for="formMessage" class="form__label" >Сообщение</label>
    <textarea name="Message" id="formMessage"     class="form__input"></textarea>

</div>


<div class="form__item">
    <div class="form__label">Прикрепить фото</div>
    <div class="file">
        <div class="file__item">
            <input id="formImage"  accept=".jpg, .png, .gif" type="file" name="image" class="file__input">
            <div class="file__button">Выбрать</div>
        </div>
        <div id="formPreview" class="file__preview"></div>
    </div>
</div>
<div class="form__item">
    <div class="checkbox">
        <input id="formAgreement" type="checkbox" name="agreement" class="checkbox__input _req">
        <label for="formAgreement" class="checkbox__label" >Я даю согласие обработку своих персональных данных</label>
    </div>
</div>

<button type="submit" class="form__button">Send</button>
        </form>
    </div>
</div>
<script src="222.js"></script>
    </body>
</html>
