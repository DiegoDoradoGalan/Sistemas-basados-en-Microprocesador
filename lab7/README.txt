RUN BROKER:
mosquitto -c broker.conf

RUN SUBSCRIBER:
mosquitto_sub -t A12/# -h <ip_broker> -p <puerto_broker>
