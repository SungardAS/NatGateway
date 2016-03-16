# particles-nat-gateway

Particles for [condensation](https://github.com/SungardAS/condensation) that help build an AWS NatGateway.

## Use

    > npm install
    > gulp

Templates will be created in the `dist` directory

To upload to S3 create `config/local.js` with bucket configuation and
run `gulp deploy`

## Particles

### cftemplates

#### template

The main stack that will build a VPC having 2 subnets & 2 custom routing tables and a NATGateway.

#### natgateway.template

A stack that will build a NATGateway in a given VPC.
