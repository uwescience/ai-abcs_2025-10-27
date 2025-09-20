# Registration

## Before Registration

### Prerequisites
Primarily, you must be comfortable with basic Python. Advanced knowledge is not
required, but at a minimum students should be comfortable with Python syntax
and familiar with the [NumPy](https://numpy.org/) library and the
[Pandas](https://pandas.pydata.org/) library. See the [preparation
page]({{base.siteurl}}/prep) for more information.

The course also uses a small amount of
[git](https://github.com/git-guides/install-git) and
[Docker](https://www.docker.com/get-started/) to coordinate the lessons, but
novices to these tools are welcome to register.


### Setup Instructions
You must bring a laptop to the course (not a tablet or chromebook), and you
must install a few pieces of software on it:
* [Install Docker](https://www.docker.com/get-started/). Docker is a virtual
  machine tool that is used in the workshop. The link includes instructions for
  all major operating systems.
* [Install a Shell/Terminal](https://carpentries.github.io/workshop-template/install_instructions/#shell).
* [Install Git](https://carpentries.github.io/workshop-template/install_instructions/#git).

You cannot complete the registration process without this software installed.


## How to Register

Registration fees are $10.

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
