# coTURN_installation
coTURN installation steps

## apt-get install gcc build-essential
## apt-get install libssl-dev libevent-dev libpq-dev
## apt-get -y install coturn

## nano /etc/default/coturn

Uncomment the following line by removing the # at the beginning to run Coturn as an automatic system service daemon

### TURNSERVER_ENABLED=1

