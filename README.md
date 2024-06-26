<div align="center">
	<img src="https://github.com/ProgrammerNinja/ESP32_Cluster/blob/main/img/logo15x15.png">
</div>
<h1 align="center">ESP32 Cluser</h1>
<h2 align="center"> Make a super computer of ESP32 </h2>

## Some usefull info:

There are many existing communication and software platforms, such as Kafka, Dask, Ipython Parallel, Celery, MQTT, etc.
which can be used as a mechanism of communication and integration for cluster and distributed systems. There are many common design patterns, for example: controller/master/broker corresponds to nodes/workers/clients, the message queue and message-passing interfaces, and the paradigms of producer/queue/consumer or publisher/topic/subscriber. With these all combined, it is possible to build an elastic and robust computing platform for distributed/parallel operations. [Celery](http://www.celeryproject.org/) is one of the famous examples. Mechanism of Celery   Celery operates in a producer/queue/consumer paradigm. It is used with some suites (eg RabbitMQ, Redis...) which follow the [AMQP](https://www.amqp.org/) protocol. The mechanism is described in details in the [Celery documents](http://docs.celeryproject.org/en/latest/getting-started/index.html). Please also refer to [this]( Https://www.vinta.com.br/blog/2017/celery-overview-archtecture-and-how-it-works/) easy-to-understand articles.  Canvas is one of Celery's cores. Celery provides a sub-module called [Canvas](http://docs.celeryproject.org/en/latest/userguide/canvas.html). With Canvas it's easy to organize tasks into workflow and dispatch it all at once to workers for processing. The client only needs to wait for the final result. I was very curious and interested in its souce code.  
## Project goal:  
  - Therefore, the goal of this project was set as: Creating a package, with which we can, in a Celery-Canvas fashion, dispatch tasks to an ESP32 cluster for processing.
  - Creatin our personal Cluster, and will run an simple ai on it.

    <img src="https://github.com/ProgrammerNinja/ESP32_Cluster/blob/main/img/Broccoli_cluster_cover.gif">
