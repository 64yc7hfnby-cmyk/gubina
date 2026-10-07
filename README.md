[index.html.html](https://github.com/user-attachments/files/33177281/index.html.html)
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Биомеханика аджилити</title>
    <style>
        :root {
            --primary: #1e3a8a;
            --accent: #f59e0b;
            --text: #334155;
            --bg: #f8fafc;
            --white: #ffffff;
        }
        * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        body { background-color: var(--bg); color: var(--text); line-height: 1.6; }
        
        header { background: var(--primary); color: var(--white); padding: 1rem 0; sticky: top; position: sticky; top: 0; z-index: 100; box-shadow: 0 2px 4px rgba(0,0,0,0.1); }
        nav { max-width: 1100px; margin: 0 auto; display: flex; justify-content: space-around; flex-wrap: wrap; }
        nav a { color: var(--white); text-decoration: none; font-weight: bold; padding: 0.5rem 1rem; border-radius: 4px; transition: 0.3s; }
        nav a:hover { background: var(--accent); color: var(--primary); }

        .container { max-width: 1100px; margin: 2rem auto; padding: 0 1rem; }
        section { background: var(--white); padding: 2.5rem; margin-bottom: 3rem; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.05); }
        h1 { color: var(--primary); margin-bottom: 1.5rem; font-size: 2.5rem; }
        h2 { color: var(--primary); margin-bottom: 1.2rem; border-bottom: 2px solid var(--accent); padding-bottom: 0.5rem; font-size: 1.8rem; }
        h3 { color: var(--primary); margin: 1rem 0 0.5rem 0; }
        p { margin-bottom: 1rem; font-size: 1.1rem; }
        ul { margin-bottom: 1rem; padding-left: 1.5rem; }
        li { margin-bottom: 0.5rem; }

        /* Стиль для места под фото */
        .photo-placeholder { background: #e2e8f0; border: 3px dashed #cbd5e1; height: 350px; display: flex; align-items: center; justify-content: center; font-size: 5rem; font-weight: bold; color: #94a3b8; margin: 1.5rem 0; border-radius: 6px; position: relative; }
        .photo-placeholder::after { content: 'Место для фото / схемы'; position: absolute; bottom: 15px; font-size: 1rem; color: #64748b; font-weight: normal; }

        table { width: 100%; border-collapse: collapse; margin: 1.5rem 0; font-size: 1rem; }
        th, td { border: 1px solid #cbd5e1; padding: 0.75rem; text-align: left; }
        th { background-color: #f1f5f9; color: var(--primary); }
        
        .grid { display: grid; grid-template-columns: 1fr 1fr; gap: 2rem; }
        @media (max-width: 768px) { .grid { grid-template-columns: 1fr; } .photo-placeholder { height: 200px; } }
    </style>
</head>
<body>

    <header>
        <nav>
            <a href="#main">1. Главная</a>
            <a href="#anatomy">2. Анатомия баланса</a>
            <a href="#obstacles">3. Разбор снарядов</a>
            <a href="#breeds">4. Породы</a>
        </nav>
    </header>

    <div class="container">

        <!-- СТРАНИЦА 1: ГЛАВНАЯ -->
        <section id="main">
            <h1>Биомеханика аджилити: как физика управляет собакой на трассе</h1>
            <img src="foto1.jpg" style="width:100%; border-radius:8px; margin:20px 0;">
            <p><strong>Аджилити</strong> — это не просто скоростной бег под руководством хендлера, а сложнейшее испытание для опорно-двигательного аппарата животного. Проходя полосу из 15–22 препятствий длиной до 220 метров, собака на подсознательном уровне каждую секунду решает уравнения механики.</p>
            <p>В отличие от человека, опирающегося на две ноги, собака имеет четырёхточечную опору. Это делает её базово более устойчивой в покое, однако узкие и динамические спортивные снаряды резко сужают площадь опоры и предъявляют экстремальные требования к координации движений.</p>
        </section>

        <!-- СТРАНИЦА 2: АНАТОМИЯ БАЛАНСА -->
        <section id="anatomy">
            <h2>Анатомия баланса: Центр тяжести и инструменты</h2>
            <div class="grid">
                <div>
                    <h3>Где у собаки «точка равновесия»?</h3>
                    <p>В естественной стойке <strong>центр тяжести (ЦТ) собаки находится в районе грудной клетки</strong> (на пересечении горизонтальной линии плечелопаточного сустава и вертикали от диафрагмального позвонка). Для идеального баланса должны соблюдаться два закона физики:</p>
                    <ul>
                        <li><strong>Поступательное равновесие:</strong> Сила тяжести полностью компенсируется силой реакции опоры, направленной вверх через лапы.</li>
                        <li><strong>Вращательное равновесие:</strong> Сумма всех моментов сил равна нулю, благодаря чему собака не опрокидывается вперед, назад или на бок.</li>
                    </ul>
                </div>
                <img src="foto3.jpg" style="width:100%; border-radius:8px; margin:20px 0;">
            </div>

            <h3>Биомеханические инструменты балансировки</h3>
            <ul>
                <li><strong>Голова и шея (Живой противовес):</strong> Работает как шест канатоходца. Опуская голову, собака смещает ЦТ вперед для разгона; поднимая голову — переносит вес назад для экстренного торможения перед прыжком.</li>
                <li><strong>Хвост (Динамический руль):</strong> При резких поворотах на скорости собака совершает активные движения хвостом в сторону, противоположную заносу. Это компенсирует крутящий момент.</li>
                <li><strong>Изменение клиренса:</strong> На опасных или скользких участках собака инстинктивно прижимается корпусом ниже к настилу, снижая высоту ЦТ и повышая свою устойчивость.</li>
            </ul>
        </section>

        <!-- СТРАНИЦА 3: РАЗБОР СНАРЯДОВ -->
        <section id="obstacles">
            <h2>Разбор снарядов: Физика в действии</h2>
            <p>Каждое препятствие на трассе создаёт для биомеханики животного уникальную физическую задачу:</p>
            
            <table>
                <thead>
                    <tr>
                        <th>Снаряд / Ситуация</th>
                        <th>Смещение центра тяжести</th>
                        <th>Главный риск</th>
                        <th>Физический прием собаки</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>Наклонный Бум и Горка</strong></td>
                        <td>При подъеме — назад. При спуске — опасно сдвигается вперед.</td>
                        <td>Опрокидывание через голову на спуске или падение назад при подъеме.</td>
                        <td>Собака группируется, переносит таз назад, тормозит задними лапами и сгибает передние.</td>
                    </tr>
                    <tr>
                        <td><strong>Качели (Динамика)</strong></td>
                        <td>Резко меняется в точке прохождения оси вращения доски.</td>
                        <td>Сила инерции тянет собаку вперед в пустоту до опускания снаряда.</td>
                        <td>Собака приседает (снижает ЦТ) и задействует когти для усиления силы трения.</td>
                    </tr>
                    <tr>
                        <td><strong>Барьеры (Баллистика)</strong></td>
                        <td>Движется по жесткой параболе, которую нельзя изменить в воздухе.</td>
                        <td>Сбивание планки, жесткое приземление или неверный угол выхода.</td>
                        <td>Собака вращается вокруг своего ЦТ в воздухе: поджимает лапы и двигает шеей для баланса.</td>
                    </tr>
                </tbody>
            </table>
            
            <img src="foto3.jpg" style="width:100%; border-radius:8px; margin:20px 0;">
        </section>

        <!-- СТРАНИЦА 4: ПОРОДНЫЕ ОСОБЕННОСТИ -->
        <section id="breeds">
            <h2>Породные особенности: Геометрия против скорости</h2>
            <div class="grid">
                <img src="foto6.jpg" style="width:100%; border-radius:8px; margin:20px 0;">
                <div>
                    <p>Строение тела напрямую влияет на успешность собаки в физических дисциплинах:</p>
                    <ul>
                        <li><strong>Коротконогие породы (Корги, Таксы, Джек-расселы):</strong> Обладают низким ЦТ и вытянутым телом. У них очень высокая базовая устойчивость на узком буме или качелях. Минусы: короткие лапы ограничивают высоту прыжка, а длинный корпус усложняет прохождение слалома.</li>
                        <li><strong>Высоконогие породы квадратного формата (Бордер-колли, Малинуа):</strong> Их ЦТ расположен выше, что снижает устойчивость на узких поверхностях. Однако это дает колоссальное преимущество в скорости, длине прыжка, маневренности и перераспределении момента инерции. Бордер-колли признаны лидерами мирового аджилити именно за счет идеального соотношения пропорций и координации.</li>
                    </ul>
                </div>
            </div>
        </section>

    </div>

</body>
</html>
