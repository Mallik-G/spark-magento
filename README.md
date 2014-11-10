![Dr.Krusche & Partner PartG](https://raw.github.com/skrusche63/spark-magento/master/images/dr_kruscheundpartner_640.png)

## Integration of Predictiveworks. and Magento

[Predictiveworks.](http://predictiveworks.eu) is an ensemble of dedicated predictive engines that covers a wide range of today's analytics requirements from Association Analysis,
to Context-Aware Recommendations up to Text Analysis. This project empowers Magento to seamlessly use these multiple engines.

---

### Common JDBC Support

Predictiveworks. supports JDBC databases as data sources for data mining & predictive analytics, and thus supports Magento's MySQL database. To use Predictiveworks. 
with Magento, the following steps have to be performed:

![Register Train Get](https://raw.github.com/skrusche63/spark-magento/master/images/register_train_get_640.png)

#### 1. Register

Specify which fields of a database table or view form a transaction or sequence database for market basket analysis, or even a feature set to determine 
outliers or predict purchase decisions. Use the REST API to register the respective field descriptions.

#### 2. Train

Use the REST API to start a certain data mining or predictive modeling task.

#### 3. Get

Use the REST API to retrieve mining & modeling results, make decision, or request predictions and recommendations.

---

### Specific Magento Support

The aim of this project is to ease the use of Predictiveworks. by eliminating the need to specify which tables form a certain transaction, sequence or other 
data source. Registration of field descriptions is no longer necessary and mining & predictive tasks can directly be initiated. 
