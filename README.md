# ravada
Remove Virtual Desktops Manager
[![GitHub version]

Broker: ravada

Hypervisors: [KVM](http://www.linux-kvm.org/) - [LXC](https://linuxcontainers.org/)

Remote Access: [Spice](http://www.spice-space.org/)

## Install

Read [docs/INSTALL.md](https://github.com/frankiejol/ravada/blob/master/docs/INSTALL.md)

## Run

### Development
To run it in development mode run those commands in two different terminals:

    $ morbo ./rvd_front.pl
    $ sudo ./bin/rvd_back.pl --debug

Connect to the server with a web browser at http://servername:3000/

### Production

See [docs/production.md](https://github.com/frankiejol/ravada/blob/master/docs/production.md)

### Operation

See [docs/operation.md](https://github.com/frankiejol/ravada/blob/master/docs/operation.md)

### Testing

See [docs/test.md](https://github.com/frankiejol/ravada/blob/master/docs/test.md)
