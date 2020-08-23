# How to host WCF Service in IIS

This article will give you a brief description of the required steps to host your WCF service in IIS and test it using console application.

## Application

1. **[NorthwindServices](https://github.com/geeksarray/how-to-host-wcf-service-in-iis-7/tree/master/IISHost/NorthwindServices)** - WCF service project having ProductService as WCF   
   service, that implements IProducts Service Contract. 

1. **[NorthWindApp](https://github.com/geeksarray/how-to-host-wcf-service-in-iis-7/tree/master/IISHost/NorthwindApp)** - console application using to NorthwindServiice WCF service.

Below picture shows how to add reference to WCF service

![WCF Service with Console application](http://dotnetmentors.com/Images/ServiceRef.png)

For more detailed steps visit - https://geeksarray.com/blog/how-to-host-wcf-service-in-iis-7
