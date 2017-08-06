# Cross Slider - jQuery Plugin

*Using Cross Slider:*  

    $("#slides-collection").crossslider({
        duration: 500,
        containerWidth: 1020
    });

*Available Options:*  

    duration: 1000, //Duration of animation in miliseconds.
    containerWidth: 1450, //container width to add max-width for content in slides.

    //List of slider elements:
    left_half: ".left-half",
    right_half: ".right-half",
    content: ".slide-content",
    slides: ".slide",

    //Navigation elements:
    next_button: ".next-slide",
    prev_button: ".prev-slide",

    //CSS Classes
    active_slide: 'active',
    disabled_nav: 'disabled',
