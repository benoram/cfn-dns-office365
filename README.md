# cfn-dns-office365
CloudFormation scripts to setup Office365 records for a given Route53 Zone, or to setup an entirely new zone with Office365 records and Amazon CAA records.


## cfn-dns.yaml
This template creates everything

### Parameters

#### DomainName
The domain name for the zone

#### DomainKey:
Your domain-key from the Office365 portal


## cfn-dns-office365.yaml
This template creates just the DNS records for Office365 in an existing Route53 zone

### Parameters

#### ZoneId
The Route53 Zone to write records to

#### DomainName
The domain name for the zone

#### DomainKey:
Your domain-key from the Office365 portal
