<h1>Приложение: "Бросок кубика с случайными числами от 1 до 6."</h1>
<br>
Разработчик: Бобина Елизавета Сергеевна
<img width="244" height="536" alt="image" src="https://github.com/user-attachments/assets/f5da3b59-3af2-40b6-8c30-39b9ad92e0a9" />
<br>
<br>
Дополнение. Что использовала в MainActivity.kt:<br>
<b>onCreate()</b> - вызывается при создании Activity<br>
<b>savedInstanceState</b> - сохраненное состояние<br>
<b>override означает</b> - переопределение метода, который уже существует в родительском классе или интерфейсе. Изменяет его реализацию в текущем классе.<br>
<b>inflate()</b> - превращает XML-разметку в реальные объекты на экране телефона.<br>
<b>binding.root</b> - корневой элемент (ConstraintLayout)<br>
<b>setContentView()</b> - устанавливает разметку для Activity<br>
<b>enableEdgeToEdge()</b> - делает приложение полноэкранным<br>
<b>binding.btnStart</b> - доступ к кнопке через ViewBinding<br>
<b>setOnClickListener</b> - устанавливает обработчик клика<br>
<b>Random.nextInt(1, 7)</b> - генерирует случайное число от 1 до 6<br>
<b>binding.diceResult.text</b> - обновление текста TextView<br>
<b>toString()</b> - преобразование числа в строку<br>
