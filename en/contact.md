---
layout: page
lang-ref: page-contact
title: Contact Us
---
<!-- Main -->
<article id="main">

    <header class="special container">
        <span class="icon fa-envelope"></span>
        <h2>Get In Touch</h2>
        <p>Use the form below to give /dev/null a piece of your mind.</p>
    </header>

    <section class="wrapper style4 container">

        <div class="row gtr-150">
            <div class="col-4 col-12-narrower">

                <!-- Sidebar -->
                <div class="sidebar">
                    <section>
                        <header>
                            <h3>Find Us</h3>
                        </header>

                        <p>
                            <span class="icon fa-home"></span>
                            {{ site.street_address }}, {{ site.zip_code }} {{ site.city }}</p>
                        <p>
                            <span class="icon fa-phone"></span>
                            {{ site.phone }}
                        </p>
                        <p>
                            <span class="icon fa-envelope"></span>
                            {{ site.email }}
                        </p>
                        <a href="#" class="image featured"><img src="{{ 'assets/images/cochon-dinde.png' | absolute_url }}" alt="" /></a>
                    </section>
                </div>

            </div>
            <div class="col-8 col-12-narrower imp-narrower">

                <!-- Content -->
                    <div class="content">
                        <form>
                            <div class="row gtr-50">
                                <div class="col-6 col-12-mobile">
                                    <input type="text" name="name" placeholder="Name" />
                                </div>
                                <div class="col-6 col-12-mobile">
                                    <input type="text" name="email" placeholder="Email" />
                                </div>
                                <div class="col-12">
                                    <input type="text" name="phone" placeholder="Phone Number" />
                                </div>
                                <div class="col-12">
                                    <select>
                                        <option value="0">Choose a subject</option>
                                        <option value="0">Sponsoring an animal</option>
                                        <option value="0">Donating</option>
                                        <option value="0">Visiting the refuge</option>
                                        <option value="0">Volunteering</option>
                                        <option value="0">Contacting the press</option>
                                        <option value="0">Other</option>
                                    </select>
                                </div>
                                <div class="col-12">
                                    <textarea name="message" placeholder="Your message" rows="7"></textarea>
                                </div>
                                <div class="col-12">
                                    <ul class="buttons">
                                        <li><input type="submit" class="special" value="Send Message" /></li>
                                    </ul>
                                </div>
                            </div>
                        </form>
                    </div>

            </div>
        </div>
    </section>

</article>