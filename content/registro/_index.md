---
title: "Registro"
date: 2022-07-25T13:51:25+06:00
draft: false
description: ""
---

<div id="eventbrite-widget-container-391362715417"></div>

<script src="https://www.eventbrite.com/static/widgets/eb_widgets.js"></script>

<script type="text/javascript">
    var exampleCallback = function() {
        console.log('Order complete!');
    };

    
</iframe>

    window.EBWidgets.createWidget({
        // Required
        widgetType: 'checkout',
        eventId: '391362715417',
        iframeContainerId: 'eventbrite-widget-container-391362715417',

        // Optional
        iframeContainerHeight: 425,  // Widget height in pixels. Defaults to a minimum of 425px if not provided
        onOrderComplete: exampleCallback  // Method called when an order has successfully completed
    });
</script>

