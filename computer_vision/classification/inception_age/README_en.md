EN|[CN](README.osc.md)
##### Notice:
When converting the model, you should use the PB model Link in the warehouse. If you need to retrain, you can refer to the network model link of the PB original model Link

##### PB model Link:
https://obs-model-ascend.obs.cn-east-2.myhuaweicloud.com/inception_age/inception_age.pb

##### PB original model Link:
https://drive.google.com/drive/folders/0B8N1oYmGLVGWbDZ4Y21GLWxtV1E

##### Input Description:
Input image size is 227*227, format is BGR

##### Output Description:
AGE_LIST = ['(0, 2)','(4, 6)','(8, 12)','(15, 20)','(25, 32)','(38, 43)','(48, 53)','(60, 100)']
output probability of each type

##### Custom Operator:
//Custom operator is included or not: No
//Custom operater code link ---optional
