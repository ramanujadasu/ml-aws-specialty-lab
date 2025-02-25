# AWS ML Specialty

This repo includes various jupyter notbooks, notes from courses, white papers that helped me pass the [AWS ML Specialty certification](https://aws.amazon.com/certification/certified-machine-learning-specialty/) in 2020. It is not intended to list every resource that exists out there but should help some of my fellow associates to get started with some good documentation.


I personally passed that exam on 11/10/2020 with score of 922 / 1000 or 92.2%. The passing score is 75%.
I found the exam quite hard and I am glad I invested time (roughly 3 months) to refresh and/or learn on various topics in modeling, operations, monitoring, security and data engineering/analysis.

![ml-specialty-image](images/aws-ml-specialty-badge.png)

### ML Specialty certification overview:  
*"The AWS Certified Machine Learning - Specialty certification is intended for individuals who perform a development or data science role. It validates a candidate's ability to design, implement, deploy, and maintain machine learning (ML) solutions for given business problems."*

Topics covered during the exam:
1. **Data Engineering (20%)**: S3 (and VPC Endpoint Gateway), Kinesis (Streams, FireHose, Data Analytics, Video), Glue (Data Catalog and Crawler), Athena, AWS Data Stores (Redshift, RDS/Aurora, DynamoDB, ElasticSearch, ElastiCache), AWS Data Pipelines, AWS Batch, AWS DMS, AWS Step Functions
2. **Exploratory Data Analysis (24%)**: Data Types and Distribution, Time Series, Amazon Athena, Quicksight, Ground Truth, EMR, Spark, Dat binning, transforming, encoding, scaling and shuffling, Dealing with Missing data, outliers, unbalanced data, outliers,  
3. **Modeling (36%)**: CNN, RNN, Tuning neural networks, Regularization, Gradient, L1 and L2 regularization, Confusion matrix (Precision, Recall, F1, AUC), Ensemble methods (Bagging and Boosting), Amazon Sagemaker, Amazon Algorithms (Linear Learner, XGBoost, Seq2Seq, BlazingText, DeepAR, Object2Vec, ObjectDetection, Image Classification, Semantic Segmentation, RCF, LDA, KNN, K-Means, PCA, Factorization Machine), Amazon AI Services (Comprehend, Translate, Transcribe, Polly, Rekognition, Forecast, Lex, ...)
4. **ML Implementations and Operations (20%)**: SageMaker Production Variants, Neo, IoT Greengrass, Encryption at Rest and in Transit, VPC, IAM, Logging, Monitoring, Instance Types and Spot Instances, Elasstic Inference, Auto-Scaling, Availability Zones, Inference Pipelines, ...

#### Additional Info about the exam
Cost; $300
180 mn long (3 hours) and ~65 questions
 - multiple choice
 - multiple response

Notes:
- No partial credit for questions (if we get 2 or 3 right out of 5, no credit)
- Can mark questions an g back to them
- No points for unanswered
- Scores: between 100 and 1000
- Minimum passing score: 750
- Scaled scoring models are used

![4domains](images/ml-specialty-4-domains.png)



### 1. Course and lab

#### 1.1 AWS SageMaker Notebooks
I have tried many SageMaker notebooks in my personal account to really get a good feel for the various algorithms and modeling techniques.
You can see the list of Sagemaker repos in this other repo: [aws-sagemaker-notebooks](https://github.com/FabG/aws-sagemaker-notebooks)


#### 1.2 CloudGuru Course
The [Cloud Guru - AWS Certified Machine Learning - Specialty 2020 Course](https://learn.acloud.guru/course/aws-certified-machine-learning-specialty/dashboard) includes over 17 hours of videos, 79 lessons, 8 course quizzes and 1 practice exam. There are also some great labs to get hands on.

Below are some of my notes/snapshots from the course:
 - [1-data-collection](cloudguru-course/1-data-collection/cloudguru-1-data-collection.pdf)
 - [2-streaming-data-collection](cloudguru-course/2-streaming-data-collection/cloudguru-2-streaming-data-collection.pdf)
 - [3-data-preparation](cloudguru-course/3-data-preparation/cloudguru-3-data-preparation.pdf)
 - [4-data-visualization](cloudguru-course/4-data-visualization/cloudguru-4-data-analysis-visualization.pdf)
 - [5-modeling](cloudguru-course/5-modeling/cloudguru-5-modeling.pdf)
 - [6-algorithms](cloudguru-course/6-algorithms/cloudguru-6-algorithms.pdf)
 - [7-evaluation-optimization](cloudguru-course/7-evaluation-optimization/cloudguru-7-evaluation-and-optimization.pdf)
 - [course completion](course-completion/cloudguru-ml-specialty-course-completion-10192020.png)

#####  CloudGuru Lab Work
 - [Data Preparation](3-data-preparation/readme.md)
 - [Data Visualization](4-data-visualization/readme.md)
 - [Modeling](5-modeling/readme.md)
 - [Algorithms](6-algorithms/readme.md)
 - [Evaluation and Optimization](7-evaluation-optimization/readme.md)


#### 1.3 Udemy Course
The [Udemy AWS Certified Machine Learning Specialty 2020 - Hands On! Course](https://www.udemy.com/course/aws-machine-learning/learn/lecture/16368832#overview) includes over 9 hours of videos, 114 lessons and 1 practice exam. The full list of course slides is available [here](udemy-course/udemy-ml-specialty-course-all-slides.pdf).

Below are some of my notes/snapshots from the course:
 - [1-data-engineering (part1)](udemy-course/udemy-ml-specialty-course-1-data-engineering-part1.pdf)
 - [1-data-engineering (part2)](udemy-course/udemy-ml-specialty-course-1-data-engineering-part2.pdf)
 Below are some of my notes/snapshots from the course:
 - [1-data-engineering (part1)](udemy-course/udemy-ml-specialty-course-1-data-engineering-part1.pdf)
 - [1-data-engineering (part2)](udemy-course/udemy-ml-specialty-course-1-data-engineering-part2.pdf)
 - [2-exploratory-data-analysis)](udemy-course/udemy-ml-specialty-course-2-exploratory-data-analysis.pdf)
 - [2-exploratory-data-analysis (lab))](udemy-course/udemy-ml-specialty-course-2-exploratory-data-analysis-lab.pdf)
 - [3-modeling-concepts](udemy-course/udemy-ml-specialty-course-3-modeling-concepts.pdf)
 - [3-modeling-ml-services (part1)](udemy-course/udemy-ml-specialty-course-3-ml-services-part1.pdf)
 - [3-modeling-ml-services (part2)](udemy-course/udemy-ml-specialty-course-3-ml-services-part2.pdf)
 - [3-modeling-ai-services](udemy-course/udemy-ml-specialty-course-3-ai-services.pdf)
 - [3-modeling-lab](udemy-course/udemy-ml-specialty-course-3-modeling-lab.pdf)
 - [4-ml-implementation-operation](udemy-course/udemy-ml-specialty-course-4-ml-implementation-operation.pdf)
 - [4-ml-implementation-operation (lab)](udemy-course/udemy-ml-specialty-course-4-ml-implementation-operation.pdf)
 - [exam tips](udemy-course/udemy-ml-specialty-course-exam-tips.pdf)
 - [warmup test - quick assessment](udemy-course/udemy-ml-specialty-course-warmup-test-quick-assessment.pdf)
 - [course completion](course-completion/udemy-aws-ml-specialty-course-completion-10252020.jpg)

#### 1.4 WhizLabs courses
The [Whizlabs Course (and tests)](https://www.whizlabs.com/learn/course/aws-mls-practice-tests) is a great course, with a lot of examples/labs via Jupyter notebook to grasp the materials taught.
I also found the Tests a lot harder than Udemy and CloudGuru and would recommend passing these tests last.

Below are some of my notes/snapshots from the course:
 - [1-data-engineering (part1)](whizlabs-course/whizlabs-course-1-data-engineering-part1.pdf)
 - [1-data-engineering (part2)](whizlabs-course/whizlabs-course-1-data-engineering-part2.pdf)
 - [2-data-analysis (part1)](whizlabs-course/whizlabs-course-2-data-analysis-part1.pdf)
 - [2-data-analysis (part2)](whizlabs-course/whizlabs-course-2-data-analysis-part2.pdf)
 - [2-data-analysis (part3)](whizlabs-course/whizlabs-course-2-data-analysis-part3.pdf)
 - [3-modeling (part1)](whizlabs-course/whizlabs-course-3-modeling-part1.pdf)
  - [lab - xgboost notebook](whizlabs-course/lab/train-xgboost-lab.ipynb)
 - [3-modeling (part2)](whizlabs-course/whizlabs-course-3-modeling-part2.pdf)
  - [lab - hyperparameter tuning notebook](whizlabs-course/lab/perform-automatic-model-tuning.ipynb)
  - [lab - train with tuned parameters notebook](whizlabs-course/lab/train-with-tuned-hyperparameters.ipynb)
 - [4-algorithms (part 1)](whizlabs-course/whizlabs-course-4-algorithms-part1.pdf)
  - [lab - regression (LinearLearner) notebook](whizlabs-course/lab/regression-lab/linearlearner-regression.ipynb)
  - [lab - clustering (K-Means) notebook](whizlabs-course/lab/clustering-lab/clustering-kmeans.ipynb)
 - [4-algorithms (part 2)](whizlabs-course/whizlabs-course-4-algorithms-part2.pdf)
  - [lab - classification (XGboost) notebook](whizlabs-course/lab/classification-lab/classification-xgboost.ipynb)
 - [4-algorithms (part 3)](whizlabs-course/whizlabs-course-4-algorithms-part3.pdf)
  - [lab - text analysis (BlazingText) notebook](whizlabs-course/lab/textanalysis-lab/blazingtext-fasttext.ipynb)
 - [5-implementation-operations](whizlabs-course/whizlabs-course-5-implementation-and-operations.pdf)


#### 1.5 AWS Course
- [Linear and Logistic Regression](aws-course/aws-course-linear-logistic-regression.pdf)
 - [aws video](https://www.aws.training/Details/eLearning?id=26599)


- [The Elements of Data Science - part 1](aws-course/aws-course-elements-data-science-part1.pdf)
- [The Elements of Data Science - part 2](aws-course/aws-course-elements-data-science-part2.pdf)
- [The Elements of Data Science - part 3](aws-course/aws-course-elements-data-science-part3.pdf)
- [The Elements of Data Science - part 4](aws-course/aws-course-elements-data-science-part4.pdf)


#### 1.6 AWS White Papers
- [Deep Learning on AWS - pdf extract](aws-whitepaper/aws-white-paper-deep-learning.pdf)
 - [Full white paper](https://d1.awsstatic.com/whitepapers/Deep_Learning_on_AWS.pdf?did=wp_card&trk=wp_card)
- [AWS White Paper - Machine Learning Foundations - pdf extract](aws-whitepaper/aws-white-paper-machine-learning-foundations.pdf)
 - [Full white paper](https://d1.awsstatic.com/whitepapers/machine-learning-foundations.pdf)
- [AWS White Paper - Power Machine Learning at Scale - pdf extract](aws-whitepaper/aws-white-paper-power-machine-learning-at-scale.pdf)
 - [Full white paper](https://d1.awsstatic.com/whitepapers/aws-power-ml-at-scale.pdf?did=wp_card&trk=wp_card)
- [AWS White Paper - Streaming Data Solutions on AWS with Amazon Kinesis - pdf extract](aws-whitepaper/aws-white-paper-streaming-data-solutions-kinesis.pdf)
 - [Full white paper](https://d0.awsstatic.com/whitepapers/whitepaper-streaming-data-solutions-on-aws-with-amazon-kinesis.pdf)
)


#### 1.7 AWS FAQ

- [AWS FAQ - pdf extract](aws-faq/aws-faq.pdf)
 - [Full FAQ Link](https://aws.amazon.com/sagemaker/faqs/)

#### 1.8 AWS Machine Learning Cheat Sheet
 - [My Cheat Sheet for AWS Machine Learning](aws-notes/aws-machine-learning-cheat-sheet-112020.pdf)



### 2. Practice Exams

#### 2.1 CloudGuru Practice Exam
passed on 10/18/2020: scored 75% and used 1h35 from the 3 hours to cover the 65 questions
- [cloudguru practice exam - part 1](exam-readiness/cloudguru-exam-readiness/cloudguru-practice-exam-part-1.pdf)
- [cloudguru practice exam - part 2](exam-readiness/cloudguru-exam-readiness/cloudguru-practice-exam-part-2.pdf)
- [cloudguru practice exam - review](exam-readiness/cloudguru-exam-readiness/cloudguru-practice-exam-review.pdf)
- [cloudguru practice exam 2nd attempt ](exam-readiness/cloudguru-exam-readiness/cloudguru-practice-exam2-11102020.pdf)

#### 2.2 Udemy Practice Exam
 - [udemy practice exam 2](exam-readiness/whizlabs-exam-readiness/udemy-exam-readiness/udemy-exam-practice2-11062020.pdf)
 - [udemy practice exam 3](exam-readiness/whizlabs-exam-readiness/udemy-exam-readiness/udemy-exam-practice3-11072020.pdf)

#### 2.3 Whizlabs Practice Exam
 - [whizlabs practice exam 1](exam-readiness/whizlabs-exam-readiness/whizlabs-practice-test-1-11112020.pdf)
 - [whizlabs practice exam 2](exam-readiness/whizlabs-exam-readiness/whizlabs-practice-test-2-11112020.pdf)


#### 2.4 TestPrep Practice Exam
  - [testprep practice exam 1](exam-readiness/testprep-exam-readiness/testprep-exam-practice1-11092020.pdf)
  - [testprep practice exam 2](exam-readiness/testprep-exam-readiness/testprep-exam-practice2-11102020.pdf)


#### 2.5 AWS Practice Exam
- [aws sample exam questions](exam-readiness/aws-exam-readiness/aws-ml-sample-exam-questions-oct2020.pdf)
- [aws exam readiness - certified ml specialty](exam-readiness/aws-exam-readiness/aws-exam-readiness-certified-ml-specialty.pdf)
- [aws exam readiness - domain1 - data engineering -](exam-readiness/aws-exam-readiness/aws-exam-readiness-domain1-data-engineering.pdf)
- [aws exam readiness - domain2 - exploratory data analysis](exam-readiness/aws-exam-readiness/aws-exam-readiness-domain2-exploratory-data-analysis.pdf)
- [aws exam readiness - domain3 - modeling](exam-readiness/aws-exam-readiness/aws-exam-readiness-domain3-modeling.pdf)
- [aws exam readiness - domain4 - ml implementation operations.pdf](exam-readiness/aws-exam-readiness/aws-exam-readiness-domain4-mlimplementation-operations.pdf)
- [aws exam readiness - study questions](exam-readiness/aws-exam-readiness/aws-exam-readiness-study-questions.pdf)
- [aws exam readiness - study results](exam-readiness/aws-exam-readiness/aws-exam-readiness-study-questions-results.pdf)
- [aws practice exam - 20 questions](exam-readiness/aws-exam-readiness/aws-practice-exam-20-questions-11062020.pdf)

#### 2.6 Misc
- [additional exam notes](exam-readiness/additional-notes-practice-exam.pdf)
- [my aws ml specialty certification](certificates/aws-certified-machine-learning-specialty-fabrice-certificate-11222020.pdf) and [score](certificates/aws-certified-machine-learning-specialty-fabrice-score-11222020.pdf)


### Resources
Great set of courses from Andrew Ng in Coursera that I highly recommend:
 - [Machine Learning - Andrew Ng](https://www.coursera.org/learn/machine-learning)
 - [Deep Learning Specialization (5 course) - Andrew Ng](https://www.coursera.org/specializations/deep-learning)

Article extracts and notes (pdf):
 - [Creating a Data Schema for Amazon ML](aws-articles/creating-data-schema-amazon-ml.pdf)
 - [Securing, Protecting and Managing Data](aws-articles/securing-protecting-managing-data.pdf)


Other:
 - [A Cloud Guru - ML Specialty Course](https://acloud.guru/learn/aws-certified-machine-learning-specialty)
 - [A Cloud guru AWS Certification prep](https://acloud.guru/learn/aws-certification-preparation)
 - [A Cloud Guru Labs - Github](https://github.com/ACloudGuru-Resources/Course_AWS_Certified_Machine_Learning)
 - [AWS Training and Certification](https://www.aws.training/) - this is where you can pass the Exam Readiness course and quiz
 - [Amazon SageMaker Developer guide](https://docs.aws.amazon.com/sagemaker/latest/dg/sagemaker-dg.pdf)
 - [Whizlabs course and several solid practice exams](https://www.whizlabs.com/aws-certified-machine-learning-specialty/)
