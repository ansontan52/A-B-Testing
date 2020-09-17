# A/B Testing on Marketing Campaigns 


## 1.Dataset Description
The dataset was collected from two marketing campaigns in Alipay.

https://tianchi.aliyun.com/dataset/dataDetail?dataId=50893


effect_tb.csv:  Click/Non-click dataset.

Fields	                 Descriptions
dt	             Values from {1,2}. Indicates whether it's a first day log (“1”) or a second day log (“2”) for the target campaign
user_id	         The unique ID of an Alipay user.
label	           Denotes whether a user clicked the campaign ads in that day dt.
dmp_id	         The unique ID of a targeting campaign.


## Purpose

This Analysis takes Alipay's two marketing campaigns as an example, and compares them through the click-through rate via A/B test and see if the effect is statistical significant.
