# LittleBits CloudBit API Tutorial

This tutorial will introduce you to LittleBit's CloudBit API. You'll learn how to list the available CloudBit devices on your account, access individual CloudBits, and send commands to CloudBits for output to occur. You will need a setup CloudBit on [http://control.littlebitscloud.cc/](http://control.littlebitscloud.cc/). If you do not have a CloudBit, you may [http://littlebits.cc/kits/cloudbit-starter-kit](purchase a starter kit from LittleBits). 

> _Why CloudBit and not Raspberry Pi/Arduino?_ LittleBits are designed to be used without much electronics knowledge and a service-oriented architecture (SOA) secured using OAuth 2.0 is provided from LittleBits.

## Goals

* Introduce the LittleBits ecosystem of modules
* Verify that your _CloudBit_ is online
* Understand the basics of _OAuth 2.0_
* Create appropriate headers for your _requests_ to the API
* Send a _GET_ request to list all of the CloudBits on your account
* Parse the JSON _response_ from your GET request
* Send a _POST_ request to trigger your CloudBit's output


#### Resources

* CloudBit API URI - https://api-http.littlebitscloud.cc/
