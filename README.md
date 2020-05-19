# Running a .Net Core Web API Service on Minikube

**Prerequisite**

* Linux machine with Minikube ([Install Minikube](https://github.com/salman-mukhtar/setting-up-kubernetes-environment/blob/master/README.md)
* Visual studio code
* Docker
* Kubectl

**Setting up .Net Core Web API**

We can start with a .net core web api as an example. The service application will run on Docker. To create it, we can proceed with the terminal command below.

```
dotnet new webapi -o WeatherAPI
```
This will create a project with necessory file. Run the api by typing following on terminal.

```
dotnet run
```

Weather API will return random weather forcasting as shown below.

| ![images/api-result.png](images/api-result.png) |
| ------------------------------------------------------------------- |

