.

> ## AWS Cloud Computing Mock Exam 1

.

**Let's gather all the questions and correct answers from the screenshots you provided:**



> Question 1:

Original:

A company uses Amazon WorkSpaces. Which task is the responsibility of AWS, according to the AWS shared responsibility model?


Arabic Translation:
تستخدم الشركة Amazon WorkSpaces. ما هي المهمة التي تقع على عاتق AWS وفقًا لنموذج المسؤولية المشتركة في AWS؟

Correct Answer:

B. Ensure the environmental safety and security of the AWS infrastructure that hosts WorkSpaces.


  Explanation:

في نموذج المسؤولية المشتركة لـ AWS، تكون AWS مسؤولة عن أمان البنية التحتية المادية، مثل مراكز البيانات وأمان المعدات والشبكات، بينما تقع على عاتق العملاء مسؤولية أمان البيانات والتطبيقات وإعدادات المستخدم. في هذا السياق، AWS مسؤولة عن ضمان سلامة وأمن البيئة التي تستضيف Amazon WorkSpaces.


==============================================


> Question 2:

Original:

A security engineer wants a single-tenant AWS solution to create, control, and manage their own cryptographic keys to meet regulatory compliance requirements for data security. Which AWS service should the engineer use?


Arabic Translation:

يريد مهندس الأمان حلاً من AWS للمستأجر الفردي لإنشاء وإدارة مفاتيح التشفير الخاصة به للامتثال لمتطلبات الأمان التنظيمية. أي خدمة من AWS يجب أن يستخدمها المهندس؟


Correct Answer:

A. AWS Key Management Service (AWS KMS)

  Explanation:
تتيح خدمة AWS KMS للمستخدمين إنشاء وإدارة مفاتيح التشفير الخاصة بهم وإدارتها بطريقة تلبي المتطلبات التنظيمية لحماية البيانات. تساعد هذه الخدمة في ضمان إدارة وتحكم دقيقين في مفاتيح التشفير.




==============================================


> Question 3:


Original:

A company is designing an identity access management solution for an application. The company wants users to be able to use their social media, email, or online shopping accounts to access the application. Which AWS service provides this functionality?

Arabic Translation:
تصمم الشركة حلاً لإدارة الوصول إلى الهوية لتطبيق ما. ترغب الشركة في أن يتمكن المستخدمون من استخدام حسابات وسائل التواصل الاجتماعي أو البريد الإلكتروني أو التسوق عبر الإنترنت للوصول إلى التطبيق. أي خدمة من AWS توفر هذه الوظيفة؟


Correct Answer:

C. Amazon Cognito


Explanation:
توفر خدمة Amazon Cognito إمكانية تسجيل دخول المستخدمين باستخدام حسابات وسائل التواصل الاجتماعي أو البريد الإلكتروني أو التسوق عبر الإنترنت. هذه الخدمة مثالية لتبسيط عملية إدارة الهوية والوصول.



==============================================


> Question 4:

Original:

Which option is the default pricing model for Amazon EC2 instances?

Arabic Translation:
ما هو نموذج التسعير الافتراضي لحالات Amazon EC2؟

Correct Answer:

A. On-Demand Instances

Explanation:
نموذج التسعير الافتراضي لحالات Amazon EC2 هو "On-Demand Instances"، حيث يدفع المستخدمون فقط مقابل السعة المستخدمة في الحوسبة بالساعة أو الثانية دون الحاجة إلى الالتزام طويل الأمد.



==============================================


> Question 5:

Original:


Which AWS service gives users the ability to combine existing accounts into a centrally managed hierarchy?


Arabic Translation:
أي خدمة من AWS تمنح المستخدمين القدرة على دمج الحسابات الحالية في تسلسل هرمي مُدار مركزيًا؟

Correct Answer:

A. AWS Organizations


Explanation:
تسمح خدمة AWS Organizations للمستخدمين بإدارة حسابات AWS متعددة تحت تسلسل هرمي مركزي، مما يسهل إدارة الأذونات والسياسات والأمان عبر عدة حسابات.



==============================================


> Question 6:

Original:


Who enables encryption of data at rest for Amazon Elastic Block Store (Amazon EBS)?


Arabic Translation:
من يمكّن تشفير البيانات الثابتة لـ Amazon Elastic Block Store (Amazon EBS)؟

Correct Answer:


