# Forms
use different forms
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
 	 <body>
   		 <form action="/" method="">
    		<strong>Войти</strong> 
    		<input type="text" name="name" placeholder="Логин" maxlength="6">
    		<input type="password" name="name" placeholder="Пaроль" maxlength="6"><br><br>
    		<input type="radio" name="sex">	Муж.<br>
 			<input type="radio" name="sex">	Жен.<br><br>
   Ваша профессия:<br>
  			<input id="mil" type="checkbox" name="prof"><label for="mil">Военный</label><br>
  			<input  id="doc" type="checkbox" name="prof"><label for="doc">Врач</label><br>
  			<input id="bil" type="checkbox" name="prof"><label for="bil">Строитель</label><br><hr>
				<textarea cols="20" rows="6" placeholder="Напишите несколько строк о себе..."></textarea><br>
					<button type="submit">Отправить</button>
					<button type="reset">Очистить</button>

    </form>
	
  </body>
</html>
