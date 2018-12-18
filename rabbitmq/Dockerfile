FROM rabbitmq:3-management

RUN rabbitmq-plugins enable rabbitmq_shovel rabbitmq_shovel_management

HEALTHCHECK --interval=30s --timeout=30s --start-period=5s --retries=3 CMD [ "rabbitmqctl", "status" ]