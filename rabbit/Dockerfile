FROM rabbitmq:3.9-management-alpine

COPY etc/rabbitmq /etc/rabbitmq
COPY var/lib/rabbitmq/.erlang.cookie /var/lib/rabbitmq/.erlang.cookie
RUN chmod 0400 /var/lib/rabbitmq/.erlang.cookie