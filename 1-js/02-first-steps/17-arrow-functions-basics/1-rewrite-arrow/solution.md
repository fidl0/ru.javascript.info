let ask = (question, yes, no) => confirm(question) ? yes(): no();
ask(
	'Вы согласны?',
    () => alert('Да'),
    () => alert('Нет')
);

Выглядит короче и понятней, правда?