C. AWS Key Management Service (AWS KMS)


Explanation:
توفر AWS KMS إمكانية إدارة المفاتيح التي تستخدم لتشفير البيانات الثابتة في Amazon EBS، ما يوفر أمانًا إضافيًا للبيانات المخزنة.



==============================================


> Question 7:

Original:


Which AWS design principle emphasizes the reduction of interdependencies between components of an application?


Arabic Translation:
أي مبدأ تصميم من AWS يؤكد على تقليل الاعتماد المتبادل بين مكونات التطبيق؟

Correct Answer:

B. Loose coupling


Explanation:
مبدأ "Loose coupling" يشير إلى تقليل الاعتماد المتبادل بين مكونات التطبيق، ما يتيح تطويرًا وصيانة أسهل وزيادة في المرونة والتوسع.



==============================================


> Question 8:

Original:

A company is developing an application that uses multiple AWS services. The application needs to use temporary, limited-privilege credentials for authentication with other AWS APIs. Which AWS service or feature should the company use to meet these authentication requirements?


Arabic Translation:

تقوم شركة بتطوير تطبيق يستخدم خدمات AWS متعددة. يحتاج التطبيق إلى استخدام بيانات اعتماد مؤقتة ومحدودة الامتياز للمصادقة مع واجهات برمجة التطبيقات الأخرى من AWS. أي خدمة أو ميزة من AWS يجب أن تستخدمها الشركة لتلبية متطلبات المصادقة هذه؟

Correct Answer:

C. AWS Security Token Service (AWS STS)

Explanation:
يوفر AWS STS بيانات اعتماد مؤقتة ومحدودة الامتياز، مما يسهل المصادقة مع خدمات متعددة في AWS، وهو مثالي للتطبيقات التي تتطلب أذونات مؤقتة.



==============================================


> Question 9:

Original:


Which AWS service or feature offers HTTP attack protection to users running public-facing web applications?


Arabic Translation:
أي خدمة أو ميزة من AWS تقدم حماية من هجمات HTTP للمستخدمين الذين يديرون تطبيقات الويب العامة؟

Correct Answer:

C. AWS WAF

  Explanation:

AWS WAF (Web Application Firewall) يوفر حماية لتطبيقات الويب العامة من الهجمات التي تستهدف بروتوكولات HTTP وHTTPS، مما يحمي تطبيقات المستخدمين من أنواع متعددة من التهديدات.



==============================================


> Question 10:

Original:

A company wants to troubleshoot and debug a serverless application that is deployed in the AWS Cloud. Which AWS service should the company use to achieve this goal?


Arabic Translation:
تريد شركة استكشاف الأخطاء وإصلاحها وتصحيح تطبيق بدون خادم يتم نشره في AWS Cloud. أي خدمة من AWS يجب أن تستخدمها الشركة لتحقيق هذا الهدف؟


Correct Answer:

C. AWS X-Ray


Explanation:


AWS X-Ray يساعد في تتبع طلبات المستخدم وتحليل الأداء في التطبيقات التي لا تستخدم خوادم (Serverless)، ما يسهل عملية تصحيح الأخطاء وتحسين الأداء.



==============================================


>  Question 11:


Original:


A company needs to connect multiple VPCs and on-premises networks through a single network connection to the AWS Cloud. Which solution meets this requirement?



Arabic Translation:

تحتاج الشركة إلى توصيل العديد من شبكات VPC والشبكات المحلية من خلال اتصال شبكة واحد إلى AWS Cloud. أي حل يلبي هذا المتطلب؟

Correct Answer:


A. AWS Transit Gateway




Explanation:



تسمح خدمة AWS Transit Gateway بربط شبكات VPC متعددة والشبكات المحلية عبر اتصال شبكة واحد، مما يبسط إدارة الشبكات والاتصالات بين البيئات المتعددة.



==============================================


> Question 12:



Original:



A company needs to continuously monitor its environment to analyze network and account activity and identify potential security threats. Which AWS service should the company use to meet these requirements?



Arabic Translation:



تحتاج الشركة إلى مراقبة بيئتها بشكل مستمر لتحليل نشاط الشبكة والحسابات وتحديد التهديدات الأمنية المحتملة. أي خدمة من AWS يجب أن تستخدمها الشركة لتلبية هذه المتطلبات؟

Correct Answer:



D. Amazon GuardDuty  واجب الحراسة



