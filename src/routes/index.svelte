
<!-- [ SCRIPT ] -->
<script>

    // [ IMPORTS: components ]
    // import Sidebar from '$components/Sidebar'

</script>


<!-- [ TEMPLATE: Monitoring ] -->
<svelte:head>
    <title>Monitoring</title>
</svelte:head>

<main class = 'monitoring'>

    <!-- [ section: zone tabs ] -->
    <ul class = 'zone-tabs'>
        <li class="tab active">Зона А</li>
        <li class="tab">Зона Б</li>
        <li class="tab">Зона В</li>
    </ul>

    <!-- [ section: dashboard ] -->
    <div class="dashboard">

        <!-- process info -->
        <p class = 'process-info'>
            <span class = 'supplier'>ООО Белкин и Стрелкин</span>
            Приемка: гречка, 15 тонн
        </p>

        <!-- video canvas & analytics -->
        <div class="monitor">
            <div class="video"></div>
            <div class="analytics">
                <p class = 'caption'>Анализ качества груза:</p>
                <p class = 'estimation defect'>Обнаружен брак</p>

                <div class="defect-rate">
                    <img src="/img/circle-progress.png" alt="defect-rate">
                    <span class="caption">Процент брака</span>
                </div>

                <p class="loss defect">- 220 000 ₽</p>
            </div>
        </div>

        <!-- button: complete acceptance -->
        <button class="CTA complete-acceptance">завершить приемку</button>
    </div>

    <!-- [ section: process schedule ] -->
    <div class="process-schedule">
        <p class = 'caption'>Текущее состояние:</p>
        <ul>
            <li class="sched-row active">
                <span class="time">09:25</span>
                <span class="descr">Производится разгрузка</span>
            </li>
            <li class="sched-row">
                <span class="time">09:20</span>
                <span class="descr">Прибыло на место разгрузки</span>
            </li>
            <li class="sched-row">
                <span class="time">07:35</span>
                <span class="descr">Ожидается груз ...</span>
            </li>
        </ul>
    </div>

</main>
