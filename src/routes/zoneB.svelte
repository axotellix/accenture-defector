
<!-- [ SCRIPT ] -->
<script>

    // [ IMPORTS: components ]
    import { fade } from 'svelte/transition'

</script>


<!-- [ TEMPLATE: Monitoring ] -->
<svelte:head>
    <title>Monitoring</title>
</svelte:head>

<main in:fade='{{ duration: 100 }}' out:fade|local='{{ duration: 100 }}' class = 'monitoring'>

    <!-- [ section: zone tabs ] -->
    <ul class = 'zone-tabs'>
        <li class="tab"><a href = '/'>Зона А</a></li>
        <li class="tab active"><a href = 'zoneB'>Зона Б</a></li>
        <li class="tab">Зона В</li>
    </ul>

    <!-- [ section: dashboard ] -->
    <div class="dashboard">

        <!-- process info -->
        <p class = 'process-info'>
            <span class = 'supplier'>ООО Трио</span>
            Приемка: овес, 20 тонн
        </p>

        <!-- video canvas & analytics -->
        <div class="monitor">
            <div class="video"></div>
            <div class="analytics">
                <p class = 'caption'>Анализ качества груза:</p>
                <p class = 'estimation no-defect'>Брак не обнаружен</p>

                <div class="defect-rate">
                    <img src="/img/no-defect.png" alt="defect-rate">
                    <span class="caption">Процент брака</span>
                </div>

                <p class="loss defect"></p>
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