Explanation:


Amazon GuardDuty هي خدمة مراقبة مستمرة تهدف إلى تحليل الأنشطة في الشبكة وتحديد التهديدات الأمنية باستخدام التعلم الآلي والذكاء الأمني.




==============================================


> Question 13:


Original:



Which AWS network service or feature allows CIDR block notation when providing an IP address range?




Arabic Translation:


أي خدمة أو ميزة شبكات من AWS تسمح باستخدام ترميز CIDR عند تقديم نطاق عناوين IP؟

Correct Answer



A. Security groups




Explanation:
تتيح Security Groups في AWS إمكانية تحديد نطاقات عناوين IP باستخدام ترميز CIDR لضبط قواعد الوصول والأمان.



==============================================



> Question 14:


Original:



A company is designing workloads in the AWS Cloud. The company wants the workloads to perform their intended function correctly and consistently throughout their lifecycle. Which pillar of the AWS Well-Architected Framework does this goal represent?




Arabic Translation:


تصمم الشركة أحمال العمل في AWS Cloud. تريد الشركة أن تقوم أحمال العمل بأداء وظيفتها المقصودة بشكل صحيح ومتسق طوال دورة حياتها. أي ركيزة من إطار العمل الهندسي الجيد من AWS يمثل هذا الهدف؟



Correct Answer:



C. Reliability  مصداقية



Explanation:
تشير الركيزة "Reliability" إلى ضمان أن الأنظمة تعمل بشكل صحيح ومتسق عبر دورة حياتها مع قدرة على التعافي من الفشل.



==============================================


> Question 15:


Original:



A cloud practitioner needs to apply security rules to a subnet for Amazon EC2 instances. Which AWS service or feature can the cloud practitioner use to meet this requirement?




Arabic Translation:



يحتاج ممارس السحابة إلى تطبيق قواعد الأمان على شبكة فرعية لحالات Amazon EC2. أي خدمة أو ميزة من AWS يمكن أن يستخدمها ممارس السحابة لتلبية هذا المتطلب؟



Correct Answer:



C. Security groups



Explanation:


تستخدم Security Groups لتطبيق قواعد الأمان في AWS على مستوى الشبكة الفرعية لحالات Amazon EC2، مما يسمح بالتحكم في حركة المرور المسموح بها داخل وخارج الشبكة الفرعية.


========================



>  **Question 28:**  
   **Which AWS service provides a scalable data warehouse solution?**  
   **Answer:** D. Amazon Redshift

2. **Question 29:**  
   **Which statement is true regarding pricing for these eight instances?**  
   **Answer:** C. Five instances will be charged as RIs, and three will be charged as regular instances.

3. **Question 30:**  
   **Which task is the company's responsibility, according to the AWS shared responsibility model?**  
   **Answer:** C. Manage database access permissions.

4. **Question 31:**  
   **Which task is the customer's responsibility when managing AWS Lambda functions?**  
   **Answer:** A. Creating versions of Lambda functions.

5. **Question 32:**  
   **Which AWS service is fully managed and allows employees to access applications through a virtual interface?**  
   **Answer:** C. Amazon AppStream 2.0.

6. **Question 33:**  
   **Which AWS service or capability should the company use to automatically adjust compute capacity to meet customer demand?**  
   **Answer:** B. AWS Auto Scaling.

7. **Question 34:**  
   **Which AWS Cloud design principle is being used when implementing AWS CloudTrail?**  
   **Answer:** A. Activate traceability.

8. **Question 35:**  
   **Which AWS service helps manage infrastructure as code in the AWS Cloud?**  
   **Answer:** A. AWS CloudFormation.

9. **Question 36:**  
   **Which activity can companies complete using AWS Organizations?**  
   **Answer:** B. Manage service control policies (SCPs).

10. **Question 37:**  
   **Which task is the responsibility of AWS, according to the AWS shared responsibility model?**  
   **Answer:** A. Patch AWS network devices.

11. **Question 38:**  
   **What is the minimum credential required to allow IT department users to access AWS CLI?**  
   **Answer:** C. IAM user name and password.

12. **Question 39:**  
   **Which encryption type can be used to protect objects at rest in Amazon S3?**  
   **Answer:** B. Server-side encryption with AWS KMS managed keys (SSE-KMS).

13. **Question 40:**  
   **Which of the following is a pillar of the AWS Well-Architected Framework?**  
   **Answer:** B. Performance efficiency.

