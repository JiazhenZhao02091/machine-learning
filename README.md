## machine-learning
---
### kaggle竞赛题目复盘
---
#### 电信客户流失
##### 数据字段说明
| 字段名              | 类型     | 说明                                                                 | 示例值                                |
|---------------------|----------|----------------------------------------------------------------------|---------------------------------------|
| customerID          | 字符串   | 客户唯一标识符                                                      | 7590-VHVEG                           |
| gender              | 字符串   | 客户性别（Male/Female）                                             | Female                               |
| SeniorCitizen       | 整型     | 老年客户标识（0=否，1=是）                                           | 0                                    |
| Partner             | 字符串   | 是否有配偶（Yes/No）                                                | Yes                                  |
| Dependents          | 字符串   | 是否有家属（Yes/No）                                                | No                                   |
| tenure              | 整型     | 在网时长（月）                                                     | 1                                    |
| PhoneService        | 字符串   | 是否开通电话服务（Yes/No）                                           | No                                   |
| MultipleLines       | 字符串   | 多线路服务（No phone service表示未开通电话服务）                     | No phone service                     |
| InternetService     | 字符串   | 网络服务类型（DSL/光纤/无）                                         | DSL                                  |
| OnlineSecurity      | 字符串   | 网络安全服务（Yes/No/No internet service）                          | No                                   |
| OnlineBackup        | 字符串   | 在线备份服务（Yes/No/No internet service）                          | Yes                                  |
| DeviceProtection    | 字符串   | 设备保护服务（Yes/No/No internet service）                          | No                                   |
| TechSupport         | 字符串   | 技术支持服务（Yes/No/No internet service）                           | No                                   |
| StreamingTV         | 字符串   | 网络电视（Yes/No/No internet service）                              | No                                   |
| StreamingMovies     | 字符串   | 网络电影（Yes/No/No internet service）                              | No                                   |
| Contract            | 字符串   | 合同类型（按月/1年/2年）                                            | Month-to-month                       |
| PaperlessBilling    | 字符串   | 电子账单（Yes/No）                                                  | Yes                                  |
| PaymentMethod       | 字符串   | 支付方式（电子支票/邮寄支票/银行转账/信用卡）                        | Electronic check                     |
| MonthlyCharges      | 浮点型   | 月度费用                                                           | 29.85                                |
| TotalCharges        | 浮点型   | 总费用（需处理空值）                                                | 29.85                                |
| Churn               | 字符串   | 是否流失（Yes/No）                                                  | No                                   |

