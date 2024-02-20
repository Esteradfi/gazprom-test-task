Привет, тебя приветствует команда разрабоки аналитических бизнес-приложений Практики бизнес и продвинутой аналитики [**Газпромнефть-ЦР**](https://ds.gazprom-neft.ru/)!

В рамках данного тестового задания тебе необходимо будет реализовать небольшое React-приложение с использованием библиотеки [**echarts.js**](https://echarts.apache.org/en/index.html) и библиотеки компонентов [**Consta UI Kit**](https://consta.design/libs/uikit)

- Макет дешборда ты можешь увидеть здесь: [**Figma**](https://www.figma.com/file/CppcOcor3NP1BfrppRgd4a/Test?node-id=0%3A1&mode=dev). Не ждем от тебя pixel perfect, но от макета сильно отступать не стоит.

- Пример того, как должна выглядеть готовая реализация вот здесь: [**Видео**](./assets/video.mp4)

- В папке проекта создан шаблон React-приложения, который можно использовать для работы

- В файле [**package.json**](./package.json) указаны минимально-необходимые для работы библиотеки

- В файле [**ReactECharts.ts**](src/components/Content/Echarts/ReactECharts.tsx) реализован компонент ReactECharts, который можно использовать для отрисовки элементов из библиотеки [**echarts.js**](https://echarts.apache.org/en/index.html)

Пример использования:

```
<ReactECharts option={option}/>
```

- В файле [**data.ts**](./src/data/data.ts) представлен массив данных, который необходимо использовать для отрисовки визуализации в рамках разработки

- Будет преимуществом реализации запроса к данным по api. В качестве эндпоинта можно использовать сервис [**mockAPI**](https://mockapi.io/) или любой другой аналогичный сервис, куда необходимо будет внести данные, представленные в файле [**data.ts**](./src/data/data.ts)

- Дополнительно большим преимуществом будет отформатированный, структурированный и типизированный код с комментариями, а так же заполненный README, где кратко описано что и как ты делал (можно удалить содержимое этого файла и написать сюда)

В качестве итогого результата должно быть реализовано приложение, обрабатывающее предоставленные данные по курсам валют и отрисовывающее визуализацию, представленную в [**макете**](https://www.figma.com/file/CppcOcor3NP1BfrppRgd4a/Test?node-id=0%3A1&mode=dev0). В приложении должны присутствовать:

1. Тултипы, отображающиеся при наведении на график и показывающие значение в данной точке
2. Среднее значение за период
3. Переключение курсов валют
4. Компоненты из библиотеки Consta UI Kit

Написанный код нужно залить на Github и в обратном письме выслать ссылку на репозиторий (обязательное проверьте, чтобы репозиторий был открытым).

Желаем удачи и с нетерпением ждем тебя в нашей команде!

<p align="left">
 <img width="250" src="./assets/coter.jpg" alt="jpg"/>
</p>
