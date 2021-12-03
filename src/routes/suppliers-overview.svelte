
<!-- [ SCRIPT ] -->
<script>

    // [ IMPORTS: components ]
    import { fade } from 'svelte/transition'

</script>


<!-- [ TEMPLATE: Monitoring ] -->
<svelte:head>
    <title>Monitoring</title>
</svelte:head>

<main in:fade='{{ duration: 100 }}' out:fade|local='{{ duration: 100 }}' class = 'suppliers-overview'>

    <!-- [ section: recommended suppliers ] -->
    <section class="recommended-suppliers suppliers">

        <!-- title -->
        <div class="title">
            <p class="title">Рекомендованные поставщики</p>
            <button class="CTA-small select-all">выбрать всех</button>
        </div>

        <!-- supplier cards -->
        <div class="supplier-cards">

            <div class="supplier-card">
                <!-- supplier info -->
                <div class="supplier-info">
                    <p class="supplier-title">
                        <span class = 'city'>г. Орел</span>
                        ООО Белкин и Стрелкин
                    </p>

                    <p class="supplier-metrics">
                        <span class = 'cargo-price'>₽ 1 200 000 / т</span>
                        <span class = 'cargo-price'><b>350 тонн</b> в наличии</span>
                        <span class = 'cargo-price'>постоплата</span>
                    </p>

                    <div class="time-badge badge">
                        3 час
                    </div>
                </div>

                <!-- supplier info -->
                <div class="defect-rate">
                    <div class="estimation">
                        <img src="/img/circle-progress.png" alt="defect-rate">
                        <p class="caption">Процент брака</p>
                    </div>
                    <button class="CTA-small select">выбрать</button>
                </div>
            </div>

            <div class="supplier-card">
                <!-- supplier info -->
                <div class="supplier-info">
                    <p class="supplier-title">
                        <span class = 'city'>г. Орел</span>
                        ООО Белкин и Стрелкин
                    </p>

                    <p class="supplier-metrics">
                        <span class = 'cargo-price'>₽ 1 200 000 / т</span>
                        <span class = 'cargo-price'><b>350 тонн</b> в наличии</span>
                        <span class = 'cargo-price'>постоплата</span>
                    </p>

                    <div class="time-badge badge">
                        3 час
                    </div>
                </div>

                <!-- supplier info -->
                <div class="defect-rate">
                    <div class="estimation">
                        <img src="/img/circle-progress.png" alt="defect-rate">
                        <p class="caption">Процент брака</p>
                    </div>
                    <button class="CTA-small select">выбрать</button>
                </div>
            </div>

            <div class="supplier-card">
                <!-- supplier info -->
                <div class="supplier-info">
                    <p class="supplier-title">
                        <span class = 'city'>г. Орел</span>
                        ООО Белкин и Стрелкин
                    </p>

                    <p class="supplier-metrics">
                        <span class = 'cargo-price'>₽ 1 200 000 / т</span>
                        <span class = 'cargo-price'><b>350 тонн</b> в наличии</span>
                        <span class = 'cargo-price'>постоплата</span>
                    </p>

                    <div class="time-badge badge">
                        3 час
                    </div>
                </div>

                <!-- supplier info -->
                <div class="defect-rate">
                    <div class="estimation">
                        <img src="/img/circle-progress.png" alt="defect-rate">
                        <p class="caption">Процент брака</p>
                    </div>
                    <button class="CTA-small select">выбрать</button>
                </div>
            </div>

            <div class="supplier-card">
                <!-- supplier info -->
                <div class="supplier-info">
                    <p class="supplier-title">
                        <span class = 'city'>г. Орел</span>
                        ООО Белкин и Стрелкин
                    </p>

                    <p class="supplier-metrics">
                        <span class = 'cargo-price'>₽ 1 200 000 / т</span>
                        <span class = 'cargo-price'><b>350 тонн</b> в наличии</span>
                        <span class = 'cargo-price'>постоплата</span>
                    </p>

                    <div class="time-badge badge">
                        3 час
                    </div>
                </div>

                <!-- supplier info -->
                <div class="defect-rate">
                    <div class="estimation">
                        <img src="/img/circle-progress.png" alt="defect-rate">
                        <p class="caption">Процент брака</p>
                    </div>
                    <button class="CTA-small select">выбрать</button>
                </div>
            </div>

        </div>

    </section>

    <!-- [ section: rest suppliers ] -->
    <section class="rest-suppliers suppliers">

        <!-- title -->
        <div class="title">
            <p class="title">Прочие поставщики</p>
            <button class="CTA-small select-all">выбрать всех</button>
        </div>

        <!-- supplier cards -->
        <div class="supplier-cards">

            <div class="supplier-card">
                <!-- supplier info -->
                <div class="supplier-info">
                    <p class="supplier-title">
                        <span class = 'city'>г. Орел</span>
                        ООО Белкин и Стрелкин
                    </p>

                    <p class="supplier-metrics">
                        <span class = 'cargo-price'>₽ 1 200 000 / т</span>
                        <span class = 'cargo-price'><b>350 тонн</b> в наличии</span>
                        <span class = 'cargo-price'>постоплата</span>
                    </p>

                    <div class="time-badge badge">
                        3 час
                    </div>
                </div>

                <!-- supplier info -->
                <div class="defect-rate">
                    <div class="estimation">
                        <img src="/img/circle-progress.png" alt="defect-rate">
                        <p class="caption">Процент брака</p>
                    </div>
                    <button class="CTA-small select">выбрать</button>
                </div>
            </div>

            <div class="supplier-card">
                <!-- supplier info -->
                <div class="supplier-info">
                    <p class="supplier-title">
                        <span class = 'city'>г. Орел</span>
                        ООО Белкин и Стрелкин
                    </p>

                    <p class="supplier-metrics">
                        <span class = 'cargo-price'>₽ 1 200 000 / т</span>
                        <span class = 'cargo-price'><b>350 тонн</b> в наличии</span>
                        <span class = 'cargo-price'>постоплата</span>
                    </p>

                    <div class="time-badge badge">
                        3 час
                    </div>
                </div>

                <!-- supplier info -->
                <div class="defect-rate">
                    <div class="estimation">
                        <img src="/img/circle-progress.png" alt="defect-rate">
                        <p class="caption">Процент брака</p>
                    </div>
                    <button class="CTA-small select">выбрать</button>
                </div>
            </div>

        </div>

    </section>

</main>
