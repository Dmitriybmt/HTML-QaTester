# HTML-QaTester
HTML -practice
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>Иконников ДЗ</title>
</head>

<body>
	<em>Пожалуйста, заполните форму. Обязательные поля помечены *</em>
	<fieldset>
		<legend> Контактная информация </legend>
		<div>
			<label> Имя* </label>
			<input type="text" name="text" maxlength="10">
		</div>
		<div>
			<label> Телефон </label>
			<input type="namber" name="namber" maxlength="11">
		</div>
		<div>
			<label> Emale* </label>
			<input type="text" name="text">
		</div>
		
	</fieldset>
	<fieldset>
		<legend> Персональная информация </legend>
		<div>
			<label> Возраст </label>
			<input type="text" maxlength="2">
		</div>
		<div>
			<label> Пол </label>
			<select>
				<option> женщина </option>
				<option> мужчина </option>
			</select>
		</div>
		<div>
			<label> Перечислите личные качесва </label>
			<textarea></textarea>
		</div>
	</fieldset>
	<fieldset>
            		<legend> Выберете ваших любимых животных </legend>
            		<label><input type="checkbox">Зебра</label>
                	<label><input type="checkbox">Кошак</label>
                	<label><input type="checkbox">Анаконда</label>
                	<label><input type="checkbox">Человек</label>
                	<label><input type="checkbox">Слон</label>
                	<label><input type="checkbox">Антилопа</label>
                	<label><input type="checkbox">Голубь</label>
                	<label><input type="checkbox">Краб</label>
    </fieldset>

    <input type="submit" value="Отправить информацию">
</body>
