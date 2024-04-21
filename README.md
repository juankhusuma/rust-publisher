a. How many data your publlsher program will send to the message broker in one
run? 
> The publisher program will send 5 data to the message broker in one run.

b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber
program, what does it mean?
> This means that the publisher and subscriber are using the same message broker to communicate with each other.

![Publisher Result](publisher.png)
> The publisher program has successfully sent 5 data to the message broker.

![Overview](overview.png)
> The spikes on the graph indicates the message rates that measusres how much message are sent on the channel within a time interval. Because the publisher sends some messages to the message broker, the message rates are increased, thus causing a spike on the graph.