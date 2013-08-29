---
layout: base
title: Scooch Module Examples
description:
    See examples of the Scooch module in action,
    including the sample code snippets.
---
<div class="m-pikabu-viewport">
    <!-- the left sidebar -->
    <div class="m-pikabu-sidebar m-pikabu-left">
        <!-- left sidebar content -->
        Left
    </div>
    <!-- the main page content -->
    <div class="m-pikabu-container">
        <!-- Overlay is needed to have a big click area to close the sidebars -->
        <div class="m-pikabu-overlay"></div>
        <header>
            <a class="m-pikabu-nav-toggle" data-role="left">Left Menu</a>
            <h1>Pikabu</h1>
            <a class="m-pikabu-nav-toggle" data-role="right">Right Menu</a>
        </header>
        <section>
            <!-- Body content goes in here -->
            <h2><strong>Pikabu</strong> is a speedy, flexible framework for off-canvas flyout panels.</h2>

            <h3>Why use <strong>Pikabu</strong>?</h3>

            <p><em>Simple markup</em> &mdash; Few containers and classes means implementation is a breeze.</p>

            <p><em>Native scrolling</em> &mdash; Just like mom used to make. Momentum scrolling in sidebars and smart fallbacks for browsers that don&rsquo;t support it.</p>

            <p><em>Customization</em> &mdash; No theme, just barebones HTML and CSS. Pikabu is super customizable to your needs.</p>

            <p><em>Compatibility</em> &mdash; This thing works on everything. We progressively enhance the experience for devices that support it.</p>
        </section>
    </div>
    <!-- the right sidebar -->
    <div class="m-pikabu-sidebar m-pikabu-right">
        <!-- right sidebar content -->
        Right 
    </div>
</div>

<!-- include zepto.js or jquery.js -->
<!-- <script type="text/javascript" src="//cdnjs.cloudflare.com/ajax/libs/zepto/1.0/zepto.min.js"></script> -->
<script src="//code.jquery.com/jquery-1.10.2.min.js"></script>
<!-- include pikabu.js -->
<script type="text/javascript" src="//cdn.mobify.com/modules/pikabu/0.1.0/pikabu.min.js"></script>
<script>
    $(function() {
        pikabu = new Pikabu;
        pikabu.init();
    });
</script>
