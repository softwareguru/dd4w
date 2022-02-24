---
title: "Registro"
date: 2019-09-10T13:51:25+06:00
draft: false
description: ""
---


<div id="eventbrite-widget-container-275065246557"></div>
<script src="https://www.eventbrite.com.mx/static/widgets/eb_widgets.js"></script>
<script type="text/javascript">
    var exampleCallback = function() {
        console.log('Pedido completo');
    };
    window.EBWidgets.createWidget({
        // Required
        widgetType: 'checkout',
        eventId: '275065246557',
        iframeContainerId: 'eventbrite-widget-container-275065246557',
        // Optional
        iframeContainerHeight: 425,  // Widget height in pixels. Defaults to a minimum of 425px if not provided
        onOrderComplete: exampleCallback  // Method called when an order has successfully completed
    });
</script>