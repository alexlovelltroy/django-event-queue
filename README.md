django-event-queue
==================

Use AMQP to send  events to a queue and STOMP to consume them (For high level event logging)
django auth for STOMP access using http_auth plugin
limit work done in normal django http request
 * using celery tasks to build interesting log messages 
 * using a listener on the queue to send logs to db
 * using fanout exchange (if no one is listening, messages can disappear)
 * stomp plugin