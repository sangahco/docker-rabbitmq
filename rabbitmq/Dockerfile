FROM rabbitmq:3-management

RUN rabbitmq-plugins enable rabbitmq_shovel rabbitmq_shovel_management

HEALTHCHECK --interval=5s --timeout=30s --start-period=10s --retries=5 CMD [ "rabbitmqctl", "status" ]