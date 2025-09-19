# Registration

Registration fees are $10.

Fee waivers are available on a limited basis. If you need a fee waiver, please
contact [Noah Benson](mailto:nben@uw.edu). Please note that to receive a fee
waiver, your principal investigator must attest in writing that there is no
funding source available for you to attend the course.

<div id="eventbrite-widget-container-{{site.eventbrite}}"></div>

<script src="https://www.eventbrite.com/static/widgets/eb_widgets.js"></script>

<script type="text/javascript">
    var exampleCallback = function() {
        console.log('Order complete!');
    };

    window.EBWidgets.createWidget({
        // Required
        widgetType: 'checkout',
        eventId: '{{site.eventbrite}}',
        iframeContainerId: 'eventbrite-widget-container-{{site.eventbrite}}',

        // Optional
        iframeContainerHeight: 925,  // Widget height in pixels. Defaults to a minimum of 425px if not provided
        onOrderComplete: exampleCallback  // Method called when an order has successfully completed
    });
</script>
