# Frequently Asked Questions

### How do I access the API?

In order to access the API, you must first register for an account, and then login. Once you have logged in, you must then create an API key. You should send this API key in the headers of all requests to the API as `apikey`.

### How do I change my subscription plan?

In order to change your subscription plan, you should first login to the dashboard. Next, head to the 'Plans' section, and then click on the Stripe icon in the column that represents the plan you wish to switch to. Finally, follow the steps on the screen.

If you wish to switch to the free plan, click on the Stripe logo on any plan where it is present, and then select 'Cancel plan' when you are at the Stripe checkout. This will downgrade you to the free plan after your current billing period ends.

### How is API usage calculated?

We charge 1 API call for each resolver call made against the API.

For example, if you request `rail.departures`, this will use 1 API call.
If you request `rail.departures`, `tfl.tubeLines` and `bus.stops.nearby`, this will use 3 API calls.

Your total and used API calls for the remainder of your current billing period can be viewed in your dashboard.

### Is there any documentation available?

Our API utilises a GraphQL playground which allows queries to be autocompleted (via introspection). Where possible, all fields have been named using human-friendly language, such as `platformIsHidden` and `trainId` (for example).

As such, there is no specific written document which covers individual fields within the API.

### Do you offer enterprise or pay-as-you-go plans?

At this time, TheTransportLab does not offer enterprise or pay-as-you-go plans for our data.

### Can I get a copy of the data?

At this time, TheTransportLab does not provide the raw datasets or offer bulk licensing of the data or datasets.

### What can I use the data for?

There are no specific restrictions imposed by us on what you can use the data for. We encourage you to use it in ways that are beneficial for the general public, but if you want to build an app just for yourself, then that's actively encouraged too.

While most of our data is provided by data providers under the Open Government License, we encourage you to check the attribution page for specifics.

### What transport modes do you currently provide data for?

TheTransportLab currently provides data for the following transport modes in the United Kingdom:

- London tube
- Rail
- Bus

We are working to bring data from other transport modes to the platform in the future. Updates will be posted to our website and social media platforms when these are made available.
