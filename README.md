[![Build Status](https://cloud.drone.io/api/badges/NORDUnet/opennsa/status.svg)](https://cloud.drone.io/NORDUnet/opennsa)

OpenNSA
-------

**Attention**: This is a fork from https://github.com/NORDUnet/opennsa/

OpenNSA is an implementation of the Network Service Interface (NSI).

NSI (Network Service Interface) is a technology agnostic protocol for
provisioning network circuits. For more information on NSI, see project page at
OGF: https://redmine.ogf.org/projects/nsi-wg

OpenNSA is currently in a state of heavy development, and many features are
only partially implemented.


#### OpenNSA features

* Open-source NSI implementation
* Pluggable backends to support different equipment
  * Support: Junox MX, Force10 switch (etherscale), Dell Powerconnect
  * DUD backend for easy testing
  * Any custom Python backend
* Easy development of new backends
* Easy creation of NML topology from short-hand topology specification
* Topology aggregation and path finding to do multi-domain circuit creation
* PostgreSQL for database
* Includes command line tool for basic operations

#### Documentation 

Full and detailed documentation available [here](https://NORDUnet.github.io/opennsa/)


#### License

NORDUnet License (3-clause BSD). See LICENSE for more details.

#### Contact

* Johannes Garm Houen - jgh @ nordu.net
* Samir Faci - samir @ es.net

#### Copyright

[NORDUnet](http://www.nordu.net) (2011-2015)


