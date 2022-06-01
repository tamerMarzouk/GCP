# GCP
What does Google Cloud Platform architect exam test?
GCP exam tests your ability to perfom high-level design and  architecture tasks related to:
1. Designing applications.
2. Planning migrations.
3. Ensuring feasibility of proposed designs.
4. Building and deploying code.
5. Managing data lifecycles.

You will use a mix of compute, storage, networking and other specialized services.
Your design must satisfy both business and technical requirements.
if you find a question that seems to have two correct answers, review the business requirements, there is likely a business requirement that will make one answer a better choice.
You will be tested on how to plan the execution of work required to implement a cloud solution.
Migration to the cloud  are often done in stages. For example, low risk migration tasks like setting up a test environment in the cloud before moving production workloads to GCP.
Sometimes the business and technical requirements may leave you open to proposing two or more different solutions. In these cases, consider the feasiblity of the implementation, will it scalable and reliable? 
if you depend on a third party service that might go down, if that happen, what is the impact on your workflow.
Should you plan to buffer work in a cloud pub/sub queue rather than sending it directly to the third-party service?
You should also consider costs and optimizations but ONLY after you have a technically viable solution that meets business requirements.
"Premature optimization is the root of all evil" Donald Knuth. The same can be said for architecture as well, meet technical requirements before trying to optimize.

Architects should be familiar with the software development life cycle and agile practices.
Blue/Green Deployments: when applying new deployment in production a copy of production Green (new environment) is used to receive production traffic gradually from production Blue (existing production environment). Then finally Green deployment would be handling full production traffic.This allows testing on production where the QA environment might not provide the exact situations.
