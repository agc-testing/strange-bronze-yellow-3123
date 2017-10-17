# Add react landing page that displays the lat/lon data from the backend

### Description
We should start to build out an interface for our Go backend that can users can interact with.  The frontend should be React.

### Specifications

Use react to display the "data" object from the backend root endpoint.

The backend endpoint returns 

    {"metadata":{"id":"8454000","name":"Providence","lat":"41.8067","lon":"-71.4006"}, "data": [{"t":"2013-01-01 10:00", "v":"0.072", "s":"0.003", "f":"0,0,0,0", "q":"v"},{"t":"2013-01-01 10:06", "v":"0.095", "s":"0.003", "f":"0,0,0,0", "q":"v"},{"t":"2013-01-01 10:12", "v":"0.115", "s":"0.003", "f":"0,0,0,0", "q":"v"},{"t":"2013-01-01 10:18", "v":"0.138", "s":"0.004", "f":"0,0,0,0", "q":"v"},{"t":"2013-01-01 10:24", "v":"0.167", "s":"0.004", "f":"0,0,0,0", "q":"v"}]}

Display the lat/lon and name key values as a header to the data displayed.
