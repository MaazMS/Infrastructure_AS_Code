### Architecture & Concepts

1. Pulumi is a modern infrastructure as code platform.  
1. It leverages existing programming languages—TypeScript, JavaScript, Python, Go, and .NET and their native ecosystem   
   to interact with cloud resources through the Pulumi SDK.  
1. It provides cloud resources provisioning, updating, and managing cloud infrastructure.     
````bash
infrastructure : 
The basic physical and organizational structures and facilities (e.g. buildings, roads, power supplies) needed for    
the operation of a society or enterprise.
```` 
![](https://www.pulumi.com/images/docs/pulumi-programming-model-diagram.svg)       
## Bit more about pulumi    
1. Pulumi programs, written in general-purpose programming languages, describe how your cloud infrastructure should be composed(written).    
1. To declare new infrastructure in your program, you allocate resource objects whose properties correspond to the desired state of your infrastructure.     
1. These properties are also used between resources to handle any necessary dependencies and can be exported outside of the stack, if needed.  