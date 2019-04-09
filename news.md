---
layout: page
title: News
---
<!-- Main -->
<article id="main">

    <header class="special container">
        <span class="icon fa-mobile"></span>
        <h2>En haut de la <strong>Colline</strong></h2>
        <p>Où les lapins se planquent dans les ronces, les chats ronronnent à en perdre le souffle, les chiens amassent joyeusement la boue et on aimerait plus de place pour les brebis.</p>
    </header>

    {% for post in site.posts %}
    <section class="wrapper style4 container">

        <!-- Content -->
            <div class="content">
                <section>
                    <header>
                        <h3>{{ post.title }}</h3>
                    </header>
                    {{ post.content | markdownify }}
                </section>
            </div>

    </section>
    {% endfor %}

</article>