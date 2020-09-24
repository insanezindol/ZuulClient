# ZuulClient

Netflix Zuul is an edge service provider that sits between an API client and a plethora of microservices.

The post-filter runs before the final responses are sent to the API client. This gives us the opportunity to act on the raw response body and do things like logging and other data transformations we desire.
