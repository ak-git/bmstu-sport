<script lang="ts">
    import cyberhealth from './assets/1.jpg'
    import healthreserve from './assets/2.jpg'
</script>

<main>
    <section class="hero is-small">
        <div class="hero-head container box has-text-centered media">
            <div class="media-left">
                <figure class="image is-48x48">
                    <img src="favicon.svg" alt="Logo"/>
                </figure>
            </div>
            <div class="media-content">
                <p class="title">
                    Диагностика Базовой Функциональной Готовности
                </p>
            </div>
        </div>
        <div class="hero-body container box has-text-centered columns">
            <div class="column">
                <article class="panel is-warning">
                    <p class="panel-heading">
                        <a class="tag is-rounded is-large is-hoverable"
                           href="http://www.cyberhealth.ru.s3-website-us-east-1.amazonaws.com">
                            Кибер Здоровье
                        </a>
                    </p>
                    <a href="http://www.cyberhealth.ru.s3-website-us-east-1.amazonaws.com">
                        <figure class="image is-1by1">
                            <img src="{cyberhealth}" alt="cyberhealth"/>
                        </figure>
                    </a>
                </article>
            </div>
            <div class="column">
                <article class="panel is-danger">
                    <p class="panel-heading">
                        <a class="tag is-rounded is-large is-hoverable"
                           href="http://www.healthreserve.ru.s3-website-us-east-1.amazonaws.com">
                            Запас Здоровья
                        </a>
                    </p>
                    <a href="http://www.healthreserve.ru.s3-website-us-east-1.amazonaws.com">
                        <figure class="image is-1by1">
                            <img src="{healthreserve}" alt="healthreserve"/>
                        </figure>
                    </a>
                </article>
            </div>
        </div>
        <div class="hero-foot container box has-text-centered">
            <a class="button is-link is-outlined is-rounded" href="https://www.savostyanov.moscow">
                savostyanov.moscow
            </a>
        </div>
    </section>
</main>
