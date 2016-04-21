# Master-thesis
Existing frameworks for the provisioning and deployment of multi-cloud applications usually rely on declarative (using application topology models) or imperative (using deployment plans) deployment approaches. Declarative approaches are considered to be easy to use, but not very flexible because the deployment logic is predefined, and users can not change it according to their needs. Imperative approaches allow explicit definition of every deployment action but are considered to be hard to write and maintain. Besides, imperative approaches usually rely on generic workflow definition languages to describe deployment plans. These languages are often too powerful and complex to be used in the deployment domain.

In this work, we combine both approaches by generating deployment plans from the application topology models and introduce a domain-specific language for the plans definition and manipulation. This allows application owners to deploy applications without much effort while having the ability to tune generated plans according to their needs. Moreover, we developed a deployment engine that shows the deployment process in real time. It helps developers to analyze, optimize and debug the deployment process.

Finally, most applications have to be updated many times during their life-cycle. To do this efficiently (without redeploying the whole application or writing additional deployment plans) we exploit the models@runtime approach in combination with the plan generation mechanism. This combination reduces the complexity of the application updates and application delivery times by enabling seamless reconfigurations at run time, that only impact parts of the system that are going to be changed.

# Reading version
https://www.overleaf.com/read/vgnkppdmthmq
