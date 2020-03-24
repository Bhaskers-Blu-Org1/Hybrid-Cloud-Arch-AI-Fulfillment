# 3 Ways our Hybrid Cloud Architecture Makes it Easy to Add AI to Fulfillment

In previous blogs, we introduced [IBM Sterling Fulfillment Optimizer with Watson](https://community.ibm.com/community/user/supplychain/blogs/anum-valliani1/2019/08/28/take-the-next-step-add-ai-to-ibm-order-management?CommunityKey=dd15f3ff-b6c6-4b0a-8248-169fc0c994ed&tab=recentcommunityblogsdashboard) and [the Results Explainer's]() self-service capability. Now, we’re going to look behind the scenes at our hybrid cloud architecture and its impact on integration. Whether you’ve deployed Sterling Order Management software (OMS) on-premise or in the cloud, our hybrid cloud approach allows you to ramp up quickly on our cloud-based Sterling Fulfillment Optimizer.

Here are three ways our architecture streamlines deployment and administration so you can start solving complex, multi-dimensional fulfillment challenges faster and easier:


<ol>
<li>Our hybrid cloud architecture accelerates the onboarding process and alleviates any scalability concerns so you can get up and running in just a few days, not weeks. Simply complete our questionnaire to provide us with a sense of sizing (for example, how many order lines per hour) and we can provision accordingly with little back and forth. The bulk of our services are containerized so we have a ready-made image. In effect, Sterling Fulfillment Optimizer is agnostic of size/volume and can scale to accommodate the data flow and service needs of mega users and smaller companies as well. Faster onboarding for you, means you can start enhancing your customers’ experiences faster as well.<br/>
&nbsp

Looking ahead, as we certify our containerized services on IBM Kubernetes, the provisioning aspect of the onboarding process can happen instantly. Expect to see even faster onboarding sometime next year.</li><br/><br/>

<li><u>Data feeds:</u> There are two ways to send your OMS data to Sterling Fulfillment Optimizer, manually in batch mode using a file adapter or automated via an events trigger using Event Streams, based on Apache Kafka. As explained in our initial blog, Sterling Fulfillment Optimizer continuously captures sales and inventory information for every SKU and node combination available, figures out the potential risk for stockouts and markdowns, and optimizes fulfillment to meet your business objectives. To take full advantage of this real-time analysis capability, integration through Kafka is recommended because it is event based. As soon as any updates happen, data automatically flows to Sterling Fulfillment Optimizer. This data is used to calculate predictions which is later used to determine the best option to fulfill an order and maximize profits. Using Event Streams to send data allows you to capture more business value from the solution’s decision-making abilities.</li><br/><br/>
&nbsp &nbsp &nbsp

<li>Previously, when users uploaded a file manually and if data ingestion failed for some reason, IBM would notify the customer manually. The entire process – from notification to response and resolution – could take hours or days. Our hybrid cloud architecture accelerates the process with a new microservice that sends failure and success notifications automatically, so there is no lag time. You have peace of mind that data ingestion is running smoothly, and in the event of a failure you are notified instantly and can take corrective actions faster.</li>
</ol>


### Want to know more?

I hope you now have a better understanding of our hybrid cloud approach and the added functionality it provides when you integrate Sterling Fulfillment Optimizer with Sterling OMS.

To learn more about our integration, visit our [Knowledge Center](https://www.ibm.com/support/knowledgecenter/en/SSZMC6/com.ibm.help.orderoptimizer.doc/Integration/IntegrationwithOM.html).

Have specific questions about integration within your environment? Post them to the [forum](https://community.ibm.com/community/user/supplychain/communities/community-home/digestviewer?communitykey=dd15f3ff-b6c6-4b0a-8248-169fc0c994ed&tab=digestviewer) and we’ll address them as quickly as possible.
