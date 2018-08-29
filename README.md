## Welcome to Project Continuum

We are a group at Microsoft working on exciting Big Data problems. We will be
updating this page with more information about the details of our work -
please keep an eye on this space. If you are interested in joining our team,
email me.

## Publications

### Chi: A Scalable and Programmable Control Plane for Distributed Stream Processing Systems

Stream-processing workloads and modern shared cluster environments exhibit
high variability and unpredictability. Combined with the large parameter space
and the diverse set of user SLOs, this makes modern streaming systems very
challenging to statically configure and tune. To address these issues, in this
paper we investigate a novel control-plane design, Chi, which supports
continuous monitoring and feedback, and enables dynamic re-configuration. Chi
leverages the key insight of embedding control-plane messages in the data-
plane channels to achieve a low-latency and flexible control plane for stream-
processing systems.

Chi introduces a new reactive programming model and design mechanisms to
asynchronously execute control policies, thus avoiding global synchronization.
We show how this allows us to easily implement a wide spectrum of control
policies targeting different use cases observed in production. Large-scale
experiments using production workloads from a popular cloud provider
demonstrate the flexibility and efficiency of our approach.

Read our [paper](http://www.vldb.org/pvldb/vol11/p1303-mai.pdf) for more details.