# reinvent-API
Minimalistic and Reusable REST API Design pattern for Hyperledger fabric Applications

##### Big Picture

REST API Design pattern for Hyperledger fabric. API code is reusable and fixed irrespective of Application size. Chaincode function can be passed as argument to API. So, no need to create separate routes for chaincode functions.


#### Things to Consider Modification:

1. Connection Profile Name and location
2. Channel name
3. Chaincode Name

>Query or body parameters should be passed as the order defined in chaincode function. First argument must be function name to call..
##### Swagger Demo:

<img align="center" src="https://github.com/BCDevs/reinvent-API/blob/master/explorer.png" width="90%">

<img align="center" src="https://github.com/BCDevs/reinvent-API/blob/master/get_response.png" width="90%">

##### Author   

##### :wave: [Salman Dabbakuti](https://salmandabbakuti.github.io)

<a href="https://www.buymeacoffee.com/Salmandabbakuti" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>    