14. **Question 41:**  
   **Which design principle should the company use to ensure the application remains available if an individual component fails?**  
   **Answer:** D. Loose coupling.

15. **Question 42:**  
   **Which AWS global infrastructure component does Amazon CloudFront use to speed up content delivery?**  
   **Answer:** B. Edge locations.

16. **Question 43:**  
   **Which solution minimizes latency for users around the world using EC2 instances?**  
   **Answer:** C. Use Amazon CloudFront with the EC2 instances configured as the source.

17. **Question 44:**  
   **Which AWS service can serve large amounts of online video content with the lowest possible latency?**  
   **Answer:** B. Amazon S3.

18. **Question 45:**  
   **Which design principle belongs to the reliability pillar of the AWS Well-Architected Framework?**  
   **Answer:** C. Automatically recover from failure.

19. **Question 46:**  
   **Which AWS service should a cloud engineer use to view API calls to AWS services?**  
   **Answer:** B. AWS CloudTrail.

20. **Question 47:**  
   **Which instance purchasing option will meet the requirements most cost-effectively for running a stateless process after business hours?**  
   **Answer:** A. Spot Instances.

21. **Question 48:**  
   **According to the AWS shared responsibility model, which task is the customer's responsibility?**  
   **Answer:** B. Configure logical access controls for resources and protect account credentials.

22. **Question 49:**  
   **Which S3 storage class meets the cost-effectiveness requirement for storing some yearly and some daily accessed data?**  
   **Answer:** D. S3 Intelligent-Tiering.

23. **Question 50:**  
   **What could cause a user to be unable to close an AWS account managed by AWS Organizations?**  
   **Answer:** D. The organizational administrator has used a service control policy (SCP) to limit the root user permissions.

24. **Question 51:**  
   **Which AWS service can determine if newly imported EC2 instances are of the appropriate size and type?**  
   **Answer:** C. AWS Trusted Advisor.

25. **Question 52:**  
   **Which AWS service should a company use to back up 10 TB of data without changing existing workflows?**  
   **Answer:** B. AWS Storage Gateway.

26. **Question 53:**  
   **Which actions represent best practices for using AWS IAM?**  
   **Answer:** D. A & C (Configure a strong password policy & Rotate access keys on a regular basis).

27. **Question 54:**  
   **Which solution will improve the availability of a business-critical Amazon RDS for MySQL DB instance?**  
   **Answer:** C. Convert the DB instance into a Multi-AZ deployment.

28. **Question 55:**  
   **Which AWS service should be used to run a MySQL database that scales easily?**  
   **Answer:** A. Amazon Aurora.

29. **Question 56:**  
   **Which AWS Global Infrastructure component consists of one or more data centers interconnected through low latency links?**  
   **Answer:** A. Availability Zone.

30. **Question 57:**  
   **Which best practice is the company following when migrating an application to AWS and dividing it into microservices?**  
   **Answer:** D. Implement loosely coupled dependencies.

31. **Question 58:**  
   **Which benefit comes from using an AWS managed service?**  
   **Answer:** A. Reduced operational overhead for a company’s IT staff.

32. **Question 59:**  
   **How many Availability Zones should compute resources be provisioned across to achieve high availability?**  
   **Answer:** B. A minimum of two.

33. **Question 60:**  
   **What does the concept of agility mean in AWS Cloud computing?**  
   **Answer:** D. A & C (The speed at which AWS resources are implemented & The ability to experiment quickly).

34. **Question 61:**  
   **Which AWS service or feature can control VPC traffic?**  
   **Answer:** A. Security groups.

35. **Question 62:**  
   **What is the lowest-cost, durable storage option for retaining database backups for immediate retrieval?**  
   **Answer:** A. Amazon S3.

36. **Question 63:**  
   **Which AWS solution provides a scalable data warehouse solution?**  
   **Answer:** D. Amazon Redshift.

37. **Question 64:**  
   **Which are benefits of migrating to the AWS Cloud?**  
   **Answer:** D. A & C (Operational resilience & Business agility).

38. **Question 65:**  
   **Which pillar of the AWS Well-Architected Framework does replacing physical compute servers with serverless services represent?**  
   **Answer:** B. Performance efficiency.

---

This is the summary of questions and their correct answers from the screenshots you shared. Let me know if you need further clarifications!
