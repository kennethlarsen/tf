<svelte:head>
  <title>Sapper project template</title>
</svelte:head>

<section class="subscribe">
  <div class="intro">
    <h2 class="tag">Teknologi og politik. I din indbakke hver anden uge.</h2>
  </div>

  <!-- Begin Mailchimp Signup Form -->
  <div id="mc_embed_signup">
    <form
      action="https://twitter.us4.list-manage.com/subscribe/post?u=359e23baf22b822dbf2b03b1c&amp;id=cf45a544a9"
      method="post"
      id="mc-embedded-subscribe-form"
      name="mc-embedded-subscribe-form"
      class="validate"
      target="_blank"
      novalidate>
      <div id="mc_embed_signup_scroll">

        <div class="mc-field-group">
          <label for="mce-EMAIL">Email</label>
          <br />
          <input
            type="email"
            value=""
            name="EMAIL"
            class="required email"
            id="mce-EMAIL" />
        </div>
        <div id="mce-responses" class="clear">
          <div class="response" id="mce-error-response" style="display:none" />
          <div
            class="response"
            id="mce-success-response"
            style="display:none" />
        </div>
        <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
        <div style="position: absolute; left: -5000px;" aria-hidden="true">
          <input
            type="text"
            name="b_359e23baf22b822dbf2b03b1c_cf45a544a9"
            tabindex="-1"
            value="" />
        </div>
        <div class="clear">
          <input
            type="submit"
            value="Tilmeld"
            name="subscribe"
            id="mc-embedded-subscribe"
            class="button" />
        </div>
      </div>
    </form>
  </div>

  <!--End mc_embed_signup-->
</section>

<section class="reviews">
  <div class="review-alt">
    <div class="review-text">
      <h3>"Klart det bedste nyhedsbrev derude!"</h3>
      <span>Thomas Noppen, vært på Weah - podcasten om fodbold og poltik</span>
    </div>
    <img src="noppen.svg" class="intro-image" alt="" role="presentation" />

  </div>

  <div class="review">
    <img src="ipland.svg" class="intro-image" alt="" role="presentation" />

    <div class="review-text">
      <h3>"Mega fedt!"</h3>
      <span>Søren Høgh Ipland, Adm. direktør for Føljeton</span>
    </div>

  </div>

  <div class="review-alt">
    <div class="review-text">
      <h3>
        "Det her nyhedsbrev ser ud til at blive rigtig godt.
        <br />
        Begavet tænkning om og i krydsfeltet mellem teknologi, filosofi og
        politik"
      </h3>
      <span>
        <a href="https://twitter.com/mikkel_arre/status/1226862298381406208">
          @mikkel_arre
        </a>
      </span>
    </div>
    <img src="arre.svg" class="intro-image" alt="" role="presentation" />

  </div>
</section>
