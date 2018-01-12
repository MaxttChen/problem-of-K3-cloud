# problem-of-K3-cloud
K3 Cloud 桥头公司问题点收集


[MarkDown语法](http://wowubuntu.com/markdown/index.html)



### 2018年1月12日
* 半成品半委外  
  300J外壳工程资料不完善，141正在建立。  
  
* 工艺路线--同一部门连续不同作业时，合并成一行，同时工时也汇总  
  如：后加工--钻孔，后加工--磨牙；合并成后加工--钻孔+磨牙；  
  已知会工程部--陈雪 
  
* 盘点导入导出格式  

* 盘点权限下放
***

### 2018年1月11日
* 建立半成品编号盘点

* 试运行 **300J外壳** 半成品半工序

* 受托加工模块上线

***

### 之前部分问题点
* 委外订单发料  
   工序转移单，按成品编号管理，如果第一个工序就委外，则由仓库作领料发给委外的供应商。  
   
   
* 委外系统对账明细    
  生产制造—车间管理—工序委外发出/接受转移列表  
  
  
* 当前工序不是第一，却需要领料  
  工程部可以在 物料清单物料控制生产 中设置对应的工序。
  
  
* 生产中补料、退料、返工  
  退料：正在二开；在 **工序计划列表** 中减少汇报数量。  
  返工：由计划人员，在工序计划 **工序序列** 新增行，并在 **类型** 中选择 **返工** ，填入返工工序和数量。  
  补料：根据工序的生产订单好，在生产列表中找到对应的生产订单，点下推，选择补料。  
  
  
* 一个委外工序对应多个供应商  
  根据工序计划对应的生产订单号 在 **车间调度工作台** 找到对应的生产订单对工序进行拆单，拆分数量即可。
***
